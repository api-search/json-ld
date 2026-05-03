---
api_specs:
- filename: unsplash-openapi.yml
  format: yaml
  label: Unsplash API
  slug: unsplash
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/unsplash/refs/heads/main/openapi/unsplash-openapi.yml
class_count: 11
classes:
- Photo
- Collection
- Topic
- Photographer
- id
- description
- alt_description
- width
- height
- name
- title
context_file: json-ld/unsplash-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/unsplash/refs/heads/main/json-ld/unsplash-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Unsplash from Unsplash.
layout: jsonld
name: Unsplash Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: unsplash
  uri: https://unsplash.com/ontology#
- prefix: iptc
  uri: http://iptc.org/std/Iptc4xmpCore/1.0/xmlns/
- prefix: exif
  uri: http://ns.adobe.com/exif/1.0/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: color
  type: string
- container: ''
  name: blur_hash
  type: string
- container: ''
  name: likes
  type: integer
- container: ''
  name: downloads
  type: integer
- container: ''
  name: views
  type: integer
- container: ''
  name: created_at
  type: dateTime
- container: ''
  name: updated_at
  type: dateTime
- container: ''
  name: promoted_at
  type: dateTime
- container: ''
  name: urls
  type: ''
- container: ''
  name: raw
  type: anyURI
- container: ''
  name: full
  type: anyURI
- container: ''
  name: regular
  type: anyURI
- container: ''
  name: small
  type: anyURI
- container: ''
  name: thumb
  type: anyURI
- container: ''
  name: links
  type: ''
- container: ''
  name: html
  type: anyURI
- container: ''
  name: download_location
  type: anyURI
- container: ''
  name: user
  type: schema:Person
- container: ''
  name: username
  type: string
- container: ''
  name: portfolio_url
  type: anyURI
- container: ''
  name: bio
  type: string
- container: ''
  name: total_photos
  type: integer
- container: ''
  name: total_likes
  type: integer
- container: ''
  name: profile_image
  type: ''
- container: ''
  name: location
  type: schema:Place
- container: ''
  name: city
  type: string
- container: ''
  name: country
  type: string
- container: ''
  name: position
  type: schema:GeoCoordinates
- container: ''
  name: latitude
  type: float
- container: ''
  name: longitude
  type: float
- container: ''
  name: exif_data
  type: ''
- container: ''
  name: make
  type: string
- container: ''
  name: model
  type: string
- container: ''
  name: exposure_time
  type: string
- container: ''
  name: aperture
  type: string
- container: ''
  name: focal_length
  type: string
- container: ''
  name: iso
  type: integer
- container: set
  name: tags
  type: ''
- container: ''
  name: slug
  type: string
- container: ''
  name: total
  type: integer
- container: ''
  name: total_pages
  type: integer
- container: list
  name: results
  type: ''
property_count: 42
provider_name: Unsplash
provider_slug: unsplash
slug: unsplash-context
source_filename: unsplash-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"unsplash\": \"https://unsplash.com/ontology#\",\n    \"iptc\": \"http://iptc.org/std/Iptc4xmpCore/1.0/xmlns/\",\n    \"exif\": \"http://ns.adobe.com/exif/1.0/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Photo\": \"schema:Photograph\",\n    \"Collection\": \"schema:Collection\",\n    \"Topic\": \"schema:CreativeWorkSeries\",\n    \"Photographer\": \"schema:Person\",\n\n    \"id\": \"schema:identifier\",\n    \"description\": \"schema:description\",\n    \"alt_description\": \"schema:alternateName\",\n    \"width\": \"schema:width\",\n    \"height\": \"schema:height\",\n    \"color\": {\n      \"@id\": \"unsplash:dominantColor\",\n      \"@type\": \"xsd:string\"\n    },\n    \"blur_hash\": {\n      \"@id\": \"unsplash:blurHash\",\n      \"@type\": \"xsd:string\"\n    },\n    \"likes\": {\n      \"@id\": \"schema:interactionStatistic\",\n      \"@type\": \"xsd:integer\"\
  \n    },\n    \"downloads\": {\n      \"@id\": \"schema:downloadUrl\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"views\": {\n      \"@id\": \"schema:viewCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"created_at\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updated_at\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"promoted_at\": {\n      \"@id\": \"unsplash:promotedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n\n    \"urls\": {\n      \"@id\": \"schema:image\"\n    },\n    \"raw\": {\n      \"@id\": \"unsplash:rawUrl\",\n      \"@type\": \"xsd:anyURI\"\n    },\n    \"full\": {\n      \"@id\": \"schema:contentUrl\",\n      \"@type\": \"xsd:anyURI\"\n    },\n    \"regular\": {\n      \"@id\": \"schema:thumbnailUrl\",\n      \"@type\": \"xsd:anyURI\"\n    },\n    \"small\": {\n      \"@id\": \"unsplash:smallUrl\",\n      \"@type\": \"xsd:anyURI\"\n    },\n    \"thumb\": {\n\
  \      \"@id\": \"schema:thumbnail\",\n      \"@type\": \"xsd:anyURI\"\n    },\n\n    \"links\": {\n      \"@id\": \"schema:sameAs\"\n    },\n    \"html\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"xsd:anyURI\"\n    },\n    \"download_location\": {\n      \"@id\": \"unsplash:downloadLocation\",\n      \"@type\": \"xsd:anyURI\"\n    },\n\n    \"user\": {\n      \"@id\": \"schema:creator\",\n      \"@type\": \"schema:Person\"\n    },\n    \"username\": {\n      \"@id\": \"schema:accountName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"portfolio_url\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"xsd:anyURI\"\n    },\n    \"bio\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"total_photos\": {\n      \"@id\": \"unsplash:totalPhotos\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"total_likes\": {\n      \"@id\": \"unsplash:totalLikes\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"\
  profile_image\": {\n      \"@id\": \"schema:image\"\n    },\n\n    \"location\": {\n      \"@id\": \"schema:locationCreated\",\n      \"@type\": \"schema:Place\"\n    },\n    \"city\": {\n      \"@id\": \"schema:addressLocality\",\n      \"@type\": \"xsd:string\"\n    },\n    \"country\": {\n      \"@id\": \"schema:addressCountry\",\n      \"@type\": \"xsd:string\"\n    },\n    \"position\": {\n      \"@id\": \"schema:geo\",\n      \"@type\": \"schema:GeoCoordinates\"\n    },\n    \"latitude\": {\n      \"@id\": \"schema:latitude\",\n      \"@type\": \"xsd:float\"\n    },\n    \"longitude\": {\n      \"@id\": \"schema:longitude\",\n      \"@type\": \"xsd:float\"\n    },\n\n    \"exif_data\": {\n      \"@id\": \"unsplash:exif\"\n    },\n    \"make\": {\n      \"@id\": \"exif:Make\",\n      \"@type\": \"xsd:string\"\n    },\n    \"model\": {\n      \"@id\": \"exif:Model\",\n      \"@type\": \"xsd:string\"\n    },\n    \"exposure_time\": {\n      \"@id\": \"exif:ExposureTime\",\n      \"\
  @type\": \"xsd:string\"\n    },\n    \"aperture\": {\n      \"@id\": \"exif:FNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"focal_length\": {\n      \"@id\": \"exif:FocalLength\",\n      \"@type\": \"xsd:string\"\n    },\n    \"iso\": {\n      \"@id\": \"exif:ISOSpeedRatings\",\n      \"@type\": \"xsd:integer\"\n    },\n\n    \"tags\": {\n      \"@id\": \"schema:keywords\",\n      \"@container\": \"@set\"\n    },\n    \"title\": \"schema:name\",\n    \"slug\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"total\": {\n      \"@id\": \"schema:numberOfItems\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"total_pages\": {\n      \"@id\": \"schema:numberOfPages\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"results\": {\n      \"@id\": \"schema:itemListElement\",\n      \"@container\": \"@list\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/unsplash/refs/heads/main/json-ld/unsplash-context.jsonld
tags:
- Photos
- Images
- Photography
- Stock Photos
- Creative
- Open Source
- Media
- JSON-LD
- Linked Data
- Semantic Web
---
