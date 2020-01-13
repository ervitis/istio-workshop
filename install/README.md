# Install

## Requirement

Download vendor material running:

```bash
$ pwd
istio-workshop/install
$ furyctl install
```

## Content

Contains three kustomize projects:

- [requirements](./requirements): Installs Prometheus Operator and Required pre-installation Istio Resources
- [istio](./istio): Install Istio (near full featured)
- [Observability](./observability): Install Istio telemetry + Kiali

