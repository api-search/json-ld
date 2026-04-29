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
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aws\": \"https://aws.amazon.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ListenerTlsCertificate\": \"aws:ListenerTlsCertificate\",\n    \"ListenerTimeout\": \"aws:ListenerTimeout\",\n    \"ListenerTlsFileCertificate\": \"aws:ListenerTlsFileCertificate\",\n    \"ListenerTlsSdsCertificate\": \"aws:ListenerTlsSdsCertificate\",\n    \"ListenerTlsValidationContextTrust\": \"aws:ListenerTlsValidationContextTrust\",\n    \"ListenerTls\": \"aws:ListenerTls\",\n    \"ListenerTlsValidationContext\": \"aws:ListenerTlsValidationContext\",\n    \"ListenerTlsAcmCertificate\": \"aws:ListenerTlsAcmCertificate\",\n    \"Listener\": \"aws:Listener\",\n    \"acm\": {\n      \"@id\": \"aws:acm\",\n      \"@type\": \"xsd:string\"\n    },\n    \"file\": {\n      \"@id\": \"aws:file\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"sds\": {\n      \"@id\": \"aws:sds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"connectionPool\": {\n      \"@id\": \"aws:connectionPool\",\n      \"@type\": \"xsd:string\"\n    },\n    \"healthCheck\": {\n      \"@id\": \"aws:healthCheck\",\n      \"@type\": \"xsd:string\"\n    },\n    \"outlierDetection\": {\n      \"@id\": \"aws:outlierDetection\",\n      \"@type\": \"xsd:string\"\n    },\n    \"portMapping\": {\n      \"@id\": \"aws:portMapping\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timeout\": {\n      \"@id\": \"aws:timeout\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tls\": {\n      \"@id\": \"aws:tls\",\n      \"@type\": \"xsd:string\"\n    },\n    \"certificate\": {\n      \"@id\": \"aws:certificate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mode\": {\n      \"@id\": \"aws:mode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"validation\": {\n      \"@id\": \"aws:validation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"secretName\"\
  : {\n      \"@id\": \"aws:secretName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subjectAlternativeNames\": {\n      \"@id\": \"aws:subjectAlternativeNames\",\n      \"@type\": \"xsd:string\"\n    },\n    \"trust\": {\n      \"@id\": \"aws:trust\",\n      \"@type\": \"xsd:string\"\n    },\n    \"certificateChain\": {\n      \"@id\": \"aws:certificateChain\",\n      \"@type\": \"xsd:string\"\n    },\n    \"privateKey\": {\n      \"@id\": \"aws:privateKey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"grpc\": {\n      \"@id\": \"aws:grpc\",\n      \"@type\": \"xsd:string\"\n    },\n    \"http\": {\n      \"@id\": \"aws:http\",\n      \"@type\": \"xsd:string\"\n    },\n    \"http2\": {\n      \"@id\": \"aws:http2\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tcp\": {\n      \"@id\": \"aws:tcp\",\n      \"@type\": \"xsd:string\"\n    },\n    \"certificateArn\": {\n      \"@id\": \"aws:certificateArn\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/aws-app-mesh/refs/heads/main/json-ld/aws-app-mesh-listener-context.jsonld
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
