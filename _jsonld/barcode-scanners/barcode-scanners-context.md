---
class_count: 5
classes:
- description
- brand
- category
- image
- price
context_file: json-ld/barcode-scanners-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/barcode-scanners/refs/heads/main/json-ld/barcode-scanners-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Barcode Scanners from Barcode Scanners.
layout: jsonld
name: Barcode Scanners Context
namespaces:
- prefix: barcode
  uri: https://api-evangelist.github.io/barcode-scanners/vocab/
- prefix: schema
  uri: https://schema.org/
- prefix: gs1
  uri: https://www.gs1.org/voc/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: Barcode
  type: reference
- container: ''
  name: Product
  type: reference
- container: ''
  name: BarcodeFormat
  type: reference
- container: ''
  name: barcodeNumber
  type: string
- container: ''
  name: barcodeFormat
  type: string
- container: ''
  name: gtin
  type: string
- container: ''
  name: upc
  type: string
- container: ''
  name: ean
  type: string
- container: ''
  name: isbn
  type: string
- container: ''
  name: productName
  type: string
property_count: 10
provider_name: Barcode Scanners
provider_slug: barcode-scanners
slug: barcode-scanners-context
tags:
- Barcodes
- Inventory
- Product Lookup
- QR Codes
- Retail
- Scanning
- Supply Chain
- JSON-LD
- Linked Data
- Semantic Web
---
