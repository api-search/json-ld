---
api_specs:
- filename: meditech-fhir-openapi.yml
  format: yaml
  label: Meditech Expanse FHIR API
  slug: meditech-expanse-fhir-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/meditech/refs/heads/main/openapi/meditech-fhir-openapi.yml
class_count: 16
classes:
- Patient
- id
- name
- family
- given
- gender
- address
- telecom
- value
- identifier
- Observation
- Condition
- MedicationRequest
- AllergyIntolerance
- Encounter
- DiagnosticReport
context_file: json-ld/meditech-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/meditech/refs/heads/main/json-ld/meditech-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Meditech from meditech.
layout: jsonld
name: Meditech Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: fhir
  uri: http://hl7.org/fhir/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: active
  type: boolean
- container: ''
  name: birthDate
  type: date
- container: ''
  name: deceasedDateTime
  type: dateTime
- container: ''
  name: generalPractitioner
  type: reference
- container: ''
  name: managingOrganization
  type: reference
- container: ''
  name: lastUpdated
  type: dateTime
property_count: 6
provider_name: meditech
provider_slug: meditech
slug: meditech-context
source_filename: meditech-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"fhir\": \"http://hl7.org/fhir/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Patient\": \"schema:Patient\",\n    \"id\": \"schema:identifier\",\n    \"active\": {\n      \"@id\": \"schema:activeStatus\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"name\": \"schema:name\",\n    \"family\": \"schema:familyName\",\n    \"given\": \"schema:givenName\",\n    \"gender\": \"schema:gender\",\n    \"birthDate\": {\n      \"@id\": \"schema:birthDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"deceasedDateTime\": {\n      \"@id\": \"schema:deathDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"address\": \"schema:address\",\n    \"telecom\": \"schema:contactPoint\",\n    \"value\": \"schema:value\",\n    \"identifier\": \"schema:identifier\",\n    \"Observation\": \"schema:Observation\",\n    \"Condition\": \"schema:MedicalCondition\",\n    \"MedicationRequest\"\
  : \"schema:Drug\",\n    \"AllergyIntolerance\": \"schema:allergyOrIntolerance\",\n    \"Encounter\": \"schema:MedicalVisit\",\n    \"DiagnosticReport\": \"schema:MedicalTest\",\n    \"generalPractitioner\": {\n      \"@id\": \"schema:doctor\",\n      \"@type\": \"@id\"\n    },\n    \"managingOrganization\": {\n      \"@id\": \"schema:memberOf\",\n      \"@type\": \"@id\"\n    },\n    \"lastUpdated\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/meditech/refs/heads/main/json-ld/meditech-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
