---
api_specs:
- filename: techcrunch-wordpress-rest-api-openapi.yml
  format: yaml
  label: TechCrunch WordPress REST API
  slug: wordpress-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/techcrunch/refs/heads/main/openapi/techcrunch-wordpress-rest-api-openapi.yml
class_count: 57
classes:
- Post
- postId
- postDate
- postModified
- postSlug
- postStatus
- postType
- postLink
- postTitle
- postContent
- postExcerpt
- postAuthor
- featuredMedia
- categories
- tags
- sticky
- format
- commentStatus
- Category
- categoryId
- categoryName
- categorySlug
- categoryDescription
- categoryLink
- categoryCount
- categoryParent
- Tag
- tagId
- tagName
- tagSlug
- tagDescription
- tagCount
- Author
- authorId
- authorName
- authorSlug
- authorDescription
- authorLink
- authorUrl
- avatarUrls
- Media
- mediaId
- mediaDate
- mediaSlug
- mediaType
- mimeType
- mediaLink
- sourceUrl
- altText
- caption
- SearchResult
- searchTitle
- searchUrl
- searchType
- RenderedValue
- rendered
- protected
context_file: json-ld/techcrunch-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/techcrunch/refs/heads/main/json-ld/techcrunch-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Techcrunch from TechCrunch.
layout: jsonld
name: Techcrunch Context
namespaces:
- prefix: wp
  uri: https://raw.githubusercontent.com/api-evangelist/techcrunch/main/json-ld/techcrunch-context.jsonld#
- prefix: schema
  uri: https://schema.org/
properties: []
property_count: 0
provider_name: TechCrunch
provider_slug: techcrunch
slug: techcrunch-context
source_filename: techcrunch-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"wp\": \"https://raw.githubusercontent.com/api-evangelist/techcrunch/main/json-ld/techcrunch-context.jsonld#\",\n    \"schema\": \"https://schema.org/\",\n\n    \"Post\": \"schema:BlogPosting\",\n    \"postId\": \"schema:identifier\",\n    \"postDate\": \"schema:datePublished\",\n    \"postModified\": \"schema:dateModified\",\n    \"postSlug\": \"schema:url\",\n    \"postStatus\": \"wp:postStatus\",\n    \"postType\": \"wp:postType\",\n    \"postLink\": \"schema:url\",\n    \"postTitle\": \"schema:headline\",\n    \"postContent\": \"schema:articleBody\",\n    \"postExcerpt\": \"schema:description\",\n    \"postAuthor\": \"schema:author\",\n    \"featuredMedia\": \"schema:image\",\n    \"categories\": \"schema:articleSection\",\n    \"tags\": \"schema:keywords\",\n    \"sticky\": \"wp:sticky\",\n    \"format\": \"wp:format\",\n    \"commentStatus\": \"wp:commentStatus\",\n\n    \"Category\": \"schema:Thing\"\
  ,\n    \"categoryId\": \"schema:identifier\",\n    \"categoryName\": \"schema:name\",\n    \"categorySlug\": \"wp:slug\",\n    \"categoryDescription\": \"schema:description\",\n    \"categoryLink\": \"schema:url\",\n    \"categoryCount\": \"wp:count\",\n    \"categoryParent\": \"schema:isPartOf\",\n\n    \"Tag\": \"schema:DefinedTerm\",\n    \"tagId\": \"schema:identifier\",\n    \"tagName\": \"schema:name\",\n    \"tagSlug\": \"wp:slug\",\n    \"tagDescription\": \"schema:description\",\n    \"tagCount\": \"wp:count\",\n\n    \"Author\": \"schema:Person\",\n    \"authorId\": \"schema:identifier\",\n    \"authorName\": \"schema:name\",\n    \"authorSlug\": \"wp:slug\",\n    \"authorDescription\": \"schema:description\",\n    \"authorLink\": \"schema:url\",\n    \"authorUrl\": \"schema:sameAs\",\n    \"avatarUrls\": \"schema:image\",\n\n    \"Media\": \"schema:MediaObject\",\n    \"mediaId\": \"schema:identifier\",\n    \"mediaDate\": \"schema:datePublished\",\n    \"mediaSlug\": \"wp:slug\"\
  ,\n    \"mediaType\": \"schema:encodingFormat\",\n    \"mimeType\": \"schema:encodingFormat\",\n    \"mediaLink\": \"schema:url\",\n    \"sourceUrl\": \"schema:contentUrl\",\n    \"altText\": \"schema:alternateName\",\n    \"caption\": \"schema:caption\",\n\n    \"SearchResult\": \"schema:SearchResultsPage\",\n    \"searchTitle\": \"schema:name\",\n    \"searchUrl\": \"schema:url\",\n    \"searchType\": \"schema:additionalType\",\n\n    \"RenderedValue\": \"wp:RenderedValue\",\n    \"rendered\": \"wp:rendered\",\n    \"protected\": \"wp:protected\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/techcrunch/refs/heads/main/json-ld/techcrunch-context.jsonld
tags:
- Media
- News
- Startups
- Technology News
- Venture Capital
- JSON-LD
- Linked Data
- Semantic Web
---
