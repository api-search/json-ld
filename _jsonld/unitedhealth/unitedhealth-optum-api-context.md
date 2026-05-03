---
api_specs:
- filename: unitedhealth-optum-api-openapi.yml
  format: yaml
  label: UnitedHealth Group Optum API
  slug: optum-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/unitedhealth/refs/heads/main/openapi/unitedhealth-optum-api-openapi.yml
class_count: 21
classes:
- resourceType
- id
- identifier
- name
- gender
- address
- telecom
- status
- total
- entry
- link
- billablePeriod
- subscriberId
- Patient
- Bundle
- ExplanationOfBenefit
- Coverage
- Practitioner
- Organization
- MedicationKnowledge
- Condition
context_file: json-ld/unitedhealth-optum-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/unitedhealth/refs/heads/main/json-ld/unitedhealth-optum-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Unitedhealth Optum Api from UnitedHealth Group.
layout: jsonld
name: Unitedhealth Optum Api Context
namespaces:
- prefix: fhir
  uri: http://hl7.org/fhir/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: uh
  uri: https://api.uhc.com/fhir/R4/vocab#
properties:
- container: ''
  name: birthDate
  type: date
property_count: 1
provider_name: UnitedHealth Group
provider_slug: unitedhealth
slug: unitedhealth-optum-api-context
source_filename: unitedhealth-optum-api-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"fhir\": \"http://hl7.org/fhir/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"uh\": \"https://api.uhc.com/fhir/R4/vocab#\",\n    \"resourceType\": \"fhir:resourceType\",\n    \"id\": \"@id\",\n    \"identifier\": \"fhir:identifier\",\n    \"name\": \"fhir:name\",\n    \"birthDate\": {\n      \"@id\": \"fhir:birthDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"gender\": \"fhir:gender\",\n    \"address\": \"fhir:address\",\n    \"telecom\": \"fhir:telecom\",\n    \"status\": \"fhir:status\",\n    \"total\": \"fhir:total\",\n    \"entry\": \"fhir:entry\",\n    \"link\": \"fhir:link\",\n    \"billablePeriod\": \"fhir:billablePeriod\",\n    \"subscriberId\": \"fhir:subscriberId\",\n    \"Patient\": \"fhir:Patient\",\n    \"Bundle\": \"fhir:Bundle\",\n    \"ExplanationOfBenefit\": \"fhir:ExplanationOfBenefit\",\n    \"Coverage\": \"fhir:Coverage\",\n    \"Practitioner\"\
  : \"fhir:Practitioner\",\n    \"Organization\": \"fhir:Organization\",\n    \"MedicationKnowledge\": \"fhir:MedicationKnowledge\",\n    \"Condition\": \"fhir:Condition\"\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/unitedhealth/refs/heads/main/json-ld/unitedhealth-optum-api-context.jsonld
tags:
- Healthcare
- Health Insurance
- FHIR
- Claims
- Interoperability
- JSON-LD
- Linked Data
- Semantic Web
---
