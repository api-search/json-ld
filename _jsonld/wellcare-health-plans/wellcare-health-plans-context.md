---
api_specs:
- filename: wellcare-fhir-patient-access-api-openapi.yml
  format: yaml
  label: WellCare FHIR Patient Access API
  slug: fhir-patient-access-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/wellcare-health-plans/refs/heads/main/openapi/wellcare-fhir-patient-access-api-openapi.yml
- filename: wellcare-fhir-provider-directory-api-openapi.yml
  format: yaml
  label: WellCare FHIR Provider Directory API
  slug: fhir-provider-directory-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/wellcare-health-plans/refs/heads/main/openapi/wellcare-fhir-provider-directory-api-openapi.yml
class_count: 7
classes:
- WellCareMember
- WellCareProvider
- WellCareOrganization
- WellCarePlan
- WellCareClaim
- WellCarePrescription
- WellCareImmunization
context_file: json-ld/wellcare-health-plans-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/wellcare-health-plans/refs/heads/main/json-ld/wellcare-health-plans-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Wellcare Health Plans from wellcare-health-plans.
layout: jsonld
name: Wellcare Health Plans Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: fhir
  uri: http://hl7.org/fhir/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: wellcare
  uri: https://www.wellcare.com/vocab#
properties:
- container: ''
  name: memberId
  type: string
- container: ''
  name: memberName
  type: string
- container: ''
  name: memberBirthDate
  type: date
- container: ''
  name: memberGender
  type: string
- container: ''
  name: memberAddress
  type: schema:PostalAddress
- container: ''
  name: planId
  type: string
- container: ''
  name: planName
  type: string
- container: ''
  name: planType
  type: string
- container: ''
  name: planNetwork
  type: string
- container: ''
  name: enrollmentStart
  type: date
- container: ''
  name: enrollmentEnd
  type: date
- container: ''
  name: claimId
  type: string
- container: ''
  name: claimType
  type: string
- container: ''
  name: serviceDate
  type: date
- container: ''
  name: claimAmount
  type: decimal
- container: ''
  name: benefitAmount
  type: decimal
- container: ''
  name: npi
  type: string
- container: ''
  name: providerName
  type: string
- container: ''
  name: providerSpecialty
  type: ''
- container: ''
  name: networkStatus
  type: string
- container: ''
  name: rxNumber
  type: string
- container: ''
  name: drugName
  type: string
- container: ''
  name: drugCode
  type: string
- container: ''
  name: prescribingProvider
  type: ''
- container: ''
  name: icd10Code
  type: string
- container: ''
  name: conditionName
  type: string
- container: ''
  name: clinicalStatus
  type: string
property_count: 27
provider_name: wellcare-health-plans
provider_slug: wellcare-health-plans
slug: wellcare-health-plans-context
source_filename: wellcare-health-plans-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"fhir\": \"http://hl7.org/fhir/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"wellcare\": \"https://www.wellcare.com/vocab#\",\n\n    \"WellCareMember\": \"schema:Patient\",\n    \"WellCareProvider\": \"schema:Physician\",\n    \"WellCareOrganization\": \"schema:MedicalOrganization\",\n    \"WellCarePlan\": \"schema:HealthInsurancePlan\",\n    \"WellCareClaim\": \"schema:MedicalClaim\",\n    \"WellCarePrescription\": \"schema:Drug\",\n    \"WellCareImmunization\": \"schema:Immunization\",\n\n    \"memberId\": { \"@id\": \"schema:memberOf\", \"@type\": \"xsd:string\" },\n    \"memberName\": { \"@id\": \"schema:name\", \"@type\": \"xsd:string\" },\n    \"memberBirthDate\": { \"@id\": \"schema:birthDate\", \"@type\": \"xsd:date\" },\n    \"memberGender\": { \"@id\": \"schema:gender\", \"@type\": \"xsd:string\" },\n    \"memberAddress\": { \"@id\": \"schema:address\", \"\
  @type\": \"schema:PostalAddress\" },\n\n    \"planId\": { \"@id\": \"schema:identifier\", \"@type\": \"xsd:string\" },\n    \"planName\": { \"@id\": \"schema:name\", \"@type\": \"xsd:string\" },\n    \"planType\": { \"@id\": \"wellcare:planType\", \"@type\": \"xsd:string\" },\n    \"planNetwork\": { \"@id\": \"wellcare:networkType\", \"@type\": \"xsd:string\" },\n    \"enrollmentStart\": { \"@id\": \"schema:validFrom\", \"@type\": \"xsd:date\" },\n    \"enrollmentEnd\": { \"@id\": \"schema:validThrough\", \"@type\": \"xsd:date\" },\n\n    \"claimId\": { \"@id\": \"schema:identifier\", \"@type\": \"xsd:string\" },\n    \"claimType\": { \"@id\": \"wellcare:claimType\", \"@type\": \"xsd:string\" },\n    \"serviceDate\": { \"@id\": \"schema:dateCreated\", \"@type\": \"xsd:date\" },\n    \"claimAmount\": { \"@id\": \"schema:price\", \"@type\": \"xsd:decimal\" },\n    \"benefitAmount\": { \"@id\": \"wellcare:benefitAmount\", \"@type\": \"xsd:decimal\" },\n\n    \"npi\": { \"@id\": \"fhir:Practitioner.identifier\"\
  , \"@type\": \"xsd:string\" },\n    \"providerName\": { \"@id\": \"schema:name\", \"@type\": \"xsd:string\" },\n    \"providerSpecialty\": { \"@id\": \"schema:medicalSpecialty\" },\n    \"networkStatus\": { \"@id\": \"wellcare:networkStatus\", \"@type\": \"xsd:string\" },\n\n    \"rxNumber\": { \"@id\": \"schema:identifier\", \"@type\": \"xsd:string\" },\n    \"drugName\": { \"@id\": \"schema:name\", \"@type\": \"xsd:string\" },\n    \"drugCode\": { \"@id\": \"fhir:MedicationRequest.medication\", \"@type\": \"xsd:string\" },\n    \"prescribingProvider\": { \"@id\": \"schema:performer\" },\n\n    \"icd10Code\": { \"@id\": \"wellcare:icd10Code\", \"@type\": \"xsd:string\" },\n    \"conditionName\": { \"@id\": \"schema:name\", \"@type\": \"xsd:string\" },\n    \"clinicalStatus\": { \"@id\": \"wellcare:clinicalStatus\", \"@type\": \"xsd:string\" }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/wellcare-health-plans/refs/heads/main/json-ld/wellcare-health-plans-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
