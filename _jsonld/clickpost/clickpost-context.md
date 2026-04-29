---
class_count: 0
classes: []
context_file: json-ld/clickpost-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/clickpost/refs/heads/main/json-ld/clickpost-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Clickpost from ClickPost.
layout: jsonld
name: Clickpost Context
namespaces:
- prefix: cp
  uri: https://clickpost.ai/ns/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: Order
  type: ''
- container: ''
  name: Shipment
  type: ''
- container: ''
  name: TrackingEvent
  type: ''
- container: ''
  name: Carrier
  type: ''
- container: ''
  name: NdrAction
  type: ''
- container: ''
  name: ProofOfDelivery
  type: ''
property_count: 6
provider_name: ClickPost
provider_slug: clickpost
slug: clickpost-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"cp\": \"https://clickpost.ai/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Order\": {\n      \"@id\": \"schema:Order\",\n      \"@context\": {\n        \"id\": \"schema:orderNumber\",\n        \"waybill\": \"cp:waybill\",\n        \"awbNumber\": \"cp:awbNumber\",\n        \"carrier\": \"cp:carrier\",\n        \"status\": \"schema:orderStatus\",\n        \"createdAt\": {\n          \"@id\": \"schema:orderDate\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Shipment\": {\n      \"@id\": \"schema:ParcelDelivery\",\n      \"@context\": {\n        \"waybill\": \"cp:waybill\",\n        \"carrier\": \"cp:carrier\",\n        \"origin\": \"schema:originAddress\",\n        \"destination\": \"schema:deliveryAddress\",\n        \"weight\": \"cp:weightKg\",\n        \"trackingUrl\": \"schema:trackingUrl\",\n        \"expectedDelivery\": {\n\
  \          \"@id\": \"schema:expectedArrivalUntil\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"TrackingEvent\": {\n      \"@id\": \"cp:TrackingEvent\",\n      \"@context\": {\n        \"waybill\": \"cp:waybill\",\n        \"status\": \"cp:status\",\n        \"location\": \"schema:location\",\n        \"remark\": \"cp:remark\",\n        \"timestamp\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Carrier\": {\n      \"@id\": \"schema:DeliveryService\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"type\": \"cp:carrierType\"\n      }\n    },\n\n    \"NdrAction\": {\n      \"@id\": \"cp:NdrAction\",\n      \"@context\": {\n        \"waybill\": \"cp:waybill\",\n        \"action\": \"cp:action\",\n        \"reason\": \"cp:reason\",\n        \"createdAt\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\"\
  : \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"ProofOfDelivery\": {\n      \"@id\": \"cp:ProofOfDelivery\",\n      \"@context\": {\n        \"waybill\": \"cp:waybill\",\n        \"signatureUrl\": \"cp:signatureUrl\",\n        \"photoUrl\": \"cp:photoUrl\",\n        \"deliveredAt\": {\n          \"@id\": \"schema:deliveredAt\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/clickpost/refs/heads/main/json-ld/clickpost-context.jsonld
tags:
- Carriers
- Delivery
- E-Commerce Logistics
- Logistics
- Returns
- Shipping
- Supply Chain
- Tracking
- JSON-LD
- Linked Data
- Semantic Web
---
