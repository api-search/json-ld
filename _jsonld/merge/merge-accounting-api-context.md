---
api_specs:
- filename: merge-hris-api-openapi.yaml
  format: yaml
  label: Merge HRIS API
  slug: hris-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/merge/refs/heads/main/openapi/merge-hris-api-openapi.yaml
- filename: merge-ats-api-openapi.yaml
  format: yaml
  label: Merge ATS API
  slug: ats-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/merge/refs/heads/main/openapi/merge-ats-api-openapi.yaml
- filename: merge-accounting-api-openapi.yaml
  format: yaml
  label: Merge Accounting API
  slug: accounting-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/merge/refs/heads/main/openapi/merge-accounting-api-openapi.yaml
- filename: merge-ticketing-api-openapi.yaml
  format: yaml
  label: Merge Ticketing API
  slug: ticketing-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/merge/refs/heads/main/openapi/merge-ticketing-api-openapi.yaml
- filename: merge-crm-api-openapi.yaml
  format: yaml
  label: Merge CRM API
  slug: crm-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/merge/refs/heads/main/openapi/merge-crm-api-openapi.yaml
- filename: merge-file-storage-api-openapi.yaml
  format: yaml
  label: Merge File Storage API
  slug: file-storage-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/merge/refs/heads/main/openapi/merge-file-storage-api-openapi.yaml
class_count: 10
classes:
- Account
- Contact
- Invoice
- Payment
- JournalEntry
- Expense
- CompanyInfo
- Item
- TaxRate
- PurchaseOrder
context_file: json-ld/merge-accounting-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/merge/refs/heads/main/json-ld/merge-accounting-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Merge Accounting Api from Merge.
layout: jsonld
name: Merge Accounting Api Context
namespaces:
- prefix: merge
  uri: https://api.merge.dev/schema/
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
  name: name
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: classification
  type: string
- container: ''
  name: currentBalance
  type: decimal
- container: ''
  name: currency
  type: string
- container: ''
  name: accountNumber
  type: string
- container: ''
  name: isSupplier
  type: boolean
- container: ''
  name: isCustomer
  type: boolean
- container: ''
  name: emailAddress
  type: string
- container: ''
  name: number
  type: string
- container: ''
  name: issueDate
  type: dateTime
- container: ''
  name: dueDate
  type: dateTime
- container: ''
  name: totalAmount
  type: decimal
- container: ''
  name: balance
  type: decimal
- container: ''
  name: status
  type: string
- container: ''
  name: transactionDate
  type: dateTime
- container: ''
  name: memo
  type: string
- container: ''
  name: legalName
  type: string
- container: ''
  name: unitPrice
  type: decimal
- container: ''
  name: totalTaxRate
  type: decimal
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: modifiedAt
  type: dateTime
- container: ''
  name: remoteWasDeleted
  type: boolean
property_count: 24
provider_name: Merge
provider_slug: merge
slug: merge-accounting-api-context
source_filename: merge-accounting-api-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"merge\": \"https://api.merge.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Account\": \"merge:Account\",\n    \"Contact\": \"merge:Contact\",\n    \"Invoice\": \"merge:Invoice\",\n    \"Payment\": \"merge:Payment\",\n    \"JournalEntry\": \"merge:JournalEntry\",\n    \"Expense\": \"merge:Expense\",\n    \"CompanyInfo\": \"merge:CompanyInfo\",\n    \"Item\": \"merge:Item\",\n    \"TaxRate\": \"merge:TaxRate\",\n    \"PurchaseOrder\": \"merge:PurchaseOrder\",\n\n    \"id\": { \"@id\": \"dcterms:identifier\", \"@type\": \"xsd:string\" },\n    \"name\": { \"@id\": \"schema:name\", \"@type\": \"xsd:string\" },\n    \"description\": { \"@id\": \"schema:description\", \"@type\": \"xsd:string\" },\n    \"classification\": { \"@id\": \"merge:classification\", \"@type\": \"xsd:string\" },\n    \"currentBalance\"\
  : { \"@id\": \"merge:current_balance\", \"@type\": \"xsd:decimal\" },\n    \"currency\": { \"@id\": \"merge:currency\", \"@type\": \"xsd:string\" },\n    \"accountNumber\": { \"@id\": \"merge:account_number\", \"@type\": \"xsd:string\" },\n    \"isSupplier\": { \"@id\": \"merge:is_supplier\", \"@type\": \"xsd:boolean\" },\n    \"isCustomer\": { \"@id\": \"merge:is_customer\", \"@type\": \"xsd:boolean\" },\n    \"emailAddress\": { \"@id\": \"schema:email\", \"@type\": \"xsd:string\" },\n    \"number\": { \"@id\": \"merge:number\", \"@type\": \"xsd:string\" },\n    \"issueDate\": { \"@id\": \"merge:issue_date\", \"@type\": \"xsd:dateTime\" },\n    \"dueDate\": { \"@id\": \"merge:due_date\", \"@type\": \"xsd:dateTime\" },\n    \"totalAmount\": { \"@id\": \"merge:total_amount\", \"@type\": \"xsd:decimal\" },\n    \"balance\": { \"@id\": \"merge:balance\", \"@type\": \"xsd:decimal\" },\n    \"status\": { \"@id\": \"merge:status\", \"@type\": \"xsd:string\" },\n    \"transactionDate\": { \"\
  @id\": \"merge:transaction_date\", \"@type\": \"xsd:dateTime\" },\n    \"memo\": { \"@id\": \"merge:memo\", \"@type\": \"xsd:string\" },\n    \"legalName\": { \"@id\": \"schema:legalName\", \"@type\": \"xsd:string\" },\n    \"unitPrice\": { \"@id\": \"merge:unit_price\", \"@type\": \"xsd:decimal\" },\n    \"totalTaxRate\": { \"@id\": \"merge:total_tax_rate\", \"@type\": \"xsd:decimal\" },\n    \"createdAt\": { \"@id\": \"schema:dateCreated\", \"@type\": \"xsd:dateTime\" },\n    \"modifiedAt\": { \"@id\": \"schema:dateModified\", \"@type\": \"xsd:dateTime\" },\n    \"remoteWasDeleted\": { \"@id\": \"merge:remote_was_deleted\", \"@type\": \"xsd:boolean\" }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/merge/refs/heads/main/json-ld/merge-accounting-api-context.jsonld
tags:
- Integrations
- Platform
- Unified API
- JSON-LD
- Linked Data
- Semantic Web
---
