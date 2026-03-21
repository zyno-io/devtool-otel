Quick launch tool to launch a local Grafana LGTM environment for use in local development.

Startup: `npx @zyno-io/devtool-otel`\
Shutdown: `npx @zyno-io/devtool-otel down`

Exposes:
- Grafana at http://localhost:4316/explore
- gRPC OpenTelemetry collector at http://localhost:4317
- HTTP OpenTelemetry collector at http://localhost:4318
- Tempo (HTTP) at http://localhost:4320
- Loki (HTTP) at http://localhost:4319
