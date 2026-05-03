---
class_count: 18
classes:
- Article
- NewsArticle
- title
- description
- link
- pubDate
- author
- category
- guid
- content
- thumbnail
- enclosure
- RSSFeed
- feedUrl
- feedCategory
- Organization
- Publication
- publisher
context_file: json-ld/wired-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/wired/refs/heads/main/json-ld/wired-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Wired from Wired.
layout: jsonld
name: Wired Context
namespaces:
- prefix: wired
  uri: https://www.wired.com/vocab/
properties:
- container: ''
  name: Wired
  type: schema:Periodical
property_count: 1
provider_name: Wired
provider_slug: wired
slug: wired-context
source_filename: wired-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"wired\": \"https://www.wired.com/vocab/\",\n    \"Article\": \"schema:Article\",\n    \"NewsArticle\": \"schema:NewsArticle\",\n    \"title\": \"schema:headline\",\n    \"description\": \"schema:description\",\n    \"link\": \"schema:url\",\n    \"pubDate\": \"schema:datePublished\",\n    \"author\": \"schema:author\",\n    \"category\": \"schema:keywords\",\n    \"guid\": \"schema:identifier\",\n    \"content\": \"schema:articleBody\",\n    \"thumbnail\": \"schema:image\",\n    \"enclosure\": \"schema:associatedMedia\",\n    \"RSSFeed\": \"wired:RSSFeed\",\n    \"feedUrl\": \"wired:feedUrl\",\n    \"feedCategory\": \"wired:feedCategory\",\n    \"Organization\": \"schema:Organization\",\n    \"Publication\": \"schema:Periodical\",\n    \"publisher\": \"schema:publisher\",\n    \"Wired\": {\n      \"@id\": \"wired:WiredMagazine\",\n      \"@type\": \"schema:Periodical\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/wired/refs/heads/main/json-ld/wired-context.jsonld
tags:
- Content
- Innovation
- Media
- News
- RSS
- Science
- Technology News
- JSON-LD
- Linked Data
- Semantic Web
---
