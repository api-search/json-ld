---
api_specs:
- filename: veeva-vault-openapi.yml
  format: yaml
  label: Veeva Vault Platform API
  slug: veeva-vault-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/veeva/refs/heads/main/openapi/veeva-vault-openapi.yml
- filename: veeva-vault-openapi.yml
  format: yaml
  label: Veeva Vault Query Language (VQL) API
  slug: veeva-vault-query-language
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/veeva/refs/heads/main/openapi/veeva-vault-openapi.yml
class_count: 25
classes:
- Document
- ObjectRecord
- User
- Vault
- id
- name__v
- description__v
- type__v
- subtype__v
- classification__v
- lifecycle__v
- status__v
- document_number__v
- major_version_number__v
- minor_version_number__v
- size__v
- format__v
- external_id__v
- user_name__v
- user_first_name__v
- user_last_name__v
- user_email__v
- is_active__v
- sessionId
- vaultId
context_file: json-ld/veeva-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/veeva/refs/heads/main/json-ld/veeva-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Veeva from veeva.
layout: jsonld
name: Veeva Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: veeva
  uri: https://developer.veevavault.com/vocab/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: created_by__v
  type: reference
- container: ''
  name: last_modified_by__v
  type: reference
- container: ''
  name: created_date__v
  type: dateTime
- container: ''
  name: last_modified_date__v
  type: dateTime
- container: ''
  name: owner__v
  type: reference
- container: ''
  name: effective_date__v
  type: date
- container: ''
  name: expiration_date__v
  type: date
property_count: 7
provider_name: veeva
provider_slug: veeva
slug: veeva-context
source_filename: veeva-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"veeva\": \"https://developer.veevavault.com/vocab/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Document\": \"schema:DigitalDocument\",\n    \"ObjectRecord\": \"schema:Thing\",\n    \"User\": \"schema:Person\",\n    \"Vault\": \"schema:SoftwareApplication\",\n\n    \"id\": \"@id\",\n    \"name__v\": \"schema:name\",\n    \"description__v\": \"schema:description\",\n    \"type__v\": \"schema:additionalType\",\n    \"subtype__v\": \"veeva:documentSubtype\",\n    \"classification__v\": \"schema:category\",\n    \"lifecycle__v\": \"veeva:lifecycle\",\n    \"status__v\": \"schema:status\",\n    \"document_number__v\": \"schema:identifier\",\n    \"major_version_number__v\": \"schema:version\",\n    \"minor_version_number__v\": \"veeva:minorVersion\",\n    \"created_by__v\": {\n      \"@id\": \"schema:author\",\n      \"@type\": \"@id\"\n    },\n    \"last_modified_by__v\"\
  : {\n      \"@id\": \"schema:editor\",\n      \"@type\": \"@id\"\n    },\n    \"created_date__v\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"last_modified_date__v\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"size__v\": \"schema:contentSize\",\n    \"format__v\": \"schema:encodingFormat\",\n    \"external_id__v\": \"schema:sameAs\",\n    \"owner__v\": {\n      \"@id\": \"schema:accountablePerson\",\n      \"@type\": \"@id\"\n    },\n    \"effective_date__v\": {\n      \"@id\": \"schema:startDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"expiration_date__v\": {\n      \"@id\": \"schema:expires\",\n      \"@type\": \"xsd:date\"\n    },\n\n    \"user_name__v\": \"schema:identifier\",\n    \"user_first_name__v\": \"schema:givenName\",\n    \"user_last_name__v\": \"schema:familyName\",\n    \"user_email__v\": \"schema:email\",\n    \"is_active__v\": \"schema:isAccessibleForFree\",\n\n\
  \    \"sessionId\": \"veeva:sessionId\",\n    \"vaultId\": \"veeva:vaultId\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/veeva/refs/heads/main/json-ld/veeva-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
