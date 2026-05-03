---
api_specs:
- filename: science-museum-group-collection-openapi.yml
  format: yaml
  label: Science Museum Group Collection API
  slug: collection-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/science-museum-group/refs/heads/main/openapi/science-museum-group-collection-openapi.yml
class_count: 23
classes:
- CollectionObject
- CollectionPerson
- CollectionDocument
- Museum
- name
- summary
- description
- on_display
- categories
- places
- accession_number
- images
- imageWidth
- imageHeight
- copyright
- location
- gallery
- occupation
- searchEndpoint
- searchQuery
- totalResults
- pageNumber
- pageSize
context_file: json-ld/science-museum-group-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/science-museum-group/refs/heads/main/json-ld/science-museum-group-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Science Museum Group from Science Museum Group.
layout: jsonld
name: Science Museum Group Context
namespaces:
- prefix: smg
  uri: https://collection.sciencemuseumgroup.org.uk/
- prefix: jsonapi
  uri: https://jsonapi.org/format/#
properties:
- container: ''
  name: objectId
  type: reference
- container: ''
  name: personId
  type: reference
- container: ''
  name: documentId
  type: reference
- container: ''
  name: date
  type: ''
- container: ''
  name: dateFrom
  type: schema:Date
- container: ''
  name: dateTo
  type: schema:Date
- container: ''
  name: imageUrl
  type: reference
- container: ''
  name: license
  type: reference
- container: ''
  name: museums
  type: reference
- container: ''
  name: makers
  type: reference
- container: ''
  name: people
  type: reference
- container: ''
  name: documents
  type: reference
- container: ''
  name: birthPlace
  type: reference
- container: ''
  name: birthDate
  type: schema:Date
- container: ''
  name: deathDate
  type: schema:Date
- container: ''
  name: ScienceMuseum
  type: schema:Museum
- container: ''
  name: NationalRailwayMuseum
  type: schema:Museum
- container: ''
  name: ScienceAndIndustryMuseum
  type: schema:Museum
- container: ''
  name: NationalScienceAndMediaMuseum
  type: schema:Museum
property_count: 19
provider_name: Science Museum Group
provider_slug: science-museum-group
slug: science-museum-group-context
source_filename: science-museum-group-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"smg\": \"https://collection.sciencemuseumgroup.org.uk/\",\n    \"jsonapi\": \"https://jsonapi.org/format/#\",\n\n    \"CollectionObject\": \"schema:CreativeWork\",\n    \"CollectionPerson\": \"schema:Person\",\n    \"CollectionDocument\": \"schema:DigitalDocument\",\n    \"Museum\": \"schema:Museum\",\n\n    \"objectId\": {\n      \"@id\": \"smg:objects\",\n      \"@type\": \"@id\"\n    },\n    \"personId\": {\n      \"@id\": \"smg:people\",\n      \"@type\": \"@id\"\n    },\n    \"documentId\": {\n      \"@id\": \"smg:documents\",\n      \"@type\": \"@id\"\n    },\n\n    \"name\": \"schema:name\",\n    \"summary\": \"schema:description\",\n    \"description\": \"schema:description\",\n    \"on_display\": \"schema:availability\",\n    \"categories\": \"schema:keywords\",\n    \"places\": \"schema:spatialCoverage\",\n    \"accession_number\": \"schema:identifier\",\n\n    \"date\": {\n      \"@id\": \"schema:temporalCoverage\"\
  \n    },\n    \"dateFrom\": {\n      \"@id\": \"schema:startDate\",\n      \"@type\": \"schema:Date\"\n    },\n    \"dateTo\": {\n      \"@id\": \"schema:endDate\",\n      \"@type\": \"schema:Date\"\n    },\n\n    \"images\": \"schema:image\",\n    \"imageUrl\": {\n      \"@id\": \"schema:contentUrl\",\n      \"@type\": \"@id\"\n    },\n    \"imageWidth\": \"schema:width\",\n    \"imageHeight\": \"schema:height\",\n    \"copyright\": \"schema:copyrightNotice\",\n    \"license\": {\n      \"@id\": \"schema:license\",\n      \"@type\": \"@id\"\n    },\n\n    \"museums\": {\n      \"@id\": \"schema:holdingArchive\",\n      \"@type\": \"@id\"\n    },\n    \"location\": \"schema:locationCreated\",\n    \"gallery\": \"schema:containedInPlace\",\n\n    \"makers\": {\n      \"@id\": \"schema:creator\",\n      \"@type\": \"@id\"\n    },\n    \"people\": {\n      \"@id\": \"schema:contributor\",\n      \"@type\": \"@id\"\n    },\n    \"documents\": {\n      \"@id\": \"schema:associatedMedia\",\n\
  \      \"@type\": \"@id\"\n    },\n\n    \"occupation\": \"schema:hasOccupation\",\n    \"birthPlace\": {\n      \"@id\": \"schema:birthPlace\",\n      \"@type\": \"@id\"\n    },\n    \"birthDate\": {\n      \"@id\": \"schema:birthDate\",\n      \"@type\": \"schema:Date\"\n    },\n    \"deathDate\": {\n      \"@id\": \"schema:deathDate\",\n      \"@type\": \"schema:Date\"\n    },\n\n    \"ScienceMuseum\": {\n      \"@id\": \"smg:SMG\",\n      \"@type\": \"schema:Museum\"\n    },\n    \"NationalRailwayMuseum\": {\n      \"@id\": \"smg:NRM\",\n      \"@type\": \"schema:Museum\"\n    },\n    \"ScienceAndIndustryMuseum\": {\n      \"@id\": \"smg:MSI\",\n      \"@type\": \"schema:Museum\"\n    },\n    \"NationalScienceAndMediaMuseum\": {\n      \"@id\": \"smg:NMeM\",\n      \"@type\": \"schema:Museum\"\n    },\n\n    \"searchEndpoint\": \"schema:SearchAction\",\n    \"searchQuery\": \"schema:query\",\n    \"totalResults\": \"schema:numberOfItems\",\n    \"pageNumber\": \"schema:pageNumber\"\
  ,\n    \"pageSize\": \"schema:pageSize\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/science-museum-group/refs/heads/main/json-ld/science-museum-group-context.jsonld
tags:
- Museums
- Collections
- Cultural Heritage
- Open Data
- Science
- Technology
- United Kingdom
- JSON-LD
- Linked Data
- Semantic Web
---
