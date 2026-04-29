---
class_count: 0
classes: []
context_file: json-ld/allianz-trade-claims-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/allianz-trade-online/refs/heads/main/json-ld/allianz-trade-claims-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Allianz Trade Claims from Allianz Trade.
layout: jsonld
name: Allianz Trade Claims Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
- prefix: trade
  uri: https://api.allianz-trade.com/vocab/
properties:
- container: ''
  name: claimId
  type: string
- container: ''
  name: policyId
  type: string
- container: ''
  name: debtorName
  type: string
- container: ''
  name: debtorId
  type: string
- container: ''
  name: claimAmount
  type: decimal
- container: ''
  name: approvedAmount
  type: decimal
- container: ''
  name: currency
  type: string
- container: ''
  name: claimStatus
  type: string
- container: ''
  name: lossDate
  type: date
- container: ''
  name: invoiceReference
  type: string
- container: ''
  name: overdueId
  type: string
- container: ''
  name: submittedAt
  type: dateTime
- container: ''
  name: resolvedAt
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
property_count: 22
provider_name: Allianz Trade
provider_slug: allianz-trade-online
slug: allianz-trade-claims-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"trade\": \"https://api.allianz-trade.com/vocab/\",\n    \"claimId\": {\"@id\": \"trade:claimId\", \"@type\": \"xsd:string\"},\n    \"policyId\": {\"@id\": \"trade:policyId\", \"@type\": \"xsd:string\"},\n    \"debtorName\": {\"@id\": \"schema:name\", \"@type\": \"xsd:string\"},\n    \"debtorId\": {\"@id\": \"trade:debtorId\", \"@type\": \"xsd:string\"},\n    \"claimAmount\": {\"@id\": \"schema:amount\", \"@type\": \"xsd:decimal\"},\n    \"approvedAmount\": {\"@id\": \"trade:approvedAmount\", \"@type\": \"xsd:decimal\"},\n    \"currency\": {\"@id\": \"schema:currency\", \"@type\": \"xsd:string\"},\n    \"claimStatus\": {\"@id\": \"schema:status\", \"@type\": \"xsd:string\"},\n    \"lossDate\": {\"@id\": \"trade:lossDate\", \"@type\": \"xsd:date\"},\n    \"invoiceReference\": {\"@id\": \"trade:invoiceReference\", \"@type\": \"xsd:string\"\
  },\n    \"overdueId\": {\"@id\": \"trade:overdueId\", \"@type\": \"xsd:string\"},\n    \"submittedAt\": {\"@id\": \"schema:dateCreated\", \"@type\": \"xsd:dateTime\"},\n    \"resolvedAt\": {\"@id\": \"schema:dateModified\", \"@type\": \"xsd:dateTime\"},\n    \"jobId\": {\"@id\": \"trade:jobId\", \"@type\": \"xsd:string\"},\n    \"status\": {\"@id\": \"schema:status\", \"@type\": \"xsd:string\"},\n    \"result\": {\"@id\": \"trade:result\"},\n    \"createdAt\": {\"@id\": \"schema:dateCreated\", \"@type\": \"xsd:dateTime\"},\n    \"completedAt\": {\"@id\": \"schema:dateModified\", \"@type\": \"xsd:dateTime\"},\n    \"code\": {\"@id\": \"trade:errorCode\", \"@type\": \"xsd:string\"},\n    \"message\": {\"@id\": \"schema:description\", \"@type\": \"xsd:string\"},\n    \"requestId\": {\"@id\": \"trade:requestId\", \"@type\": \"xsd:string\"},\n    \"data\": {\"@id\": \"trade:data\", \"@container\": \"@list\"}\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/allianz-trade-online/refs/heads/main/json-ld/allianz-trade-claims-context.jsonld
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
