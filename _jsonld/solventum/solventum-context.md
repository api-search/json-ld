---
class_count: 1
classes:
- Organization
context_file: json-ld/solventum-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/solventum/refs/heads/main/json-ld/solventum-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Solventum from Solventum.
layout: jsonld
name: Solventum Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: fhir
  uri: https://hl7.org/fhir/
- prefix: snomed
  uri: http://snomed.info/id/
- prefix: icd10
  uri: http://hl7.org/fhir/sid/icd-10-cm/
- prefix: cpt
  uri: http://www.ama-assn.org/go/cpt/
- prefix: solventum
  uri: https://www.solventum.com/vocabulary/
properties:
- container: ''
  name: ClinicalEncounter
  type: ''
- container: ''
  name: Diagnosis
  type: ''
- container: ''
  name: Procedure
  type: ''
- container: ''
  name: ClinicalNote
  type: ''
- container: ''
  name: CodingResult
  type: ''
- container: ''
  name: DRGAssignment
  type: ''
property_count: 6
provider_name: Solventum
provider_slug: solventum
slug: solventum-context
source_filename: solventum-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"fhir\": \"https://hl7.org/fhir/\",\n    \"snomed\": \"http://snomed.info/id/\",\n    \"icd10\": \"http://hl7.org/fhir/sid/icd-10-cm/\",\n    \"cpt\": \"http://www.ama-assn.org/go/cpt/\",\n    \"solventum\": \"https://www.solventum.com/vocabulary/\",\n\n    \"Organization\": \"schema:Organization\",\n\n    \"ClinicalEncounter\": {\n      \"@id\": \"fhir:Encounter\",\n      \"@context\": {\n        \"encounterId\": \"@id\",\n        \"encounterType\": {\n          \"@id\": \"fhir:Encounter.class\",\n          \"@type\": \"@id\"\n        },\n        \"admissionDate\": \"fhir:Encounter.period.start\",\n        \"dischargeDate\": \"fhir:Encounter.period.end\",\n        \"patientId\": \"fhir:Encounter.subject\",\n        \"facilityId\": \"fhir:Encounter.serviceProvider\"\n      }\n    },\n\n    \"Diagnosis\": {\n      \"@id\": \"fhir:Condition\",\n      \"@context\": {\n        \"code\"\
  : {\n          \"@id\": \"fhir:Condition.code\",\n          \"@type\": \"@id\"\n        },\n        \"description\": \"schema:description\",\n        \"poa\": \"solventum:presentOnAdmission\"\n      }\n    },\n\n    \"Procedure\": {\n      \"@id\": \"fhir:Procedure\",\n      \"@context\": {\n        \"code\": {\n          \"@id\": \"fhir:Procedure.code\",\n          \"@type\": \"@id\"\n        },\n        \"description\": \"schema:description\",\n        \"performedDate\": \"fhir:Procedure.performedDateTime\"\n      }\n    },\n\n    \"ClinicalNote\": {\n      \"@id\": \"fhir:DocumentReference\",\n      \"@context\": {\n        \"noteType\": \"fhir:DocumentReference.type\",\n        \"content\": \"fhir:DocumentReference.content\",\n        \"author\": \"fhir:DocumentReference.author\",\n        \"dateTime\": \"fhir:DocumentReference.date\"\n      }\n    },\n\n    \"CodingResult\": {\n      \"@id\": \"solventum:CodingResult\",\n      \"@context\": {\n        \"encounterId\": \"solventum:encounterId\"\
  ,\n        \"processingTimestamp\": \"schema:dateCreated\",\n        \"drgAssignment\": \"solventum:drgAssignment\"\n      }\n    },\n\n    \"DRGAssignment\": {\n      \"@id\": \"solventum:DRGAssignment\",\n      \"@context\": {\n        \"msdrg\": \"solventum:msDRG\",\n        \"mdc\": \"solventum:majorDiagnosticCategory\",\n        \"severity\": \"solventum:severityOfIllness\",\n        \"mortalityRisk\": \"solventum:riskOfMortality\",\n        \"relativeWeight\": \"solventum:relativeWeight\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/solventum/refs/heads/main/json-ld/solventum-context.jsonld
tags:
- Dental
- EHR
- Electronic Health Records
- Healthcare
- Healthcare IT
- Health Information Systems
- Medical Devices
- Medical Technology
- JSON-LD
- Linked Data
- Semantic Web
---
