---
class_count: 12
classes:
- SouthernCompany
- UtilityAccount
- EnergyUsage
- BillingPeriod
- EnergyMeter
- OutageEvent
- ServiceAddress
- EnergyRate
- AlabamaPower
- GeorgiaPower
- MississippiPower
- SouthernCompanyGas
context_file: json-ld/southern-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/southern/refs/heads/main/json-ld/southern-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Southern from Southern Company.
layout: jsonld
name: Southern Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: southern
  uri: https://api-evangelist.github.io/southern/vocab#
properties:
- container: ''
  name: accountNumber
  type: string
- container: ''
  name: serviceAddress
  type: reference
- container: ''
  name: usageKwh
  type: decimal
- container: ''
  name: usageTherms
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
  name: outageStartTime
  type: dateTime
- container: ''
  name: outageEndTime
  type: dateTime
- container: ''
  name: customersAffected
  type: integer
- container: ''
  name: rateSchedule
  type: string
- container: ''
  name: subsidiary
  type: reference
property_count: 13
provider_name: Southern Company
provider_slug: southern
slug: southern-context
source_filename: southern-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"southern\": \"https://api-evangelist.github.io/southern/vocab#\",\n\n    \"SouthernCompany\": \"schema:Corporation\",\n    \"UtilityAccount\": \"schema:Account\",\n    \"EnergyUsage\": \"schema:QuantitativeValue\",\n    \"BillingPeriod\": \"schema:Duration\",\n    \"EnergyMeter\": \"schema:Product\",\n    \"OutageEvent\": \"schema:Event\",\n    \"ServiceAddress\": \"schema:PostalAddress\",\n    \"EnergyRate\": \"schema:PriceSpecification\",\n\n    \"accountNumber\": {\n      \"@id\": \"southern:accountNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"serviceAddress\": {\n      \"@id\": \"schema:address\",\n      \"@type\": \"@id\"\n    },\n    \"usageKwh\": {\n      \"@id\": \"southern:usageKwh\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"usageTherms\": {\n      \"@id\": \"southern:usageTherms\",\n      \"@type\":\
  \ \"xsd:decimal\"\n    },\n    \"billingAmount\": {\n      \"@id\": \"schema:price\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"billingPeriodStart\": {\n      \"@id\": \"schema:startDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"billingPeriodEnd\": {\n      \"@id\": \"schema:endDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"meterSerialNumber\": {\n      \"@id\": \"southern:meterSerialNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"outageStartTime\": {\n      \"@id\": \"schema:startDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"outageEndTime\": {\n      \"@id\": \"schema:endDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"customersAffected\": {\n      \"@id\": \"southern:customersAffected\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"rateSchedule\": {\n      \"@id\": \"southern:rateSchedule\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subsidiary\": {\n      \"@id\": \"schema:parentOrganization\",\n      \"@type\": \"@id\"\n\
  \    },\n    \"AlabamaPower\": \"schema:Organization\",\n    \"GeorgiaPower\": \"schema:Organization\",\n    \"MississippiPower\": \"schema:Organization\",\n    \"SouthernCompanyGas\": \"schema:Organization\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/southern/refs/heads/main/json-ld/southern-context.jsonld
tags:
- Fortune 500
- Electric Utility
- Natural Gas
- Energy
- JSON-LD
- Linked Data
- Semantic Web
---
