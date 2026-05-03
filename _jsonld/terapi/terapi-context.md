---
api_specs:
- filename: terapi-openapi.yml
  format: yaml
  label: Terapi API
  slug: terapi-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/terapi/refs/heads/main/openapi/terapi-openapi.yml
class_count: 5
classes:
- id
- name
- description
- Organization
- url
context_file: json-ld/terapi-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/terapi/refs/heads/main/json-ld/terapi-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Terapi from Terapi.
layout: jsonld
name: Terapi Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: terapi
  uri: https://terapi.dev/api/v1#
- prefix: owl
  uri: http://www.w3.org/2002/07/owl#
- prefix: rdfs
  uri: http://www.w3.org/2000/01/rdf-schema#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: Integration
  type: reference
- container: ''
  name: Connection
  type: reference
- container: ''
  name: Sync
  type: reference
- container: ''
  name: Action
  type: reference
- container: ''
  name: AuthToken
  type: reference
- container: ''
  name: provider
  type: string
- container: ''
  name: provider_config_key
  type: string
- container: ''
  name: connection_id
  type: string
- container: ''
  name: connection_count
  type: integer
- container: ''
  name: metadata
  type: '@json'
- container: ''
  name: credentials
  type: '@json'
- container: ''
  name: access_token
  type: string
- container: ''
  name: expires_at
  type: dateTime
- container: ''
  name: sync_name
  type: string
- container: ''
  name: status
  type: '@vocab'
- container: ''
  name: records_count
  type: integer
- container: ''
  name: action_name
  type: string
- container: ''
  name: last_sync_date
  type: dateTime
- container: ''
  name: next_sync_date
  type: dateTime
- container: ''
  name: created_at
  type: dateTime
- container: ''
  name: updated_at
  type: dateTime
property_count: 21
provider_name: Terapi
provider_slug: terapi
slug: terapi-context
source_filename: terapi-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"terapi\": \"https://terapi.dev/api/v1#\",\n    \"owl\": \"http://www.w3.org/2002/07/owl#\",\n    \"rdfs\": \"http://www.w3.org/2000/01/rdf-schema#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Integration\": {\n      \"@id\": \"terapi:Integration\",\n      \"@type\": \"@id\",\n      \"rdfs:comment\": \"An integration provider configuration in Terapi\"\n    },\n    \"Connection\": {\n      \"@id\": \"terapi:Connection\",\n      \"@type\": \"@id\",\n      \"rdfs:comment\": \"An authenticated end-user connection to a third-party service\"\n    },\n    \"Sync\": {\n      \"@id\": \"terapi:Sync\",\n      \"@type\": \"@id\",\n      \"rdfs:comment\": \"A data synchronization job in Terapi\"\n    },\n    \"Action\": {\n      \"@id\": \"terapi:Action\",\n      \"@type\": \"@id\",\n      \"rdfs:comment\": \"A write action triggered on a connected third-party service\"\n  \
  \  },\n    \"AuthToken\": {\n      \"@id\": \"terapi:AuthToken\",\n      \"@type\": \"@id\",\n      \"rdfs:comment\": \"An authentication token for a Terapi connection\"\n    },\n\n    \"id\": \"@id\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"provider\": {\n      \"@id\": \"terapi:provider\",\n      \"@type\": \"xsd:string\"\n    },\n    \"provider_config_key\": {\n      \"@id\": \"terapi:providerConfigKey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"connection_id\": {\n      \"@id\": \"terapi:connectionId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"connection_count\": {\n      \"@id\": \"terapi:connectionCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"metadata\": {\n      \"@id\": \"terapi:metadata\",\n      \"@type\": \"@json\"\n    },\n    \"credentials\": {\n      \"@id\": \"terapi:credentials\",\n      \"@type\": \"@json\"\n    },\n    \"access_token\": {\n      \"@id\": \"terapi:accessToken\",\n      \"@type\": \"\
  xsd:string\"\n    },\n    \"expires_at\": {\n      \"@id\": \"terapi:expiresAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"sync_name\": {\n      \"@id\": \"terapi:syncName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"schema:status\",\n      \"@type\": \"@vocab\",\n      \"@context\": {\n        \"running\": \"terapi:Running\",\n        \"success\": \"terapi:Success\",\n        \"error\": \"terapi:Error\",\n        \"paused\": \"terapi:Paused\"\n      }\n    },\n    \"records_count\": {\n      \"@id\": \"terapi:recordsCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"action_name\": {\n      \"@id\": \"terapi:actionName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"last_sync_date\": {\n      \"@id\": \"terapi:lastSyncDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"next_sync_date\": {\n      \"@id\": \"terapi:nextSyncDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"created_at\": {\n      \"@id\": \"schema:dateCreated\"\
  ,\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updated_at\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"Organization\": \"schema:Organization\",\n    \"url\": \"schema:url\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/terapi/refs/heads/main/json-ld/terapi-context.jsonld
tags:
- Authentication
- Connectors
- Embedded iPaaS
- Integration
- Native Integrations
- Open Source
- Workflow Automation
- JSON-LD
- Linked Data
- Semantic Web
---
