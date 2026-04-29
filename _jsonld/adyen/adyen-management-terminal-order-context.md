---
class_count: 2
classes:
- TerminalOrderRequest
- TerminalOrder
context_file: json-ld/adyen-management-terminal-order-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-terminal-order-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Management Terminal Order from Adyen.
layout: jsonld
name: Adyen Management Terminal Order Context
namespaces:
- prefix: adyen
  uri: https://docs.adyen.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: billingEntityId
  type: string
- container: ''
  name: customerOrderReference
  type: string
- container: set
  name: items
  type: string
- container: ''
  name: orderType
  type: string
- container: ''
  name: shippingLocationId
  type: string
- container: ''
  name: taxId
  type: string
- container: ''
  name: billingEntity
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: orderDate
  type: string
- container: ''
  name: shippingLocation
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: trackingUrl
  type: string
property_count: 12
provider_name: Adyen
provider_slug: adyen
slug: adyen-management-terminal-order-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"TerminalOrderRequest\": \"adyen:TerminalOrderRequest\",\n    \"TerminalOrder\": \"adyen:TerminalOrder\",\n    \"billingEntityId\": {\n      \"@id\": \"adyen:billingEntityId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"customerOrderReference\": {\n      \"@id\": \"adyen:customerOrderReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"items\": {\n      \"@id\": \"adyen:items\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"orderType\": {\n      \"@id\": \"adyen:orderType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shippingLocationId\": {\n      \"@id\": \"adyen:shippingLocationId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"taxId\": {\n      \"@id\": \"adyen:taxId\",\n \
  \     \"@type\": \"xsd:string\"\n    },\n    \"billingEntity\": {\n      \"@id\": \"adyen:billingEntity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"adyen:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"orderDate\": {\n      \"@id\": \"adyen:orderDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shippingLocation\": {\n      \"@id\": \"adyen:shippingLocation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"adyen:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"trackingUrl\": {\n      \"@id\": \"adyen:trackingUrl\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-terminal-order-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
