# Spinnaker

Spinnaker is an open source multi-cloud continuous delivery platform for releasing software changes with high velocity and confidence. Originally developed at Netflix and Google, Spinnaker provides a deployment platform supporting AWS, GCP, Azure, Kubernetes, and other cloud providers. The Gate API is the primary REST interface for all Spinnaker operations including application management, pipeline execution, and infrastructure orchestration.

## APIs

### Spinnaker Gate API

Gate is the Spinnaker API Gateway — the primary REST interface for all Spinnaker operations. It runs on port 8084 and is used by the Spinnaker UI (Deck) as well as external automation and integrations. Supports OAuth 2.0, SAML, LDAP, and X.509 certificate authentication.

- **Documentation:** https://spinnaker.io/docs/reference/api/
- **Swagger UI:** https://spinnaker.io/docs/reference/api/docs.html
- **GitHub:** https://github.com/spinnaker/gate
- **OpenAPI:** [openapi/spinnaker-gate-openapi.yml](openapi/spinnaker-gate-openapi.yml)

## OpenAPI Specifications

| API | File |
|-----|------|
| Spinnaker Gate API | [openapi/spinnaker-gate-openapi.yml](openapi/spinnaker-gate-openapi.yml) |

## Spectral Rules

| Ruleset | File |
|---------|------|
| Spinnaker Rules | [rules/spinnaker-rules.yml](rules/spinnaker-rules.yml) |

## Capabilities

| Capability | Description | File |
|------------|-------------|------|
| Continuous Delivery | Pipeline management and deployment orchestration | [capabilities/continuous-delivery.yaml](capabilities/continuous-delivery.yaml) |

### Shared Definitions

| API | File |
|-----|------|
| Gate | [capabilities/shared/gate.yaml](capabilities/shared/gate.yaml) |

## JSON Schema

| Schema | File |
|--------|------|
| Pipeline Execution | [json-schema/spinnaker-pipeline-schema.json](json-schema/spinnaker-pipeline-schema.json) |

## JSON Structure

| Structure | File |
|-----------|------|
| Pipeline Execution | [json-structure/spinnaker-pipeline-structure.json](json-structure/spinnaker-pipeline-structure.json) |

## JSON-LD

| Context | File |
|---------|------|
| Spinnaker Context | [json-ld/spinnaker-context.jsonld](json-ld/spinnaker-context.jsonld) |

## Examples

| Example | File |
|---------|------|
| List Applications | [examples/spinnaker-list-applications-example.json](examples/spinnaker-list-applications-example.json) |
| Invoke Pipeline | [examples/spinnaker-invoke-pipeline-example.json](examples/spinnaker-invoke-pipeline-example.json) |

## Vocabulary

| Vocabulary | File |
|------------|------|
| Spinnaker Vocabulary | [vocabulary/spinnaker-vocabulary.yml](vocabulary/spinnaker-vocabulary.yml) |

## Links

- **Website:** https://spinnaker.io/
- **Documentation:** https://spinnaker.io/docs/
- **GitHub Organization:** https://github.com/spinnaker
- **Community:** https://spinnaker.io/community/
- **Slack:** https://join.spinnaker.io/
- **Blog:** https://spinnaker.io/blog/
- **Changelog:** https://spinnaker.io/changelogs/
