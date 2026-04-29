---
api_specs:
- filename: albato-automations-openapi.yaml
  format: yaml
  label: Albato Automations API
  slug: automations-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/albato/refs/heads/main/openapi/albato-automations-openapi.yaml
- filename: albato-embedded-openapi.yaml
  format: yaml
  label: Albato Embedded API
  slug: embedded-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/albato/refs/heads/main/openapi/albato-embedded-openapi.yaml
class_count: 0
classes: []
context_file: json-ld/albato-albato-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/albato/refs/heads/main/json-ld/albato-albato-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Albato Albato from Albato.
layout: jsonld
name: Albato Albato Context
namespaces:
- prefix: albato
  uri: https://albato.com/schema/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: Automation
  type: ''
- container: ''
  name: id
  type: string
- container: ''
  name: name
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: trigger_count
  type: integer
- container: ''
  name: success_count
  type: integer
- container: ''
  name: error_count
  type: integer
- container: ''
  name: created_at
  type: dateTime
- container: ''
  name: updated_at
  type: dateTime
- container: ''
  name: AutomationStep
  type: ''
- container: ''
  name: app
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: event
  type: string
- container: ''
  name: config
  type: string
- container: ''
  name: Execution
  type: ''
- container: ''
  name: automation_id
  type: string
- container: ''
  name: started_at
  type: dateTime
- container: ''
  name: finished_at
  type: dateTime
- container: ''
  name: error_message
  type: string
- container: ''
  name: steps_completed
  type: integer
- container: ''
  name: Team
  type: ''
- container: ''
  name: external_id
  type: string
- container: ''
  name: plan
  type: string
- container: ''
  name: active_automations
  type: integer
- container: ''
  name: transaction_count
  type: integer
- container: ''
  name: User
  type: ''
- container: ''
  name: email
  type: string
- container: ''
  name: role
  type: string
- container: ''
  name: team_id
  type: string
- container: ''
  name: Connector
  type: ''
- container: ''
  name: category
  type: string
- container: ''
  name: triggers_count
  type: integer
- container: ''
  name: actions_count
  type: integer
- container: ''
  name: icon_url
  type: anyURI
- container: ''
  name: Template
  type: ''
property_count: 36
provider_name: Albato
provider_slug: albato
slug: albato-albato-context
source_json: "{\n  \"@context\": {\n    \"albato\": \"https://albato.com/schema/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Automation\": {\n      \"@id\": \"albato:Automation\"\n    },\n    \"id\": {\n      \"@id\": \"albato:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"albato:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"albato:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"albato:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"trigger_count\": {\n      \"@id\": \"albato:trigger_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"success_count\": {\n      \"@id\": \"albato:success_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"error_count\": {\n      \"@id\": \"albato:error_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"created_at\": {\n      \"@id\": \"albato:created_at\",\n      \"@type\": \"xsd:dateTime\"\
  \n    },\n    \"updated_at\": {\n      \"@id\": \"albato:updated_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"AutomationStep\": {\n      \"@id\": \"albato:AutomationStep\"\n    },\n    \"app\": {\n      \"@id\": \"albato:app\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"albato:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"event\": {\n      \"@id\": \"albato:event\",\n      \"@type\": \"xsd:string\"\n    },\n    \"config\": {\n      \"@id\": \"albato:config\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Execution\": {\n      \"@id\": \"albato:Execution\"\n    },\n    \"automation_id\": {\n      \"@id\": \"albato:automation_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"started_at\": {\n      \"@id\": \"albato:started_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"finished_at\": {\n      \"@id\": \"albato:finished_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"error_message\": {\n      \"@id\": \"albato:error_message\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"steps_completed\": {\n      \"@id\": \"albato:steps_completed\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"Team\": {\n      \"@id\": \"albato:Team\"\n    },\n    \"external_id\": {\n      \"@id\": \"albato:external_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"plan\": {\n      \"@id\": \"albato:plan\",\n      \"@type\": \"xsd:string\"\n    },\n    \"active_automations\": {\n      \"@id\": \"albato:active_automations\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"transaction_count\": {\n      \"@id\": \"albato:transaction_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"User\": {\n      \"@id\": \"albato:User\"\n    },\n    \"email\": {\n      \"@id\": \"albato:email\",\n      \"@type\": \"xsd:string\"\n    },\n    \"role\": {\n      \"@id\": \"albato:role\",\n      \"@type\": \"xsd:string\"\n    },\n    \"team_id\": {\n      \"@id\": \"albato:team_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Connector\"\
  : {\n      \"@id\": \"albato:Connector\"\n    },\n    \"category\": {\n      \"@id\": \"albato:category\",\n      \"@type\": \"xsd:string\"\n    },\n    \"triggers_count\": {\n      \"@id\": \"albato:triggers_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"actions_count\": {\n      \"@id\": \"albato:actions_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"icon_url\": {\n      \"@id\": \"albato:icon_url\",\n      \"@type\": \"xsd:anyURI\"\n    },\n    \"Template\": {\n      \"@id\": \"albato:Template\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/albato/refs/heads/main/json-ld/albato-albato-context.jsonld
tags:
- No-Code Automation
- Workflow Automation
- Embedded iPaaS
- App Integration
- Integrations
- Webhooks
- White-Label
- JSON-LD
- Linked Data
- Semantic Web
---
