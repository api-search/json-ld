---
api_specs:
- filename: usgs-earthquake-api-openapi.yaml
  format: yaml
  label: Earthquake Notifications, Feeds, and Web Services
  slug: earthquake-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/u-s-geological-survey/refs/heads/main/openapi/usgs-earthquake-api-openapi.yaml
- filename: usgs-water-data-api-openapi.yaml
  format: yaml
  label: USGS Water Data APIs
  slug: water-data-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/u-s-geological-survey/refs/heads/main/openapi/usgs-water-data-api-openapi.yaml
class_count: 6
classes:
- CountResponse
- EarthquakeFeatureCollection
- EarthquakeFeature
- EarthquakeGeometry
- EarthquakeMetadata
- EarthquakeProperties
context_file: json-ld/usgs-earthquake-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/u-s-geological-survey/refs/heads/main/json-ld/usgs-earthquake-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Usgs Earthquake Api from U.S. Geological Survey.
layout: jsonld
name: Usgs Earthquake Api Context
namespaces:
- prefix: usgs
  uri: https://www.usgs.gov/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: geo
  uri: http://www.opengis.net/ont/geosparql#
properties:
- container: ''
  name: count
  type: integer
- container: ''
  name: maxAllowed
  type: integer
- container: ''
  name: type
  type: string
- container: ''
  name: metadata
  type: string
- container: set
  name: features
  type: string
- container: set
  name: bbox
  type: decimal
- container: ''
  name: properties
  type: string
- container: ''
  name: geometry
  type: string
- container: ''
  name: id
  type: string
- container: set
  name: coordinates
  type: decimal
- container: ''
  name: generated
  type: integer
- container: ''
  name: url
  type: ''
- container: ''
  name: title
  type: ''
- container: ''
  name: status
  type: integer
- container: ''
  name: api
  type: string
- container: ''
  name: limit
  type: integer
- container: ''
  name: offset
  type: integer
- container: ''
  name: mag
  type: decimal
- container: ''
  name: place
  type: string
- container: ''
  name: time
  type: integer
- container: ''
  name: updated
  type: integer
- container: ''
  name: detail
  type: string
- container: ''
  name: felt
  type: integer
- container: ''
  name: cdi
  type: decimal
- container: ''
  name: mmi
  type: decimal
- container: ''
  name: alert
  type: string
- container: ''
  name: tsunami
  type: integer
- container: ''
  name: sig
  type: integer
- container: ''
  name: net
  type: string
- container: ''
  name: code
  type: string
- container: ''
  name: magType
  type: string
- container: ''
  name: gap
  type: decimal
- container: ''
  name: dmin
  type: decimal
- container: ''
  name: rms
  type: decimal
- container: ''
  name: nst
  type: integer
property_count: 35
provider_name: U.S. Geological Survey
provider_slug: u-s-geological-survey
slug: usgs-earthquake-api-context
source_filename: usgs-earthquake-api-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"usgs\": \"https://www.usgs.gov/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"geo\": \"http://www.opengis.net/ont/geosparql#\",\n    \"CountResponse\": \"usgs:CountResponse\",\n    \"EarthquakeFeatureCollection\": \"usgs:EarthquakeFeatureCollection\",\n    \"EarthquakeFeature\": \"usgs:EarthquakeFeature\",\n    \"EarthquakeGeometry\": \"usgs:EarthquakeGeometry\",\n    \"EarthquakeMetadata\": \"usgs:EarthquakeMetadata\",\n    \"EarthquakeProperties\": \"usgs:EarthquakeProperties\",\n    \"count\": {\n      \"@id\": \"usgs:count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"maxAllowed\": {\n      \"@id\": \"usgs:maxAllowed\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"type\": {\n      \"@id\": \"usgs:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"metadata\": {\n      \"@id\": \"usgs:metadata\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"features\": {\n      \"@id\": \"usgs:features\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bbox\": {\n      \"@id\": \"usgs:bbox\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"properties\": {\n      \"@id\": \"usgs:properties\",\n      \"@type\": \"xsd:string\"\n    },\n    \"geometry\": {\n      \"@id\": \"usgs:geometry\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"usgs:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"coordinates\": {\n      \"@id\": \"usgs:coordinates\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"generated\": {\n      \"@id\": \"usgs:generated\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"url\": {\n      \"@id\": \"schema:url\"\n    },\n    \"title\": {\n      \"@id\": \"schema:name\"\n    },\n    \"status\": {\n      \"@id\": \"usgs:status\",\n      \"@type\": \"\
  xsd:integer\"\n    },\n    \"api\": {\n      \"@id\": \"usgs:api\",\n      \"@type\": \"xsd:string\"\n    },\n    \"limit\": {\n      \"@id\": \"usgs:limit\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"offset\": {\n      \"@id\": \"usgs:offset\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"mag\": {\n      \"@id\": \"usgs:mag\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"place\": {\n      \"@id\": \"usgs:place\",\n      \"@type\": \"xsd:string\"\n    },\n    \"time\": {\n      \"@id\": \"usgs:time\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"updated\": {\n      \"@id\": \"usgs:updated\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"detail\": {\n      \"@id\": \"usgs:detail\",\n      \"@type\": \"xsd:string\"\n    },\n    \"felt\": {\n      \"@id\": \"usgs:felt\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"cdi\": {\n      \"@id\": \"usgs:cdi\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"mmi\": {\n      \"@id\": \"usgs:mmi\",\n      \"@type\": \"xsd:decimal\"\
  \n    },\n    \"alert\": {\n      \"@id\": \"usgs:alert\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tsunami\": {\n      \"@id\": \"usgs:tsunami\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"sig\": {\n      \"@id\": \"usgs:sig\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"net\": {\n      \"@id\": \"usgs:net\",\n      \"@type\": \"xsd:string\"\n    },\n    \"code\": {\n      \"@id\": \"usgs:code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"magType\": {\n      \"@id\": \"usgs:magType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"gap\": {\n      \"@id\": \"usgs:gap\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"dmin\": {\n      \"@id\": \"usgs:dmin\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"rms\": {\n      \"@id\": \"usgs:rms\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"nst\": {\n      \"@id\": \"usgs:nst\",\n      \"@type\": \"xsd:integer\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/u-s-geological-survey/refs/heads/main/json-ld/usgs-earthquake-api-context.jsonld
tags:
- Federal Government
- Geological
- Earth Science
- Natural Resources
- Earthquake
- Water
- Hydrology
- JSON-LD
- Linked Data
- Semantic Web
---
