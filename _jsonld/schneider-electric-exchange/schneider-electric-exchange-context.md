---
class_count: 32
classes:
- EcoStruxureAPI
- DataCenterDevice
- EnergyMeasurement
- BuildingAsset
- IndustrialAsset
- PartnerAPI
- ProductCatalog
- PartnerOrder
- PartnerQuote
- name
- description
- url
- identifier
- serialNumber
- manufacturer
- model
- dateCreated
- dateModified
- measurementValue
- measurementUnit
- alarmSeverity
- deviceStatus
- energyConsumption
- commercialReference
- listPrice
- netPrice
- warrantyStartDate
- warrantyEndDate
- Place
- Product
- Organization
- SoftwareApplication
context_file: json-ld/schneider-electric-exchange-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/schneider-electric-exchange/refs/heads/main/json-ld/schneider-electric-exchange-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Schneider Electric Exchange from Schneider Electric Exchange.
layout: jsonld
name: Schneider Electric Exchange Context
namespaces:
- prefix: se
  uri: https://exchange.se.com/vocab#
- prefix: ecostruxure
  uri: https://ecostruxure.se.com/vocab#
- prefix: iotlit
  uri: http://iotschema.org/
properties:
- container: ''
  name: hasDevice
  type: reference
- container: ''
  name: hasSensor
  type: reference
- container: ''
  name: hasAlarm
  type: reference
property_count: 3
provider_name: Schneider Electric Exchange
provider_slug: schneider-electric-exchange
slug: schneider-electric-exchange-context
source_filename: schneider-electric-exchange-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"se\": \"https://exchange.se.com/vocab#\",\n    \"ecostruxure\": \"https://ecostruxure.se.com/vocab#\",\n    \"iotlit\": \"http://iotschema.org/\",\n\n    \"EcoStruxureAPI\": \"ecostruxure:EcoStruxureAPI\",\n    \"DataCenterDevice\": \"ecostruxure:DataCenterDevice\",\n    \"EnergyMeasurement\": \"ecostruxure:EnergyMeasurement\",\n    \"BuildingAsset\": \"ecostruxure:BuildingAsset\",\n    \"IndustrialAsset\": \"ecostruxure:IndustrialAsset\",\n    \"PartnerAPI\": \"se:PartnerAPI\",\n    \"ProductCatalog\": \"se:ProductCatalog\",\n    \"PartnerOrder\": \"se:Order\",\n    \"PartnerQuote\": \"se:Quote\",\n\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"identifier\": \"schema:identifier\",\n    \"serialNumber\": \"schema:serialNumber\",\n    \"manufacturer\": \"schema:manufacturer\",\n    \"model\": \"schema:model\",\n    \"dateCreated\": \"schema:dateCreated\"\
  ,\n    \"dateModified\": \"schema:dateModified\",\n\n    \"hasDevice\": {\n      \"@id\": \"ecostruxure:hasDevice\",\n      \"@type\": \"@id\"\n    },\n    \"hasSensor\": {\n      \"@id\": \"iotlit:hasSensor\",\n      \"@type\": \"@id\"\n    },\n    \"hasAlarm\": {\n      \"@id\": \"ecostruxure:hasAlarm\",\n      \"@type\": \"@id\"\n    },\n    \"measurementValue\": \"schema:value\",\n    \"measurementUnit\": \"schema:unitCode\",\n    \"alarmSeverity\": \"ecostruxure:alarmSeverity\",\n    \"deviceStatus\": \"ecostruxure:deviceStatus\",\n    \"energyConsumption\": \"schema:energy\",\n    \"commercialReference\": \"se:commercialReference\",\n    \"listPrice\": \"schema:price\",\n    \"netPrice\": \"se:netPrice\",\n    \"warrantyStartDate\": \"schema:purchaseDate\",\n    \"warrantyEndDate\": \"schema:expires\",\n\n    \"Place\": \"schema:Place\",\n    \"Product\": \"schema:Product\",\n    \"Organization\": \"schema:Organization\",\n    \"SoftwareApplication\": \"schema:SoftwareApplication\"\
  \n  },\n  \"@graph\": [\n    {\n      \"@id\": \"https://exchange.se.com/\",\n      \"@type\": [\"Organization\", \"SoftwareApplication\"],\n      \"name\": \"Schneider Electric Exchange\",\n      \"description\": \"Developer platform providing EcoStruxure energy management and partner commerce APIs for Schneider Electric integrations.\",\n      \"url\": \"https://exchange.se.com/\",\n      \"manufacturer\": {\n        \"@id\": \"https://www.se.com/\",\n        \"@type\": \"Organization\",\n        \"name\": \"Schneider Electric\"\n      }\n    }\n  ]\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/schneider-electric-exchange/refs/heads/main/json-ld/schneider-electric-exchange-context.jsonld
tags:
- Building Automation
- Commerce APIs
- EcoStruxure
- Energy Management
- Industrial IoT
- Schneider Electric
- JSON-LD
- Linked Data
- Semantic Web
---
