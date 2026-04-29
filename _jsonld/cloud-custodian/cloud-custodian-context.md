---
class_count: 0
classes: []
context_file: json-ld/cloud-custodian-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/cloud-custodian/refs/heads/main/json-ld/cloud-custodian-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Cloud Custodian from Cloud Custodian.
layout: jsonld
name: Cloud Custodian Context
namespaces:
- prefix: c7n
  uri: https://cloudcustodian.io/vocab/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Policy
  type: ''
- container: ''
  name: PolicyMode
  type: ''
- container: ''
  name: Filter
  type: ''
- container: ''
  name: Action
  type: ''
- container: ''
  name: NotifyAction
  type: ''
- container: ''
  name: PolicyNotification
  type: ''
- container: ''
  name: CloudResource
  type: ''
- container: ''
  name: MailerConfig
  type: ''
property_count: 8
provider_name: Cloud Custodian
provider_slug: cloud-custodian
slug: cloud-custodian-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"c7n\": \"https://cloudcustodian.io/vocab/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Policy\": {\n      \"@id\": \"c7n:Policy\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"dcterms:identifier\"\n        },\n        \"description\": {\n          \"@id\": \"dcterms:description\"\n        },\n        \"resource\": {\n          \"@id\": \"c7n:resourceType\"\n        },\n        \"filters\": {\n          \"@id\": \"c7n:hasFilter\",\n          \"@container\": \"@set\"\n        },\n        \"actions\": {\n          \"@id\": \"c7n:hasAction\",\n          \"@container\": \"@set\"\n        },\n        \"mode\": {\n          \"@id\": \"c7n:executionMode\"\n        },\n        \"tags\": {\n          \"@id\": \"schema:keywords\",\n          \"@container\": \"@set\"\n        },\n        \"metadata\": {\n\
  \          \"@id\": \"c7n:metadata\"\n        }\n      }\n    },\n\n    \"PolicyMode\": {\n      \"@id\": \"c7n:PolicyMode\",\n      \"@context\": {\n        \"type\": {\n          \"@id\": \"c7n:modeType\"\n        },\n        \"role\": {\n          \"@id\": \"c7n:iamRole\",\n          \"@type\": \"@id\"\n        },\n        \"schedule\": {\n          \"@id\": \"c7n:schedule\"\n        },\n        \"timeout\": {\n          \"@id\": \"c7n:timeout\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"memory\": {\n          \"@id\": \"c7n:memoryMb\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"Filter\": {\n      \"@id\": \"c7n:Filter\",\n      \"@context\": {\n        \"type\": {\n          \"@id\": \"c7n:filterType\"\n        },\n        \"key\": {\n          \"@id\": \"c7n:jmesPathKey\"\n        },\n        \"op\": {\n          \"@id\": \"c7n:operator\"\n        },\n        \"value\": {\n          \"@id\": \"c7n:filterValue\"\n        },\n     \
  \   \"value_type\": {\n          \"@id\": \"c7n:valueTransform\"\n        }\n      }\n    },\n\n    \"Action\": {\n      \"@id\": \"c7n:Action\",\n      \"@context\": {\n        \"type\": {\n          \"@id\": \"c7n:actionType\"\n        }\n      }\n    },\n\n    \"NotifyAction\": {\n      \"@id\": \"c7n:NotifyAction\",\n      \"@context\": {\n        \"type\": {\n          \"@id\": \"c7n:actionType\"\n        },\n        \"to\": {\n          \"@id\": \"schema:recipient\",\n          \"@container\": \"@set\"\n        },\n        \"subject\": {\n          \"@id\": \"schema:name\"\n        },\n        \"template\": {\n          \"@id\": \"c7n:messageTemplate\"\n        },\n        \"transport\": {\n          \"@id\": \"c7n:notifyTransport\"\n        },\n        \"violation_desc\": {\n          \"@id\": \"c7n:violationDescription\"\n        },\n        \"action_desc\": {\n          \"@id\": \"c7n:actionDescription\"\n        }\n      }\n    },\n\n    \"PolicyNotification\": {\n      \"@id\"\
  : \"c7n:PolicyNotification\",\n      \"@context\": {\n        \"account_id\": {\n          \"@id\": \"c7n:awsAccountId\"\n        },\n        \"account\": {\n          \"@id\": \"schema:name\"\n        },\n        \"region\": {\n          \"@id\": \"c7n:awsRegion\"\n        },\n        \"execution_id\": {\n          \"@id\": \"dcterms:identifier\"\n        },\n        \"execution_start\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"policy\": {\n          \"@id\": \"c7n:triggeredPolicy\"\n        },\n        \"resources\": {\n          \"@id\": \"c7n:matchedResources\",\n          \"@container\": \"@set\"\n        },\n        \"event\": {\n          \"@id\": \"c7n:triggeringEvent\"\n        }\n      }\n    },\n\n    \"CloudResource\": {\n      \"@id\": \"c7n:CloudResource\",\n      \"@context\": {\n        \"account_id\": {\n          \"@id\": \"c7n:awsAccountId\"\n        },\n        \"region\": {\n          \"@id\": \"c7n:awsRegion\"\
  \n        },\n        \"Tags\": {\n          \"@id\": \"schema:keywords\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"MailerConfig\": {\n      \"@id\": \"c7n:MailerConfig\",\n      \"@context\": {\n        \"queue_url\": {\n          \"@id\": \"c7n:sqsQueueUrl\",\n          \"@type\": \"@id\"\n        },\n        \"region\": {\n          \"@id\": \"c7n:awsRegion\"\n        },\n        \"from_address\": {\n          \"@id\": \"schema:email\"\n        },\n        \"role\": {\n          \"@id\": \"c7n:iamRole\",\n          \"@type\": \"@id\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/cloud-custodian/refs/heads/main/json-ld/cloud-custodian-context.jsonld
tags:
- Cloud Security
- Compliance
- Cost Optimization
- Multi-Cloud
- Policy as Code
- JSON-LD
- Linked Data
- Semantic Web
---
