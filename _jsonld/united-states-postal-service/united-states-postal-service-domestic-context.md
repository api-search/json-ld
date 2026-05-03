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
class_count: 8
classes:
- BaseRateRequest
- ExtraServiceRateRequest
- ExtraServiceRateResponse
- RateResponse
- TotalRateRequest
- TotalRateResponse
- name
- description
context_file: json-ld/united-states-postal-service-domestic-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/united-states-postal-service/refs/heads/main/json-ld/united-states-postal-service-domestic-context.jsonld
description: JSON-LD context defining the semantic vocabulary for United States Postal Service Domestic from United States Postal Service.
layout: jsonld
name: United States Postal Service Domestic Context
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
- container: ''
  name: originZIPCode
  type: string
- container: ''
  name: destinationZIPCode
  type: string
- container: ''
  name: weight
  type: decimal
- container: ''
  name: length
  type: decimal
- container: ''
  name: width
  type: decimal
- container: ''
  name: height
  type: decimal
- container: ''
  name: mailClass
  type: string
- container: ''
  name: processingCategory
  type: string
- container: ''
  name: destinationEntryFacilityType
  type: string
- container: ''
  name: rateIndicator
  type: string
- container: ''
  name: extraServiceCode
  type: string
- container: set
  name: extraServices
  type: ''
- container: ''
  name: price
  type: decimal
- container: set
  name: rates
  type: ''
- container: ''
  name: skuCode
  type: string
- container: ''
  name: maxWeight
  type: decimal
- container: set
  name: fees
  type: ''
- container: ''
  name: totalBasePrice
  type: decimal
- container: ''
  name: totalPrice
  type: decimal
property_count: 19
provider_name: United States Postal Service
provider_slug: united-states-postal-service
slug: united-states-postal-service-domestic-context
source_filename: united-states-postal-service-domestic-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"usps\": \"https://usps.api.usps.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"BaseRateRequest\": \"usps:BaseRateRequest\",\n    \"ExtraServiceRateRequest\": \"usps:ExtraServiceRateRequest\",\n    \"ExtraServiceRateResponse\": \"usps:ExtraServiceRateResponse\",\n    \"RateResponse\": \"usps:RateResponse\",\n    \"TotalRateRequest\": \"usps:TotalRateRequest\",\n    \"TotalRateResponse\": \"usps:TotalRateResponse\",\n    \"originZIPCode\": {\n      \"@id\": \"usps:originZIPCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"destinationZIPCode\": {\n      \"@id\": \"usps:destinationZIPCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"weight\": {\n      \"@id\": \"usps:weight\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"length\": {\n      \"@id\": \"usps:length\",\n      \"@type\": \"xsd:decimal\"\
  \n    },\n    \"width\": {\n      \"@id\": \"usps:width\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"height\": {\n      \"@id\": \"usps:height\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"mailClass\": {\n      \"@id\": \"usps:mailClass\",\n      \"@type\": \"xsd:string\"\n    },\n    \"processingCategory\": {\n      \"@id\": \"usps:processingCategory\",\n      \"@type\": \"xsd:string\"\n    },\n    \"destinationEntryFacilityType\": {\n      \"@id\": \"usps:destinationEntryFacilityType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rateIndicator\": {\n      \"@id\": \"usps:rateIndicator\",\n      \"@type\": \"xsd:string\"\n    },\n    \"extraServiceCode\": {\n      \"@id\": \"usps:extraServiceCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"extraServices\": {\n      \"@id\": \"usps:extraServices\",\n      \"@container\": \"@set\"\n    },\n    \"name\": \"schema:name\",\n    \"price\": {\n      \"@id\": \"usps:price\",\n      \"@type\": \"xsd:decimal\"\n    },\n\
  \    \"rates\": {\n      \"@id\": \"usps:rates\",\n      \"@container\": \"@set\"\n    },\n    \"skuCode\": {\n      \"@id\": \"usps:skuCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\",\n    \"maxWeight\": {\n      \"@id\": \"usps:maxWeight\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"fees\": {\n      \"@id\": \"usps:fees\",\n      \"@container\": \"@set\"\n    },\n    \"totalBasePrice\": {\n      \"@id\": \"usps:totalBasePrice\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"totalPrice\": {\n      \"@id\": \"usps:totalPrice\",\n      \"@type\": \"xsd:decimal\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/united-states-postal-service/refs/heads/main/json-ld/united-states-postal-service-domestic-context.jsonld
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
