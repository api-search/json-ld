---
api_specs:
- filename: manhattan-associates-omni-openapi.yml
  format: yaml
  label: Manhattan Active Omni and Enterprise Promise & Fulfill API
  slug: manhattan-active-omni-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/manhattan-associates/refs/heads/main/openapi/manhattan-associates-omni-openapi.yml
- filename: manhattan-associates-wms-openapi.yml
  format: yaml
  label: Manhattan Active Supply Chain API
  slug: manhattan-active-supply-chain-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/manhattan-associates/refs/heads/main/openapi/manhattan-associates-wms-openapi.yml
class_count: 22
classes:
- Order
- orderId
- status
- shippingAddress
- Address
- firstName
- lastName
- street1
- city
- state
- postalCode
- country
- phone
- OrderLine
- lineId
- sku
- description
- totals
- currency
- Fulfillment
- trackingNumber
- carrier
context_file: json-ld/manhattan-associates-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/manhattan-associates/refs/heads/main/json-ld/manhattan-associates-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Manhattan Associates from manhattan-associates.
layout: jsonld
name: Manhattan Associates Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: manh
  uri: https://developer.manh.com/ontology/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: externalOrderId
  type: ''
- container: ''
  name: orderDate
  type: dateTime
- container: ''
  name: customerId
  type: ''
- container: set
  name: lines
  type: ''
- container: ''
  name: itemId
  type: ''
- container: ''
  name: quantity
  type: decimal
- container: ''
  name: unitPrice
  type: decimal
- container: ''
  name: orderTotal
  type: decimal
- container: set
  name: fulfillments
  type: ''
- container: ''
  name: estimatedDeliveryDate
  type: date
- container: ''
  name: shippedAt
  type: dateTime
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: updatedAt
  type: dateTime
property_count: 13
provider_name: manhattan-associates
provider_slug: manhattan-associates
slug: manhattan-associates-context
source_filename: manhattan-associates-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"manh\": \"https://developer.manh.com/ontology/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Order\": \"schema:Order\",\n    \"orderId\": \"schema:identifier\",\n    \"externalOrderId\": { \"@id\": \"schema:orderNumber\" },\n    \"status\": \"schema:orderStatus\",\n    \"orderDate\": {\n      \"@id\": \"schema:orderDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"customerId\": { \"@id\": \"schema:customer\" },\n    \"shippingAddress\": \"schema:shippingAddress\",\n    \"Address\": \"schema:PostalAddress\",\n    \"firstName\": \"schema:givenName\",\n    \"lastName\": \"schema:familyName\",\n    \"street1\": \"schema:streetAddress\",\n    \"city\": \"schema:addressLocality\",\n    \"state\": \"schema:addressRegion\",\n    \"postalCode\": \"schema:postalCode\",\n    \"country\": \"schema:addressCountry\",\n    \"phone\": \"schema:telephone\",\n    \"lines\"\
  : {\n      \"@id\": \"schema:orderedItem\",\n      \"@container\": \"@set\"\n    },\n    \"OrderLine\": \"schema:OrderItem\",\n    \"lineId\": \"schema:identifier\",\n    \"itemId\": { \"@id\": \"schema:orderItemNumber\" },\n    \"sku\": \"schema:sku\",\n    \"description\": \"schema:description\",\n    \"quantity\": {\n      \"@id\": \"schema:orderQuantity\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"unitPrice\": {\n      \"@id\": \"schema:price\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"totals\": \"schema:priceSpecification\",\n    \"orderTotal\": {\n      \"@id\": \"schema:totalPrice\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"currency\": \"schema:priceCurrency\",\n    \"fulfillments\": {\n      \"@id\": \"schema:delivery\",\n      \"@container\": \"@set\"\n    },\n    \"Fulfillment\": \"schema:ParcelDelivery\",\n    \"trackingNumber\": \"schema:trackingNumber\",\n    \"carrier\": \"schema:deliveryMethod\",\n    \"estimatedDeliveryDate\": {\n      \"@id\": \"\
  schema:expectedArrivalFrom\",\n      \"@type\": \"xsd:date\"\n    },\n    \"shippedAt\": {\n      \"@id\": \"schema:departureTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/manhattan-associates/refs/heads/main/json-ld/manhattan-associates-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
