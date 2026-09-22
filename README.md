# Customer Service

DevOps CI/CD assignment for the Pensionat booking system.

## G Requirements
- **Repository:** Personal repo on GitHub (`stoilsteve-hub/customer-service`).
- **CI:** GitHub Actions triggers on push to `main`.
- **Tests:** Automated unit tests execute and pass in the pipeline.
- **Deployment & CD:** Deployed on Render with automatic deploy on push to `main`:  
  https://customer-service-wh4q.onrender.com/api/customers

## VG Requirements
- **Secrets & Security:** Docker Hub credentials stored in GitHub Secrets. No secrets or `.env` files in Git.
- **Environment Variables:** Database and JWT key configured via environment variables in Render (`SPRING_DATASOURCE_URL`, `JWT_KEY`).
- **Docker Hub:** Automated build and push to Docker Hub on merge:  
  `stoilsteve/customer-service:latest`
