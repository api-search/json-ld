---
class_count: 13
classes:
- City
- Country
- name
- cityCode
- unCode
- countryCode
- lat
- lng
- elevation
- timezone
- population
- wikipedia
- slug
context_file: json-ld/cities-database-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/cities-database-api/refs/heads/main/json-ld/cities-database-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Cities Database Api from Cities Database API.
layout: jsonld
name: Cities Database Api Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: airlabs
  uri: https://airlabs.co/vocab/
properties: []
property_count: 0
provider_name: Cities Database API
provider_slug: cities-database-api
slug: cities-database-api-context
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://airlabs.co/vocab/\",\n    \"schema\": \"https://schema.org/\",\n    \"airlabs\": \"https://airlabs.co/vocab/\",\n    \"City\": \"schema:City\",\n    \"Country\": \"schema:Country\",\n    \"name\": \"schema:name\",\n    \"cityCode\": \"airlabs:city_code\",\n    \"unCode\": \"airlabs:un_code\",\n    \"countryCode\": \"airlabs:country_code\",\n    \"lat\": \"schema:latitude\",\n    \"lng\": \"schema:longitude\",\n    \"elevation\": \"schema:elevation\",\n    \"timezone\": \"airlabs:timezone\",\n    \"population\": \"airlabs:population\",\n    \"wikipedia\": \"schema:sameAs\",\n    \"slug\": \"airlabs:slug\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/cities-database-api/refs/heads/main/json-ld/cities-database-api-context.jsonld
tags:
- Cities
- Data
- Geography
- Locations
- Reference Data
- Travel
- JSON-LD
- Linked Data
- Semantic Web
---
