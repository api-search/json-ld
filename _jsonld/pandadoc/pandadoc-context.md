---
api_specs:
- filename: pandadoc-rest-api-openapi.yml
  format: yaml
  label: PandaDoc REST API
  slug: rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/pandadoc/refs/heads/main/openapi/pandadoc-rest-api-openapi.yml
- filename: pandadoc-rest-api-openapi.yml
  format: yaml
  label: PandaDoc Document Generation API
  slug: document-generation-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/pandadoc/refs/heads/main/openapi/pandadoc-rest-api-openapi.yml
- filename: pandadoc-rest-api-openapi.yml
  format: yaml
  label: PandaDoc E-Signature API
  slug: e-signature-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/pandadoc/refs/heads/main/openapi/pandadoc-rest-api-openapi.yml
- filename: pandadoc-rest-api-openapi.yml
  format: yaml
  label: PandaDoc Embedded Editing API
  slug: embedded-editing-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/pandadoc/refs/heads/main/openapi/pandadoc-rest-api-openapi.yml
- filename: pandadoc-rest-api-openapi.yml
  format: yaml
  label: PandaDoc Webhooks API
  slug: webhooks-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/pandadoc/refs/heads/main/openapi/pandadoc-rest-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/pandadoc-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/pandadoc/refs/heads/main/json-ld/pandadoc-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Pandadoc from PandaDoc.
layout: jsonld
name: Pandadoc Context
namespaces:
- prefix: pandadoc
  uri: https://api.pandadoc.com/schemas/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Document
  type: ''
- container: ''
  name: Recipient
  type: ''
- container: ''
  name: Template
  type: ''
- container: ''
  name: Contact
  type: ''
- container: ''
  name: Member
  type: ''
- container: ''
  name: WebhookSubscription
  type: ''
- container: ''
  name: Folder
  type: ''
- container: ''
  name: Workspace
  type: ''
- container: ''
  name: ContentLibraryItem
  type: ''
- container: ''
  name: PricingLineItem
  type: ''
property_count: 10
provider_name: PandaDoc
provider_slug: pandadoc
slug: pandadoc-context
source_filename: pandadoc-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"pandadoc\": \"https://api.pandadoc.com/schemas/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Document\": {\n      \"@id\": \"pandadoc:Document\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"status\": \"pandadoc:documentStatus\",\n        \"date_created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"date_modified\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"expiration_date\": {\n          \"@id\": \"pandadoc:expirationDate\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"version\": \"schema:version\",\n        \"tags\": {\n          \"@id\": \"schema:keywords\",\n          \"\
  @container\": \"@set\"\n        },\n        \"folder_uuid\": {\n          \"@id\": \"pandadoc:folder\",\n          \"@type\": \"@id\"\n        },\n        \"created_by\": {\n          \"@id\": \"dcterms:creator\",\n          \"@type\": \"@id\"\n        },\n        \"sent_by\": {\n          \"@id\": \"pandadoc:sentBy\",\n          \"@type\": \"@id\"\n        },\n        \"recipients\": {\n          \"@id\": \"pandadoc:hasRecipient\",\n          \"@container\": \"@set\"\n        },\n        \"template\": {\n          \"@id\": \"pandadoc:fromTemplate\",\n          \"@type\": \"@id\"\n        },\n        \"grand_total\": \"schema:totalPrice\",\n        \"metadata\": \"pandadoc:metadata\",\n        \"linked_objects\": {\n          \"@id\": \"pandadoc:linkedObject\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Recipient\": {\n      \"@id\": \"pandadoc:Recipient\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"first_name\": \"schema:givenName\",\n  \
  \      \"last_name\": \"schema:familyName\",\n        \"email\": \"schema:email\",\n        \"phone\": \"schema:telephone\",\n        \"recipient_type\": \"pandadoc:recipientType\",\n        \"role\": \"pandadoc:signerRole\",\n        \"signing_order\": \"pandadoc:signingOrder\",\n        \"has_completed\": \"pandadoc:hasCompleted\",\n        \"contact_id\": {\n          \"@id\": \"pandadoc:contact\",\n          \"@type\": \"@id\"\n        },\n        \"shared_link\": {\n          \"@id\": \"pandadoc:sharedSigningLink\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Template\": {\n      \"@id\": \"pandadoc:Template\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": \"schema:name\",\n        \"date_created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"date_modified\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"tags\": {\n \
  \         \"@id\": \"schema:keywords\",\n          \"@container\": \"@set\"\n        },\n        \"roles\": {\n          \"@id\": \"pandadoc:hasRole\",\n          \"@container\": \"@set\"\n        },\n        \"tokens\": {\n          \"@id\": \"pandadoc:hasToken\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Contact\": {\n      \"@id\": \"pandadoc:Contact\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"email\": \"schema:email\",\n        \"first_name\": \"schema:givenName\",\n        \"last_name\": \"schema:familyName\",\n        \"company\": \"schema:worksFor\",\n        \"job_title\": \"schema:jobTitle\",\n        \"phone\": \"schema:telephone\",\n        \"street_address\": \"schema:streetAddress\",\n        \"city\": \"schema:addressLocality\",\n        \"state\": \"schema:addressRegion\",\n        \"postal_code\": \"schema:postalCode\",\n        \"country\": \"schema:addressCountry\"\n      }\n    },\n\n    \"Member\": {\n      \"@id\":\
  \ \"pandadoc:Member\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"email\": \"schema:email\",\n        \"first_name\": \"schema:givenName\",\n        \"last_name\": \"schema:familyName\",\n        \"role\": \"pandadoc:memberRole\",\n        \"status\": \"schema:status\",\n        \"user_id\": {\n          \"@id\": \"pandadoc:user\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"WebhookSubscription\": {\n      \"@id\": \"pandadoc:WebhookSubscription\",\n      \"@context\": {\n        \"uuid\": \"@id\",\n        \"name\": \"schema:name\",\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"status\": \"schema:status\",\n        \"active\": \"pandadoc:isActive\",\n        \"triggers\": {\n          \"@id\": \"pandadoc:eventTrigger\",\n          \"@container\": \"@set\"\n        },\n        \"payload\": {\n          \"@id\": \"pandadoc:payloadOption\",\n          \"@container\": \"@set\"\n        },\n\
  \        \"shared_key\": \"pandadoc:sharedKey\",\n        \"workspace_id\": {\n          \"@id\": \"pandadoc:workspace\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Folder\": {\n      \"@id\": \"pandadoc:Folder\",\n      \"@context\": {\n        \"uuid\": \"@id\",\n        \"name\": \"schema:name\",\n        \"date_created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"parent_uuid\": {\n          \"@id\": \"schema:isPartOf\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Workspace\": {\n      \"@id\": \"pandadoc:Workspace\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": \"schema:name\",\n        \"owner\": \"schema:email\",\n        \"date_created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"ContentLibraryItem\": {\n      \"@id\": \"pandadoc:ContentLibraryItem\",\n      \"@context\":\
  \ {\n        \"id\": \"@id\",\n        \"name\": \"schema:name\",\n        \"date_created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"status\": \"schema:status\"\n      }\n    },\n\n    \"PricingLineItem\": {\n      \"@id\": \"pandadoc:PricingLineItem\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"qty\": \"schema:orderQuantity\",\n        \"price\": \"schema:price\",\n        \"subtotal\": \"pandadoc:lineSubtotal\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/pandadoc/refs/heads/main/json-ld/pandadoc-context.jsonld
tags:
- Document Automation
- E-Signature
- Document Management
- Document Generation
- Webhooks
- JSON-LD
- Linked Data
- Semantic Web
---
