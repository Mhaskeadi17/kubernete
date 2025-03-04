# Microservices Deployment on Kubernetes

## Steps to Deploy
1. Set up a Kubernetes cluster.
2. Containerize each microservice using Docker.
3. Create Kubernetes YAML files for deployments and services.
4. Deploy the microservices using `kubectl apply`.

## YAML Configuration Files
- `microservice1-deployment.yaml`
- `microservice1-service.yaml`

## Commands
- To deploy:
  ```bash
  kubectl apply -f microservice1-deployment.yaml
  kubectl apply -f microservice1-service.yaml
