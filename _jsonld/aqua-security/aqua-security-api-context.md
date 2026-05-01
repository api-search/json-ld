---
api_specs:
- filename: aqua-security-api.yaml
  format: yaml
  label: Aqua Security
  slug: aqua-security
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/aqua-security/refs/heads/main/openapi/aqua-security-api.yaml
class_count: 20
classes:
- LoginRequest
- LoginResponse
- ErrorResponse
- VulnerabilityCounts
- Image
- ImageList
- ImageRequest
- Container
- ContainerList
- Policy
- PolicyList
- PolicyRequest
- Registry
- RegistryList
- User
- UserList
- description
- email
- name
- url
context_file: json-ld/aqua-security-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/aqua-security/refs/heads/main/json-ld/aqua-security-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Aqua Security Api from Aqua Security.
layout: jsonld
name: Aqua Security Api Context
namespaces:
- prefix: aqua
  uri: https://aquasec.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: blockFailed
  type: boolean
- container: ''
  name: code
  type: integer
- container: ''
  name: containerId
  type: string
- container: ''
  name: count
  type: integer
- container: ''
  name: critical
  type: integer
- container: ''
  name: digest
  type: string
- container: ''
  name: disallowed
  type: boolean
- container: ''
  name: high
  type: integer
- container: ''
  name: host
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: image
  type: string
- container: ''
  name: low
  type: integer
- container: ''
  name: maximumScore
  type: decimal
- container: ''
  name: medium
  type: integer
- container: ''
  name: message
  type: string
- container: ''
  name: negligible
  type: integer
- container: ''
  name: password
  type: string
- container: ''
  name: policy
  type: string
- container: ''
  name: registry
  type: string
- container: set
  name: result
  type: string
- container: ''
  name: role
  type: string
- container: ''
  name: scanStatus
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: tag
  type: string
- container: ''
  name: token
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: username
  type: string
- container: ''
  name: vulnerabilities
  type: string
property_count: 28
provider_name: Aqua Security
provider_slug: aqua-security
slug: aqua-security-api-context
source_filename: aqua-security-api-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aqua\": \"https://aquasec.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"LoginRequest\": \"aqua:LoginRequest\",\n    \"LoginResponse\": \"aqua:LoginResponse\",\n    \"ErrorResponse\": \"aqua:ErrorResponse\",\n    \"VulnerabilityCounts\": \"aqua:VulnerabilityCounts\",\n    \"Image\": \"aqua:Image\",\n    \"ImageList\": \"aqua:ImageList\",\n    \"ImageRequest\": \"aqua:ImageRequest\",\n    \"Container\": \"aqua:Container\",\n    \"ContainerList\": \"aqua:ContainerList\",\n    \"Policy\": \"aqua:Policy\",\n    \"PolicyList\": \"aqua:PolicyList\",\n    \"PolicyRequest\": \"aqua:PolicyRequest\",\n    \"Registry\": \"aqua:Registry\",\n    \"RegistryList\": \"aqua:RegistryList\",\n    \"User\": \"aqua:User\",\n    \"UserList\": \"aqua:UserList\",\n    \"blockFailed\": {\n      \"@id\": \"aqua:block_failed\",\n  \
  \    \"@type\": \"xsd:boolean\"\n    },\n    \"code\": {\n      \"@id\": \"aqua:code\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"containerId\": {\n      \"@id\": \"aqua:container_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"count\": {\n      \"@id\": \"aqua:count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"critical\": {\n      \"@id\": \"aqua:critical\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"description\": \"schema:description\",\n    \"digest\": {\n      \"@id\": \"aqua:digest\",\n      \"@type\": \"xsd:string\"\n    },\n    \"disallowed\": {\n      \"@id\": \"aqua:disallowed\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"email\": \"schema:email\",\n    \"high\": {\n      \"@id\": \"aqua:high\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"host\": {\n      \"@id\": \"aqua:host\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"aqua:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"image\": {\n      \"@id\": \"\
  aqua:image\",\n      \"@type\": \"xsd:string\"\n    },\n    \"low\": {\n      \"@id\": \"aqua:low\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"maximumScore\": {\n      \"@id\": \"aqua:maximum_score\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"medium\": {\n      \"@id\": \"aqua:medium\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"message\": {\n      \"@id\": \"aqua:message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"negligible\": {\n      \"@id\": \"aqua:negligible\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"password\": {\n      \"@id\": \"aqua:password\",\n      \"@type\": \"xsd:string\"\n    },\n    \"policy\": {\n      \"@id\": \"aqua:policy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"registry\": {\n      \"@id\": \"aqua:registry\",\n      \"@type\": \"xsd:string\"\n    },\n    \"result\": {\n      \"@id\": \"aqua:result\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"role\"\
  : {\n      \"@id\": \"aqua:role\",\n      \"@type\": \"xsd:string\"\n    },\n    \"scanStatus\": {\n      \"@id\": \"aqua:scan_status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"aqua:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tag\": {\n      \"@id\": \"aqua:tag\",\n      \"@type\": \"xsd:string\"\n    },\n    \"token\": {\n      \"@id\": \"aqua:token\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"aqua:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"url\": \"schema:url\",\n    \"username\": {\n      \"@id\": \"aqua:username\",\n      \"@type\": \"xsd:string\"\n    },\n    \"vulnerabilities\": {\n      \"@id\": \"aqua:vulnerabilities\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/aqua-security/refs/heads/main/json-ld/aqua-security-api-context.jsonld
tags:
- Cloud Native
- Containers
- Kubernetes
- Runtime Protection
- Security
- Vulnerability Scanning
- JSON-LD
- Linked Data
- Semantic Web
---
