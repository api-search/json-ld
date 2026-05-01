---
api_specs:
- filename: doordash-drive-openapi.yml
  format: yaml
  label: DoorDash Drive API
  slug: drive-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/doordash/refs/heads/main/openapi/doordash-drive-openapi.yml
- filename: doordash-drive-classic-openapi.yml
  format: yaml
  label: DoorDash Drive Classic API
  slug: drive-classic-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/doordash/refs/heads/main/openapi/doordash-drive-classic-openapi.yml
- filename: doordash-marketplace-openapi.yml
  format: yaml
  label: DoorDash Marketplace API
  slug: marketplace-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/doordash/refs/heads/main/openapi/doordash-marketplace-openapi.yml
- filename: doordash-item-management-openapi.yml
  format: yaml
  label: DoorDash Item Management API
  slug: marketplace-item-management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/doordash/refs/heads/main/openapi/doordash-item-management-openapi.yml
- filename: doordash-reporting-openapi.yml
  format: yaml
  label: DoorDash Reporting API
  slug: reporting-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/doordash/refs/heads/main/openapi/doordash-reporting-openapi.yml
class_count: 0
classes: []
context_file: json-ld/doordash-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/doordash/refs/heads/main/json-ld/doordash-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Doordash from doordash.
layout: jsonld
name: Doordash Context
namespaces:
- prefix: dd
  uri: https://developer.doordash.com/schemas/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Delivery
  type: ''
- container: ''
  name: Dasher
  type: ''
- container: ''
  name: Order
  type: ''
- container: ''
  name: MenuItem
  type: ''
- container: ''
  name: Business
  type: ''
- container: ''
  name: Store
  type: ''
- container: ''
  name: Report
  type: ''
property_count: 7
provider_name: doordash
provider_slug: doordash
slug: doordash-context
source_filename: doordash-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"dd\": \"https://developer.doordash.com/schemas/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Delivery\": {\n      \"@id\": \"dd:Delivery\",\n      \"@context\": {\n        \"external_delivery_id\": \"schema:identifier\",\n        \"delivery_status\": \"dd:deliveryStatus\",\n        \"fee\": \"schema:price\",\n        \"currency\": \"schema:priceCurrency\",\n        \"tip\": \"dd:tipAmount\",\n        \"order_value\": \"dd:orderValue\",\n        \"pickup_address\": {\n          \"@id\": \"dd:pickupAddress\",\n          \"@type\": \"schema:PostalAddress\"\n        },\n        \"pickup_business_name\": \"dd:pickupBusinessName\",\n        \"pickup_phone_number\": \"dd:pickupPhoneNumber\",\n        \"pickup_instructions\": \"dd:pickupInstructions\",\n        \"pickup_time_estimated\": {\n          \"@id\": \"dd:pickupTimeEstimated\"\
  ,\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"pickup_time_actual\": {\n          \"@id\": \"dd:pickupTimeActual\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"dropoff_address\": {\n          \"@id\": \"dd:dropoffAddress\",\n          \"@type\": \"schema:PostalAddress\"\n        },\n        \"dropoff_business_name\": \"dd:dropoffBusinessName\",\n        \"dropoff_phone_number\": \"dd:dropoffPhoneNumber\",\n        \"dropoff_instructions\": \"dd:dropoffInstructions\",\n        \"dropoff_time_estimated\": {\n          \"@id\": \"dd:dropoffTimeEstimated\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"dropoff_time_actual\": {\n          \"@id\": \"dd:dropoffTimeActual\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"tracking_url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"contains_alcohol\": \"dd:containsAlcohol\",\n        \"created_at\": {\n          \"@id\": \"dcterms:created\"\
  ,\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updated_at\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Dasher\": {\n      \"@id\": \"dd:Dasher\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"name\": \"schema:givenName\",\n        \"phone_number\": \"schema:telephone\",\n        \"location\": \"schema:GeoCoordinates\"\n      }\n    },\n\n    \"Order\": {\n      \"@id\": \"dd:Order\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"status\": \"schema:orderStatus\",\n        \"store_id\": \"dd:storeId\",\n        \"subtotal\": \"dd:subtotal\",\n        \"tax\": \"dd:taxAmount\",\n        \"delivery_fee\": \"dd:deliveryFee\",\n        \"tip\": \"dd:tipAmount\",\n        \"items\": {\n          \"@id\": \"schema:orderedItem\",\n          \"@container\": \"@set\"\n        },\n        \"customer\": \"schema:customer\",\n        \"delivery_address\"\
  : {\n          \"@id\": \"schema:deliveryAddress\",\n          \"@type\": \"schema:PostalAddress\"\n        },\n        \"special_instructions\": \"dd:specialInstructions\",\n        \"estimated_pickup_time\": {\n          \"@id\": \"dd:estimatedPickupTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"MenuItem\": {\n      \"@id\": \"dd:MenuItem\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"price\": \"schema:price\",\n        \"image_url\": {\n          \"@id\": \"schema:image\",\n          \"@type\": \"@id\"\n        },\n        \"is_active\": \"dd:isActive\",\n        \"option_groups\": {\n          \"@id\": \"dd:optionGroups\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Business\": {\n    \
  \  \"@id\": \"dd:Business\",\n      \"@context\": {\n        \"external_business_id\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\"\n      }\n    },\n\n    \"Store\": {\n      \"@id\": \"dd:Store\",\n      \"@context\": {\n        \"external_store_id\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"phone_number\": \"schema:telephone\",\n        \"address\": {\n          \"@id\": \"schema:address\",\n          \"@type\": \"schema:PostalAddress\"\n        }\n      }\n    },\n\n    \"Report\": {\n      \"@id\": \"dd:Report\",\n      \"@context\": {\n        \"report_id\": \"schema:identifier\",\n        \"report_type\": \"dd:reportType\",\n        \"start_date\": {\n          \"@id\": \"dd:startDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"end_date\": {\n          \"@id\": \"dd:endDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"status\": \"dd:reportStatus\",\n     \
  \   \"download_url\": {\n          \"@id\": \"schema:contentUrl\",\n          \"@type\": \"@id\"\n        },\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"completed_at\": {\n          \"@id\": \"dd:completedAt\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/doordash/refs/heads/main/json-ld/doordash-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
