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
class_count: 5
classes:
- PickupAddress
- PickupPackage
- PickupRequest
- PickupResponse
- PickupUpdateRequest
context_file: json-ld/united-states-postal-service-carrier-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/united-states-postal-service/refs/heads/main/json-ld/united-states-postal-service-carrier-context.jsonld
description: JSON-LD context defining the semantic vocabulary for United States Postal Service Carrier from United States Postal Service.
layout: jsonld
name: United States Postal Service Carrier Context
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
  name: streetAddress
  type: string
- container: ''
  name: secondaryAddress
  type: string
- container: ''
  name: city
  type: string
- container: ''
  name: state
  type: string
- container: ''
  name: ZIPCode
  type: string
- container: ''
  name: serviceType
  type: string
- container: ''
  name: count
  type: integer
- container: ''
  name: firstName
  type: string
- container: ''
  name: lastName
  type: string
- container: ''
  name: pickupAddress
  type: string
- container: set
  name: packages
  type: string
- container: ''
  name: packageLocation
  type: string
- container: ''
  name: specialInstructions
  type: string
- container: ''
  name: confirmationNumber
  type: string
- container: ''
  name: dayOfWeek
  type: string
- container: ''
  name: pickupDate
  type: date
- container: ''
  name: address
  type: string
property_count: 17
provider_name: United States Postal Service
provider_slug: united-states-postal-service
slug: united-states-postal-service-carrier-context
source_filename: united-states-postal-service-carrier-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"usps\": \"https://usps.api.usps.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"PickupAddress\": \"usps:PickupAddress\",\n    \"PickupPackage\": \"usps:PickupPackage\",\n    \"PickupRequest\": \"usps:PickupRequest\",\n    \"PickupResponse\": \"usps:PickupResponse\",\n    \"PickupUpdateRequest\": \"usps:PickupUpdateRequest\",\n    \"streetAddress\": {\n      \"@id\": \"usps:streetAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"secondaryAddress\": {\n      \"@id\": \"usps:secondaryAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"city\": {\n      \"@id\": \"usps:city\",\n      \"@type\": \"xsd:string\"\n    },\n    \"state\": {\n      \"@id\": \"usps:state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ZIPCode\": {\n      \"@id\": \"usps:ZIPCode\",\n      \"@type\": \"xsd:string\"\n  \
  \  },\n    \"serviceType\": {\n      \"@id\": \"usps:serviceType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"count\": {\n      \"@id\": \"usps:count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"firstName\": {\n      \"@id\": \"usps:firstName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastName\": {\n      \"@id\": \"usps:lastName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pickupAddress\": {\n      \"@id\": \"usps:pickupAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"packages\": {\n      \"@id\": \"usps:packages\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"packageLocation\": {\n      \"@id\": \"usps:packageLocation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"specialInstructions\": {\n      \"@id\": \"usps:specialInstructions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"confirmationNumber\": {\n      \"@id\": \"usps:confirmationNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dayOfWeek\"\
  : {\n      \"@id\": \"usps:dayOfWeek\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pickupDate\": {\n      \"@id\": \"usps:pickupDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"address\": {\n      \"@id\": \"usps:address\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/united-states-postal-service/refs/heads/main/json-ld/united-states-postal-service-carrier-context.jsonld
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
