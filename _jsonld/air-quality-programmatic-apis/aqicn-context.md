---
api_specs:
- filename: air-quality-programmatic-apis-openapi.yml
  format: yaml
  label: AQICN Real-Time Air Quality API
  slug: air-quality-programmatic-apis
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/air-quality-programmatic-apis/refs/heads/main/openapi/air-quality-programmatic-apis-openapi.yml
- filename: aqicn-json-api-openapi.yaml
  format: yaml
  label: AQICN JSON Air Quality API
  slug: aqicn-json-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/air-quality-programmatic-apis/refs/heads/main/openapi/aqicn-json-api-openapi.yaml
class_count: 11
classes:
- AQIStation
- StationData
- name
- url
- CityInfo
- TimeInfo
- PollutantData
- ForecastData
- ForecastDay
- Attribution
- StationSearchResult
context_file: json-ld/aqicn-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/air-quality-programmatic-apis/refs/heads/main/json-ld/aqicn-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Aqicn from Air Quality Programmatic APIs.
layout: jsonld
name: Aqicn Context
namespaces:
- prefix: aqicn
  uri: https://aqicn.org/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: status
  type: string
- container: ''
  name: data
  type: string
- container: ''
  name: aqi
  type: integer
- container: ''
  name: idx
  type: integer
- container: ''
  name: city
  type: string
- container: ''
  name: time
  type: string
- container: ''
  name: iaqi
  type: string
- container: ''
  name: forecast
  type: string
- container: set
  name: attributions
  type: string
- container: set
  name: geo
  type: string
- container: ''
  name: s
  type: string
- container: ''
  name: tz
  type: string
- container: ''
  name: v
  type: integer
- container: ''
  name: pm25
  type: string
- container: ''
  name: pm10
  type: string
- container: ''
  name: no2
  type: string
- container: ''
  name: o3
  type: string
- container: ''
  name: so2
  type: string
- container: ''
  name: co
  type: string
- container: ''
  name: daily
  type: string
- container: ''
  name: avg
  type: integer
- container: ''
  name: day
  type: string
- container: ''
  name: max
  type: integer
- container: ''
  name: min
  type: integer
property_count: 24
provider_name: Air Quality Programmatic APIs
provider_slug: air-quality-programmatic-apis
slug: aqicn-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aqicn\": \"https://aqicn.org/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"status\": {\n      \"@id\": \"aqicn:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"data\": {\n      \"@id\": \"aqicn:data\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AQIStation\": \"aqicn:AQIStation\",\n    \"aqi\": {\n      \"@id\": \"aqicn:aqi\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"idx\": {\n      \"@id\": \"aqicn:idx\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"city\": {\n      \"@id\": \"aqicn:city\",\n      \"@type\": \"xsd:string\"\n    },\n    \"time\": {\n      \"@id\": \"aqicn:time\",\n      \"@type\": \"xsd:string\"\n    },\n    \"iaqi\": {\n      \"@id\": \"aqicn:iaqi\",\n      \"@type\": \"xsd:string\"\n    },\n    \"forecast\": {\n      \"@id\": \"aqicn:forecast\",\n      \"@type\": \"xsd:string\"\n    },\n    \"attributions\": {\n \
  \     \"@id\": \"aqicn:attributions\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"StationData\": \"aqicn:StationData\",\n    \"name\": \"schema:name\",\n    \"url\": \"schema:url\",\n    \"geo\": {\n      \"@id\": \"aqicn:geo\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CityInfo\": \"aqicn:CityInfo\",\n    \"s\": {\n      \"@id\": \"aqicn:s\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tz\": {\n      \"@id\": \"aqicn:tz\",\n      \"@type\": \"xsd:string\"\n    },\n    \"v\": {\n      \"@id\": \"aqicn:v\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"TimeInfo\": \"aqicn:TimeInfo\",\n    \"pm25\": {\n      \"@id\": \"aqicn:pm25\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pm10\": {\n      \"@id\": \"aqicn:pm10\",\n      \"@type\": \"xsd:string\"\n    },\n    \"no2\": {\n      \"@id\": \"aqicn:no2\",\n      \"@type\": \"xsd:string\"\n    },\n    \"o3\": {\n      \"@id\": \"aqicn:o3\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"so2\": {\n      \"@id\": \"aqicn:so2\",\n      \"@type\": \"xsd:string\"\n    },\n    \"co\": {\n      \"@id\": \"aqicn:co\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PollutantData\": \"aqicn:PollutantData\",\n    \"daily\": {\n      \"@id\": \"aqicn:daily\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ForecastData\": \"aqicn:ForecastData\",\n    \"avg\": {\n      \"@id\": \"aqicn:avg\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"day\": {\n      \"@id\": \"aqicn:day\",\n      \"@type\": \"xsd:string\"\n    },\n    \"max\": {\n      \"@id\": \"aqicn:max\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"min\": {\n      \"@id\": \"aqicn:min\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"ForecastDay\": \"aqicn:ForecastDay\",\n    \"Attribution\": \"aqicn:Attribution\",\n    \"StationSearchResult\": \"aqicn:StationSearchResult\"\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/air-quality-programmatic-apis/refs/heads/main/json-ld/aqicn-context.jsonld
tags:
- Air Quality
- Environment
- EPA
- Open Data
- Public Health
- IoT
- Government Data
- Real-Time Data
- JSON-LD
- Linked Data
- Semantic Web
---
