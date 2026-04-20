# Azure Container Apps (azure-container-apps)
Azure Container Apps is a serverless container service for running microservices and containerized applications with built-in autoscaling, traffic splitting, and Dapr integration. It enables developers to deploy containers without managing complex infrastructure while supporting event-driven architectures and microservices patterns.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/azure-container-apps/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Azure, Containers, Dapr, Kubernetes, Microservices, Serverless

## Timestamps

- **Created:** 2026-03-26
- **Modified:** 2026-04-19

## APIs

### Azure Container Apps
Azure Container Apps is a serverless container service for running microservices and containerized applications with built-in autoscaling, traffic splitting, and Dapr integration.

**Human URL:** [https://azure.microsoft.com/en-us/products/container-apps](https://azure.microsoft.com/en-us/products/container-apps)

#### Tags:

 - Azure, Containers, Kubernetes, Microservices, Serverless

#### Properties

- [OpenAPI](openapi/azure-container-apps-openapi.yml)
- [JSONSchema](json-schema/azure-container-apps-container-app-schema.json)
- [JSONSchema](json-schema/azure-container-apps-managed-environment-schema.json)
- [JSONSchema](json-schema/azure-container-apps-job-schema.json)
- [JSONSchema](json-schema/azure-container-apps-revision-schema.json)
- [Documentation](https://learn.microsoft.com/en-us/azure/container-apps/)
- [GettingStarted](https://learn.microsoft.com/en-us/azure/container-apps/get-started)
- [APIReference](https://learn.microsoft.com/en-us/rest/api/resource-manager/containerapps/operation-groups)
- [Authentication](https://learn.microsoft.com/en-us/azure/container-apps/authentication)
- [Pricing](https://azure.microsoft.com/en-us/pricing/details/container-apps/)

## Common Properties

- [Portal](https://portal.azure.com)
- [Documentation](https://learn.microsoft.com/en-us/azure/container-apps/)
- [GettingStarted](https://learn.microsoft.com/en-us/azure/container-apps/get-started)
- [GitHubRepository](https://github.com/microsoft/azure-container-apps)
- [GitHubOrganization](https://github.com/Azure)
- [Blog](https://techcommunity.microsoft.com/blog/appsonazureblog/)
- [Pricing](https://azure.microsoft.com/en-us/pricing/details/container-apps/)
- [StatusPage](https://status.azure.com/)
- [TermsOfService](https://azure.microsoft.com/en-us/support/legal/)
- [PrivacyPolicy](https://privacy.microsoft.com/en-us/privacystatement)
- [SignUp](https://azure.microsoft.com/en-us/free/)
- [Support](https://azure.microsoft.com/en-us/support/)
- [FAQ](https://learn.microsoft.com/en-us/azure/container-apps/faq)

## Features

| Name | Description |
|------|-------------|
| Serverless Containers | Run containers without managing servers or Kubernetes cluster infrastructure. |
| Built-in Autoscaling | Automatically scale based on HTTP traffic, event messages, or custom KEDA scalers. |
| Traffic Splitting | Gradually shift traffic between container revisions for canary deployments and A/B testing. |
| Dapr Integration | Built-in support for the Dapr distributed application runtime for service discovery and state management. |
| Managed Environments | Shared networking and logging infrastructure for groups of container apps. |
| Dynamic Sessions | Secure, ephemeral code-interpreter and custom container sessions with data-plane REST APIs. |
| Jobs Support | Schedule and run containerized batch jobs on demand or on a schedule. |
| GPU Support | Deploy AI/ML workloads on GPU-enabled container instances. |

## Use Cases

| Name | Description |
|------|-------------|
| Microservices Architecture | Deploy and scale individual microservices independently with built-in service discovery. |
| API Backend Deployment | Host REST APIs with automatic HTTPS, custom domains, and traffic management. |
| Event-Driven Processing | Process messages from Service Bus, Event Hubs, and storage queues with KEDA-based scaling. |
| AI and ML Workloads | Run AI inference workloads on GPU-enabled container instances with dynamic sessions. |
| Background Jobs | Run scheduled and on-demand batch jobs without maintaining dedicated infrastructure. |
| Dapr Microservices | Build microservices with Dapr for pub/sub messaging, service invocation, and state management. |

## Integrations

| Name | Description |
|------|-------------|
| Azure Kubernetes Service | Share underlying Kubernetes infrastructure while abstracting cluster management complexity. |
| Azure Container Registry | Pull container images directly from private ACR registries with managed identity. |
| Azure Service Bus | Trigger container app scaling based on Service Bus queue depth. |
| Azure Event Hubs | Process streaming data from Event Hubs with auto-scaling. |
| GitHub Actions | Deploy container apps directly from GitHub Actions CI/CD workflows. |
| Dapr | Built-in Dapr runtime support for distributed systems patterns. |
| Azure Monitor | Native integration with Azure Monitor and Log Analytics for observability. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Azure Container Apps OpenAPI](openapi/azure-container-apps-openapi.yml)

### JSON Schema

- [Container App](json-schema/azure-container-apps-container-app-schema.json)
- [Auth Config](json-schema/azure-container-apps-auth-config-schema.json)
- [Configuration](json-schema/azure-container-apps-configuration-schema.json)
- [Container](json-schema/azure-container-apps-container-schema.json)
- [Job](json-schema/azure-container-apps-job-schema.json)
- [Job Execution](json-schema/azure-container-apps-job-execution-schema.json)
- [Job Execution Template](json-schema/azure-container-apps-job-execution-template-schema.json)
- [Managed Environment](json-schema/azure-container-apps-managed-environment-schema.json)
- [Revision](json-schema/azure-container-apps-revision-schema.json)
- [Secret](json-schema/azure-container-apps-secret-schema.json)
- [Template](json-schema/azure-container-apps-template-schema.json)

### JSON-LD

- [Azure Container Apps Context](json-ld/azure-container-apps-context.jsonld)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Azure Container Apps](capabilities/shared/azure-container-apps.yaml) — 5 operations for container app, environment, and job management

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Container Apps Management](capabilities/container-apps-management.yaml) | Azure Container Apps | 5 | Platform Engineer, DevOps Engineer |

## Vocabulary

- [Azure Container Apps Vocabulary](vocabulary/azure-container-apps-vocabulary.yaml) — Unified taxonomy mapping 6 resources, 5 actions, 1 workflow, and 2 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Azure Container Apps Spectral Rules](rules/azure-container-apps-spectral-rules.yml) — 15 rules across 8 categories enforcing Azure Container Apps API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
