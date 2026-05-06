---
class_count: 8
classes:
- AmericoldEdiWarehouseShippingOrder
- AmericoldEdiWarehouseShippingAdvice
- AmericoldI3plInventorySnapshot
- ShippingOrderLineItem
- ShippingAdviceLineItem
- InventoryLot
- description
- name
context_file: json-ld/americold-realty-trust-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/americold-realty-trust/refs/heads/main/json-ld/americold-realty-trust-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Americold Realty Trust from Americold Realty Trust.
layout: jsonld
name: Americold Realty Trust Context
namespaces:
- prefix: americold
  uri: https://www.americold.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: actualShipDate
  type: dateTime
- container: ''
  name: adviceId
  type: string
- container: ''
  name: billOfLadingNumber
  type: string
- container: ''
  name: carrier
  type: reference
- container: ''
  name: carrierScac
  type: string
- container: ''
  name: casesAvailable
  type: integer
- container: ''
  name: casesCommitted
  type: integer
- container: ''
  name: casesOnHand
  type: integer
- container: ''
  name: casesOnHold
  type: integer
- container: ''
  name: depositorId
  type: string
- container: ''
  name: depositorName
  type: string
- container: ''
  name: expirationDate
  type: date
- container: ''
  name: facilityCode
  type: string
- container: ''
  name: facilityName
  type: string
- container: ''
  name: gtin
  type: string
- container: ''
  name: lastReceivedDate
  type: dateTime
- container: set
  name: lineItems
  type: reference
- container: ''
  name: lineNumber
  type: integer
- container: ''
  name: loadTemperatureF
  type: decimal
- container: set
  name: lots
  type: reference
- container: ''
  name: lotNumber
  type: string
- container: ''
  name: manufactureDate
  type: date
- container: ''
  name: maxTemperatureF
  type: decimal
- container: ''
  name: minTemperatureF
  type: decimal
- container: ''
  name: orderDate
  type: date
- container: ''
  name: proNumber
  type: string
- container: ''
  name: productDescription
  type: string
- container: ''
  name: purposeCode
  type: string
- container: ''
  name: quantity
  type: integer
- container: ''
  name: quantityOrdered
  type: integer
- container: ''
  name: quantityShipped
  type: integer
- container: ''
  name: quantityShortage
  type: integer
- container: ''
  name: requestedDeliveryDate
  type: date
- container: ''
  name: requestedShipDate
  type: date
- container: ''
  name: scac
  type: string
- container: ''
  name: sealNumber
  type: string
- container: ''
  name: shipmentId
  type: string
- container: ''
  name: shipTo
  type: reference
- container: ''
  name: sku
  type: string
- container: ''
  name: snapshotDate
  type: dateTime
- container: ''
  name: snapshotId
  type: string
- container: ''
  name: specialInstructions
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: temperatureRequirements
  type: reference
- container: ''
  name: temperatureZone
  type: string
- container: ''
  name: totalCases
  type: integer
- container: ''
  name: totalPallets
  type: integer
- container: ''
  name: totalWeightLbs
  type: decimal
- container: ''
  name: trailerNumber
  type: string
- container: ''
  name: unitOfMeasure
  type: string
- container: ''
  name: weightLbs
  type: decimal
- container: ''
  name: zone
  type: string
property_count: 52
provider_name: Americold Realty Trust
provider_slug: americold-realty-trust
slug: americold-realty-trust-context
source_filename: americold-realty-trust-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"americold\": \"https://www.americold.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"AmericoldEdiWarehouseShippingOrder\": \"americold:AmericoldEdiWarehouseShippingOrder\",\n    \"AmericoldEdiWarehouseShippingAdvice\": \"americold:AmericoldEdiWarehouseShippingAdvice\",\n    \"AmericoldI3plInventorySnapshot\": \"americold:AmericoldI3plInventorySnapshot\",\n    \"ShippingOrderLineItem\": \"americold:ShippingOrderLineItem\",\n    \"ShippingAdviceLineItem\": \"americold:ShippingAdviceLineItem\",\n    \"InventoryLot\": \"americold:InventoryLot\",\n\n    \"actualShipDate\": {\n      \"@id\": \"americold:actualShipDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"adviceId\": {\n      \"@id\": \"americold:adviceId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"billOfLadingNumber\": {\n      \"@id\": \"\
  americold:billOfLadingNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"carrier\": {\n      \"@id\": \"americold:carrier\",\n      \"@type\": \"@id\"\n    },\n    \"carrierScac\": {\n      \"@id\": \"americold:carrierScac\",\n      \"@type\": \"xsd:string\"\n    },\n    \"casesAvailable\": {\n      \"@id\": \"americold:casesAvailable\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"casesCommitted\": {\n      \"@id\": \"americold:casesCommitted\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"casesOnHand\": {\n      \"@id\": \"americold:casesOnHand\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"casesOnHold\": {\n      \"@id\": \"americold:casesOnHold\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"depositorId\": {\n      \"@id\": \"americold:depositorId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"depositorName\": {\n      \"@id\": \"americold:depositorName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\",\n    \"expirationDate\"\
  : {\n      \"@id\": \"americold:expirationDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"facilityCode\": {\n      \"@id\": \"americold:facilityCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"facilityName\": {\n      \"@id\": \"americold:facilityName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"gtin\": {\n      \"@id\": \"americold:gtin\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastReceivedDate\": {\n      \"@id\": \"americold:lastReceivedDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"lineItems\": {\n      \"@id\": \"americold:lineItems\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"lineNumber\": {\n      \"@id\": \"americold:lineNumber\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"loadTemperatureF\": {\n      \"@id\": \"americold:loadTemperatureF\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"lots\": {\n      \"@id\": \"americold:lots\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n\
  \    \"lotNumber\": {\n      \"@id\": \"americold:lotNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"manufactureDate\": {\n      \"@id\": \"americold:manufactureDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"maxTemperatureF\": {\n      \"@id\": \"americold:maxTemperatureF\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"minTemperatureF\": {\n      \"@id\": \"americold:minTemperatureF\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"name\": \"schema:name\",\n    \"orderDate\": {\n      \"@id\": \"americold:orderDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"proNumber\": {\n      \"@id\": \"americold:proNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"productDescription\": {\n      \"@id\": \"americold:productDescription\",\n      \"@type\": \"xsd:string\"\n    },\n    \"purposeCode\": {\n      \"@id\": \"americold:purposeCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"quantity\": {\n      \"@id\": \"americold:quantity\",\n      \"@type\": \"\
  xsd:integer\"\n    },\n    \"quantityOrdered\": {\n      \"@id\": \"americold:quantityOrdered\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"quantityShipped\": {\n      \"@id\": \"americold:quantityShipped\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"quantityShortage\": {\n      \"@id\": \"americold:quantityShortage\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"requestedDeliveryDate\": {\n      \"@id\": \"americold:requestedDeliveryDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"requestedShipDate\": {\n      \"@id\": \"americold:requestedShipDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"scac\": {\n      \"@id\": \"americold:scac\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sealNumber\": {\n      \"@id\": \"americold:sealNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shipmentId\": {\n      \"@id\": \"americold:shipmentId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shipTo\": {\n      \"@id\": \"americold:shipTo\",\n      \"@type\":\
  \ \"@id\"\n    },\n    \"sku\": {\n      \"@id\": \"americold:sku\",\n      \"@type\": \"xsd:string\"\n    },\n    \"snapshotDate\": {\n      \"@id\": \"americold:snapshotDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"snapshotId\": {\n      \"@id\": \"americold:snapshotId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"specialInstructions\": {\n      \"@id\": \"americold:specialInstructions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"americold:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"temperatureRequirements\": {\n      \"@id\": \"americold:temperatureRequirements\",\n      \"@type\": \"@id\"\n    },\n    \"temperatureZone\": {\n      \"@id\": \"americold:temperatureZone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"totalCases\": {\n      \"@id\": \"americold:totalCases\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"totalPallets\": {\n      \"@id\": \"americold:totalPallets\",\n      \"@type\": \"xsd:integer\"\
  \n    },\n    \"totalWeightLbs\": {\n      \"@id\": \"americold:totalWeightLbs\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"trailerNumber\": {\n      \"@id\": \"americold:trailerNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"unitOfMeasure\": {\n      \"@id\": \"americold:unitOfMeasure\",\n      \"@type\": \"xsd:string\"\n    },\n    \"weightLbs\": {\n      \"@id\": \"americold:weightLbs\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"zone\": {\n      \"@id\": \"americold:zone\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/americold-realty-trust/refs/heads/main/json-ld/americold-realty-trust-context.jsonld
tags:
- Cold Storage
- Logistics
- Supply Chain
- Warehousing
- Real Estate
- Temperature-Controlled
- Cold Chain
- EDI
- 3PL
- JSON-LD
- Linked Data
- Semantic Web
---
