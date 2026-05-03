---
api_specs:
- filename: united-rentals-total-control-openapi.yml
  format: yaml
  label: United Rentals Total Control Integration API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/united-rentals/main/openapi/united-rentals-total-control-openapi.yml
class_count: 0
classes: []
context_file: json-ld/united-rentals-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/united-rentals/refs/heads/main/json-ld/united-rentals-context.jsonld
description: JSON-LD context defining the semantic vocabulary for United Rentals from United Rentals.
layout: jsonld
name: United Rentals Context
namespaces:
- prefix: ur
  uri: https://schema.unitedrentals.com/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: Equipment
  type: reference
- container: ''
  name: equipmentId
  type: string
- container: ''
  name: name
  type: string
- container: ''
  name: category
  type: string
- container: ''
  name: manufacturer
  type: reference
- container: ''
  name: model
  type: string
- container: ''
  name: specifications
  type: reference
- container: ''
  name: dailyRate
  type: decimal
- container: ''
  name: weeklyRate
  type: decimal
- container: ''
  name: monthlyRate
  type: decimal
- container: ''
  name: available
  type: boolean
- container: ''
  name: RentalOrder
  type: reference
- container: ''
  name: rentalId
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: startDate
  type: date
- container: ''
  name: endDate
  type: date
- container: ''
  name: returnDate
  type: date
- container: ''
  name: jobSite
  type: string
- container: ''
  name: deliveryAddress
  type: reference
- container: ''
  name: purchaseOrderNumber
  type: string
- container: ''
  name: totalCost
  type: decimal
- container: ''
  name: branchId
  type: string
- container: ''
  name: Invoice
  type: reference
- container: ''
  name: invoiceId
  type: string
- container: ''
  name: invoiceNumber
  type: string
- container: ''
  name: issueDate
  type: date
- container: ''
  name: dueDate
  type: date
- container: ''
  name: subtotal
  type: decimal
- container: ''
  name: tax
  type: decimal
- container: ''
  name: totalAmount
  type: decimal
- container: list
  name: lineItems
  type: reference
- container: ''
  name: Branch
  type: reference
property_count: 32
provider_name: United Rentals
provider_slug: united-rentals
slug: united-rentals-context
source_filename: united-rentals-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"ur\": \"https://schema.unitedrentals.com/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Equipment\": {\n      \"@id\": \"ur:Equipment\",\n      \"@type\": \"@id\",\n      \"subClassOf\": \"schema:Product\"\n    },\n    \"equipmentId\": { \"@id\": \"ur:equipmentId\", \"@type\": \"xsd:string\" },\n    \"name\": { \"@id\": \"schema:name\", \"@type\": \"xsd:string\" },\n    \"category\": { \"@id\": \"schema:category\", \"@type\": \"xsd:string\" },\n    \"manufacturer\": { \"@id\": \"schema:manufacturer\", \"@type\": \"@id\" },\n    \"model\": { \"@id\": \"schema:model\", \"@type\": \"xsd:string\" },\n    \"specifications\": { \"@id\": \"ur:specifications\", \"@type\": \"@id\" },\n    \"dailyRate\": { \"@id\": \"ur:dailyRate\", \"@type\": \"xsd:decimal\" },\n    \"weeklyRate\": { \"@id\": \"ur:weeklyRate\", \"@type\": \"xsd:decimal\" },\n    \"monthlyRate\": { \"@id\"\
  : \"ur:monthlyRate\", \"@type\": \"xsd:decimal\" },\n    \"available\": { \"@id\": \"schema:availability\", \"@type\": \"xsd:boolean\" },\n\n    \"RentalOrder\": {\n      \"@id\": \"ur:RentalOrder\",\n      \"@type\": \"@id\",\n      \"subClassOf\": \"schema:Order\"\n    },\n    \"rentalId\": { \"@id\": \"ur:rentalId\", \"@type\": \"xsd:string\" },\n    \"status\": { \"@id\": \"ur:status\", \"@type\": \"xsd:string\" },\n    \"startDate\": { \"@id\": \"schema:startDate\", \"@type\": \"xsd:date\" },\n    \"endDate\": { \"@id\": \"schema:endDate\", \"@type\": \"xsd:date\" },\n    \"returnDate\": { \"@id\": \"ur:returnDate\", \"@type\": \"xsd:date\" },\n    \"jobSite\": { \"@id\": \"ur:jobSite\", \"@type\": \"xsd:string\" },\n    \"deliveryAddress\": { \"@id\": \"schema:deliveryAddress\", \"@type\": \"@id\" },\n    \"purchaseOrderNumber\": { \"@id\": \"ur:purchaseOrderNumber\", \"@type\": \"xsd:string\" },\n    \"totalCost\": { \"@id\": \"schema:totalPrice\", \"@type\": \"xsd:decimal\" },\n\
  \    \"branchId\": { \"@id\": \"ur:branchId\", \"@type\": \"xsd:string\" },\n\n    \"Invoice\": {\n      \"@id\": \"ur:Invoice\",\n      \"@type\": \"@id\",\n      \"subClassOf\": \"schema:Invoice\"\n    },\n    \"invoiceId\": { \"@id\": \"ur:invoiceId\", \"@type\": \"xsd:string\" },\n    \"invoiceNumber\": { \"@id\": \"schema:confirmationNumber\", \"@type\": \"xsd:string\" },\n    \"issueDate\": { \"@id\": \"ur:issueDate\", \"@type\": \"xsd:date\" },\n    \"dueDate\": { \"@id\": \"ur:dueDate\", \"@type\": \"xsd:date\" },\n    \"subtotal\": { \"@id\": \"ur:subtotal\", \"@type\": \"xsd:decimal\" },\n    \"tax\": { \"@id\": \"ur:taxAmount\", \"@type\": \"xsd:decimal\" },\n    \"totalAmount\": { \"@id\": \"schema:totalPrice\", \"@type\": \"xsd:decimal\" },\n    \"lineItems\": { \"@id\": \"ur:hasLineItem\", \"@type\": \"@id\", \"@container\": \"@list\" },\n\n    \"Branch\": {\n      \"@id\": \"ur:Branch\",\n      \"@type\": \"@id\",\n      \"subClassOf\": \"schema:LocalBusiness\"\n    }\n\
  \  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/united-rentals/refs/heads/main/json-ld/united-rentals-context.jsonld
tags:
- Equipment Rental
- Procurement
- Supply Chain
- Construction
- Fortune 500
- JSON-LD
- Linked Data
- Semantic Web
---
