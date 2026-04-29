---
class_count: 9
classes:
- WorkloadSpec
- ServiceDependency
- ComponentModel
- ResourceDiscovery
- ApplicationBundle
- name
- description
- version
- url
context_file: json-ld/application-research-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/application-research/refs/heads/main/json-ld/application-research-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Application Research from Application Research.
layout: jsonld
name: Application Research Context
namespaces:
- prefix: appdeps
  uri: https://application-research.dev/schema/
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
  name: kind
  type: string
- container: ''
  name: metadata
  type: reference
- container: ''
  name: spec
  type: reference
- container: set
  name: services
  type: ''
- container: set
  name: dependencies
  type: ''
- container: set
  name: containers
  type: ''
- container: set
  name: resources
  type: ''
- container: ''
  name: namespace
  type: string
- container: ''
  name: platform
  type: string
- container: ''
  name: image
  type: string
- container: ''
  name: port
  type: integer
- container: ''
  name: replicas
  type: integer
- container: set
  name: environment
  type: ''
- container: ''
  name: labels
  type: reference
- container: ''
  name: annotations
  type: reference
property_count: 16
provider_name: Application Research
provider_slug: application-research
slug: application-research-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"appdeps\": \"https://application-research.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"WorkloadSpec\": \"appdeps:WorkloadSpec\",\n    \"ServiceDependency\": \"appdeps:ServiceDependency\",\n    \"ComponentModel\": \"appdeps:ComponentModel\",\n    \"ResourceDiscovery\": \"appdeps:ResourceDiscovery\",\n    \"ApplicationBundle\": \"appdeps:ApplicationBundle\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"version\": \"schema:version\",\n    \"url\": \"schema:url\",\n    \"apiVersion\": {\n      \"@id\": \"appdeps:apiVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"kind\": {\n      \"@id\": \"appdeps:kind\",\n      \"@type\": \"xsd:string\"\n    },\n    \"metadata\": {\n      \"@id\": \"appdeps:metadata\",\n      \"@type\": \"@id\"\n    },\n    \"spec\": {\n  \
  \    \"@id\": \"appdeps:spec\",\n      \"@type\": \"@id\"\n    },\n    \"services\": {\n      \"@id\": \"appdeps:services\",\n      \"@container\": \"@set\"\n    },\n    \"dependencies\": {\n      \"@id\": \"appdeps:dependencies\",\n      \"@container\": \"@set\"\n    },\n    \"containers\": {\n      \"@id\": \"appdeps:containers\",\n      \"@container\": \"@set\"\n    },\n    \"resources\": {\n      \"@id\": \"appdeps:resources\",\n      \"@container\": \"@set\"\n    },\n    \"namespace\": {\n      \"@id\": \"appdeps:namespace\",\n      \"@type\": \"xsd:string\"\n    },\n    \"platform\": {\n      \"@id\": \"appdeps:platform\",\n      \"@type\": \"xsd:string\"\n    },\n    \"image\": {\n      \"@id\": \"appdeps:image\",\n      \"@type\": \"xsd:string\"\n    },\n    \"port\": {\n      \"@id\": \"appdeps:port\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"replicas\": {\n      \"@id\": \"appdeps:replicas\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"environment\": {\n      \"\
  @id\": \"appdeps:environment\",\n      \"@container\": \"@set\"\n    },\n    \"labels\": {\n      \"@id\": \"appdeps:labels\",\n      \"@type\": \"@id\"\n    },\n    \"annotations\": {\n      \"@id\": \"appdeps:annotations\",\n      \"@type\": \"@id\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/application-research/refs/heads/main/json-ld/application-research-context.jsonld
tags:
- Application Dependencies
- Cloud Native
- Integration
- Research
- Specifications
- Workload Specifications
- JSON-LD
- Linked Data
- Semantic Web
---
