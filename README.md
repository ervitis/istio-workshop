# Istio Workshop

![Istio Kiali](./assets/istio-kiali.png)

This repository contains all needed resources to follow the Istio Workshop.

## Requirements

- Accesible Kubernetes Cluster *(Version > 1.14.x)*.
- SO Packages like: git, curl, jq, awk, grep...
- Kubernetes related packages: kubectl, kustomize, stern...
- SIGHUP package manager: furyctl

## Slides

You can find public slides in the
[following google presentations url](https://docs.google.com/presentation/d/1GgpOnSGY_UUa6dHfZ8k8QbfVitv1-QohjjL7n2RMwNo)

### Content/Agenda

During workshop you will learn basics about Service Mesh, what is Istio, what  components are behind Istio and
you will deploy some demo applications applying traffic policies, applying security rules and so on.

- **Istio Introduction**
    - ***Istio installation***: Content available under [`install`](./install) directory.
- **Deploy microservices**: Content available under [`deploy-microservices`](./deploy-microservices) directory.
- **mTLS *(Mutual TLS):***: Content available under [`mtls`](./mTLS) and [`no-mTLS`](./no-mTLS) directory.
- **Simple routing**: Content available under [`simple-routing`](./simple-routing) directory.
- **Advance routing**: Content available under [`advance-routing`](./advance-routing) directory.
- **Egress**: Content available under [`egress`](./egress) directory.

