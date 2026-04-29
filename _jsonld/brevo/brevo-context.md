---
class_count: 0
classes: []
context_file: json-ld/brevo-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/brevo/refs/heads/main/json-ld/brevo-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Brevo from brevo.
layout: jsonld
name: Brevo Context
namespaces:
- prefix: brevo
  uri: https://api.brevo.com/v3/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Contact
  type: ''
- container: ''
  name: ContactList
  type: ''
- container: ''
  name: EmailCampaign
  type: ''
- container: ''
  name: TransactionalEmail
  type: ''
- container: ''
  name: EmailEvent
  type: ''
- container: ''
  name: Product
  type: ''
- container: ''
  name: Order
  type: ''
- container: ''
  name: Webhook
  type: ''
- container: ''
  name: Conversation
  type: ''
- container: ''
  name: WhatsAppCampaign
  type: ''
property_count: 10
provider_name: brevo
provider_slug: brevo
slug: brevo-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"brevo\": \"https://api.brevo.com/v3/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Contact\": {\n      \"@id\": \"brevo:Contact\",\n      \"@context\": {\n        \"email\": \"schema:email\",\n        \"phone\": \"schema:telephone\",\n        \"emailBlacklisted\": \"brevo:emailBlacklisted\",\n        \"smsBlacklisted\": \"brevo:smsBlacklisted\",\n        \"listIds\": {\n          \"@id\": \"brevo:listIds\",\n          \"@container\": \"@set\"\n        },\n        \"attributes\": \"brevo:attributes\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"modifiedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"ContactList\": {\n      \"@id\": \"brevo:ContactList\",\n\
  \      \"@context\": {\n        \"name\": \"schema:name\",\n        \"totalSubscribers\": \"brevo:totalSubscribers\",\n        \"totalBlacklisted\": \"brevo:totalBlacklisted\",\n        \"folderId\": \"brevo:folderId\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"EmailCampaign\": {\n      \"@id\": \"brevo:EmailCampaign\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"subject\": \"brevo:subject\",\n        \"status\": \"brevo:status\",\n        \"type\": \"brevo:campaignType\",\n        \"sender\": \"schema:sender\",\n        \"scheduledAt\": {\n          \"@id\": \"brevo:scheduledAt\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"recipients\": {\n          \"@id\": \"brevo:recipients\",\n          \"@container\": \"@set\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n\
  \        \"modifiedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"TransactionalEmail\": {\n      \"@id\": \"brevo:TransactionalEmail\",\n      \"@context\": {\n        \"sender\": \"schema:sender\",\n        \"to\": \"schema:recipient\",\n        \"subject\": \"brevo:subject\",\n        \"htmlContent\": \"brevo:htmlContent\",\n        \"templateId\": \"brevo:templateId\",\n        \"messageId\": \"schema:identifier\",\n        \"scheduledAt\": {\n          \"@id\": \"brevo:scheduledAt\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"tags\": {\n          \"@id\": \"brevo:tags\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"EmailEvent\": {\n      \"@id\": \"brevo:EmailEvent\",\n      \"@context\": {\n        \"event\": \"schema:actionStatus\",\n        \"email\": \"schema:email\",\n        \"messageId\": \"schema:identifier\",\n        \"subject\": \"brevo:subject\"\
  ,\n        \"tag\": \"brevo:tag\",\n        \"reason\": \"brevo:reason\",\n        \"link\": {\n          \"@id\": \"brevo:clickedLink\",\n          \"@type\": \"@id\"\n        },\n        \"date\": {\n          \"@id\": \"dcterms:date\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Product\": {\n      \"@id\": \"schema:Product\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"imageUrl\": {\n          \"@id\": \"schema:image\",\n          \"@type\": \"@id\"\n        },\n        \"sku\": \"schema:sku\",\n        \"price\": \"schema:price\",\n        \"categories\": {\n          \"@id\": \"schema:category\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Order\": {\n      \"@id\": \"schema:Order\",\n      \"@context\": {\n        \"email\": \"schema:email\",\n        \"status\": \"schema:orderStatus\",\n        \"\
  amount\": \"schema:totalPrice\",\n        \"products\": {\n          \"@id\": \"schema:orderedItem\",\n          \"@container\": \"@set\"\n        },\n        \"coupons\": {\n          \"@id\": \"schema:discount\",\n          \"@container\": \"@set\"\n        },\n        \"createdAt\": {\n          \"@id\": \"schema:orderDate\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Webhook\": {\n      \"@id\": \"brevo:Webhook\",\n      \"@context\": {\n        \"url\": {\n          \"@id\": \"brevo:webhookUrl\",\n          \"@type\": \"@id\"\n        },\n        \"description\": \"schema:description\",\n        \"type\": \"brevo:webhookType\",\n        \"events\": {\n          \"@id\": \"brevo:subscribedEvents\",\n          \"@container\": \"@set\"\n        },\n        \"isActive\": \"brevo:isActive\",\n        \"createdAt\": {\n          \"@id\"\
  : \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"modifiedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Conversation\": {\n      \"@id\": \"brevo:Conversation\",\n      \"@context\": {\n        \"visitorId\": \"brevo:visitorId\",\n        \"text\": \"schema:text\",\n        \"agentId\": \"brevo:agentId\",\n        \"agentName\": \"schema:name\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"WhatsAppCampaign\": {\n      \"@id\": \"brevo:WhatsAppCampaign\",\n      \"@context\": {\n        \"campaignName\": \"schema:name\",\n        \"campaignStatus\": \"brevo:status\",\n        \"templateId\": \"brevo:templateId\",\n        \"scheduledAt\": {\n          \"@id\": \"brevo:scheduledAt\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"recipients\": {\n          \"@id\"\
  : \"brevo:recipients\",\n          \"@container\": \"@set\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"modifiedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/brevo/refs/heads/main/json-ld/brevo-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
