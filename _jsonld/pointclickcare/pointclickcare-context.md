---
api_specs:
- filename: pointclickcare-ehr-openapi.yml
  format: yaml
  label: PointClickCare Long-Term Care EHR API
  slug: pointclickcare-ehr-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/pointclickcare/refs/heads/main/openapi/pointclickcare-ehr-openapi.yml
class_count: 0
classes: []
context_file: json-ld/pointclickcare-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/pointclickcare/refs/heads/main/json-ld/pointclickcare-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Pointclickcare from PointClickCare.
layout: jsonld
name: Pointclickcare Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: fhir
  uri: http://hl7.org/fhir/
- prefix: pcc
  uri: https://developer.pointclickcare.com/vocab#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: Patient
  type: reference
- container: ''
  name: patientId
  type: ''
- container: ''
  name: mrn
  type: ''
- container: ''
  name: firstName
  type: ''
- container: ''
  name: lastName
  type: ''
- container: ''
  name: dateOfBirth
  type: date
- container: ''
  name: gender
  type: ''
- container: ''
  name: admissionDate
  type: date
- container: ''
  name: dischargeDate
  type: date
- container: ''
  name: language
  type: ''
- container: ''
  name: allergies
  type: ''
- container: ''
  name: VitalSign
  type: reference
- container: ''
  name: vitalType
  type: ''
- container: ''
  name: recordedDatetime
  type: dateTime
- container: ''
  name: systolic
  type: integer
- container: ''
  name: heartRate
  type: integer
- container: ''
  name: temperature
  type: decimal
- container: ''
  name: weight
  type: decimal
- container: ''
  name: oxygenSaturation
  type: decimal
- container: ''
  name: MedicationOrder
  type: reference
- container: ''
  name: medicationName
  type: ''
- container: ''
  name: ndc
  type: ''
- container: ''
  name: dose
  type: ''
- container: ''
  name: route
  type: ''
- container: ''
  name: frequency
  type: ''
- container: ''
  name: Diagnosis
  type: reference
- container: ''
  name: icdCode
  type: ''
- container: ''
  name: description
  type: ''
- container: ''
  name: onsetDate
  type: date
- container: ''
  name: Facility
  type: reference
- container: ''
  name: facilityId
  type: ''
- container: ''
  name: npi
  type: ''
- container: ''
  name: facilityType
  type: ''
property_count: 33
provider_name: PointClickCare
provider_slug: pointclickcare
slug: pointclickcare-context
source_filename: pointclickcare-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"fhir\": \"http://hl7.org/fhir/\",\n    \"pcc\": \"https://developer.pointclickcare.com/vocab#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Patient\": {\n      \"@id\": \"fhir:Patient\",\n      \"@type\": \"@id\"\n    },\n    \"patientId\": {\n      \"@id\": \"schema:identifier\"\n    },\n    \"mrn\": {\n      \"@id\": \"fhir:Patient.identifier\"\n    },\n    \"firstName\": {\n      \"@id\": \"schema:givenName\"\n    },\n    \"lastName\": {\n      \"@id\": \"schema:familyName\"\n    },\n    \"dateOfBirth\": {\n      \"@id\": \"schema:birthDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"gender\": {\n      \"@id\": \"schema:gender\"\n    },\n    \"admissionDate\": {\n      \"@id\": \"fhir:Encounter.period.start\",\n      \"@type\": \"xsd:date\"\n    },\n    \"dischargeDate\": {\n      \"@id\": \"fhir:Encounter.period.end\",\n      \"@type\": \"xsd:date\"\n  \
  \  },\n    \"language\": {\n      \"@id\": \"schema:knowsLanguage\"\n    },\n    \"allergies\": {\n      \"@id\": \"fhir:AllergyIntolerance\"\n    },\n\n    \"VitalSign\": {\n      \"@id\": \"fhir:Observation\",\n      \"@type\": \"@id\"\n    },\n    \"vitalType\": {\n      \"@id\": \"fhir:Observation.code\"\n    },\n    \"recordedDatetime\": {\n      \"@id\": \"fhir:Observation.effectiveDateTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"systolic\": {\n      \"@id\": \"fhir:Observation.component.valueSampledData\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"heartRate\": {\n      \"@id\": \"pcc:heartRate\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"temperature\": {\n      \"@id\": \"pcc:bodyTemperature\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"weight\": {\n      \"@id\": \"schema:weight\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"oxygenSaturation\": {\n      \"@id\": \"pcc:oxygenSaturation\",\n      \"@type\": \"xsd:decimal\"\n    },\n\n    \"MedicationOrder\"\
  : {\n      \"@id\": \"fhir:MedicationRequest\",\n      \"@type\": \"@id\"\n    },\n    \"medicationName\": {\n      \"@id\": \"schema:name\"\n    },\n    \"ndc\": {\n      \"@id\": \"fhir:Medication.code\"\n    },\n    \"dose\": {\n      \"@id\": \"fhir:MedicationRequest.dosageInstruction.doseAndRate\"\n    },\n    \"route\": {\n      \"@id\": \"fhir:MedicationRequest.dosageInstruction.route\"\n    },\n    \"frequency\": {\n      \"@id\": \"fhir:MedicationRequest.dosageInstruction.timing\"\n    },\n\n    \"Diagnosis\": {\n      \"@id\": \"fhir:Condition\",\n      \"@type\": \"@id\"\n    },\n    \"icdCode\": {\n      \"@id\": \"fhir:Condition.code\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\"\n    },\n    \"onsetDate\": {\n      \"@id\": \"fhir:Condition.onsetDateTime\",\n      \"@type\": \"xsd:date\"\n    },\n\n    \"Facility\": {\n      \"@id\": \"schema:MedicalOrganization\",\n      \"@type\": \"@id\"\n    },\n    \"facilityId\": {\n      \"@id\": \"schema:identifier\"\
  \n    },\n    \"npi\": {\n      \"@id\": \"pcc:npi\"\n    },\n    \"facilityType\": {\n      \"@id\": \"schema:medicalSpecialty\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/pointclickcare/refs/heads/main/json-ld/pointclickcare-context.jsonld
tags:
- Healthcare
- Long-Term Care
- Post-Acute Care
- EHR
- FHIR
- Senior Care
- Interoperability
- JSON-LD
- Linked Data
- Semantic Web
---
