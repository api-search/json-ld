---
api_specs:
- filename: us-army-public-openapi.yml
  format: yaml
  label: US Army Public API
  slug: us-army-public-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/us-army/refs/heads/main/openapi/us-army-public-openapi.yml
class_count: 20
classes:
- GovernmentOrganization
- NewsArticle
- Event
- Person
- ImageObject
- id
- title
- summary
- body
- author
- tags
- sourceOrg
- ArmyArticle
- ArmyEvent
- ArmyNewsItem
- ArmyUnit
- MilitaryCommand
- ArmyInstallation
- location
- category
context_file: json-ld/us-army-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/us-army/refs/heads/main/json-ld/us-army-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Us Army from US Army.
layout: jsonld
name: Us Army Context
namespaces:
- prefix: dct
  uri: http://purl.org/dc/terms/
- prefix: foaf
  uri: http://xmlns.com/foaf/0.1/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: army
  uri: https://www.army.mil/vocab/
properties:
- container: ''
  name: publishedDate
  type: dateTime
- container: ''
  name: updatedDate
  type: dateTime
- container: ''
  name: imageUrl
  type: reference
- container: ''
  name: url
  type: reference
- container: ''
  name: USARMY
  type: GovernmentOrganization
- container: ''
  name: startDate
  type: dateTime
- container: ''
  name: endDate
  type: dateTime
property_count: 7
provider_name: US Army
provider_slug: us-army
slug: us-army-context
source_filename: us-army-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"dct\": \"http://purl.org/dc/terms/\",\n    \"foaf\": \"http://xmlns.com/foaf/0.1/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"army\": \"https://www.army.mil/vocab/\",\n\n    \"GovernmentOrganization\": \"GovernmentOrganization\",\n    \"NewsArticle\": \"NewsArticle\",\n    \"Event\": \"Event\",\n    \"Person\": \"Person\",\n    \"ImageObject\": \"ImageObject\",\n\n    \"id\": \"@id\",\n    \"title\": \"headline\",\n    \"summary\": \"description\",\n    \"body\": \"articleBody\",\n    \"author\": \"author\",\n    \"publishedDate\": {\n      \"@id\": \"datePublished\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updatedDate\": {\n      \"@id\": \"dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"tags\": \"keywords\",\n    \"imageUrl\": {\n      \"@id\": \"image\",\n      \"@type\": \"@id\"\n    },\n    \"url\": {\n      \"@id\": \"url\",\n      \"@type\": \"@id\"\n\
  \    },\n    \"sourceOrg\": \"publisher\",\n\n    \"ArmyArticle\": \"army:ArmyArticle\",\n    \"ArmyEvent\": \"army:ArmyEvent\",\n    \"ArmyNewsItem\": \"army:ArmyNewsItem\",\n    \"ArmyUnit\": \"army:ArmyUnit\",\n    \"MilitaryCommand\": \"army:MilitaryCommand\",\n    \"ArmyInstallation\": \"army:ArmyInstallation\",\n\n    \"USARMY\": {\n      \"@id\": \"army:USARMY\",\n      \"@type\": \"GovernmentOrganization\"\n    },\n\n    \"startDate\": {\n      \"@id\": \"startDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"endDate\": {\n      \"@id\": \"endDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"location\": \"location\",\n    \"category\": \"eventStatus\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/us-army/refs/heads/main/json-ld/us-army-context.jsonld
tags:
- Army
- Federal Government
- Military
- Defense
- Open Data
- News
- JSON-LD
- Linked Data
- Semantic Web
---
