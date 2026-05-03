---
api_specs:
- filename: trello-rest-api-openapi.yml
  format: yaml
  label: Trello REST API
  slug: rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/trello/refs/heads/main/openapi/trello-rest-api-openapi.yml
- filename: trello-webhooks-asyncapi.yml
  format: yaml
  label: Trello Webhooks API
  slug: webhooks-api
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/trello/refs/heads/main/asyncapi/trello-webhooks-asyncapi.yml
class_count: 0
classes: []
context_file: json-ld/trello-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/trello/refs/heads/main/json-ld/trello-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Trello from trello.
layout: jsonld
name: Trello Context
namespaces:
- prefix: trello
  uri: https://api.trello.com/1/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Board
  type: ''
- container: ''
  name: Card
  type: ''
- container: ''
  name: List
  type: ''
- container: ''
  name: Label
  type: ''
- container: ''
  name: Member
  type: ''
- container: ''
  name: Organization
  type: ''
- container: ''
  name: Checklist
  type: ''
- container: ''
  name: CheckItem
  type: ''
- container: ''
  name: Attachment
  type: ''
- container: ''
  name: Webhook
  type: ''
- container: ''
  name: Action
  type: ''
- container: ''
  name: CustomField
  type: ''
- container: ''
  name: Notification
  type: ''
property_count: 13
provider_name: trello
provider_slug: trello
slug: trello-context
source_filename: trello-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"trello\": \"https://api.trello.com/1/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Board\": {\n      \"@id\": \"trello:Board\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"shortUrl\": {\n          \"@id\": \"trello:shortUrl\",\n          \"@type\": \"@id\"\n        },\n        \"closed\": \"trello:closed\",\n        \"pinned\": \"trello:pinned\",\n        \"starred\": \"trello:starred\",\n        \"dateLastActivity\": {\n          \"@id\": \"schema:dateModified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"dateLastView\": {\n          \"@id\": \"trello:dateLastView\",\n          \"@type\": \"xsd:dateTime\"\n        },\n    \
  \    \"idOrganization\": \"trello:idOrganization\",\n        \"idMemberCreator\": \"dcterms:creator\",\n        \"members\": {\n          \"@id\": \"schema:member\",\n          \"@container\": \"@set\"\n        },\n        \"lists\": {\n          \"@id\": \"trello:lists\",\n          \"@container\": \"@set\"\n        },\n        \"labels\": {\n          \"@id\": \"trello:labels\",\n          \"@container\": \"@set\"\n        },\n        \"prefs\": \"trello:prefs\"\n      }\n    },\n\n    \"Card\": {\n      \"@id\": \"trello:Card\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"shortUrl\": {\n          \"@id\": \"trello:shortUrl\",\n          \"@type\": \"@id\"\n        },\n        \"closed\": \"trello:closed\",\n        \"due\": {\n          \"@id\": \"trello:due\",\n          \"@type\": \"xsd:dateTime\"\n        },\n\
  \        \"dueComplete\": \"trello:dueComplete\",\n        \"start\": {\n          \"@id\": \"trello:start\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"dateLastActivity\": {\n          \"@id\": \"schema:dateModified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"pos\": \"trello:pos\",\n        \"idBoard\": \"trello:idBoard\",\n        \"idList\": \"trello:idList\",\n        \"idShort\": \"trello:idShort\",\n        \"subscribed\": \"trello:subscribed\",\n        \"members\": {\n          \"@id\": \"schema:member\",\n          \"@container\": \"@set\"\n        },\n        \"labels\": {\n          \"@id\": \"trello:labels\",\n          \"@container\": \"@set\"\n        },\n        \"checklists\": {\n          \"@id\": \"trello:checklists\",\n          \"@container\": \"@set\"\n        },\n        \"attachments\": {\n          \"@id\": \"trello:attachments\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"List\": {\n      \"\
  @id\": \"trello:List\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"closed\": \"trello:closed\",\n        \"pos\": \"trello:pos\",\n        \"idBoard\": \"trello:idBoard\",\n        \"subscribed\": \"trello:subscribed\",\n        \"cards\": {\n          \"@id\": \"trello:cards\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Label\": {\n      \"@id\": \"trello:Label\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"color\": \"trello:color\",\n        \"idBoard\": \"trello:idBoard\"\n      }\n    },\n\n    \"Member\": {\n      \"@id\": \"trello:Member\",\n      \"@context\": {\n        \"username\": \"schema:alternateName\",\n        \"fullName\": \"schema:name\",\n        \"bio\": \"schema:description\",\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"avatarUrl\": {\n          \"@id\": \"schema:image\",\n          \"@type\": \"@id\"\n        },\n    \
  \    \"initials\": \"trello:initials\",\n        \"confirmed\": \"trello:confirmed\",\n        \"memberType\": \"trello:memberType\",\n        \"status\": \"trello:status\",\n        \"organizations\": {\n          \"@id\": \"schema:memberOf\",\n          \"@container\": \"@set\"\n        },\n        \"boards\": {\n          \"@id\": \"trello:boards\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Organization\": {\n      \"@id\": \"trello:Organization\",\n      \"@context\": {\n        \"name\": \"schema:alternateName\",\n        \"displayName\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"website\": {\n          \"@id\": \"schema:sameAs\",\n          \"@type\": \"@id\"\n        },\n        \"members\": {\n          \"@id\": \"schema:member\",\n          \"@container\": \"@set\"\n        },\n        \"boards\": {\n          \"@id\"\
  : \"trello:boards\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Checklist\": {\n      \"@id\": \"trello:Checklist\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"pos\": \"trello:pos\",\n        \"idBoard\": \"trello:idBoard\",\n        \"idCard\": \"trello:idCard\",\n        \"checkItems\": {\n          \"@id\": \"trello:checkItems\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"CheckItem\": {\n      \"@id\": \"trello:CheckItem\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"state\": \"trello:state\",\n        \"pos\": \"trello:pos\",\n        \"due\": {\n          \"@id\": \"trello:due\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"idMember\": \"trello:idMember\"\n      }\n    },\n\n    \"Attachment\": {\n      \"@id\": \"trello:Attachment\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"url\": {\n          \"@id\": \"schema:contentUrl\"\
  ,\n          \"@type\": \"@id\"\n        },\n        \"mimeType\": \"schema:encodingFormat\",\n        \"bytes\": \"schema:contentSize\",\n        \"date\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"isUpload\": \"trello:isUpload\",\n        \"idMember\": \"trello:idMember\"\n      }\n    },\n\n    \"Webhook\": {\n      \"@id\": \"trello:Webhook\",\n      \"@context\": {\n        \"description\": \"schema:description\",\n        \"callbackURL\": {\n          \"@id\": \"trello:callbackURL\",\n          \"@type\": \"@id\"\n        },\n        \"idModel\": \"trello:idModel\",\n        \"active\": \"trello:active\",\n        \"consecutiveFailures\": \"trello:consecutiveFailures\",\n        \"firstConsecutiveFailDate\": {\n          \"@id\": \"trello:firstConsecutiveFailDate\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Action\": {\n      \"@id\": \"trello:Action\",\n      \"@context\": {\n      \
  \  \"type\": \"trello:actionType\",\n        \"date\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"idMemberCreator\": \"dcterms:creator\",\n        \"data\": \"trello:actionData\",\n        \"memberCreator\": \"trello:memberCreator\"\n      }\n    },\n\n    \"CustomField\": {\n      \"@id\": \"trello:CustomField\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"type\": \"trello:fieldType\",\n        \"pos\": \"trello:pos\",\n        \"idModel\": \"trello:idModel\",\n        \"options\": {\n          \"@id\": \"trello:options\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Notification\": {\n      \"@id\": \"trello:Notification\",\n      \"@context\": {\n        \"type\": \"trello:notificationType\",\n        \"date\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"unread\": \"trello:unread\",\n        \"data\": \"trello:notificationData\"\
  ,\n        \"idMemberCreator\": \"dcterms:creator\",\n        \"memberCreator\": \"trello:memberCreator\"\n      }\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/trello/refs/heads/main/json-ld/trello-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
