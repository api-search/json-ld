---
api_specs:
- filename: aws-app-mesh-openapi.yaml
  format: yaml
  label: AWS App Mesh API
  slug: aws-app-mesh-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/aws-app-mesh/refs/heads/main/openapi/aws-app-mesh-openapi.yaml
class_count: 5
classes:
- TlsValidationContextSdsTrust
- TlsValidationContextTrust
- TlsValidationContextAcmTrust
- TlsValidationContext
- TlsValidationContextFileTrust
context_file: json-ld/aws-app-mesh-tls-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/aws-app-mesh/refs/heads/main/json-ld/aws-app-mesh-tls-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Aws App Mesh Tls from AWS App Mesh.
layout: jsonld
name: Aws App Mesh Tls Context
namespaces:
- prefix: aws
  uri: https://aws.amazon.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: subjectAlternativeNames
  type: string
- container: ''
  name: trust
  type: string
- container: ''
  name: certificateChain
  type: string
- container: ''
  name: secretName
  type: string
- container: ''
  name: acm
  type: string
- container: ''
  name: file
  type: string
- container: ''
  name: sds
  type: string
- container: ''
  name: certificateAuthorityArns
  type: string
property_count: 8
provider_name: AWS App Mesh
provider_slug: aws-app-mesh
slug: aws-app-mesh-tls-context
source_filename: aws-app-mesh-tls-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aws\": \"https://aws.amazon.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"TlsValidationContextSdsTrust\": \"aws:TlsValidationContextSdsTrust\",\n    \"TlsValidationContextTrust\": \"aws:TlsValidationContextTrust\",\n    \"TlsValidationContextAcmTrust\": \"aws:TlsValidationContextAcmTrust\",\n    \"TlsValidationContext\": \"aws:TlsValidationContext\",\n    \"TlsValidationContextFileTrust\": \"aws:TlsValidationContextFileTrust\",\n    \"subjectAlternativeNames\": {\n      \"@id\": \"aws:subjectAlternativeNames\",\n      \"@type\": \"xsd:string\"\n    },\n    \"trust\": {\n      \"@id\": \"aws:trust\",\n      \"@type\": \"xsd:string\"\n    },\n    \"certificateChain\": {\n      \"@id\": \"aws:certificateChain\",\n      \"@type\": \"xsd:string\"\n    },\n    \"secretName\": {\n      \"@id\": \"aws:secretName\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"acm\": {\n      \"@id\": \"aws:acm\",\n      \"@type\": \"xsd:string\"\n    },\n    \"file\": {\n      \"@id\": \"aws:file\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sds\": {\n      \"@id\": \"aws:sds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"certificateAuthorityArns\": {\n      \"@id\": \"aws:certificateAuthorityArns\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/aws-app-mesh/refs/heads/main/json-ld/aws-app-mesh-tls-context.jsonld
tags:
- Deprecated
- Envoy
- Microservices
- Networking
- Service Mesh
- JSON-LD
- Linked Data
- Semantic Web
---
