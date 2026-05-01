---
api_specs:
- filename: nps-data-api-openapi.yml
  format: yaml
  label: National Park Service Data API
  slug: nps-data-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/department-of-the-interior/refs/heads/main/openapi/nps-data-api-openapi.yml
- filename: usgs-earthquake-api-openapi.yml
  format: yaml
  label: USGS Earthquake Hazards Program API
  slug: usgs-earthquake-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/department-of-the-interior/refs/heads/main/openapi/usgs-earthquake-api-openapi.yml
- filename: usgs-water-services-api-openapi.yml
  format: yaml
  label: USGS Water Services API
  slug: usgs-water-services-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/department-of-the-interior/refs/heads/main/openapi/usgs-water-services-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/doi-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/department-of-the-interior/refs/heads/main/json-ld/doi-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Doi from Department of the Interior.
layout: jsonld
name: Doi Context
namespaces:
- prefix: doi
  uri: https://api-evangelist.com/department-of-the-interior/vocab/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: geo
  uri: http://www.w3.org/2003/01/geo/wgs84_pos#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Park
  type: ''
- container: ''
  name: Campground
  type: ''
- container: ''
  name: Earthquake
  type: ''
- container: ''
  name: WaterSite
  type: ''
property_count: 4
provider_name: Department of the Interior
provider_slug: department-of-the-interior
slug: doi-context
source_filename: doi-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"doi\": \"https://api-evangelist.com/department-of-the-interior/vocab/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"geo\": \"http://www.w3.org/2003/01/geo/wgs84_pos#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Park\": {\n      \"@id\": \"doi:Park\",\n      \"@context\": {\n        \"fullName\": \"schema:name\",\n        \"parkCode\": \"schema:identifier\",\n        \"description\": \"schema:description\",\n        \"url\": { \"@id\": \"schema:url\", \"@type\": \"@id\" },\n        \"latitude\": { \"@id\": \"geo:lat\", \"@type\": \"xsd:decimal\" },\n        \"longitude\": { \"@id\": \"geo:long\", \"@type\": \"xsd:decimal\" },\n        \"states\": \"schema:addressRegion\",\n        \"designation\": \"doi:designation\"\n      }\n    },\n    \"Campground\": {\n      \"@id\": \"doi:Campground\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n\
  \        \"description\": \"schema:description\",\n        \"parkCode\": \"doi:parkCode\",\n        \"latitude\": { \"@id\": \"geo:lat\", \"@type\": \"xsd:decimal\" },\n        \"longitude\": { \"@id\": \"geo:long\", \"@type\": \"xsd:decimal\" }\n      }\n    },\n    \"Earthquake\": {\n      \"@id\": \"doi:Earthquake\",\n      \"@context\": {\n        \"mag\": { \"@id\": \"doi:magnitude\", \"@type\": \"xsd:decimal\" },\n        \"place\": \"schema:location\",\n        \"time\": { \"@id\": \"schema:dateTime\", \"@type\": \"xsd:dateTime\" },\n        \"depth\": { \"@id\": \"doi:depthKm\", \"@type\": \"xsd:decimal\" },\n        \"alert\": \"doi:alertLevel\",\n        \"tsunami\": { \"@id\": \"doi:tsunamiFlag\", \"@type\": \"xsd:boolean\" }\n      }\n    },\n    \"WaterSite\": {\n      \"@id\": \"doi:WaterSite\",\n      \"@context\": {\n        \"siteCode\": \"schema:identifier\",\n        \"siteName\": \"schema:name\",\n        \"stateCd\": \"schema:addressRegion\",\n        \"latitude\"\
  : { \"@id\": \"geo:lat\", \"@type\": \"xsd:decimal\" },\n        \"longitude\": { \"@id\": \"geo:long\", \"@type\": \"xsd:decimal\" }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/department-of-the-interior/refs/heads/main/json-ld/doi-context.jsonld
tags:
- Federal Government
- Public Lands
- Natural Resources
- Geospatial
- JSON-LD
- Linked Data
- Semantic Web
---
