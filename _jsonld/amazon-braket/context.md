---
api_specs:
- filename: amazon-braket-api-openapi.yml
  format: yaml
  label: Amazon Braket API
  slug: amazon-braket-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-braket/refs/heads/main/openapi/amazon-braket-api-openapi.yml
class_count: 23
classes:
- QuantumTask
- quantumTaskArn
- shots
- action
- deviceParameters
- Device
- deviceArn
- deviceName
- deviceType
- deviceStatus
- providerName
- deviceCapabilities
- Job
- jobArn
- jobName
- algorithmSpecification
- instanceConfig
- hyperParameters
- status
- failureReason
- outputS3Bucket
- outputS3KeyPrefix
- tags
context_file: json-ld/context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-braket/refs/heads/main/json-ld/context.jsonld
description: JSON-LD context defining the semantic vocabulary for context from Amazon Braket.
layout: jsonld
name: context Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: braket
  uri: https://aws.amazon.com/braket/vocab#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: endedAt
  type: dateTime
- container: ''
  name: startedAt
  type: dateTime
property_count: 3
provider_name: Amazon Braket
provider_slug: amazon-braket
slug: context
source_filename: context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"braket\": \"https://aws.amazon.com/braket/vocab#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"QuantumTask\": \"braket:QuantumTask\",\n    \"quantumTaskArn\": \"braket:quantumTaskArn\",\n    \"shots\": \"braket:shots\",\n    \"action\": \"braket:circuitAction\",\n    \"deviceParameters\": \"braket:deviceParameters\",\n\n    \"Device\": \"braket:Device\",\n    \"deviceArn\": \"braket:deviceArn\",\n    \"deviceName\": \"schema:name\",\n    \"deviceType\": \"braket:deviceType\",\n    \"deviceStatus\": \"braket:deviceStatus\",\n    \"providerName\": \"schema:provider\",\n    \"deviceCapabilities\": \"braket:deviceCapabilities\",\n\n    \"Job\": \"braket:HybridJob\",\n    \"jobArn\": \"braket:jobArn\",\n    \"jobName\": \"schema:name\",\n    \"algorithmSpecification\": \"braket:algorithmSpecification\",\n    \"instanceConfig\": \"braket:instanceConfig\",\n    \"hyperParameters\"\
  : \"braket:hyperParameters\",\n\n    \"status\": \"braket:status\",\n    \"failureReason\": \"braket:failureReason\",\n\n    \"outputS3Bucket\": \"braket:outputS3Bucket\",\n    \"outputS3KeyPrefix\": \"braket:outputS3KeyPrefix\",\n\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"endedAt\": {\n      \"@id\": \"braket:endedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"startedAt\": {\n      \"@id\": \"braket:startedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n\n    \"tags\": \"schema:additionalProperty\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-braket/refs/heads/main/json-ld/context.jsonld
tags:
- Quantum Computing
- Quantum Hardware
- Hybrid Quantum-Classical
- QPU
- Quantum Simulation
- Amazon Web Services
- Research
- HPC
- JSON-LD
- Linked Data
- Semantic Web
---
