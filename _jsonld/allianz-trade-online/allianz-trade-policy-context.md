---
class_count: 0
classes: []
context_file: json-ld/allianz-trade-policy-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/allianz-trade-online/refs/heads/main/json-ld/allianz-trade-policy-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Allianz Trade Policy from Allianz Trade.
layout: jsonld
name: Allianz Trade Policy Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
- prefix: trade
  uri: https://api.allianz-trade.com/vocab/
properties:
- container: ''
  name: policyId
  type: string
- container: ''
  name: policyNumber
  type: string
- container: ''
  name: policyHolderName
  type: string
- container: ''
  name: policyType
  type: string
- container: ''
  name: policyStatus
  type: string
- container: ''
  name: currency
  type: string
- container: ''
  name: maxCoverageAmount
  type: decimal
- container: ''
  name: coveragePercentage
  type: integer
- container: ''
  name: startDate
  type: date
- container: ''
  name: endDate
  type: date
- container: ''
  name: country
  type: string
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: jointInsuredId
  type: string
- container: ''
  name: companyName
  type: string
- container: ''
  name: registrationNumber
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: jobId
  type: string
- container: ''
  name: result
  type: ''
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
property_count: 23
provider_name: Allianz Trade
provider_slug: allianz-trade-online
slug: allianz-trade-policy-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"trade\": \"https://api.allianz-trade.com/vocab/\",\n    \"policyId\": {\"@id\": \"trade:policyId\", \"@type\": \"xsd:string\"},\n    \"policyNumber\": {\"@id\": \"schema:identifier\", \"@type\": \"xsd:string\"},\n    \"policyHolderName\": {\"@id\": \"schema:name\", \"@type\": \"xsd:string\"},\n    \"policyType\": {\"@id\": \"trade:policyType\", \"@type\": \"xsd:string\"},\n    \"policyStatus\": {\"@id\": \"schema:status\", \"@type\": \"xsd:string\"},\n    \"currency\": {\"@id\": \"schema:currency\", \"@type\": \"xsd:string\"},\n    \"maxCoverageAmount\": {\"@id\": \"trade:maxCoverageAmount\", \"@type\": \"xsd:decimal\"},\n    \"coveragePercentage\": {\"@id\": \"trade:coveragePercentage\", \"@type\": \"xsd:integer\"},\n    \"startDate\": {\"@id\": \"schema:startDate\", \"@type\": \"xsd:date\"},\n    \"endDate\": {\"@id\": \"schema:endDate\"\
  , \"@type\": \"xsd:date\"},\n    \"country\": {\"@id\": \"schema:addressCountry\", \"@type\": \"xsd:string\"},\n    \"createdAt\": {\"@id\": \"schema:dateCreated\", \"@type\": \"xsd:dateTime\"},\n    \"jointInsuredId\": {\"@id\": \"trade:jointInsuredId\", \"@type\": \"xsd:string\"},\n    \"companyName\": {\"@id\": \"schema:name\", \"@type\": \"xsd:string\"},\n    \"registrationNumber\": {\"@id\": \"schema:taxID\", \"@type\": \"xsd:string\"},\n    \"status\": {\"@id\": \"schema:status\", \"@type\": \"xsd:string\"},\n    \"jobId\": {\"@id\": \"trade:jobId\", \"@type\": \"xsd:string\"},\n    \"result\": {\"@id\": \"trade:result\"},\n    \"completedAt\": {\"@id\": \"schema:dateModified\", \"@type\": \"xsd:dateTime\"},\n    \"code\": {\"@id\": \"trade:errorCode\", \"@type\": \"xsd:string\"},\n    \"message\": {\"@id\": \"schema:description\", \"@type\": \"xsd:string\"},\n    \"requestId\": {\"@id\": \"trade:requestId\", \"@type\": \"xsd:string\"},\n    \"data\": {\"@id\": \"trade:data\", \"\
  @container\": \"@list\"}\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/allianz-trade-online/refs/heads/main/json-ld/allianz-trade-policy-context.jsonld
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
