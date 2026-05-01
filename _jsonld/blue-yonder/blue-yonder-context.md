---
api_specs:
- filename: blue-yonder-warehouse-management-openapi.yml
  format: yaml
  label: Blue Yonder Warehouse Management API
  slug: blue-yonder-warehouse-management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/blue-yonder/refs/heads/main/openapi/blue-yonder-warehouse-management-openapi.yml
class_count: 0
classes: []
context_file: json-ld/blue-yonder-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/blue-yonder/refs/heads/main/json-ld/blue-yonder-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Blue Yonder from blue-yonder.
layout: jsonld
name: Blue Yonder Context
namespaces:
- prefix: by
  uri: https://blueyonder.com/ontology/
- prefix: schema
  uri: https://schema.org/
- prefix: gs1
  uri: https://www.gs1.org/voc/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: InventoryPosition
  type: ''
- container: ''
  name: Order
  type: ''
- container: ''
  name: Receipt
  type: ''
- container: ''
  name: Address
  type: ''
property_count: 4
provider_name: blue-yonder
provider_slug: blue-yonder
slug: blue-yonder-context
source_filename: blue-yonder-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"by\": \"https://blueyonder.com/ontology/\",\n    \"schema\": \"https://schema.org/\",\n    \"gs1\": \"https://www.gs1.org/voc/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"InventoryPosition\": {\n      \"@id\": \"gs1:StoredProduct\",\n      \"@context\": {\n        \"positionId\": {\"@id\": \"by:positionId\"},\n        \"itemId\": {\"@id\": \"gs1:gtin\"},\n        \"itemDescription\": {\"@id\": \"schema:name\"},\n        \"locationId\": {\"@id\": \"by:locationId\"},\n        \"locationName\": {\"@id\": \"gs1:logisticUnitGroupingQuantity\"},\n        \"zone\": {\"@id\": \"by:warehouseZone\"},\n        \"quantityOnHand\": {\"@id\": \"gs1:quantity\", \"@type\": \"xsd:decimal\"},\n        \"quantityAvailable\": {\"@id\": \"by:quantityAvailable\", \"@type\": \"xsd:decimal\"},\n        \"quantityReserved\": {\"@id\": \"by:quantityReserved\", \"@type\": \"xsd:decimal\"},\n        \"unitOfMeasure\": {\"@id\": \"\
  gs1:unitCode\"},\n        \"lotNumber\": {\"@id\": \"gs1:lotNumber\"},\n        \"serialNumber\": {\"@id\": \"gs1:serialNumber\"},\n        \"expirationDate\": {\"@id\": \"gs1:expiryDate\", \"@type\": \"xsd:date\"},\n        \"status\": {\"@id\": \"by:inventoryStatus\"}\n      }\n    },\n\n    \"Order\": {\n      \"@id\": \"schema:Order\",\n      \"@context\": {\n        \"orderId\": {\"@id\": \"schema:orderNumber\"},\n        \"orderNumber\": {\"@id\": \"schema:identifier\"},\n        \"status\": {\"@id\": \"schema:orderStatus\"},\n        \"priority\": {\"@id\": \"by:fulfillmentPriority\"},\n        \"requestedShipDate\": {\"@id\": \"schema:expectedArrivalUntil\", \"@type\": \"xsd:date\"},\n        \"shipToAddress\": {\"@id\": \"schema:deliveryAddress\"},\n        \"lineItems\": {\"@id\": \"schema:orderedItem\", \"@container\": \"@set\"}\n      }\n    },\n\n    \"Receipt\": {\n      \"@id\": \"schema:ReceiveAction\",\n      \"@context\": {\n        \"receiptId\": {\"@id\": \"by:receiptId\"\
  },\n        \"referenceNumber\": {\"@id\": \"schema:identifier\"},\n        \"status\": {\"@id\": \"by:receiptStatus\"},\n        \"expectedDate\": {\"@id\": \"schema:expectedArrivalFrom\", \"@type\": \"xsd:date\"},\n        \"supplierId\": {\"@id\": \"schema:supplier\"},\n        \"lineItems\": {\"@id\": \"schema:object\", \"@container\": \"@set\"}\n      }\n    },\n\n    \"Address\": {\n      \"@id\": \"schema:PostalAddress\",\n      \"@context\": {\n        \"name\": {\"@id\": \"schema:name\"},\n        \"street1\": {\"@id\": \"schema:streetAddress\"},\n        \"city\": {\"@id\": \"schema:addressLocality\"},\n        \"state\": {\"@id\": \"schema:addressRegion\"},\n        \"postalCode\": {\"@id\": \"schema:postalCode\"},\n        \"country\": {\"@id\": \"schema:addressCountry\"}\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/blue-yonder/refs/heads/main/json-ld/blue-yonder-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
