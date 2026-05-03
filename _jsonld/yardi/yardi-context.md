---
api_specs:
- filename: yardi-voyager-api-openapi.yml
  format: yaml
  label: Yardi Voyager API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/yardi/refs/heads/main/openapi/yardi-voyager-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/yardi-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/yardi/refs/heads/main/json-ld/yardi-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Yardi from Yardi.
layout: jsonld
name: Yardi Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
- prefix: yardi
  uri: https://www.yardi.com/vocab/
properties:
- container: ''
  name: Tenant
  type: reference
- container: ''
  name: Property
  type: reference
- container: ''
  name: Unit
  type: reference
- container: ''
  name: Lease
  type: reference
- container: ''
  name: Transaction
  type: reference
- container: ''
  name: ServiceRequest
  type: reference
- container: ''
  name: VendorInvoice
  type: reference
- container: ''
  name: BudgetData
  type: reference
- container: ''
  name: ChartOfAccounts
  type: reference
- container: ''
  name: JobCost
  type: reference
- container: ''
  name: tenantId
  type: string
- container: ''
  name: propertyId
  type: string
- container: ''
  name: unitId
  type: string
- container: ''
  name: firstName
  type: string
- container: ''
  name: lastName
  type: string
- container: ''
  name: email
  type: string
- container: ''
  name: phone
  type: string
- container: ''
  name: leaseStartDate
  type: date
- container: ''
  name: leaseEndDate
  type: date
- container: ''
  name: monthlyRent
  type: decimal
- container: ''
  name: balance
  type: decimal
- container: ''
  name: amount
  type: decimal
- container: ''
  name: transactionDate
  type: date
- container: ''
  name: transactionType
  type: string
- container: ''
  name: chargeCode
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: name
  type: string
property_count: 28
provider_name: Yardi
provider_slug: yardi
slug: yardi-context
source_filename: yardi-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"yardi\": \"https://www.yardi.com/vocab/\",\n\n    \"Tenant\": { \"@id\": \"yardi:Tenant\", \"@type\": \"@id\" },\n    \"Property\": { \"@id\": \"schema:RealEstateListing\", \"@type\": \"@id\" },\n    \"Unit\": { \"@id\": \"schema:Accommodation\", \"@type\": \"@id\" },\n    \"Lease\": { \"@id\": \"yardi:Lease\", \"@type\": \"@id\" },\n    \"Transaction\": { \"@id\": \"schema:PayAction\", \"@type\": \"@id\" },\n    \"ServiceRequest\": { \"@id\": \"yardi:ServiceRequest\", \"@type\": \"@id\" },\n    \"VendorInvoice\": { \"@id\": \"schema:Invoice\", \"@type\": \"@id\" },\n    \"BudgetData\": { \"@id\": \"yardi:BudgetData\", \"@type\": \"@id\" },\n    \"ChartOfAccounts\": { \"@id\": \"yardi:ChartOfAccounts\", \"@type\": \"@id\" },\n    \"JobCost\": { \"@id\": \"yardi:JobCost\", \"@type\": \"@id\" },\n\n    \"tenantId\": { \"@id\": \"schema:identifier\"\
  , \"@type\": \"xsd:string\" },\n    \"propertyId\": { \"@id\": \"schema:identifier\", \"@type\": \"xsd:string\" },\n    \"unitId\": { \"@id\": \"schema:identifier\", \"@type\": \"xsd:string\" },\n    \"firstName\": { \"@id\": \"schema:givenName\", \"@type\": \"xsd:string\" },\n    \"lastName\": { \"@id\": \"schema:familyName\", \"@type\": \"xsd:string\" },\n    \"email\": { \"@id\": \"schema:email\", \"@type\": \"xsd:string\" },\n    \"phone\": { \"@id\": \"schema:telephone\", \"@type\": \"xsd:string\" },\n    \"leaseStartDate\": { \"@id\": \"schema:startDate\", \"@type\": \"xsd:date\" },\n    \"leaseEndDate\": { \"@id\": \"schema:endDate\", \"@type\": \"xsd:date\" },\n    \"monthlyRent\": { \"@id\": \"yardi:monthlyRent\", \"@type\": \"xsd:decimal\" },\n    \"balance\": { \"@id\": \"yardi:balance\", \"@type\": \"xsd:decimal\" },\n    \"amount\": { \"@id\": \"schema:price\", \"@type\": \"xsd:decimal\" },\n    \"transactionDate\": { \"@id\": \"schema:startDate\", \"@type\": \"xsd:date\"\
  \ },\n    \"transactionType\": { \"@id\": \"yardi:transactionType\", \"@type\": \"xsd:string\" },\n    \"chargeCode\": { \"@id\": \"yardi:chargeCode\", \"@type\": \"xsd:string\" },\n    \"description\": { \"@id\": \"schema:description\", \"@type\": \"xsd:string\" },\n    \"status\": { \"@id\": \"schema:status\", \"@type\": \"xsd:string\" },\n    \"name\": { \"@id\": \"schema:name\", \"@type\": \"xsd:string\" }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/yardi/refs/heads/main/json-ld/yardi-context.jsonld
tags:
- Accounting
- Commercial Real Estate
- Coworking
- Investment Management
- Multifamily
- Property Management
- Real Estate
- Residential
- Self Storage
- Senior Living
- JSON-LD
- Linked Data
- Semantic Web
---
