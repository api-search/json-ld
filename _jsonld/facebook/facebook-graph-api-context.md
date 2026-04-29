---
class_count: 5
classes:
- User
- Post
- Page
- Photo
- Comment
context_file: json-ld/facebook-graph-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/facebook/refs/heads/main/json-ld/facebook-graph-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Facebook Graph Api from Facebook.
layout: jsonld
name: Facebook Graph Api Context
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
  name: email
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: message
  type: string
- container: ''
  name: createdTime
  type: dateTime
- container: ''
  name: updatedTime
  type: dateTime
- container: ''
  name: link
  type: reference
- container: ''
  name: permalinkUrl
  type: reference
- container: ''
  name: category
  type: string
- container: ''
  name: fanCount
  type: integer
- container: ''
  name: website
  type: reference
- container: ''
  name: likeCount
  type: integer
- container: ''
  name: width
  type: integer
- container: ''
  name: height
  type: integer
property_count: 14
provider_name: Facebook
provider_slug: facebook
slug: facebook-graph-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"fb\": \"https://developers.facebook.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"User\": \"fb:User\",\n    \"Post\": \"fb:Post\",\n    \"Page\": \"fb:Page\",\n    \"Photo\": \"fb:Photo\",\n    \"Comment\": \"fb:Comment\",\n    \"name\": { \"@id\": \"schema:name\", \"@type\": \"xsd:string\" },\n    \"email\": { \"@id\": \"schema:email\", \"@type\": \"xsd:string\" },\n    \"description\": { \"@id\": \"schema:description\", \"@type\": \"xsd:string\" },\n    \"message\": { \"@id\": \"fb:message\", \"@type\": \"xsd:string\" },\n    \"createdTime\": { \"@id\": \"schema:dateCreated\", \"@type\": \"xsd:dateTime\" },\n    \"updatedTime\": { \"@id\": \"schema:dateModified\", \"@type\": \"xsd:dateTime\" },\n    \"link\": { \"@id\": \"fb:link\", \"@type\": \"@id\" },\n    \"permalinkUrl\": { \"@id\": \"fb:permalink_url\"\
  , \"@type\": \"@id\" },\n    \"category\": { \"@id\": \"fb:category\", \"@type\": \"xsd:string\" },\n    \"fanCount\": { \"@id\": \"fb:fan_count\", \"@type\": \"xsd:integer\" },\n    \"website\": { \"@id\": \"schema:url\", \"@type\": \"@id\" },\n    \"likeCount\": { \"@id\": \"fb:like_count\", \"@type\": \"xsd:integer\" },\n    \"width\": { \"@id\": \"fb:width\", \"@type\": \"xsd:integer\" },\n    \"height\": { \"@id\": \"fb:height\", \"@type\": \"xsd:integer\" }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/facebook/refs/heads/main/json-ld/facebook-graph-api-context.jsonld
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
