---
api_specs:
- filename: policy-api.yml
  format: yaml
  label: Open Policy Agent Policy API
  slug: open-policy-agent-policy-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/open-policy-agent/refs/heads/main/openapi/policy-api.yml
- filename: data-api.yml
  format: yaml
  label: Open Policy Agent Data API
  slug: open-policy-agent-data-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/open-policy-agent/refs/heads/main/openapi/data-api.yml
- filename: query-api.yml
  format: yaml
  label: Open Policy Agent Query API
  slug: open-policy-agent-query-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/open-policy-agent/refs/heads/main/openapi/query-api.yml
- filename: compile-api.yml
  format: yaml
  label: Open Policy Agent Compile API
  slug: open-policy-agent-compile-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/open-policy-agent/refs/heads/main/openapi/compile-api.yml
- filename: health-api.yml
  format: yaml
  label: Open Policy Agent Health API
  slug: open-policy-agent-health-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/open-policy-agent/refs/heads/main/openapi/health-api.yml
- filename: config-api.yml
  format: yaml
  label: Open Policy Agent Config API
  slug: open-policy-agent-config-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/open-policy-agent/refs/heads/main/openapi/config-api.yml
- filename: status-api.yml
  format: yaml
  label: Open Policy Agent Status API
  slug: open-policy-agent-status-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/open-policy-agent/refs/heads/main/openapi/status-api.yml
class_count: 0
classes: []
context_file: json-ld/opa-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/open-policy-agent/refs/heads/main/json-ld/opa-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Opa from Open Policy Agent.
layout: jsonld
name: Opa Context
namespaces:
- prefix: opa
  uri: https://www.openpolicyagent.org/vocab/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: rdfs
  uri: http://www.w3.org/2000/01/rdf-schema#
properties:
- container: ''
  name: PolicyModule
  type: ''
- container: ''
  name: PolicyRule
  type: ''
- container: ''
  name: DataDocument
  type: ''
- container: ''
  name: PolicyDecisionRequest
  type: ''
- container: ''
  name: QueryRequest
  type: ''
- container: ''
  name: QueryResult
  type: ''
- container: ''
  name: CompileRequest
  type: ''
- container: ''
  name: OPAError
  type: ''
- container: ''
  name: OPAStatus
  type: ''
- container: ''
  name: BundleStatus
  type: ''
- container: ''
  name: EvaluationMetrics
  type: ''
- container: ''
  name: Provenance
  type: ''
property_count: 12
provider_name: Open Policy Agent
provider_slug: open-policy-agent
slug: opa-context
source_filename: opa-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"opa\": \"https://www.openpolicyagent.org/vocab/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"rdfs\": \"http://www.w3.org/2000/01/rdf-schema#\",\n\n    \"PolicyModule\": {\n      \"@id\": \"opa:PolicyModule\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"schema:identifier\"\n        },\n        \"raw\": {\n          \"@id\": \"opa:regoSource\"\n        },\n        \"ast\": {\n          \"@id\": \"opa:abstractSyntaxTree\"\n        }\n      }\n    },\n\n    \"PolicyRule\": {\n      \"@id\": \"opa:PolicyRule\",\n      \"@context\": {\n        \"default\": {\n          \"@id\": \"opa:isDefault\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"head\": {\n          \"@id\": \"opa:ruleHead\"\n        },\n        \"body\": {\n          \"@id\": \"opa:ruleBody\",\n          \"@container\": \"\
  @set\"\n        }\n      }\n    },\n\n    \"DataDocument\": {\n      \"@id\": \"opa:DataDocument\",\n      \"@context\": {\n        \"result\": {\n          \"@id\": \"opa:documentValue\"\n        },\n        \"decision_id\": {\n          \"@id\": \"schema:identifier\"\n        },\n        \"metrics\": {\n          \"@id\": \"opa:evaluationMetrics\"\n        }\n      }\n    },\n\n    \"PolicyDecisionRequest\": {\n      \"@id\": \"opa:PolicyDecisionRequest\",\n      \"@context\": {\n        \"input\": {\n          \"@id\": \"opa:inputDocument\"\n        }\n      }\n    },\n\n    \"QueryRequest\": {\n      \"@id\": \"opa:QueryRequest\",\n      \"@context\": {\n        \"query\": {\n          \"@id\": \"opa:regoQuery\"\n        },\n        \"input\": {\n          \"@id\": \"opa:inputDocument\"\n        },\n        \"unknowns\": {\n          \"@id\": \"opa:unknownRefs\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"QueryResult\": {\n      \"@id\": \"opa:QueryResult\"\
  ,\n      \"@context\": {\n        \"result\": {\n          \"@id\": \"opa:resultSet\",\n          \"@container\": \"@set\"\n        },\n        \"decision_id\": {\n          \"@id\": \"schema:identifier\"\n        },\n        \"metrics\": {\n          \"@id\": \"opa:evaluationMetrics\"\n        }\n      }\n    },\n\n    \"CompileRequest\": {\n      \"@id\": \"opa:CompileRequest\",\n      \"@context\": {\n        \"query\": {\n          \"@id\": \"opa:regoQuery\"\n        },\n        \"input\": {\n          \"@id\": \"opa:inputDocument\"\n        },\n        \"unknowns\": {\n          \"@id\": \"opa:unknownRefs\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"OPAError\": {\n      \"@id\": \"opa:OPAError\",\n      \"@context\": {\n        \"code\": {\n          \"@id\": \"schema:identifier\"\n        },\n        \"message\": {\n          \"@id\": \"schema:description\"\n        }\n      }\n    },\n\n    \"OPAStatus\": {\n      \"@id\": \"opa:OPAStatus\",\n    \
  \  \"@context\": {\n        \"bundles\": {\n          \"@id\": \"opa:bundleStatus\"\n        },\n        \"plugins\": {\n          \"@id\": \"opa:pluginStatus\"\n        }\n      }\n    },\n\n    \"BundleStatus\": {\n      \"@id\": \"opa:BundleStatus\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\"\n        },\n        \"active_revision\": {\n          \"@id\": \"opa:activeRevision\"\n        },\n        \"last_successful_activation\": {\n          \"@id\": \"opa:lastSuccessfulActivation\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"last_successful_download\": {\n          \"@id\": \"opa:lastSuccessfulDownload\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"EvaluationMetrics\": {\n      \"@id\": \"opa:EvaluationMetrics\",\n      \"@context\": {\n        \"timer_rego_query_eval_ns\": {\n          \"@id\": \"opa:queryEvalNs\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"timer_rego_query_parse_ns\"\
  : {\n          \"@id\": \"opa:queryParseNs\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"timer_rego_query_compile_ns\": {\n          \"@id\": \"opa:queryCompileNs\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"Provenance\": {\n      \"@id\": \"opa:Provenance\",\n      \"@context\": {\n        \"version\": {\n          \"@id\": \"schema:version\"\n        },\n        \"build_commit\": {\n          \"@id\": \"opa:buildCommit\"\n        },\n        \"build_timestamp\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"build_hostname\": {\n          \"@id\": \"schema:hostName\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/open-policy-agent/refs/heads/main/json-ld/opa-context.jsonld
tags:
- Policies
- Standards
- JSON-LD
- Linked Data
- Semantic Web
---
