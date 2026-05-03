---
api_specs:
- filename: swetrix-events-api-openapi.yml
  format: yaml
  label: Swetrix Events API
  slug: swetrix-events-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/swetrix/refs/heads/main/openapi/swetrix-events-api-openapi.yml
- filename: swetrix-statistics-api-openapi.yml
  format: yaml
  label: Swetrix Statistics API
  slug: swetrix-statistics-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/swetrix/refs/heads/main/openapi/swetrix-statistics-api-openapi.yml
- filename: swetrix-admin-api-openapi.yml
  format: yaml
  label: Swetrix Admin API
  slug: swetrix-admin-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/swetrix/refs/heads/main/openapi/swetrix-admin-api-openapi.yml
class_count: 30
classes:
- Project
- Session
- PageviewEvent
- CustomEvent
- ErrorEvent
- RevenueTransaction
- Funnel
- Organisation
- id
- name
- description
- active
- public
- origins
- pid
- psid
- browser
- os
- device
- locale
- referrer
- pageviews
- ev
- pg
- lc
- ref
- type
- currency
- transactionId
- steps
context_file: json-ld/swetrix-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/swetrix/refs/heads/main/json-ld/swetrix-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Swetrix from Swetrix.
layout: jsonld
name: Swetrix Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: swetrix
  uri: https://swetrix.com/vocab#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: created
  type: dateTime
- container: ''
  name: modified
  type: dateTime
- container: ''
  name: country
  type: schema:Country
- container: ''
  name: duration
  type: integer
- container: ''
  name: amount
  type: decimal
- container: ''
  name: conversionRate
  type: decimal
property_count: 6
provider_name: Swetrix
provider_slug: swetrix
slug: swetrix-context
source_filename: swetrix-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"swetrix\": \"https://swetrix.com/vocab#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Project\": \"swetrix:Project\",\n    \"Session\": \"swetrix:Session\",\n    \"PageviewEvent\": \"swetrix:PageviewEvent\",\n    \"CustomEvent\": \"swetrix:CustomEvent\",\n    \"ErrorEvent\": \"swetrix:ErrorEvent\",\n    \"RevenueTransaction\": \"swetrix:RevenueTransaction\",\n    \"Funnel\": \"swetrix:Funnel\",\n    \"Organisation\": \"schema:Organization\",\n\n    \"id\": \"@id\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"created\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"modified\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"active\": \"swetrix:active\",\n    \"public\": \"swetrix:isPublic\",\n    \"origins\": \"swetrix:allowedOrigins\"\
  ,\n    \"pid\": \"swetrix:projectId\",\n    \"psid\": \"swetrix:sessionId\",\n\n    \"browser\": \"swetrix:browser\",\n    \"os\": \"swetrix:operatingSystem\",\n    \"country\": {\n      \"@id\": \"schema:addressCountry\",\n      \"@type\": \"schema:Country\"\n    },\n    \"device\": \"swetrix:device\",\n    \"locale\": \"schema:inLanguage\",\n    \"referrer\": \"schema:isBasedOn\",\n    \"duration\": {\n      \"@id\": \"schema:duration\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"pageviews\": \"swetrix:pageviewCount\",\n\n    \"ev\": \"swetrix:eventName\",\n    \"pg\": \"swetrix:pagePath\",\n    \"lc\": \"schema:inLanguage\",\n    \"ref\": \"schema:isBasedOn\",\n\n    \"type\": \"schema:additionalType\",\n    \"amount\": {\n      \"@id\": \"schema:price\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"currency\": \"schema:priceCurrency\",\n    \"transactionId\": \"schema:orderNumber\",\n\n    \"steps\": \"swetrix:funnelSteps\",\n    \"conversionRate\": {\n      \"@id\": \"swetrix:conversionRate\"\
  ,\n      \"@type\": \"xsd:decimal\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/swetrix/refs/heads/main/json-ld/swetrix-context.jsonld
tags:
- Analytics
- Cookieless Tracking
- GDPR Compliant
- Open Source
- Privacy
- Real-Time Analytics
- Web Analytics
- JSON-LD
- Linked Data
- Semantic Web
---
