---
api_specs:
- filename: tropic-openapi.yml
  format: yaml
  label: Tropic API
  slug: rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tropic/refs/heads/main/openapi/tropic-openapi.yml
class_count: 22
classes:
- Contract
- Supplier
- ProcurementRequest
- Webhook
- id
- name
- description
- status
- total_value
- currency
- website
- email
- amount
- category
- risk_rating
- spend
- contacts
- documents
- events
- url
- active
- role
context_file: json-ld/tropic-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/tropic/refs/heads/main/json-ld/tropic-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Tropic from Tropic.
layout: jsonld
name: Tropic Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: created_at
  type: dateTime
- container: ''
  name: updated_at
  type: dateTime
- container: ''
  name: start_date
  type: date
- container: ''
  name: end_date
  type: date
- container: ''
  name: renewal_date
  type: date
- container: ''
  name: supplier_id
  type: reference
- container: ''
  name: owner_id
  type: reference
- container: ''
  name: requester_id
  type: reference
property_count: 8
provider_name: Tropic
provider_slug: tropic
slug: tropic-context
source_filename: tropic-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.tropicapp.io/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Contract\": \"schema:Contract\",\n    \"Supplier\": \"schema:Organization\",\n    \"ProcurementRequest\": \"schema:Order\",\n    \"Webhook\": \"schema:WebhookEvent\",\n\n    \"id\": \"@id\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"status\": \"schema:status\",\n    \"created_at\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updated_at\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"start_date\": {\n      \"@id\": \"schema:startDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"end_date\": {\n      \"@id\": \"schema:endDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"renewal_date\": {\n      \"@id\": \"schema:expires\",\n      \"@type\": \"xsd:date\"\n    },\n\
  \    \"total_value\": \"schema:price\",\n    \"currency\": \"schema:priceCurrency\",\n    \"website\": \"schema:url\",\n    \"email\": \"schema:email\",\n    \"supplier_id\": {\n      \"@id\": \"schema:seller\",\n      \"@type\": \"@id\"\n    },\n    \"owner_id\": {\n      \"@id\": \"schema:agent\",\n      \"@type\": \"@id\"\n    },\n    \"requester_id\": {\n      \"@id\": \"schema:customer\",\n      \"@type\": \"@id\"\n    },\n    \"amount\": \"schema:price\",\n    \"category\": \"schema:category\",\n    \"risk_rating\": \"riskLevel\",\n    \"spend\": \"annualSpend\",\n    \"contacts\": \"schema:contactPoint\",\n    \"documents\": \"schema:subjectOf\",\n    \"events\": \"schema:eventType\",\n    \"url\": \"schema:url\",\n    \"active\": \"schema:isAccessibleForFree\",\n    \"role\": \"schema:roleName\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/tropic/refs/heads/main/json-ld/tropic-context.jsonld
tags:
- Benchmarking
- Contract Management
- Cost Optimization
- Procurement
- Renewals
- SaaS Management
- SaaS Procurement
- Spend Management
- Supplier Management
- JSON-LD
- Linked Data
- Semantic Web
---
