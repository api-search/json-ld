---
api_specs:
- filename: varian-aria-fhir-openapi.yml
  format: yaml
  label: ARIA FHIR API
  slug: aria-fhir-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/varian-medical-systems/refs/heads/main/openapi/varian-aria-fhir-openapi.yml
class_count: 15
classes:
- resourceType
- id
- gender
- family
- given
- city
- state
- postalCode
- country
- status
- category
- valueQuantity
- interpretation
- clinicalStatus
- verificationStatus
context_file: json-ld/varian-medical-systems-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/varian-medical-systems/refs/heads/main/json-ld/varian-medical-systems-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Varian Medical Systems from Varian Medical Systems.
layout: jsonld
name: Varian Medical Systems Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
- prefix: fhir
  uri: http://hl7.org/fhir/
- prefix: varian
  uri: https://varian.dynamicfhir.com/fhir/varian/basepractice/r4/
properties:
- container: ''
  name: Patient
  type: reference
- container: ''
  name: Condition
  type: reference
- container: ''
  name: Procedure
  type: reference
- container: ''
  name: Observation
  type: reference
- container: ''
  name: DiagnosticReport
  type: reference
- container: ''
  name: CarePlan
  type: reference
- container: ''
  name: MedicationRequest
  type: reference
- container: ''
  name: birthDate
  type: date
- container: ''
  name: active
  type: boolean
- container: list
  name: identifier
  type: ''
- container: list
  name: name
  type: ''
- container: ''
  name: address
  type: schema:PostalAddress
- container: ''
  name: code
  type: reference
- container: ''
  name: subject
  type: reference
- container: ''
  name: onsetDateTime
  type: dateTime
- container: ''
  name: performedDateTime
  type: dateTime
- container: ''
  name: effectiveDateTime
  type: dateTime
- container: ''
  name: issued
  type: dateTime
- container: list
  name: result
  type: ''
- container: list
  name: dosageInstruction
  type: ''
property_count: 20
provider_name: Varian Medical Systems
provider_slug: varian-medical-systems
slug: varian-medical-systems-context
source_filename: varian-medical-systems-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"fhir\": \"http://hl7.org/fhir/\",\n    \"varian\": \"https://varian.dynamicfhir.com/fhir/varian/basepractice/r4/\",\n\n    \"Patient\": {\n      \"@id\": \"fhir:Patient\",\n      \"@type\": \"@id\",\n      \"@context\": \"https://schema.org/Patient\"\n    },\n    \"Condition\": {\n      \"@id\": \"fhir:Condition\",\n      \"@type\": \"@id\"\n    },\n    \"Procedure\": {\n      \"@id\": \"fhir:Procedure\",\n      \"@type\": \"@id\",\n      \"@context\": \"https://schema.org/MedicalProcedure\"\n    },\n    \"Observation\": {\n      \"@id\": \"fhir:Observation\",\n      \"@type\": \"@id\",\n      \"@context\": \"https://schema.org/MedicalTest\"\n    },\n    \"DiagnosticReport\": {\n      \"@id\": \"fhir:DiagnosticReport\",\n      \"@type\": \"@id\",\n      \"@context\": \"https://schema.org/MedicalTest\"\n    },\n    \"CarePlan\": {\n\
  \      \"@id\": \"fhir:CarePlan\",\n      \"@type\": \"@id\",\n      \"@context\": \"https://schema.org/MedicalGuideline\"\n    },\n    \"MedicationRequest\": {\n      \"@id\": \"fhir:MedicationRequest\",\n      \"@type\": \"@id\",\n      \"@context\": \"https://schema.org/PrescribeDrugAction\"\n    },\n\n    \"resourceType\": \"fhir:resourceType\",\n    \"id\": \"@id\",\n    \"birthDate\": {\n      \"@id\": \"schema:birthDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"gender\": \"schema:gender\",\n    \"active\": {\n      \"@id\": \"fhir:active\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"identifier\": {\n      \"@id\": \"fhir:identifier\",\n      \"@container\": \"@list\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@container\": \"@list\"\n    },\n    \"family\": \"schema:familyName\",\n    \"given\": \"schema:givenName\",\n    \"address\": {\n      \"@id\": \"schema:address\",\n      \"@type\": \"schema:PostalAddress\"\n    },\n    \"city\": \"schema:addressLocality\"\
  ,\n    \"state\": \"schema:addressRegion\",\n    \"postalCode\": \"schema:postalCode\",\n    \"country\": \"schema:addressCountry\",\n\n    \"code\": {\n      \"@id\": \"fhir:code\",\n      \"@type\": \"@id\"\n    },\n    \"status\": \"fhir:status\",\n    \"subject\": {\n      \"@id\": \"fhir:subject\",\n      \"@type\": \"@id\"\n    },\n    \"onsetDateTime\": {\n      \"@id\": \"fhir:onset\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"performedDateTime\": {\n      \"@id\": \"fhir:performed\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"effectiveDateTime\": {\n      \"@id\": \"fhir:effective\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"issued\": {\n      \"@id\": \"fhir:issued\",\n      \"@type\": \"xsd:dateTime\"\n    },\n\n    \"category\": \"fhir:category\",\n    \"valueQuantity\": \"fhir:value\",\n    \"interpretation\": \"fhir:interpretation\",\n    \"result\": {\n      \"@id\": \"fhir:result\",\n      \"@container\": \"@list\"\n    },\n    \"dosageInstruction\"\
  : {\n      \"@id\": \"fhir:dosage\",\n      \"@container\": \"@list\"\n    },\n    \"clinicalStatus\": \"fhir:clinicalStatus\",\n    \"verificationStatus\": \"fhir:verificationStatus\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/varian-medical-systems/refs/heads/main/json-ld/varian-medical-systems-context.jsonld
tags:
- Healthcare
- Oncology
- Medical Devices
- FHIR
- Radiation Therapy
- Health IT
- JSON-LD
- Linked Data
- Semantic Web
---
