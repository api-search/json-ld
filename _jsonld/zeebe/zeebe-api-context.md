---
api_specs:
- filename: zeebe-api.yml
  format: yaml
  label: Zeebe REST API
  slug: zeebe
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/zeebe/refs/heads/main/openapi/zeebe-api.yml
class_count: 5
classes:
- DeploymentResponse
- Job
- ProcessInstance
- TopologyResponse
- version
context_file: json-ld/zeebe-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/zeebe/refs/heads/main/json-ld/zeebe-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Zeebe Api from Zeebe.
layout: jsonld
name: Zeebe Api Context
namespaces:
- prefix: zeebe
  uri: https://zeebe.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: deploymentKey
  type: integer
- container: set
  name: deployments
  type: string
- container: ''
  name: tenantId
  type: string
- container: ''
  name: jobKey
  type: integer
- container: ''
  name: type
  type: string
- container: ''
  name: processInstanceKey
  type: integer
- container: ''
  name: processDefinitionKey
  type: integer
- container: ''
  name: bpmnProcessId
  type: string
- container: ''
  name: elementId
  type: string
- container: ''
  name: elementInstanceKey
  type: integer
- container: ''
  name: customHeaders
  type: reference
- container: ''
  name: worker
  type: string
- container: ''
  name: retries
  type: integer
- container: ''
  name: deadline
  type: integer
- container: ''
  name: variables
  type: reference
- container: set
  name: brokers
  type: string
- container: ''
  name: nodeId
  type: integer
- container: ''
  name: host
  type: string
- container: ''
  name: port
  type: integer
- container: set
  name: partitions
  type: string
- container: ''
  name: partitionId
  type: integer
- container: ''
  name: role
  type: string
- container: ''
  name: health
  type: string
- container: ''
  name: clusterSize
  type: integer
- container: ''
  name: partitionsCount
  type: integer
- container: ''
  name: replicationFactor
  type: integer
- container: ''
  name: gatewayVersion
  type: string
property_count: 27
provider_name: Zeebe
provider_slug: zeebe
slug: zeebe-api-context
source_filename: zeebe-api-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"zeebe\": \"https://zeebe.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"DeploymentResponse\": \"zeebe:DeploymentResponse\",\n    \"Job\": \"zeebe:Job\",\n    \"ProcessInstance\": \"zeebe:ProcessInstance\",\n    \"TopologyResponse\": \"zeebe:TopologyResponse\",\n    \"deploymentKey\": {\n      \"@id\": \"zeebe:deploymentKey\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"deployments\": {\n      \"@id\": \"zeebe:deployments\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tenantId\": {\n      \"@id\": \"zeebe:tenantId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"jobKey\": {\n      \"@id\": \"zeebe:jobKey\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"type\": {\n      \"@id\": \"zeebe:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"processInstanceKey\"\
  : {\n      \"@id\": \"zeebe:processInstanceKey\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"processDefinitionKey\": {\n      \"@id\": \"zeebe:processDefinitionKey\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"bpmnProcessId\": {\n      \"@id\": \"zeebe:bpmnProcessId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"elementId\": {\n      \"@id\": \"zeebe:elementId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"elementInstanceKey\": {\n      \"@id\": \"zeebe:elementInstanceKey\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"customHeaders\": {\n      \"@id\": \"zeebe:customHeaders\",\n      \"@type\": \"@id\"\n    },\n    \"worker\": {\n      \"@id\": \"zeebe:worker\",\n      \"@type\": \"xsd:string\"\n    },\n    \"retries\": {\n      \"@id\": \"zeebe:retries\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"deadline\": {\n      \"@id\": \"zeebe:deadline\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"variables\": {\n      \"@id\": \"zeebe:variables\",\n      \"\
  @type\": \"@id\"\n    },\n    \"version\": \"schema:version\",\n    \"brokers\": {\n      \"@id\": \"zeebe:brokers\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nodeId\": {\n      \"@id\": \"zeebe:nodeId\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"host\": {\n      \"@id\": \"zeebe:host\",\n      \"@type\": \"xsd:string\"\n    },\n    \"port\": {\n      \"@id\": \"zeebe:port\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"partitions\": {\n      \"@id\": \"zeebe:partitions\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"partitionId\": {\n      \"@id\": \"zeebe:partitionId\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"role\": {\n      \"@id\": \"zeebe:role\",\n      \"@type\": \"xsd:string\"\n    },\n    \"health\": {\n      \"@id\": \"zeebe:health\",\n      \"@type\": \"xsd:string\"\n    },\n    \"clusterSize\": {\n      \"@id\": \"zeebe:clusterSize\",\n      \"@type\": \"xsd:integer\"\n    },\n \
  \   \"partitionsCount\": {\n      \"@id\": \"zeebe:partitionsCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"replicationFactor\": {\n      \"@id\": \"zeebe:replicationFactor\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"gatewayVersion\": {\n      \"@id\": \"zeebe:gatewayVersion\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/zeebe/refs/heads/main/json-ld/zeebe-api-context.jsonld
tags:
- BPMN
- Camunda
- Cloud Native
- Distributed Systems
- Java
- Microservices
- Process Automation
- Workflow Orchestration
- JSON-LD
- Linked Data
- Semantic Web
---
