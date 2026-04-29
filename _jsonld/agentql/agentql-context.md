---
class_count: 5
classes:
- QueryDataRequest
- QueryDataResponse
- CreateSessionRequest
- CreateSessionResponse
- QueryDocumentRequest
context_file: json-ld/agentql-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/agentql/refs/heads/main/json-ld/agentql-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Agentql from AgentQL.
layout: jsonld
name: Agentql Context
namespaces:
- prefix: agql
  uri: https://api.agentql.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: url
  type: reference
- container: ''
  name: query
  type: string
- container: ''
  name: prompt
  type: string
- container: ''
  name: html
  type: string
- container: ''
  name: data
  type: reference
- container: ''
  name: metadata
  type: reference
- container: ''
  name: requestId
  type: string
- container: ''
  name: responseTimeMs
  type: integer
- container: ''
  name: sessionId
  type: string
- container: ''
  name: cdpUrl
  type: reference
- container: ''
  name: expiresAt
  type: dateTime
- container: ''
  name: mode
  type: string
- container: ''
  name: waitFor
  type: integer
- container: ''
  name: browserProfile
  type: string
- container: ''
  name: browserUaPreset
  type: string
- container: ''
  name: inactivityTimeoutSeconds
  type: integer
property_count: 16
provider_name: AgentQL
provider_slug: agentql
slug: agentql-context
source_filename: agentql-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"agql\": \"https://api.agentql.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"QueryDataRequest\": \"agql:QueryDataRequest\",\n    \"QueryDataResponse\": \"agql:QueryDataResponse\",\n    \"CreateSessionRequest\": \"agql:CreateSessionRequest\",\n    \"CreateSessionResponse\": \"agql:CreateSessionResponse\",\n    \"QueryDocumentRequest\": \"agql:QueryDocumentRequest\",\n\n    \"url\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    },\n    \"query\": {\n      \"@id\": \"agql:query\",\n      \"@type\": \"xsd:string\"\n    },\n    \"prompt\": {\n      \"@id\": \"agql:prompt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"html\": {\n      \"@id\": \"agql:html\",\n      \"@type\": \"xsd:string\"\n    },\n    \"data\": {\n      \"@id\": \"agql:data\",\n      \"@type\": \"@id\"\n    },\n    \"\
  metadata\": {\n      \"@id\": \"agql:metadata\",\n      \"@type\": \"@id\"\n    },\n    \"requestId\": {\n      \"@id\": \"dcterms:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"responseTimeMs\": {\n      \"@id\": \"agql:response_time_ms\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"sessionId\": {\n      \"@id\": \"agql:session_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cdpUrl\": {\n      \"@id\": \"agql:cdp_url\",\n      \"@type\": \"@id\"\n    },\n    \"expiresAt\": {\n      \"@id\": \"schema:expires\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"mode\": {\n      \"@id\": \"agql:mode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"waitFor\": {\n      \"@id\": \"agql:wait_for\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"browserProfile\": {\n      \"@id\": \"agql:browser_profile\",\n      \"@type\": \"xsd:string\"\n    },\n    \"browserUaPreset\": {\n      \"@id\": \"agql:browser_ua_preset\",\n      \"@type\": \"xsd:string\"\n    },\n   \
  \ \"inactivityTimeoutSeconds\": {\n      \"@id\": \"agql:inactivity_timeout_seconds\",\n      \"@type\": \"xsd:integer\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/agentql/refs/heads/main/json-ld/agentql-context.jsonld
tags:
- Agents
- Artificial Intelligence
- Web Scraping
- Data Extraction
- Browser Automation
- REST API
- JSON-LD
- Linked Data
- Semantic Web
---
