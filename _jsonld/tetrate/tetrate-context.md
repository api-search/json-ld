---
api_specs:
- filename: tetrate-service-bridge-openapi.yml
  format: yaml
  label: Tetrate Service Bridge REST API
  slug: tsb-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tetrate/refs/heads/main/openapi/tetrate-service-bridge-openapi.yml
class_count: 10
classes:
- Organization
- name
- description
- displayName
- labels
- annotations
- Tenant
- Application
- Role
- rules
context_file: json-ld/tetrate-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/tetrate/refs/heads/main/json-ld/tetrate-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Tetrate from Tetrate.
layout: jsonld
name: Tetrate Context
namespaces:
- prefix: schema
  uri: http://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: network
  uri: https://schema.tetrate.io/v2/network
- prefix: GatewayGroup
  uri: https://schema.tetrate.io/v2/GatewayGroup
- prefix: TrafficGroup
  uri: https://schema.tetrate.io/v2/TrafficGroup
- prefix: SecurityGroup
  uri: https://schema.tetrate.io/v2/SecurityGroup
- prefix: configMode
  uri: https://schema.tetrate.io/v2/configMode
properties:
- container: ''
  name: fqn
  type: string
- container: ''
  name: etag
  type: string
- container: ''
  name: Workspace
  type: schema:Place
- container: ''
  name: namespaceSelector
  type: reference
- container: ''
  name: Cluster
  type: schema:SoftwareApplication
- container: ''
  name: tier1Cluster
  type: boolean
- container: ''
  name: workspace
  type: reference
- container: ''
  name: API
  type: schema:WebAPI
- container: ''
  name: openapi
  type: string
- container: ''
  name: endpoints
  type: reference
- container: ''
  name: created
  type: dateTime
- container: ''
  name: modified
  type: dateTime
property_count: 12
provider_name: Tetrate
provider_slug: tetrate
slug: tetrate-context
source_filename: tetrate-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.tetrate.io/v2/\",\n    \"schema\": \"http://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Organization\": \"schema:Organization\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"displayName\": \"schema:name\",\n    \"fqn\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"etag\": {\n      \"@id\": \"schema:version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"labels\": \"schema:additionalProperty\",\n    \"annotations\": \"schema:additionalProperty\",\n\n    \"Tenant\": \"schema:Organization\",\n    \"Workspace\": {\n      \"@id\": \"https://schema.tetrate.io/v2/Workspace\",\n      \"@type\": \"schema:Place\"\n    },\n    \"namespaceSelector\": {\n      \"@id\": \"https://schema.tetrate.io/v2/namespaceSelector\",\n      \"@type\": \"@id\"\n    },\n\n    \"Cluster\": {\n      \"@id\": \"https://schema.tetrate.io/v2/Cluster\"\
  ,\n      \"@type\": \"schema:SoftwareApplication\"\n    },\n    \"network\": \"https://schema.tetrate.io/v2/network\",\n    \"tier1Cluster\": {\n      \"@id\": \"https://schema.tetrate.io/v2/tier1Cluster\",\n      \"@type\": \"xsd:boolean\"\n    },\n\n    \"Application\": \"schema:SoftwareApplication\",\n    \"workspace\": {\n      \"@id\": \"https://schema.tetrate.io/v2/workspace\",\n      \"@type\": \"@id\"\n    },\n\n    \"API\": {\n      \"@id\": \"https://schema.tetrate.io/v2/API\",\n      \"@type\": \"schema:WebAPI\"\n    },\n    \"openapi\": {\n      \"@id\": \"schema:encodingFormat\",\n      \"@type\": \"xsd:string\"\n    },\n    \"endpoints\": {\n      \"@id\": \"schema:serviceUrl\",\n      \"@type\": \"@id\"\n    },\n\n    \"GatewayGroup\": \"https://schema.tetrate.io/v2/GatewayGroup\",\n    \"TrafficGroup\": \"https://schema.tetrate.io/v2/TrafficGroup\",\n    \"SecurityGroup\": \"https://schema.tetrate.io/v2/SecurityGroup\",\n    \"configMode\": \"https://schema.tetrate.io/v2/configMode\"\
  ,\n\n    \"Role\": \"schema:Role\",\n    \"rules\": \"schema:permissions\",\n\n    \"created\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"modified\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/tetrate/refs/heads/main/json-ld/tetrate-context.jsonld
tags:
- Enterprise
- Envoy
- Istio
- Kubernetes
- Service Mesh
- JSON-LD
- Linked Data
- Semantic Web
---
