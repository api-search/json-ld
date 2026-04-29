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
source_filename: barcode-scanners-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"barcode\": \"https://api-evangelist.github.io/barcode-scanners/vocab/\",\n    \"schema\": \"https://schema.org/\",\n    \"gs1\": \"https://www.gs1.org/voc/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Barcode\": {\n      \"@id\": \"barcode:Barcode\",\n      \"@type\": \"@id\"\n    },\n    \"Product\": {\n      \"@id\": \"schema:Product\",\n      \"@type\": \"@id\"\n    },\n    \"BarcodeFormat\": {\n      \"@id\": \"barcode:BarcodeFormat\",\n      \"@type\": \"@id\"\n    },\n    \"barcodeNumber\": {\n      \"@id\": \"barcode:barcodeNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"barcodeFormat\": {\n      \"@id\": \"barcode:barcodeFormat\",\n      \"@type\": \"xsd:string\"\n    },\n    \"gtin\": {\n      \"@id\": \"gs1:gtin\",\n      \"@type\": \"xsd:string\"\n    },\n    \"upc\": {\n      \"@id\": \"barcode:upc\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ean\": {\n      \"@id\": \"barcode:ean\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"isbn\": {\n      \"@id\": \"barcode:isbn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"productName\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\",\n    \"brand\": \"schema:brand\",\n    \"category\": \"schema:category\",\n    \"image\": \"schema:image\",\n    \"price\": \"schema:price\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/barcode-scanners/refs/heads/main/json-ld/barcode-scanners-context.jsonld
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
