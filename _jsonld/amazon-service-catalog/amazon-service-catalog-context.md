---
class_count: 3
classes:
- Portfolio
- ProductViewSummary
- ProvisionedProduct
context_file: json-ld/amazon-service-catalog-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-service-catalog/refs/heads/main/json-ld/amazon-service-catalog-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Service Catalog from Amazon Service Catalog.
layout: jsonld
name: Amazon Service Catalog Context
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
  name: Id
  type: string
- container: ''
  name: ARN
  type: string
- container: ''
  name: DisplayName
  type: string
- container: ''
  name: Description
  type: string
- container: ''
  name: CreatedTime
  type: dateTime
- container: ''
  name: ProviderName
  type: string
- container: ''
  name: ProductId
  type: string
- container: ''
  name: Name
  type: string
- container: ''
  name: Owner
  type: string
- container: ''
  name: ShortDescription
  type: string
- container: ''
  name: Type
  type: string
- container: ''
  name: RecordDetail
  type: reference
property_count: 12
provider_name: Amazon Service Catalog
provider_slug: amazon-service-catalog
slug: amazon-service-catalog-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aws\": \"https://aws.amazon.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Portfolio\": \"aws:Portfolio\",\n    \"Id\": {\n      \"@id\": \"aws:Id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ARN\": {\n      \"@id\": \"aws:ARN\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DisplayName\": {\n      \"@id\": \"aws:DisplayName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Description\": {\n      \"@id\": \"aws:Description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreatedTime\": {\n      \"@id\": \"aws:CreatedTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"ProviderName\": {\n      \"@id\": \"aws:ProviderName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ProductViewSummary\": \"aws:ProductViewSummary\",\n    \"ProductId\": {\n      \"@id\": \"aws:ProductId\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"Name\": {\n      \"@id\": \"aws:Name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Owner\": {\n      \"@id\": \"aws:Owner\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ShortDescription\": {\n      \"@id\": \"aws:ShortDescription\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Type\": {\n      \"@id\": \"aws:Type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ProvisionedProduct\": \"aws:ProvisionedProduct\",\n    \"RecordDetail\": {\n      \"@id\": \"aws:RecordDetail\",\n      \"@type\": \"@id\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-service-catalog/refs/heads/main/json-ld/amazon-service-catalog-context.jsonld
tags:
- AWS
- Cloud Governance
- Compliance
- IT Governance
- Service Catalog
- JSON-LD
- Linked Data
- Semantic Web
---
