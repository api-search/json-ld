---
class_count: 1
classes:
- Position
context_file: json-ld/apache-cordova-geolocation-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apache-cordova/refs/heads/main/json-ld/apache-cordova-geolocation-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apache Cordova Geolocation from Apache Cordova.
layout: jsonld
name: Apache Cordova Geolocation Context
namespaces:
- prefix: cordova
  uri: https://cordova.apache.org/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: accuracy
  type: decimal
- container: ''
  name: altitude
  type: decimal
- container: ''
  name: altitudeAccuracy
  type: decimal
- container: ''
  name: coords
  type: reference
- container: ''
  name: heading
  type: decimal
- container: ''
  name: latitude
  type: decimal
- container: ''
  name: longitude
  type: decimal
- container: ''
  name: speed
  type: decimal
- container: ''
  name: timestamp
  type: integer
property_count: 9
provider_name: Apache Cordova
provider_slug: apache-cordova
slug: apache-cordova-geolocation-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"cordova\": \"https://cordova.apache.org/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Position\": \"cordova:Position\",\n    \"accuracy\": {\n      \"@id\": \"cordova:accuracy\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"altitude\": {\n      \"@id\": \"cordova:altitude\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"altitudeAccuracy\": {\n      \"@id\": \"cordova:altitudeAccuracy\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"coords\": {\n      \"@id\": \"cordova:coords\",\n      \"@type\": \"@id\"\n    },\n    \"heading\": {\n      \"@id\": \"cordova:heading\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"latitude\": {\n      \"@id\": \"cordova:latitude\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"longitude\": {\n      \"@id\": \"cordova:longitude\",\n      \"@type\": \"xsd:decimal\"\
  \n    },\n    \"speed\": {\n      \"@id\": \"cordova:speed\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"timestamp\": {\n      \"@id\": \"cordova:timestamp\",\n      \"@type\": \"xsd:integer\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/apache-cordova/refs/heads/main/json-ld/apache-cordova-geolocation-context.jsonld
tags:
- Apache
- Cross-Platform
- Hybrid Apps
- JavaScript
- Mobile
- Open Source
- Plugins
- JSON-LD
- Linked Data
- Semantic Web
---
