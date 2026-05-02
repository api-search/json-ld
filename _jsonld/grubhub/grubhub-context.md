---
api_specs:
- filename: grubhub-menu-openapi.yml
  format: yaml
  label: Grubhub Menu API
  slug: menu-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/grubhub/refs/heads/main/openapi/grubhub-menu-openapi.yml
- filename: grubhub-orders-openapi.yml
  format: yaml
  label: Grubhub Orders API
  slug: orders-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/grubhub/refs/heads/main/openapi/grubhub-orders-openapi.yml
- filename: grubhub-merchant-data-openapi.yml
  format: yaml
  label: Grubhub Merchant Data API
  slug: merchant-data-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/grubhub/refs/heads/main/openapi/grubhub-merchant-data-openapi.yml
- filename: grubhub-merchant-schedules-openapi.yml
  format: yaml
  label: Grubhub Merchant Schedules API
  slug: merchant-schedules-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/grubhub/refs/heads/main/openapi/grubhub-merchant-schedules-openapi.yml
- filename: grubhub-deliveries-openapi.yml
  format: yaml
  label: Grubhub Deliveries API
  slug: deliveries-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/grubhub/refs/heads/main/openapi/grubhub-deliveries-openapi.yml
- filename: grubhub-onboarding-openapi.yml
  format: yaml
  label: Grubhub Onboarding API
  slug: onboarding-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/grubhub/refs/heads/main/openapi/grubhub-onboarding-openapi.yml
class_count: 0
classes: []
context_file: json-ld/grubhub-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/grubhub/refs/heads/main/json-ld/grubhub-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Grubhub from grubhub.
layout: jsonld
name: Grubhub Context
namespaces:
- prefix: grubhub
  uri: https://developer.grubhub.com/vocab/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Merchant
  type: ''
- container: ''
  name: Order
  type: ''
- container: ''
  name: MenuItem
  type: ''
- container: ''
  name: MenuSection
  type: ''
- container: ''
  name: Delivery
  type: ''
- container: ''
  name: Driver
  type: ''
- container: ''
  name: Address
  type: ''
property_count: 7
provider_name: grubhub
provider_slug: grubhub
slug: grubhub-context
source_filename: grubhub-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"grubhub\": \"https://developer.grubhub.com/vocab/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Merchant\": {\n      \"@id\": \"grubhub:Merchant\",\n      \"@context\": {\n        \"merchant_id\": \"grubhub:merchantId\",\n        \"external_id\": \"grubhub:externalId\",\n        \"name\": \"schema:name\",\n        \"status\": \"grubhub:merchantStatus\",\n        \"phone\": \"schema:telephone\",\n        \"address\": \"schema:address\",\n        \"tax_rate\": \"grubhub:taxRate\",\n        \"cuisine_types\": {\n          \"@id\": \"grubhub:cuisineTypes\",\n          \"@container\": \"@set\"\n        },\n        \"fulfillment_types\": {\n          \"@id\": \"grubhub:fulfillmentTypes\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Order\": {\n      \"@id\": \"grubhub:Order\",\n      \"@context\"\
  : {\n        \"order_uuid\": \"grubhub:orderUuid\",\n        \"merchant_id\": \"grubhub:merchantId\",\n        \"status\": \"grubhub:orderStatus\",\n        \"fulfillment_type\": \"grubhub:fulfillmentType\",\n        \"placed_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"confirmed_at\": {\n          \"@id\": \"grubhub:confirmedAt\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"estimated_delivery_at\": {\n          \"@id\": \"grubhub:estimatedDeliveryAt\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"customer\": \"grubhub:customer\",\n        \"items\": {\n          \"@id\": \"grubhub:orderItems\",\n          \"@container\": \"@set\"\n        },\n        \"totals\": \"grubhub:orderTotals\",\n        \"delivery_address\": \"schema:deliveryAddress\",\n        \"special_instructions\": \"grubhub:specialInstructions\"\n      }\n    },\n\n    \"MenuItem\": {\n      \"@id\": \"grubhub:MenuItem\"\
  ,\n      \"@context\": {\n        \"external_id\": \"grubhub:externalId\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"price\": \"schema:price\",\n        \"available\": \"schema:availability\",\n        \"modifier_prompts\": {\n          \"@id\": \"grubhub:modifierPrompts\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"MenuSection\": {\n      \"@id\": \"grubhub:MenuSection\",\n      \"@context\": {\n        \"external_id\": \"grubhub:externalId\",\n        \"name\": \"schema:name\",\n        \"items\": {\n          \"@id\": \"grubhub:menuItems\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Delivery\": {\n      \"@id\": \"grubhub:Delivery\",\n      \"@context\": {\n        \"delivery_id\": \"grubhub:deliveryId\",\n        \"order_uuid\": \"grubhub:orderUuid\",\n        \"status\": \"grubhub:deliveryStatus\",\n        \"driver\": \"grubhub:driver\",\n        \"pickup_eta\": {\n\
  \          \"@id\": \"grubhub:pickupEta\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"dropoff_eta\": {\n          \"@id\": \"grubhub:dropoffEta\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"tracking_url\": {\n          \"@id\": \"grubhub:trackingUrl\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Driver\": {\n      \"@id\": \"grubhub:Driver\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"phone\": \"schema:telephone\",\n        \"delivery_method\": \"grubhub:deliveryMethod\",\n        \"latitude\": \"schema:latitude\",\n        \"longitude\": \"schema:longitude\"\n      }\n    },\n\n    \"Address\": {\n      \"@id\": \"schema:PostalAddress\",\n      \"@context\": {\n        \"street_address\": \"schema:streetAddress\",\n        \"city\": \"schema:addressLocality\",\n        \"state\": \"schema:addressRegion\",\n        \"zip\": \"schema:postalCode\",\n        \"latitude\": \"schema:latitude\",\n       \
  \ \"longitude\": \"schema:longitude\"\n      }\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/grubhub/refs/heads/main/json-ld/grubhub-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
