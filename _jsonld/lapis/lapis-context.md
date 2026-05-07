---
class_count: 22
classes:
- LapisDocument
- MetaSection
- TypesSection
- OpsSection
- WebhooksSection
- ErrorsSection
- LimitsSection
- FlowsSection
- Operation
- Webhook
- ErrorDefinition
- TypeDefinition
- EnumDefinition
- ObjectDefinition
- Field
- Flow
- FlowStep
- RateLimit
- Quota
- Plan
- Authentication
- OperationModifier
context_file: json-ld/lapis-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/lapis/refs/heads/main/json-ld/lapis-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Lapis from LAPIS.
layout: jsonld
name: Lapis Context
namespaces:
- prefix: lapis
  uri: https://raw.githubusercontent.com/api-evangelist/lapis/refs/heads/main/json-ld/lapis-context.jsonld#
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: owl
  uri: http://www.w3.org/2002/07/owl#
- prefix: rdfs
  uri: http://www.w3.org/2000/01/rdf-schema#
properties:
- container: ''
  name: lapisVersion
  type: string
- container: ''
  name: api
  type: string
- container: ''
  name: name
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: desc
  type: string
- container: ''
  name: summary
  type: string
- container: ''
  name: base
  type: reference
- container: ''
  name: version
  type: string
- container: ''
  name: format
  type: string
- container: ''
  name: auth
  type: reference
- container: ''
  name: type
  type: string
- container: ''
  name: location
  type: string
- container: ''
  name: tokenUrl
  type: reference
- container: ''
  name: method
  type: string
- container: ''
  name: path
  type: string
- container: ''
  name: code
  type: integer
- container: set
  name: ops
  type: reference
- container: set
  name: webhooks
  type: reference
- container: set
  name: errors
  type: reference
- container: ''
  name: limits
  type: reference
- container: set
  name: flows
  type: reference
- container: ''
  name: types
  type: reference
- container: ''
  name: meta
  type: reference
- container: set
  name: fields
  type: reference
- container: set
  name: inputs
  type: reference
- container: set
  name: outputs
  type: reference
- container: set
  name: payload
  type: reference
- container: set
  name: triggers
  type: string
- container: set
  name: modifiers
  type: reference
- container: list
  name: values
  type: string
- container: ''
  name: kind
  type: string
- container: ''
  name: optional
  type: boolean
- container: ''
  name: default
  type: ''
- container: ''
  name: since
  type: string
- container: ''
  name: deprecated
  type: ''
- container: ''
  name: headerName
  type: string
- container: ''
  name: typeRef
  type: string
- container: set
  name: ops_scope
  type: string
- container: set
  name: headers
  type: string
- container: ''
  name: onExceed
  type: string
- container: ''
  name: maxBody
  type: string
- container: ''
  name: maxUpload
  type: string
- container: ''
  name: maxResponse
  type: string
- container: ''
  name: maxBatch
  type: integer
- container: set
  name: rate
  type: reference
- container: set
  name: quota
  type: reference
- container: set
  name: plans
  type: reference
- container: ''
  name: count
  type: ''
- container: ''
  name: window
  type: string
- container: ''
  name: period
  type: string
- container: ''
  name: scope
  type: string
- container: list
  name: chain
  type: reference
- container: set
  name: conditions
  type: reference
- container: ''
  name: operation
  type: string
- container: ''
  name: outputField
  type: string
- container: ''
  name: argument
  type: string
- container: ''
  name: loop
  type: boolean
- container: set
  name: branches
  type: reference
- container: ''
  name: wait
  type: string
- container: ''
  name: target
  type: string
- container: ''
  name: text
  type: string
- container: ''
  name: note
  type: string
property_count: 62
provider_name: LAPIS
provider_slug: lapis
slug: lapis-context
source_filename: lapis-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"lapis\": \"https://raw.githubusercontent.com/api-evangelist/lapis/refs/heads/main/json-ld/lapis-context.jsonld#\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"owl\": \"http://www.w3.org/2002/07/owl#\",\n    \"rdfs\": \"http://www.w3.org/2000/01/rdf-schema#\",\n\n    \"LapisDocument\": \"lapis:LapisDocument\",\n    \"MetaSection\": \"lapis:MetaSection\",\n    \"TypesSection\": \"lapis:TypesSection\",\n    \"OpsSection\": \"lapis:OpsSection\",\n    \"WebhooksSection\": \"lapis:WebhooksSection\",\n    \"ErrorsSection\": \"lapis:ErrorsSection\",\n    \"LimitsSection\": \"lapis:LimitsSection\",\n    \"FlowsSection\": \"lapis:FlowsSection\",\n    \"Operation\": \"lapis:Operation\",\n    \"Webhook\": \"lapis:Webhook\",\n    \"ErrorDefinition\": \"lapis:ErrorDefinition\",\n    \"TypeDefinition\": \"lapis:TypeDefinition\",\n \
  \   \"EnumDefinition\": \"lapis:EnumDefinition\",\n    \"ObjectDefinition\": \"lapis:ObjectDefinition\",\n    \"Field\": \"lapis:Field\",\n    \"Flow\": \"lapis:Flow\",\n    \"FlowStep\": \"lapis:FlowStep\",\n    \"RateLimit\": \"lapis:RateLimit\",\n    \"Quota\": \"lapis:Quota\",\n    \"Plan\": \"lapis:Plan\",\n    \"Authentication\": \"lapis:Authentication\",\n    \"OperationModifier\": \"lapis:OperationModifier\",\n\n    \"lapisVersion\": {\n      \"@id\": \"schema:version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"api\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"desc\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"summary\": {\n      \"@id\": \"schema:abstract\",\n      \"@type\": \"xsd:string\"\n\
  \    },\n    \"base\": {\n      \"@id\": \"lapis:base\",\n      \"@type\": \"@id\"\n    },\n    \"version\": {\n      \"@id\": \"schema:version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"format\": {\n      \"@id\": \"lapis:format\",\n      \"@type\": \"xsd:string\"\n    },\n    \"auth\": {\n      \"@id\": \"lapis:auth\",\n      \"@type\": \"@id\"\n    },\n    \"type\": {\n      \"@id\": \"lapis:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"location\": {\n      \"@id\": \"lapis:location\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tokenUrl\": {\n      \"@id\": \"lapis:tokenUrl\",\n      \"@type\": \"@id\"\n    },\n    \"method\": {\n      \"@id\": \"lapis:httpMethod\",\n      \"@type\": \"xsd:string\"\n    },\n    \"path\": {\n      \"@id\": \"lapis:path\",\n      \"@type\": \"xsd:string\"\n    },\n    \"code\": {\n      \"@id\": \"schema:statusCode\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"ops\": {\n      \"@id\": \"lapis:operations\",\n      \"@container\"\
  : \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"webhooks\": {\n      \"@id\": \"lapis:webhooks\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"errors\": {\n      \"@id\": \"lapis:errors\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"limits\": {\n      \"@id\": \"lapis:limits\",\n      \"@type\": \"@id\"\n    },\n    \"flows\": {\n      \"@id\": \"lapis:flows\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"types\": {\n      \"@id\": \"lapis:types\",\n      \"@type\": \"@id\"\n    },\n    \"meta\": {\n      \"@id\": \"lapis:meta\",\n      \"@type\": \"@id\"\n    },\n    \"fields\": {\n      \"@id\": \"lapis:fields\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"inputs\": {\n      \"@id\": \"lapis:inputs\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"outputs\": {\n      \"@id\": \"lapis:outputs\",\n      \"@container\": \"@set\",\n      \"\
  @type\": \"@id\"\n    },\n    \"payload\": {\n      \"@id\": \"lapis:payload\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"triggers\": {\n      \"@id\": \"lapis:triggers\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"modifiers\": {\n      \"@id\": \"lapis:modifiers\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"values\": {\n      \"@id\": \"lapis:enumValues\",\n      \"@container\": \"@list\",\n      \"@type\": \"xsd:string\"\n    },\n    \"kind\": {\n      \"@id\": \"lapis:kind\",\n      \"@type\": \"xsd:string\"\n    },\n    \"optional\": {\n      \"@id\": \"lapis:optional\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"default\": {\n      \"@id\": \"lapis:default\"\n    },\n    \"since\": {\n      \"@id\": \"lapis:since\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deprecated\": {\n      \"@id\": \"lapis:deprecated\"\n    },\n    \"headerName\": {\n      \"@id\": \"lapis:headerName\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"typeRef\": {\n      \"@id\": \"lapis:typeRef\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ops_scope\": {\n      \"@id\": \"lapis:scopedOps\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"headers\": {\n      \"@id\": \"lapis:headers\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"onExceed\": {\n      \"@id\": \"lapis:onExceed\",\n      \"@type\": \"xsd:string\"\n    },\n    \"maxBody\": {\n      \"@id\": \"lapis:maxBody\",\n      \"@type\": \"xsd:string\"\n    },\n    \"maxUpload\": {\n      \"@id\": \"lapis:maxUpload\",\n      \"@type\": \"xsd:string\"\n    },\n    \"maxResponse\": {\n      \"@id\": \"lapis:maxResponse\",\n      \"@type\": \"xsd:string\"\n    },\n    \"maxBatch\": {\n      \"@id\": \"lapis:maxBatch\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"rate\": {\n      \"@id\": \"lapis:rate\",\n      \"@container\": \"@set\",\n      \"@type\": \"\
  @id\"\n    },\n    \"quota\": {\n      \"@id\": \"lapis:quota\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"plans\": {\n      \"@id\": \"lapis:plans\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"count\": {\n      \"@id\": \"lapis:count\"\n    },\n    \"window\": {\n      \"@id\": \"lapis:window\",\n      \"@type\": \"xsd:string\"\n    },\n    \"period\": {\n      \"@id\": \"lapis:period\",\n      \"@type\": \"xsd:string\"\n    },\n    \"scope\": {\n      \"@id\": \"lapis:scope\",\n      \"@type\": \"xsd:string\"\n    },\n    \"chain\": {\n      \"@id\": \"lapis:chain\",\n      \"@container\": \"@list\",\n      \"@type\": \"@id\"\n    },\n    \"conditions\": {\n      \"@id\": \"lapis:conditions\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"operation\": {\n      \"@id\": \"lapis:operation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"outputField\": {\n      \"@id\": \"lapis:outputField\",\n\
  \      \"@type\": \"xsd:string\"\n    },\n    \"argument\": {\n      \"@id\": \"lapis:argument\",\n      \"@type\": \"xsd:string\"\n    },\n    \"loop\": {\n      \"@id\": \"lapis:loop\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"branches\": {\n      \"@id\": \"lapis:branches\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"wait\": {\n      \"@id\": \"lapis:wait\",\n      \"@type\": \"xsd:string\"\n    },\n    \"target\": {\n      \"@id\": \"lapis:target\",\n      \"@type\": \"xsd:string\"\n    },\n    \"text\": {\n      \"@id\": \"schema:text\",\n      \"@type\": \"xsd:string\"\n    },\n    \"note\": {\n      \"@id\": \"lapis:note\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/lapis/refs/heads/main/json-ld/lapis-context.jsonld
tags:
- API
- Specification
- LLM
- AI Agents
- OpenAPI
- Token Optimization
- Standards
- JSON-LD
- Linked Data
- Semantic Web
---
