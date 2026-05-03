---
class_count: 12
classes:
- Article
- Feed
- Author
- Organization
- title
- description
- author
- category
- guid
- enclosure
- feedTitle
- feedDescription
context_file: json-ld/the-next-web-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/the-next-web/refs/heads/main/json-ld/the-next-web-context.jsonld
description: JSON-LD context defining the semantic vocabulary for The Next Web from The Next Web.
layout: jsonld
name: The Next Web Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: rss
  uri: http://www.rssboard.org/rss-specification#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dc
  uri: http://purl.org/dc/elements/1.1/
- prefix: thenextweb
  uri: https://thenextweb.com/
properties:
- container: ''
  name: link
  type: reference
- container: ''
  name: pubDate
  type: dateTime
- container: ''
  name: feedUrl
  type: reference
- container: ''
  name: lastBuildDate
  type: dateTime
property_count: 4
provider_name: The Next Web
provider_slug: the-next-web
slug: the-next-web-context
source_filename: the-next-web-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"rss\": \"http://www.rssboard.org/rss-specification#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dc\": \"http://purl.org/dc/elements/1.1/\",\n\n    \"Article\": \"schema:NewsArticle\",\n    \"Feed\": \"schema:DataFeed\",\n    \"Author\": \"schema:Person\",\n    \"Organization\": \"schema:NewsMediaOrganization\",\n\n    \"title\": \"schema:headline\",\n    \"link\": { \"@id\": \"schema:url\", \"@type\": \"@id\" },\n    \"description\": \"schema:description\",\n    \"pubDate\": { \"@id\": \"schema:datePublished\", \"@type\": \"xsd:dateTime\" },\n    \"author\": \"schema:author\",\n    \"category\": \"schema:articleSection\",\n    \"guid\": \"schema:identifier\",\n    \"enclosure\": \"schema:image\",\n\n    \"thenextweb\": \"https://thenextweb.com/\",\n    \"feedUrl\": { \"@id\": \"schema:url\", \"@type\": \"@id\" },\n    \"feedTitle\": \"schema:name\",\n    \"feedDescription\"\
  : \"schema:description\",\n    \"lastBuildDate\": { \"@id\": \"schema:dateModified\", \"@type\": \"xsd:dateTime\" }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/the-next-web/refs/heads/main/json-ld/the-next-web-context.jsonld
tags:
- Technology News
- Innovation
- Media
- Events
- Startups
- Artificial Intelligence
- JSON-LD
- Linked Data
- Semantic Web
---
