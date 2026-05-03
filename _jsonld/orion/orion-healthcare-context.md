---
api_specs:
- filename: orion-fhir-openapi.yml
  format: yaml
  label: Orion Health FHIR API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/orion/refs/heads/main/openapi/orion-fhir-openapi.yml
- filename: orion-population-health-openapi.yml
  format: yaml
  label: Orion Health Population Health API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/orion/refs/heads/main/openapi/orion-population-health-openapi.yml
- filename: orion-hie-openapi.yml
  format: yaml
  label: Orion Health HIE API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/orion/refs/heads/main/openapi/orion-hie-openapi.yml
- filename: orion-rhapsody-openapi.yml
  format: yaml
  label: Orion Health Rhapsody Integration API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/orion/refs/heads/main/openapi/orion-rhapsody-openapi.yml
class_count: 5
classes:
- name
- description
- email
- telephone
- address
context_file: json-ld/orion-healthcare-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/orion/refs/heads/main/json-ld/orion-healthcare-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Orion Healthcare from Orion Health.
layout: jsonld
name: Orion Healthcare Context
namespaces:
- prefix: orion
  uri: https://schema.orionhealth.com/
- prefix: fhir
  uri: http://hl7.org/fhir/
- prefix: schema
  uri: https://schema.org/
- prefix: snomed
  uri: http://snomed.info/id/
- prefix: loinc
  uri: http://loinc.org/rdf#
- prefix: icd10
  uri: http://hl7.org/fhir/sid/icd-10-cm/
- prefix: rxnorm
  uri: http://www.nlm.nih.gov/research/umls/rxnorm/
- prefix: cvx
  uri: http://hl7.org/fhir/sid/cvx/
- prefix: npi
  uri: http://hl7.org/fhir/sid/us-npi/
- prefix: hie
  uri: https://schema.orionhealth.com/hie/
- prefix: phm
  uri: https://schema.orionhealth.com/population-health/
properties:
- container: ''
  name: Patient
  type: ''
- container: ''
  name: Observation
  type: ''
- container: ''
  name: Encounter
  type: ''
- container: ''
  name: Condition
  type: ''
- container: ''
  name: MedicationRequest
  type: ''
- container: ''
  name: CarePlan
  type: ''
- container: ''
  name: DocumentReference
  type: ''
- container: ''
  name: HealthInformationExchange
  type: ''
- container: ''
  name: PopulationHealthRegistry
  type: ''
- container: ''
  name: RiskScore
  type: ''
- container: ''
  name: IntegrationRoute
  type: ''
- container: ''
  name: CodeableConcept
  type: ''
- container: ''
  name: Coding
  type: ''
- container: ''
  name: Reference
  type: ''
- container: ''
  name: Organization
  type: schema:Organization
- container: ''
  name: Practitioner
  type: schema:Physician
- container: ''
  name: url
  type: reference
property_count: 17
provider_name: Orion Health
provider_slug: orion
slug: orion-healthcare-context
source_filename: orion-healthcare-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"orion\": \"https://schema.orionhealth.com/\",\n    \"fhir\": \"http://hl7.org/fhir/\",\n    \"schema\": \"https://schema.org/\",\n    \"snomed\": \"http://snomed.info/id/\",\n    \"loinc\": \"http://loinc.org/rdf#\",\n    \"icd10\": \"http://hl7.org/fhir/sid/icd-10-cm/\",\n    \"rxnorm\": \"http://www.nlm.nih.gov/research/umls/rxnorm/\",\n    \"cvx\": \"http://hl7.org/fhir/sid/cvx/\",\n    \"npi\": \"http://hl7.org/fhir/sid/us-npi/\",\n    \"hie\": \"https://schema.orionhealth.com/hie/\",\n    \"phm\": \"https://schema.orionhealth.com/population-health/\",\n\n    \"Patient\": {\n      \"@id\": \"fhir:Patient\",\n      \"@context\": {\n        \"resourceType\": \"fhir:resourceType\",\n        \"identifier\": {\n          \"@id\": \"fhir:identifier\",\n          \"@type\": \"@id\"\n        },\n        \"active\": \"fhir:active\",\n        \"name\": \"fhir:name\",\n        \"family\": \"fhir:name.family\",\n        \"given\"\
  : \"fhir:name.given\",\n        \"telecom\": \"fhir:telecom\",\n        \"gender\": \"fhir:gender\",\n        \"birthDate\": {\n          \"@id\": \"fhir:birthDate\",\n          \"@type\": \"schema:Date\"\n        },\n        \"address\": \"fhir:address\",\n        \"maritalStatus\": \"fhir:maritalStatus\",\n        \"communication\": \"fhir:communication\",\n        \"generalPractitioner\": {\n          \"@id\": \"fhir:generalPractitioner\",\n          \"@type\": \"@id\"\n        },\n        \"managingOrganization\": {\n          \"@id\": \"fhir:managingOrganization\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Observation\": {\n      \"@id\": \"fhir:Observation\",\n      \"@context\": {\n        \"resourceType\": \"fhir:resourceType\",\n        \"status\": \"fhir:status\",\n        \"category\": \"fhir:category\",\n        \"code\": \"fhir:code\",\n        \"subject\": {\n          \"@id\": \"fhir:subject\",\n          \"@type\": \"@id\"\n        },\n        \"\
  encounter\": {\n          \"@id\": \"fhir:encounter\",\n          \"@type\": \"@id\"\n        },\n        \"effectiveDateTime\": {\n          \"@id\": \"fhir:effectiveDateTime\",\n          \"@type\": \"schema:DateTime\"\n        },\n        \"valueQuantity\": \"fhir:valueQuantity\",\n        \"valueString\": \"fhir:valueString\",\n        \"interpretation\": \"fhir:interpretation\",\n        \"referenceRange\": \"fhir:referenceRange\",\n        \"component\": \"fhir:component\"\n      }\n    },\n\n    \"Encounter\": {\n      \"@id\": \"fhir:Encounter\",\n      \"@context\": {\n        \"resourceType\": \"fhir:resourceType\",\n        \"status\": \"fhir:status\",\n        \"class\": \"fhir:class\",\n        \"type\": \"fhir:type\",\n        \"subject\": {\n          \"@id\": \"fhir:subject\",\n          \"@type\": \"@id\"\n        },\n        \"period\": \"fhir:period\",\n        \"participant\": \"fhir:participant\",\n        \"reasonCode\": \"fhir:reasonCode\"\n      }\n    },\n\n  \
  \  \"Condition\": {\n      \"@id\": \"fhir:Condition\",\n      \"@context\": {\n        \"resourceType\": \"fhir:resourceType\",\n        \"clinicalStatus\": \"fhir:clinicalStatus\",\n        \"verificationStatus\": \"fhir:verificationStatus\",\n        \"category\": \"fhir:category\",\n        \"severity\": \"fhir:severity\",\n        \"code\": \"fhir:code\",\n        \"subject\": {\n          \"@id\": \"fhir:subject\",\n          \"@type\": \"@id\"\n        },\n        \"onsetDateTime\": {\n          \"@id\": \"fhir:onsetDateTime\",\n          \"@type\": \"schema:DateTime\"\n        }\n      }\n    },\n\n    \"MedicationRequest\": {\n      \"@id\": \"fhir:MedicationRequest\",\n      \"@context\": {\n        \"resourceType\": \"fhir:resourceType\",\n        \"status\": \"fhir:status\",\n        \"intent\": \"fhir:intent\",\n        \"medicationCodeableConcept\": \"fhir:medicationCodeableConcept\",\n        \"subject\": {\n          \"@id\": \"fhir:subject\",\n          \"@type\": \"@id\"\
  \n        },\n        \"authoredOn\": {\n          \"@id\": \"fhir:authoredOn\",\n          \"@type\": \"schema:DateTime\"\n        },\n        \"requester\": {\n          \"@id\": \"fhir:requester\",\n          \"@type\": \"@id\"\n        },\n        \"dosageInstruction\": \"fhir:dosageInstruction\"\n      }\n    },\n\n    \"CarePlan\": {\n      \"@id\": \"fhir:CarePlan\",\n      \"@context\": {\n        \"resourceType\": \"fhir:resourceType\",\n        \"status\": \"fhir:status\",\n        \"intent\": \"fhir:intent\",\n        \"category\": \"fhir:category\",\n        \"subject\": {\n          \"@id\": \"fhir:subject\",\n          \"@type\": \"@id\"\n        },\n        \"period\": \"fhir:period\",\n        \"activity\": \"fhir:activity\",\n        \"goal\": {\n          \"@id\": \"fhir:goal\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"DocumentReference\": {\n      \"@id\": \"fhir:DocumentReference\",\n      \"@context\": {\n        \"resourceType\": \"fhir:resourceType\"\
  ,\n        \"status\": \"fhir:status\",\n        \"type\": \"fhir:type\",\n        \"category\": \"fhir:category\",\n        \"subject\": {\n          \"@id\": \"fhir:subject\",\n          \"@type\": \"@id\"\n        },\n        \"date\": {\n          \"@id\": \"fhir:date\",\n          \"@type\": \"schema:DateTime\"\n        },\n        \"content\": \"fhir:content\"\n      }\n    },\n\n    \"HealthInformationExchange\": {\n      \"@id\": \"hie:HealthInformationExchange\",\n      \"@context\": {\n        \"participatingOrganization\": {\n          \"@id\": \"hie:participatingOrganization\",\n          \"@type\": \"@id\"\n        },\n        \"consentDirective\": {\n          \"@id\": \"hie:consentDirective\",\n          \"@type\": \"@id\"\n        },\n        \"documentExchange\": \"hie:documentExchange\",\n        \"patientMatch\": \"hie:patientMatch\"\n      }\n    },\n\n    \"PopulationHealthRegistry\": {\n      \"@id\": \"phm:Registry\",\n      \"@context\": {\n        \"registryType\"\
  : \"phm:registryType\",\n        \"patientCount\": \"phm:patientCount\",\n        \"riskStratification\": \"phm:riskStratification\",\n        \"careProgram\": {\n          \"@id\": \"phm:careProgram\",\n          \"@type\": \"@id\"\n        },\n        \"qualityMeasure\": \"phm:qualityMeasure\",\n        \"cohort\": {\n          \"@id\": \"phm:cohort\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"RiskScore\": {\n      \"@id\": \"phm:RiskScore\",\n      \"@context\": {\n        \"patient\": {\n          \"@id\": \"phm:patient\",\n          \"@type\": \"@id\"\n        },\n        \"riskModel\": \"phm:riskModel\",\n        \"score\": \"phm:score\",\n        \"riskLevel\": \"phm:riskLevel\",\n        \"riskFactors\": \"phm:riskFactors\",\n        \"calculatedAt\": {\n          \"@id\": \"phm:calculatedAt\",\n          \"@type\": \"schema:DateTime\"\n        }\n      }\n    },\n\n    \"IntegrationRoute\": {\n      \"@id\": \"orion:IntegrationRoute\",\n      \"@context\"\
  : {\n        \"routeName\": \"orion:routeName\",\n        \"routeStatus\": \"orion:routeStatus\",\n        \"communicationPoint\": {\n          \"@id\": \"orion:communicationPoint\",\n          \"@type\": \"@id\"\n        },\n        \"messageType\": \"orion:messageType\",\n        \"protocol\": \"orion:protocol\"\n      }\n    },\n\n    \"CodeableConcept\": {\n      \"@id\": \"fhir:CodeableConcept\",\n      \"@context\": {\n        \"coding\": \"fhir:coding\",\n        \"text\": \"fhir:text\"\n      }\n    },\n\n    \"Coding\": {\n      \"@id\": \"fhir:Coding\",\n      \"@context\": {\n        \"system\": {\n          \"@id\": \"fhir:system\",\n          \"@type\": \"@id\"\n        },\n        \"code\": \"fhir:code\",\n        \"display\": \"fhir:display\"\n      }\n    },\n\n    \"Reference\": {\n      \"@id\": \"fhir:Reference\",\n      \"@context\": {\n        \"reference\": {\n          \"@id\": \"fhir:reference\",\n          \"@type\": \"@id\"\n        },\n        \"display\": \"\
  fhir:display\"\n      }\n    },\n\n    \"Organization\": {\n      \"@id\": \"fhir:Organization\",\n      \"@type\": \"schema:Organization\"\n    },\n\n    \"Practitioner\": {\n      \"@id\": \"fhir:Practitioner\",\n      \"@type\": \"schema:Physician\"\n    },\n\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    },\n    \"email\": \"schema:email\",\n    \"telephone\": \"schema:telephone\",\n    \"address\": \"schema:address\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/orion/refs/heads/main/json-ld/orion-healthcare-context.jsonld
tags:
- EHR
- FHIR
- Health IT
- Healthcare
- HIE
- HL7
- Integration
- Interoperability
- Population Health
- JSON-LD
- Linked Data
- Semantic Web
---
