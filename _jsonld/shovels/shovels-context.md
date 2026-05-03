---
api_specs:
- filename: shovels-openapi.yml
  format: yaml
  label: Shovels API
  slug: shovels-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/shovels/refs/heads/main/openapi/shovels-openapi.yml
class_count: 22
classes:
- Permit
- Contractor
- Address
- Employee
- id
- name
- description
- email
- phone
- website
- address
- latitude
- longitude
- street_no
- street
- city
- county
- state
- zip_code
- next_cursor
- size
- items
context_file: json-ld/shovels-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/shovels/refs/heads/main/json-ld/shovels-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Shovels from Shovels.
layout: jsonld
name: Shovels Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: shovels
  uri: https://api.shovels.ai/v2/vocab#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: status
  type: '@vocab'
- container: ''
  name: issue_date
  type: date
- container: ''
  name: final_date
  type: date
- container: ''
  name: job_value
  type: decimal
- container: set
  name: tags
  type: ''
- container: ''
  name: property_type
  type: '@vocab'
- container: ''
  name: contractor_id
  type: string
- container: ''
  name: jurisdiction
  type: string
- container: ''
  name: license
  type: string
- container: ''
  name: classification
  type: '@vocab'
- container: ''
  name: inspection_pass_rate
  type: decimal
- container: ''
  name: permit_count
  type: integer
- container: ''
  name: geo_id
  type: string
property_count: 13
provider_name: Shovels
provider_slug: shovels
slug: shovels-context
source_filename: shovels-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"shovels\": \"https://api.shovels.ai/v2/vocab#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Permit\": \"shovels:Permit\",\n    \"Contractor\": \"shovels:Contractor\",\n    \"Address\": \"schema:PostalAddress\",\n    \"Employee\": \"schema:Person\",\n\n    \"id\": \"@id\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"email\": \"schema:email\",\n    \"phone\": \"schema:telephone\",\n    \"website\": \"schema:url\",\n    \"address\": \"schema:address\",\n    \"latitude\": \"schema:latitude\",\n    \"longitude\": \"schema:longitude\",\n\n    \"status\": {\n      \"@id\": \"shovels:status\",\n      \"@type\": \"@vocab\"\n    },\n    \"issue_date\": {\n      \"@id\": \"shovels:issueDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"final_date\": {\n      \"@id\": \"shovels:finalDate\",\n      \"@type\": \"xsd:date\"\n    },\n\
  \    \"job_value\": {\n      \"@id\": \"shovels:jobValue\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"tags\": {\n      \"@id\": \"shovels:tags\",\n      \"@container\": \"@set\"\n    },\n    \"property_type\": {\n      \"@id\": \"shovels:propertyType\",\n      \"@type\": \"@vocab\"\n    },\n    \"contractor_id\": {\n      \"@id\": \"shovels:contractorId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"jurisdiction\": {\n      \"@id\": \"shovels:jurisdiction\",\n      \"@type\": \"xsd:string\"\n    },\n    \"license\": {\n      \"@id\": \"shovels:licenseNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"classification\": {\n      \"@id\": \"shovels:classification\",\n      \"@type\": \"@vocab\"\n    },\n    \"inspection_pass_rate\": {\n      \"@id\": \"shovels:inspectionPassRate\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"permit_count\": {\n      \"@id\": \"shovels:permitCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"geo_id\": {\n      \"@id\": \"shovels:geoId\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"street_no\": \"schema:streetAddress\",\n    \"street\": \"schema:streetAddress\",\n    \"city\": \"schema:addressLocality\",\n    \"county\": \"schema:addressRegion\",\n    \"state\": \"schema:addressRegion\",\n    \"zip_code\": \"schema:postalCode\",\n    \"next_cursor\": \"shovels:nextCursor\",\n    \"size\": \"shovels:pageSize\",\n    \"items\": \"shovels:items\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/shovels/refs/heads/main/json-ld/shovels-context.jsonld
tags:
- Construction
- Building Permits
- Contractors
- Real Estate
- Property Data
- Market Intelligence
- JSON-LD
- Linked Data
- Semantic Web
---
