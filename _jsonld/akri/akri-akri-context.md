---
api_specs:
- filename: akri-metrics-openapi.yaml
  format: yaml
  label: Akri Metrics API
  slug: metrics-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/akri/refs/heads/main/openapi/akri-metrics-openapi.yaml
class_count: 6
classes:
- AkriDiscoveryResponseResult
- AkriInstanceCount
- AkriBrokerPodCount
- AkriInstance
- AkriConfiguration
- AkriDiscoveryResponseTime
context_file: json-ld/akri-akri-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/akri/refs/heads/main/json-ld/akri-akri-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Akri Akri from Akri.
layout: jsonld
name: Akri Akri Context
namespaces:
- prefix: akri
  uri: https://akri.sh/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: apiVersion
  type: string
- container: ''
  name: capacity
  type: integer
- container: ''
  name: configuration
  type: string
- container: ''
  name: configurationName
  type: string
- container: ''
  name: deviceUsage
  type: reference
- container: ''
  name: discoveryDetails
  type: string
- container: ''
  name: discoveryHandler
  type: reference
- container: set
  name: discoveryProperties
  type: string
- container: ''
  name: kind
  type: string
- container: ''
  name: le
  type: string
- container: ''
  name: metadata
  type: reference
- container: ''
  name: name
  type: string
- container: ''
  name: namespace
  type: string
- container: ''
  name: node
  type: string
- container: set
  name: nodes
  type: string
- container: ''
  name: result
  type: string
- container: ''
  name: shared
  type: string
- container: ''
  name: spec
  type: reference
- container: ''
  name: value
  type: decimal
property_count: 19
provider_name: Akri
provider_slug: akri
slug: akri-akri-context
source_filename: akri-akri-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"akri\": \"https://akri.sh/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AkriDiscoveryResponseResult\": \"akri:AkriDiscoveryResponseResult\",\n    \"AkriInstanceCount\": \"akri:AkriInstanceCount\",\n    \"AkriBrokerPodCount\": \"akri:AkriBrokerPodCount\",\n    \"AkriInstance\": \"akri:AkriInstance\",\n    \"AkriConfiguration\": \"akri:AkriConfiguration\",\n    \"AkriDiscoveryResponseTime\": \"akri:AkriDiscoveryResponseTime\",\n    \"apiVersion\": {\n      \"@id\": \"akri:apiVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"capacity\": {\n      \"@id\": \"akri:capacity\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"configuration\": {\n      \"@id\": \"akri:configuration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"configurationName\": {\n      \"@id\": \"akri:configurationName\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"deviceUsage\": {\n      \"@id\": \"akri:deviceUsage\",\n      \"@type\": \"@id\"\n    },\n    \"discoveryDetails\": {\n      \"@id\": \"akri:discoveryDetails\",\n      \"@type\": \"xsd:string\"\n    },\n    \"discoveryHandler\": {\n      \"@id\": \"akri:discoveryHandler\",\n      \"@type\": \"@id\"\n    },\n    \"discoveryProperties\": {\n      \"@id\": \"akri:discoveryProperties\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"kind\": {\n      \"@id\": \"akri:kind\",\n      \"@type\": \"xsd:string\"\n    },\n    \"le\": {\n      \"@id\": \"akri:le\",\n      \"@type\": \"xsd:string\"\n    },\n    \"metadata\": {\n      \"@id\": \"akri:metadata\",\n      \"@type\": \"@id\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"namespace\": {\n      \"@id\": \"akri:namespace\",\n      \"@type\": \"xsd:string\"\n    },\n    \"node\": {\n      \"@id\": \"akri:node\",\n    \
  \  \"@type\": \"xsd:string\"\n    },\n    \"nodes\": {\n      \"@id\": \"akri:nodes\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"result\": {\n      \"@id\": \"akri:result\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shared\": {\n      \"@id\": \"akri:shared\",\n      \"@type\": \"xsd:string\"\n    },\n    \"spec\": {\n      \"@id\": \"akri:spec\",\n      \"@type\": \"@id\"\n    },\n    \"value\": {\n      \"@id\": \"akri:value\",\n      \"@type\": \"xsd:decimal\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/akri/refs/heads/main/json-ld/akri-akri-context.jsonld
tags:
- Device Management
- Edge Computing
- IoT
- Kubernetes
- CNCF
- Open Source
- OPC UA
- ONVIF
- udev
- JSON-LD
- Linked Data
- Semantic Web
---
