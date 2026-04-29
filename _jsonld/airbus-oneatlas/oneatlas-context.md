---
class_count: 0
classes: []
context_file: json-ld/oneatlas-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/airbus-oneatlas/refs/heads/main/json-ld/oneatlas-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Oneatlas from Airbus OneAtlas.
layout: jsonld
name: Oneatlas Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
- prefix: geo
  uri: http://www.opengis.net/ont/geosparql#
- prefix: oneatlas
  uri: https://raw.githubusercontent.com/api-evangelist/airbus-oneatlas/refs/heads/main/json-schema/
properties:
- container: ''
  name: CatalogItem
  type: ''
- container: ''
  name: id
  type: ''
- container: ''
  name: title
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: acquisitionDate
  type: dateTime
- container: ''
  name: cloudCover
  type: decimal
- container: ''
  name: geometry
  type: ''
- container: ''
  name: bbox
  type: ''
- container: ''
  name: Activity
  type: ''
- container: ''
  name: status
  type: string
- container: ''
  name: created
  type: dateTime
- container: ''
  name: updated
  type: dateTime
- container: ''
  name: ApiKey
  type: ''
- container: ''
  name: key
  type: string
- container: ''
  name: expiresAt
  type: dateTime
- container: ''
  name: elevation
  type: decimal
- container: ''
  name: latitude
  type: decimal
- container: ''
  name: longitude
  type: decimal
property_count: 18
provider_name: Airbus OneAtlas
provider_slug: airbus-oneatlas
slug: oneatlas-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"geo\": \"http://www.opengis.net/ont/geosparql#\",\n    \"oneatlas\": \"https://raw.githubusercontent.com/api-evangelist/airbus-oneatlas/refs/heads/main/json-schema/\",\n    \"CatalogItem\": {\n      \"@id\": \"schema:ImageObject\"\n    },\n    \"id\": {\n      \"@id\": \"@id\"\n    },\n    \"title\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"acquisitionDate\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"cloudCover\": {\n      \"@id\": \"schema:additionalProperty\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"geometry\": {\n      \"@id\": \"geo:hasGeometry\"\n    },\n    \"bbox\": {\n      \"@id\": \"schema:spatialCoverage\"\n    },\n\
  \    \"Activity\": {\n      \"@id\": \"schema:Action\"\n    },\n    \"status\": {\n      \"@id\": \"schema:actionStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"created\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updated\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"ApiKey\": {\n      \"@id\": \"schema:DigitalDocument\"\n    },\n    \"key\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"expiresAt\": {\n      \"@id\": \"schema:expires\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"elevation\": {\n      \"@id\": \"schema:elevation\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"latitude\": {\n      \"@id\": \"schema:latitude\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"longitude\": {\n      \"@id\": \"schema:longitude\",\n      \"@type\": \"xsd:decimal\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/airbus-oneatlas/refs/heads/main/json-ld/oneatlas-context.jsonld
tags:
- Imagery
- Satellites
- JSON-LD
- Linked Data
- Semantic Web
---
