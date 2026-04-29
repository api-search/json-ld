---
api_specs:
- filename: cigna-patient-access-api-openapi.yml
  format: yaml
  label: Cigna Patient Access API
  slug: patient-access-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/cigna/refs/heads/main/openapi/cigna-patient-access-api-openapi.yml
- filename: cigna-provider-directory-api-openapi.yml
  format: yaml
  label: Cigna Provider Directory API
  slug: provider-directory-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/cigna/refs/heads/main/openapi/cigna-provider-directory-api-openapi.yml
- filename: cigna-drug-formulary-api-openapi.yml
  format: yaml
  label: Cigna Drug Formulary API
  slug: drug-formulary-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/cigna/refs/heads/main/openapi/cigna-drug-formulary-api-openapi.yml
- filename: cigna-provider-access-api-openapi.yml
  format: yaml
  label: Cigna Provider Access API
  slug: provider-access-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/cigna/refs/heads/main/openapi/cigna-provider-access-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/cigna-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/cigna/refs/heads/main/json-ld/cigna-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Cigna from Cigna.
layout: jsonld
name: Cigna Context
namespaces:
- prefix: cigna
  uri: https://developer.cigna.com/schemas/
- prefix: fhir
  uri: http://hl7.org/fhir/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: Patient
  type: ''
- container: ''
  name: Coverage
  type: ''
- container: ''
  name: ExplanationOfBenefit
  type: ''
- container: ''
  name: Practitioner
  type: ''
- container: ''
  name: Organization
  type: ''
- container: ''
  name: Location
  type: ''
- container: ''
  name: MedicationKnowledge
  type: ''
- container: ''
  name: InsurancePlan
  type: ''
property_count: 8
provider_name: Cigna
provider_slug: cigna
slug: cigna-context
source_filename: cigna-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"cigna\": \"https://developer.cigna.com/schemas/\",\n    \"fhir\": \"http://hl7.org/fhir/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Patient\": {\n      \"@id\": \"fhir:Patient\",\n      \"@context\": {\n        \"id\": \"fhir:Resource.id\",\n        \"name\": \"schema:name\",\n        \"birthDate\": {\n          \"@id\": \"fhir:Patient.birthDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"gender\": \"fhir:Patient.gender\",\n        \"identifier\": \"fhir:Patient.identifier\"\n      }\n    },\n\n    \"Coverage\": {\n      \"@id\": \"fhir:Coverage\",\n      \"@context\": {\n        \"id\": \"fhir:Resource.id\",\n        \"status\": \"fhir:Coverage.status\",\n        \"subscriberId\": \"fhir:Coverage.subscriberId\",\n        \"beneficiary\": \"fhir:Coverage.beneficiary\",\n        \"payor\": \"fhir:Coverage.payor\",\n        \"period\": \"fhir:Coverage.period\"\
  \n      }\n    },\n\n    \"ExplanationOfBenefit\": {\n      \"@id\": \"fhir:ExplanationOfBenefit\",\n      \"@context\": {\n        \"id\": \"fhir:Resource.id\",\n        \"status\": \"fhir:ExplanationOfBenefit.status\",\n        \"type\": \"fhir:ExplanationOfBenefit.type\",\n        \"use\": \"fhir:ExplanationOfBenefit.use\",\n        \"patient\": \"fhir:ExplanationOfBenefit.patient\",\n        \"billablePeriod\": \"fhir:ExplanationOfBenefit.billablePeriod\",\n        \"insurer\": \"fhir:ExplanationOfBenefit.insurer\",\n        \"provider\": \"fhir:ExplanationOfBenefit.provider\",\n        \"total\": \"fhir:ExplanationOfBenefit.total\"\n      }\n    },\n\n    \"Practitioner\": {\n      \"@id\": \"fhir:Practitioner\",\n      \"@context\": {\n        \"id\": \"fhir:Resource.id\",\n        \"identifier\": \"fhir:Practitioner.identifier\",\n        \"name\": \"schema:name\",\n        \"telecom\": \"fhir:Practitioner.telecom\",\n        \"address\": \"fhir:Practitioner.address\",\n       \
  \ \"qualification\": \"fhir:Practitioner.qualification\"\n      }\n    },\n\n    \"Organization\": {\n      \"@id\": \"fhir:Organization\",\n      \"@context\": {\n        \"id\": \"fhir:Resource.id\",\n        \"identifier\": \"fhir:Organization.identifier\",\n        \"name\": \"schema:name\",\n        \"type\": \"fhir:Organization.type\",\n        \"address\": \"fhir:Organization.address\"\n      }\n    },\n\n    \"Location\": {\n      \"@id\": \"fhir:Location\",\n      \"@context\": {\n        \"id\": \"fhir:Resource.id\",\n        \"name\": \"schema:name\",\n        \"address\": \"fhir:Location.address\",\n        \"position\": \"fhir:Location.position\"\n      }\n    },\n\n    \"MedicationKnowledge\": {\n      \"@id\": \"fhir:MedicationKnowledge\",\n      \"@context\": {\n        \"id\": \"fhir:Resource.id\",\n        \"code\": \"fhir:MedicationKnowledge.code\",\n        \"status\": \"fhir:MedicationKnowledge.status\",\n        \"doseForm\": \"fhir:MedicationKnowledge.doseForm\"\
  ,\n        \"drugCharacteristic\": \"fhir:MedicationKnowledge.drugCharacteristic\"\n      }\n    },\n\n    \"InsurancePlan\": {\n      \"@id\": \"fhir:InsurancePlan\",\n      \"@context\": {\n        \"id\": \"fhir:Resource.id\",\n        \"name\": \"schema:name\",\n        \"type\": \"fhir:InsurancePlan.type\",\n        \"coverageArea\": \"fhir:InsurancePlan.coverageArea\",\n        \"network\": \"fhir:InsurancePlan.network\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/cigna/refs/heads/main/json-ld/cigna-context.jsonld
tags:
- CMS Interoperability
- Da Vinci
- Drug Formulary
- FHIR
- Health Insurance
- Healthcare
- Patient Access
- Provider Directory
- SMART on FHIR
- JSON-LD
- Linked Data
- Semantic Web
---
