---
class_count: 0
classes: []
context_file: json-ld/wec-energy-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/wec-energy/refs/heads/main/json-ld/wec-energy-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Wec Energy from WEC Energy Group.
layout: jsonld
name: Wec Energy Context
namespaces:
- prefix: wec
  uri: https://www.wecenergygroup.com/vocab#
- prefix: schema
  uri: https://schema.org/
- prefix: espi
  uri: https://naesb.org/espi#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: EnergyAccount
  type: reference
- container: ''
  name: ElectricService
  type: reference
- container: ''
  name: NaturalGasService
  type: reference
- container: ''
  name: EnergyUsage
  type: reference
- container: ''
  name: OutageEvent
  type: reference
- container: ''
  name: WeEnergies
  type: schema:Organization
- container: ''
  name: WisconsinPublicService
  type: schema:Organization
- container: ''
  name: PeoplesGas
  type: schema:Organization
- container: ''
  name: GreenButton
  type: reference
- container: ''
  name: accountNumber
  type: string
- container: ''
  name: customerName
  type: string
- container: ''
  name: serviceAddress
  type: schema:PostalAddress
- container: ''
  name: accountStatus
  type: string
- container: ''
  name: serviceType
  type: string
- container: ''
  name: currentBalance
  type: decimal
- container: ''
  name: dueDate
  type: date
- container: ''
  name: usageReadings
  type: reference
- container: ''
  name: totalUsage
  type: decimal
- container: ''
  name: unit
  type: string
- container: ''
  name: customersAffected
  type: integer
- container: ''
  name: estimatedRestoration
  type: dateTime
- container: ''
  name: FocusOnEnergy
  type: reference
- container: ''
  name: rateCode
  type: string
property_count: 23
provider_name: WEC Energy Group
provider_slug: wec-energy
slug: wec-energy-context
source_filename: wec-energy-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"wec\": \"https://www.wecenergygroup.com/vocab#\",\n    \"schema\": \"https://schema.org/\",\n    \"espi\": \"https://naesb.org/espi#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"EnergyAccount\": {\n      \"@id\": \"wec:EnergyAccount\",\n      \"@type\": \"@id\",\n      \"description\": \"A utility customer account for electric or natural gas service\"\n    },\n\n    \"ElectricService\": {\n      \"@id\": \"wec:ElectricService\",\n      \"@type\": \"@id\",\n      \"description\": \"Electric power delivery service from a WEC Energy Group utility\"\n    },\n\n    \"NaturalGasService\": {\n      \"@id\": \"wec:NaturalGasService\",\n      \"@type\": \"@id\",\n      \"description\": \"Natural gas distribution service from a WEC Energy Group utility\"\n    },\n\n    \"EnergyUsage\": {\n      \"@id\": \"espi:UsagePoint\",\n      \"@type\": \"@id\",\n      \"description\"\
  : \"A record of energy consumption at a service point (Green Button ESPI)\"\n    },\n\n    \"OutageEvent\": {\n      \"@id\": \"wec:OutageEvent\",\n      \"@type\": \"@id\",\n      \"description\": \"An electricity service interruption event in WEC Energy Group service territory\"\n    },\n\n    \"WeEnergies\": {\n      \"@id\": \"wec:WeEnergies\",\n      \"@type\": \"schema:Organization\",\n      \"schema:name\": \"We Energies\",\n      \"schema:description\": \"Electric and natural gas utility serving southeast Wisconsin\"\n    },\n\n    \"WisconsinPublicService\": {\n      \"@id\": \"wec:WisconsinPublicService\",\n      \"@type\": \"schema:Organization\",\n      \"schema:name\": \"Wisconsin Public Service\",\n      \"schema:description\": \"Electric and natural gas utility serving northeast and central Wisconsin\"\n    },\n\n    \"PeoplesGas\": {\n      \"@id\": \"wec:PeoplesGas\",\n      \"@type\": \"schema:Organization\",\n      \"schema:name\": \"Peoples Gas\",\n      \"schema:description\"\
  : \"Natural gas utility serving Chicago metropolitan area\"\n    },\n\n    \"GreenButton\": {\n      \"@id\": \"https://www.energy.gov/data/green-button\",\n      \"@type\": \"@id\",\n      \"description\": \"Standard for accessing customer energy usage data from utilities\"\n    },\n\n    \"accountNumber\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"customerName\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"serviceAddress\": {\n      \"@id\": \"schema:address\",\n      \"@type\": \"schema:PostalAddress\"\n    },\n\n    \"accountStatus\": {\n      \"@id\": \"wec:accountStatus\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"serviceType\": {\n      \"@id\": \"wec:serviceType\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"currentBalance\": {\n      \"@id\": \"schema:price\",\n      \"@type\": \"xsd:decimal\"\n    },\n\n    \"dueDate\": {\n      \"@id\": \"schema:paymentDueDate\",\n      \"\
  @type\": \"xsd:date\"\n    },\n\n    \"usageReadings\": {\n      \"@id\": \"espi:IntervalReading\",\n      \"@type\": \"@id\"\n    },\n\n    \"totalUsage\": {\n      \"@id\": \"espi:value\",\n      \"@type\": \"xsd:decimal\"\n    },\n\n    \"unit\": {\n      \"@id\": \"espi:uom\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"customersAffected\": {\n      \"@id\": \"wec:customersAffected\",\n      \"@type\": \"xsd:integer\"\n    },\n\n    \"estimatedRestoration\": {\n      \"@id\": \"wec:estimatedRestoration\",\n      \"@type\": \"xsd:dateTime\"\n    },\n\n    \"FocusOnEnergy\": {\n      \"@id\": \"wec:FocusOnEnergy\",\n      \"@type\": \"@id\",\n      \"description\": \"Wisconsin's statewide energy efficiency program administered by WEC Energy Group\"\n    },\n\n    \"rateCode\": {\n      \"@id\": \"wec:rateCode\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/wec-energy/refs/heads/main/json-ld/wec-energy-context.jsonld
tags:
- Energy
- Electric Utility
- Fortune 500
- Green Button
- Illinois
- Michigan
- Minnesota
- Natural Gas
- NYSE
- Utility
- Wisconsin
- JSON-LD
- Linked Data
- Semantic Web
---
