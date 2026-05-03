---
api_specs:
- filename: samhsa-treatment-locator-openapi.yml
  format: yaml
  label: SAMHSA Behavioral Health Treatment Services Locator API
  slug: samhsa-treatment-locator-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/substance-abuse-and-mental-health-services-administration/refs/heads/main/openapi/samhsa-treatment-locator-openapi.yml
class_count: 18
classes:
- name
- description
- url
- address
- telephone
- latitude
- longitude
- geo
- MedicalOrganization
- GovernmentAgency
- Dataset
- DataDownload
- publisher
- creator
- issued
- modified
- license
- language
context_file: json-ld/samhsa-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/substance-abuse-and-mental-health-services-administration/refs/heads/main/json-ld/samhsa-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Samhsa from Substance Abuse and Mental Health Services Administration.
layout: jsonld
name: Samhsa Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: samhsa
  uri: https://www.samhsa.gov/vocab#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: gov
  uri: https://www.data.gov/vocab#
properties:
- container: ''
  name: TreatmentFacility
  type: schema:MedicalOrganization
- container: ''
  name: SubstanceAbuseProgram
  type: schema:MedicalOrganization
- container: ''
  name: MentalHealthProgram
  type: schema:MedicalOrganization
- container: ''
  name: facilityType
  type: ''
- container: ''
  name: serviceCategory
  type: ''
- container: ''
  name: treatmentServices
  type: ''
- container: ''
  name: paymentOptions
  type: ''
- container: ''
  name: acceptsMedicaid
  type: schema:Boolean
- container: ''
  name: acceptsMedicare
  type: schema:Boolean
- container: ''
  name: offersNoFeeTreatment
  type: schema:Boolean
- container: ''
  name: offersSlidingFee
  type: schema:Boolean
- container: ''
  name: populationsServed
  type: ''
- container: ''
  name: SurveyDataRecord
  type: ''
- container: ''
  name: NSDUH
  type: ''
- container: ''
  name: substanceType
  type: ''
- container: ''
  name: measureType
  type: ''
- container: ''
  name: prevalencePercentage
  type: schema:Number
- container: ''
  name: ageGroup
  type: ''
property_count: 18
provider_name: Substance Abuse and Mental Health Services Administration
provider_slug: substance-abuse-and-mental-health-services-administration
slug: samhsa-context
source_filename: samhsa-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"samhsa\": \"https://www.samhsa.gov/vocab#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"gov\": \"https://www.data.gov/vocab#\",\n\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"address\": \"schema:address\",\n    \"telephone\": \"schema:telephone\",\n    \"latitude\": \"schema:latitude\",\n    \"longitude\": \"schema:longitude\",\n    \"geo\": \"schema:geo\",\n\n    \"MedicalOrganization\": \"schema:MedicalOrganization\",\n    \"TreatmentFacility\": {\n      \"@id\": \"samhsa:TreatmentFacility\",\n      \"@type\": \"schema:MedicalOrganization\"\n    },\n    \"SubstanceAbuseProgram\": {\n      \"@id\": \"samhsa:SubstanceAbuseProgram\",\n      \"@type\": \"schema:MedicalOrganization\"\n    },\n    \"MentalHealthProgram\": {\n      \"@id\": \"samhsa:MentalHealthProgram\",\n      \"@type\": \"schema:MedicalOrganization\"\
  \n    },\n\n    \"facilityType\": {\n      \"@id\": \"samhsa:facilityType\"\n    },\n    \"serviceCategory\": {\n      \"@id\": \"samhsa:serviceCategory\"\n    },\n    \"treatmentServices\": {\n      \"@id\": \"samhsa:treatmentServices\"\n    },\n    \"paymentOptions\": {\n      \"@id\": \"samhsa:paymentOptions\"\n    },\n    \"acceptsMedicaid\": {\n      \"@id\": \"samhsa:acceptsMedicaid\",\n      \"@type\": \"schema:Boolean\"\n    },\n    \"acceptsMedicare\": {\n      \"@id\": \"samhsa:acceptsMedicare\",\n      \"@type\": \"schema:Boolean\"\n    },\n    \"offersNoFeeTreatment\": {\n      \"@id\": \"samhsa:offersNoFeeTreatment\",\n      \"@type\": \"schema:Boolean\"\n    },\n    \"offersSlidingFee\": {\n      \"@id\": \"samhsa:offersSlidingFee\",\n      \"@type\": \"schema:Boolean\"\n    },\n    \"populationsServed\": {\n      \"@id\": \"samhsa:populationsServed\"\n    },\n\n    \"SurveyDataRecord\": {\n      \"@id\": \"samhsa:SurveyDataRecord\"\n    },\n    \"NSDUH\": {\n      \"@id\"\
  : \"samhsa:NationalSurveyDrugUseHealth\"\n    },\n    \"substanceType\": {\n      \"@id\": \"samhsa:substanceType\"\n    },\n    \"measureType\": {\n      \"@id\": \"samhsa:measureType\"\n    },\n    \"prevalencePercentage\": {\n      \"@id\": \"samhsa:prevalencePercentage\",\n      \"@type\": \"schema:Number\"\n    },\n    \"ageGroup\": {\n      \"@id\": \"samhsa:ageGroup\"\n    },\n\n    \"GovernmentAgency\": \"schema:GovernmentOrganization\",\n    \"Dataset\": \"schema:Dataset\",\n    \"DataDownload\": \"schema:DataDownload\",\n    \"publisher\": \"schema:publisher\",\n    \"creator\": \"schema:creator\",\n    \"issued\": \"dcterms:issued\",\n    \"modified\": \"dcterms:modified\",\n    \"license\": \"dcterms:license\",\n    \"language\": \"dcterms:language\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/substance-abuse-and-mental-health-services-administration/refs/heads/main/json-ld/samhsa-context.jsonld
tags:
- Federal Government
- Public Health
- Behavioral Health
- Substance Use Disorders
- Mental Health
- Open Data
- Healthcare
- JSON-LD
- Linked Data
- Semantic Web
---
