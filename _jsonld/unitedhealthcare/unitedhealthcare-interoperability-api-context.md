---
api_specs:
- filename: unitedhealthcare-provider-api-openapi.yml
  format: yaml
  label: UnitedHealthcare Provider API
  slug: provider-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/unitedhealthcare/refs/heads/main/openapi/unitedhealthcare-provider-api-openapi.yml
- filename: unitedhealthcare-interoperability-api-openapi.yml
  format: yaml
  label: UnitedHealthcare Interoperability API
  slug: interoperability-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/unitedhealthcare/refs/heads/main/openapi/unitedhealthcare-interoperability-api-openapi.yml
class_count: 17
classes:
- resourceType
- id
- identifier
- name
- gender
- address
- telecom
- total
- entry
- link
- Patient
- Bundle
- ExplanationOfBenefit
- Coverage
- Practitioner
- Organization
- MedicationKnowledge
context_file: json-ld/unitedhealthcare-interoperability-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/unitedhealthcare/refs/heads/main/json-ld/unitedhealthcare-interoperability-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Unitedhealthcare Interoperability Api from UnitedHealthcare.
layout: jsonld
name: Unitedhealthcare Interoperability Api Context
namespaces:
- prefix: fhir
  uri: http://hl7.org/fhir/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: uhci
  uri: https://api.uhc.com/fhir/R4/vocab#
properties:
- container: ''
  name: birthDate
  type: date
property_count: 1
provider_name: UnitedHealthcare
provider_slug: unitedhealthcare
slug: unitedhealthcare-interoperability-api-context
source_filename: unitedhealthcare-interoperability-api-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"fhir\": \"http://hl7.org/fhir/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"uhci\": \"https://api.uhc.com/fhir/R4/vocab#\",\n    \"resourceType\": \"fhir:resourceType\",\n    \"id\": \"@id\",\n    \"identifier\": \"fhir:identifier\",\n    \"name\": \"fhir:name\",\n    \"birthDate\": {\n      \"@id\": \"fhir:birthDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"gender\": \"fhir:gender\",\n    \"address\": \"fhir:address\",\n    \"telecom\": \"fhir:telecom\",\n    \"total\": \"fhir:total\",\n    \"entry\": \"fhir:entry\",\n    \"link\": \"fhir:link\",\n    \"Patient\": \"fhir:Patient\",\n    \"Bundle\": \"fhir:Bundle\",\n    \"ExplanationOfBenefit\": \"fhir:ExplanationOfBenefit\",\n    \"Coverage\": \"fhir:Coverage\",\n    \"Practitioner\": \"fhir:Practitioner\",\n    \"Organization\": \"fhir:Organization\",\n    \"MedicationKnowledge\": \"fhir:MedicationKnowledge\"\
  \n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/unitedhealthcare/refs/heads/main/json-ld/unitedhealthcare-interoperability-api-context.jsonld
tags:
- Health Insurance
- Healthcare
- FHIR
- Claims
- Eligibility
- JSON-LD
- Linked Data
- Semantic Web
---
