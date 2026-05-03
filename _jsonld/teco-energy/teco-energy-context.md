---
api_specs:
- filename: teco-energy-outage-openapi.yml
  format: yaml
  label: Tampa Electric Outage API
  slug: outage-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/teco-energy/refs/heads/main/openapi/teco-energy-outage-openapi.yml
- filename: teco-energy-account-openapi.yml
  format: yaml
  label: Tampa Electric Account API
  slug: account-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/teco-energy/refs/heads/main/openapi/teco-energy-account-openapi.yml
class_count: 36
classes:
- Outage
- outageId
- status
- cause
- customersAffected
- affectedArea
- outageStartTime
- estimatedRestorationTime
- actualRestorationTime
- lastUpdated
- Account
- accountNumber
- customerName
- serviceAddress
- accountType
- serviceType
- currentBalance
- dueDate
- paperlessBilling
- UsageRecord
- startTime
- endTime
- usage
- cost
- temperature
- Bill
- billId
- billDate
- totalAmount
- kwhUsed
- ServiceRequest
- requestId
- type
- zipCodes
- county
- city
context_file: json-ld/teco-energy-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/teco-energy/refs/heads/main/json-ld/teco-energy-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Teco Energy from TECO Energy.
layout: jsonld
name: Teco Energy Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: teco
  uri: https://www.tecoenergy.com/
- prefix: energy
  uri: https://ontology.teco-energy.com/
properties: []
property_count: 0
provider_name: TECO Energy
provider_slug: teco-energy
slug: teco-energy-context
source_filename: teco-energy-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"teco\": \"https://www.tecoenergy.com/\",\n    \"energy\": \"https://ontology.teco-energy.com/\",\n\n    \"Outage\": \"schema:Event\",\n    \"outageId\": \"schema:identifier\",\n    \"status\": \"schema:status\",\n    \"cause\": \"schema:description\",\n    \"customersAffected\": \"schema:numberOfItems\",\n    \"affectedArea\": \"schema:areaServed\",\n    \"outageStartTime\": \"schema:startDate\",\n    \"estimatedRestorationTime\": \"schema:endDate\",\n    \"actualRestorationTime\": \"schema:endDate\",\n    \"lastUpdated\": \"schema:dateModified\",\n\n    \"Account\": \"schema:BankAccount\",\n    \"accountNumber\": \"schema:identifier\",\n    \"customerName\": \"schema:name\",\n    \"serviceAddress\": \"schema:address\",\n    \"accountType\": \"schema:accountType\",\n    \"serviceType\": \"energy:serviceType\",\n    \"currentBalance\": \"schema:price\",\n    \"dueDate\": \"schema:paymentDue\"\
  ,\n    \"paperlessBilling\": \"energy:paperlessBilling\",\n\n    \"UsageRecord\": \"energy:UsageRecord\",\n    \"startTime\": \"schema:startDate\",\n    \"endTime\": \"schema:endDate\",\n    \"usage\": \"energy:kwhUsage\",\n    \"cost\": \"schema:price\",\n    \"temperature\": \"schema:value\",\n\n    \"Bill\": \"schema:Invoice\",\n    \"billId\": \"schema:identifier\",\n    \"billDate\": \"schema:dateIssued\",\n    \"dueDate\": \"schema:paymentDue\",\n    \"totalAmount\": \"schema:totalPrice\",\n    \"kwhUsed\": \"energy:kwhUsage\",\n\n    \"ServiceRequest\": \"schema:Order\",\n    \"requestId\": \"schema:orderNumber\",\n    \"type\": \"schema:orderType\",\n\n    \"zipCodes\": \"schema:postalCode\",\n    \"county\": \"schema:addressRegion\",\n    \"city\": \"schema:addressLocality\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/teco-energy/refs/heads/main/json-ld/teco-energy-context.jsonld
tags:
- Energy
- Utilities
- Electric
- Natural Gas
- Smart Grid
- Tampa Bay
- JSON-LD
- Linked Data
- Semantic Web
---
