---
class_count: 2
classes:
- AndroidApp
- description
context_file: json-ld/adyen-management-android-app-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-android-app-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Management Android App from Adyen.
layout: jsonld
name: Adyen Management Android App Context
namespaces:
- prefix: adyen
  uri: https://docs.adyen.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: errorCode
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: label
  type: string
- container: ''
  name: packageName
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: versionCode
  type: integer
- container: ''
  name: versionName
  type: string
property_count: 7
provider_name: Adyen
provider_slug: adyen
slug: adyen-management-android-app-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AndroidApp\": \"adyen:AndroidApp\",\n    \"description\": \"schema:description\",\n    \"errorCode\": {\n      \"@id\": \"adyen:errorCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"adyen:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"label\": {\n      \"@id\": \"adyen:label\",\n      \"@type\": \"xsd:string\"\n    },\n    \"packageName\": {\n      \"@id\": \"adyen:packageName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"adyen:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"versionCode\": {\n      \"@id\": \"adyen:versionCode\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"versionName\": {\n      \"@id\": \"adyen:versionName\",\n      \"@type\"\
  : \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-android-app-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
