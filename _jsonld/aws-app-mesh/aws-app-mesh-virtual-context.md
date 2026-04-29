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
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aws\": \"https://aws.amazon.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"VirtualGatewayHttpConnectionPool\": \"aws:VirtualGatewayHttpConnectionPool\",\n    \"VirtualGatewayBackendDefaults\": \"aws:VirtualGatewayBackendDefaults\",\n    \"VirtualNodeStatus\": \"aws:VirtualNodeStatus\",\n    \"VirtualNodeConnectionPool\": \"aws:VirtualNodeConnectionPool\",\n    \"VirtualGatewayListenerTlsFileCertificate\": \"aws:VirtualGatewayListenerTlsFileCertificate\",\n    \"VirtualGatewayTlsValidationContextTrust\": \"aws:VirtualGatewayTlsValidationContextTrust\",\n    \"VirtualGatewayListener\": \"aws:VirtualGatewayListener\",\n    \"VirtualGatewayListenerTlsValidationContext\": \"aws:VirtualGatewayListenerTlsValidationContext\",\n    \"VirtualGatewayClientPolicy\": \"aws:VirtualGatewayClientPolicy\",\n    \"VirtualGatewayClientTlsCertificate\"\
  : \"aws:VirtualGatewayClientTlsCertificate\",\n    \"VirtualGatewayRef\": \"aws:VirtualGatewayRef\",\n    \"VirtualGatewayGrpcConnectionPool\": \"aws:VirtualGatewayGrpcConnectionPool\",\n    \"VirtualRouterListener\": \"aws:VirtualRouterListener\",\n    \"VirtualGatewayTlsValidationContext\": \"aws:VirtualGatewayTlsValidationContext\",\n    \"VirtualGatewayPortMapping\": \"aws:VirtualGatewayPortMapping\",\n    \"VirtualServiceBackend\": \"aws:VirtualServiceBackend\",\n    \"VirtualRouterData\": \"aws:VirtualRouterData\",\n    \"VirtualServiceProvider\": \"aws:VirtualServiceProvider\",\n    \"VirtualGatewayFileAccessLog\": \"aws:VirtualGatewayFileAccessLog\",\n    \"VirtualGatewayConnectionPool\": \"aws:VirtualGatewayConnectionPool\",\n    \"VirtualGatewaySpec\": \"aws:VirtualGatewaySpec\",\n    \"VirtualGatewayHealthCheckPolicy\": \"aws:VirtualGatewayHealthCheckPolicy\",\n    \"VirtualRouterRef\": \"aws:VirtualRouterRef\",\n    \"VirtualGatewayListenerTlsValidationContextTrust\": \"aws:VirtualGatewayListenerTlsValidationContextTrust\"\
  ,\n    \"VirtualNodeRef\": \"aws:VirtualNodeRef\",\n    \"VirtualRouterSpec\": \"aws:VirtualRouterSpec\",\n    \"VirtualRouterServiceProvider\": \"aws:VirtualRouterServiceProvider\",\n    \"VirtualGatewayTlsValidationContextFileTrust\": \"aws:VirtualGatewayTlsValidationContextFileTrust\",\n    \"VirtualGatewayTlsValidationContextAcmTrust\": \"aws:VirtualGatewayTlsValidationContextAcmTrust\",\n    \"VirtualRouterStatus\": \"aws:VirtualRouterStatus\",\n    \"VirtualServiceSpec\": \"aws:VirtualServiceSpec\",\n    \"VirtualServiceData\": \"aws:VirtualServiceData\",\n    \"VirtualServiceRef\": \"aws:VirtualServiceRef\",\n    \"VirtualGatewayStatus\": \"aws:VirtualGatewayStatus\",\n    \"VirtualGatewayLogging\": \"aws:VirtualGatewayLogging\",\n    \"VirtualGatewayListenerTls\": \"aws:VirtualGatewayListenerTls\",\n    \"VirtualNodeHttpConnectionPool\": \"aws:VirtualNodeHttpConnectionPool\",\n    \"VirtualGatewayListenerTlsSdsCertificate\": \"aws:VirtualGatewayListenerTlsSdsCertificate\",\n  \
  \  \"VirtualNodeData\": \"aws:VirtualNodeData\",\n    \"VirtualGatewayData\": \"aws:VirtualGatewayData\",\n    \"VirtualGatewayTlsValidationContextSdsTrust\": \"aws:VirtualGatewayTlsValidationContextSdsTrust\",\n    \"VirtualGatewayListenerTlsAcmCertificate\": \"aws:VirtualGatewayListenerTlsAcmCertificate\",\n    \"VirtualServiceStatus\": \"aws:VirtualServiceStatus\",\n    \"VirtualNodeServiceProvider\": \"aws:VirtualNodeServiceProvider\",\n    \"VirtualGatewayHttp2ConnectionPool\": \"aws:VirtualGatewayHttp2ConnectionPool\",\n    \"VirtualGatewayClientPolicyTls\": \"aws:VirtualGatewayClientPolicyTls\",\n    \"VirtualNodeGrpcConnectionPool\": \"aws:VirtualNodeGrpcConnectionPool\",\n    \"VirtualNodeSpec\": \"aws:VirtualNodeSpec\",\n    \"VirtualNodeHttp2ConnectionPool\": \"aws:VirtualNodeHttp2ConnectionPool\",\n    \"VirtualGatewayListenerTlsCertificate\": \"aws:VirtualGatewayListenerTlsCertificate\",\n    \"VirtualNodeTcpConnectionPool\": \"aws:VirtualNodeTcpConnectionPool\",\n    \"VirtualGatewayAccessLog\"\
  : \"aws:VirtualGatewayAccessLog\",\n    \"meshName\": {\n      \"@id\": \"aws:meshName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"metadata\": {\n      \"@id\": \"aws:metadata\",\n      \"@type\": \"xsd:string\"\n    },\n    \"spec\": {\n      \"@id\": \"aws:spec\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"aws:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"virtualRouterName\": {\n      \"@id\": \"aws:virtualRouterName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"clientPolicy\": {\n      \"@id\": \"aws:clientPolicy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"certificateAuthorityArns\": {\n      \"@id\": \"aws:certificateAuthorityArns\",\n      \"@type\": \"xsd:string\"\n    },\n    \"certificate\": {\n      \"@id\": \"aws:certificate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mode\": {\n      \"@id\": \"aws:mode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"validation\": {\n      \"@id\": \"aws:validation\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"subjectAlternativeNames\": {\n      \"@id\": \"aws:subjectAlternativeNames\",\n      \"@type\": \"xsd:string\"\n    },\n    \"trust\": {\n      \"@id\": \"aws:trust\",\n      \"@type\": \"xsd:string\"\n    },\n    \"secretName\": {\n      \"@id\": \"aws:secretName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"portMapping\": {\n      \"@id\": \"aws:portMapping\",\n      \"@type\": \"@id\"\n    },\n    \"maxRequests\": {\n      \"@id\": \"aws:maxRequests\",\n      \"@type\": \"xsd:string\"\n    },\n    \"certificateChain\": {\n      \"@id\": \"aws:certificateChain\",\n      \"@type\": \"xsd:string\"\n    },\n    \"provider\": {\n      \"@id\": \"aws:provider\",\n      \"@type\": \"xsd:string\"\n    },\n    \"grpc\": {\n      \"@id\": \"aws:grpc\",\n      \"@type\": \"xsd:string\"\n    },\n    \"http\": {\n      \"@id\": \"aws:http\",\n      \"@type\": \"xsd:string\"\n    },\n    \"http2\": {\n      \"@id\": \"aws:http2\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"backendDefaults\": {\n      \"@id\": \"aws:backendDefaults\",\n      \"@type\": \"xsd:string\"\n    },\n    \"backends\": {\n      \"@id\": \"aws:backends\",\n      \"@type\": \"xsd:string\"\n    },\n    \"listeners\": {\n      \"@id\": \"aws:listeners\",\n      \"@type\": \"xsd:string\"\n    },\n    \"logging\": {\n      \"@id\": \"aws:logging\",\n      \"@type\": \"xsd:string\"\n    },\n    \"serviceDiscovery\": {\n      \"@id\": \"aws:serviceDiscovery\",\n      \"@type\": \"xsd:string\"\n    },\n    \"arn\": {\n      \"@id\": \"aws:arn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdAt\": {\n      \"@id\": \"aws:createdAt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastUpdatedAt\": {\n      \"@id\": \"aws:lastUpdatedAt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"meshOwner\": {\n      \"@id\": \"aws:meshOwner\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resourceOwner\": {\n      \"@id\": \"aws:resourceOwner\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"version\": \"schema:version\",\n    \"virtualServiceName\": {\n      \"@id\": \"aws:virtualServiceName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"port\": {\n      \"@id\": \"aws:port\",\n      \"@type\": \"xsd:string\"\n    },\n    \"protocol\": {\n      \"@id\": \"aws:protocol\",\n      \"@type\": \"xsd:string\"\n    },\n    \"enforce\": {\n      \"@id\": \"aws:enforce\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ports\": {\n      \"@id\": \"aws:ports\",\n      \"@type\": \"xsd:string\"\n    },\n    \"certificateArn\": {\n      \"@id\": \"aws:certificateArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"virtualGatewayName\": {\n      \"@id\": \"aws:virtualGatewayName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"virtualNodeName\": {\n      \"@id\": \"aws:virtualNodeName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"file\": {\n      \"@id\": \"aws:file\",\n      \"@type\": \"xsd:string\"\n    },\n    \"virtualNode\": {\n     \
  \ \"@id\": \"aws:virtualNode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"virtualRouter\": {\n      \"@id\": \"aws:virtualRouter\",\n      \"@type\": \"xsd:string\"\n    },\n    \"maxConnections\": {\n      \"@id\": \"aws:maxConnections\",\n      \"@type\": \"xsd:string\"\n    },\n    \"maxPendingRequests\": {\n      \"@id\": \"aws:maxPendingRequests\",\n      \"@type\": \"xsd:string\"\n    },\n    \"format\": {\n      \"@id\": \"aws:format\",\n      \"@type\": \"xsd:string\"\n    },\n    \"path\": {\n      \"@id\": \"aws:path\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sds\": {\n      \"@id\": \"aws:sds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accessLog\": {\n      \"@id\": \"aws:accessLog\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tls\": {\n      \"@id\": \"aws:tls\",\n      \"@type\": \"xsd:string\"\n    },\n    \"connectionPool\": {\n      \"@id\": \"aws:connectionPool\",\n      \"@type\": \"xsd:string\"\n    },\n    \"healthCheck\": {\n      \"@id\"\
  : \"aws:healthCheck\",\n      \"@type\": \"xsd:string\"\n    },\n    \"acm\": {\n      \"@id\": \"aws:acm\",\n      \"@type\": \"xsd:string\"\n    },\n    \"healthyThreshold\": {\n      \"@id\": \"aws:healthyThreshold\",\n      \"@type\": \"xsd:string\"\n    },\n    \"intervalMillis\": {\n      \"@id\": \"aws:intervalMillis\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timeoutMillis\": {\n      \"@id\": \"aws:timeoutMillis\",\n      \"@type\": \"xsd:string\"\n    },\n    \"unhealthyThreshold\": {\n      \"@id\": \"aws:unhealthyThreshold\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tcp\": {\n      \"@id\": \"aws:tcp\",\n      \"@type\": \"xsd:string\"\n    },\n    \"privateKey\": {\n      \"@id\": \"aws:privateKey\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/aws-app-mesh/refs/heads/main/json-ld/aws-app-mesh-virtual-context.jsonld
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
