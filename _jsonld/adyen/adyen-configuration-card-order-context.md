---
class_count: 3
classes:
- CardOrderItemDeliveryStatus
- CardOrderItem
- CardOrder
context_file: json-ld/adyen-configuration-card-order-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-configuration-card-order-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Configuration Card Order from Adyen.
layout: jsonld
name: Adyen Configuration Card Order Context
namespaces:
- prefix: adyen
  uri: https://docs.adyen.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: errorMessage
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: trackingNumber
  type: string
- container: ''
  name: balancePlatform
  type: string
- container: ''
  name: card
  type: string
- container: ''
  name: cardOrderItemId
  type: string
- container: ''
  name: creationDate
  type: dateTime
- container: ''
  name: id
  type: string
- container: ''
  name: paymentInstrumentId
  type: string
- container: ''
  name: pin
  type: string
- container: ''
  name: shippingMethod
  type: string
- container: ''
  name: beginDate
  type: dateTime
- container: ''
  name: cardManufacturingProfileId
  type: string
- container: ''
  name: closedDate
  type: dateTime
- container: ''
  name: endDate
  type: dateTime
- container: ''
  name: lockDate
  type: dateTime
- container: ''
  name: serviceCenter
  type: string
property_count: 17
provider_name: Adyen
provider_slug: adyen
slug: adyen-configuration-card-order-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"CardOrderItemDeliveryStatus\": \"adyen:CardOrderItemDeliveryStatus\",\n    \"CardOrderItem\": \"adyen:CardOrderItem\",\n    \"CardOrder\": \"adyen:CardOrder\",\n    \"errorMessage\": {\n      \"@id\": \"adyen:errorMessage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"adyen:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"trackingNumber\": {\n      \"@id\": \"adyen:trackingNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"balancePlatform\": {\n      \"@id\": \"adyen:balancePlatform\",\n      \"@type\": \"xsd:string\"\n    },\n    \"card\": {\n      \"@id\": \"adyen:card\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cardOrderItemId\": {\n      \"@id\": \"adyen:cardOrderItemId\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"creationDate\": {\n      \"@id\": \"adyen:creationDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"id\": {\n      \"@id\": \"adyen:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"paymentInstrumentId\": {\n      \"@id\": \"adyen:paymentInstrumentId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pin\": {\n      \"@id\": \"adyen:pin\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shippingMethod\": {\n      \"@id\": \"adyen:shippingMethod\",\n      \"@type\": \"xsd:string\"\n    },\n    \"beginDate\": {\n      \"@id\": \"adyen:beginDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"cardManufacturingProfileId\": {\n      \"@id\": \"adyen:cardManufacturingProfileId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"closedDate\": {\n      \"@id\": \"adyen:closedDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"endDate\": {\n      \"@id\": \"adyen:endDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"\
  lockDate\": {\n      \"@id\": \"adyen:lockDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"serviceCenter\": {\n      \"@id\": \"adyen:serviceCenter\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-configuration-card-order-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
