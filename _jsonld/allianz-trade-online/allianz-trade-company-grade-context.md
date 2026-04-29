---
api_specs:
- filename: allianz-trade-payment-overdues.yaml
  format: yaml
  label: Allianz Trade Payment Overdues API
  slug: payment-overdues-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/allianz-trade-online/refs/heads/main/openapi/allianz-trade-payment-overdues.yaml
- filename: allianz-trade-company-grade.yaml
  format: yaml
  label: Allianz Trade Company Grade API
  slug: company-grade-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/allianz-trade-online/refs/heads/main/openapi/allianz-trade-company-grade.yaml
- filename: allianz-trade-claims.yaml
  format: yaml
  label: Allianz Trade Claims API
  slug: claims-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/allianz-trade-online/refs/heads/main/openapi/allianz-trade-claims.yaml
- filename: allianz-trade-policy.yaml
  format: yaml
  label: Allianz Trade Policy API
  slug: policy-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/allianz-trade-online/refs/heads/main/openapi/allianz-trade-policy.yaml
class_count: 0
classes: []
context_file: json-ld/allianz-trade-company-grade-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/allianz-trade-online/refs/heads/main/json-ld/allianz-trade-company-grade-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Allianz Trade Company Grade from Allianz Trade.
layout: jsonld
name: Allianz Trade Company Grade Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
- prefix: trade
  uri: https://api.allianz-trade.com/vocab/
properties:
- container: ''
  name: gradeId
  type: string
- container: ''
  name: policyId
  type: string
- container: ''
  name: companyName
  type: string
- container: ''
  name: companyRegistrationNumber
  type: string
- container: ''
  name: country
  type: string
- container: ''
  name: grade
  type: string
- container: ''
  name: gradeScore
  type: integer
- container: ''
  name: currency
  type: string
- container: ''
  name: creditLimit
  type: decimal
- container: ''
  name: requestedCreditLimit
  type: decimal
- container: ''
  name: validUntil
  type: date
- container: ''
  name: gradedAt
  type: dateTime
- container: ''
  name: jobId
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: result
  type: ''
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: completedAt
  type: dateTime
- container: ''
  name: code
  type: string
- container: ''
  name: message
  type: string
- container: ''
  name: requestId
  type: string
- container: list
  name: data
  type: ''
property_count: 21
provider_name: Allianz Trade
provider_slug: allianz-trade-online
slug: allianz-trade-company-grade-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"trade\": \"https://api.allianz-trade.com/vocab/\",\n    \"gradeId\": {\"@id\": \"trade:gradeId\", \"@type\": \"xsd:string\"},\n    \"policyId\": {\"@id\": \"trade:policyId\", \"@type\": \"xsd:string\"},\n    \"companyName\": {\"@id\": \"schema:name\", \"@type\": \"xsd:string\"},\n    \"companyRegistrationNumber\": {\"@id\": \"schema:taxID\", \"@type\": \"xsd:string\"},\n    \"country\": {\"@id\": \"schema:addressCountry\", \"@type\": \"xsd:string\"},\n    \"grade\": {\"@id\": \"trade:creditGrade\", \"@type\": \"xsd:string\"},\n    \"gradeScore\": {\"@id\": \"trade:gradeScore\", \"@type\": \"xsd:integer\"},\n    \"currency\": {\"@id\": \"schema:currency\", \"@type\": \"xsd:string\"},\n    \"creditLimit\": {\"@id\": \"trade:creditLimit\", \"@type\": \"xsd:decimal\"},\n    \"requestedCreditLimit\": {\"@id\": \"trade:requestedCreditLimit\"\
  , \"@type\": \"xsd:decimal\"},\n    \"validUntil\": {\"@id\": \"schema:validThrough\", \"@type\": \"xsd:date\"},\n    \"gradedAt\": {\"@id\": \"schema:dateModified\", \"@type\": \"xsd:dateTime\"},\n    \"jobId\": {\"@id\": \"trade:jobId\", \"@type\": \"xsd:string\"},\n    \"status\": {\"@id\": \"schema:status\", \"@type\": \"xsd:string\"},\n    \"result\": {\"@id\": \"trade:result\"},\n    \"createdAt\": {\"@id\": \"schema:dateCreated\", \"@type\": \"xsd:dateTime\"},\n    \"completedAt\": {\"@id\": \"schema:dateModified\", \"@type\": \"xsd:dateTime\"},\n    \"code\": {\"@id\": \"trade:errorCode\", \"@type\": \"xsd:string\"},\n    \"message\": {\"@id\": \"schema:description\", \"@type\": \"xsd:string\"},\n    \"requestId\": {\"@id\": \"trade:requestId\", \"@type\": \"xsd:string\"},\n    \"data\": {\"@id\": \"trade:data\", \"@container\": \"@list\"}\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/allianz-trade-online/refs/heads/main/json-ld/allianz-trade-company-grade-context.jsonld
tags:
- Credit Insurance
- Insurance
- Risk Management
- Trade Credit
- E-Commerce
- Surety
- JSON-LD
- Linked Data
- Semantic Web
---
