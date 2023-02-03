# Project
Rotten potatoes - KubeDev

## Technology
* Node JS
* Mongo DB
* Docker
* K3D
* Kubernetes

## Build Project
## Docker
```
docker-compose up -d --build
```

--- 

## Kubernetes
```
k3d cluster create  -p "8080:30000@loadbalancer"
```
### Helm
```
helm install minhaapi ./api-produto/
```