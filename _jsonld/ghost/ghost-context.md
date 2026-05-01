---
api_specs:
- filename: ghost-content-api-openapi.yml
  format: yaml
  label: Ghost Content API
  slug: content-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/ghost/refs/heads/main/openapi/ghost-content-api-openapi.yml
- filename: ghost-admin-api-openapi.yml
  format: yaml
  label: Ghost Admin API
  slug: admin-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/ghost/refs/heads/main/openapi/ghost-admin-api-openapi.yml
- filename: ghost-webhooks-asyncapi.yml
  format: yaml
  label: Ghost Webhooks
  slug: webhooks
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/ghost/refs/heads/main/asyncapi/ghost-webhooks-asyncapi.yml
class_count: 0
classes: []
context_file: json-ld/ghost-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/ghost/refs/heads/main/json-ld/ghost-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Ghost from Ghost.
layout: jsonld
name: Ghost Context
namespaces:
- prefix: ghost
  uri: https://ghost.org/ns/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Post
  type: ''
- container: ''
  name: Page
  type: ''
- container: ''
  name: Tag
  type: ''
- container: ''
  name: Author
  type: ''
- container: ''
  name: Member
  type: ''
- container: ''
  name: Tier
  type: ''
- container: ''
  name: Newsletter
  type: ''
- container: ''
  name: Offer
  type: ''
- container: ''
  name: Webhook
  type: ''
property_count: 9
provider_name: Ghost
provider_slug: ghost
slug: ghost-context
source_filename: ghost-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"ghost\": \"https://ghost.org/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Post\": {\n      \"@id\": \"ghost:Post\",\n      \"@context\": {\n        \"title\": \"schema:headline\",\n        \"slug\": \"ghost:slug\",\n        \"html\": \"ghost:html\",\n        \"plaintext\": \"ghost:plaintext\",\n        \"excerpt\": \"schema:description\",\n        \"featureImage\": {\n          \"@id\": \"schema:image\",\n          \"@type\": \"@id\"\n        },\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"canonicalUrl\": {\n          \"@id\": \"schema:sameAs\",\n          \"@type\": \"@id\"\n        },\n        \"featured\": \"ghost:featured\",\n        \"status\": \"ghost:status\",\n        \"visibility\": \"ghost:visibility\",\n        \"readingTime\": \"ghost:readingTime\"\
  ,\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"publishedAt\": {\n          \"@id\": \"dcterms:issued\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"authors\": {\n          \"@id\": \"schema:author\",\n          \"@container\": \"@set\"\n        },\n        \"tags\": {\n          \"@id\": \"schema:keywords\",\n          \"@container\": \"@set\"\n        },\n        \"primaryAuthor\": \"schema:author\",\n        \"primaryTag\": \"ghost:primaryTag\",\n        \"metaTitle\": \"ghost:metaTitle\",\n        \"metaDescription\": \"ghost:metaDescription\",\n        \"ogTitle\": \"ghost:ogTitle\",\n        \"ogDescription\": \"ghost:ogDescription\",\n        \"ogImage\": {\n          \"@id\": \"ghost:ogImage\",\n          \"@type\": \"@id\"\n        },\n        \"twitterTitle\"\
  : \"ghost:twitterTitle\",\n        \"twitterDescription\": \"ghost:twitterDescription\",\n        \"twitterImage\": {\n          \"@id\": \"ghost:twitterImage\",\n          \"@type\": \"@id\"\n        },\n        \"emailSubject\": \"ghost:emailSubject\",\n        \"customExcerpt\": \"ghost:customExcerpt\",\n        \"customTemplate\": \"ghost:customTemplate\"\n      }\n    },\n\n    \"Page\": {\n      \"@id\": \"ghost:Page\",\n      \"@context\": {\n        \"title\": \"schema:headline\",\n        \"slug\": \"ghost:slug\",\n        \"html\": \"ghost:html\",\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"publishedAt\": {\n          \"@id\": \"dcterms:issued\",\n          \"@type\": \"xsd:dateTime\"\
  \n        }\n      }\n    },\n\n    \"Tag\": {\n      \"@id\": \"ghost:Tag\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"slug\": \"ghost:slug\",\n        \"description\": \"schema:description\",\n        \"featureImage\": {\n          \"@id\": \"schema:image\",\n          \"@type\": \"@id\"\n        },\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"visibility\": \"ghost:visibility\",\n        \"accentColor\": \"ghost:accentColor\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Author\": {\n      \"@id\": \"ghost:Author\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"slug\": \"ghost:slug\",\n        \"bio\": \"schema:description\",\n        \"profileImage\": {\n\
  \          \"@id\": \"schema:image\",\n          \"@type\": \"@id\"\n        },\n        \"coverImage\": {\n          \"@id\": \"ghost:coverImage\",\n          \"@type\": \"@id\"\n        },\n        \"website\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"location\": \"schema:address\",\n        \"facebook\": \"ghost:facebook\",\n        \"twitter\": \"ghost:twitter\",\n        \"url\": {\n          \"@id\": \"schema:mainEntityOfPage\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Member\": {\n      \"@id\": \"ghost:Member\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"email\": \"schema:email\",\n        \"status\": \"ghost:memberStatus\",\n        \"note\": \"ghost:note\",\n        \"geolocation\": \"ghost:geolocation\",\n        \"labels\": {\n          \"@id\": \"ghost:labels\",\n          \"@container\": \"@set\"\n        },\n        \"newsletters\": {\n          \"@id\": \"ghost:newsletters\"\
  ,\n          \"@container\": \"@set\"\n        },\n        \"subscriptions\": {\n          \"@id\": \"ghost:subscriptions\",\n          \"@container\": \"@set\"\n        },\n        \"avatarImage\": {\n          \"@id\": \"schema:image\",\n          \"@type\": \"@id\"\n        },\n        \"emailCount\": \"ghost:emailCount\",\n        \"emailOpenedCount\": \"ghost:emailOpenedCount\",\n        \"emailOpenRate\": \"ghost:emailOpenRate\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Tier\": {\n      \"@id\": \"ghost:Tier\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"slug\": \"ghost:slug\",\n        \"description\": \"schema:description\",\n        \"active\": \"ghost:active\",\n        \"type\": \"ghost:tierType\",\n        \"visibility\": \"ghost:visibility\"\
  ,\n        \"monthlyPrice\": \"ghost:monthlyPrice\",\n        \"yearlyPrice\": \"ghost:yearlyPrice\",\n        \"currency\": \"schema:priceCurrency\",\n        \"trialDays\": \"ghost:trialDays\",\n        \"benefits\": {\n          \"@id\": \"ghost:benefits\",\n          \"@container\": \"@set\"\n        },\n        \"welcomePageUrl\": {\n          \"@id\": \"ghost:welcomePageUrl\",\n          \"@type\": \"@id\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Newsletter\": {\n      \"@id\": \"ghost:Newsletter\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"slug\": \"ghost:slug\",\n        \"description\": \"schema:description\",\n        \"senderName\": \"ghost:senderName\",\n        \"senderEmail\": \"ghost:senderEmail\",\n        \"status\"\
  : \"ghost:newsletterStatus\",\n        \"subscribeOnSignup\": \"ghost:subscribeOnSignup\",\n        \"sortOrder\": \"ghost:sortOrder\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Offer\": {\n      \"@id\": \"ghost:Offer\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"code\": \"ghost:offerCode\",\n        \"displayTitle\": \"ghost:displayTitle\",\n        \"displayDescription\": \"ghost:displayDescription\",\n        \"type\": \"ghost:offerType\",\n        \"cadence\": \"ghost:cadence\",\n        \"amount\": \"ghost:amount\",\n        \"duration\": \"ghost:duration\",\n        \"status\": \"ghost:offerStatus\",\n        \"redemptionCount\": \"ghost:redemptionCount\",\n        \"tier\": \"ghost:tier\",\n        \"createdAt\": {\n          \"@id\":\
  \ \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Webhook\": {\n      \"@id\": \"ghost:Webhook\",\n      \"@context\": {\n        \"event\": \"ghost:event\",\n        \"targetUrl\": {\n          \"@id\": \"ghost:targetUrl\",\n          \"@type\": \"@id\"\n        },\n        \"name\": \"schema:name\",\n        \"status\": \"ghost:webhookStatus\",\n        \"lastTriggeredAt\": {\n          \"@id\": \"ghost:lastTriggeredAt\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/ghost/refs/heads/main/json-ld/ghost-context.jsonld
tags:
- Content Management
- Publishing
- Headless CMS
- Blogging
- Newsletters
- Memberships
- JSON-LD
- Linked Data
- Semantic Web
---
