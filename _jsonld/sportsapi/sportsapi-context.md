---
class_count: 23
classes:
- ApiProvider
- name
- description
- url
- SportDataProvider
- pricing
- sportsSupported
- dataCategories
- coverageLevel
- PricingTier
- price
- priceCurrency
- requestLimit
- features
- Sport
- sportName
- leagues
- DataCategory
- categoryName
- includesLiveScores
- includesOdds
- includesStats
- includesFantasy
context_file: json-ld/sportsapi-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/sportsapi/refs/heads/main/json-ld/sportsapi-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Sportsapi from SportsAPI.
layout: jsonld
name: Sportsapi Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties: []
property_count: 0
provider_name: SportsAPI
provider_slug: sportsapi
slug: sportsapi-context
source_filename: sportsapi-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://sportsapi.com/ontology/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"ApiProvider\": \"schema:SoftwareApplication\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n\n    \"SportDataProvider\": \"sportsapi:SportDataProvider\",\n    \"pricing\": \"schema:offers\",\n    \"sportsSupported\": \"sportsapi:sportsSupported\",\n    \"dataCategories\": \"sportsapi:dataCategories\",\n    \"coverageLevel\": \"sportsapi:coverageLevel\",\n\n    \"PricingTier\": \"schema:Offer\",\n    \"price\": \"schema:price\",\n    \"priceCurrency\": \"schema:priceCurrency\",\n    \"requestLimit\": \"sportsapi:requestLimit\",\n    \"features\": \"schema:description\",\n\n    \"Sport\": \"sportsapi:Sport\",\n    \"sportName\": \"schema:name\",\n    \"leagues\": \"sportsapi:hasLeague\",\n\n    \"DataCategory\": \"sportsapi:DataCategory\"\
  ,\n    \"categoryName\": \"schema:name\",\n    \"includesLiveScores\": \"sportsapi:includesLiveScores\",\n    \"includesOdds\": \"sportsapi:includesOdds\",\n    \"includesStats\": \"sportsapi:includesStats\",\n    \"includesFantasy\": \"sportsapi:includesFantasy\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/sportsapi/refs/heads/main/json-ld/sportsapi-context.jsonld
tags:
- Sports
- Sports Data
- API Directory
- Comparison
- JSON-LD
- Linked Data
- Semantic Web
---
