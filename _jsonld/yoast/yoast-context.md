---
api_specs:
- filename: yoast-rest-openapi.yml
  format: yaml
  label: Yoast REST API
  slug: yoast-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/yoast/refs/heads/main/openapi/yoast-rest-openapi.yml
class_count: 5
classes:
- SeoMetadata
- SeoHeadResponse
- RobotsDirectives
- OpenGraphMetadata
- TwitterCardMetadata
context_file: json-ld/yoast-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/yoast/refs/heads/main/json-ld/yoast-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Yoast from Yoast.
layout: jsonld
name: Yoast Context
namespaces:
- prefix: yoast
  uri: https://developer.yoast.com/vocabulary#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: schema
  type: '@json'
- container: ''
  name: title
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: canonical
  type: reference
- container: ''
  name: robots
  type: yoast:RobotsDirectives
- container: ''
  name: index
  type: string
- container: ''
  name: follow
  type: string
- container: ''
  name: og_locale
  type: string
- container: ''
  name: og_type
  type: string
- container: ''
  name: og_title
  type: string
- container: ''
  name: og_description
  type: string
- container: ''
  name: og_url
  type: reference
- container: ''
  name: og_site_name
  type: string
- container: set
  name: og_image
  type: ''
- container: ''
  name: twitter_card
  type: string
- container: ''
  name: twitter_title
  type: string
- container: ''
  name: twitter_description
  type: string
- container: ''
  name: twitter_image
  type: reference
- container: ''
  name: article_published_time
  type: dateTime
- container: ''
  name: article_modified_time
  type: dateTime
- container: ''
  name: author
  type: string
- container: ''
  name: html
  type: string
- container: ''
  name: json
  type: yoast:SeoMetadata
- container: ''
  name: status
  type: integer
- container: ''
  name: yoast_head
  type: string
- container: ''
  name: yoast_head_json
  type: yoast:SeoMetadata
property_count: 26
provider_name: Yoast
provider_slug: yoast
slug: yoast-context
source_filename: yoast-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"yoast\": \"https://developer.yoast.com/vocabulary#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"SeoMetadata\": \"yoast:SeoMetadata\",\n    \"SeoHeadResponse\": \"yoast:SeoHeadResponse\",\n    \"RobotsDirectives\": \"yoast:RobotsDirectives\",\n    \"OpenGraphMetadata\": \"yoast:OpenGraphMetadata\",\n    \"TwitterCardMetadata\": \"yoast:TwitterCardMetadata\",\n\n    \"title\": { \"@id\": \"schema:name\", \"@type\": \"xsd:string\" },\n    \"description\": { \"@id\": \"schema:description\", \"@type\": \"xsd:string\" },\n    \"canonical\": { \"@id\": \"schema:url\", \"@type\": \"@id\" },\n    \"robots\": { \"@id\": \"yoast:robots\", \"@type\": \"yoast:RobotsDirectives\" },\n    \"index\": { \"@id\": \"yoast:indexDirective\", \"@type\": \"xsd:string\" },\n    \"follow\": { \"@id\": \"yoast:followDirective\", \"@type\": \"xsd:string\" },\n\n    \"og_locale\": { \"@id\"\
  : \"yoast:ogLocale\", \"@type\": \"xsd:string\" },\n    \"og_type\": { \"@id\": \"yoast:ogType\", \"@type\": \"xsd:string\" },\n    \"og_title\": { \"@id\": \"yoast:ogTitle\", \"@type\": \"xsd:string\" },\n    \"og_description\": { \"@id\": \"yoast:ogDescription\", \"@type\": \"xsd:string\" },\n    \"og_url\": { \"@id\": \"yoast:ogUrl\", \"@type\": \"@id\" },\n    \"og_site_name\": { \"@id\": \"yoast:ogSiteName\", \"@type\": \"xsd:string\" },\n    \"og_image\": { \"@id\": \"yoast:ogImage\", \"@container\": \"@set\" },\n\n    \"twitter_card\": { \"@id\": \"yoast:twitterCard\", \"@type\": \"xsd:string\" },\n    \"twitter_title\": { \"@id\": \"yoast:twitterTitle\", \"@type\": \"xsd:string\" },\n    \"twitter_description\": { \"@id\": \"yoast:twitterDescription\", \"@type\": \"xsd:string\" },\n    \"twitter_image\": { \"@id\": \"yoast:twitterImage\", \"@type\": \"@id\" },\n\n    \"article_published_time\": { \"@id\": \"schema:datePublished\", \"@type\": \"xsd:dateTime\" },\n    \"article_modified_time\"\
  : { \"@id\": \"schema:dateModified\", \"@type\": \"xsd:dateTime\" },\n    \"author\": { \"@id\": \"schema:author\", \"@type\": \"xsd:string\" },\n    \"schema\": { \"@id\": \"yoast:schemaGraph\", \"@type\": \"@json\" },\n\n    \"html\": { \"@id\": \"yoast:htmlHead\", \"@type\": \"xsd:string\" },\n    \"json\": { \"@id\": \"yoast:seoMetadata\", \"@type\": \"yoast:SeoMetadata\" },\n    \"status\": { \"@id\": \"yoast:httpStatus\", \"@type\": \"xsd:integer\" },\n\n    \"yoast_head\": { \"@id\": \"yoast:htmlHead\", \"@type\": \"xsd:string\" },\n    \"yoast_head_json\": { \"@id\": \"yoast:seoMetadata\", \"@type\": \"yoast:SeoMetadata\" }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/yoast/refs/heads/main/json-ld/yoast-context.jsonld
tags:
- SEO
- WordPress
- Content Optimization
- Schema
- Metadata
- JSON-LD
- Linked Data
- Semantic Web
---
