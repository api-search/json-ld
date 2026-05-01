---
api_specs:
- filename: flutter-pub-dev-openapi.yml
  format: yaml
  label: Pub.dev API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-flutter/refs/heads/main/openapi/flutter-pub-dev-openapi.yml
class_count: 0
classes: []
context_file: json-ld/google-flutter-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-flutter/refs/heads/main/json-ld/google-flutter-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Google Flutter from Google Flutter.
layout: jsonld
name: Google Flutter Context
namespaces:
- prefix: flutter
  uri: https://flutter.dev/ns/
- prefix: pub
  uri: https://pub.dev/ns/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Package
  type: ''
- container: ''
  name: PackageVersion
  type: ''
- container: ''
  name: PackageScore
  type: ''
property_count: 3
provider_name: Google Flutter
provider_slug: google-flutter
slug: google-flutter-context
source_filename: google-flutter-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"flutter\": \"https://flutter.dev/ns/\",\n    \"pub\": \"https://pub.dev/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Package\": {\n      \"@id\": \"pub:Package\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"version\": \"schema:version\",\n        \"homepage\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"repository\": {\n          \"@id\": \"schema:codeRepository\",\n          \"@type\": \"@id\"\n        },\n        \"publishedAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"license\": \"schema:license\"\n      }\n    },\n\n    \"PackageVersion\": {\n      \"@id\": \"pub:PackageVersion\",\n      \"@context\": {\n        \"version\"\
  : \"schema:version\",\n        \"archiveUrl\": {\n          \"@id\": \"schema:downloadUrl\",\n          \"@type\": \"@id\"\n        },\n        \"published\": {\n          \"@id\": \"dcterms:issued\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"PackageScore\": {\n      \"@id\": \"pub:PackageScore\",\n      \"@context\": {\n        \"grantedPoints\": \"pub:grantedPoints\",\n        \"maxPoints\": \"pub:maxPoints\",\n        \"likeCount\": \"schema:interactionCount\",\n        \"popularityScore\": \"pub:popularityScore\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-flutter/refs/heads/main/json-ld/google-flutter-context.jsonld
tags:
- Cross-Platform
- Dart
- Google
- Mobile Development
- Open Source
- UI Framework
- JSON-LD
- Linked Data
- Semantic Web
---
