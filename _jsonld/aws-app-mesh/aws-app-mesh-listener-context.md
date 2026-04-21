---
class_count: 9
classes:
- ListenerTlsCertificate
- ListenerTimeout
- ListenerTlsFileCertificate
- ListenerTlsSdsCertificate
- ListenerTlsValidationContextTrust
- ListenerTls
- ListenerTlsValidationContext
- ListenerTlsAcmCertificate
- Listener
context_file: json-ld/aws-app-mesh-listener-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/aws-app-mesh/refs/heads/main/json-ld/aws-app-mesh-listener-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Aws App Mesh Listener from AWS App Mesh.
layout: jsonld
name: Aws App Mesh Listener Context
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
  name: acm
  type: string
- container: ''
  name: file
  type: string
- container: ''
  name: sds
  type: string
- container: ''
  name: connectionPool
  type: string
- container: ''
  name: healthCheck
  type: string
- container: ''
  name: outlierDetection
  type: string
- container: ''
  name: portMapping
  type: string
- container: ''
  name: timeout
  type: string
- container: ''
  name: tls
  type: string
- container: ''
  name: certificate
  type: string
- container: ''
  name: mode
  type: string
- container: ''
  name: validation
  type: string
- container: ''
  name: secretName
  type: string
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
  name: privateKey
  type: string
- container: ''
  name: grpc
  type: string
- container: ''
  name: http
  type: string
- container: ''
  name: http2
  type: string
- container: ''
  name: tcp
  type: string
- container: ''
  name: certificateArn
  type: string
property_count: 22
provider_name: AWS App Mesh
provider_slug: aws-app-mesh
slug: aws-app-mesh-listener-context
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
