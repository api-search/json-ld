---
api_specs:
- filename: firebase-realtime-database-openapi.yml
  format: yaml
  label: Firebase Realtime Database API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-firebase/refs/heads/main/openapi/firebase-realtime-database-openapi.yml
- filename: firebase-cloud-messaging-openapi.yml
  format: yaml
  label: Firebase Cloud Messaging API (FCM)
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-firebase/refs/heads/main/openapi/firebase-cloud-messaging-openapi.yml
class_count: 0
classes: []
context_file: json-ld/google-firebase-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-firebase/refs/heads/main/json-ld/google-firebase-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Google Firebase from Google Firebase.
layout: jsonld
name: Google Firebase Context
namespaces:
- prefix: firebase
  uri: https://firebase.google.com/ns/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Project
  type: ''
- container: ''
  name: DatabaseNode
  type: ''
- container: ''
  name: CloudMessage
  type: ''
- container: ''
  name: HostingSite
  type: ''
- container: ''
  name: RemoteConfigTemplate
  type: ''
property_count: 5
provider_name: Google Firebase
provider_slug: google-firebase
slug: google-firebase-context
source_filename: google-firebase-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"firebase\": \"https://firebase.google.com/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Project\": {\n      \"@id\": \"firebase:Project\",\n      \"@context\": {\n        \"projectId\": \"firebase:projectId\",\n        \"projectNumber\": \"firebase:projectNumber\",\n        \"displayName\": \"schema:name\",\n        \"state\": \"firebase:state\",\n        \"resources\": \"firebase:resources\"\n      }\n    },\n\n    \"DatabaseNode\": {\n      \"@id\": \"firebase:DatabaseNode\",\n      \"@context\": {\n        \"path\": \"firebase:path\",\n        \"value\": \"firebase:value\",\n        \"priority\": \"firebase:priority\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n    \
  \      \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"CloudMessage\": {\n      \"@id\": \"firebase:CloudMessage\",\n      \"@context\": {\n        \"messageId\": \"firebase:messageId\",\n        \"token\": \"firebase:registrationToken\",\n        \"topic\": \"firebase:topic\",\n        \"condition\": \"firebase:condition\",\n        \"title\": \"schema:headline\",\n        \"body\": \"schema:text\",\n        \"sentAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"HostingSite\": {\n      \"@id\": \"firebase:HostingSite\",\n      \"@context\": {\n        \"siteId\": \"firebase:siteId\",\n        \"defaultUrl\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"appId\": \"firebase:appId\"\n      }\n    },\n\n    \"RemoteConfigTemplate\": {\n      \"@id\": \"firebase:RemoteConfigTemplate\",\n      \"@context\": {\n        \"parameters\": \"firebase:parameters\"\
  ,\n        \"conditions\": \"firebase:conditions\",\n        \"version\": \"schema:version\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-firebase/refs/heads/main/json-ld/google-firebase-context.jsonld
tags:
- Analytics
- Authentication
- Backend as a Service
- Cloud Messaging
- Google Cloud
- Hosting
- Mobile
- Real-Time Database
- JSON-LD
- Linked Data
- Semantic Web
---
