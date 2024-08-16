# Full-Stack Application Deployment on Kubernetes

## Overview
This project involves deploying a full-stack application on Kubernetes, including Nginx (frontend), Node.js (backend), and MongoDB (database). 

## File Structure
- **docker**
  - `Dockerfile.nginx`: Dockerfile for the Nginx frontend.
  - `Dockerfile.node`: Dockerfile for the Node.js backend.
- **kubernetes**
  - **persistent-volumes**
    - `pv.yaml`: Persistent Volume configuration.
    - `pvc.yaml`: Persistent Volume Claim configuration.
  - **configmaps**
    - `mongodb-configmap.yaml`: ConfigMap for MongoDB settings.
  - **secrets**
    - `mongodb-secret.yaml`: Secret for MongoDB credentials.
  - **deployments**
    - `mongodb-deployment.yaml`: Deployment for MongoDB.
    - `node-backend-deployment.yaml`: Deployment for Node.js backend.
    - `nginx-frontend-deployment.yaml`: Deployment for Nginx frontend.
  - **services**
    - `mongodb-service.yaml`: Service for MongoDB.
    - `node-backend-service.yaml`: Service for Node.js backend.
    - `nginx-frontend-service.yaml`: Service for Nginx frontend.
- **documentation**
  - `README.md`: This file.
  - `documentation.pdf`: Detailed project documentation.
  - `presentation.mp4`: Presentation video.

## Getting Started

1. **Setup Kubernetes Environment**
   - Start Minikube and configure `kubectl`.

2. **Build and Push Docker Images**
   - Build and push Docker images for Node.js and Nginx.

3. **Apply Kubernetes Manifests**
   - Create Persistent Volumes, ConfigMaps, Secrets, Deployments, and Services.

4. **Manage and Scale Application**
   - Monitor logs, scale deployments, and perform rolling updates.

5. **Testing and Validation**
   - Access the application, verify data persistence, and perform load testing.

## Documentation
The detailed project documentation is available in `documentation/documentation.pdf`. The project presentation can be viewed at `documentation/presentation.mp4`.

## GitHub Repository

