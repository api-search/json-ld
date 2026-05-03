---
api_specs:
- filename: abilityone-procurement-list-api-openapi.yml
  format: yaml
  label: AbilityOne Procurement List API
  slug: procurement-list-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/us-abilityone-commission/refs/heads/main/openapi/abilityone-procurement-list-api-openapi.yml
class_count: 23
classes:
- Product
- ProductSearchResponse
- Service
- ServiceSearchResponse
- Agency
- AgencyListResponse
- APIError
- affiliate
- agencies
- error
- federalSupplyClass
- id
- location
- longDescription
- message
- nonprofitAffiliate
- nsn
- performingAgency
- productGroupName
- products
- serviceType
- services
- unitOfMeasure
context_file: json-ld/us-abilityone-commission-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/us-abilityone-commission/refs/heads/main/json-ld/us-abilityone-commission-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Us Abilityone Commission from US AbilityOne Commission.
layout: jsonld
name: Us Abilityone Commission Context
namespaces:
- prefix: abi
  uri: https://www.abilityone.gov/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: gov
  uri: https://www.w3.org/ns/gov/
properties:
- container: ''
  name: address
  type: ''
- container: ''
  name: approvalDate
  type: date
- container: ''
  name: city
  type: ''
- container: ''
  name: code
  type: integer
- container: ''
  name: description
  type: ''
- container: ''
  name: employeesBlind
  type: integer
- container: ''
  name: employeesDisabled
  type: integer
- container: ''
  name: limit
  type: integer
- container: ''
  name: name
  type: ''
- container: ''
  name: offset
  type: integer
- container: ''
  name: phone
  type: ''
- container: ''
  name: state
  type: ''
- container: ''
  name: status
  type: ''
- container: ''
  name: total
  type: integer
- container: ''
  name: unitPrice
  type: ''
- container: ''
  name: website
  type: ''
property_count: 16
provider_name: US AbilityOne Commission
provider_slug: us-abilityone-commission
slug: us-abilityone-commission-context
source_filename: us-abilityone-commission-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"abi\": \"https://www.abilityone.gov/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"gov\": \"https://www.w3.org/ns/gov/\",\n    \"Product\": \"abi:Product\",\n    \"ProductSearchResponse\": \"abi:ProductSearchResponse\",\n    \"Service\": \"abi:Service\",\n    \"ServiceSearchResponse\": \"abi:ServiceSearchResponse\",\n    \"Agency\": \"abi:Agency\",\n    \"AgencyListResponse\": \"abi:AgencyListResponse\",\n    \"APIError\": \"abi:APIError\",\n    \"address\": {\n      \"@id\": \"schema:address\"\n    },\n    \"affiliate\": \"abi:affiliate\",\n    \"agencies\": \"abi:agencies\",\n    \"approvalDate\": {\n      \"@id\": \"abi:approvalDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"city\": {\n      \"@id\": \"schema:addressLocality\"\n    },\n    \"code\": {\n      \"@id\": \"abi:code\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\"\
  \n    },\n    \"employeesBlind\": {\n      \"@id\": \"abi:employeesBlind\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"employeesDisabled\": {\n      \"@id\": \"abi:employeesDisabled\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"error\": \"abi:error\",\n    \"federalSupplyClass\": \"abi:federalSupplyClass\",\n    \"id\": \"abi:id\",\n    \"limit\": {\n      \"@id\": \"abi:limit\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"location\": \"abi:location\",\n    \"longDescription\": \"abi:longDescription\",\n    \"message\": \"abi:message\",\n    \"name\": {\n      \"@id\": \"schema:name\"\n    },\n    \"nonprofitAffiliate\": \"abi:nonprofitAffiliate\",\n    \"nsn\": \"abi:nsn\",\n    \"offset\": {\n      \"@id\": \"abi:offset\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"performingAgency\": \"abi:performingAgency\",\n    \"phone\": {\n      \"@id\": \"schema:telephone\"\n    },\n    \"productGroupName\": \"abi:productGroupName\",\n    \"products\": \"abi:products\",\n\
  \    \"serviceType\": \"abi:serviceType\",\n    \"services\": \"abi:services\",\n    \"state\": {\n      \"@id\": \"schema:addressRegion\"\n    },\n    \"status\": {\n      \"@id\": \"schema:status\"\n    },\n    \"total\": {\n      \"@id\": \"abi:total\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"unitOfMeasure\": \"abi:unitOfMeasure\",\n    \"unitPrice\": {\n      \"@id\": \"schema:price\"\n    },\n    \"website\": {\n      \"@id\": \"schema:url\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/us-abilityone-commission/refs/heads/main/json-ld/us-abilityone-commission-context.jsonld
tags:
- Federal Government
- Disability Employment
- Procurement
- Nonprofit
- Accessibility
- JSON-LD
- Linked Data
- Semantic Web
---
