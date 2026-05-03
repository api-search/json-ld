---
class_count: 3
classes:
- AnnualReport
- CountryAssessment
- PolicyRecommendation
context_file: json-ld/us-commission-on-international-religious-freedom-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/us-commission-on-international-religious-freedom/refs/heads/main/json-ld/us-commission-on-international-religious-freedom-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Us Commission On International Religious Freedom from US Commission on International Religious Freedom.
layout: jsonld
name: Us Commission On International Religious Freedom Context
namespaces:
- prefix: uscirf
  uri: https://www.uscirf.gov/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: addressee
  type: string
- container: ''
  name: category
  type: string
- container: ''
  name: countries_assessed
  type: integer
- container: ''
  name: country
  type: string
- container: ''
  name: country_name
  type: string
- container: set
  name: cpc_countries
  type: string
- container: ''
  name: designation_status
  type: string
- container: set
  name: epc_entities
  type: string
- container: ''
  name: iso_code
  type: string
- container: set
  name: key_themes
  type: string
- container: set
  name: key_violations
  type: string
- container: ''
  name: pdf_url
  type: reference
- container: ''
  name: publication_date
  type: date
- container: ''
  name: rationale
  type: string
- container: ''
  name: recommendation_id
  type: string
- container: ''
  name: recommendation_text
  type: string
- container: set
  name: recommendations
  type: string
- container: set
  name: related_violations
  type: string
- container: set
  name: religious_minorities_at_risk
  type: string
- container: ''
  name: report_url
  type: reference
- container: ''
  name: report_year
  type: integer
- container: ''
  name: severity_level
  type: string
- container: ''
  name: state_department_designation
  type: string
- container: set
  name: swl_countries
  type: string
- container: ''
  name: title
  type: string
property_count: 25
provider_name: US Commission on International Religious Freedom
provider_slug: us-commission-on-international-religious-freedom
slug: us-commission-on-international-religious-freedom-context
source_filename: us-commission-on-international-religious-freedom-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"uscirf\": \"https://www.uscirf.gov/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AnnualReport\": \"uscirf:AnnualReport\",\n    \"CountryAssessment\": \"uscirf:CountryAssessment\",\n    \"PolicyRecommendation\": \"uscirf:PolicyRecommendation\",\n    \"addressee\": {\n      \"@id\": \"uscirf:addressee\",\n      \"@type\": \"xsd:string\"\n    },\n    \"category\": {\n      \"@id\": \"uscirf:category\",\n      \"@type\": \"xsd:string\"\n    },\n    \"countries_assessed\": {\n      \"@id\": \"uscirf:countries_assessed\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"country\": {\n      \"@id\": \"uscirf:country\",\n      \"@type\": \"xsd:string\"\n    },\n    \"country_name\": {\n      \"@id\": \"uscirf:country_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cpc_countries\": {\n      \"@id\": \"uscirf:cpc_countries\"\
  ,\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"designation_status\": {\n      \"@id\": \"uscirf:designation_status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"epc_entities\": {\n      \"@id\": \"uscirf:epc_entities\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"iso_code\": {\n      \"@id\": \"uscirf:iso_code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"key_themes\": {\n      \"@id\": \"uscirf:key_themes\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"key_violations\": {\n      \"@id\": \"uscirf:key_violations\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pdf_url\": {\n      \"@id\": \"uscirf:pdf_url\",\n      \"@type\": \"@id\"\n    },\n    \"publication_date\": {\n      \"@id\": \"uscirf:publication_date\",\n      \"@type\": \"xsd:date\"\n    },\n    \"rationale\": {\n      \"@id\": \"uscirf:rationale\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"recommendation_id\": {\n      \"@id\": \"uscirf:recommendation_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"recommendation_text\": {\n      \"@id\": \"uscirf:recommendation_text\",\n      \"@type\": \"xsd:string\"\n    },\n    \"recommendations\": {\n      \"@id\": \"uscirf:recommendations\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"related_violations\": {\n      \"@id\": \"uscirf:related_violations\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"religious_minorities_at_risk\": {\n      \"@id\": \"uscirf:religious_minorities_at_risk\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"report_url\": {\n      \"@id\": \"uscirf:report_url\",\n      \"@type\": \"@id\"\n    },\n    \"report_year\": {\n      \"@id\": \"uscirf:report_year\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"severity_level\": {\n      \"@id\": \"uscirf:severity_level\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"state_department_designation\": {\n      \"@id\": \"uscirf:state_department_designation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"swl_countries\": {\n      \"@id\": \"uscirf:swl_countries\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"title\": {\n      \"@id\": \"uscirf:title\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/us-commission-on-international-religious-freedom/refs/heads/main/json-ld/us-commission-on-international-religious-freedom-context.jsonld
tags:
- Federal Government
- Religious Freedom
- International Human Rights
- Foreign Policy
- JSON-LD
- Linked Data
- Semantic Web
---
