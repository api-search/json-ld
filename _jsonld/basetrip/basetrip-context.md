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
