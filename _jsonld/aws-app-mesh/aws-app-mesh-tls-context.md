---
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
tags:
- AWS
- Deprecated
- Envoy
- Microservices
- Networking
- Service Mesh
- JSON-LD
- Linked Data
- Semantic Web
---
