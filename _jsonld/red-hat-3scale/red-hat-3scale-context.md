---
api_specs:
- filename: red-hat-3scale-service-management-openapi.yml
  format: yaml
  label: Red Hat 3scale Service Management API
  slug: service-management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/red-hat-3scale/refs/heads/main/openapi/red-hat-3scale-service-management-openapi.yml
- filename: red-hat-3scale-account-management-openapi.yml
  format: yaml
  label: Red Hat 3scale Account Management API
  slug: account-management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/red-hat-3scale/refs/heads/main/openapi/red-hat-3scale-account-management-openapi.yml
- filename: red-hat-3scale-analytics-openapi.yml
  format: yaml
  label: Red Hat 3scale Analytics API
  slug: analytics-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/red-hat-3scale/refs/heads/main/openapi/red-hat-3scale-analytics-openapi.yml
- filename: red-hat-3scale-billing-openapi.yml
  format: yaml
  label: Red Hat 3scale Billing API
  slug: billing-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/red-hat-3scale/refs/heads/main/openapi/red-hat-3scale-billing-openapi.yml
- filename: red-hat-3scale-apicast-management-openapi.yml
  format: yaml
  label: Red Hat 3scale APIcast Management API
  slug: apicast-management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/red-hat-3scale/refs/heads/main/openapi/red-hat-3scale-apicast-management-openapi.yml
class_count: 3
classes:
- id
- name
- description
context_file: json-ld/red-hat-3scale-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/red-hat-3scale/refs/heads/main/json-ld/red-hat-3scale-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Red Hat 3Scale from Red Hat 3scale.
layout: jsonld
name: Red Hat 3Scale Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: threescale
  uri: https://access.redhat.com/documentation/en-us/red_hat_3scale_api_management/2.14/
properties:
- container: ''
  name: Account
  type: schema:Organization
- container: ''
  name: Application
  type: schema:SoftwareApplication
- container: ''
  name: ApplicationPlan
  type: schema:OfferCatalog
- container: ''
  name: org_name
  type: string
- container: ''
  name: state
  type: string
- container: ''
  name: created_at
  type: dateTime
- container: ''
  name: updated_at
  type: dateTime
- container: ''
  name: user_key
  type: string
- container: ''
  name: plan
  type: schema:Offer
- container: ''
  name: setup_fee
  type: decimal
- container: ''
  name: cost_per_month
  type: decimal
- container: ''
  name: hits
  type: integer
- container: ''
  name: metric
  type: string
- container: ''
  name: period
  type: string
- container: ''
  name: Invoice
  type: schema:Invoice
- container: ''
  name: invoice_id
  type: string
- container: ''
  name: amount
  type: decimal
- container: ''
  name: currency
  type: string
- container: ''
  name: provider_key
  type: string
- container: ''
  name: service_id
  type: string
property_count: 20
provider_name: Red Hat 3scale
provider_slug: red-hat-3scale
slug: red-hat-3scale-context
source_filename: red-hat-3scale-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"threescale\": \"https://access.redhat.com/documentation/en-us/red_hat_3scale_api_management/2.14/\",\n    \"Account\": {\n      \"@id\": \"schema:Organization\",\n      \"@type\": \"schema:Organization\"\n    },\n    \"Application\": {\n      \"@id\": \"schema:SoftwareApplication\",\n      \"@type\": \"schema:SoftwareApplication\"\n    },\n    \"ApplicationPlan\": {\n      \"@id\": \"schema:OfferCatalog\",\n      \"@type\": \"schema:OfferCatalog\"\n    },\n    \"id\": \"@id\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"org_name\": {\n      \"@id\": \"schema:legalName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"state\": {\n      \"@id\": \"schema:actionStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"created_at\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\":\
  \ \"xsd:dateTime\"\n    },\n    \"updated_at\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"user_key\": {\n      \"@id\": \"schema:accessCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"plan\": {\n      \"@id\": \"schema:Offer\",\n      \"@type\": \"schema:Offer\"\n    },\n    \"setup_fee\": {\n      \"@id\": \"schema:price\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"cost_per_month\": {\n      \"@id\": \"schema:price\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"hits\": {\n      \"@id\": \"schema:numberOfItems\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"metric\": {\n      \"@id\": \"schema:measurementTechnique\",\n      \"@type\": \"xsd:string\"\n    },\n    \"period\": {\n      \"@id\": \"schema:temporalCoverage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Invoice\": {\n      \"@id\": \"schema:Invoice\",\n      \"@type\": \"schema:Invoice\"\n    },\n    \"invoice_id\": {\n      \"@id\": \"schema:identifier\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"amount\": {\n      \"@id\": \"schema:price\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"currency\": {\n      \"@id\": \"schema:priceCurrency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"provider_key\": {\n      \"@id\": \"schema:accessCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"service_id\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/red-hat-3scale/refs/heads/main/json-ld/red-hat-3scale-context.jsonld
tags:
- API Gateway
- API Management
- Developer Portal
- Enterprise
- Red Hat
- JSON-LD
- Linked Data
- Semantic Web
---
