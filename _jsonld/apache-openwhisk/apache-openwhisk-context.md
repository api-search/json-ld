---
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
