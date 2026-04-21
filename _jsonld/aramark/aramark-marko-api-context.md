---
class_count: 15
classes:
- ErrorResponse
- OrganizationUnit
- OrganizationResponse
- Service
- ServiceResponse
- Product
- ProductResponse
- ProfitCenter
- ProfitCenterResponse
- RevenueSnapshot
- RevenueSnapshotResponse
- POSTransaction
- POSResponse
- id
- name
context_file: json-ld/aramark-marko-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/aramark/refs/heads/main/json-ld/aramark-marko-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Aramark Marko Api from Aramark.
layout: jsonld
name: Aramark Marko Api Context
namespaces:
- prefix: aramark
  uri: https://marko.aramark.net/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: active
  type: boolean
- container: set
  name: allergens
  type: string
- container: ''
  name: amount
  type: decimal
- container: ''
  name: averageTicket
  type: decimal
- container: ''
  name: calories
  type: integer
- container: ''
  name: category
  type: string
- container: ''
  name: code
  type: integer
- container: ''
  name: count
  type: integer
- container: set
  name: data
  type: string
- container: ''
  name: items
  type: integer
- container: ''
  name: locationCount
  type: integer
- container: ''
  name: locationId
  type: string
- container: ''
  name: message
  type: string
- container: ''
  name: parentId
  type: string
- container: ''
  name: paymentMethod
  type: string
- container: ''
  name: period
  type: string
- container: ''
  name: price
  type: decimal
- container: ''
  name: profitCenterId
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: timestamp
  type: dateTime
- container: ''
  name: totalRevenue
  type: decimal
- container: ''
  name: transactionCount
  type: integer
- container: ''
  name: transactionId
  type: string
- container: ''
  name: type
  type: string
property_count: 24
provider_name: Aramark
provider_slug: aramark
slug: aramark-marko-api-context
tags:
- Food Services
- Facilities Management
- Uniform Services
- Data Platform
- Fortune 500
- JSON-LD
- Linked Data
- Semantic Web
---
