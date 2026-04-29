---
class_count: 50
classes:
- InventoryItem
- InventoryList
- Order
- OrderList
- Shipment
- ShipmentList
- CatalogItem
- CatalogItemList
- Webpage
- WebpageList
- productNumber
- description
- brand
- totalQuantity
- warehouses
- items
- total
- cursor
- orderId
- purchaseOrderNumber
- status
- lineItems
- totalAmount
- shipToAddress
- shipmentId
- carrier
- proNumber
- trackingUrl
- weight
- name
- category
- subcategory
- specifications
- certifications
- listPrice
- upc
- imageUrl
- dataSheetUrl
- pageId
- url
- title
- type
- metaDescription
- orders
- shipments
- pages
- quantity
- unitPrice
- lineNumber
- quantityShipped
context_file: json-ld/acuity-brands-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/acuity-brands/refs/heads/main/json-ld/acuity-brands-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Acuity Brands from acuity-brands.
layout: jsonld
name: Acuity Brands Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: acuity
  uri: https://vocab.api-evangelist.com/acuity-brands/
properties:
- container: ''
  name: updatedAt
  type: dateTime
- container: ''
  name: orderDate
  type: date
- container: ''
  name: estimatedShipDate
  type: date
- container: ''
  name: actualShipDate
  type: date
- container: ''
  name: shipDate
  type: date
- container: ''
  name: estimatedDeliveryDate
  type: date
- container: ''
  name: lastModified
  type: dateTime
property_count: 7
provider_name: acuity-brands
provider_slug: acuity-brands
slug: acuity-brands-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"acuity\": \"https://vocab.api-evangelist.com/acuity-brands/\",\n\n    \"InventoryItem\": \"acuity:InventoryItem\",\n    \"InventoryList\": \"acuity:InventoryList\",\n    \"Order\": \"acuity:Order\",\n    \"OrderList\": \"acuity:OrderList\",\n    \"Shipment\": \"acuity:Shipment\",\n    \"ShipmentList\": \"acuity:ShipmentList\",\n    \"CatalogItem\": \"acuity:CatalogItem\",\n    \"CatalogItemList\": \"acuity:CatalogItemList\",\n    \"Webpage\": \"acuity:Webpage\",\n    \"WebpageList\": \"acuity:WebpageList\",\n\n    \"productNumber\": \"acuity:productNumber\",\n    \"description\": \"schema:description\",\n    \"brand\": \"schema:brand\",\n    \"totalQuantity\": \"acuity:totalQuantity\",\n    \"warehouses\": \"acuity:warehouses\",\n    \"updatedAt\": {\"@id\": \"acuity:updatedAt\", \"@type\": \"xsd:dateTime\"},\n    \"items\": \"acuity:items\"\
  ,\n    \"total\": \"acuity:total\",\n    \"cursor\": \"acuity:cursor\",\n    \"orderId\": \"acuity:orderId\",\n    \"purchaseOrderNumber\": \"acuity:purchaseOrderNumber\",\n    \"status\": \"acuity:status\",\n    \"orderDate\": {\"@id\": \"acuity:orderDate\", \"@type\": \"xsd:date\"},\n    \"estimatedShipDate\": {\"@id\": \"acuity:estimatedShipDate\", \"@type\": \"xsd:date\"},\n    \"actualShipDate\": {\"@id\": \"acuity:actualShipDate\", \"@type\": \"xsd:date\"},\n    \"lineItems\": \"acuity:lineItems\",\n    \"totalAmount\": \"acuity:totalAmount\",\n    \"shipToAddress\": \"acuity:shipToAddress\",\n    \"shipmentId\": \"acuity:shipmentId\",\n    \"carrier\": \"acuity:carrier\",\n    \"proNumber\": \"acuity:proNumber\",\n    \"trackingUrl\": \"acuity:trackingUrl\",\n    \"shipDate\": {\"@id\": \"acuity:shipDate\", \"@type\": \"xsd:date\"},\n    \"estimatedDeliveryDate\": {\"@id\": \"acuity:estimatedDeliveryDate\", \"@type\": \"xsd:date\"},\n    \"weight\": \"acuity:weight\",\n    \"name\"\
  : \"schema:name\",\n    \"category\": \"schema:category\",\n    \"subcategory\": \"acuity:subcategory\",\n    \"specifications\": \"acuity:specifications\",\n    \"certifications\": \"acuity:certifications\",\n    \"listPrice\": \"schema:price\",\n    \"upc\": \"schema:gtin12\",\n    \"imageUrl\": \"schema:image\",\n    \"dataSheetUrl\": \"acuity:dataSheetUrl\",\n    \"pageId\": \"acuity:pageId\",\n    \"url\": \"schema:url\",\n    \"title\": \"schema:name\",\n    \"type\": \"schema:additionalType\",\n    \"metaDescription\": \"schema:description\",\n    \"lastModified\": {\"@id\": \"schema:dateModified\", \"@type\": \"xsd:dateTime\"},\n    \"orders\": \"acuity:orders\",\n    \"shipments\": \"acuity:shipments\",\n    \"pages\": \"acuity:pages\",\n    \"quantity\": \"acuity:quantity\",\n    \"unitPrice\": \"schema:price\",\n    \"lineNumber\": \"acuity:lineNumber\",\n    \"quantityShipped\": \"acuity:quantityShipped\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/acuity-brands/refs/heads/main/json-ld/acuity-brands-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
