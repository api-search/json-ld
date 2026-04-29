---
api_specs:
- filename: charmhealth-fhir-api-openapi.yml
  format: yaml
  label: CharmHealth FHIR API
  slug: fhir-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/charmhealth/refs/heads/main/openapi/charmhealth-fhir-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/charmhealth-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/charmhealth/refs/heads/main/json-ld/charmhealth-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Charmhealth from CharmHealth.
layout: jsonld
name: Charmhealth Context
namespaces:
- prefix: charmhealth
  uri: https://www.charmhealth.com/schemas/
- prefix: fhir
  uri: http://hl7.org/fhir/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Patient
  type: ''
- container: ''
  name: Encounter
  type: ''
- container: ''
  name: Observation
  type: ''
- container: ''
  name: Condition
  type: ''
- container: ''
  name: MedicationRequest
  type: ''
- container: ''
  name: AllergyIntolerance
  type: ''
property_count: 6
provider_name: CharmHealth
provider_slug: charmhealth
slug: charmhealth-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"charmhealth\": \"https://www.charmhealth.com/schemas/\",\n    \"fhir\": \"http://hl7.org/fhir/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Patient\": {\n      \"@id\": \"fhir:Patient\",\n      \"@context\": {\n        \"id\": \"fhir:id\",\n        \"identifier\": \"fhir:Patient.identifier\",\n        \"name\": \"fhir:Patient.name\",\n        \"gender\": \"fhir:Patient.gender\",\n        \"birthDate\": {\n          \"@id\": \"fhir:Patient.birthDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"address\": \"fhir:Patient.address\",\n        \"telecom\": \"fhir:Patient.telecom\"\n      }\n    },\n\n    \"Encounter\": {\n      \"@id\": \"fhir:Encounter\",\n      \"@context\": {\n        \"id\": \"fhir:id\",\n        \"status\": \"fhir:Encounter.status\",\n        \"class\": \"fhir:Encounter.class\",\n \
  \       \"subject\": {\n          \"@id\": \"fhir:Encounter.subject\",\n          \"@type\": \"@id\"\n        },\n        \"period\": \"fhir:Encounter.period\"\n      }\n    },\n\n    \"Observation\": {\n      \"@id\": \"fhir:Observation\",\n      \"@context\": {\n        \"id\": \"fhir:id\",\n        \"status\": \"fhir:Observation.status\",\n        \"category\": \"fhir:Observation.category\",\n        \"code\": \"fhir:Observation.code\",\n        \"subject\": {\n          \"@id\": \"fhir:Observation.subject\",\n          \"@type\": \"@id\"\n        },\n        \"effectiveDateTime\": {\n          \"@id\": \"fhir:Observation.effectiveDateTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"valueQuantity\": \"fhir:Observation.valueQuantity\"\n      }\n    },\n\n    \"Condition\": {\n      \"@id\": \"fhir:Condition\",\n      \"@context\": {\n        \"id\": \"fhir:id\",\n        \"clinicalStatus\": \"fhir:Condition.clinicalStatus\",\n        \"verificationStatus\": \"fhir:Condition.verificationStatus\"\
  ,\n        \"category\": \"fhir:Condition.category\",\n        \"code\": \"fhir:Condition.code\",\n        \"subject\": {\n          \"@id\": \"fhir:Condition.subject\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"MedicationRequest\": {\n      \"@id\": \"fhir:MedicationRequest\",\n      \"@context\": {\n        \"id\": \"fhir:id\",\n        \"status\": \"fhir:MedicationRequest.status\",\n        \"intent\": \"fhir:MedicationRequest.intent\",\n        \"medicationCodeableConcept\": \"fhir:MedicationRequest.medicationCodeableConcept\",\n        \"subject\": {\n          \"@id\": \"fhir:MedicationRequest.subject\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"AllergyIntolerance\": {\n      \"@id\": \"fhir:AllergyIntolerance\",\n      \"@context\": {\n        \"id\": \"fhir:id\",\n        \"clinicalStatus\": \"fhir:AllergyIntolerance.clinicalStatus\",\n        \"code\": \"fhir:AllergyIntolerance.code\",\n        \"patient\": {\n          \"@id\"\
  : \"fhir:AllergyIntolerance.patient\",\n          \"@type\": \"@id\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/charmhealth/refs/heads/main/json-ld/charmhealth-context.jsonld
tags:
- EHR
- EMR
- FHIR
- Healthcare
- HL7
- Patient Engagement
- Patients
- SMART on FHIR
- US Core
- JSON-LD
- Linked Data
- Semantic Web
---
