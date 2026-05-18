---
class_count: 0
classes: []
context_file: json-ld/clearview-ai-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/clearview-ai/refs/heads/main/json-ld/clearview-ai-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Clearview Ai from Clearview AI.
layout: jsonld
name: Clearview Ai Context
namespaces:
- prefix: clearview
  uri: https://www.clearview.ai/ns/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: FaceMatch
  type: ''
- container: ''
  name: Investigation
  type: ''
- container: ''
  name: User
  type: ''
- container: ''
  name: AuditEvent
  type: ''
property_count: 4
provider_name: Clearview AI
provider_slug: clearview-ai
slug: clearview-ai-context
source_filename: clearview-ai-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"clearview\": \"https://www.clearview.ai/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"FaceMatch\": {\n      \"@id\": \"clearview:FaceMatch\",\n      \"@context\": {\n        \"id\": \"clearview:id\",\n        \"probeImage\": \"clearview:probe_image\",\n        \"score\": \"clearview:match_score\",\n        \"sourceUrl\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Investigation\": {\n      \"@id\": \"clearview:Investigation\",\n      \"@context\": {\n        \"id\": \"clearview:id\",\n        \"caseNumber\": \"clearview:case_number\",\n        \"agency\": \"schema:memberOf\",\n        \"investigator\": \"clearview:investigator\",\n   \
  \     \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"User\": {\n      \"@id\": \"clearview:User\",\n      \"@context\": {\n        \"id\": \"clearview:id\",\n        \"name\": \"schema:name\",\n        \"agency\": \"schema:memberOf\",\n        \"role\": \"clearview:role\"\n      }\n    },\n\n    \"AuditEvent\": {\n      \"@id\": \"clearview:AuditEvent\",\n      \"@context\": {\n        \"id\": \"clearview:id\",\n        \"actor\": \"clearview:actor\",\n        \"action\": \"clearview:action\",\n        \"timestamp\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/clearview-ai/refs/heads/main/json-ld/clearview-ai-context.jsonld
tags:
- Biometrics
- Facial Recognition
- Identity
- Investigations
- Law Enforcement
- Surveillance
- JSON-LD
- Linked Data
- Semantic Web
---
