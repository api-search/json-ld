---
api_specs:
- filename: apache-openwhisk-rest-api.yaml
  format: yaml
  label: Apache OpenWhisk REST API
  slug: apache-openwhisk-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/apache-openwhisk/refs/heads/main/openapi/apache-openwhisk-rest-api.yaml
class_count: 18
classes:
- KeyValue
- ActionExec
- Action
- ActionRequest
- ActionLimits
- Trigger
- TriggerRequest
- Rule
- RuleRequest
- Package
- PackageRequest
- EntityRef
- Activation
- ActivationResponse
- ActivationRef
- ActivationSummary
- NamespaceEntities
- NamespaceLimits
context_file: json-ld/apache-openwhisk-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apache-openwhisk/refs/heads/main/json-ld/apache-openwhisk-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apache Openwhisk from Apache OpenWhisk.
layout: jsonld
name: Apache Openwhisk Context
namespaces:
- prefix: ow
  uri: https://openwhisk.apache.org/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: key
  type: string
- container: ''
  name: value
  type: string
- container: ''
  name: kind
  type: string
- container: ''
  name: code
  type: string
- container: ''
  name: image
  type: string
- container: set
  name: components
  type: ''
- container: ''
  name: namespace
  type: schema:name
- container: ''
  name: name
  type: schema:name
- container: ''
  name: version
  type: string
- container: ''
  name: publish
  type: boolean
- container: ''
  name: exec
  type: string
- container: set
  name: annotations
  type: ''
- container: set
  name: parameters
  type: ''
- container: ''
  name: limits
  type: string
- container: ''
  name: updated
  type: integer
- container: ''
  name: timeout
  type: integer
- container: ''
  name: memory
  type: integer
- container: ''
  name: logs
  type: integer
- container: ''
  name: status
  type: string
- container: ''
  name: trigger
  type: string
- container: ''
  name: action
  type: string
- container: set
  name: actions
  type: ''
- container: set
  name: feeds
  type: ''
- container: ''
  name: activationId
  type: string
- container: ''
  name: subject
  type: string
- container: ''
  name: start
  type: integer
- container: ''
  name: end
  type: integer
- container: ''
  name: duration
  type: integer
- container: ''
  name: response
  type: string
- container: ''
  name: statusCode
  type: integer
- container: ''
  name: success
  type: boolean
- container: ''
  name: result
  type: string
- container: set
  name: triggers
  type: ''
- container: set
  name: rules
  type: ''
- container: ''
  name: concurrency
  type: integer
- container: ''
  name: minuteRate
  type: integer
- container: ''
  name: hourRate
  type: integer
property_count: 37
provider_name: Apache OpenWhisk
provider_slug: apache-openwhisk
slug: apache-openwhisk-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"ow\": \"https://openwhisk.apache.org/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"KeyValue\": \"ow:KeyValue\",\n    \"ActionExec\": \"ow:ActionExec\",\n    \"Action\": \"ow:Action\",\n    \"ActionRequest\": \"ow:ActionRequest\",\n    \"ActionLimits\": \"ow:ActionLimits\",\n    \"Trigger\": \"ow:Trigger\",\n    \"TriggerRequest\": \"ow:TriggerRequest\",\n    \"Rule\": \"ow:Rule\",\n    \"RuleRequest\": \"ow:RuleRequest\",\n    \"Package\": \"ow:Package\",\n    \"PackageRequest\": \"ow:PackageRequest\",\n    \"EntityRef\": \"ow:EntityRef\",\n    \"Activation\": \"ow:Activation\",\n    \"ActivationResponse\": \"ow:ActivationResponse\",\n    \"ActivationRef\": \"ow:ActivationRef\",\n    \"ActivationSummary\": \"ow:ActivationSummary\",\n    \"NamespaceEntities\": \"ow:NamespaceEntities\",\n    \"NamespaceLimits\": \"ow:NamespaceLimits\",\n    \"key\": {\n     \
  \ \"@id\": \"ow:key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"ow:value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"kind\": {\n      \"@id\": \"ow:kind\",\n      \"@type\": \"xsd:string\"\n    },\n    \"code\": {\n      \"@id\": \"ow:code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"image\": {\n      \"@id\": \"ow:image\",\n      \"@type\": \"xsd:string\"\n    },\n    \"components\": {\n      \"@id\": \"ow:components\",\n      \"@container\": \"@set\"\n    },\n    \"namespace\": {\n      \"@id\": \"ow:namespace\",\n      \"@type\": \"schema:name\"\n    },\n    \"name\": {\n      \"@id\": \"ow:name\",\n      \"@type\": \"schema:name\"\n    },\n    \"version\": {\n      \"@id\": \"ow:version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"publish\": {\n      \"@id\": \"ow:publish\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"exec\": {\n      \"@id\": \"ow:exec\",\n      \"@type\": \"xsd:string\"\n    },\n    \"annotations\": {\n\
  \      \"@id\": \"ow:annotations\",\n      \"@container\": \"@set\"\n    },\n    \"parameters\": {\n      \"@id\": \"ow:parameters\",\n      \"@container\": \"@set\"\n    },\n    \"limits\": {\n      \"@id\": \"ow:limits\",\n      \"@type\": \"xsd:string\"\n    },\n    \"updated\": {\n      \"@id\": \"ow:updated\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"timeout\": {\n      \"@id\": \"ow:timeout\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"memory\": {\n      \"@id\": \"ow:memory\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"logs\": {\n      \"@id\": \"ow:logs\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"status\": {\n      \"@id\": \"ow:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"trigger\": {\n      \"@id\": \"ow:trigger\",\n      \"@type\": \"xsd:string\"\n    },\n    \"action\": {\n      \"@id\": \"ow:action\",\n      \"@type\": \"xsd:string\"\n    },\n    \"actions\": {\n      \"@id\": \"ow:actions\",\n      \"@container\": \"@set\"\n    },\n\
  \    \"feeds\": {\n      \"@id\": \"ow:feeds\",\n      \"@container\": \"@set\"\n    },\n    \"activationId\": {\n      \"@id\": \"ow:activationId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subject\": {\n      \"@id\": \"ow:subject\",\n      \"@type\": \"xsd:string\"\n    },\n    \"start\": {\n      \"@id\": \"ow:start\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"end\": {\n      \"@id\": \"ow:end\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"duration\": {\n      \"@id\": \"ow:duration\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"response\": {\n      \"@id\": \"ow:response\",\n      \"@type\": \"xsd:string\"\n    },\n    \"statusCode\": {\n      \"@id\": \"ow:statusCode\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"success\": {\n      \"@id\": \"ow:success\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"result\": {\n      \"@id\": \"ow:result\",\n      \"@type\": \"xsd:string\"\n    },\n    \"triggers\": {\n      \"@id\": \"ow:triggers\",\n      \"\
  @container\": \"@set\"\n    },\n    \"rules\": {\n      \"@id\": \"ow:rules\",\n      \"@container\": \"@set\"\n    },\n    \"concurrency\": {\n      \"@id\": \"ow:concurrency\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"minuteRate\": {\n      \"@id\": \"ow:minuteRate\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"hourRate\": {\n      \"@id\": \"ow:hourRate\",\n      \"@type\": \"xsd:integer\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/apache-openwhisk/refs/heads/main/json-ld/apache-openwhisk-context.jsonld
tags:
- Cloud Native
- Event-Driven
- FaaS
- Serverless
- Apache
- Open Source
- Functions
- JSON-LD
- Linked Data
- Semantic Web
---
