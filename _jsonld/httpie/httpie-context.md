---
api_specs:
- filename: httpie-httpie-openapi.yml
  format: yaml
  label: HTTPie
  slug: httpie
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/httpie/refs/heads/main/openapi/httpie-httpie-openapi.yml
class_count: 22
classes:
- name
- description
- url
- version
- Request
- Response
- Session
- method
- statusCode
- headers
- body
- auth
- cookies
- elapsed
- timeout
- host
- queryParams
- contentType
- encoding
- verify
- SoftwareApplication
- APIClient
context_file: json-ld/httpie-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/httpie/refs/heads/main/json-ld/httpie-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Httpie from HTTPie.
layout: jsonld
name: Httpie Context
namespaces:
- prefix: httpie
  uri: https://httpie.io/ns#
properties: []
property_count: 0
provider_name: HTTPie
provider_slug: httpie
slug: httpie-context
source_filename: httpie-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"httpie\": \"https://httpie.io/ns#\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"version\": \"schema:softwareVersion\",\n    \"Request\": \"httpie:Request\",\n    \"Response\": \"httpie:Response\",\n    \"Session\": \"httpie:Session\",\n    \"method\": \"httpie:method\",\n    \"statusCode\": \"httpie:statusCode\",\n    \"headers\": \"httpie:headers\",\n    \"body\": \"httpie:body\",\n    \"auth\": \"httpie:auth\",\n    \"cookies\": \"httpie:cookies\",\n    \"elapsed\": \"httpie:elapsed\",\n    \"timeout\": \"httpie:timeout\",\n    \"host\": \"httpie:host\",\n    \"queryParams\": \"httpie:queryParams\",\n    \"contentType\": \"httpie:contentType\",\n    \"encoding\": \"httpie:encoding\",\n    \"verify\": \"httpie:verify\",\n    \"SoftwareApplication\": \"schema:SoftwareApplication\",\n    \"APIClient\": \"httpie:APIClient\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/httpie/refs/heads/main/json-ld/httpie-context.jsonld
tags:
- API Client
- API Testing
- CLI
- Client
- Command Line
- Developer Tools
- HTTP
- Open Source
- Sessions
- JSON-LD
- Linked Data
- Semantic Web
---
