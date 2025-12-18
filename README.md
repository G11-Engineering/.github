# CMS Management System

Cloud-native CMS platform designed for building and managing blog content at scale. The system is built using **6 independent microservices** that communicate through REST APIs and are deployed on Kubernetes with ArgoCD for GitOps-based continuous delivery.

**Core Services:**
- **User Service** - Authentication with WSO2 Asgardeo
- **Content Service** - Post management
- **Category Service** - Categories and tags
- **Comment Service** - Comment system
- **Media Service** - File storage (S3/Local)
- **Frontend Service** - Next.js application

## Repositories

| Repository | Description |
|-----------|-------------|
| [g11-user-service](https://github.com/G11-Engineering/g11-user-service) | User authentication and management |
| [g11-content-service](https://github.com/G11-Engineering/g11-content-service) | Blog post management and publishing |
| [g11-category-service](https://github.com/G11-Engineering/g11-category-service) | Categories and tags |
| [g11-comment-service](https://github.com/G11-Engineering/g11-comment-service) | Comment management |
| [g11-media-service](https://github.com/G11-Engineering/g11-media-service) | Media storage and upload |
| [g11-frontend-service](https://github.com/G11-Engineering/g11-frontend-service) | Next.js frontend with MUI |
| [g11-k8s-charts](https://github.com/G11-Engineering/g11-k8s-charts) | Kubernetes manifests |
| [g11-helm-charts](https://github.com/G11-Engineering/g11-helm-charts) | Helm charts with Istio |
| [docs](https://github.com/G11-Engineering/docs) | Complete documentation |

## Tech Stack

**Frontend:** Next.js 14, Material-UI, TipTap Editor  
**Backend:** Node.js, TypeScript, Express, PostgreSQL, Drizzle ORM
**Security:** WSO2 Asgardeo (OAuth 2.0/OIDC), Trivy scanning  
**DevOps:** Docker, Kubernetes, ArgoCD, Istio, Helm, GitHub Actions  

## Documentation

For detailed documentation, please visit **[docs repository](https://github.com/G11-Engineering/docs)**
---
