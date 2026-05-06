---
api_specs:
- filename: wordpress-rest-api-openapi.yml
  format: yaml
  label: WordPress REST API
  slug: rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/wordpress/refs/heads/main/openapi/wordpress-rest-api-openapi.yml
class_count: 18
classes:
- Block
- BlockType
- Comment
- CommentInput
- MediaItem
- Page
- PageInput
- Plugin
- Post
- PostInput
- PostType
- RenderedContent
- SearchResult
- Settings
- Term
- TermInput
- Theme
- User
context_file: json-ld/wordpress-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/wordpress/refs/heads/main/json-ld/wordpress-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Wordpress from WordPress.
layout: jsonld
name: Wordpress Context
namespaces:
- prefix: wp
  uri: https://developer.wordpress.org/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: altText
  type: string
- container: ''
  name: attributes
  type: reference
- container: ''
  name: author
  type: integer
- container: ''
  name: authorEmail
  type: string
- container: ''
  name: authorName
  type: string
- container: ''
  name: authorUri
  type: string
- container: ''
  name: avatarUrls
  type: reference
- container: ''
  name: capabilities
  type: reference
- container: set
  name: categories
  type: integer
- container: ''
  name: category
  type: string
- container: ''
  name: commentStatus
  type: string
- container: ''
  name: content
  type: string
- container: ''
  name: count
  type: integer
- container: ''
  name: date
  type: dateTime
- container: ''
  name: dateFormat
  type: string
- container: ''
  name: dateGmt
  type: dateTime
- container: ''
  name: defaultCategory
  type: integer
- container: ''
  name: description
  type: ''
- container: ''
  name: email
  type: ''
- container: ''
  name: excerpt
  type: string
- container: ''
  name: featuredMedia
  type: integer
- container: ''
  name: format
  type: string
- container: ''
  name: hierarchical
  type: boolean
- container: ''
  name: id
  type: integer
- container: ''
  name: isDynamic
  type: boolean
- container: ''
  name: language
  type: string
- container: ''
  name: link
  type: string
- container: ''
  name: mediaDetails
  type: reference
- container: ''
  name: mediaType
  type: string
- container: ''
  name: menuOrder
  type: integer
- container: ''
  name: mimeType
  type: string
- container: ''
  name: modified
  type: dateTime
- container: ''
  name: name
  type: ''
- container: ''
  name: parent
  type: integer
- container: ''
  name: pingStatus
  type: string
- container: ''
  name: plugin
  type: string
- container: ''
  name: pluginUri
  type: string
- container: ''
  name: post
  type: integer
- container: ''
  name: postsPerPage
  type: integer
- container: ''
  name: protected
  type: boolean
- container: ''
  name: rendered
  type: string
- container: ''
  name: restBase
  type: string
- container: set
  name: roles
  type: string
- container: ''
  name: slug
  type: string
- container: ''
  name: sourceUrl
  type: string
- container: ''
  name: startOfWeek
  type: integer
- container: ''
  name: status
  type: string
- container: ''
  name: sticky
  type: boolean
- container: ''
  name: stylesheet
  type: string
- container: ''
  name: subtype
  type: string
- container: set
  name: tags
  type: integer
- container: set
  name: taxonomies
  type: string
- container: ''
  name: taxonomy
  type: string
- container: ''
  name: template
  type: string
- container: ''
  name: themeUri
  type: string
- container: ''
  name: timeFormat
  type: string
- container: ''
  name: timezone
  type: string
- container: ''
  name: title
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: url
  type: ''
- container: ''
  name: useSmilies
  type: boolean
- container: ''
  name: version
  type: ''
property_count: 62
provider_name: WordPress
provider_slug: wordpress
slug: wordpress-context
source_filename: wordpress-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"wp\": \"https://developer.wordpress.org/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Block\": \"wp:Block\",\n    \"BlockType\": \"wp:BlockType\",\n    \"Comment\": \"wp:Comment\",\n    \"CommentInput\": \"wp:CommentInput\",\n    \"MediaItem\": \"wp:MediaItem\",\n    \"Page\": \"wp:Page\",\n    \"PageInput\": \"wp:PageInput\",\n    \"Plugin\": \"wp:Plugin\",\n    \"Post\": \"wp:Post\",\n    \"PostInput\": \"wp:PostInput\",\n    \"PostType\": \"wp:PostType\",\n    \"RenderedContent\": \"wp:RenderedContent\",\n    \"SearchResult\": \"wp:SearchResult\",\n    \"Settings\": \"wp:Settings\",\n    \"Term\": \"wp:Term\",\n    \"TermInput\": \"wp:TermInput\",\n    \"Theme\": \"wp:Theme\",\n    \"User\": \"wp:User\",\n    \"altText\": {\n      \"@id\": \"wp:alt_text\",\n      \"@type\": \"xsd:string\"\n    },\n    \"attributes\"\
  : {\n      \"@id\": \"wp:attributes\",\n      \"@type\": \"@id\"\n    },\n    \"author\": {\n      \"@id\": \"wp:author\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"authorEmail\": {\n      \"@id\": \"wp:author_email\",\n      \"@type\": \"xsd:string\"\n    },\n    \"authorName\": {\n      \"@id\": \"wp:author_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"authorUri\": {\n      \"@id\": \"wp:author_uri\",\n      \"@type\": \"xsd:string\"\n    },\n    \"avatarUrls\": {\n      \"@id\": \"wp:avatar_urls\",\n      \"@type\": \"@id\"\n    },\n    \"capabilities\": {\n      \"@id\": \"wp:capabilities\",\n      \"@type\": \"@id\"\n    },\n    \"categories\": {\n      \"@id\": \"wp:categories\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"category\": {\n      \"@id\": \"wp:category\",\n      \"@type\": \"xsd:string\"\n    },\n    \"commentStatus\": {\n      \"@id\": \"wp:comment_status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"content\"\
  : {\n      \"@id\": \"wp:content\",\n      \"@type\": \"xsd:string\"\n    },\n    \"count\": {\n      \"@id\": \"wp:count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"date\": {\n      \"@id\": \"wp:date\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"dateFormat\": {\n      \"@id\": \"wp:date_format\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dateGmt\": {\n      \"@id\": \"wp:date_gmt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"defaultCategory\": {\n      \"@id\": \"wp:default_category\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\"\n    },\n    \"email\": {\n      \"@id\": \"schema:email\"\n    },\n    \"excerpt\": {\n      \"@id\": \"wp:excerpt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"featuredMedia\": {\n      \"@id\": \"wp:featured_media\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"format\": {\n      \"@id\": \"wp:format\",\n      \"@type\": \"xsd:string\"\n    },\n    \"hierarchical\"\
  : {\n      \"@id\": \"wp:hierarchical\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"id\": {\n      \"@id\": \"wp:id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"isDynamic\": {\n      \"@id\": \"wp:is_dynamic\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"language\": {\n      \"@id\": \"wp:language\",\n      \"@type\": \"xsd:string\"\n    },\n    \"link\": {\n      \"@id\": \"wp:link\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mediaDetails\": {\n      \"@id\": \"wp:media_details\",\n      \"@type\": \"@id\"\n    },\n    \"mediaType\": {\n      \"@id\": \"wp:media_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"menuOrder\": {\n      \"@id\": \"wp:menu_order\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"mimeType\": {\n      \"@id\": \"wp:mime_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"modified\": {\n      \"@id\": \"wp:modified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\"\n    },\n    \"\
  parent\": {\n      \"@id\": \"wp:parent\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"pingStatus\": {\n      \"@id\": \"wp:ping_status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"plugin\": {\n      \"@id\": \"wp:plugin\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pluginUri\": {\n      \"@id\": \"wp:plugin_uri\",\n      \"@type\": \"xsd:string\"\n    },\n    \"post\": {\n      \"@id\": \"wp:post\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"postsPerPage\": {\n      \"@id\": \"wp:posts_per_page\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"protected\": {\n      \"@id\": \"wp:protected\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"rendered\": {\n      \"@id\": \"wp:rendered\",\n      \"@type\": \"xsd:string\"\n    },\n    \"restBase\": {\n      \"@id\": \"wp:rest_base\",\n      \"@type\": \"xsd:string\"\n    },\n    \"roles\": {\n      \"@id\": \"wp:roles\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"slug\": {\n  \
  \    \"@id\": \"wp:slug\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sourceUrl\": {\n      \"@id\": \"wp:source_url\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startOfWeek\": {\n      \"@id\": \"wp:start_of_week\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"status\": {\n      \"@id\": \"wp:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sticky\": {\n      \"@id\": \"wp:sticky\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"stylesheet\": {\n      \"@id\": \"wp:stylesheet\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subtype\": {\n      \"@id\": \"wp:subtype\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tags\": {\n      \"@id\": \"wp:tags\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"taxonomies\": {\n      \"@id\": \"wp:taxonomies\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"taxonomy\": {\n      \"@id\": \"wp:taxonomy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"\
  template\": {\n      \"@id\": \"wp:template\",\n      \"@type\": \"xsd:string\"\n    },\n    \"themeUri\": {\n      \"@id\": \"wp:theme_uri\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timeFormat\": {\n      \"@id\": \"wp:time_format\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timezone\": {\n      \"@id\": \"wp:timezone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"title\": {\n      \"@id\": \"wp:title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"wp:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"url\": {\n      \"@id\": \"schema:url\"\n    },\n    \"useSmilies\": {\n      \"@id\": \"wp:use_smilies\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"version\": {\n      \"@id\": \"schema:version\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/wordpress/refs/heads/main/json-ld/wordpress-context.jsonld
tags:
- CMS
- Content Management
- Open Source
- WordPress
- JSON-LD
- Linked Data
- Semantic Web
---
