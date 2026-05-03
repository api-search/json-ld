---
api_specs:
- filename: tenet-healthcare-fhir-openapi.yml
  format: yaml
  label: Tenet Health Patient Portal API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tenet-healthcare/refs/heads/main/openapi/tenet-healthcare-fhir-openapi.yml
class_count: 10
classes:
- name
- description
- url
- MedicalOrganization
- Hospital
- MedicalAppointment
- MedicalCondition
- Drug
- Tags
- Documentation
context_file: json-ld/tenet-healthcare-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/tenet-healthcare/refs/heads/main/json-ld/tenet-healthcare-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Tenet Healthcare from Tenet Healthcare.
layout: jsonld
name: Tenet Healthcare Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: fhir
  uri: https://hl7.org/fhir/R4/
- prefix: snomed
  uri: http://snomed.info/sct/
- prefix: loinc
  uri: http://loinc.org/
- prefix: tenet
  uri: https://api-evangelist.com/providers/tenet-healthcare/
properties:
- container: ''
  name: Patient
  type: schema:Person
- container: ''
  name: patient
  type: reference
- container: ''
  name: appointment
  type: reference
- container: ''
  name: observation
  type: reference
- container: ''
  name: condition
  type: reference
- container: ''
  name: medicationRequest
  type: reference
- container: ''
  name: patientId
  type: schema:Text
- container: ''
  name: birthDate
  type: schema:Date
- container: ''
  name: gender
  type: schema:Text
- container: ''
  name: appointmentDate
  type: schema:DateTime
- container: ''
  name: provider
  type: reference
- container: ''
  name: location
  type: reference
property_count: 12
provider_name: Tenet Healthcare
provider_slug: tenet-healthcare
slug: tenet-healthcare-context
source_filename: tenet-healthcare-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"fhir\": \"https://hl7.org/fhir/R4/\",\n    \"snomed\": \"http://snomed.info/sct/\",\n    \"loinc\": \"http://loinc.org/\",\n    \"tenet\": \"https://api-evangelist.com/providers/tenet-healthcare/\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"MedicalOrganization\": \"schema:MedicalOrganization\",\n    \"Hospital\": \"schema:Hospital\",\n    \"Patient\": {\n      \"@id\": \"schema:Patient\",\n      \"@type\": \"schema:Person\"\n    },\n    \"MedicalAppointment\": \"schema:MedicalAppointment\",\n    \"MedicalCondition\": \"schema:MedicalCondition\",\n    \"Drug\": \"schema:Drug\",\n    \"patient\": {\n      \"@id\": \"fhir:Patient\",\n      \"@type\": \"@id\"\n    },\n    \"appointment\": {\n      \"@id\": \"fhir:Appointment\",\n      \"@type\": \"@id\"\n    },\n    \"observation\": {\n      \"@id\": \"fhir:Observation\"\
  ,\n      \"@type\": \"@id\"\n    },\n    \"condition\": {\n      \"@id\": \"fhir:Condition\",\n      \"@type\": \"@id\"\n    },\n    \"medicationRequest\": {\n      \"@id\": \"fhir:MedicationRequest\",\n      \"@type\": \"@id\"\n    },\n    \"patientId\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"schema:Text\"\n    },\n    \"birthDate\": {\n      \"@id\": \"schema:birthDate\",\n      \"@type\": \"schema:Date\"\n    },\n    \"gender\": {\n      \"@id\": \"schema:gender\",\n      \"@type\": \"schema:Text\"\n    },\n    \"appointmentDate\": {\n      \"@id\": \"schema:startDate\",\n      \"@type\": \"schema:DateTime\"\n    },\n    \"provider\": {\n      \"@id\": \"schema:provider\",\n      \"@type\": \"@id\"\n    },\n    \"location\": {\n      \"@id\": \"schema:location\",\n      \"@type\": \"@id\"\n    },\n    \"Tags\": \"schema:keywords\",\n    \"Documentation\": \"schema:documentation\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/tenet-healthcare/refs/heads/main/json-ld/tenet-healthcare-context.jsonld
tags:
- Healthcare
- Hospitals
- Ambulatory Surgery Centers
- Revenue Cycle Management
- Fortune 500
- JSON-LD
- Linked Data
- Semantic Web
---
