---
class_count: 18
classes:
- SoftwareApplication
- SDKGenerator
- SDK
- DocumentationSite
- MCPServer
- TerraformProvider
- CLI
- name
- description
- url
- version
- language
- license
- targetLanguage
- retryPolicy
- pagination
- streaming
- authentication
context_file: json-ld/stainless-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/stainless/refs/heads/main/json-ld/stainless-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Stainless from Stainless.
layout: jsonld
name: Stainless Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: stainless
  uri: https://stainless.com/vocab/
- prefix: openapi
  uri: https://spec.openapis.org/oas/v3.1.0#
properties:
- container: ''
  name: inputSpec
  type: reference
- container: set
  name: outputLanguages
  type: ''
- container: ''
  name: customer
  type: schema:Organization
- container: set
  name: integrations
  type: ''
property_count: 4
provider_name: Stainless
provider_slug: stainless
slug: stainless-context
source_filename: stainless-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"stainless\": \"https://stainless.com/vocab/\",\n    \"openapi\": \"https://spec.openapis.org/oas/v3.1.0#\",\n\n    \"SoftwareApplication\": \"schema:SoftwareApplication\",\n    \"SDKGenerator\": \"stainless:SDKGenerator\",\n    \"SDK\": \"stainless:SDK\",\n    \"DocumentationSite\": \"stainless:DocumentationSite\",\n    \"MCPServer\": \"stainless:MCPServer\",\n    \"TerraformProvider\": \"stainless:TerraformProvider\",\n    \"CLI\": \"stainless:CLI\",\n\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"version\": \"schema:version\",\n    \"language\": \"schema:programmingLanguage\",\n    \"license\": \"schema:license\",\n\n    \"inputSpec\": {\n      \"@id\": \"stainless:inputSpec\",\n      \"@type\": \"@id\"\n    },\n    \"outputLanguages\": {\n      \"@id\": \"stainless:outputLanguages\"\
  ,\n      \"@container\": \"@set\"\n    },\n    \"targetLanguage\": \"stainless:targetLanguage\",\n    \"retryPolicy\": \"stainless:retryPolicy\",\n    \"pagination\": \"stainless:pagination\",\n    \"streaming\": \"stainless:streaming\",\n    \"authentication\": \"stainless:authentication\",\n\n    \"customer\": {\n      \"@id\": \"schema:customer\",\n      \"@type\": \"schema:Organization\"\n    },\n    \"integrations\": {\n      \"@id\": \"schema:additionalProperty\",\n      \"@container\": \"@set\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/stainless/refs/heads/main/json-ld/stainless-context.jsonld
tags:
- Code Generation
- Documentation
- Developer Experience
- MCP
- Platform
- SDKs
- Terraform
- JSON-LD
- Linked Data
- Semantic Web
---
