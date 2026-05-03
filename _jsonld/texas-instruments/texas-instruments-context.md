---
api_specs:
- filename: texas-instruments-store-openapi.yml
  format: yaml
  label: Texas Instruments Store API
  slug: ti-store-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/texas-instruments/refs/heads/main/openapi/texas-instruments-store-openapi.yml
- filename: texas-instruments-product-information-openapi.yml
  format: yaml
  label: Texas Instruments Product Information API
  slug: ti-product-information-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/texas-instruments/refs/heads/main/openapi/texas-instruments-product-information-openapi.yml
class_count: 3
classes:
- Product
- description
- Order
context_file: json-ld/texas-instruments-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/texas-instruments/refs/heads/main/json-ld/texas-instruments-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Texas Instruments from Texas Instruments.
layout: jsonld
name: Texas Instruments Context
namespaces:
- prefix: schema
  uri: http://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: gs1
  uri: https://www.gs1.org/voc/
properties:
- container: ''
  name: tiPartNumber
  type: string
- container: ''
  name: genericPartNumber
  type: string
- container: ''
  name: packageType
  type: string
- container: ''
  name: pinCount
  type: integer
- container: ''
  name: lifeCycle
  type: string
- container: ''
  name: quantity
  type: integer
- container: ''
  name: minimumOrderQuantity
  type: integer
- container: ''
  name: pricing
  type: reference
- container: ''
  name: priceBreaks
  type: reference
- container: ''
  name: priceBreakQuantity
  type: integer
- container: ''
  name: price
  type: decimal
- container: ''
  name: currency
  type: string
- container: ''
  name: eccn
  type: string
- container: ''
  name: htsCode
  type: string
- container: ''
  name: rohs
  type: boolean
- container: ''
  name: aecQ100
  type: boolean
- container: ''
  name: orderNumber
  type: string
- container: ''
  name: orderStatus
  type: string
- container: ''
  name: lineItems
  type: reference
- container: ''
  name: totalPrice
  type: decimal
- container: ''
  name: shippingAddress
  type: reference
- container: ''
  name: billingAddress
  type: reference
- container: ''
  name: trackingNumber
  type: string
- container: ''
  name: carrier
  type: string
- container: ''
  name: dataSheetUrl
  type: reference
- container: ''
  name: productPageUrl
  type: reference
property_count: 26
provider_name: Texas Instruments
provider_slug: texas-instruments
slug: texas-instruments-context
source_filename: texas-instruments-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.ti.com/api/v1/\",\n    \"schema\": \"http://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"gs1\": \"https://www.gs1.org/voc/\",\n\n    \"Product\": \"schema:Product\",\n    \"tiPartNumber\": {\n      \"@id\": \"schema:sku\",\n      \"@type\": \"xsd:string\"\n    },\n    \"genericPartNumber\": {\n      \"@id\": \"schema:productID\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\",\n    \"packageType\": {\n      \"@id\": \"https://schema.ti.com/api/v1/packageType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pinCount\": {\n      \"@id\": \"https://schema.ti.com/api/v1/pinCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"lifeCycle\": {\n      \"@id\": \"schema:itemCondition\",\n      \"@type\": \"xsd:string\"\n    },\n    \"quantity\": {\n      \"@id\": \"schema:inventoryLevel\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"minimumOrderQuantity\"\
  : {\n      \"@id\": \"schema:orderQuantity\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"pricing\": {\n      \"@id\": \"schema:offers\",\n      \"@type\": \"@id\"\n    },\n    \"priceBreaks\": {\n      \"@id\": \"schema:priceSpecification\",\n      \"@type\": \"@id\"\n    },\n    \"priceBreakQuantity\": {\n      \"@id\": \"schema:eligibleQuantity\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"price\": {\n      \"@id\": \"schema:price\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"currency\": {\n      \"@id\": \"schema:priceCurrency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eccn\": {\n      \"@id\": \"https://schema.ti.com/api/v1/eccn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"htsCode\": {\n      \"@id\": \"gs1:additionalProductDescription\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rohs\": {\n      \"@id\": \"https://schema.ti.com/api/v1/rohsCompliant\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"aecQ100\": {\n      \"@id\": \"https://schema.ti.com/api/v1/aecQ100\"\
  ,\n      \"@type\": \"xsd:boolean\"\n    },\n    \"Order\": \"schema:Order\",\n    \"orderNumber\": {\n      \"@id\": \"schema:orderNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"orderStatus\": {\n      \"@id\": \"schema:orderStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lineItems\": {\n      \"@id\": \"schema:orderedItem\",\n      \"@type\": \"@id\"\n    },\n    \"totalPrice\": {\n      \"@id\": \"schema:totalPaymentDue\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"shippingAddress\": {\n      \"@id\": \"schema:deliveryAddress\",\n      \"@type\": \"@id\"\n    },\n    \"billingAddress\": {\n      \"@id\": \"schema:billingAddress\",\n      \"@type\": \"@id\"\n    },\n    \"trackingNumber\": {\n      \"@id\": \"schema:trackingNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"carrier\": {\n      \"@id\": \"schema:deliveryMethod\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dataSheetUrl\": {\n      \"@id\": \"schema:subjectOf\",\n      \"@type\": \"\
  @id\"\n    },\n    \"productPageUrl\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/texas-instruments/refs/heads/main/json-ld/texas-instruments-context.jsonld
tags:
- Electronics
- Ordering
- Semiconductors
- Supply Chain
- JSON-LD
- Linked Data
- Semantic Web
---
