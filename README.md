# Yagiz Kilicarslan

Backend engineer at [Areal.AI](https://areal.ai), focused on platform. I own the reliability, performance and security of our platform, from the services and database to the cloud they run on.

### What I've done

- **Led a monolith → cloud-native rewrite.** Built the MVP solo, then led the team to production. Core services now ship as independent containers that autoscale horizontally on ECS and run on Kubernetes. The result was 10× daily throughput and the headroom to onboard our largest customer.
- **Made our backend agent-native.** Built agent skills, plugins and MCP servers that cover the codebase, deployments, the design system and the observability stack. Also built a CLI and MCP server for our API with OAuth and fine-grained permissions.
- **Replaced log files with OpenTelemetry.** Instrumented the app end to end. Filterable, shareable traces changed how the team debugs.
- **Built auth & SSO** for our API.
- **Internal tools:** a document labeling tool for model fine-tuning, a mock-document generator for demos and tests, and agent-native integration tooling.

### Stack

Python (Django, FastAPI) · PostgreSQL · Docker · Kubernetes · AWS (ECS, RDS, S3, Bedrock, SageMaker) · Go · Rust

### Next

Self-hosted infrastructure and AI: on-prem Kubernetes, running models on our own GPUs, and inference.

---

[yagizklc.github.io](https://yagizklc.github.io)
