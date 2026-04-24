---
class_count: 6
classes:
- Product
- Vendor
- PricingResponse
- Webhook
- name
- description
context_file: json-ld/blissfully-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/blissfully/refs/heads/main/json-ld/blissfully-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Blissfully from Blissfully.
layout: jsonld
name: Blissfully Context
namespaces:
- prefix: vendr
  uri: https://api.vendr.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: id
  type: string
- container: ''
  name: website
  type: reference
- container: ''
  name: url
  type: reference
- container: ''
  name: category
  type: string
- container: ''
  name: vendor_id
  type: string
- container: ''
  name: product_id
  type: string
- container: set
  name: features
  type: string
- container: set
  name: add_ons
  type: string
- container: set
  name: events
  type: string
- container: ''
  name: fair_price_per_seat
  type: decimal
- container: ''
  name: currency
  type: string
- container: ''
  name: confidence
  type: string
- container: ''
  name: negotiation_guidance
  type: string
- container: ''
  name: active
  type: boolean
property_count: 14
provider_name: Blissfully
provider_slug: blissfully
slug: blissfully-context
tags:
- Procurement
- SaaS Discovery
- SaaS Management
- Software Procurement
- Spend Optimization
- Vendor Management
- JSON-LD
- Linked Data
- Semantic Web
---
