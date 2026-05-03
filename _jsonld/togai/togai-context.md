---
api_specs:
- filename: togai-openapi.yml
  format: yaml
  label: Togai API
  slug: togai-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/togai/refs/heads/main/openapi/togai-openapi.yml
class_count: 21
classes:
- Customer
- Account
- Event
- PricePlan
- Invoice
- Credit
- UsageMeter
- id
- name
- primaryEmail
- billingAddress
- addressLine1
- addressLine2
- city
- state
- country
- zipCode
- schemaName
- dimensions
- attributes
- creditAmount
context_file: json-ld/togai-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/togai/refs/heads/main/json-ld/togai-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Togai from Togai.
layout: jsonld
name: Togai Context
namespaces:
- prefix: togai
  uri: https://docs.togai.com/api-reference/#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: updatedAt
  type: dateTime
- container: ''
  name: accountId
  type: reference
- container: ''
  name: timestamp
  type: dateTime
- container: ''
  name: effectiveFrom
  type: dateTime
- container: ''
  name: effectiveTo
  type: dateTime
property_count: 6
provider_name: Togai
provider_slug: togai
slug: togai-context
source_filename: togai-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"togai\": \"https://docs.togai.com/api-reference/#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Customer\": \"schema:Organization\",\n    \"Account\": \"togai:Account\",\n    \"Event\": \"schema:Action\",\n    \"PricePlan\": \"schema:Offer\",\n    \"Invoice\": \"schema:Invoice\",\n    \"Credit\": \"togai:Credit\",\n    \"UsageMeter\": \"togai:UsageMeter\",\n    \"id\": \"@id\",\n    \"name\": \"schema:name\",\n    \"primaryEmail\": \"schema:email\",\n    \"billingAddress\": \"schema:address\",\n    \"addressLine1\": \"schema:streetAddress\",\n    \"addressLine2\": \"schema:streetAddress\",\n    \"city\": \"schema:addressLocality\",\n    \"state\": \"schema:addressRegion\",\n    \"country\": \"schema:addressCountry\",\n    \"zipCode\": \"schema:postalCode\",\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updatedAt\": {\n    \
  \  \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"accountId\": {\n      \"@id\": \"schema:subjectOf\",\n      \"@type\": \"@id\"\n    },\n    \"schemaName\": \"schema:additionalType\",\n    \"timestamp\": {\n      \"@id\": \"schema:startTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"dimensions\": \"schema:additionalProperty\",\n    \"attributes\": \"schema:additionalProperty\",\n    \"creditAmount\": \"schema:price\",\n    \"effectiveFrom\": {\n      \"@id\": \"schema:validFrom\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"effectiveTo\": {\n      \"@id\": \"schema:validThrough\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/togai/refs/heads/main/json-ld/togai-context.jsonld
tags:
- Billing
- Metering
- Usage-Based Pricing
- Revenue Management
- SaaS
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
