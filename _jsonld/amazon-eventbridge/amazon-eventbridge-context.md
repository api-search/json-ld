---
api_specs:
- filename: amazon-eventbridge-openapi.yml
  format: yaml
  label: Amazon EventBridge API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-eventbridge/refs/heads/main/openapi/amazon-eventbridge-openapi.yml
class_count: 5
classes:
- version
- detail-type
- account
- region
- detail
context_file: json-ld/amazon-eventbridge-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-eventbridge/refs/heads/main/json-ld/amazon-eventbridge-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Eventbridge from Amazon EventBridge.
layout: jsonld
name: Amazon Eventbridge Context
namespaces:
- prefix: eventbridge
  uri: https://aws.amazon.com/eventbridge/schemas/
- prefix: aws
  uri: https://aws.amazon.com/schemas/
properties:
- container: ''
  name: id
  type: reference
- container: ''
  name: source
  type: reference
- container: ''
  name: time
  type: http://www.w3.org/2001/XMLSchema#dateTime
- container: set
  name: resources
  type: reference
- container: ''
  name: EventBus
  type: ''
- container: ''
  name: Rule
  type: ''
- container: ''
  name: Target
  type: ''
- container: ''
  name: Archive
  type: ''
- container: ''
  name: Event
  type: ''
property_count: 9
provider_name: Amazon EventBridge
provider_slug: amazon-eventbridge
slug: amazon-eventbridge-context
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"eventbridge\": \"https://aws.amazon.com/eventbridge/schemas/\",\n    \"aws\": \"https://aws.amazon.com/schemas/\",\n    \"id\": {\n      \"@id\": \"eventbridge:eventId\",\n      \"@type\": \"@id\"\n    },\n    \"version\": \"eventbridge:version\",\n    \"detail-type\": \"eventbridge:detailType\",\n    \"source\": {\n      \"@id\": \"eventbridge:source\",\n      \"@type\": \"@id\"\n    },\n    \"account\": \"eventbridge:account\",\n    \"time\": {\n      \"@id\": \"eventbridge:time\",\n      \"@type\": \"http://www.w3.org/2001/XMLSchema#dateTime\"\n    },\n    \"region\": \"eventbridge:region\",\n    \"resources\": {\n      \"@id\": \"eventbridge:resources\",\n      \"@type\": \"@id\",\n      \"@container\": \"@set\"\n    },\n    \"detail\": \"eventbridge:detail\",\n    \"EventBus\": {\n      \"@id\": \"eventbridge:EventBus\",\n      \"@context\": {\n        \"name\": \"eventbridge:eventBusName\",\n      \
  \  \"arn\": {\n          \"@id\": \"aws:arn\",\n          \"@type\": \"@id\"\n        },\n        \"policy\": \"eventbridge:policy\"\n      }\n    },\n    \"Rule\": {\n      \"@id\": \"eventbridge:Rule\",\n      \"@context\": {\n        \"name\": \"eventbridge:ruleName\",\n        \"arn\": {\n          \"@id\": \"aws:arn\",\n          \"@type\": \"@id\"\n        },\n        \"eventPattern\": \"eventbridge:eventPattern\",\n        \"scheduleExpression\": \"eventbridge:scheduleExpression\",\n        \"state\": \"eventbridge:ruleState\",\n        \"description\": \"schema:description\",\n        \"roleArn\": {\n          \"@id\": \"aws:roleArn\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n    \"Target\": {\n      \"@id\": \"eventbridge:Target\",\n      \"@context\": {\n        \"targetId\": \"eventbridge:targetId\",\n        \"arn\": {\n          \"@id\": \"aws:arn\",\n          \"@type\": \"@id\"\n        },\n        \"roleArn\": {\n          \"@id\": \"aws:roleArn\",\n \
  \         \"@type\": \"@id\"\n        },\n        \"input\": \"eventbridge:input\",\n        \"inputPath\": \"eventbridge:inputPath\"\n      }\n    },\n    \"Archive\": {\n      \"@id\": \"eventbridge:Archive\",\n      \"@context\": {\n        \"archiveName\": \"eventbridge:archiveName\",\n        \"eventSourceArn\": {\n          \"@id\": \"eventbridge:eventSourceArn\",\n          \"@type\": \"@id\"\n        },\n        \"retentionDays\": {\n          \"@id\": \"eventbridge:retentionDays\",\n          \"@type\": \"http://www.w3.org/2001/XMLSchema#integer\"\n        },\n        \"state\": \"eventbridge:archiveState\"\n      }\n    },\n    \"Event\": {\n      \"@id\": \"eventbridge:Event\",\n      \"@context\": {\n        \"detailType\": \"eventbridge:detailType\",\n        \"source\": {\n          \"@id\": \"eventbridge:source\",\n          \"@type\": \"@id\"\n        },\n        \"eventBusName\": \"eventbridge:eventBusName\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-eventbridge/refs/heads/main/json-ld/amazon-eventbridge-context.jsonld
tags:
- Amazon Web Services
- AWS
- Event Bus
- Event-Driven
- Events
- Integration
- Serverless
- JSON-LD
- Linked Data
- Semantic Web
---
