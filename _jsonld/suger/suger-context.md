---
api_specs:
- filename: suger-openapi.yml
  format: yaml
  label: Suger API
  slug: suger
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/suger/refs/heads/main/openapi/suger-openapi.yml
class_count: 16
classes:
- id
- orgId
- name
- description
- status
- partner
- fulfillmentUrl
- buyerId
- productId
- offerId
- price
- currency
- startTime
- endTime
- createdAt
- updatedAt
context_file: json-ld/suger-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/suger/refs/heads/main/json-ld/suger-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Suger from Suger.
layout: jsonld
name: Suger Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: suger
  uri: https://api.suger.cloud/vocab#
properties:
- container: ''
  name: Product
  type: reference
- container: ''
  name: Offer
  type: reference
- container: ''
  name: Entitlement
  type: reference
- container: ''
  name: Buyer
  type: reference
- container: ''
  name: Invoice
  type: reference
- container: ''
  name: UsageRecordGroup
  type: reference
- container: ''
  name: BillableMetric
  type: reference
property_count: 7
provider_name: Suger
provider_slug: suger
slug: suger-context
source_filename: suger-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"suger\": \"https://api.suger.cloud/vocab#\",\n\n    \"Product\": {\n      \"@id\": \"suger:Product\",\n      \"@type\": \"@id\",\n      \"schema:sameAs\": \"schema:Product\"\n    },\n    \"Offer\": {\n      \"@id\": \"suger:Offer\",\n      \"@type\": \"@id\",\n      \"schema:sameAs\": \"schema:Offer\"\n    },\n    \"Entitlement\": {\n      \"@id\": \"suger:Entitlement\",\n      \"@type\": \"@id\"\n    },\n    \"Buyer\": {\n      \"@id\": \"suger:Buyer\",\n      \"@type\": \"@id\",\n      \"schema:sameAs\": \"schema:Organization\"\n    },\n    \"Invoice\": {\n      \"@id\": \"suger:Invoice\",\n      \"@type\": \"@id\",\n      \"schema:sameAs\": \"schema:Invoice\"\n    },\n    \"UsageRecordGroup\": {\n      \"@id\": \"suger:UsageRecordGroup\",\n      \"@type\": \"@id\"\n    },\n    \"BillableMetric\": {\n      \"@id\": \"suger:BillableMetric\",\n      \"@type\": \"@id\"\n    },\n\n \
  \   \"id\": \"@id\",\n    \"orgId\": \"suger:orgId\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"status\": \"suger:status\",\n    \"partner\": \"suger:partner\",\n    \"fulfillmentUrl\": \"schema:url\",\n    \"buyerId\": \"suger:buyerId\",\n    \"productId\": \"suger:productId\",\n    \"offerId\": \"suger:offerId\",\n    \"price\": \"schema:price\",\n    \"currency\": \"schema:priceCurrency\",\n    \"startTime\": \"schema:startDate\",\n    \"endTime\": \"schema:endDate\",\n    \"createdAt\": \"schema:dateCreated\",\n    \"updatedAt\": \"schema:dateModified\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/suger/refs/heads/main/json-ld/suger-context.jsonld
tags:
- Cloud Marketplace
- GTM
- SaaS
- Billing
- Entitlement
- Revenue
- Co-Sell
- JSON-LD
- Linked Data
- Semantic Web
---
