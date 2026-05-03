---
api_specs:
- filename: signnow-openapi.yml
  format: yaml
  label: SignNow REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/signnow/refs/heads/main/openapi/signnow-openapi.yml
class_count: 26
classes:
- Document
- Template
- Field
- SigningRequest
- Role
- id
- document_name
- user_id
- page_count
- tags
- roles
- fields
- requests
- fieldinvite_status
- signer_email
- status
- role_id
- signing_order
- required
- label
- type
- x
- y
- width
- height
- page_number
context_file: json-ld/signnow-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/signnow/refs/heads/main/json-ld/signnow-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Signnow from SignNow.
layout: jsonld
name: Signnow Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: signnow
  uri: https://docs.signnow.com/vocab#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: created
  type: dateTime
- container: ''
  name: updated
  type: dateTime
property_count: 2
provider_name: SignNow
provider_slug: signnow
slug: signnow-context
source_filename: signnow-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"signnow\": \"https://docs.signnow.com/vocab#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Document\": \"schema:DigitalDocument\",\n    \"Template\": \"signnow:Template\",\n    \"Field\": \"signnow:Field\",\n    \"SigningRequest\": \"signnow:SigningRequest\",\n    \"Role\": \"signnow:Role\",\n\n    \"id\": \"@id\",\n    \"document_name\": \"schema:name\",\n    \"created\": {\"@id\": \"schema:dateCreated\", \"@type\": \"xsd:dateTime\"},\n    \"updated\": {\"@id\": \"schema:dateModified\", \"@type\": \"xsd:dateTime\"},\n    \"user_id\": \"schema:creator\",\n    \"page_count\": \"schema:numberOfPages\",\n    \"tags\": \"schema:keywords\",\n    \"roles\": \"signnow:hasRole\",\n    \"fields\": \"signnow:hasField\",\n    \"requests\": \"signnow:hasSigningRequest\",\n    \"fieldinvite_status\": \"signnow:inviteStatus\",\n\n    \"signer_email\": \"schema:email\",\n    \"\
  status\": \"schema:status\",\n    \"role_id\": \"signnow:roleReference\",\n    \"signing_order\": \"signnow:signingOrder\",\n    \"required\": \"schema:valueRequired\",\n    \"label\": \"schema:name\",\n    \"type\": \"schema:additionalType\",\n\n    \"x\": \"signnow:positionX\",\n    \"y\": \"signnow:positionY\",\n    \"width\": \"schema:width\",\n    \"height\": \"schema:height\",\n    \"page_number\": \"signnow:pageNumber\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/signnow/refs/heads/main/json-ld/signnow-context.jsonld
tags:
- E-Signature
- Document Management
- Electronic Signature
- Workflow Automation
- JSON-LD
- Linked Data
- Semantic Web
---
