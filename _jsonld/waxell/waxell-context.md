---
api_specs:
- filename: waxell-observe-openapi.yml
  format: yaml
  label: Waxell Observe API
  slug: observe
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/waxell/refs/heads/main/openapi/waxell-observe-openapi.yml
class_count: 26
classes:
- Agent
- Run
- Session
- LlmCall
- Span
- Step
- Score
- Policy
- PolicyDecision
- Event
- ModelCost
- Prompt
- session_id
- model
- provider
- input_tokens
- output_tokens
- latency_ms
- cost_usd
- decision
- category
- policy_id
- span_id
- parent_span_id
- kind
- attributes
context_file: json-ld/waxell-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/waxell/refs/heads/main/json-ld/waxell-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Waxell from Waxell.
layout: jsonld
name: Waxell Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: waxell
  uri: https://waxell.ai/ns#
- prefix: otel
  uri: https://opentelemetry.io/schemas/
properties:
- container: ''
  name: agent_name
  type: string
- container: ''
  name: run_id
  type: string
- container: ''
  name: user_id
  type: reference
- container: ''
  name: started_at
  type: dateTime
- container: ''
  name: completed_at
  type: dateTime
- container: ''
  name: reason
  type: string
property_count: 6
provider_name: Waxell
provider_slug: waxell
slug: waxell-context
source_filename: waxell-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"waxell\": \"https://waxell.ai/ns#\",\n    \"otel\": \"https://opentelemetry.io/schemas/\",\n    \"Agent\": \"waxell:Agent\",\n    \"Run\": \"waxell:Run\",\n    \"Session\": \"waxell:Session\",\n    \"LlmCall\": \"waxell:LlmCall\",\n    \"Span\": \"waxell:Span\",\n    \"Step\": \"waxell:Step\",\n    \"Score\": \"waxell:Score\",\n    \"Policy\": \"waxell:Policy\",\n    \"PolicyDecision\": \"waxell:PolicyDecision\",\n    \"Event\": \"waxell:Event\",\n    \"ModelCost\": \"waxell:ModelCost\",\n    \"Prompt\": \"waxell:Prompt\",\n    \"agent_name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"run_id\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"session_id\": \"waxell:sessionId\",\n    \"user_id\": {\n      \"@id\": \"schema:agent\",\n      \"@type\": \"@id\"\n    },\n    \"model\": \"waxell:model\",\n  \
  \  \"provider\": \"waxell:provider\",\n    \"input_tokens\": \"waxell:inputTokens\",\n    \"output_tokens\": \"waxell:outputTokens\",\n    \"latency_ms\": \"waxell:latencyMs\",\n    \"cost_usd\": \"waxell:costUsd\",\n    \"started_at\": {\n      \"@id\": \"schema:startTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"completed_at\": {\n      \"@id\": \"schema:endTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"decision\": \"waxell:decision\",\n    \"category\": \"waxell:policyCategory\",\n    \"reason\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"policy_id\": \"waxell:policyId\",\n    \"span_id\": \"waxell:spanId\",\n    \"parent_span_id\": \"waxell:parentSpanId\",\n    \"kind\": \"waxell:spanKind\",\n    \"attributes\": \"otel:attributes\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/waxell/refs/heads/main/json-ld/waxell-context.jsonld
tags:
- AI Agent Governance
- Observability
- Policy Enforcement
- LLM Telemetry
- Cost Management
- MCP
- Agent Runtime
- JSON-LD
- Linked Data
- Semantic Web
---
