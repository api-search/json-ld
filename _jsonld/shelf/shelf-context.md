---
class_count: 4
classes:
- name
- description
- url
- identifier
context_file: json-ld/shelf-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/shelf/refs/heads/main/json-ld/shelf-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Shelf from Shelf.io.
layout: jsonld
name: Shelf Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: shelf
  uri: https://api-evangelist.github.io/shelf/vocab#
properties:
- container: ''
  name: Gem
  type: reference
- container: ''
  name: gemId
  type: schema:Text
- container: ''
  name: gemTitle
  type: schema:Text
- container: ''
  name: gemContent
  type: schema:Text
- container: ''
  name: gemStatus
  type: schema:Text
- container: ''
  name: tags
  type: schema:Text
- container: ''
  name: KnowledgeBase
  type: reference
- container: ''
  name: knowledgeBaseId
  type: schema:Text
- container: ''
  name: DecisionTree
  type: reference
- container: ''
  name: treeId
  type: schema:Text
- container: ''
  name: treeTitle
  type: schema:Text
- container: ''
  name: SearchResult
  type: reference
- container: ''
  name: query
  type: schema:Text
- container: ''
  name: results
  type: reference
- container: ''
  name: confidence
  type: schema:Number
- container: ''
  name: User
  type: reference
- container: ''
  name: userId
  type: schema:Text
- container: ''
  name: email
  type: schema:Text
- container: ''
  name: role
  type: schema:Text
- container: ''
  name: WebhookEvent
  type: reference
- container: ''
  name: eventType
  type: schema:Text
- container: ''
  name: eventTimestamp
  type: schema:DateTime
- container: ''
  name: payload
  type: reference
property_count: 23
provider_name: Shelf.io
provider_slug: shelf
slug: shelf-context
source_filename: shelf-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"shelf\": \"https://api-evangelist.github.io/shelf/vocab#\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"identifier\": \"schema:identifier\",\n    \"Gem\": {\n      \"@id\": \"shelf:Gem\",\n      \"@type\": \"@id\"\n    },\n    \"gemId\": {\n      \"@id\": \"shelf:gemId\",\n      \"@type\": \"schema:Text\"\n    },\n    \"gemTitle\": {\n      \"@id\": \"schema:headline\",\n      \"@type\": \"schema:Text\"\n    },\n    \"gemContent\": {\n      \"@id\": \"schema:text\",\n      \"@type\": \"schema:Text\"\n    },\n    \"gemStatus\": {\n      \"@id\": \"shelf:gemStatus\",\n      \"@type\": \"schema:Text\"\n    },\n    \"tags\": {\n      \"@id\": \"schema:keywords\",\n      \"@type\": \"schema:Text\"\n    },\n    \"KnowledgeBase\": {\n      \"@id\": \"schema:Dataset\",\n      \"@type\": \"@id\"\n    },\n    \"knowledgeBaseId\"\
  : {\n      \"@id\": \"shelf:knowledgeBaseId\",\n      \"@type\": \"schema:Text\"\n    },\n    \"DecisionTree\": {\n      \"@id\": \"shelf:DecisionTree\",\n      \"@type\": \"@id\"\n    },\n    \"treeId\": {\n      \"@id\": \"shelf:treeId\",\n      \"@type\": \"schema:Text\"\n    },\n    \"treeTitle\": {\n      \"@id\": \"schema:headline\",\n      \"@type\": \"schema:Text\"\n    },\n    \"SearchResult\": {\n      \"@id\": \"schema:SearchResultsPage\",\n      \"@type\": \"@id\"\n    },\n    \"query\": {\n      \"@id\": \"schema:query\",\n      \"@type\": \"schema:Text\"\n    },\n    \"results\": {\n      \"@id\": \"schema:result\",\n      \"@type\": \"@id\"\n    },\n    \"confidence\": {\n      \"@id\": \"shelf:confidence\",\n      \"@type\": \"schema:Number\"\n    },\n    \"User\": {\n      \"@id\": \"schema:Person\",\n      \"@type\": \"@id\"\n    },\n    \"userId\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"schema:Text\"\n    },\n    \"email\": {\n      \"@id\": \"\
  schema:email\",\n      \"@type\": \"schema:Text\"\n    },\n    \"role\": {\n      \"@id\": \"schema:roleName\",\n      \"@type\": \"schema:Text\"\n    },\n    \"WebhookEvent\": {\n      \"@id\": \"schema:Event\",\n      \"@type\": \"@id\"\n    },\n    \"eventType\": {\n      \"@id\": \"shelf:eventType\",\n      \"@type\": \"schema:Text\"\n    },\n    \"eventTimestamp\": {\n      \"@id\": \"schema:startDate\",\n      \"@type\": \"schema:DateTime\"\n    },\n    \"payload\": {\n      \"@id\": \"schema:additionalProperty\",\n      \"@type\": \"@id\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/shelf/refs/heads/main/json-ld/shelf-context.jsonld
tags:
- Artificial Intelligence
- Contact Center
- Knowledge Management
- SaaS
- Search
- JSON-LD
- Linked Data
- Semantic Web
---
