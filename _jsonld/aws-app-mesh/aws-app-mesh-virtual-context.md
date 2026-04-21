---
class_count: 53
classes:
- VirtualGatewayHttpConnectionPool
- VirtualGatewayBackendDefaults
- VirtualNodeStatus
- VirtualNodeConnectionPool
- VirtualGatewayListenerTlsFileCertificate
- VirtualGatewayTlsValidationContextTrust
- VirtualGatewayListener
- VirtualGatewayListenerTlsValidationContext
- VirtualGatewayClientPolicy
- VirtualGatewayClientTlsCertificate
- VirtualGatewayRef
- VirtualGatewayGrpcConnectionPool
- VirtualRouterListener
- VirtualGatewayTlsValidationContext
- VirtualGatewayPortMapping
- VirtualServiceBackend
- VirtualRouterData
- VirtualServiceProvider
- VirtualGatewayFileAccessLog
- VirtualGatewayConnectionPool
- VirtualGatewaySpec
- VirtualGatewayHealthCheckPolicy
- VirtualRouterRef
- VirtualGatewayListenerTlsValidationContextTrust
- VirtualNodeRef
- VirtualRouterSpec
- VirtualRouterServiceProvider
- VirtualGatewayTlsValidationContextFileTrust
- VirtualGatewayTlsValidationContextAcmTrust
- VirtualRouterStatus
- VirtualServiceSpec
- VirtualServiceData
- VirtualServiceRef
- VirtualGatewayStatus
- VirtualGatewayLogging
- VirtualGatewayListenerTls
- VirtualNodeHttpConnectionPool
- VirtualGatewayListenerTlsSdsCertificate
- VirtualNodeData
- VirtualGatewayData
- VirtualGatewayTlsValidationContextSdsTrust
- VirtualGatewayListenerTlsAcmCertificate
- VirtualServiceStatus
- VirtualNodeServiceProvider
- VirtualGatewayHttp2ConnectionPool
- VirtualGatewayClientPolicyTls
- VirtualNodeGrpcConnectionPool
- VirtualNodeSpec
- VirtualNodeHttp2ConnectionPool
- VirtualGatewayListenerTlsCertificate
- VirtualNodeTcpConnectionPool
- VirtualGatewayAccessLog
- version
context_file: json-ld/aws-app-mesh-virtual-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/aws-app-mesh/refs/heads/main/json-ld/aws-app-mesh-virtual-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Aws App Mesh Virtual from AWS App Mesh.
layout: jsonld
name: Aws App Mesh Virtual Context
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
  name: meshName
  type: string
- container: ''
  name: metadata
  type: string
- container: ''
  name: spec
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: virtualRouterName
  type: string
- container: ''
  name: clientPolicy
  type: string
- container: ''
  name: certificateAuthorityArns
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
  name: subjectAlternativeNames
  type: string
- container: ''
  name: trust
  type: string
- container: ''
  name: secretName
  type: string
- container: ''
  name: portMapping
  type: reference
- container: ''
  name: maxRequests
  type: string
- container: ''
  name: certificateChain
  type: string
- container: ''
  name: provider
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
  name: backendDefaults
  type: string
- container: ''
  name: backends
  type: string
- container: ''
  name: listeners
  type: string
- container: ''
  name: logging
  type: string
- container: ''
  name: serviceDiscovery
  type: string
- container: ''
  name: arn
  type: string
- container: ''
  name: createdAt
  type: string
- container: ''
  name: lastUpdatedAt
  type: string
- container: ''
  name: meshOwner
  type: string
- container: ''
  name: resourceOwner
  type: string
- container: ''
  name: virtualServiceName
  type: string
- container: ''
  name: port
  type: string
- container: ''
  name: protocol
  type: string
- container: ''
  name: enforce
  type: string
- container: ''
  name: ports
  type: string
- container: ''
  name: certificateArn
  type: string
- container: ''
  name: virtualGatewayName
  type: string
- container: ''
  name: virtualNodeName
  type: string
- container: ''
  name: file
  type: string
- container: ''
  name: virtualNode
  type: string
- container: ''
  name: virtualRouter
  type: string
- container: ''
  name: maxConnections
  type: string
- container: ''
  name: maxPendingRequests
  type: string
- container: ''
  name: format
  type: string
- container: ''
  name: path
  type: string
- container: ''
  name: sds
  type: string
- container: ''
  name: accessLog
  type: string
- container: ''
  name: tls
  type: string
- container: ''
  name: connectionPool
  type: string
- container: ''
  name: healthCheck
  type: string
- container: ''
  name: acm
  type: string
- container: ''
  name: healthyThreshold
  type: string
- container: ''
  name: intervalMillis
  type: string
- container: ''
  name: timeoutMillis
  type: string
- container: ''
  name: unhealthyThreshold
  type: string
- container: ''
  name: tcp
  type: string
- container: ''
  name: privateKey
  type: string
property_count: 57
provider_name: AWS App Mesh
provider_slug: aws-app-mesh
slug: aws-app-mesh-virtual-context
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
