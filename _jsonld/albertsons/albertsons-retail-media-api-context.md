---
class_count: 13
classes:
- Audience List Response
- Audience
- Campaign List Response
- Campaign
- Create Campaign Request
- Error Response
- Performance Metric
- Performance Metrics Response
- Report Request
- Report Response
- createdAt
- description
- name
context_file: json-ld/albertsons-retail-media-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/albertsons/refs/heads/main/json-ld/albertsons-retail-media-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Albertsons Retail Media Api from albertsons.
layout: jsonld
name: Albertsons Retail Media Api Context
namespaces:
- prefix: alb
  uri: https://albertsons.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: audienceId
  type: string
- container: set
  name: audiences
  type: string
- container: ''
  name: budget
  type: double
- container: ''
  name: campaignId
  type: string
- container: set
  name: campaignIds
  type: string
- container: set
  name: campaigns
  type: string
- container: ''
  name: category
  type: string
- container: ''
  name: clickThroughRate
  type: double
- container: ''
  name: clicks
  type: integer
- container: ''
  name: conversions
  type: integer
- container: ''
  name: date
  type: date
- container: set
  name: dimensions
  type: string
- container: ''
  name: downloadUrl
  type: reference
- container: ''
  name: endDate
  type: date
- container: ''
  name: error
  type: string
- container: ''
  name: format
  type: string
- container: ''
  name: impressions
  type: integer
- container: ''
  name: limit
  type: integer
- container: ''
  name: message
  type: string
- container: set
  name: metrics
  type: string
- container: ''
  name: offset
  type: integer
- container: ''
  name: reportId
  type: string
- container: ''
  name: roas
  type: double
- container: ''
  name: size
  type: integer
- container: ''
  name: spend
  type: double
- container: ''
  name: startDate
  type: date
- container: ''
  name: status
  type: string
- container: ''
  name: statusCode
  type: integer
- container: set
  name: targetAudienceIds
  type: string
- container: ''
  name: total
  type: integer
property_count: 30
provider_name: albertsons
provider_slug: albertsons
slug: albertsons-retail-media-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"alb\": \"https://albertsons.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Audience List Response\": \"alb:Audience List Response\",\n    \"Audience\": \"alb:Audience\",\n    \"Campaign List Response\": \"alb:Campaign List Response\",\n    \"Campaign\": \"alb:Campaign\",\n    \"Create Campaign Request\": \"alb:Create Campaign Request\",\n    \"Error Response\": \"alb:Error Response\",\n    \"Performance Metric\": \"alb:Performance Metric\",\n    \"Performance Metrics Response\": \"alb:Performance Metrics Response\",\n    \"Report Request\": \"alb:Report Request\",\n    \"Report Response\": \"alb:Report Response\",\n    \"audienceId\": {\n      \"@id\": \"alb:audienceId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"audiences\": {\n      \"@id\": \"alb:audiences\",\n      \"@container\": \"@set\",\n   \
  \   \"@type\": \"xsd:string\"\n    },\n    \"budget\": {\n      \"@id\": \"alb:budget\",\n      \"@type\": \"xsd:double\"\n    },\n    \"campaignId\": {\n      \"@id\": \"alb:campaignId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"campaignIds\": {\n      \"@id\": \"alb:campaignIds\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"campaigns\": {\n      \"@id\": \"alb:campaigns\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"category\": {\n      \"@id\": \"alb:category\",\n      \"@type\": \"xsd:string\"\n    },\n    \"clickThroughRate\": {\n      \"@id\": \"alb:clickThroughRate\",\n      \"@type\": \"xsd:double\"\n    },\n    \"clicks\": {\n      \"@id\": \"alb:clicks\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"conversions\": {\n      \"@id\": \"alb:conversions\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"createdAt\": \"schema:dateCreated\",\n    \"date\": {\n      \"@id\": \"alb:date\",\n      \"\
  @type\": \"xsd:date\"\n    },\n    \"description\": \"schema:description\",\n    \"dimensions\": {\n      \"@id\": \"alb:dimensions\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"downloadUrl\": {\n      \"@id\": \"alb:downloadUrl\",\n      \"@type\": \"@id\"\n    },\n    \"endDate\": {\n      \"@id\": \"alb:endDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"error\": {\n      \"@id\": \"alb:error\",\n      \"@type\": \"xsd:string\"\n    },\n    \"format\": {\n      \"@id\": \"alb:format\",\n      \"@type\": \"xsd:string\"\n    },\n    \"impressions\": {\n      \"@id\": \"alb:impressions\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"limit\": {\n      \"@id\": \"alb:limit\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"message\": {\n      \"@id\": \"alb:message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"metrics\": {\n      \"@id\": \"alb:metrics\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"\
  name\": \"schema:name\",\n    \"offset\": {\n      \"@id\": \"alb:offset\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"reportId\": {\n      \"@id\": \"alb:reportId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"roas\": {\n      \"@id\": \"alb:roas\",\n      \"@type\": \"xsd:double\"\n    },\n    \"size\": {\n      \"@id\": \"alb:size\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"spend\": {\n      \"@id\": \"alb:spend\",\n      \"@type\": \"xsd:double\"\n    },\n    \"startDate\": {\n      \"@id\": \"alb:startDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"status\": {\n      \"@id\": \"alb:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"statusCode\": {\n      \"@id\": \"alb:statusCode\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"targetAudienceIds\": {\n      \"@id\": \"alb:targetAudienceIds\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"total\": {\n      \"@id\": \"alb:total\",\n      \"@type\": \"xsd:integer\"\n\
  \    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/albertsons/refs/heads/main/json-ld/albertsons-retail-media-api-context.jsonld
tags:
- Grocery
- Retail
- Retail Media
- Advertising
- Campaigns
- Analytics
- Consumer Goods
- Food
- Pharmacy
- JSON-LD
- Linked Data
- Semantic Web
---
