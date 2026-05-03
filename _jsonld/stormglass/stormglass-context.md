---
api_specs:
- filename: stormglass-openapi.yml
  format: yaml
  label: Stormglass API
  slug: stormglass-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/stormglass/refs/heads/main/openapi/stormglass-openapi.yml
class_count: 16
classes:
- WeatherMeasurement
- MarineEnvironment
- TideEvent
- AstronomicalEvent
- ElevationData
- waveHeight
- waveDirection
- wavePeriod
- swellHeight
- waterTemperature
- currentSpeed
- visibility
- precipitation
- humidity
- pressure
- cloudCover
context_file: json-ld/stormglass-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/stormglass/refs/heads/main/json-ld/stormglass-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Stormglass from Stormglass.
layout: jsonld
name: Stormglass Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: qudt
  uri: https://qudt.org/schema/qudt/
- prefix: geo
  uri: http://www.w3.org/2003/01/geo/wgs84_pos#
- prefix: dailyQuota
  uri: https://stormglass.io/schema/dailyQuota
- prefix: requestCount
  uri: https://stormglass.io/schema/requestCount
- prefix: chlorophyll
  uri: https://stormglass.io/schema/chlorophyll
- prefix: oxygen
  uri: https://stormglass.io/schema/dissolvedOxygen
- prefix: salinity
  uri: https://stormglass.io/schema/salinity
- prefix: ph
  uri: https://stormglass.io/schema/ph
properties:
- container: list
  name: hours
  type: ''
- container: ''
  name: time
  type: dateTime
- container: ''
  name: lat
  type: float
- container: ''
  name: lng
  type: float
- container: ''
  name: airTemperature
  type: '@json'
- container: ''
  name: windSpeed
  type: '@json'
- container: ''
  name: windDirection
  type: '@json'
- container: ''
  name: sunrise
  type: dateTime
- container: ''
  name: sunset
  type: dateTime
- container: ''
  name: moonrise
  type: dateTime
- container: ''
  name: moonset
  type: dateTime
- container: ''
  name: moonFraction
  type: float
- container: ''
  name: tideHeight
  type: float
- container: ''
  name: tideType
  type: ''
- container: ''
  name: elevation
  type: float
- container: ''
  name: cost
  type: integer
- container: ''
  name: station
  type: ''
- container: ''
  name: source
  type: ''
- container: ''
  name: uvIndex
  type: float
property_count: 19
provider_name: Stormglass
provider_slug: stormglass
slug: stormglass-context
source_filename: stormglass-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://stormglass.io/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"qudt\": \"https://qudt.org/schema/qudt/\",\n    \"geo\": \"http://www.w3.org/2003/01/geo/wgs84_pos#\",\n    \"WeatherMeasurement\": \"schema:Observation\",\n    \"MarineEnvironment\": \"schema:Observation\",\n    \"TideEvent\": \"schema:Event\",\n    \"AstronomicalEvent\": \"schema:Event\",\n    \"ElevationData\": \"schema:Place\",\n    \"hours\": {\n      \"@id\": \"schema:temporalCoverage\",\n      \"@container\": \"@list\"\n    },\n    \"time\": {\n      \"@id\": \"schema:startDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"lat\": {\n      \"@id\": \"geo:lat\",\n      \"@type\": \"xsd:float\"\n    },\n    \"lng\": {\n      \"@id\": \"geo:long\",\n      \"@type\": \"xsd:float\"\n    },\n    \"airTemperature\": {\n      \"@id\": \"schema:temperature\",\n      \"@type\": \"@json\"\n    },\n \
  \   \"windSpeed\": {\n      \"@id\": \"schema:speed\",\n      \"@type\": \"@json\"\n    },\n    \"windDirection\": {\n      \"@id\": \"schema:Course\",\n      \"@type\": \"@json\"\n    },\n    \"waveHeight\": \"schema:height\",\n    \"waveDirection\": \"schema:Course\",\n    \"wavePeriod\": \"schema:duration\",\n    \"swellHeight\": \"schema:height\",\n    \"waterTemperature\": \"schema:temperature\",\n    \"currentSpeed\": \"schema:speed\",\n    \"visibility\": \"schema:distance\",\n    \"precipitation\": \"schema:elevation\",\n    \"humidity\": \"schema:humidity\",\n    \"pressure\": \"schema:elevation\",\n    \"cloudCover\": \"schema:coverageArea\",\n    \"sunrise\": {\n      \"@id\": \"schema:sunrise\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"sunset\": {\n      \"@id\": \"schema:sunset\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"moonrise\": {\n      \"@id\": \"https://stormglass.io/schema/moonrise\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"moonset\": {\n\
  \      \"@id\": \"https://stormglass.io/schema/moonset\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"moonFraction\": {\n      \"@id\": \"https://stormglass.io/schema/moonFraction\",\n      \"@type\": \"xsd:float\"\n    },\n    \"tideHeight\": {\n      \"@id\": \"schema:height\",\n      \"@type\": \"xsd:float\"\n    },\n    \"tideType\": {\n      \"@id\": \"schema:additionalType\"\n    },\n    \"elevation\": {\n      \"@id\": \"schema:elevation\",\n      \"@type\": \"xsd:float\"\n    },\n    \"cost\": {\n      \"@id\": \"schema:price\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"dailyQuota\": \"https://stormglass.io/schema/dailyQuota\",\n    \"requestCount\": \"https://stormglass.io/schema/requestCount\",\n    \"station\": {\n      \"@id\": \"schema:location\"\n    },\n    \"source\": {\n      \"@id\": \"schema:provider\"\n    },\n    \"uvIndex\": {\n      \"@id\": \"schema:uvIndex\",\n      \"@type\": \"xsd:float\"\n    },\n    \"chlorophyll\": \"https://stormglass.io/schema/chlorophyll\"\
  ,\n    \"oxygen\": \"https://stormglass.io/schema/dissolvedOxygen\",\n    \"salinity\": \"https://stormglass.io/schema/salinity\",\n    \"ph\": \"https://stormglass.io/schema/ph\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/stormglass/refs/heads/main/json-ld/stormglass-context.jsonld
tags:
- Astronomy
- Bio
- Climate
- Elevation
- Forecasting
- Marine
- Ocean
- Solar
- Tides
- Weather
- Wind
- JSON-LD
- Linked Data
- Semantic Web
---
