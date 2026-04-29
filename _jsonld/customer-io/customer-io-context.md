---
api_specs:
- filename: customer-io-track-api-openapi.yml
  format: yaml
  label: Customer.io Track API
  slug: track-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/customer-io/refs/heads/main/openapi/customer-io-track-api-openapi.yml
- filename: customer-io-app-api-openapi.yml
  format: yaml
  label: Customer.io App API
  slug: app-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/customer-io/refs/heads/main/openapi/customer-io-app-api-openapi.yml
- filename: customer-io-pipelines-api-openapi.yml
  format: yaml
  label: Customer.io Pipelines API
  slug: pipelines-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/customer-io/refs/heads/main/openapi/customer-io-pipelines-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/customer-io-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/customer-io/refs/heads/main/json-ld/customer-io-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Customer Io from Customer.io.
layout: jsonld
name: Customer Io Context
namespaces:
- prefix: cio
  uri: https://customer.io/ns/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Customer
  type: ''
- container: ''
  name: Event
  type: ''
- container: ''
  name: Campaign
  type: ''
- container: ''
  name: Segment
  type: ''
- container: ''
  name: Message
  type: ''
- container: ''
  name: Broadcast
  type: ''
- container: ''
  name: Device
  type: ''
- container: ''
  name: Newsletter
  type: ''
- container: ''
  name: Collection
  type: ''
- container: ''
  name: SenderIdentity
  type: ''
- container: ''
  name: WebhookEvent
  type: ''
property_count: 11
provider_name: Customer.io
provider_slug: customer-io
slug: customer-io-context
source_filename: customer-io-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"cio\": \"https://customer.io/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Customer\": {\n      \"@id\": \"cio:Customer\",\n      \"@context\": {\n        \"identifier\": \"schema:identifier\",\n        \"email\": \"schema:email\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"anonymousId\": \"cio:anonymousId\",\n        \"unsubscribed\": \"cio:unsubscribed\",\n        \"attributes\": \"cio:attributes\",\n        \"devices\": {\n          \"@id\": \"cio:devices\",\n          \"@container\": \"@set\"\n        },\n        \"segments\": {\n          \"@id\": \"cio:segments\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Event\": {\n      \"@id\": \"cio:Event\",\n      \"@context\": {\n        \"name\": \"\
  schema:name\",\n        \"eventType\": \"cio:eventType\",\n        \"timestamp\": {\n          \"@id\": \"dcterms:date\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"data\": \"cio:eventData\",\n        \"customerId\": \"cio:customerId\",\n        \"anonymousId\": \"cio:anonymousId\"\n      }\n    },\n\n    \"Campaign\": {\n      \"@id\": \"cio:Campaign\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"campaignType\": \"cio:campaignType\",\n        \"active\": \"cio:active\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"tags\": {\n          \"@id\": \"schema:keywords\",\n          \"@container\": \"@set\"\n        },\n        \"actions\": {\n          \"@id\": \"cio:actions\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n   \
  \ \"Segment\": {\n      \"@id\": \"cio:Segment\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"segmentType\": \"cio:segmentType\",\n        \"state\": \"cio:state\"\n      }\n    },\n\n    \"Message\": {\n      \"@id\": \"cio:Message\",\n      \"@context\": {\n        \"subject\": \"cio:subject\",\n        \"messageType\": \"cio:messageType\",\n        \"customerId\": \"cio:customerId\",\n        \"campaignId\": \"cio:campaignId\",\n        \"deliveryId\": \"cio:deliveryId\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"sentAt\": {\n          \"@id\": \"cio:sentAt\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"deliveredAt\": {\n          \"@id\": \"cio:deliveredAt\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"openedAt\": {\n          \"@id\": \"cio:openedAt\",\n          \"@type\": \"xsd:dateTime\"\
  \n        }\n      }\n    },\n\n    \"Broadcast\": {\n      \"@id\": \"cio:Broadcast\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"campaignId\": \"cio:campaignId\",\n        \"triggeredAt\": {\n          \"@id\": \"cio:triggeredAt\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"data\": \"cio:broadcastData\",\n        \"recipients\": {\n          \"@id\": \"cio:recipients\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Device\": {\n      \"@id\": \"cio:Device\",\n      \"@context\": {\n        \"deviceToken\": \"cio:deviceToken\",\n        \"platform\": \"cio:platform\",\n        \"lastUsed\": {\n          \"@id\": \"cio:lastUsed\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Newsletter\": {\n      \"@id\": \"cio:Newsletter\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"sentAt\": {\n          \"@id\": \"cio:sentAt\",\n          \"@type\": \"xsd:dateTime\"\n \
  \       },\n        \"numRecipients\": \"cio:numRecipients\",\n        \"tags\": {\n          \"@id\": \"schema:keywords\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Collection\": {\n      \"@id\": \"cio:Collection\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"dataType\": \"cio:dataType\",\n        \"dataUrl\": {\n          \"@id\": \"cio:dataUrl\",\n          \"@type\": \"@id\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"SenderIdentity\": {\n      \"@id\": \"cio:SenderIdentity\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"address\": \"schema:email\",\n        \"replyTo\": \"cio:replyTo\",\n        \"verified\": \"cio:verified\"\n      }\n    },\n\n    \"WebhookEvent\": {\n  \
  \    \"@id\": \"cio:WebhookEvent\",\n      \"@context\": {\n        \"eventId\": \"schema:identifier\",\n        \"metric\": \"cio:metric\",\n        \"timestamp\": {\n          \"@id\": \"dcterms:date\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"deliveryId\": \"cio:deliveryId\",\n        \"customerId\": \"cio:customerId\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/customer-io/refs/heads/main/json-ld/customer-io-context.jsonld
tags:
- Behavioral Data
- Broadcasts
- Campaigns
- CDP
- Customer Data
- Customer Data Platform
- Data Ingestion
- Email
- Event Tracking
- Marketing Automation
- Messaging
- Push Notifications
- Segments
- SMS
- Transactional Email
- JSON-LD
- Linked Data
- Semantic Web
---
