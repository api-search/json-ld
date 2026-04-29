---
class_count: 0
classes: []
context_file: json-ld/zendesk-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/zendesk/refs/heads/main/json-ld/zendesk-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Zendesk from Zendesk.
layout: jsonld
name: Zendesk Context
namespaces:
- prefix: zendesk
  uri: https://developer.zendesk.com/api-reference/ticketing/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: foaf
  uri: http://xmlns.com/foaf/0.1/
- prefix: vcard
  uri: http://www.w3.org/2006/vcard/ns#
- prefix: org
  uri: http://www.w3.org/ns/org#
properties:
- container: ''
  name: Ticket
  type: ''
- container: ''
  name: User
  type: ''
- container: ''
  name: Organization
  type: ''
- container: ''
  name: Comment
  type: ''
- container: ''
  name: SatisfactionRating
  type: ''
property_count: 5
provider_name: Zendesk
provider_slug: zendesk
slug: zendesk-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"zendesk\": \"https://developer.zendesk.com/api-reference/ticketing/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"foaf\": \"http://xmlns.com/foaf/0.1/\",\n    \"vcard\": \"http://www.w3.org/2006/vcard/ns#\",\n    \"org\": \"http://www.w3.org/ns/org#\",\n\n    \"Ticket\": {\n      \"@id\": \"zendesk:tickets/tickets/#ticket\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"dcterms:identifier\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"externalId\": {\n          \"@id\": \"zendesk:tickets/tickets/#external_id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"type\": {\n          \"@id\": \"dcterms:type\",\n          \"@type\": \"xsd:string\"\n        },\n        \"subject\"\
  : {\n          \"@id\": \"dcterms:title\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"dcterms:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"priority\": {\n          \"@id\": \"zendesk:tickets/tickets/#priority\",\n          \"@type\": \"xsd:string\"\n        },\n        \"status\": {\n          \"@id\": \"zendesk:tickets/tickets/#status\",\n          \"@type\": \"xsd:string\"\n        },\n        \"requesterId\": {\n          \"@id\": \"zendesk:tickets/tickets/#requester_id\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"submitterId\": {\n          \"@id\": \"zendesk:tickets/tickets/#submitter_id\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"assigneeId\": {\n          \"@id\": \"zendesk:tickets/tickets/#assignee_id\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"organizationId\": {\n          \"@id\": \"zendesk:tickets/tickets/#organization_id\",\n    \
  \      \"@type\": \"xsd:integer\"\n        },\n        \"groupId\": {\n          \"@id\": \"zendesk:tickets/tickets/#group_id\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"tags\": {\n          \"@id\": \"zendesk:tickets/tickets/#tags\",\n          \"@container\": \"@set\"\n        },\n        \"dueAt\": {\n          \"@id\": \"zendesk:tickets/tickets/#due_at\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"brandId\": {\n          \"@id\": \"zendesk:tickets/tickets/#brand_id\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"ticketFormId\": {\n          \"@id\": \"zendesk:tickets/tickets/#ticket_form_id\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"User\": {\n      \"@id\": \"\
  zendesk:users/users/#user\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"dcterms:identifier\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"name\": {\n          \"@id\": \"foaf:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"email\": {\n          \"@id\": \"foaf:mbox\",\n          \"@type\": \"xsd:string\"\n        },\n        \"phone\": {\n          \"@id\": \"vcard:tel\",\n          \"@type\": \"xsd:string\"\n        },\n        \"role\": {\n          \"@id\": \"zendesk:users/users/#role\",\n          \"@type\": \"xsd:string\"\n        },\n        \"organizationId\": {\n          \"@id\": \"zendesk:users/users/#organization_id\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"externalId\": {\n          \"@id\": \"zendesk:users/users/#external_id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"alias\": {\n\
  \          \"@id\": \"zendesk:users/users/#alias\",\n          \"@type\": \"xsd:string\"\n        },\n        \"verified\": {\n          \"@id\": \"zendesk:users/users/#verified\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"active\": {\n          \"@id\": \"zendesk:users/users/#active\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"suspended\": {\n          \"@id\": \"zendesk:users/users/#suspended\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"tags\": {\n          \"@id\": \"zendesk:users/users/#tags\",\n          \"@container\": \"@set\"\n        },\n        \"locale\": {\n          \"@id\": \"zendesk:users/users/#locale\",\n          \"@type\": \"xsd:string\"\n        },\n        \"timeZone\": {\n          \"@id\": \"zendesk:users/users/#time_zone\",\n          \"@type\": \"xsd:string\"\n        },\n        \"signature\": {\n          \"@id\": \"zendesk:users/users/#signature\",\n          \"@type\": \"xsd:string\"\n        },\n   \
  \     \"details\": {\n          \"@id\": \"zendesk:users/users/#details\",\n          \"@type\": \"xsd:string\"\n        },\n        \"notes\": {\n          \"@id\": \"zendesk:users/users/#notes\",\n          \"@type\": \"xsd:string\"\n        },\n        \"lastLoginAt\": {\n          \"@id\": \"zendesk:users/users/#last_login_at\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Organization\": {\n      \"@id\": \"zendesk:organizations/organizations/#organization\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"dcterms:identifier\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"name\": {\n      \
  \    \"@id\": \"org:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"details\": {\n          \"@id\": \"zendesk:organizations/organizations/#details\",\n          \"@type\": \"xsd:string\"\n        },\n        \"notes\": {\n          \"@id\": \"zendesk:organizations/organizations/#notes\",\n          \"@type\": \"xsd:string\"\n        },\n        \"domainNames\": {\n          \"@id\": \"zendesk:organizations/organizations/#domain_names\",\n          \"@container\": \"@set\"\n        },\n        \"groupId\": {\n          \"@id\": \"zendesk:organizations/organizations/#group_id\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"sharedTickets\": {\n          \"@id\": \"zendesk:organizations/organizations/#shared_tickets\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"sharedComments\": {\n          \"@id\": \"zendesk:organizations/organizations/#shared_comments\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"externalId\": {\n\
  \          \"@id\": \"zendesk:organizations/organizations/#external_id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"tags\": {\n          \"@id\": \"zendesk:organizations/organizations/#tags\",\n          \"@container\": \"@set\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Comment\": {\n      \"@id\": \"zendesk:tickets/ticket_comments/#comment\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"dcterms:identifier\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"body\": {\n          \"@id\": \"schema:text\",\n          \"@type\": \"xsd:string\"\n        },\n        \"htmlBody\": {\n          \"@id\": \"zendesk:tickets/ticket_comments/#html_body\",\n          \"@type\": \"xsd:string\"\n        },\n        \"public\"\
  : {\n          \"@id\": \"zendesk:tickets/ticket_comments/#public\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"authorId\": {\n          \"@id\": \"dcterms:creator\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"SatisfactionRating\": {\n      \"@id\": \"zendesk:tickets/satisfaction_ratings/#satisfaction_rating\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"dcterms:identifier\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"score\": {\n          \"@id\": \"schema:ratingValue\",\n          \"@type\": \"xsd:string\"\n        },\n        \"comment\": {\n          \"@id\": \"schema:reviewBody\",\n          \"@type\": \"xsd:string\"\n        },\n        \"ticketId\": {\n          \"@id\": \"zendesk:tickets/satisfaction_ratings/#ticket_id\",\n          \"@type\": \"xsd:integer\"\n        },\n  \
  \      \"requesterId\": {\n          \"@id\": \"zendesk:tickets/satisfaction_ratings/#requester_id\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"assigneeId\": {\n          \"@id\": \"zendesk:tickets/satisfaction_ratings/#assignee_id\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/zendesk/refs/heads/main/json-ld/zendesk-context.jsonld
tags:
- Chat
- CRM
- Help Center
- Sell
- Support
- T1
- Talk
- Ticketing
- Tickets
- JSON-LD
- Linked Data
- Semantic Web
---
