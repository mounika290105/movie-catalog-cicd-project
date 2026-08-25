# Movie Picture Pipeline CI/CD Project Submission

For this project, I have successfully implemented both Continuous Integration and Continuous Deployment pipelines for the frontend and backend applications using GitHub Actions. 
- The CI pipelines are configured to trigger correctly on pull requests, successfully running linting, testing, and container builds with appropriate dependencies. 
- The CD pipelines securely manage deployment to an AWS EKS cluster, utilizing Kustomize to update deployment manifests and trigger rolling updates for our services automatically upon merge to main. 
- I have also verified the deployed applications dynamically correctly communicate and function via their ELB endpoints as documented below.

## Frontend Deployment
The frontend is deployed and accessible at:

[Live Frontend URL]([YOUR_DEPLOYMENT_URL])


## Backend Deployment

The backend is deployed and accessible at:

[Live Backend URL]([YOUR_DEPLOYMENT_URL])

