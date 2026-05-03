---
api_specs:
- filename: united-states-postal-service-addresses-openapi.yml
  format: yaml
  label: USPS Addresses API
  slug: usps-addresses-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/united-states-postal-service/refs/heads/main/openapi/united-states-postal-service-addresses-openapi.yml
- filename: united-states-postal-service-tracking-openapi.yml
  format: yaml
  label: USPS Tracking API
  slug: usps-tracking-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/united-states-postal-service/refs/heads/main/openapi/united-states-postal-service-tracking-openapi.yml
- filename: united-states-postal-service-domestic-prices-openapi.yml
  format: yaml
  label: USPS Domestic Prices API
  slug: usps-domestic-prices-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/united-states-postal-service/refs/heads/main/openapi/united-states-postal-service-domestic-prices-openapi.yml
- filename: united-states-postal-service-carrier-pickup-openapi.yml
  format: yaml
  label: USPS Carrier Pickup API
  slug: usps-carrier-pickup-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/united-states-postal-service/refs/heads/main/openapi/united-states-postal-service-carrier-pickup-openapi.yml
class_count: 4
classes:
- MultipleTrackingRequest
- MultipleTrackingResult
- TrackingEvent
- TrackingResult
context_file: json-ld/united-states-postal-service-tracking-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/united-states-postal-service/refs/heads/main/json-ld/united-states-postal-service-tracking-context.jsonld
description: JSON-LD context defining the semantic vocabulary for United States Postal Service Tracking from United States Postal Service.
layout: jsonld
name: United States Postal Service Tracking Context
namespaces:
- prefix: usps
  uri: https://usps.api.usps.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: set
  name: trackingNumbers
  type: string
- container: set
  name: trackingResults
  type: ''
- container: ''
  name: trackingNumber
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: deliveryDate
  type: date
- container: ''
  name: EventTime
  type: string
- container: ''
  name: EventDate
  type: string
- container: ''
  name: Event
  type: string
- container: ''
  name: EventCity
  type: string
- container: ''
  name: EventState
  type: string
- container: ''
  name: EventZIPCode
  type: string
- container: ''
  name: EventCountry
  type: string
- container: ''
  name: FirmName
  type: string
- container: ''
  name: Name
  type: string
- container: ''
  name: AuthorizedAgent
  type: string
- container: ''
  name: DeliveryAttributeCode
  type: string
- container: ''
  name: TrackSummary
  type: string
- container: set
  name: TrackDetail
  type: string
property_count: 18
provider_name: United States Postal Service
provider_slug: united-states-postal-service
slug: united-states-postal-service-tracking-context
source_filename: united-states-postal-service-tracking-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"usps\": \"https://usps.api.usps.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"MultipleTrackingRequest\": \"usps:MultipleTrackingRequest\",\n    \"MultipleTrackingResult\": \"usps:MultipleTrackingResult\",\n    \"TrackingEvent\": \"usps:TrackingEvent\",\n    \"TrackingResult\": \"usps:TrackingResult\",\n    \"trackingNumbers\": {\n      \"@id\": \"usps:trackingNumbers\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"trackingResults\": {\n      \"@id\": \"usps:trackingResults\",\n      \"@container\": \"@set\"\n    },\n    \"trackingNumber\": {\n      \"@id\": \"usps:trackingNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"usps:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deliveryDate\": {\n      \"@id\": \"usps:deliveryDate\"\
  ,\n      \"@type\": \"xsd:date\"\n    },\n    \"EventTime\": {\n      \"@id\": \"usps:EventTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EventDate\": {\n      \"@id\": \"usps:EventDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Event\": {\n      \"@id\": \"usps:Event\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EventCity\": {\n      \"@id\": \"usps:EventCity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EventState\": {\n      \"@id\": \"usps:EventState\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EventZIPCode\": {\n      \"@id\": \"usps:EventZIPCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EventCountry\": {\n      \"@id\": \"usps:EventCountry\",\n      \"@type\": \"xsd:string\"\n    },\n    \"FirmName\": {\n      \"@id\": \"usps:FirmName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Name\": {\n      \"@id\": \"usps:Name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AuthorizedAgent\": {\n      \"@id\": \"usps:AuthorizedAgent\",\n  \
  \    \"@type\": \"xsd:string\"\n    },\n    \"DeliveryAttributeCode\": {\n      \"@id\": \"usps:DeliveryAttributeCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TrackSummary\": {\n      \"@id\": \"usps:TrackSummary\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TrackDetail\": {\n      \"@id\": \"usps:TrackDetail\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/united-states-postal-service/refs/heads/main/json-ld/united-states-postal-service-tracking-context.jsonld
tags:
- Government
- Postal Service
- Shipping
- Logistics
- Address Validation
- Package Tracking
- JSON-LD
- Linked Data
- Semantic Web
---
