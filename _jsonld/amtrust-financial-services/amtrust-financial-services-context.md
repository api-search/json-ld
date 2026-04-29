---
api_specs:
- filename: amtrust-financial-services-commercial-lines-api.yaml
  format: yaml
  label: AmTrust Commercial Lines API
  slug: commercial-lines-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amtrust-financial-services/refs/heads/main/openapi/amtrust-financial-services-commercial-lines-api.yaml
class_count: 6
classes:
- QuoteRequest
- QuoteResponse
- PolicyResponse
- Insured
- name
- description
context_file: json-ld/amtrust-financial-services-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amtrust-financial-services/refs/heads/main/json-ld/amtrust-financial-services-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amtrust Financial Services from AmTrust Financial Services.
layout: jsonld
name: Amtrust Financial Services Context
namespaces:
- prefix: amtrust
  uri: https://amtrustfinancial.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: productType
  type: string
- container: ''
  name: state
  type: string
- container: ''
  name: effectiveDate
  type: date
- container: ''
  name: expirationDate
  type: date
- container: ''
  name: premium
  type: decimal
- container: ''
  name: policyNumber
  type: string
- container: ''
  name: quoteId
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: classCode
  type: string
- container: ''
  name: payroll
  type: decimal
- container: ''
  name: employeeCount
  type: integer
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: boundAt
  type: dateTime
property_count: 13
provider_name: AmTrust Financial Services
provider_slug: amtrust-financial-services
slug: amtrust-financial-services-context
source_filename: amtrust-financial-services-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"amtrust\": \"https://amtrustfinancial.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"QuoteRequest\": \"amtrust:QuoteRequest\",\n    \"QuoteResponse\": \"amtrust:QuoteResponse\",\n    \"PolicyResponse\": \"amtrust:PolicyResponse\",\n    \"Insured\": \"amtrust:Insured\",\n    \"productType\": {\n      \"@id\": \"amtrust:product_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"state\": {\n      \"@id\": \"amtrust:state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"effectiveDate\": {\n      \"@id\": \"amtrust:effective_date\",\n      \"@type\": \"xsd:date\"\n    },\n    \"expirationDate\": {\n      \"@id\": \"amtrust:expiration_date\",\n      \"@type\": \"xsd:date\"\n    },\n    \"premium\": {\n      \"@id\": \"amtrust:premium\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"policyNumber\": {\n      \"@id\": \"amtrust:policy_number\",\n      \"\
  @type\": \"xsd:string\"\n    },\n    \"quoteId\": {\n      \"@id\": \"amtrust:quote_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"amtrust:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"classCode\": {\n      \"@id\": \"amtrust:class_code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"payroll\": {\n      \"@id\": \"amtrust:payroll\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"employeeCount\": {\n      \"@id\": \"amtrust:employee_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"createdAt\": {\n      \"@id\": \"amtrust:created_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"boundAt\": {\n      \"@id\": \"amtrust:bound_at\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amtrust-financial-services/refs/heads/main/json-ld/amtrust-financial-services-context.jsonld
tags:
- Commercial Insurance
- Insurance
- Property And Casualty
- Small Business
- Workers Compensation
- JSON-LD
- Linked Data
- Semantic Web
---
