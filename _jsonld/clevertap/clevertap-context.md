---
class_count: 0
classes: []
context_file: json-ld/clevertap-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/clevertap/refs/heads/main/json-ld/clevertap-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Clevertap from CleverTap.
layout: jsonld
name: Clevertap Context
namespaces:
- prefix: ct
  uri: https://clevertap.com/ns/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: Profile
  type: ''
- container: ''
  name: Event
  type: ''
- container: ''
  name: Campaign
  type: ''
- container: ''
  name: Bulletin
  type: ''
- container: ''
  name: CatalogItem
  type: ''
- container: ''
  name: CustomList
  type: ''
property_count: 6
provider_name: CleverTap
provider_slug: clevertap
slug: clevertap-context
source_filename: clevertap-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"ct\": \"https://clevertap.com/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Profile\": {\n      \"@id\": \"ct:Profile\",\n      \"@context\": {\n        \"identity\": \"schema:identifier\",\n        \"objectID\": \"ct:objectId\",\n        \"email\": \"schema:email\",\n        \"name\": \"schema:name\",\n        \"phone\": \"schema:telephone\",\n        \"properties\": \"ct:profileProperties\"\n      }\n    },\n\n    \"Event\": {\n      \"@id\": \"ct:Event\",\n      \"@context\": {\n        \"evtName\": \"schema:name\",\n        \"evtData\": \"ct:eventData\",\n        \"ts\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"identity\": \"schema:identifier\"\n      }\n    },\n\n    \"Campaign\": {\n      \"@id\": \"ct:Campaign\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"\
  name\": \"schema:name\",\n        \"channel\": \"ct:channel\",\n        \"type\": \"schema:additionalType\",\n        \"status\": \"ct:status\",\n        \"schedule\": \"schema:scheduledTime\"\n      }\n    },\n\n    \"Bulletin\": {\n      \"@id\": \"ct:Bulletin\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"data\": \"ct:bulletinData\"\n      }\n    },\n\n    \"CatalogItem\": {\n      \"@id\": \"schema:Product\",\n      \"@context\": {\n        \"id\": \"schema:productID\",\n        \"name\": \"schema:name\",\n        \"price\": \"schema:price\",\n        \"image\": \"schema:image\",\n        \"url\": \"schema:url\"\n      }\n    },\n\n    \"CustomList\": {\n      \"@id\": \"ct:CustomList\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"members\": \"ct:members\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/clevertap/refs/heads/main/json-ld/clevertap-context.jsonld
tags:
- Audiences
- Customer Engagement
- Customer Retention
- Marketing Automation
- Mobile Engagement
- Push Notifications
- User Behavior
- JSON-LD
- Linked Data
- Semantic Web
---
