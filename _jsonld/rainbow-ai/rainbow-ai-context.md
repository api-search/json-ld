---
api_specs:
- filename: rainbow-ai-nowcast-openapi.yml
  format: yaml
  label: Rainbow.AI Nowcast API
  slug: rainbow-ai-nowcast
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/rainbow-ai/refs/heads/main/openapi/rainbow-ai-nowcast-openapi.yml
- filename: rainbow-ai-tiles-openapi.yml
  format: yaml
  label: Rainbow.AI Tiles API
  slug: rainbow-ai-tiles
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/rainbow-ai/refs/heads/main/openapi/rainbow-ai-tiles-openapi.yml
class_count: 5
classes:
- NowcastResponse
- ForecastPoint
- RadarResponse
- RadarPoint
- Location
context_file: json-ld/rainbow-ai-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/rainbow-ai/refs/heads/main/json-ld/rainbow-ai-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Rainbow Ai from Rainbow.AI.
layout: jsonld
name: Rainbow Ai Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: rainbow
  uri: https://api.rainbow.ai/vocab#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: geo
  uri: http://www.w3.org/2003/01/geo/wgs84_pos#
properties:
- container: ''
  name: location
  type: reference
- container: ''
  name: lat
  type: decimal
- container: ''
  name: lon
  type: decimal
- container: list
  name: forecasts
  type: ''
- container: list
  name: radar_data
  type: ''
- container: ''
  name: timestamp
  type: dateTime
- container: ''
  name: updated_at
  type: dateTime
- container: ''
  name: precipitation_type
  type: ''
- container: ''
  name: precipitation_intensity
  type: decimal
- container: ''
  name: probability
  type: decimal
- container: ''
  name: reflectivity
  type: decimal
property_count: 11
provider_name: Rainbow.AI
provider_slug: rainbow-ai
slug: rainbow-ai-context
source_filename: rainbow-ai-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"rainbow\": \"https://api.rainbow.ai/vocab#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"geo\": \"http://www.w3.org/2003/01/geo/wgs84_pos#\",\n\n    \"NowcastResponse\": \"rainbow:NowcastResponse\",\n    \"ForecastPoint\": \"rainbow:ForecastPoint\",\n    \"RadarResponse\": \"rainbow:RadarResponse\",\n    \"RadarPoint\": \"rainbow:RadarPoint\",\n    \"Location\": \"schema:GeoCoordinates\",\n\n    \"location\": {\n      \"@id\": \"schema:geo\",\n      \"@type\": \"@id\"\n    },\n    \"lat\": {\n      \"@id\": \"geo:lat\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"lon\": {\n      \"@id\": \"geo:long\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"forecasts\": {\n      \"@id\": \"rainbow:forecasts\",\n      \"@container\": \"@list\"\n    },\n    \"radar_data\": {\n      \"@id\": \"rainbow:radarData\",\n      \"@container\": \"@list\"\n    },\n    \"timestamp\"\
  : {\n      \"@id\": \"schema:dateTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updated_at\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"precipitation_type\": {\n      \"@id\": \"rainbow:precipitationType\"\n    },\n    \"precipitation_intensity\": {\n      \"@id\": \"rainbow:precipitationIntensity\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"probability\": {\n      \"@id\": \"rainbow:probability\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"reflectivity\": {\n      \"@id\": \"rainbow:reflectivity\",\n      \"@type\": \"xsd:decimal\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/rainbow-ai/refs/heads/main/json-ld/rainbow-ai-context.jsonld
tags:
- Weather
- Precipitation
- Forecasting
- Nowcast
- Radar
- Tiles
- Geospatial
- JSON-LD
- Linked Data
- Semantic Web
---
