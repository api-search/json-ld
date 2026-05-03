---
class_count: 8
classes:
- GasUtility
- GasAccount
- GasUsage
- GasMeter
- BillingStatement
- ServiceAddress
- AgencyPledge
- ServiceOutage
context_file: json-ld/southwest-gas-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/southwest-gas/refs/heads/main/json-ld/southwest-gas-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Southwest Gas from Southwest Gas.
layout: jsonld
name: Southwest Gas Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: swg
  uri: https://api-evangelist.github.io/southwest-gas/vocab#
properties:
- container: ''
  name: accountNumber
  type: string
- container: ''
  name: serviceAddress
  type: reference
- container: ''
  name: usageTherms
  type: decimal
- container: ''
  name: usageCcf
  type: decimal
- container: ''
  name: billingAmount
  type: decimal
- container: ''
  name: billingPeriodStart
  type: date
- container: ''
  name: billingPeriodEnd
  type: date
- container: ''
  name: meterSerialNumber
  type: string
- container: ''
  name: pledgeAmount
  type: decimal
- container: ''
  name: pledgeAgency
  type: reference
- container: ''
  name: serviceTerritory
  type: string
- container: ''
  name: rateSchedule
  type: string
- container: ''
  name: budgetBillingAmount
  type: decimal
property_count: 13
provider_name: Southwest Gas
provider_slug: southwest-gas
slug: southwest-gas-context
source_filename: southwest-gas-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"swg\": \"https://api-evangelist.github.io/southwest-gas/vocab#\",\n\n    \"GasUtility\": \"schema:Corporation\",\n    \"GasAccount\": \"schema:Account\",\n    \"GasUsage\": \"schema:QuantitativeValue\",\n    \"GasMeter\": \"schema:Product\",\n    \"BillingStatement\": \"schema:Invoice\",\n    \"ServiceAddress\": \"schema:PostalAddress\",\n    \"AgencyPledge\": \"schema:Offer\",\n    \"ServiceOutage\": \"schema:Event\",\n\n    \"accountNumber\": {\n      \"@id\": \"swg:accountNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"serviceAddress\": {\n      \"@id\": \"schema:address\",\n      \"@type\": \"@id\"\n    },\n    \"usageTherms\": {\n      \"@id\": \"swg:usageTherms\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"usageCcf\": {\n      \"@id\": \"swg:usageCcf\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"billingAmount\"\
  : {\n      \"@id\": \"schema:price\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"billingPeriodStart\": {\n      \"@id\": \"schema:startDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"billingPeriodEnd\": {\n      \"@id\": \"schema:endDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"meterSerialNumber\": {\n      \"@id\": \"swg:meterSerialNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pledgeAmount\": {\n      \"@id\": \"schema:price\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"pledgeAgency\": {\n      \"@id\": \"schema:provider\",\n      \"@type\": \"@id\"\n    },\n    \"serviceTerritory\": {\n      \"@id\": \"swg:serviceTerritory\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rateSchedule\": {\n      \"@id\": \"swg:rateSchedule\",\n      \"@type\": \"xsd:string\"\n    },\n    \"budgetBillingAmount\": {\n      \"@id\": \"swg:budgetBillingAmount\",\n      \"@type\": \"xsd:decimal\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/southwest-gas/refs/heads/main/json-ld/southwest-gas-context.jsonld
tags:
- Fortune 1000
- Natural Gas
- Utility
- Energy
- JSON-LD
- Linked Data
- Semantic Web
---
