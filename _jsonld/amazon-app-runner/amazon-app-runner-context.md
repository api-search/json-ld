---
api_specs:
- filename: amazon-app-runner-openapi.yaml
  format: yaml
  label: Amazon App Runner API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-app-runner/refs/heads/main/openapi/amazon-app-runner-openapi.yaml
class_count: 0
classes: []
context_file: json-ld/amazon-app-runner-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-app-runner/refs/heads/main/json-ld/amazon-app-runner-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon App Runner from Amazon App Runner.
layout: jsonld
name: Amazon App Runner Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
properties:
- container: ''
  name: DNSTarget
  type: string
- container: ''
  name: ServiceArn
  type: string
- container: ''
  name: CustomDomain
  type: string
- container: ''
  name: VpcDNSTargets
  type: string
property_count: 4
provider_name: Amazon App Runner
provider_slug: amazon-app-runner
slug: amazon-app-runner-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"DNSTarget\": {\n      \"@id\": \"schema:DNSTarget\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ServiceArn\": {\n      \"@id\": \"schema:ServiceArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CustomDomain\": {\n      \"@id\": \"schema:CustomDomain\",\n      \"@type\": \"xsd:string\"\n    },\n    \"VpcDNSTargets\": {\n      \"@id\": \"schema:VpcDNSTargets\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-app-runner/refs/heads/main/json-ld/amazon-app-runner-context.jsonld
tags:
- AWS
- CI/CD
- Containers
- Deployment
- Managed Service
- Serverless
- Web Applications
- JSON-LD
- Linked Data
- Semantic Web
---
