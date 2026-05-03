---
class_count: 0
classes: []
context_file: json-ld/clinical-trials-gov-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/clinical-trials-gov/refs/heads/main/json-ld/clinical-trials-gov-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Clinical Trials Gov from ClinicalTrials.gov.
layout: jsonld
name: Clinical Trials Gov Context
namespaces:
- prefix: ctg
  uri: https://clinicaltrials.gov/ns/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Study
  type: ''
- container: ''
  name: Sponsor
  type: ''
- container: ''
  name: Intervention
  type: ''
- container: ''
  name: Condition
  type: ''
- container: ''
  name: EligibilityCriteria
  type: ''
- container: ''
  name: Location
  type: ''
- container: ''
  name: Outcome
  type: ''
property_count: 7
provider_name: ClinicalTrials.gov
provider_slug: clinical-trials-gov
slug: clinical-trials-gov-context
source_filename: clinical-trials-gov-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"ctg\": \"https://clinicaltrials.gov/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Study\": {\n      \"@id\": \"ctg:Study\",\n      \"@context\": {\n        \"nctId\": \"ctg:nct_id\",\n        \"briefTitle\": \"schema:name\",\n        \"officialTitle\": \"ctg:official_title\",\n        \"overallStatus\": \"ctg:overall_status\",\n        \"phase\": \"ctg:phase\",\n        \"studyType\": \"ctg:study_type\",\n        \"conditions\": {\n          \"@id\": \"ctg:conditions\",\n          \"@container\": \"@set\"\n        },\n        \"interventions\": {\n          \"@id\": \"ctg:interventions\",\n          \"@container\": \"@set\"\n        },\n        \"leadSponsor\": \"schema:sponsor\",\n        \"startDate\": {\n          \"@id\": \"ctg:start_date\",\n          \"@type\": \"xsd:date\"\n        },\n        \"completionDate\"\
  : {\n          \"@id\": \"ctg:completion_date\",\n          \"@type\": \"xsd:date\"\n        },\n        \"lastUpdateDate\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:date\"\n        }\n      }\n    },\n\n    \"Sponsor\": {\n      \"@id\": \"ctg:Sponsor\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"agencyClass\": \"ctg:agency_class\"\n      }\n    },\n\n    \"Intervention\": {\n      \"@id\": \"ctg:Intervention\",\n      \"@context\": {\n        \"type\": \"ctg:intervention_type\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\"\n      }\n    },\n\n    \"Condition\": {\n      \"@id\": \"ctg:Condition\",\n      \"@context\": {\n        \"name\": \"schema:name\"\n      }\n    },\n\n    \"EligibilityCriteria\": {\n      \"@id\": \"ctg:EligibilityCriteria\",\n      \"@context\": {\n        \"minimumAge\": \"ctg:minimum_age\",\n        \"maximumAge\": \"ctg:maximum_age\",\n        \"sex\": \"schema:gender\"\
  ,\n        \"healthyVolunteers\": \"ctg:healthy_volunteers\"\n      }\n    },\n\n    \"Location\": {\n      \"@id\": \"ctg:Location\",\n      \"@context\": {\n        \"facility\": \"schema:name\",\n        \"city\": \"schema:addressLocality\",\n        \"state\": \"schema:addressRegion\",\n        \"country\": \"schema:addressCountry\",\n        \"status\": \"ctg:recruitment_status\"\n      }\n    },\n\n    \"Outcome\": {\n      \"@id\": \"ctg:Outcome\",\n      \"@context\": {\n        \"measure\": \"ctg:measure\",\n        \"description\": \"schema:description\",\n        \"timeFrame\": \"ctg:time_frame\",\n        \"type\": \"ctg:outcome_type\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/clinical-trials-gov/refs/heads/main/json-ld/clinical-trials-gov-context.jsonld
tags:
- Clinical Trials
- Government
- Health
- NIH
- Open Data
- Public Health
- Research
- JSON-LD
- Linked Data
- Semantic Web
---
