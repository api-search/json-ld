---
class_count: 15
classes:
- Namespace
- name
- description
- Service
- Instance
- HttpInstanceSummary
- ListNamespacesResponse
- ListServicesResponse
- CreateServiceRequest
- CreateServiceResponse
- ListInstancesResponse
- RegisterInstanceRequest
- RegisterInstanceResponse
- DiscoverInstancesRequest
- DiscoverInstancesResponse
context_file: json-ld/amazon-cloud-map-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-cloud-map/refs/heads/main/json-ld/amazon-cloud-map-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Cloud Map from Amazon Cloud Map.
layout: jsonld
name: Amazon Cloud Map Context
namespaces:
- prefix: cloudmap
  uri: https://aws.amazon.com/cloud-map/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: id
  type: string
- container: ''
  name: arn
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: createDate
  type: dateTime
- container: ''
  name: namespaceId
  type: string
- container: ''
  name: instanceCount
  type: integer
- container: ''
  name: attributes
  type: string
- container: ''
  name: instanceId
  type: string
- container: ''
  name: namespaceName
  type: string
- container: ''
  name: serviceName
  type: string
- container: ''
  name: healthStatus
  type: string
- container: set
  name: namespaces
  type: string
- container: ''
  name: nextToken
  type: string
- container: set
  name: services
  type: string
- container: ''
  name: dnsConfig
  type: string
- container: ''
  name: creatorRequestId
  type: string
- container: ''
  name: service
  type: string
- container: set
  name: instances
  type: string
- container: ''
  name: operationId
  type: string
- container: ''
  name: maxResults
  type: integer
property_count: 20
provider_name: Amazon Cloud Map
provider_slug: amazon-cloud-map
slug: amazon-cloud-map-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"cloudmap\": \"https://aws.amazon.com/cloud-map/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Namespace\": \"cloudmap:Namespace\",\n    \"id\": {\n      \"@id\": \"cloudmap:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"arn\": {\n      \"@id\": \"cloudmap:arn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"type\": {\n      \"@id\": \"cloudmap:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\",\n    \"createDate\": {\n      \"@id\": \"cloudmap:create_date\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"Service\": \"cloudmap:Service\",\n    \"namespaceId\": {\n      \"@id\": \"cloudmap:namespace_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"instanceCount\": {\n      \"@id\": \"cloudmap:instance_count\",\n      \"@type\"\
  : \"xsd:integer\"\n    },\n    \"Instance\": \"cloudmap:Instance\",\n    \"attributes\": {\n      \"@id\": \"cloudmap:attributes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"HttpInstanceSummary\": \"cloudmap:HttpInstanceSummary\",\n    \"instanceId\": {\n      \"@id\": \"cloudmap:instance_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"namespaceName\": {\n      \"@id\": \"cloudmap:namespace_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"serviceName\": {\n      \"@id\": \"cloudmap:service_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"healthStatus\": {\n      \"@id\": \"cloudmap:health_status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ListNamespacesResponse\": \"cloudmap:ListNamespacesResponse\",\n    \"namespaces\": {\n      \"@id\": \"cloudmap:namespaces\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nextToken\": {\n      \"@id\": \"cloudmap:next_token\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ListServicesResponse\"\
  : \"cloudmap:ListServicesResponse\",\n    \"services\": {\n      \"@id\": \"cloudmap:services\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreateServiceRequest\": \"cloudmap:CreateServiceRequest\",\n    \"dnsConfig\": {\n      \"@id\": \"cloudmap:dns_config\",\n      \"@type\": \"xsd:string\"\n    },\n    \"creatorRequestId\": {\n      \"@id\": \"cloudmap:creator_request_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreateServiceResponse\": \"cloudmap:CreateServiceResponse\",\n    \"service\": {\n      \"@id\": \"cloudmap:service\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ListInstancesResponse\": \"cloudmap:ListInstancesResponse\",\n    \"instances\": {\n      \"@id\": \"cloudmap:instances\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RegisterInstanceRequest\": \"cloudmap:RegisterInstanceRequest\",\n    \"RegisterInstanceResponse\": \"cloudmap:RegisterInstanceResponse\",\n    \"operationId\": {\n\
  \      \"@id\": \"cloudmap:operation_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DiscoverInstancesRequest\": \"cloudmap:DiscoverInstancesRequest\",\n    \"maxResults\": {\n      \"@id\": \"cloudmap:max_results\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"DiscoverInstancesResponse\": \"cloudmap:DiscoverInstancesResponse\"\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-cloud-map/refs/heads/main/json-ld/amazon-cloud-map-context.jsonld
tags:
- AWS
- Cloud Map
- Service Discovery
- Microservices
- DNS
- JSON-LD
- Linked Data
- Semantic Web
---
