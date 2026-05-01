---
api_specs:
- filename: Welcome.html
  format: yaml
  label: Amazon OpenSearch Service API
  slug: ''
  spec_type: OpenAPI
  url: https://docs.aws.amazon.com/opensearch-service/latest/APIReference/Welcome.html
class_count: 2
classes:
- CreateDomainRequest
- DomainStatus
context_file: json-ld/amazon-opensearch-service-openapi-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-opensearch-service/refs/heads/main/json-ld/amazon-opensearch-service-openapi-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Opensearch Service Openapi from Amazon OpenSearch Service.
layout: jsonld
name: Amazon Opensearch Service Openapi Context
namespaces:
- prefix: opensearch
  uri: https://opensearch.amazonaws.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: ARN
  type: string
- container: ''
  name: AccessPolicies
  type: string
- container: ''
  name: ClusterConfig
  type: reference
- container: ''
  name: Created
  type: boolean
- container: ''
  name: Deleted
  type: boolean
- container: ''
  name: DomainId
  type: string
- container: ''
  name: DomainName
  type: string
- container: ''
  name: EBSOptions
  type: reference
- container: ''
  name: Endpoint
  type: string
- container: ''
  name: EngineVersion
  type: string
property_count: 10
provider_name: Amazon OpenSearch Service
provider_slug: amazon-opensearch-service
slug: amazon-opensearch-service-openapi-context
source_filename: amazon-opensearch-service-openapi-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"opensearch\": \"https://opensearch.amazonaws.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"CreateDomainRequest\": \"opensearch:CreateDomainRequest\",\n    \"DomainStatus\": \"opensearch:DomainStatus\",\n    \"ARN\": {\n      \"@id\": \"opensearch:ARN\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AccessPolicies\": {\n      \"@id\": \"opensearch:AccessPolicies\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ClusterConfig\": {\n      \"@id\": \"opensearch:ClusterConfig\",\n      \"@type\": \"@id\"\n    },\n    \"Created\": {\n      \"@id\": \"opensearch:Created\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"Deleted\": {\n      \"@id\": \"opensearch:Deleted\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"DomainId\": {\n      \"@id\": \"opensearch:DomainId\",\n      \"@type\": \"xsd:string\"\n\
  \    },\n    \"DomainName\": {\n      \"@id\": \"opensearch:DomainName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EBSOptions\": {\n      \"@id\": \"opensearch:EBSOptions\",\n      \"@type\": \"@id\"\n    },\n    \"Endpoint\": {\n      \"@id\": \"opensearch:Endpoint\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EngineVersion\": {\n      \"@id\": \"opensearch:EngineVersion\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-opensearch-service/refs/heads/main/json-ld/amazon-opensearch-service-openapi-context.jsonld
tags:
- Analytics
- Elasticsearch
- Full-Text Search
- Log Analytics
- OpenSearch
- Search
- JSON-LD
- Linked Data
- Semantic Web
---
