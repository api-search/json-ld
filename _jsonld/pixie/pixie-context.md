---
api_specs:
- filename: pixie-openapi.yml
  format: yaml
  label: Pixie API
  slug: pixie
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/pixie/refs/heads/main/openapi/pixie-openapi.yml
class_count: 0
classes: []
context_file: json-ld/pixie-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/pixie/refs/heads/main/json-ld/pixie-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Pixie from Pixie.
layout: jsonld
name: Pixie Context
namespaces:
- prefix: pixie
  uri: https://px.dev/vocabulary#
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: prov
  uri: http://www.w3.org/ns/prov#
- prefix: ssn
  uri: http://www.w3.org/ns/ssn/
- prefix: sosa
  uri: http://www.w3.org/ns/sosa/
properties:
- container: ''
  name: Cluster
  type: ''
- container: ''
  name: PxLScript
  type: ''
- container: ''
  name: ScriptArg
  type: ''
- container: ''
  name: RetentionScript
  type: ''
- container: ''
  name: Plugin
  type: ''
- container: ''
  name: ResultTable
  type: ''
- container: ''
  name: Observation
  type: ''
property_count: 7
provider_name: Pixie
provider_slug: pixie
slug: pixie-context
source_filename: pixie-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"pixie\": \"https://px.dev/vocabulary#\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"prov\": \"http://www.w3.org/ns/prov#\",\n    \"ssn\": \"http://www.w3.org/ns/ssn/\",\n    \"sosa\": \"http://www.w3.org/ns/sosa/\",\n\n    \"Cluster\": {\n      \"@id\": \"pixie:Cluster\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"clusterName\": \"schema:name\",\n        \"clusterUID\": \"pixie:clusterUID\",\n        \"clusterVersion\": \"schema:softwareVersion\",\n        \"status\": \"pixie:clusterStatus\",\n        \"vizierVersion\": \"pixie:vizierVersion\",\n        \"numNodes\": \"pixie:nodeCount\",\n        \"numInstrumentedNodes\": \"pixie:instrumentedNodeCount\",\n        \"lastHeartbeatNs\": {\n          \"@id\": \"pixie:lastHeartbeat\",\n          \"@type\": \"xsd:long\"\n        },\n        \"prettyClusterName\"\
  : \"schema:alternateName\"\n      }\n    },\n\n    \"PxLScript\": {\n      \"@id\": \"pixie:PxLScript\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"pxl\": \"pixie:scriptSource\",\n        \"args\": {\n          \"@id\": \"pixie:scriptArguments\",\n          \"@container\": \"@set\"\n        },\n        \"hidden\": \"pixie:isHidden\",\n        \"orgID\": {\n          \"@id\": \"pixie:organization\",\n          \"@type\": \"@id\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"ScriptArg\": {\n      \"@id\": \"pixie:ScriptArgument\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"defaultValue\"\
  : \"schema:defaultValue\",\n        \"semantic_type\": \"pixie:semanticType\",\n        \"validValues\": {\n          \"@id\": \"schema:suggestedAnswer\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"RetentionScript\": {\n      \"@id\": \"pixie:RetentionScript\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"script_name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"script\": \"pixie:scriptSource\",\n        \"frequency_s\": {\n          \"@id\": \"schema:repeatFrequency\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"enabled\": \"pixie:isEnabled\",\n        \"plugin_id\": {\n          \"@id\": \"pixie:plugin\",\n          \"@type\": \"@id\"\n        },\n        \"export_url\": {\n          \"@id\": \"pixie:exportEndpoint\",\n          \"@type\": \"@id\"\n        },\n        \"cluster_ids\": {\n          \"@id\": \"pixie:targetClusters\",\n          \"@container\": \"@set\"\n        }\n      }\n\
  \    },\n\n    \"Plugin\": {\n      \"@id\": \"pixie:Plugin\",\n      \"@context\": {\n        \"plugin_id\": \"@id\",\n        \"enabled\": \"pixie:isEnabled\",\n        \"version\": \"schema:version\",\n        \"customExportURL\": {\n          \"@id\": \"pixie:exportEndpoint\",\n          \"@type\": \"@id\"\n        },\n        \"retention_scripts\": {\n          \"@id\": \"pixie:retentionScripts\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"ResultTable\": {\n      \"@id\": \"pixie:ResultTable\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"relation\": \"pixie:tableSchema\",\n        \"data\": {\n          \"@id\": \"pixie:rowData\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Observation\": {\n      \"@id\": \"sosa:Observation\",\n      \"@context\": {\n        \"timestamp\": {\n          \"@id\": \"sosa:resultTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"service\": {\n     \
  \     \"@id\": \"schema:name\",\n          \"@type\": \"@id\"\n        },\n        \"namespace\": \"pixie:kubernetesNamespace\",\n        \"pod\": \"pixie:kubernetesPod\",\n        \"node\": \"pixie:kubernetesNode\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/pixie/refs/heads/main/json-ld/pixie-context.jsonld
tags:
- eBPF
- Kubernetes
- Monitoring
- Observability
- JSON-LD
- Linked Data
- Semantic Web
---
