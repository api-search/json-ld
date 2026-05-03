---
api_specs:
- filename: reuters-connect-api-openapi.yml
  format: yaml
  label: Reuters Connect API
  slug: reuters-connect-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/reuters/refs/heads/main/openapi/reuters-connect-api-openapi.yml
class_count: 28
classes:
- id
- type
- Item
- TextItem
- ImageItem
- VideoItem
- GraphicItem
- CompositeItem
- Channel
- Rendition
- Subject
- Association
- SearchResult
- headline
- slug
- byline
- dateline
- language
- body
- description
- name
- alias
- category
- code
- mimetype
- format
- query
- authToken
context_file: json-ld/reuters-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/reuters/refs/heads/main/json-ld/reuters-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Reuters from Reuters.
layout: jsonld
name: Reuters Context
namespaces:
- prefix: reuters
  uri: https://ns.reuters.com/connect/
- prefix: iptc
  uri: http://iptc.org/std/nar/2006-10-01/
- prefix: nitf
  uri: http://iptc.org/std/NITF/2006-10-18/
- prefix: rnews
  uri: http://iptc.org/std/rNews/2011-10-07#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
properties:
- container: ''
  name: guid
  type: string
- container: ''
  name: version
  type: string
- container: ''
  name: dateCreated
  type: dateTime
- container: ''
  name: dateModified
  type: dateTime
- container: ''
  name: lastUpdated
  type: dateTime
- container: ''
  name: mediaType
  type: string
- container: ''
  name: urgency
  type: integer
- container: ''
  name: channel
  type: reference
- container: set
  name: subjects
  type: ''
- container: set
  name: renditions
  type: ''
- container: ''
  name: href
  type: reference
- container: ''
  name: width
  type: integer
- container: ''
  name: height
  type: integer
- container: ''
  name: sizeinbytes
  type: integer
- container: ''
  name: duration
  type: decimal
- container: set
  name: associations
  type: ''
- container: list
  name: results
  type: ''
- container: ''
  name: totalResults
  type: integer
- container: ''
  name: url
  type: reference
- container: ''
  name: provider
  type: reference
property_count: 20
provider_name: Reuters
provider_slug: reuters
slug: reuters-context
source_filename: reuters-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"reuters\": \"https://ns.reuters.com/connect/\",\n    \"iptc\": \"http://iptc.org/std/nar/2006-10-01/\",\n    \"nitf\": \"http://iptc.org/std/NITF/2006-10-18/\",\n    \"rnews\": \"http://iptc.org/std/rNews/2011-10-07#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n\n    \"id\": \"@id\",\n    \"type\": \"@type\",\n\n    \"Item\": \"rnews:Article\",\n    \"TextItem\": \"schema:NewsArticle\",\n    \"ImageItem\": \"schema:ImageObject\",\n    \"VideoItem\": \"schema:VideoObject\",\n    \"GraphicItem\": \"schema:ImageObject\",\n    \"CompositeItem\": \"schema:CreativeWork\",\n    \"Channel\": \"reuters:Channel\",\n    \"Rendition\": \"schema:MediaObject\",\n    \"Subject\": \"reuters:Subject\",\n    \"Association\": \"reuters:Association\",\n    \"SearchResult\": \"schema:ItemList\",\n\n    \"guid\": {\n      \"\
  @id\": \"dcterms:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"version\": {\n      \"@id\": \"schema:version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"headline\": \"schema:headline\",\n    \"slug\": \"reuters:slug\",\n    \"dateCreated\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"dateModified\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"lastUpdated\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"mediaType\": {\n      \"@id\": \"schema:encodingFormat\",\n      \"@type\": \"xsd:string\"\n    },\n    \"urgency\": {\n      \"@id\": \"reuters:urgency\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"byline\": \"schema:author\",\n    \"dateline\": \"reuters:dateline\",\n    \"language\": \"schema:inLanguage\",\n    \"body\": \"schema:articleBody\",\n    \"description\": \"schema:description\",\n    \"name\": \"schema:name\"\
  ,\n\n    \"channel\": {\n      \"@id\": \"reuters:channel\",\n      \"@type\": \"@id\"\n    },\n    \"alias\": \"reuters:channelAlias\",\n    \"category\": \"reuters:channelCategory\",\n\n    \"subjects\": {\n      \"@id\": \"schema:about\",\n      \"@container\": \"@set\"\n    },\n    \"code\": \"reuters:subjectCode\",\n\n    \"renditions\": {\n      \"@id\": \"schema:encoding\",\n      \"@container\": \"@set\"\n    },\n    \"href\": {\n      \"@id\": \"schema:contentUrl\",\n      \"@type\": \"@id\"\n    },\n    \"mimetype\": \"schema:encodingFormat\",\n    \"width\": {\n      \"@id\": \"schema:width\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"height\": {\n      \"@id\": \"schema:height\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"sizeinbytes\": {\n      \"@id\": \"schema:contentSize\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"duration\": {\n      \"@id\": \"schema:duration\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"format\": \"reuters:format\",\n\n   \
  \ \"associations\": {\n      \"@id\": \"schema:associatedMedia\",\n      \"@container\": \"@set\"\n    },\n\n    \"results\": {\n      \"@id\": \"schema:itemListElement\",\n      \"@container\": \"@list\"\n    },\n    \"totalResults\": {\n      \"@id\": \"schema:numberOfItems\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"query\": \"reuters:searchQuery\",\n\n    \"authToken\": \"reuters:authToken\",\n\n    \"url\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    },\n    \"provider\": {\n      \"@id\": \"schema:provider\",\n      \"@type\": \"@id\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/reuters/refs/heads/main/json-ld/reuters-context.jsonld
tags:
- Business
- Finance
- Journalism
- Media
- News
- Wire Service
- JSON-LD
- Linked Data
- Semantic Web
---
