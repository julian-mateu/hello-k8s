# Hello k8s

A Hello World example on how to deploy a web app (NodeJS + yarn) using Docker, Kubernetes and Skaffold.

## Getting started

### Requirements
* [Docker](https://www.docker.com/)
* [Minikube](https://minikube.sigs.k8s.io/docs/start/)
* [Skaffold](https://skaffold.dev/)

Start the minikube node:
```bash
minikube start
```

### Dev mode

Run skaffold in dev mode:
```sh
skaffold dev
```

Configure the minikube service:
```sh
minikube service hello-world-node-port
```