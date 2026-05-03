---
api_specs:
- filename: smithsonian-open-access-openapi.yml
  format: yaml
  label: Smithsonian Open Access API
  slug: open-access-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/smithsonian-institution/refs/heads/main/openapi/smithsonian-open-access-openapi.yml
class_count: 31
classes:
- CollectionItem
- MediaItem
- id
- title
- unitCode
- type
- url
- thumbnail
- content
- descriptiveNonRepeating
- indexedStructured
- freetext
- object_type
- date
- place
- culture
- topic
- online_media
- media
- idsId
- caption
- physicalDescription
- creditLine
- data_source
- record_ID
- rowCount
- start
- rows
- facets
- terms
- category
context_file: json-ld/smithsonian-institution-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/smithsonian-institution/refs/heads/main/json-ld/smithsonian-institution-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Smithsonian Institution from Smithsonian Institution.
layout: jsonld
name: Smithsonian Institution Context
namespaces:
- prefix: si
  uri: https://edan.si.edu/openaccess/vocab#
- prefix: edan
  uri: https://edan.si.edu/vocab#
properties: []
property_count: 0
provider_name: Smithsonian Institution
provider_slug: smithsonian-institution
slug: smithsonian-institution-context
source_filename: smithsonian-institution-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"si\": \"https://edan.si.edu/openaccess/vocab#\",\n    \"edan\": \"https://edan.si.edu/vocab#\",\n    \"CollectionItem\": \"Museum\",\n    \"MediaItem\": \"MediaObject\",\n    \"id\": \"@id\",\n    \"title\": \"name\",\n    \"unitCode\": \"si:unitCode\",\n    \"type\": \"@type\",\n    \"url\": \"url\",\n    \"thumbnail\": \"thumbnail\",\n    \"content\": \"si:content\",\n    \"descriptiveNonRepeating\": \"si:descriptiveNonRepeating\",\n    \"indexedStructured\": \"si:indexedStructured\",\n    \"freetext\": \"si:freetext\",\n    \"object_type\": \"additionalType\",\n    \"date\": \"temporalCoverage\",\n    \"place\": \"spatialCoverage\",\n    \"culture\": \"si:culture\",\n    \"topic\": \"about\",\n    \"online_media\": \"associatedMedia\",\n    \"media\": \"encodesCreativeWork\",\n    \"idsId\": \"identifier\",\n    \"caption\": \"caption\",\n    \"physicalDescription\": \"description\",\n    \"creditLine\"\
  : \"creditText\",\n    \"data_source\": \"provider\",\n    \"record_ID\": \"identifier\",\n    \"rowCount\": \"numberOfItems\",\n    \"start\": \"si:start\",\n    \"rows\": \"si:rows\",\n    \"facets\": \"si:facets\",\n    \"terms\": \"si:terms\",\n    \"category\": \"si:category\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/smithsonian-institution/refs/heads/main/json-ld/smithsonian-institution-context.jsonld
tags:
- Collections
- Cultural Heritage
- Museums
- Open Data
- Art
- Natural History
- Research
- JSON-LD
- Linked Data
- Semantic Web
---
