---
api_specs:
- filename: agricultural-marketing-service-mars-api.yaml
  format: yaml
  label: USDA AMS MARS API (MyMarketNews)
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/agricultural-marketing-service/refs/heads/main/openapi/agricultural-marketing-service-mars-api.yaml
class_count: 9
classes:
- Report
- Office
- name
- Reports List Response
- Report Data Response
- Report Data
- Error Response
- Offices List Response
- Pagination Stats
context_file: json-ld/agricultural-marketing-service-mars-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/agricultural-marketing-service/refs/heads/main/json-ld/agricultural-marketing-service-mars-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Agricultural Marketing Service Mars Api from Agricultural Marketing Service.
layout: jsonld
name: Agricultural Marketing Service Mars Api Context
namespaces:
- prefix: ams
  uri: https://ams.usda.gov/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: slugId
  type: string
- container: ''
  name: slugName
  type: string
- container: ''
  name: reportDate
  type: date
- container: ''
  name: publishedDate
  type: dateTime
- container: ''
  name: commodity
  type: string
- container: ''
  name: marketType
  type: string
- container: ''
  name: office
  type: string
- container: ''
  name: sectionName
  type: string
- container: ''
  name: officeId
  type: string
- container: ''
  name: city
  type: string
- container: ''
  name: state
  type: string
- container: set
  name: commodities
  type: string
- container: set
  name: results
  type: string
- container: ''
  name: stats
  type: string
- container: ''
  name: class
  type: string
- container: ''
  name: grade
  type: string
- container: ''
  name: headCount
  type: integer
- container: ''
  name: pricePerCwt
  type: double
- container: ''
  name: priceUnit
  type: string
- container: ''
  name: region
  type: string
- container: ''
  name: error
  type: string
- container: ''
  name: message
  type: string
- container: ''
  name: status
  type: integer
- container: ''
  name: count
  type: integer
- container: ''
  name: total
  type: integer
property_count: 25
provider_name: Agricultural Marketing Service
provider_slug: agricultural-marketing-service
slug: agricultural-marketing-service-mars-api-context
source_filename: agricultural-marketing-service-mars-api-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"ams\": \"https://ams.usda.gov/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Report\": \"ams:Report\",\n    \"slugId\": {\n      \"@id\": \"ams:slug_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"slugName\": {\n      \"@id\": \"ams:slug_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reportDate\": {\n      \"@id\": \"ams:report_date\",\n      \"@type\": \"xsd:date\"\n    },\n    \"publishedDate\": {\n      \"@id\": \"ams:published_date\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"commodity\": {\n      \"@id\": \"ams:commodity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"marketType\": {\n      \"@id\": \"ams:market_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"office\": {\n      \"@id\": \"ams:office\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sectionName\": {\n   \
  \   \"@id\": \"ams:section_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Office\": \"ams:Office\",\n    \"officeId\": {\n      \"@id\": \"ams:office_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"city\": {\n      \"@id\": \"ams:city\",\n      \"@type\": \"xsd:string\"\n    },\n    \"state\": {\n      \"@id\": \"ams:state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"commodities\": {\n      \"@id\": \"ams:commodities\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Reports List Response\": \"ams:Reports List Response\",\n    \"results\": {\n      \"@id\": \"ams:results\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stats\": {\n      \"@id\": \"ams:stats\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Report Data Response\": \"ams:Report Data Response\",\n    \"Report Data\": \"ams:Report Data\",\n    \"class\": {\n      \"@id\": \"ams:class\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"grade\": {\n      \"@id\": \"ams:grade\",\n      \"@type\": \"xsd:string\"\n    },\n    \"headCount\": {\n      \"@id\": \"ams:head_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"pricePerCwt\": {\n      \"@id\": \"ams:price_per_cwt\",\n      \"@type\": \"xsd:double\"\n    },\n    \"priceUnit\": {\n      \"@id\": \"ams:price_unit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"region\": {\n      \"@id\": \"ams:region\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Error Response\": \"ams:Error Response\",\n    \"error\": {\n      \"@id\": \"ams:error\",\n      \"@type\": \"xsd:string\"\n    },\n    \"message\": {\n      \"@id\": \"ams:message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"ams:status\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"Offices List Response\": \"ams:Offices List Response\",\n    \"Pagination Stats\": \"ams:Pagination Stats\",\n    \"count\": {\n      \"@id\": \"ams:count\"\
  ,\n      \"@type\": \"xsd:integer\"\n    },\n    \"total\": {\n      \"@id\": \"ams:total\",\n      \"@type\": \"xsd:integer\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/agricultural-marketing-service/refs/heads/main/json-ld/agricultural-marketing-service-mars-api-context.jsonld
tags:
- Agriculture
- Federal Government
- Market News
- Livestock
- Dairy
- Fruits And Vegetables
- Cotton
- Tobacco
- JSON-LD
- Linked Data
- Semantic Web
---
