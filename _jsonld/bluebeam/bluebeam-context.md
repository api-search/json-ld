---
api_specs:
- filename: bluebeam-studio-openapi.yml
  format: yaml
  label: Bluebeam Studio API
  slug: bluebeam-studio-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/bluebeam/refs/heads/main/openapi/bluebeam-studio-openapi.yml
class_count: 0
classes: []
context_file: json-ld/bluebeam-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/bluebeam/refs/heads/main/json-ld/bluebeam-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Bluebeam from bluebeam.
layout: jsonld
name: Bluebeam Context
namespaces:
- prefix: bb
  uri: https://api.bluebeam.com/studio/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: Session
  type: ''
- container: ''
  name: Document
  type: ''
- container: ''
  name: Markup
  type: ''
- container: ''
  name: SessionUser
  type: ''
property_count: 4
provider_name: bluebeam
provider_slug: bluebeam
slug: bluebeam-context
source_filename: bluebeam-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"bb\": \"https://api.bluebeam.com/studio/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Session\": {\n      \"@id\": \"schema:Event\",\n      \"@context\": {\n        \"id\": {\"@id\": \"schema:identifier\"},\n        \"name\": {\"@id\": \"schema:name\"},\n        \"description\": {\"@id\": \"schema:description\"},\n        \"status\": {\"@id\": \"bb:sessionStatus\"},\n        \"inviteUrl\": {\"@id\": \"schema:url\", \"@type\": \"@id\"},\n        \"defaultPermission\": {\"@id\": \"bb:defaultPermission\"},\n        \"allowInvitations\": {\"@id\": \"bb:allowInvitations\", \"@type\": \"xsd:boolean\"},\n        \"restricted\": {\"@id\": \"bb:restricted\", \"@type\": \"xsd:boolean\"},\n        \"createdBy\": {\"@id\": \"schema:organizer\"},\n        \"createdAt\": {\"@id\": \"schema:startDate\", \"@type\": \"xsd:dateTime\"},\n        \"finishedAt\": {\"@id\": \"schema:endDate\"\
  , \"@type\": \"xsd:dateTime\"},\n        \"documentCount\": {\"@id\": \"bb:documentCount\", \"@type\": \"xsd:integer\"},\n        \"userCount\": {\"@id\": \"schema:attendeeCount\", \"@type\": \"xsd:integer\"}\n      }\n    },\n\n    \"Document\": {\n      \"@id\": \"schema:DigitalDocument\",\n      \"@context\": {\n        \"id\": {\"@id\": \"schema:identifier\"},\n        \"sessionId\": {\"@id\": \"bb:sessionId\"},\n        \"name\": {\"@id\": \"schema:name\"},\n        \"pageCount\": {\"@id\": \"schema:numberOfPages\", \"@type\": \"xsd:integer\"},\n        \"fileSize\": {\"@id\": \"schema:contentSize\", \"@type\": \"xsd:integer\"},\n        \"uploadedBy\": {\"@id\": \"schema:author\"},\n        \"uploadedAt\": {\"@id\": \"schema:uploadDate\", \"@type\": \"xsd:dateTime\"},\n        \"markupCount\": {\"@id\": \"bb:markupCount\", \"@type\": \"xsd:integer\"}\n      }\n    },\n\n    \"Markup\": {\n      \"@id\": \"schema:Comment\",\n      \"@context\": {\n        \"id\": {\"@id\": \"schema:identifier\"\
  },\n        \"documentId\": {\"@id\": \"bb:documentId\"},\n        \"pageNumber\": {\"@id\": \"bb:pageNumber\", \"@type\": \"xsd:integer\"},\n        \"markupType\": {\"@id\": \"bb:markupType\"},\n        \"subject\": {\"@id\": \"schema:headline\"},\n        \"comment\": {\"@id\": \"schema:text\"},\n        \"createdBy\": {\"@id\": \"schema:author\"},\n        \"createdAt\": {\"@id\": \"schema:dateCreated\", \"@type\": \"xsd:dateTime\"},\n        \"status\": {\"@id\": \"bb:markupStatus\"}\n      }\n    },\n\n    \"SessionUser\": {\n      \"@id\": \"schema:Person\",\n      \"@context\": {\n        \"id\": {\"@id\": \"schema:identifier\"},\n        \"email\": {\"@id\": \"schema:email\"},\n        \"name\": {\"@id\": \"schema:name\"},\n        \"permission\": {\"@id\": \"bb:sessionPermission\"},\n        \"status\": {\"@id\": \"bb:attendeeStatus\"}\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/bluebeam/refs/heads/main/json-ld/bluebeam-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
