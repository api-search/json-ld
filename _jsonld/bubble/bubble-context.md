---
api_specs:
- filename: bubble-data-api-openapi.yml
  format: yaml
  label: Bubble Data API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/bubble/refs/heads/main/openapi/bubble-data-api-openapi.yml
- filename: bubble-workflow-api-openapi.yml
  format: yaml
  label: Bubble Workflow API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/bubble/refs/heads/main/openapi/bubble-workflow-api-openapi.yml
- filename: bubble-plugin-api-openapi.yml
  format: yaml
  label: Bubble Plugin API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/bubble/refs/heads/main/openapi/bubble-plugin-api-openapi.yml
class_count: 24
classes:
- name
- description
- url
- Application
- DataType
- Thing
- Workflow
- Plugin
- PluginAction
- PluginElement
- constraintType
- value
- key
- cursor
- limit
- remaining
- count
- workflowName
- parameters
- response
- workloadUnits
- plan
- tier
- rateLimit
context_file: json-ld/bubble-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/bubble/refs/heads/main/json-ld/bubble-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Bubble from Bubble.
layout: jsonld
name: Bubble Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: bubble
  uri: https://bubble.io/ns/
properties:
- container: ''
  name: id
  type: reference
- container: ''
  name: createdDate
  type: schema:DateTime
- container: ''
  name: modifiedDate
  type: schema:DateTime
- container: ''
  name: createdBy
  type: reference
- container: list
  name: fields
  type: ''
- container: list
  name: constraints
  type: ''
- container: list
  name: results
  type: ''
property_count: 7
provider_name: Bubble
provider_slug: bubble
slug: bubble-context
source_filename: bubble-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"bubble\": \"https://bubble.io/ns/\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n\n    \"Application\": \"schema:SoftwareApplication\",\n    \"DataType\": \"bubble:DataType\",\n    \"Thing\": \"bubble:Thing\",\n    \"Workflow\": \"bubble:Workflow\",\n    \"Plugin\": \"bubble:Plugin\",\n    \"PluginAction\": \"bubble:PluginAction\",\n    \"PluginElement\": \"bubble:PluginElement\",\n\n    \"id\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"@id\"\n    },\n    \"createdDate\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"schema:DateTime\"\n    },\n    \"modifiedDate\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"schema:DateTime\"\n    },\n    \"createdBy\": {\n      \"@id\": \"schema:author\",\n      \"@type\": \"@id\"\n    },\n\n    \"fields\": {\n      \"@id\": \"bubble:field\"\
  ,\n      \"@container\": \"@list\"\n    },\n    \"constraints\": {\n      \"@id\": \"bubble:constraint\",\n      \"@container\": \"@list\"\n    },\n    \"constraintType\": \"bubble:constraintType\",\n    \"value\": \"schema:value\",\n    \"key\": \"bubble:fieldKey\",\n\n    \"cursor\": \"bubble:cursor\",\n    \"limit\": \"bubble:limit\",\n    \"remaining\": \"bubble:remaining\",\n    \"count\": \"schema:numberOfItems\",\n    \"results\": {\n      \"@id\": \"bubble:result\",\n      \"@container\": \"@list\"\n    },\n\n    \"workflowName\": \"bubble:workflowName\",\n    \"parameters\": \"bubble:parameters\",\n    \"response\": \"bubble:response\",\n\n    \"workloadUnits\": \"bubble:workloadUnits\",\n    \"plan\": \"bubble:plan\",\n    \"tier\": \"bubble:tier\",\n    \"rateLimit\": \"bubble:rateLimit\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/bubble/refs/heads/main/json-ld/bubble-context.jsonld
tags:
- No-Code
- Application Platform
- Database
- Workflow Automation
- Plugins
- JSON-LD
- Linked Data
- Semantic Web
---
