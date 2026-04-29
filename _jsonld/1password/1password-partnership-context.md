---
api_specs:
- filename: 1password-connect-openapi.yml
  format: yaml
  label: 1Password Connect Server API
  slug: 1password-connect-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/1password/refs/heads/main/openapi/1password-connect-openapi.yml
- filename: 1password-events-openapi.yml
  format: yaml
  label: 1Password Events API
  slug: 1password-events-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/1password/refs/heads/main/openapi/1password-events-openapi.yml
- filename: 1password-partnership-openapi.yml
  format: yaml
  label: 1Password Partnership API
  slug: 1password-partnership-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/1password/refs/heads/main/openapi/1password-partnership-openapi.yml
class_count: 4
classes:
- Account
- CreateAccountRequest
- UpdateAccountRequest
- createdAt
context_file: json-ld/1password-partnership-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/1password/refs/heads/main/json-ld/1password-partnership-context.jsonld
description: JSON-LD context defining the semantic vocabulary for 1Password Partnership from 1Password.
layout: jsonld
name: 1Password Partnership Context
namespaces:
- prefix: onepassword
  uri: https://1password.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: accountType
  type: string
- container: ''
  name: accountUid
  type: string
- container: ''
  name: activationToken
  type: string
- container: ''
  name: domain
  type: string
- container: ''
  name: endsAt
  type: dateTime
- container: ''
  name: status
  type: string
property_count: 6
provider_name: 1Password
provider_slug: 1password
slug: 1password-partnership-context
source_filename: 1password-partnership-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"onepassword\": \"https://1password.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Account\": \"onepassword:Account\",\n    \"CreateAccountRequest\": \"onepassword:CreateAccountRequest\",\n    \"UpdateAccountRequest\": \"onepassword:UpdateAccountRequest\",\n    \"accountType\": {\n      \"@id\": \"onepassword:account_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accountUid\": {\n      \"@id\": \"onepassword:account_uid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"activationToken\": {\n      \"@id\": \"onepassword:activation_token\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdAt\": \"schema:dateCreated\",\n    \"domain\": {\n      \"@id\": \"onepassword:domain\",\n      \"@type\": \"xsd:string\"\n    },\n    \"endsAt\": {\n      \"@id\": \"onepassword:ends_at\",\n      \"@type\":\
  \ \"xsd:dateTime\"\n    },\n    \"status\": {\n      \"@id\": \"onepassword:status\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/1password/refs/heads/main/json-ld/1password-partnership-context.jsonld
tags:
- Password Manager
- Passwords
- Security
- Secrets
- JSON-LD
- Linked Data
- Semantic Web
---
