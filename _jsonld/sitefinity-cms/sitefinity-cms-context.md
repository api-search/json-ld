---
api_specs:
- filename: sitefinity-cms-content-api-openapi.yml
  format: yaml
  label: Sitefinity CMS Content API
  slug: content-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sitefinity-cms/refs/heads/main/openapi/sitefinity-cms-content-api-openapi.yml
class_count: 24
classes:
- ContentItem
- Page
- MediaItem
- Role
- TaxonomyItem
- Id
- Title
- Content
- Summary
- Status
- Author
- UrlName
- Tags
- Category
- Language
- FileName
- MimeType
- TotalSize
- MediaUrl
- AlternativeText
- NewsItem
- BlogPost
- Event
- Library
context_file: json-ld/sitefinity-cms-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/sitefinity-cms/refs/heads/main/json-ld/sitefinity-cms-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Sitefinity Cms from Sitefinity CMS.
layout: jsonld
name: Sitefinity Cms Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: sitefinity
  uri: https://www.progress.com/sitefinity-cms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: PublicationDate
  type: dateTime
- container: ''
  name: LastModified
  type: dateTime
property_count: 2
provider_name: Sitefinity CMS
provider_slug: sitefinity-cms
slug: sitefinity-cms-context
source_filename: sitefinity-cms-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"sitefinity\": \"https://www.progress.com/sitefinity-cms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"ContentItem\": \"sitefinity:ContentItem\",\n    \"Page\": \"schema:WebPage\",\n    \"MediaItem\": \"schema:MediaObject\",\n    \"Role\": \"schema:Role\",\n    \"TaxonomyItem\": \"sitefinity:TaxonomyItem\",\n\n    \"Id\": \"@id\",\n    \"Title\": \"schema:name\",\n    \"Content\": \"schema:articleBody\",\n    \"Summary\": \"schema:description\",\n    \"Status\": \"sitefinity:publicationStatus\",\n    \"PublicationDate\": {\n      \"@id\": \"schema:datePublished\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"LastModified\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"Author\": \"schema:author\",\n    \"UrlName\": \"schema:slug\",\n    \"Tags\": \"schema:keywords\",\n    \"Category\": \"schema:about\",\n    \"\
  Language\": \"schema:inLanguage\",\n\n    \"FileName\": \"schema:name\",\n    \"MimeType\": \"schema:encodingFormat\",\n    \"TotalSize\": \"schema:contentSize\",\n    \"MediaUrl\": \"schema:contentUrl\",\n    \"AlternativeText\": \"schema:alternateName\",\n\n    \"NewsItem\": \"schema:NewsArticle\",\n    \"BlogPost\": \"schema:BlogPosting\",\n    \"Event\": \"schema:Event\",\n    \"Library\": \"schema:Collection\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/sitefinity-cms/refs/heads/main/json-ld/sitefinity-cms-context.jsonld
tags:
- Content Management
- Headless CMS
- .NET
- REST
- JSON-LD
- Linked Data
- Semantic Web
---
