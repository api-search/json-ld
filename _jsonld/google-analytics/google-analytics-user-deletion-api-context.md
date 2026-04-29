---
class_count: 2
classes:
- UserDeletionId
- UserDeletionRequest
context_file: json-ld/google-analytics-user-deletion-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-analytics/refs/heads/main/json-ld/google-analytics-user-deletion-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Google Analytics User Deletion Api from Google Analytics.
layout: jsonld
name: Google Analytics User Deletion Api Context
namespaces:
- prefix: ga
  uri: https://developers.google.com/analytics/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: deletionRequestTime
  type: dateTime
- container: ''
  name: firebaseProjectId
  type: string
- container: ''
  name: id
  type: reference
- container: ''
  name: kind
  type: string
- container: ''
  name: propertyId
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: userId
  type: string
- container: ''
  name: webPropertyId
  type: string
property_count: 8
provider_name: Google Analytics
provider_slug: google-analytics
slug: google-analytics-user-deletion-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"ga\": \"https://developers.google.com/analytics/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"UserDeletionId\": \"ga:UserDeletionId\",\n    \"UserDeletionRequest\": \"ga:UserDeletionRequest\",\n    \"deletionRequestTime\": {\n      \"@id\": \"ga:deletionRequestTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"firebaseProjectId\": {\n      \"@id\": \"ga:firebaseProjectId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"ga:id\",\n      \"@type\": \"@id\"\n    },\n    \"kind\": {\n      \"@id\": \"ga:kind\",\n      \"@type\": \"xsd:string\"\n    },\n    \"propertyId\": {\n      \"@id\": \"ga:propertyId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"ga:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"userId\": {\n      \"@id\": \"ga:userId\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"webPropertyId\": {\n      \"@id\": \"ga:webPropertyId\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-analytics/refs/heads/main/json-ld/google-analytics-user-deletion-api-context.jsonld
tags:
- Analytics
- Data
- Google
- Metrics
- Reporting
- Web Analytics
- Machine Learning
- Attribution
- JSON-LD
- Linked Data
- Semantic Web
---
