---
class_count: 5
classes:
- EnergyAccount
- Utility
- EnergyService
- ServiceLocation
- MeterReading
context_file: json-ld/ugi-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/ugi/refs/heads/main/json-ld/ugi-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Ugi from UGI Corporation.
layout: jsonld
name: Ugi Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: ugi
  uri: https://ugicorp.com/vocab/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: accountNumber
  type: string
- container: ''
  name: customerName
  type: string
- container: ''
  name: serviceAddress
  type: string
- container: ''
  name: serviceType
  type: string
- container: ''
  name: meterNumber
  type: string
- container: ''
  name: usage
  type: double
- container: ''
  name: usageUnit
  type: string
- container: ''
  name: billingPeriod
  type: string
- container: ''
  name: amountDue
  type: double
- container: ''
  name: currency
  type: string
- container: ''
  name: dueDate
  type: date
- container: ''
  name: startDate
  type: date
- container: ''
  name: endDate
  type: date
property_count: 13
provider_name: UGI Corporation
provider_slug: ugi
slug: ugi-context
source_filename: ugi-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"ugi\": \"https://ugicorp.com/vocab/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"EnergyAccount\": \"schema:Account\",\n    \"Utility\": \"schema:PublicUtility\",\n    \"EnergyService\": \"schema:Product\",\n    \"ServiceLocation\": \"schema:Place\",\n    \"MeterReading\": \"ugi:MeterReading\",\n\n    \"accountNumber\": { \"@id\": \"schema:identifier\", \"@type\": \"xsd:string\" },\n    \"customerName\": { \"@id\": \"schema:name\", \"@type\": \"xsd:string\" },\n    \"serviceAddress\": { \"@id\": \"schema:address\", \"@type\": \"xsd:string\" },\n    \"serviceType\": { \"@id\": \"schema:additionalType\", \"@type\": \"xsd:string\" },\n    \"meterNumber\": { \"@id\": \"ugi:meterNumber\", \"@type\": \"xsd:string\" },\n    \"usage\": { \"@id\": \"schema:value\", \"@type\": \"xsd:double\" },\n    \"usageUnit\": { \"@id\": \"schema:unitCode\", \"@type\": \"xsd:string\" },\n\
  \    \"billingPeriod\": { \"@id\": \"schema:temporalCoverage\", \"@type\": \"xsd:string\" },\n    \"amountDue\": { \"@id\": \"schema:price\", \"@type\": \"xsd:double\" },\n    \"currency\": { \"@id\": \"schema:priceCurrency\", \"@type\": \"xsd:string\" },\n    \"dueDate\": { \"@id\": \"schema:paymentDueDate\", \"@type\": \"xsd:date\" },\n    \"startDate\": { \"@id\": \"schema:startDate\", \"@type\": \"xsd:date\" },\n    \"endDate\": { \"@id\": \"schema:endDate\", \"@type\": \"xsd:date\" }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/ugi/refs/heads/main/json-ld/ugi-context.jsonld
tags:
- Energy
- Utilities
- Natural Gas
- Propane
- Electric
- Fortune 500
- Pennsylvania
- JSON-LD
- Linked Data
- Semantic Web
---
