---
class_count: 9
classes:
- GeoCode
- Links
- Error_500
- Error_404
- Location
- Issue
- Collection_Meta
- Error_400
- name
context_file: json-ld/amadeus-points-of-interest-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amadeus-traveler-media/refs/heads/main/json-ld/amadeus-points-of-interest-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amadeus Points Of Interest from Amadeus Traveler Media.
layout: jsonld
name: Amadeus Points Of Interest Context
namespaces:
- prefix: amadeus
  uri: https://amadeus.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: latitude
  type: decimal
- container: ''
  name: longitude
  type: decimal
- container: ''
  name: href
  type: reference
- container: set
  name: methods
  type: string
- container: set
  name: errors
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: self
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: subType
  type: string
- container: ''
  name: geoCode
  type: string
- container: ''
  name: category
  type: string
- container: set
  name: tags
  type: string
- container: ''
  name: rank
  type: string
- container: ''
  name: status
  type: integer
- container: ''
  name: code
  type: integer
- container: ''
  name: title
  type: string
- container: ''
  name: detail
  type: string
- container: ''
  name: source
  type: string
- container: ''
  name: count
  type: integer
- container: ''
  name: links
  type: string
property_count: 20
provider_name: Amadeus Traveler Media
provider_slug: amadeus-traveler-media
slug: amadeus-points-of-interest-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"amadeus\": \"https://amadeus.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"GeoCode\": \"amadeus:GeoCode\",\n    \"Links\": \"amadeus:Links\",\n    \"Error_500\": \"amadeus:Error_500\",\n    \"Error_404\": \"amadeus:Error_404\",\n    \"Location\": \"amadeus:Location\",\n    \"Issue\": \"amadeus:Issue\",\n    \"Collection_Meta\": \"amadeus:Collection_Meta\",\n    \"Error_400\": \"amadeus:Error_400\",\n    \"latitude\": {\n      \"@id\": \"amadeus:latitude\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"longitude\": {\n      \"@id\": \"amadeus:longitude\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"href\": {\n      \"@id\": \"amadeus:href\",\n      \"@type\": \"@id\"\n    },\n    \"methods\": {\n      \"@id\": \"amadeus:methods\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n\
  \    },\n    \"errors\": {\n      \"@id\": \"amadeus:errors\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"amadeus:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"self\": {\n      \"@id\": \"amadeus:self\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"amadeus:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subType\": {\n      \"@id\": \"amadeus:subType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"geoCode\": {\n      \"@id\": \"amadeus:geoCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"category\": {\n      \"@id\": \"amadeus:category\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tags\": {\n      \"@id\": \"amadeus:tags\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rank\": {\n      \"@id\": \"amadeus:rank\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"amadeus:status\"\
  ,\n      \"@type\": \"xsd:integer\"\n    },\n    \"code\": {\n      \"@id\": \"amadeus:code\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"title\": {\n      \"@id\": \"amadeus:title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"detail\": {\n      \"@id\": \"amadeus:detail\",\n      \"@type\": \"xsd:string\"\n    },\n    \"source\": {\n      \"@id\": \"amadeus:source\",\n      \"@type\": \"xsd:string\"\n    },\n    \"count\": {\n      \"@id\": \"amadeus:count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"links\": {\n      \"@id\": \"amadeus:links\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amadeus-traveler-media/refs/heads/main/json-ld/amadeus-points-of-interest-context.jsonld
tags:
- Content
- Destination
- Media
- Photos
- Points of Interest
- Tourism
- Travel
- JSON-LD
- Linked Data
- Semantic Web
---
