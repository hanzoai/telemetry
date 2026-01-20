# Hanzo Telemetry

OpenTelemetry collector for unified observability.

## Overview

Hanzo Telemetry is an OpenTelemetry-compatible collector that receives, processes, and exports telemetry data. Unify traces, metrics, and logs from your AI infrastructure into a single observability pipeline.

## Features

- **Vendor Agnostic**: Export to any backend
- **Protocol Support**: OTLP, Jaeger, Zipkin, Prometheus
- **Processing Pipeline**: Transform and filter telemetry
- **Batching & Retry**: Reliable data delivery
- **Sampling**: Intelligent trace sampling
- **Extensions**: Pluggable architecture

## Quick Start

```bash
docker run -p 4317:4317 -p 4318:4318 hanzo/telemetry
```

## Documentation

See the [documentation](https://hanzo.ai/docs/telemetry) for detailed guides and API reference.

## License

MIT License - see [LICENSE](LICENSE) for details.
