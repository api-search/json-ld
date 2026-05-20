---
api_specs:
- filename: infor-ion-api-gateway-openapi.yml
  format: yaml
  label: Infor ION API Gateway
  slug: infor-ion-api-gateway
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/infor/refs/heads/main/openapi/infor-ion-api-gateway-openapi.yml
class_count: 22
classes:
- CUNO
- CUNM
- CUA1
- CUA3
- PONO
- CSCD
- PHNO
- EMAL
- CUCD
- STAT
- LNCD
- documentId
- documentType
- status
- sender
- receiver
- Program
- Transaction
- company
- NameValue
- Name
- Value
context_file: json-ld/infor-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/infor/refs/heads/main/json-ld/infor-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Infor from Infor.
layout: jsonld
name: Infor Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dct
  uri: http://purl.org/dc/terms/
- prefix: gr
  uri: http://purl.org/goodrelations/v1#
properties:
- container: ''
  name: Customer
  type: reference
- container: ''
  name: Order
  type: reference
- container: ''
  name: Product
  type: reference
- container: ''
  name: Document
  type: reference
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: processedAt
  type: dateTime
property_count: 6
provider_name: Infor
provider_slug: infor
slug: infor-context
source_filename: infor-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dct\": \"http://purl.org/dc/terms/\",\n    \"gr\": \"http://purl.org/goodrelations/v1#\",\n\n    \"Customer\": {\n      \"@id\": \"schema:Organization\",\n      \"@type\": \"@id\"\n    },\n    \"Order\": {\n      \"@id\": \"schema:Order\",\n      \"@type\": \"@id\"\n    },\n    \"Product\": {\n      \"@id\": \"schema:Product\",\n      \"@type\": \"@id\"\n    },\n    \"Document\": {\n      \"@id\": \"schema:DigitalDocument\",\n      \"@type\": \"@id\"\n    },\n\n    \"CUNO\": \"schema:identifier\",\n    \"CUNM\": \"schema:name\",\n    \"CUA1\": \"schema:streetAddress\",\n    \"CUA3\": \"schema:addressLocality\",\n    \"PONO\": \"schema:postalCode\",\n    \"CSCD\": \"schema:addressCountry\",\n    \"PHNO\": \"schema:telephone\",\n    \"EMAL\": \"schema:email\",\n    \"CUCD\": \"schema:currency\",\n    \"STAT\": \"schema:itemCondition\"\
  ,\n    \"LNCD\": \"schema:inLanguage\",\n\n    \"documentId\": \"schema:identifier\",\n    \"documentType\": \"schema:additionalType\",\n    \"status\": \"schema:actionStatus\",\n    \"sender\": \"schema:sender\",\n    \"receiver\": \"schema:recipient\",\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"processedAt\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n\n    \"Program\": \"schema:identifier\",\n    \"Transaction\": \"schema:name\",\n    \"company\": \"schema:identifier\",\n\n    \"NameValue\": \"schema:PropertyValue\",\n    \"Name\": \"schema:name\",\n    \"Value\": \"schema:value\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/infor/refs/heads/main/json-ld/infor-context.jsonld
tags:
- ERP
- Manufacturing
- Supply Chain
- Cloud
- Integration
- JSON-LD
- Linked Data
- Semantic Web
---
