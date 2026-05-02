# Relay App

Relay.app is an AI-powered workflow automation platform that converts plain language into reliable visual workflows across 200+ app integrations. It supports webhook triggers, custom HTTP requests, scheduled automation, human-in-the-loop approval workflows, and MCP server tooling for AI agent integration. Developer features include API-triggered workflows, custom JavaScript execution, and integration with OpenAI, Anthropic, and other AI providers.

**URL:** [apis.yml](https://raw.githubusercontent.com/api-evangelist/relay-app/refs/heads/main/apis.yml)

## APIs

| Name | Description |
|---|---|
| [Relay App Automation API](https://docs.relay.app/) | Programmatic workflow triggering via webhooks, workflow management, run status monitoring, and human-in-the-loop approvals. |

## Tags

- Automation
- Workflow
- Integration
- No-Code
- AI
- Webhooks

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-05-02

## Common Properties

| Type | URL |
|---|---|
| Website | [https://www.relay.app](https://www.relay.app) |
| Documentation | [https://docs.relay.app/](https://docs.relay.app/) |
| Integrations | [https://www.relay.app/apps](https://www.relay.app/apps) |
| Blog | [https://www.relay.app/blog](https://www.relay.app/blog) |
| Features | [https://www.relay.app/features](https://www.relay.app/features) |

## Artifacts

| Type | Path |
|---|---|
| APIs Index | [apis.yml](apis.yml) |
| OpenAPI | [openapi/relay-app-openapi.yml](openapi/relay-app-openapi.yml) |
| Spectral Rules | [rules/relay-app-rules.yml](rules/relay-app-rules.yml) |
| Capabilities | [capabilities/workflow-automation.yaml](capabilities/workflow-automation.yaml) |
| Capabilities (Shared) | [capabilities/shared/relay-app.yaml](capabilities/shared/relay-app.yaml) |
| JSON Schema (Workflow) | [json-schema/relay-app-workflow-schema.json](json-schema/relay-app-workflow-schema.json) |
| JSON Schema (Workflow Run) | [json-schema/relay-app-workflow-run-schema.json](json-schema/relay-app-workflow-run-schema.json) |
| JSON Structure | [json-structure/relay-app-workflow-structure.json](json-structure/relay-app-workflow-structure.json) |
| JSON-LD Context | [json-ld/relay-app-context.jsonld](json-ld/relay-app-context.jsonld) |
| Examples | [examples/relay-app-trigger-webhook-example.json](examples/relay-app-trigger-webhook-example.json) |
| Examples | [examples/relay-app-approve-workflow-step-example.json](examples/relay-app-approve-workflow-step-example.json) |
| Vocabulary | [vocabulary/relay-app-vocabulary.yml](vocabulary/relay-app-vocabulary.yml) |

## Capabilities

### Workflow Capabilities

| Capability | Description |
|---|---|
| [Workflow Automation](capabilities/workflow-automation.yaml) | Unified REST and MCP API for triggering, monitoring, approving, and cancelling Relay.app workflow runs (7 tools). |

### Shared Definitions

| Shared File | Description |
|---|---|
| [relay-app](capabilities/shared/relay-app.yaml) | Per-API consumed definition for the Relay.app Automation REST API. |

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
