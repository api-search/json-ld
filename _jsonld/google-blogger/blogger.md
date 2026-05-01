---
api_specs:
- filename: blogger.yml
  format: yaml
  label: Google Blogger API V3
  slug: google-blogger
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-blogger/refs/heads/main/openapi/blogger.yml
class_count: 16
classes:
- Blog
- Post
- Page
- Comment
- User
- id
- title
- content
- author
- displayName
- labels
- replies
- totalItems
- description
- about
- name
context_file: json-ld/blogger.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-blogger/refs/heads/main/json-ld/blogger.jsonld
description: JSON-LD context defining the semantic vocabulary for Blogger from Google Blogger.
layout: jsonld
name: Blogger Context
namespaces:
- prefix: blogger
  uri: https://www.googleapis.com/blogger/v3/
properties:
- container: ''
  name: published
  type: schema:DateTime
- container: ''
  name: updated
  type: schema:DateTime
- container: ''
  name: url
  type: reference
property_count: 3
provider_name: Google Blogger
provider_slug: google-blogger
slug: blogger
source_filename: blogger.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"blogger\": \"https://www.googleapis.com/blogger/v3/\",\n    \"Blog\": \"schema:Blog\",\n    \"Post\": \"schema:BlogPosting\",\n    \"Page\": \"schema:WebPage\",\n    \"Comment\": \"schema:Comment\",\n    \"User\": \"schema:Person\",\n    \"id\": \"schema:identifier\",\n    \"title\": \"schema:headline\",\n    \"content\": \"schema:articleBody\",\n    \"published\": {\n      \"@id\": \"schema:datePublished\",\n      \"@type\": \"schema:DateTime\"\n    },\n    \"updated\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"schema:DateTime\"\n    },\n    \"url\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    },\n    \"author\": \"schema:author\",\n    \"displayName\": \"schema:name\",\n    \"labels\": \"schema:keywords\",\n    \"replies\": \"schema:comment\",\n    \"totalItems\": \"schema:commentCount\",\n    \"description\": \"schema:description\",\n    \"about\": \"schema:description\"\
  ,\n    \"name\": \"schema:name\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-blogger/refs/heads/main/json-ld/blogger.jsonld
tags:
- Blogging
- CMS
- Comments
- Google
- Pages
- Posts
- Publishing
- JSON-LD
- Linked Data
- Semantic Web
---
