---
api_specs:
- filename: cfpb-ccdb-openapi.yml
  format: yaml
  label: Consumer Complaint Database API
  slug: ccdb
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/consumer-financial-protection-bureau/refs/heads/main/openapi/cfpb-ccdb-openapi.yml
- filename: cfpb-hmda-data-browser-openapi.yml
  format: yaml
  label: HMDA Data Browser API
  slug: hmda-data-browser
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/consumer-financial-protection-bureau/refs/heads/main/openapi/cfpb-hmda-data-browser-openapi.yml
- filename: cfpb-hmda-institutions-openapi.yml
  format: yaml
  label: HMDA Institutions API
  slug: hmda-institutions
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/consumer-financial-protection-bureau/refs/heads/main/openapi/cfpb-hmda-institutions-openapi.yml
class_count: 0
classes: []
context_file: json-ld/consumer-financial-protection-bureau-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/consumer-financial-protection-bureau/refs/heads/main/json-ld/consumer-financial-protection-bureau-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Consumer Financial Protection Bureau from Consumer Financial Protection Bureau.
layout: jsonld
name: Consumer Financial Protection Bureau Context
namespaces:
- prefix: cfpb
  uri: https://www.consumerfinance.gov/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Complaint
  type: ''
- container: ''
  name: Institution
  type: ''
- container: ''
  name: HMDARecord
  type: ''
property_count: 3
provider_name: Consumer Financial Protection Bureau
provider_slug: consumer-financial-protection-bureau
slug: consumer-financial-protection-bureau-context
source_filename: consumer-financial-protection-bureau-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"cfpb\": \"https://www.consumerfinance.gov/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Complaint\": {\n      \"@id\": \"cfpb:Complaint\",\n      \"@context\": {\n        \"id\": \"cfpb:complaint_id\",\n        \"dateReceived\": {\n          \"@id\": \"cfpb:date_received\",\n          \"@type\": \"xsd:date\"\n        },\n        \"dateSentToCompany\": {\n          \"@id\": \"cfpb:date_sent_to_company\",\n          \"@type\": \"xsd:date\"\n        },\n        \"product\": \"cfpb:product\",\n        \"subProduct\": \"cfpb:sub_product\",\n        \"issue\": \"cfpb:issue\",\n        \"subIssue\": \"cfpb:sub_issue\",\n        \"company\": \"cfpb:company\",\n        \"companyResponse\": \"cfpb:company_response\",\n        \"companyPublicResponse\": \"cfpb:company_public_response\",\n        \"consumerConsentProvided\"\
  : \"cfpb:consumer_consent_provided\",\n        \"consumerDisputed\": \"cfpb:consumer_disputed\",\n        \"complaintWhatHappened\": \"cfpb:complaint_what_happened\",\n        \"state\": \"schema:addressRegion\",\n        \"zipCode\": \"schema:postalCode\",\n        \"tags\": \"cfpb:tags\",\n        \"timely\": \"cfpb:timely\",\n        \"submittedVia\": \"cfpb:submitted_via\"\n      }\n    },\n\n    \"Institution\": {\n      \"@id\": \"cfpb:Institution\",\n      \"@context\": {\n        \"lei\": \"cfpb:lei\",\n        \"activityYear\": \"cfpb:activity_year\",\n        \"agency\": \"cfpb:agency\",\n        \"institutionType\": \"cfpb:institution_type\",\n        \"respondent\": \"cfpb:respondent\",\n        \"parent\": \"cfpb:parent\",\n        \"assets\": \"cfpb:assets\",\n        \"hmdaFiler\": \"cfpb:hmda_filer\",\n        \"quarterlyFiler\": \"cfpb:quarterly_filer\"\n      }\n    },\n\n    \"HMDARecord\": {\n      \"@id\": \"cfpb:HMDARecord\",\n      \"@context\": {\n        \"lei\"\
  : \"cfpb:lei\",\n        \"year\": \"cfpb:activity_year\",\n        \"actionTaken\": \"cfpb:action_taken\",\n        \"loanType\": \"cfpb:loan_type\",\n        \"loanPurpose\": \"cfpb:loan_purpose\",\n        \"loanAmount\": \"cfpb:loan_amount\",\n        \"state\": \"cfpb:state\",\n        \"county\": \"cfpb:county\",\n        \"censusTract\": \"cfpb:census_tract\",\n        \"applicantRace\": \"cfpb:applicant_race\",\n        \"applicantEthnicity\": \"cfpb:applicant_ethnicity\",\n        \"applicantSex\": \"cfpb:applicant_sex\",\n        \"income\": \"cfpb:income\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/consumer-financial-protection-bureau/refs/heads/main/json-ld/consumer-financial-protection-bureau-context.jsonld
tags:
- Banking
- Complaints
- Consumer Protection
- Federal Government
- Financial Services
- HMDA
- Mortgages
- Open Data
- JSON-LD
- Linked Data
- Semantic Web
---
