---
api_specs:
- filename: chs-patient-access-api-openapi.yml
  format: yaml
  label: Community Health Systems Patient Access API
  slug: patient-access-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/community-health-systems/refs/heads/main/openapi/chs-patient-access-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/community-health-systems-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/community-health-systems/refs/heads/main/json-ld/community-health-systems-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Community Health Systems from Community Health Systems.
layout: jsonld
name: Community Health Systems Context
namespaces:
- prefix: fhir
  uri: http://hl7.org/fhir/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: chs
  uri: https://chs.net/vocab/
properties:
- container: ''
  name: Patient
  type: ''
- container: ''
  name: ExplanationOfBenefit
  type: ''
- container: ''
  name: MedicationKnowledge
  type: ''
- container: ''
  name: Practitioner
  type: ''
- container: ''
  name: Bundle
  type: ''
property_count: 5
provider_name: Community Health Systems
provider_slug: community-health-systems
slug: community-health-systems-context
source_filename: community-health-systems-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"fhir\": \"http://hl7.org/fhir/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"chs\": \"https://chs.net/vocab/\",\n\n    \"Patient\": {\n      \"@id\": \"fhir:Patient\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"resourceType\": \"@type\",\n        \"family\": \"fhir:Patient.name.family\",\n        \"given\": \"fhir:Patient.name.given\",\n        \"birthDate\": {\n          \"@id\": \"fhir:Patient.birthDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"gender\": \"fhir:Patient.gender\"\n      }\n    },\n\n    \"ExplanationOfBenefit\": {\n      \"@id\": \"fhir:ExplanationOfBenefit\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"resourceType\": \"@type\",\n        \"patient\": \"fhir:ExplanationOfBenefit.patient\",\n        \"provider\": \"fhir:ExplanationOfBenefit.provider\",\n        \"billablePeriod\": \"fhir:ExplanationOfBenefit.billablePeriod\"\
  ,\n        \"diagnosis\": \"fhir:ExplanationOfBenefit.diagnosis\",\n        \"item\": \"fhir:ExplanationOfBenefit.item\",\n        \"total\": \"fhir:ExplanationOfBenefit.total\"\n      }\n    },\n\n    \"MedicationKnowledge\": {\n      \"@id\": \"fhir:MedicationKnowledge\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"resourceType\": \"@type\",\n        \"code\": \"fhir:MedicationKnowledge.code\",\n        \"doseForm\": \"fhir:MedicationKnowledge.doseForm\",\n        \"manufacturer\": \"fhir:MedicationKnowledge.manufacturer\"\n      }\n    },\n\n    \"Practitioner\": {\n      \"@id\": \"fhir:Practitioner\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"resourceType\": \"@type\",\n        \"name\": \"fhir:Practitioner.name\",\n        \"specialty\": \"chs:specialty\",\n        \"telecom\": \"fhir:Practitioner.telecom\",\n        \"address\": \"fhir:Practitioner.address\"\n      }\n    },\n\n    \"Bundle\": {\n      \"@id\": \"fhir:Bundle\",\n      \"@context\"\
  : {\n        \"resourceType\": \"@type\",\n        \"type\": \"fhir:Bundle.type\",\n        \"total\": \"fhir:Bundle.total\",\n        \"entry\": \"fhir:Bundle.entry\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/community-health-systems/refs/heads/main/json-ld/community-health-systems-context.jsonld
tags:
- CMS-9115-F
- FHIR
- Healthcare
- Hospitals
- Interoperability
- Patient Access
- Provider Directory
- SMART-on-FHIR
- JSON-LD
- Linked Data
- Semantic Web
---
