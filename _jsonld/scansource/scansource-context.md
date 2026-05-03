---
api_specs:
- filename: scansource-product-openapi.yml
  format: yaml
  label: ScanSource Product API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/scansource/refs/heads/main/openapi/scansource-product-openapi.yml
- filename: scansource-sales-order-openapi.yml
  format: yaml
  label: ScanSource Sales Order API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/scansource/refs/heads/main/openapi/scansource-sales-order-openapi.yml
- filename: scansource-invoice-openapi.yml
  format: yaml
  label: ScanSource Invoice API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/scansource/refs/heads/main/openapi/scansource-invoice-openapi.yml
class_count: 7
classes:
- Product
- Order
- Invoice
- Organization
- PostalAddress
- Offer
- PriceSpecification
context_file: json-ld/scansource-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/scansource/refs/heads/main/json-ld/scansource-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Scansource from ScanSource.
layout: jsonld
name: Scansource Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: scansource
  uri: https://scansource.com/vocab#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: itemNumber
  type: string
- container: ''
  name: manufacturerPartNumber
  type: string
- container: ''
  name: manufacturer
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: categoryPath
  type: string
- container: ''
  name: upc
  type: string
- container: ''
  name: isObsolete
  type: boolean
- container: ''
  name: weight
  type: decimal
- container: ''
  name: dimensions
  type: reference
- container: ''
  name: unitPrice
  type: decimal
- container: ''
  name: currency
  type: string
- container: ''
  name: quantityAvailable
  type: integer
- container: ''
  name: estimatedShipDate
  type: date
- container: ''
  name: salesOrderNumber
  type: string
- container: ''
  name: poNumber
  type: string
- container: ''
  name: customerNumber
  type: string
- container: ''
  name: orderDate
  type: dateTime
- container: ''
  name: orderStatus
  type: string
- container: ''
  name: totalAmount
  type: decimal
- container: ''
  name: shipToAddress
  type: reference
- container: set
  name: lineItems
  type: ''
- container: ''
  name: invoiceNumber
  type: string
- container: ''
  name: invoiceDate
  type: date
- container: ''
  name: dueDate
  type: date
- container: ''
  name: trackingNumber
  type: string
- container: ''
  name: carrier
  type: string
- container: ''
  name: warehouse
  type: string
property_count: 27
provider_name: ScanSource
provider_slug: scansource
slug: scansource-context
source_filename: scansource-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"scansource\": \"https://scansource.com/vocab#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Product\": \"schema:Product\",\n    \"Order\": \"schema:Order\",\n    \"Invoice\": \"schema:Invoice\",\n    \"Organization\": \"schema:Organization\",\n    \"PostalAddress\": \"schema:PostalAddress\",\n    \"Offer\": \"schema:Offer\",\n    \"PriceSpecification\": \"schema:PriceSpecification\",\n\n    \"itemNumber\": {\n      \"@id\": \"scansource:itemNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"manufacturerPartNumber\": {\n      \"@id\": \"schema:mpn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"manufacturer\": {\n      \"@id\": \"schema:manufacturer\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"categoryPath\": {\n      \"@id\": \"scansource:categoryPath\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"upc\": {\n      \"@id\": \"schema:gtin12\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isObsolete\": {\n      \"@id\": \"scansource:isObsolete\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"weight\": {\n      \"@id\": \"schema:weight\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"dimensions\": {\n      \"@id\": \"schema:size\",\n      \"@type\": \"@id\"\n    },\n    \"unitPrice\": {\n      \"@id\": \"schema:price\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"currency\": {\n      \"@id\": \"schema:priceCurrency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"quantityAvailable\": {\n      \"@id\": \"schema:inventoryLevel\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"estimatedShipDate\": {\n      \"@id\": \"schema:expectedArrivalFrom\",\n      \"@type\": \"xsd:date\"\n    },\n    \"salesOrderNumber\": {\n      \"@id\": \"scansource:salesOrderNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"poNumber\"\
  : {\n      \"@id\": \"schema:orderNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"customerNumber\": {\n      \"@id\": \"scansource:customerNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"orderDate\": {\n      \"@id\": \"schema:orderDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"orderStatus\": {\n      \"@id\": \"schema:orderStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"totalAmount\": {\n      \"@id\": \"schema:totalPrice\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"shipToAddress\": {\n      \"@id\": \"schema:shippingAddress\",\n      \"@type\": \"@id\"\n    },\n    \"lineItems\": {\n      \"@id\": \"schema:orderedItem\",\n      \"@container\": \"@set\"\n    },\n    \"invoiceNumber\": {\n      \"@id\": \"scansource:invoiceNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"invoiceDate\": {\n      \"@id\": \"schema:dateIssued\",\n      \"@type\": \"xsd:date\"\n    },\n    \"dueDate\": {\n      \"@id\": \"schema:paymentDueDate\",\n \
  \     \"@type\": \"xsd:date\"\n    },\n    \"trackingNumber\": {\n      \"@id\": \"schema:trackingNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"carrier\": {\n      \"@id\": \"schema:deliveryMethod\",\n      \"@type\": \"xsd:string\"\n    },\n    \"warehouse\": {\n      \"@id\": \"scansource:warehouse\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/scansource/refs/heads/main/json-ld/scansource-context.jsonld
tags:
- ScanSource
- Distribution
- Barcode
- Point Of Sale
- AIDC
- Inventory
- Order Management
- E-Commerce
- JSON-LD
- Linked Data
- Semantic Web
---
