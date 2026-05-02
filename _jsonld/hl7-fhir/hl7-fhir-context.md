---
api_specs:
- filename: hl7-fhir-r4-openapi.yml
  format: yaml
  label: HL7 FHIR R4 Healthcare API
  slug: hl7-fhir-r4-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/hl7-fhir/refs/heads/main/openapi/hl7-fhir-r4-openapi.yml
class_count: 13
classes:
- resourceType
- id
- meta
- active
- gender
- family
- system
- code
- display
- value
- status
- valueQuantity
- text
context_file: json-ld/hl7-fhir-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/hl7-fhir/refs/heads/main/json-ld/hl7-fhir-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Hl7 Fhir from HL7 FHIR.
layout: jsonld
name: Hl7 Fhir Context
namespaces:
- prefix: fhir
  uri: http://hl7.org/fhir/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: loinc
  uri: http://loinc.org/
- prefix: snomed
  uri: http://snomed.info/sct/
- prefix: hl7v3
  uri: http://terminology.hl7.org/CodeSystem/v3-
properties:
- container: ''
  name: Patient
  type: reference
- container: ''
  name: Observation
  type: reference
- container: ''
  name: Condition
  type: reference
- container: ''
  name: MedicationRequest
  type: reference
- container: ''
  name: Encounter
  type: reference
- container: ''
  name: Bundle
  type: reference
- container: ''
  name: Practitioner
  type: reference
- container: ''
  name: Organization
  type: reference
- container: set
  name: identifier
  type: ''
- container: set
  name: name
  type: ''
- container: set
  name: telecom
  type: ''
- container: ''
  name: birthDate
  type: date
- container: set
  name: address
  type: ''
- container: set
  name: generalPractitioner
  type: reference
- container: list
  name: given
  type: ''
- container: list
  name: prefix
  type: ''
- container: ''
  name: subject
  type: reference
- container: ''
  name: effectiveDateTime
  type: dateTime
- container: ''
  name: issued
  type: dateTime
- container: set
  name: coding
  type: ''
- container: ''
  name: reference
  type: reference
property_count: 21
provider_name: HL7 FHIR
provider_slug: hl7-fhir
slug: hl7-fhir-context
source_filename: hl7-fhir-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"fhir\": \"http://hl7.org/fhir/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"loinc\": \"http://loinc.org/\",\n    \"snomed\": \"http://snomed.info/sct/\",\n    \"hl7v3\": \"http://terminology.hl7.org/CodeSystem/v3-\",\n\n    \"Patient\": {\n      \"@id\": \"fhir:Patient\",\n      \"@type\": \"@id\"\n    },\n    \"Observation\": {\n      \"@id\": \"fhir:Observation\",\n      \"@type\": \"@id\"\n    },\n    \"Condition\": {\n      \"@id\": \"fhir:Condition\",\n      \"@type\": \"@id\"\n    },\n    \"MedicationRequest\": {\n      \"@id\": \"fhir:MedicationRequest\",\n      \"@type\": \"@id\"\n    },\n    \"Encounter\": {\n      \"@id\": \"fhir:Encounter\",\n      \"@type\": \"@id\"\n    },\n    \"Bundle\": {\n      \"@id\": \"fhir:Bundle\",\n      \"@type\": \"@id\"\n    },\n    \"Practitioner\": {\n      \"@id\": \"fhir:Practitioner\",\n      \"@type\": \"@id\"\n   \
  \ },\n    \"Organization\": {\n      \"@id\": \"fhir:Organization\",\n      \"@type\": \"@id\"\n    },\n\n    \"resourceType\": \"fhir:resourceType\",\n    \"id\": \"fhir:Resource.id\",\n    \"meta\": \"fhir:Resource.meta\",\n    \"identifier\": {\n      \"@id\": \"fhir:Patient.identifier\",\n      \"@container\": \"@set\"\n    },\n    \"active\": \"fhir:Patient.active\",\n    \"name\": {\n      \"@id\": \"fhir:Patient.name\",\n      \"@container\": \"@set\"\n    },\n    \"telecom\": {\n      \"@id\": \"fhir:Patient.telecom\",\n      \"@container\": \"@set\"\n    },\n    \"gender\": \"fhir:Patient.gender\",\n    \"birthDate\": {\n      \"@id\": \"fhir:Patient.birthDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"address\": {\n      \"@id\": \"fhir:Patient.address\",\n      \"@container\": \"@set\"\n    },\n    \"generalPractitioner\": {\n      \"@id\": \"fhir:Patient.generalPractitioner\",\n      \"@type\": \"@id\",\n      \"@container\": \"@set\"\n    },\n\n    \"family\": \"fhir:HumanName.family\"\
  ,\n    \"given\": {\n      \"@id\": \"fhir:HumanName.given\",\n      \"@container\": \"@list\"\n    },\n    \"prefix\": {\n      \"@id\": \"fhir:HumanName.prefix\",\n      \"@container\": \"@list\"\n    },\n    \"system\": \"fhir:Coding.system\",\n    \"code\": \"fhir:Coding.code\",\n    \"display\": \"fhir:Coding.display\",\n    \"value\": \"fhir:Identifier.value\",\n    \"status\": \"fhir:status\",\n    \"subject\": {\n      \"@id\": \"fhir:Observation.subject\",\n      \"@type\": \"@id\"\n    },\n    \"effectiveDateTime\": {\n      \"@id\": \"fhir:Observation.effectiveDateTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"issued\": {\n      \"@id\": \"fhir:Observation.issued\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"valueQuantity\": \"fhir:Observation.valueQuantity\",\n    \"coding\": {\n      \"@id\": \"fhir:CodeableConcept.coding\",\n      \"@container\": \"@set\"\n    },\n    \"text\": \"fhir:CodeableConcept.text\",\n    \"reference\": {\n      \"@id\": \"fhir:Reference.reference\"\
  ,\n      \"@type\": \"@id\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/hl7-fhir/refs/heads/main/json-ld/hl7-fhir-context.jsonld
tags:
- Clinical
- FHIR
- Healthcare
- HL7
- Interoperability
- JSON-LD
- Linked Data
- Semantic Web
---
