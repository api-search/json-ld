---
class_count: 39
classes:
- PaintProduct
- ColorSwatch
- Supplier
- PurchaseOrder
- Invoice
- productId
- sku
- name
- brand
- category
- colorCode
- colorName
- colorFamily
- hexCode
- rgb
- finish
- coverage
- dryTime
- application
- substrate
- base
- size
- currency
- upc
- inStock
- supplierId
- supplierName
- duns
- taxId
- status
- ediCapabilities
- apiIntegrations
- paymentTerms
- certifications
- street1
- city
- state
- postalCode
- country
context_file: json-ld/sherwin-williams-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/sherwin-williams/refs/heads/main/json-ld/sherwin-williams-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Sherwin Williams from Sherwin-Williams.
layout: jsonld
name: Sherwin Williams Context
namespaces:
- prefix: sw
  uri: https://www.sherwin-williams.com/schema/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: coats
  type: integer
- container: ''
  name: price
  type: float
- container: ''
  name: contact
  type: schema:ContactPoint
- container: ''
  name: address
  type: schema:PostalAddress
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: updatedAt
  type: dateTime
property_count: 6
provider_name: Sherwin-Williams
provider_slug: sherwin-williams
slug: sherwin-williams-context
source_filename: sherwin-williams-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"sw\": \"https://www.sherwin-williams.com/schema/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"PaintProduct\": \"schema:Product\",\n    \"ColorSwatch\": \"sw:ColorSwatch\",\n    \"Supplier\": \"schema:Organization\",\n    \"PurchaseOrder\": \"schema:Order\",\n    \"Invoice\": \"schema:Invoice\",\n\n    \"productId\": \"schema:identifier\",\n    \"sku\": \"schema:sku\",\n    \"name\": \"schema:name\",\n    \"brand\": \"schema:brand\",\n    \"category\": \"schema:category\",\n    \"colorCode\": \"sw:colorCode\",\n    \"colorName\": \"sw:colorName\",\n    \"colorFamily\": \"sw:colorFamily\",\n    \"hexCode\": \"sw:hexColor\",\n    \"rgb\": \"sw:rgbValue\",\n\n    \"finish\": \"sw:paintFinish\",\n    \"coverage\": \"sw:coverage\",\n    \"coats\": { \"@id\": \"sw:recommendedCoats\", \"@type\": \"xsd:integer\" },\n    \"dryTime\": \"sw:dryingTime\",\n    \"application\": \"sw:applicationMethod\"\
  ,\n    \"substrate\": \"sw:substrate\",\n    \"base\": \"sw:paintBase\",\n    \"size\": \"schema:size\",\n\n    \"price\": { \"@id\": \"schema:price\", \"@type\": \"xsd:float\" },\n    \"currency\": \"schema:priceCurrency\",\n    \"upc\": \"schema:gtin12\",\n    \"inStock\": \"schema:availability\",\n\n    \"supplierId\": \"schema:identifier\",\n    \"supplierName\": \"schema:legalName\",\n    \"duns\": \"schema:duns\",\n    \"taxId\": \"schema:taxID\",\n    \"status\": \"schema:status\",\n    \"contact\": { \"@id\": \"schema:contactPoint\", \"@type\": \"schema:ContactPoint\" },\n    \"address\": { \"@id\": \"schema:address\", \"@type\": \"schema:PostalAddress\" },\n\n    \"ediCapabilities\": \"sw:ediTransactionTypes\",\n    \"apiIntegrations\": \"sw:apiIntegrationTypes\",\n    \"paymentTerms\": \"schema:paymentAccepted\",\n    \"certifications\": \"schema:hasCredential\",\n\n    \"street1\": \"schema:streetAddress\",\n    \"city\": \"schema:addressLocality\",\n    \"state\": \"schema:addressRegion\"\
  ,\n    \"postalCode\": \"schema:postalCode\",\n    \"country\": \"schema:addressCountry\",\n\n    \"createdAt\": { \"@id\": \"schema:dateCreated\", \"@type\": \"xsd:dateTime\" },\n    \"updatedAt\": { \"@id\": \"schema:dateModified\", \"@type\": \"xsd:dateTime\" }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/sherwin-williams/refs/heads/main/json-ld/sherwin-williams-context.jsonld
tags:
- B2B
- Construction
- Fortune 500
- Paints
- Retail
- Supply Chain
- JSON-LD
- Linked Data
- Semantic Web
---
