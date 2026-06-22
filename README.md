# Chaos Engineering 🔥

Chaos engineering experiments for Kubernetes resilience testing.

## Experiments

| Experiment | Impact | Blast Radius |
|-----------|--------|-------------|
| pod-kill | Pod restart | Single pod |
| network-partition | Traffic loss | Namespace |
| cpu-stress | CPU saturation | Node |
| latency-inject | Delayed responses | Service |

## Run

```bash
kubectl apply -f experiments/pod-kill.yaml
kubectl apply -f experiments/network-partition.yaml
```

## License

Apache 2.0