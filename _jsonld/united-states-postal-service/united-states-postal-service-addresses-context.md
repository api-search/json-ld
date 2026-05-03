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
class_count: 3
classes:
- Address
- CityState
- ZIPCodeResult
context_file: json-ld/united-states-postal-service-addresses-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/united-states-postal-service/refs/heads/main/json-ld/united-states-postal-service-addresses-context.jsonld
description: JSON-LD context defining the semantic vocabulary for United States Postal Service Addresses from United States Postal Service.
layout: jsonld
name: United States Postal Service Addresses Context
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
  name: firm
  type: string
- container: ''
  name: streetAddress
  type: string
- container: ''
  name: streetAddressAbbreviation
  type: string
- container: ''
  name: secondaryAddress
  type: string
- container: ''
  name: city
  type: string
- container: ''
  name: cityAbbreviation
  type: string
- container: ''
  name: state
  type: string
- container: ''
  name: postalCode
  type: string
- container: ''
  name: province
  type: string
- container: ''
  name: ZIPCode
  type: string
- container: ''
  name: ZIPPlus4
  type: string
- container: ''
  name: urbanization
  type: string
- container: ''
  name: classificationCode
  type: string
- container: ''
  name: DPVConfirmation
  type: string
- container: ''
  name: DPVCMRA
  type: string
- container: ''
  name: DPVFootnotes
  type: string
property_count: 16
provider_name: United States Postal Service
provider_slug: united-states-postal-service
slug: united-states-postal-service-addresses-context
source_filename: united-states-postal-service-addresses-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"usps\": \"https://usps.api.usps.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Address\": \"usps:Address\",\n    \"CityState\": \"usps:CityState\",\n    \"ZIPCodeResult\": \"usps:ZIPCodeResult\",\n    \"firm\": {\n      \"@id\": \"usps:firm\",\n      \"@type\": \"xsd:string\"\n    },\n    \"streetAddress\": {\n      \"@id\": \"usps:streetAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"streetAddressAbbreviation\": {\n      \"@id\": \"usps:streetAddressAbbreviation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"secondaryAddress\": {\n      \"@id\": \"usps:secondaryAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"city\": {\n      \"@id\": \"usps:city\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cityAbbreviation\": {\n      \"@id\": \"usps:cityAbbreviation\",\n      \"@type\": \"\
  xsd:string\"\n    },\n    \"state\": {\n      \"@id\": \"usps:state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"postalCode\": {\n      \"@id\": \"usps:postalCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"province\": {\n      \"@id\": \"usps:province\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ZIPCode\": {\n      \"@id\": \"usps:ZIPCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ZIPPlus4\": {\n      \"@id\": \"usps:ZIPPlus4\",\n      \"@type\": \"xsd:string\"\n    },\n    \"urbanization\": {\n      \"@id\": \"usps:urbanization\",\n      \"@type\": \"xsd:string\"\n    },\n    \"classificationCode\": {\n      \"@id\": \"usps:classificationCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DPVConfirmation\": {\n      \"@id\": \"usps:DPVConfirmation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DPVCMRA\": {\n      \"@id\": \"usps:DPVCMRA\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DPVFootnotes\": {\n      \"@id\": \"usps:DPVFootnotes\",\n    \
  \  \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/united-states-postal-service/refs/heads/main/json-ld/united-states-postal-service-addresses-context.jsonld
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
