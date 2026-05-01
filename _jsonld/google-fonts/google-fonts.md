---
api_specs:
- filename: openapi.yml
  format: yaml
  label: Google Fonts Developer API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-fonts/refs/heads/main/openapi/openapi.yml
class_count: 0
classes: []
context_file: json-ld/google-fonts.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-fonts/refs/heads/main/json-ld/google-fonts.jsonld
description: JSON-LD context defining the semantic vocabulary for Google Fonts from Google Fonts Developer.
layout: jsonld
name: Google Fonts Context
namespaces:
- prefix: gfonts
  uri: https://developers.google.com/fonts/docs/developer_api#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: family
  type: string
- container: list
  name: variants
  type: ''
- container: list
  name: subsets
  type: ''
- container: ''
  name: version
  type: string
- container: ''
  name: lastModified
  type: date
- container: ''
  name: category
  type: string
- container: ''
  name: files
  type: reference
- container: list
  name: axes
  type: ''
- container: ''
  name: tag
  type: string
property_count: 9
provider_name: Google Fonts Developer
provider_slug: google-fonts
slug: google-fonts
source_filename: google-fonts.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"gfonts\": \"https://developers.google.com/fonts/docs/developer_api#\",\n    \"family\": {\n      \"@id\": \"gfonts:family\",\n      \"@type\": \"xsd:string\"\n    },\n    \"variants\": {\n      \"@id\": \"gfonts:variants\",\n      \"@container\": \"@list\"\n    },\n    \"subsets\": {\n      \"@id\": \"gfonts:subsets\",\n      \"@container\": \"@list\"\n    },\n    \"version\": {\n      \"@id\": \"gfonts:version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastModified\": {\n      \"@id\": \"gfonts:lastModified\",\n      \"@type\": \"xsd:date\"\n    },\n    \"category\": {\n      \"@id\": \"gfonts:category\",\n      \"@type\": \"xsd:string\"\n    },\n    \"files\": {\n      \"@id\": \"gfonts:files\",\n      \"@type\": \"@id\"\n    },\n    \"axes\": {\n      \"@id\": \"gfonts:axes\",\n      \"@container\": \"@list\"\n    },\n    \"tag\": {\n      \"@id\": \"gfonts:tag\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-fonts/refs/heads/main/json-ld/google-fonts.jsonld
tags:
- CSS
- Design
- Fonts
- Google Fonts
- Typography
- Web Fonts
- JSON-LD
- Linked Data
- Semantic Web
---
