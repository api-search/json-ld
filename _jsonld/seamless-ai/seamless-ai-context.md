---
api_specs:
- filename: seamless-ai-contacts-openapi.yml
  format: yaml
  label: Seamless.AI Contacts API
  slug: seamless-ai-contacts-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/seamless-ai/refs/heads/main/openapi/seamless-ai-contacts-openapi.yml
- filename: seamless-ai-companies-openapi.yml
  format: yaml
  label: Seamless.AI Companies API
  slug: seamless-ai-companies-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/seamless-ai/refs/heads/main/openapi/seamless-ai-companies-openapi.yml
class_count: 19
classes:
- Contact
- Company
- id
- name
- firstName
- lastName
- title
- company
- location
- linkedinUrl
- industry
- domain
- employeeCount
- revenue
- founded
- headquarters
- funding
- searchResultId
- verified
context_file: json-ld/seamless-ai-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/seamless-ai/refs/heads/main/json-ld/seamless-ai-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Seamless Ai from Seamless.AI.
layout: jsonld
name: Seamless Ai Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: seamless
  uri: https://seamless.ai/vocab/
properties:
- container: set
  name: emails
  type: ''
- container: set
  name: phones
  type: ''
- container: list
  name: jobHistory
  type: ''
- container: set
  name: technologies
  type: ''
property_count: 4
provider_name: Seamless.AI
provider_slug: seamless-ai
slug: seamless-ai-context
source_filename: seamless-ai-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"seamless\": \"https://seamless.ai/vocab/\",\n    \"Contact\": \"schema:Person\",\n    \"Company\": \"schema:Organization\",\n    \"id\": \"@id\",\n    \"name\": \"schema:name\",\n    \"firstName\": \"schema:givenName\",\n    \"lastName\": \"schema:familyName\",\n    \"title\": \"schema:jobTitle\",\n    \"company\": \"schema:worksFor\",\n    \"emails\": {\n      \"@id\": \"schema:email\",\n      \"@container\": \"@set\"\n    },\n    \"phones\": {\n      \"@id\": \"schema:telephone\",\n      \"@container\": \"@set\"\n    },\n    \"location\": \"schema:addressLocality\",\n    \"linkedinUrl\": \"schema:sameAs\",\n    \"industry\": \"schema:industry\",\n    \"jobHistory\": {\n      \"@id\": \"seamless:jobHistory\",\n      \"@container\": \"@list\"\n    },\n    \"domain\": \"schema:url\",\n    \"employeeCount\": \"schema:numberOfEmployees\"\
  ,\n    \"revenue\": \"schema:revenue\",\n    \"founded\": \"schema:foundingDate\",\n    \"headquarters\": \"schema:address\",\n    \"technologies\": {\n      \"@id\": \"seamless:technologies\",\n      \"@container\": \"@set\"\n    },\n    \"funding\": \"seamless:funding\",\n    \"searchResultId\": \"seamless:searchResultId\",\n    \"verified\": \"seamless:verified\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/seamless-ai/refs/heads/main/json-ld/seamless-ai-context.jsonld
tags:
- B2B
- Contact Data
- Sales Intelligence
- Prospecting
- Lead Generation
- CRM Enrichment
- JSON-LD
- Linked Data
- Semantic Web
---
