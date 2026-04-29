---
class_count: 8
classes:
- Country
- City
- Phrase
- SafetyInfo
- CostInfo
- VisaInfo
- HealthInfo
- ErrorResponse
context_file: json-ld/basetrip-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/basetrip/refs/heads/main/json-ld/basetrip-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Basetrip from Basetrip.
layout: jsonld
name: Basetrip Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: basetrip
  uri: https://raw.githubusercontent.com/api-evangelist/basetrip/refs/heads/main/json-ld/
properties:
- container: ''
  name: name
  type: string
- container: ''
  name: slug
  type: string
- container: ''
  name: code
  type: string
- container: ''
  name: continent
  type: string
- container: ''
  name: capital
  type: string
- container: ''
  name: currency
  type: string
- container: ''
  name: languages
  type: string
- container: ''
  name: population
  type: integer
- container: ''
  name: timezone
  type: string
- container: ''
  name: callingCode
  type: string
- container: ''
  name: latitude
  type: decimal
- container: ''
  name: longitude
  type: decimal
- container: ''
  name: category
  type: string
- container: ''
  name: original
  type: string
- container: ''
  name: translation
  type: string
- container: ''
  name: phonetic
  type: string
- container: ''
  name: overallRating
  type: string
- container: ''
  name: advisoryLevel
  type: integer
- container: ''
  name: budgetPerDay
  type: decimal
- container: ''
  name: midRangePerDay
  type: decimal
- container: ''
  name: luxuryPerDay
  type: decimal
- container: ''
  name: destination
  type: string
- container: ''
  name: passport
  type: string
- container: ''
  name: requirement
  type: string
- container: ''
  name: maxStay
  type: integer
- container: ''
  name: vaccinations
  type: string
- container: ''
  name: healthRisks
  type: string
- container: ''
  name: drinkingWater
  type: string
- container: ''
  name: medicalFacilities
  type: string
- container: ''
  name: error
  type: string
- container: ''
  name: message
  type: string
- container: ''
  name: statusCode
  type: integer
property_count: 32
provider_name: Basetrip
provider_slug: basetrip
slug: basetrip-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"basetrip\": \"https://raw.githubusercontent.com/api-evangelist/basetrip/refs/heads/main/json-ld/\",\n    \"Country\": \"schema:Country\",\n    \"name\": {\"@id\": \"schema:name\", \"@type\": \"xsd:string\"},\n    \"slug\": {\"@id\": \"basetrip:slug\", \"@type\": \"xsd:string\"},\n    \"code\": {\"@id\": \"schema:identifier\", \"@type\": \"xsd:string\"},\n    \"continent\": {\"@id\": \"schema:containedInPlace\", \"@type\": \"xsd:string\"},\n    \"capital\": {\"@id\": \"schema:location\", \"@type\": \"xsd:string\"},\n    \"currency\": {\"@id\": \"schema:currency\", \"@type\": \"xsd:string\"},\n    \"languages\": {\"@id\": \"schema:knowsLanguage\", \"@type\": \"xsd:string\"},\n    \"population\": {\"@id\": \"schema:population\", \"@type\": \"xsd:integer\"},\n    \"timezone\": {\"@id\": \"basetrip:timezone\", \"@type\": \"xsd:string\"\
  },\n    \"callingCode\": {\"@id\": \"basetrip:callingCode\", \"@type\": \"xsd:string\"},\n    \"City\": \"schema:City\",\n    \"latitude\": {\"@id\": \"schema:latitude\", \"@type\": \"xsd:decimal\"},\n    \"longitude\": {\"@id\": \"schema:longitude\", \"@type\": \"xsd:decimal\"},\n    \"Phrase\": \"basetrip:Phrase\",\n    \"category\": {\"@id\": \"schema:category\", \"@type\": \"xsd:string\"},\n    \"original\": {\"@id\": \"basetrip:original\", \"@type\": \"xsd:string\"},\n    \"translation\": {\"@id\": \"basetrip:translation\", \"@type\": \"xsd:string\"},\n    \"phonetic\": {\"@id\": \"basetrip:phonetic\", \"@type\": \"xsd:string\"},\n    \"SafetyInfo\": \"basetrip:SafetyInfo\",\n    \"overallRating\": {\"@id\": \"basetrip:overallRating\", \"@type\": \"xsd:string\"},\n    \"advisoryLevel\": {\"@id\": \"basetrip:advisoryLevel\", \"@type\": \"xsd:integer\"},\n    \"CostInfo\": \"basetrip:CostInfo\",\n    \"budgetPerDay\": {\"@id\": \"schema:price\", \"@type\": \"xsd:decimal\"},\n    \"\
  midRangePerDay\": {\"@id\": \"basetrip:midRangePerDay\", \"@type\": \"xsd:decimal\"},\n    \"luxuryPerDay\": {\"@id\": \"basetrip:luxuryPerDay\", \"@type\": \"xsd:decimal\"},\n    \"VisaInfo\": \"basetrip:VisaInfo\",\n    \"destination\": {\"@id\": \"schema:destination\", \"@type\": \"xsd:string\"},\n    \"passport\": {\"@id\": \"basetrip:passport\", \"@type\": \"xsd:string\"},\n    \"requirement\": {\"@id\": \"basetrip:requirement\", \"@type\": \"xsd:string\"},\n    \"maxStay\": {\"@id\": \"basetrip:maxStay\", \"@type\": \"xsd:integer\"},\n    \"HealthInfo\": \"basetrip:HealthInfo\",\n    \"vaccinations\": {\"@id\": \"basetrip:vaccinations\", \"@type\": \"xsd:string\"},\n    \"healthRisks\": {\"@id\": \"basetrip:healthRisks\", \"@type\": \"xsd:string\"},\n    \"drinkingWater\": {\"@id\": \"basetrip:drinkingWater\", \"@type\": \"xsd:string\"},\n    \"medicalFacilities\": {\"@id\": \"basetrip:medicalFacilities\", \"@type\": \"xsd:string\"},\n    \"ErrorResponse\": \"basetrip:ErrorResponse\"\
  ,\n    \"error\": {\"@id\": \"basetrip:error\", \"@type\": \"xsd:string\"},\n    \"message\": {\"@id\": \"schema:description\", \"@type\": \"xsd:string\"},\n    \"statusCode\": {\"@id\": \"basetrip:statusCode\", \"@type\": \"xsd:integer\"}\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/basetrip/refs/heads/main/json-ld/basetrip-context.jsonld
tags:
- Cities
- Countries
- Health
- Safety
- Travel
- Visa
- JSON-LD
- Linked Data
- Semantic Web
---
