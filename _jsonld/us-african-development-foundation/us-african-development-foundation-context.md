---
api_specs:
- filename: usadf-grants-api-openapi.yml
  format: yaml
  label: USADF Grants Data API
  slug: grants-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/us-african-development-foundation/refs/heads/main/openapi/usadf-grants-api-openapi.yml
- filename: usadf-grant-opportunities-api-openapi.yml
  format: yaml
  label: USADF Grant Opportunities API
  slug: grant-opportunities-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/us-african-development-foundation/refs/heads/main/openapi/usadf-grant-opportunities-api-openapi.yml
class_count: 51
classes:
- AwardSearchRequest
- AwardSearchResponse
- Award
- RecipientSummary
- Recipient
- PlaceOfPerformance
- AgencyAwardSummary
- SpendingByGeographyRequest
- SpendingByGeographyResponse
- APIError
- OpportunitySearchRequest
- OpportunitySearchResponse
- Opportunity
- agencyCode
- agencyName
- awarding_agency
- category
- cfdaList
- country_code
- eligibilityExplanation
- eligibleApplicants
- errorCode
- errorMessage
- fields
- filters
- generated_unique_award_id
- geo_layer
- id
- keyword
- location
- number
- oppHits
- oppStatus
- order
- page_metadata
- place_of_performance
- recipient
- recipient_level
- recipient_name
- recipient_uei
- results
- scope
- sort
- sortBy
- sortOrder
- synopsis
- title
- toptier_code
- type
- type_description
- uei
context_file: json-ld/us-african-development-foundation-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/us-african-development-foundation/refs/heads/main/json-ld/us-african-development-foundation-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Us African Development Foundation from US African Development Foundation.
layout: jsonld
name: Us African Development Foundation Context
namespaces:
- prefix: usadf
  uri: https://www.usadf.gov/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: gov
  uri: https://www.w3.org/ns/gov/
- prefix: dcat
  uri: http://www.w3.org/ns/dcat#
properties:
- container: ''
  name: awardCeiling
  type: decimal
- container: ''
  name: awardFloor
  type: decimal
- container: ''
  name: award_count
  type: integer
- container: ''
  name: base_and_all_options_value
  type: decimal
- container: ''
  name: city_name
  type: ''
- container: ''
  name: closeDate
  type: ''
- container: ''
  name: contactEmail
  type: ''
- container: ''
  name: contactName
  type: ''
- container: ''
  name: country_name
  type: ''
- container: ''
  name: description
  type: ''
- container: ''
  name: estimatedTotalProgramFunding
  type: decimal
- container: ''
  name: expectedNumberOfAwards
  type: integer
- container: ''
  name: fiscal_year
  type: integer
- container: ''
  name: hitCount
  type: integer
- container: ''
  name: limit
  type: integer
- container: ''
  name: name
  type: ''
- container: ''
  name: openDate
  type: ''
- container: ''
  name: page
  type: integer
- container: ''
  name: period_of_performance_current_end_date
  type: date
- container: ''
  name: period_of_performance_start_date
  type: date
- container: ''
  name: recipient_count
  type: integer
- container: ''
  name: rows
  type: integer
- container: ''
  name: startRecordNum
  type: integer
- container: ''
  name: total
  type: ''
- container: ''
  name: total_obligation
  type: decimal
- container: ''
  name: total_obligations
  type: decimal
- container: ''
  name: total_transaction_amount
  type: decimal
- container: ''
  name: total_transactions
  type: integer
- container: ''
  name: transaction_count
  type: integer
property_count: 29
provider_name: US African Development Foundation
provider_slug: us-african-development-foundation
slug: us-african-development-foundation-context
source_filename: us-african-development-foundation-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"usadf\": \"https://www.usadf.gov/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"gov\": \"https://www.w3.org/ns/gov/\",\n    \"dcat\": \"http://www.w3.org/ns/dcat#\",\n    \"AwardSearchRequest\": \"usadf:AwardSearchRequest\",\n    \"AwardSearchResponse\": \"usadf:AwardSearchResponse\",\n    \"Award\": \"usadf:Award\",\n    \"RecipientSummary\": \"usadf:RecipientSummary\",\n    \"Recipient\": \"usadf:Recipient\",\n    \"PlaceOfPerformance\": \"usadf:PlaceOfPerformance\",\n    \"AgencyAwardSummary\": \"usadf:AgencyAwardSummary\",\n    \"SpendingByGeographyRequest\": \"usadf:SpendingByGeographyRequest\",\n    \"SpendingByGeographyResponse\": \"usadf:SpendingByGeographyResponse\",\n    \"APIError\": \"usadf:APIError\",\n    \"OpportunitySearchRequest\": \"usadf:OpportunitySearchRequest\",\n    \"OpportunitySearchResponse\": \"usadf:OpportunitySearchResponse\",\n    \"Opportunity\": \"usadf:Opportunity\"\
  ,\n    \"agencyCode\": \"usadf:agencyCode\",\n    \"agencyName\": \"usadf:agencyName\",\n    \"awardCeiling\": {\n      \"@id\": \"usadf:awardCeiling\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"awardFloor\": {\n      \"@id\": \"usadf:awardFloor\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"award_count\": {\n      \"@id\": \"usadf:award_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"awarding_agency\": \"usadf:awarding_agency\",\n    \"base_and_all_options_value\": {\n      \"@id\": \"usadf:base_and_all_options_value\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"category\": \"usadf:category\",\n    \"cfdaList\": \"usadf:cfdaList\",\n    \"city_name\": {\n      \"@id\": \"schema:addressLocality\"\n    },\n    \"closeDate\": {\n      \"@id\": \"schema:endDate\"\n    },\n    \"contactEmail\": {\n      \"@id\": \"schema:email\"\n    },\n    \"contactName\": {\n      \"@id\": \"schema:contactPoint\"\n    },\n    \"country_code\": \"usadf:country_code\",\n    \"\
  country_name\": {\n      \"@id\": \"schema:addressCountry\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\"\n    },\n    \"eligibilityExplanation\": \"usadf:eligibilityExplanation\",\n    \"eligibleApplicants\": \"usadf:eligibleApplicants\",\n    \"errorCode\": \"usadf:errorCode\",\n    \"errorMessage\": \"usadf:errorMessage\",\n    \"estimatedTotalProgramFunding\": {\n      \"@id\": \"usadf:estimatedTotalProgramFunding\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"expectedNumberOfAwards\": {\n      \"@id\": \"usadf:expectedNumberOfAwards\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"fields\": \"usadf:fields\",\n    \"filters\": \"usadf:filters\",\n    \"fiscal_year\": {\n      \"@id\": \"usadf:fiscal_year\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"generated_unique_award_id\": \"usadf:generated_unique_award_id\",\n    \"geo_layer\": \"usadf:geo_layer\",\n    \"hitCount\": {\n      \"@id\": \"usadf:hitCount\",\n      \"@type\": \"xsd:integer\"\
  \n    },\n    \"id\": \"usadf:id\",\n    \"keyword\": \"usadf:keyword\",\n    \"limit\": {\n      \"@id\": \"usadf:limit\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"location\": \"usadf:location\",\n    \"name\": {\n      \"@id\": \"schema:name\"\n    },\n    \"number\": \"usadf:number\",\n    \"openDate\": {\n      \"@id\": \"schema:startDate\"\n    },\n    \"oppHits\": \"usadf:oppHits\",\n    \"oppStatus\": \"usadf:oppStatus\",\n    \"order\": \"usadf:order\",\n    \"page\": {\n      \"@id\": \"usadf:page\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"page_metadata\": \"usadf:page_metadata\",\n    \"period_of_performance_current_end_date\": {\n      \"@id\": \"usadf:period_of_performance_current_end_date\",\n      \"@type\": \"xsd:date\"\n    },\n    \"period_of_performance_start_date\": {\n      \"@id\": \"usadf:period_of_performance_start_date\",\n      \"@type\": \"xsd:date\"\n    },\n    \"place_of_performance\": \"usadf:place_of_performance\",\n    \"recipient\": \"\
  usadf:recipient\",\n    \"recipient_count\": {\n      \"@id\": \"usadf:recipient_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"recipient_level\": \"usadf:recipient_level\",\n    \"recipient_name\": \"usadf:recipient_name\",\n    \"recipient_uei\": \"usadf:recipient_uei\",\n    \"results\": \"usadf:results\",\n    \"rows\": {\n      \"@id\": \"usadf:rows\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"scope\": \"usadf:scope\",\n    \"sort\": \"usadf:sort\",\n    \"sortBy\": \"usadf:sortBy\",\n    \"sortOrder\": \"usadf:sortOrder\",\n    \"startRecordNum\": {\n      \"@id\": \"usadf:startRecordNum\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"synopsis\": \"usadf:synopsis\",\n    \"title\": \"usadf:title\",\n    \"toptier_code\": \"usadf:toptier_code\",\n    \"total\": {\n      \"@id\": \"schema:totalPrice\"\n    },\n    \"total_obligation\": {\n      \"@id\": \"usadf:total_obligation\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"total_obligations\": {\n      \"\
  @id\": \"usadf:total_obligations\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"total_transaction_amount\": {\n      \"@id\": \"usadf:total_transaction_amount\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"total_transactions\": {\n      \"@id\": \"usadf:total_transactions\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"transaction_count\": {\n      \"@id\": \"usadf:transaction_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"type\": \"usadf:type\",\n    \"type_description\": \"usadf:type_description\",\n    \"uei\": \"usadf:uei\"\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/us-african-development-foundation/refs/heads/main/json-ld/us-african-development-foundation-context.jsonld
tags:
- Federal Government
- International Development
- Africa
- Grants
- Nonprofit
- Economic Development
- JSON-LD
- Linked Data
- Semantic Web
---
