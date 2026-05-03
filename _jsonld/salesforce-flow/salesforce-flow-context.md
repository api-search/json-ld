---
api_specs:
- filename: salesforce-flow-rest-api-openapi.yml
  format: yaml
  label: Salesforce Flow REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/salesforce-flow/refs/heads/main/openapi/salesforce-flow-rest-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/salesforce-flow-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/salesforce-flow/refs/heads/main/json-ld/salesforce-flow-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Salesforce Flow from Salesforce Flow.
layout: jsonld
name: Salesforce Flow Context
namespaces:
- prefix: sf
  uri: https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: Id
  type: string
- container: ''
  name: ApiName
  type: string
- container: ''
  name: Label
  type: string
- container: ''
  name: Description
  type: string
- container: ''
  name: ProcessType
  type: string
- container: ''
  name: Status
  type: string
- container: ''
  name: VersionNumber
  type: integer
- container: ''
  name: RunInMode
  type: string
- container: ''
  name: CreatedDate
  type: dateTime
- container: ''
  name: LastModifiedDate
  type: dateTime
- container: ''
  name: CreatedById
  type: string
- container: ''
  name: Flow
  type: reference
- container: ''
  name: FlowInterview
  type: reference
- container: ''
  name: HasFinished
  type: boolean
- container: ''
  name: CurrentElement
  type: string
- container: ''
  name: GuidedFlowName
  type: string
- container: list
  name: inputs
  type: reference
- container: list
  name: outputs
  type: reference
- container: ''
  name: SoftwareApplication
  type: ''
- container: ''
  name: provider
  type: reference
- container: ''
  name: Organization
  type: ''
- container: ''
  name: name
  type: ''
- container: ''
  name: url
  type: reference
property_count: 23
provider_name: Salesforce Flow
provider_slug: salesforce-flow
slug: salesforce-flow-context
source_filename: salesforce-flow-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"sf\": \"https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Id\": {\n      \"@id\": \"sf:Id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ApiName\": {\n      \"@id\": \"sf:ApiName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Label\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ProcessType\": {\n      \"@id\": \"sf:ProcessType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Status\": {\n      \"@id\": \"schema:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"VersionNumber\": {\n      \"@id\": \"sf:VersionNumber\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"RunInMode\": {\n      \"@id\": \"sf:RunInMode\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"CreatedDate\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"LastModifiedDate\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"CreatedById\": {\n      \"@id\": \"sf:CreatedById\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Flow\": {\n      \"@id\": \"sf:Flow\",\n      \"@type\": \"@id\"\n    },\n    \"FlowInterview\": {\n      \"@id\": \"sf:FlowInterview\",\n      \"@type\": \"@id\"\n    },\n    \"HasFinished\": {\n      \"@id\": \"sf:HasFinished\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"CurrentElement\": {\n      \"@id\": \"sf:CurrentElement\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GuidedFlowName\": {\n      \"@id\": \"sf:GuidedFlowName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"inputs\": {\n      \"@id\": \"sf:inputs\",\n      \"@type\": \"@id\",\n      \"@container\": \"@list\"\n    },\n    \"outputs\": {\n      \"@id\": \"sf:outputs\",\n    \
  \  \"@type\": \"@id\",\n      \"@container\": \"@list\"\n    },\n    \"SoftwareApplication\": {\n      \"@id\": \"schema:SoftwareApplication\"\n    },\n    \"provider\": {\n      \"@id\": \"schema:provider\",\n      \"@type\": \"@id\"\n    },\n    \"Organization\": {\n      \"@id\": \"schema:Organization\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\"\n    },\n    \"url\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/salesforce-flow/refs/heads/main/json-ld/salesforce-flow-context.jsonld
tags:
- Automation
- Business Process
- CRM
- Flow
- Process Builder
- Salesforce
- Workflow
- JSON-LD
- Linked Data
- Semantic Web
---
