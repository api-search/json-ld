---
api_specs:
- filename: wasmcloud-control-asyncapi.yml
  format: yaml
  label: wasmCloud Control Interface API
  slug: wasmcloud-control-api
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/wasmcloud/refs/heads/main/asyncapi/wasmcloud-control-asyncapi.yml
- filename: wasmcloud-wadm-asyncapi.yml
  format: yaml
  label: wasmCloud Application Deployment Manager (wadm) API
  slug: wasmcloud-wadm-api
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/wasmcloud/refs/heads/main/asyncapi/wasmcloud-wadm-asyncapi.yml
class_count: 8
classes:
- Application
- Component
- CapabilityProvider
- LinkDefinition
- Host
- Lattice
- Trait
- SpreadScaler
context_file: json-ld/wasmcloud-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/wasmcloud/refs/heads/main/json-ld/wasmcloud-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Wasmcloud from wasmCloud.
layout: jsonld
name: Wasmcloud Context
namespaces:
- prefix: wasmcloud
  uri: https://wasmcloud.com/vocab#
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: oci
  uri: https://opencontainers.org/schema#
- prefix: wasm
  uri: https://webassembly.github.io/spec/core/vocab#
properties:
- container: ''
  name: name
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: version
  type: string
- container: ''
  name: annotations
  type: ''
- container: ''
  name: metadata
  type: ''
- container: ''
  name: apiVersion
  type: string
- container: ''
  name: kind
  type: string
- container: ''
  name: spec
  type: ''
- container: set
  name: components
  type: ''
- container: set
  name: traits
  type: ''
- container: ''
  name: properties
  type: ''
- container: ''
  name: image
  type: reference
- container: ''
  name: id
  type: string
- container: ''
  name: type
  type: string
- container: set
  name: config
  type: ''
- container: set
  name: secrets
  type: ''
- container: ''
  name: replicas
  type: integer
- container: set
  name: spread
  type: ''
- container: ''
  name: requirements
  type: ''
- container: ''
  name: weight
  type: integer
- container: ''
  name: source_id
  type: string
- container: ''
  name: target
  type: ''
- container: ''
  name: namespace
  type: string
- container: ''
  name: package
  type: string
- container: set
  name: interfaces
  type: ''
- container: ''
  name: host_id
  type: string
- container: ''
  name: friendly_name
  type: string
- container: ''
  name: uptime_seconds
  type: integer
- container: set
  name: labels
  type: ''
- container: set
  name: providers
  type: ''
- container: ''
  name: accepted
  type: boolean
- container: ''
  name: error
  type: string
- container: ''
  name: url
  type: reference
- container: ''
  name: created
  type: date
- container: ''
  name: modified
  type: date
property_count: 35
provider_name: wasmCloud
provider_slug: wasmcloud
slug: wasmcloud-context
source_filename: wasmcloud-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"wasmcloud\": \"https://wasmcloud.com/vocab#\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"oci\": \"https://opencontainers.org/schema#\",\n    \"wasm\": \"https://webassembly.github.io/spec/core/vocab#\",\n\n    \"Application\": \"wasmcloud:Application\",\n    \"Component\": \"wasmcloud:Component\",\n    \"CapabilityProvider\": \"wasmcloud:CapabilityProvider\",\n    \"LinkDefinition\": \"wasmcloud:LinkDefinition\",\n    \"Host\": \"wasmcloud:Host\",\n    \"Lattice\": \"wasmcloud:Lattice\",\n    \"Trait\": \"wasmcloud:Trait\",\n    \"SpreadScaler\": \"wasmcloud:SpreadScaler\",\n\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"version\": {\n      \"@id\": \"schema:softwareVersion\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"annotations\": {\n      \"@id\": \"wasmcloud:annotations\"\n    },\n    \"metadata\": {\n      \"@id\": \"wasmcloud:metadata\"\n    },\n\n    \"apiVersion\": {\n      \"@id\": \"wasmcloud:apiVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"kind\": {\n      \"@id\": \"wasmcloud:kind\",\n      \"@type\": \"xsd:string\"\n    },\n    \"spec\": {\n      \"@id\": \"wasmcloud:spec\"\n    },\n    \"components\": {\n      \"@id\": \"wasmcloud:components\",\n      \"@container\": \"@set\"\n    },\n    \"traits\": {\n      \"@id\": \"wasmcloud:traits\",\n      \"@container\": \"@set\"\n    },\n    \"properties\": {\n      \"@id\": \"wasmcloud:properties\"\n    },\n\n    \"image\": {\n      \"@id\": \"oci:imageRepository\",\n      \"@type\": \"@id\"\n    },\n    \"id\": {\n      \"@id\": \"dcterms:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"wasmcloud:componentType\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"config\": {\n      \"@id\": \"wasmcloud:config\",\n      \"@container\": \"@set\"\n    },\n    \"secrets\": {\n      \"@id\": \"wasmcloud:secrets\",\n      \"@container\": \"@set\"\n    },\n\n    \"replicas\": {\n      \"@id\": \"wasmcloud:replicas\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"spread\": {\n      \"@id\": \"wasmcloud:spread\",\n      \"@container\": \"@set\"\n    },\n    \"requirements\": {\n      \"@id\": \"wasmcloud:requirements\"\n    },\n    \"weight\": {\n      \"@id\": \"wasmcloud:weight\",\n      \"@type\": \"xsd:integer\"\n    },\n\n    \"source_id\": {\n      \"@id\": \"wasmcloud:sourceId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"target\": {\n      \"@id\": \"wasmcloud:target\"\n    },\n    \"namespace\": {\n      \"@id\": \"wasmcloud:witNamespace\",\n      \"@type\": \"xsd:string\"\n    },\n    \"package\": {\n      \"@id\": \"wasmcloud:witPackage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"interfaces\": {\n      \"@id\":\
  \ \"wasmcloud:witInterfaces\",\n      \"@container\": \"@set\"\n    },\n\n    \"host_id\": {\n      \"@id\": \"wasmcloud:hostId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"friendly_name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"uptime_seconds\": {\n      \"@id\": \"wasmcloud:uptimeSeconds\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"labels\": {\n      \"@id\": \"schema:keywords\",\n      \"@container\": \"@set\"\n    },\n    \"providers\": {\n      \"@id\": \"wasmcloud:providers\",\n      \"@container\": \"@set\"\n    },\n\n    \"accepted\": {\n      \"@id\": \"wasmcloud:accepted\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"error\": {\n      \"@id\": \"schema:error\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"url\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    },\n    \"created\": {\n      \"@id\": \"dcterms:created\",\n      \"@type\": \"xsd:date\"\n    },\n    \"modified\": {\n      \"@id\":\
  \ \"dcterms:modified\",\n      \"@type\": \"xsd:date\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/wasmcloud/refs/heads/main/json-ld/wasmcloud-context.jsonld
tags:
- Cloud Native
- CNCF
- Distributed Systems
- Incubating
- Runtime
- Wasm
- WebAssembly
- WIT
- JSON-LD
- Linked Data
- Semantic Web
---
