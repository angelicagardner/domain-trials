Suggestions:
1. Manually instrument go service with OTel SDK (spans + metrics), export to local Jaeger/Prometheus via Docker compose
2. run OBI "OpenTelemetry eBPF Instrumentation" against same service with zero code changes and compar
3. Implement basic tail-based sampler (keep all error traces, sample X% of the rest)
