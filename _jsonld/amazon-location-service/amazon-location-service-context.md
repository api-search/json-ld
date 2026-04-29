---
api_specs:
- filename: amazon-location-service-openapi.yml
  format: yaml
  label: Amazon Location Service REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-location-service/refs/heads/main/openapi/amazon-location-service-openapi.yml
class_count: 2
classes:
- MapResource
- Tracker
context_file: json-ld/amazon-location-service-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-location-service/refs/heads/main/json-ld/amazon-location-service-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Location Service from Amazon Location Service.
layout: jsonld
name: Amazon Location Service Context
namespaces:
- prefix: locationservice
  uri: https://locationservice.amazonaws.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: id
  type: string
- container: ''
  name: name
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: arn
  type: string
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: updatedAt
  type: dateTime
property_count: 7
provider_name: Amazon Location Service
provider_slug: amazon-location-service
slug: amazon-location-service-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"locationservice\": \"https://locationservice.amazonaws.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"MapResource\": \"locationservice:MapResource\",\n    \"Tracker\": \"locationservice:Tracker\",\n    \"id\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"locationservice:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"arn\": {\n      \"@id\": \"locationservice:arn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updatedAt\": {\n\
  \      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-location-service/refs/heads/main/json-ld/amazon-location-service-context.jsonld
tags:
- AWS
- Geocoding
- Geofencing
- Location
- Maps
- Routing
- JSON-LD
- Linked Data
- Semantic Web
---
