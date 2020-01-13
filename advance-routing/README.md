# Advance Routing

Contains `demo` Istio configuration defining:

- [Load balancing policies](./details-destination-rule-load-balancer.yaml)
- [Rate limitting](./mixer-rule-productpage-ratelimit.yaml)
- [Canary release. V3 for Jason User, V2 otherwise](./virtual-service-reviews-jason-v2-v3.yaml)
- [Traffic mirroring from V3 to V1](./virtual-service-reviews-mirror-v3-in-v2.yaml)
