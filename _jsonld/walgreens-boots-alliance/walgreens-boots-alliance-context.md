---
class_count: 25
classes:
- Organization
- Corporation
- name
- description
- PharmacyChain
- HealthcareOrganization
- numberOfLocations
- Prescription
- prescriptionId
- medicationName
- dosage
- Patient
- patientId
- firstName
- lastName
- HealthcareService
- PopulationHealth
- MedicationTherapyManagement
- SpecialtyPharmacy
- HealthData
- datasetDescription
- dataLicense
- StoreLocation
- latitude
- longitude
context_file: json-ld/walgreens-boots-alliance-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/walgreens-boots-alliance/refs/heads/main/json-ld/walgreens-boots-alliance-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Walgreens Boots Alliance from Walgreens Boots Alliance.
layout: jsonld
name: Walgreens Boots Alliance Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: wba
  uri: https://www.walgreensbootsalliance.com/vocab/
- prefix: fibo
  uri: https://spec.edmcouncil.org/fibo/ontology/
properties:
- container: ''
  name: url
  type: reference
- container: ''
  name: prescriber
  type: schema:Physician
- container: ''
  name: dateOfBirth
  type: date
- container: ''
  name: address
  type: schema:PostalAddress
property_count: 4
provider_name: Walgreens Boots Alliance
provider_slug: walgreens-boots-alliance
slug: walgreens-boots-alliance-context
source_filename: walgreens-boots-alliance-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"wba\": \"https://www.walgreensbootsalliance.com/vocab/\",\n    \"fibo\": \"https://spec.edmcouncil.org/fibo/ontology/\",\n\n    \"Organization\": \"schema:Organization\",\n    \"Corporation\": \"schema:Corporation\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    },\n\n    \"PharmacyChain\": \"schema:Pharmacy\",\n    \"HealthcareOrganization\": \"schema:MedicalOrganization\",\n    \"numberOfLocations\": \"schema:numberOfEmployees\",\n\n    \"Prescription\": \"schema:Drug\",\n    \"prescriptionId\": \"wba:prescriptionId\",\n    \"medicationName\": \"schema:name\",\n    \"dosage\": \"schema:dose\",\n    \"prescriber\": {\n      \"@id\": \"schema:prescribedBy\",\n      \"@type\": \"schema:Physician\"\n    },\n\n    \"Patient\"\
  : \"schema:Patient\",\n    \"patientId\": \"wba:patientId\",\n    \"firstName\": \"schema:givenName\",\n    \"lastName\": \"schema:familyName\",\n    \"dateOfBirth\": {\n      \"@id\": \"schema:birthDate\",\n      \"@type\": \"xsd:date\"\n    },\n\n    \"HealthcareService\": \"schema:MedicalProcedure\",\n    \"PopulationHealth\": \"wba:PopulationHealth\",\n    \"MedicationTherapyManagement\": \"wba:MedicationTherapyManagement\",\n    \"SpecialtyPharmacy\": \"wba:SpecialtyPharmacy\",\n\n    \"HealthData\": \"schema:Dataset\",\n    \"datasetDescription\": \"schema:description\",\n    \"dataLicense\": \"schema:license\",\n\n    \"StoreLocation\": \"schema:Store\",\n    \"address\": {\n      \"@id\": \"schema:address\",\n      \"@type\": \"schema:PostalAddress\"\n    },\n    \"latitude\": \"schema:latitude\",\n    \"longitude\": \"schema:longitude\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/walgreens-boots-alliance/refs/heads/main/json-ld/walgreens-boots-alliance-context.jsonld
tags:
- Pharmacy
- Healthcare
- Health Wellbeing
- Retail
- Specialty Pharmacy
- Population Health
- JSON-LD
- Linked Data
- Semantic Web
---
