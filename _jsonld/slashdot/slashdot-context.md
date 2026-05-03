---
api_specs:
- filename: slashdot-rss-openapi.yml
  format: yaml
  label: Slashdot RSS/Atom Feeds
  slug: rss-feeds
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/slashdot/refs/heads/main/openapi/slashdot-rss-openapi.yml
class_count: 0
classes: []
context_file: json-ld/slashdot-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/slashdot/refs/heads/main/json-ld/slashdot-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Slashdot from Slashdot.
layout: jsonld
name: Slashdot Context
namespaces:
- prefix: slashdot
  uri: https://slashdot.org/vocab#
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: rss
  uri: http://purl.org/rss/1.0/
- prefix: sioc
  uri: http://rdfs.org/sioc/ns#
properties:
- container: ''
  name: NewsArticle
  type: ''
- container: ''
  name: DiscussionThread
  type: ''
- container: ''
  name: Comment
  type: ''
- container: ''
  name: RssFeed
  type: ''
- container: ''
  name: SlashdotUser
  type: ''
property_count: 5
provider_name: Slashdot
provider_slug: slashdot
slug: slashdot-context
source_filename: slashdot-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"slashdot\": \"https://slashdot.org/vocab#\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"rss\": \"http://purl.org/rss/1.0/\",\n    \"sioc\": \"http://rdfs.org/sioc/ns#\",\n\n    \"NewsArticle\": {\n      \"@id\": \"schema:NewsArticle\",\n      \"@context\": {\n        \"headline\": {\n          \"@id\": \"schema:headline\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\"\n        },\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"datePublished\": {\n          \"@id\": \"schema:datePublished\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"dateModified\": {\n          \"@id\": \"schema:dateModified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"author\": {\n          \"@id\": \"schema:author\"\
  \n        },\n        \"publisher\": {\n          \"@id\": \"schema:publisher\"\n        },\n        \"articleSection\": {\n          \"@id\": \"schema:articleSection\"\n        },\n        \"keywords\": {\n          \"@id\": \"schema:keywords\",\n          \"@container\": \"@set\"\n        },\n        \"commentCount\": {\n          \"@id\": \"schema:commentCount\"\n        },\n        \"commentUrl\": {\n          \"@id\": \"slashdot:commentUrl\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"DiscussionThread\": {\n      \"@id\": \"sioc:Thread\",\n      \"@context\": {\n        \"title\": {\n          \"@id\": \"dcterms:title\"\n        },\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"hasReply\": {\n          \"@id\": \"sioc:has_reply\",\n          \"@container\": \"@set\"\n        },\n        \"numReplies\": {\n          \"@id\": \"sioc:num_replies\"\n        },\n        \"createdAt\": {\n          \"\
  @id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Comment\": {\n      \"@id\": \"sioc:Post\",\n      \"@context\": {\n        \"content\": {\n          \"@id\": \"sioc:content\"\n        },\n        \"author\": {\n          \"@id\": \"sioc:has_creator\"\n        },\n        \"score\": {\n          \"@id\": \"slashdot:score\"\n        },\n        \"moderation\": {\n          \"@id\": \"slashdot:moderation\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"replyTo\": {\n          \"@id\": \"sioc:reply_of\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"RssFeed\": {\n      \"@id\": \"rss:channel\",\n      \"@context\": {\n        \"title\": {\n          \"@id\": \"rss:title\"\n        },\n        \"link\": {\n          \"@id\": \"rss:link\",\n          \"@type\": \"@id\"\n        },\n        \"description\": {\n          \"\
  @id\": \"rss:description\"\n        },\n        \"items\": {\n          \"@id\": \"rss:items\",\n          \"@container\": \"@list\"\n        },\n        \"feedUrl\": {\n          \"@id\": \"slashdot:feedUrl\",\n          \"@type\": \"@id\"\n        },\n        \"section\": {\n          \"@id\": \"slashdot:section\"\n        }\n      }\n    },\n\n    \"SlashdotUser\": {\n      \"@id\": \"sioc:UserAccount\",\n      \"@context\": {\n        \"username\": {\n          \"@id\": \"sioc:name\"\n        },\n        \"uid\": {\n          \"@id\": \"schema:identifier\"\n        },\n        \"karma\": {\n          \"@id\": \"slashdot:karma\"\n        },\n        \"profileUrl\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/slashdot/refs/heads/main/json-ld/slashdot-context.jsonld
tags:
- Media
- Open Source
- Technology News
- RSS
- JSON-LD
- Linked Data
- Semantic Web
---
