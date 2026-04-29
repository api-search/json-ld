---
class_count: 2
classes:
- ExpenseReport
- Expense
context_file: json-ld/concur-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/concur/refs/heads/main/json-ld/concur-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Concur from SAP Concur.
layout: jsonld
name: Concur Context
namespaces:
- prefix: concur
  uri: https://concur.dev/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: reportId
  type: string
- container: ''
  name: reportName
  type: string
- container: ''
  name: ownerName
  type: string
- container: ''
  name: businessPurpose
  type: string
- container: ''
  name: submitDate
  type: dateTime
- container: ''
  name: approvalStatus
  type: string
- container: ''
  name: total
  type: decimal
- container: ''
  name: currencyCode
  type: string
- container: ''
  name: expenseId
  type: string
- container: ''
  name: expenseTypeName
  type: string
- container: ''
  name: transactionDate
  type: date
- container: ''
  name: transactionAmount
  type: decimal
- container: ''
  name: vendorName
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: receiptRequired
  type: boolean
property_count: 15
provider_name: SAP Concur
provider_slug: concur
slug: concur-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"concur\": \"https://concur.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ExpenseReport\": \"concur:ExpenseReport\",\n    \"Expense\": \"concur:Expense\",\n    \"reportId\": { \"@id\": \"concur:reportId\", \"@type\": \"xsd:string\" },\n    \"reportName\": { \"@id\": \"schema:name\", \"@type\": \"xsd:string\" },\n    \"ownerName\": { \"@id\": \"concur:ownerName\", \"@type\": \"xsd:string\" },\n    \"businessPurpose\": { \"@id\": \"concur:businessPurpose\", \"@type\": \"xsd:string\" },\n    \"submitDate\": { \"@id\": \"concur:submitDate\", \"@type\": \"xsd:dateTime\" },\n    \"approvalStatus\": { \"@id\": \"concur:approvalStatus\", \"@type\": \"xsd:string\" },\n    \"total\": { \"@id\": \"concur:total\", \"@type\": \"xsd:decimal\" },\n    \"currencyCode\": { \"@id\": \"concur:currencyCode\", \"@type\": \"xsd:string\" },\n    \"expenseId\": { \"@id\": \"concur:expenseId\"\
  , \"@type\": \"xsd:string\" },\n    \"expenseTypeName\": { \"@id\": \"concur:expenseTypeName\", \"@type\": \"xsd:string\" },\n    \"transactionDate\": { \"@id\": \"concur:transactionDate\", \"@type\": \"xsd:date\" },\n    \"transactionAmount\": { \"@id\": \"concur:transactionAmount\", \"@type\": \"xsd:decimal\" },\n    \"vendorName\": { \"@id\": \"concur:vendorName\", \"@type\": \"xsd:string\" },\n    \"description\": { \"@id\": \"schema:description\", \"@type\": \"xsd:string\" },\n    \"receiptRequired\": { \"@id\": \"concur:receiptRequired\", \"@type\": \"xsd:boolean\" }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/concur/refs/heads/main/json-ld/concur-context.jsonld
tags:
- Expense Management
- Finance
- Invoice
- SAP
- Travel
- JSON-LD
- Linked Data
- Semantic Web
---
