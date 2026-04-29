---
api_specs:
- filename: amazon-supply-chain.yaml
  format: yaml
  label: AWS Supply Chain API
  slug: aws-supply-chain-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-supply-chain/refs/heads/main/openapi/amazon-supply-chain.yaml
class_count: 8
classes:
- DataLakeDataset
- BillOfMaterialsImportJob
- Instance
- DataIntegrationEvent
- DataIntegrationFlow
- DataLakeNamespace
- name
- description
context_file: json-ld/amazon-supply-chain-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-supply-chain/refs/heads/main/json-ld/amazon-supply-chain-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Supply Chain from Amazon Supply Chain.
layout: jsonld
name: Amazon Supply Chain Context
namespaces:
- prefix: aws
  uri: https://amazonaws.com/schema/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: schema
  type: reference
- container: ''
  name: instanceId
  type: string
- container: ''
  name: namespace
  type: string
- container: ''
  name: partitionSpec
  type: reference
- container: ''
  name: createdTime
  type: dateTime
- container: ''
  name: lastModifiedTime
  type: dateTime
- container: ''
  name: jobId
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: s3uri
  type: string
- container: ''
  name: message
  type: string
- container: ''
  name: instanceName
  type: string
- container: ''
  name: instanceDescription
  type: string
- container: ''
  name: instanceState
  type: string
- container: ''
  name: kmsKeyArn
  type: string
- container: ''
  name: webAppDnsDomain
  type: string
- container: ''
  name: eventId
  type: string
- container: ''
  name: eventType
  type: string
- container: ''
  name: eventGroupId
  type: string
- container: ''
  name: eventTimestamp
  type: dateTime
- container: ''
  name: data
  type: string
- container: set
  name: sources
  type: reference
- container: ''
  name: transformation
  type: reference
- container: ''
  name: target
  type: reference
property_count: 23
provider_name: Amazon Supply Chain
provider_slug: amazon-supply-chain
slug: amazon-supply-chain-context
source_filename: amazon-supply-chain-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aws\": \"https://amazonaws.com/schema/\",\n    \"schema\": {\n      \"@id\": \"aws:schema\",\n      \"@type\": \"@id\"\n    },\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"DataLakeDataset\": \"aws:DataLakeDataset\",\n    \"BillOfMaterialsImportJob\": \"aws:BillOfMaterialsImportJob\",\n    \"Instance\": \"aws:Instance\",\n    \"DataIntegrationEvent\": \"aws:DataIntegrationEvent\",\n    \"DataIntegrationFlow\": \"aws:DataIntegrationFlow\",\n    \"DataLakeNamespace\": \"aws:DataLakeNamespace\",\n    \"instanceId\": {\n      \"@id\": \"aws:instanceId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"namespace\": {\n      \"@id\": \"aws:namespace\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"partitionSpec\": {\n      \"@id\": \"aws:partitionSpec\",\n      \"@type\": \"@id\"\n    },\n\
  \    \"createdTime\": {\n      \"@id\": \"aws:createdTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"lastModifiedTime\": {\n      \"@id\": \"aws:lastModifiedTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"jobId\": {\n      \"@id\": \"aws:jobId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"aws:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"s3uri\": {\n      \"@id\": \"aws:s3uri\",\n      \"@type\": \"xsd:string\"\n    },\n    \"message\": {\n      \"@id\": \"aws:message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"instanceName\": {\n      \"@id\": \"aws:instanceName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"instanceDescription\": {\n      \"@id\": \"aws:instanceDescription\",\n      \"@type\": \"xsd:string\"\n    },\n    \"instanceState\": {\n      \"@id\": \"aws:instanceState\",\n      \"@type\": \"xsd:string\"\n    },\n    \"kmsKeyArn\": {\n      \"@id\": \"aws:kmsKeyArn\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"webAppDnsDomain\": {\n      \"@id\": \"aws:webAppDnsDomain\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eventId\": {\n      \"@id\": \"aws:eventId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eventType\": {\n      \"@id\": \"aws:eventType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eventGroupId\": {\n      \"@id\": \"aws:eventGroupId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eventTimestamp\": {\n      \"@id\": \"aws:eventTimestamp\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"data\": {\n      \"@id\": \"aws:data\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sources\": {\n      \"@id\": \"aws:sources\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"transformation\": {\n      \"@id\": \"aws:transformation\",\n      \"@type\": \"@id\"\n    },\n    \"target\": {\n      \"@id\": \"aws:target\",\n      \"@type\": \"@id\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-supply-chain/refs/heads/main/json-ld/amazon-supply-chain-context.jsonld
tags:
- AWS
- ERP Integration
- Logistics
- Machine Learning
- Supply Chain
- JSON-LD
- Linked Data
- Semantic Web
---
