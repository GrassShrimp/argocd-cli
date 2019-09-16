# argocd-cli
[Argo CD](https://argoproj.github.io/argo-cd/) command line tool
## Getting Started

### Prerequisites
* [docker](https://docs.docker.com/install/)

### Installation
pull lastest docker image
```
$ docker pull grassshrimp/argocd-cli
```

### Usage
show help message
```
$ docker run --rm grassshrimp/argocd-cli
```
login argo cd service
```
$ docker run --rm grassshrimp/argocd-cli login <ARGOCD_SERVER>
```