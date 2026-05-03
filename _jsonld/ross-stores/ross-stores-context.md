---
class_count: 0
classes: []
context_file: json-ld/ross-stores-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/ross-stores/refs/heads/main/json-ld/ross-stores-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Ross Stores from Ross Stores.
layout: jsonld
name: Ross Stores Context
namespaces:
- prefix: ross
  uri: https://corporate.rossstores.com/vocab/
- prefix: schema
  uri: https://schema.org/
- prefix: gs1
  uri: https://www.gs1.org/voc/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: RossStores
  type: schema:Corporation
- container: ''
  name: Store
  type: schema:Store
- container: ''
  name: SupplierOrder
  type: schema:Order
- container: ''
  name: MerchandiseItem
  type: schema:Product
- container: ''
  name: AdvanceShipNotice
  type: schema:ParcelDelivery
property_count: 5
provider_name: Ross Stores
provider_slug: ross-stores
slug: ross-stores-context
source_filename: ross-stores-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"ross\": \"https://corporate.rossstores.com/vocab/\",\n    \"schema\": \"https://schema.org/\",\n    \"gs1\": \"https://www.gs1.org/voc/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"RossStores\": {\n      \"@id\": \"ross:RossStores\",\n      \"@type\": \"schema:Corporation\",\n      \"@context\": {\n        \"name\": { \"@id\": \"schema:name\" },\n        \"description\": { \"@id\": \"schema:description\" },\n        \"url\": { \"@id\": \"schema:url\" },\n        \"tickerSymbol\": { \"@id\": \"schema:tickerSymbol\" },\n        \"numberOfLocations\": { \"@id\": \"ross:numberOfLocations\" },\n        \"retailBanners\": { \"@id\": \"ross:retailBanners\" }\n      }\n    },\n\n    \"Store\": {\n      \"@id\": \"ross:Store\",\n      \"@type\": \"schema:Store\",\n      \"@context\": {\n        \"name\": { \"@id\": \"schema:name\" },\n        \"banner\": { \"@id\"\
  : \"ross:banner\" },\n        \"address\": { \"@id\": \"schema:address\" },\n        \"storeNumber\": { \"@id\": \"ross:storeNumber\" }\n      }\n    },\n\n    \"SupplierOrder\": {\n      \"@id\": \"ross:SupplierOrder\",\n      \"@type\": \"schema:Order\",\n      \"@context\": {\n        \"orderNumber\": { \"@id\": \"schema:orderNumber\" },\n        \"supplier\": { \"@id\": \"schema:seller\" },\n        \"orderDate\": { \"@id\": \"schema:orderDate\" },\n        \"lineItems\": { \"@id\": \"schema:orderedItem\" },\n        \"totalAmount\": { \"@id\": \"schema:price\" }\n      }\n    },\n\n    \"MerchandiseItem\": {\n      \"@id\": \"ross:MerchandiseItem\",\n      \"@type\": \"schema:Product\",\n      \"@context\": {\n        \"upc\": { \"@id\": \"gs1:gtin\" },\n        \"description\": { \"@id\": \"schema:description\" },\n        \"brand\": { \"@id\": \"schema:brand\" },\n        \"category\": { \"@id\": \"schema:category\" },\n        \"unitCost\": { \"@id\": \"schema:price\" }\n     \
  \ }\n    },\n\n    \"AdvanceShipNotice\": {\n      \"@id\": \"ross:AdvanceShipNotice\",\n      \"@type\": \"schema:ParcelDelivery\",\n      \"@context\": {\n        \"shipmentId\": { \"@id\": \"schema:trackingNumber\" },\n        \"purchaseOrderNumber\": { \"@id\": \"ross:purchaseOrderNumber\" },\n        \"shipDate\": { \"@id\": \"schema:expectedArrivalFrom\" },\n        \"contents\": { \"@id\": \"schema:hasDeliveryMethod\" }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/ross-stores/refs/heads/main/json-ld/ross-stores-context.jsonld
tags:
- Fashion
- Fortune 500
- Off-Price Retail
- Retail
- Supply Chain
- JSON-LD
- Linked Data
- Semantic Web
---
