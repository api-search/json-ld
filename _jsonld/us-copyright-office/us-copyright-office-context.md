---
class_count: 5
classes:
- CopyrightRecordation
- CopyrightRegistration
- DMCADesignatedAgent
- email
- title
context_file: json-ld/us-copyright-office-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/us-copyright-office/refs/heads/main/json-ld/us-copyright-office-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Us Copyright Office from US Copyright Office.
layout: jsonld
name: Us Copyright Office Context
namespaces:
- prefix: usco
  uri: https://www.copyright.gov/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: set
  name: authors
  type: reference
- container: ''
  name: basis_of_claim
  type: string
- container: set
  name: claimants
  type: reference
- container: ''
  name: date_of_execution
  type: date
- container: ''
  name: date_of_recordation
  type: date
- container: ''
  name: designated_agent_name
  type: string
- container: ''
  name: document_number
  type: string
- container: ''
  name: document_type
  type: string
- container: ''
  name: effective_date
  type: date
- container: ''
  name: last_updated
  type: date
- container: ''
  name: mailing_address
  type: string
- container: ''
  name: pages
  type: integer
- container: set
  name: parties
  type: reference
- container: ''
  name: phone
  type: string
- container: ''
  name: previous_registration
  type: string
- container: ''
  name: record_status
  type: string
- container: ''
  name: registration_date
  type: date
- container: ''
  name: registration_id
  type: string
- container: ''
  name: registration_number
  type: string
- container: set
  name: registration_numbers
  type: string
- container: ''
  name: service_provider_name
  type: string
- container: ''
  name: service_provider_url
  type: reference
- container: ''
  name: status
  type: string
- container: ''
  name: termination_notice
  type: boolean
- container: set
  name: titles
  type: string
- container: ''
  name: volume
  type: string
- container: ''
  name: work_category
  type: string
- container: ''
  name: year_completed
  type: integer
property_count: 28
provider_name: US Copyright Office
provider_slug: us-copyright-office
slug: us-copyright-office-context
source_filename: us-copyright-office-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"usco\": \"https://www.copyright.gov/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"CopyrightRecordation\": \"usco:CopyrightRecordation\",\n    \"CopyrightRegistration\": \"usco:CopyrightRegistration\",\n    \"DMCADesignatedAgent\": \"usco:DMCADesignatedAgent\",\n    \"authors\": {\n      \"@id\": \"usco:authors\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"basis_of_claim\": {\n      \"@id\": \"usco:basis_of_claim\",\n      \"@type\": \"xsd:string\"\n    },\n    \"claimants\": {\n      \"@id\": \"usco:claimants\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"date_of_execution\": {\n      \"@id\": \"usco:date_of_execution\",\n      \"@type\": \"xsd:date\"\n    },\n    \"date_of_recordation\": {\n      \"@id\": \"usco:date_of_recordation\",\n      \"@type\"\
  : \"xsd:date\"\n    },\n    \"designated_agent_name\": {\n      \"@id\": \"usco:designated_agent_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"document_number\": {\n      \"@id\": \"usco:document_number\",\n      \"@type\": \"xsd:string\"\n    },\n    \"document_type\": {\n      \"@id\": \"usco:document_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"effective_date\": {\n      \"@id\": \"usco:effective_date\",\n      \"@type\": \"xsd:date\"\n    },\n    \"email\": \"schema:email\",\n    \"last_updated\": {\n      \"@id\": \"usco:last_updated\",\n      \"@type\": \"xsd:date\"\n    },\n    \"mailing_address\": {\n      \"@id\": \"usco:mailing_address\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pages\": {\n      \"@id\": \"usco:pages\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"parties\": {\n      \"@id\": \"usco:parties\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"phone\": {\n      \"@id\": \"usco:phone\",\n      \"@type\":\
  \ \"xsd:string\"\n    },\n    \"previous_registration\": {\n      \"@id\": \"usco:previous_registration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"record_status\": {\n      \"@id\": \"usco:record_status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"registration_date\": {\n      \"@id\": \"usco:registration_date\",\n      \"@type\": \"xsd:date\"\n    },\n    \"registration_id\": {\n      \"@id\": \"usco:registration_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"registration_number\": {\n      \"@id\": \"usco:registration_number\",\n      \"@type\": \"xsd:string\"\n    },\n    \"registration_numbers\": {\n      \"@id\": \"usco:registration_numbers\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"service_provider_name\": {\n      \"@id\": \"usco:service_provider_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"service_provider_url\": {\n      \"@id\": \"usco:service_provider_url\",\n      \"@type\": \"@id\"\n    },\n    \"status\"\
  : {\n      \"@id\": \"usco:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"termination_notice\": {\n      \"@id\": \"usco:termination_notice\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"title\": \"schema:name\",\n    \"titles\": {\n      \"@id\": \"usco:titles\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"volume\": {\n      \"@id\": \"usco:volume\",\n      \"@type\": \"xsd:string\"\n    },\n    \"work_category\": {\n      \"@id\": \"usco:work_category\",\n      \"@type\": \"xsd:string\"\n    },\n    \"year_completed\": {\n      \"@id\": \"usco:year_completed\",\n      \"@type\": \"xsd:integer\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/us-copyright-office/refs/heads/main/json-ld/us-copyright-office-context.jsonld
tags:
- Copyright
- Federal Government
- Intellectual Property
- Open Data
- JSON-LD
- Linked Data
- Semantic Web
---
