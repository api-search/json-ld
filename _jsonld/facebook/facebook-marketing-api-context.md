---
api_specs:
- filename: facebook-graph-api.yaml
  format: yaml
  label: Facebook Graph API
  slug: facebook-graph-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/facebook/refs/heads/main/openapi/facebook-graph-api.yaml
- filename: facebook-marketing-api.yaml
  format: yaml
  label: Facebook Marketing API
  slug: facebook-marketing-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/facebook/refs/heads/main/openapi/facebook-marketing-api.yaml
- filename: facebook-instagram-api.yaml
  format: yaml
  label: Instagram API
  slug: instagram-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/facebook/refs/heads/main/openapi/facebook-instagram-api.yaml
- filename: facebook-messenger-api.yaml
  format: yaml
  label: Messenger Platform API
  slug: messenger-platform-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/facebook/refs/heads/main/openapi/facebook-messenger-api.yaml
- filename: facebook-threads-api.yaml
  format: yaml
  label: Threads API
  slug: threads-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/facebook/refs/heads/main/openapi/facebook-threads-api.yaml
- filename: facebook-whatsapp-api.yaml
  format: yaml
  label: WhatsApp Business API
  slug: whatsapp-business-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/facebook/refs/heads/main/openapi/facebook-whatsapp-api.yaml
class_count: 6
classes:
- AdAccount
- Campaign
- AdSet
- Ad
- Insight
- CustomAudience
context_file: json-ld/facebook-marketing-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/facebook/refs/heads/main/json-ld/facebook-marketing-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Facebook Marketing Api from Facebook.
layout: jsonld
name: Facebook Marketing Api Context
namespaces:
- prefix: fb
  uri: https://developers.facebook.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: name
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: currency
  type: string
- container: ''
  name: balance
  type: string
- container: ''
  name: objective
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: dailyBudget
  type: string
- container: ''
  name: impressions
  type: string
- container: ''
  name: clicks
  type: string
- container: ''
  name: spend
  type: string
- container: ''
  name: cpc
  type: string
- container: ''
  name: ctr
  type: string
- container: ''
  name: reach
  type: string
- container: ''
  name: approximateCount
  type: integer
property_count: 14
provider_name: Facebook
provider_slug: facebook
slug: facebook-marketing-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"fb\": \"https://developers.facebook.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AdAccount\": \"fb:AdAccount\",\n    \"Campaign\": \"fb:Campaign\",\n    \"AdSet\": \"fb:AdSet\",\n    \"Ad\": \"fb:Ad\",\n    \"Insight\": \"fb:Insight\",\n    \"CustomAudience\": \"fb:CustomAudience\",\n    \"name\": { \"@id\": \"schema:name\", \"@type\": \"xsd:string\" },\n    \"description\": { \"@id\": \"schema:description\", \"@type\": \"xsd:string\" },\n    \"currency\": { \"@id\": \"fb:currency\", \"@type\": \"xsd:string\" },\n    \"balance\": { \"@id\": \"fb:balance\", \"@type\": \"xsd:string\" },\n    \"objective\": { \"@id\": \"fb:objective\", \"@type\": \"xsd:string\" },\n    \"status\": { \"@id\": \"fb:status\", \"@type\": \"xsd:string\" },\n    \"dailyBudget\": { \"@id\": \"fb:daily_budget\", \"@type\": \"xsd:string\"\
  \ },\n    \"impressions\": { \"@id\": \"fb:impressions\", \"@type\": \"xsd:string\" },\n    \"clicks\": { \"@id\": \"fb:clicks\", \"@type\": \"xsd:string\" },\n    \"spend\": { \"@id\": \"fb:spend\", \"@type\": \"xsd:string\" },\n    \"cpc\": { \"@id\": \"fb:cpc\", \"@type\": \"xsd:string\" },\n    \"ctr\": { \"@id\": \"fb:ctr\", \"@type\": \"xsd:string\" },\n    \"reach\": { \"@id\": \"fb:reach\", \"@type\": \"xsd:string\" },\n    \"approximateCount\": { \"@id\": \"fb:approximate_count\", \"@type\": \"xsd:integer\" }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/facebook/refs/heads/main/json-ld/facebook-marketing-api-context.jsonld
tags:
- Advertising
- Content Publishing
- Messaging
- Social Media
- Social Networking
- JSON-LD
- Linked Data
- Semantic Web
---
