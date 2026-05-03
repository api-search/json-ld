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
class_count: 12
classes:
- Collection
- CollectionsList
- ErrorResponse
- FeatureCollection
- LandingPage
- Link
- MonitoringLocationCollection
- MonitoringLocationFeature
- MonitoringLocationProperties
- TimeSeriesCollection
- TimeSeriesFeature
- TimeSeriesProperties
context_file: json-ld/usgs-water-data-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/u-s-geological-survey/refs/heads/main/json-ld/usgs-water-data-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Usgs Water Data Api from U.S. Geological Survey.
layout: jsonld
name: Usgs Water Data Api Context
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
  name: id
  type: string
- container: ''
  name: title
  type: ''
- container: ''
  name: description
  type: ''
- container: set
  name: links
  type: string
- container: set
  name: collections
  type: string
- container: ''
  name: code
  type: string
- container: ''
  name: type
  type: string
- container: set
  name: features
  type: string
- container: ''
  name: numberMatched
  type: integer
- container: ''
  name: numberReturned
  type: integer
- container: ''
  name: href
  type: string
- container: ''
  name: rel
  type: string
- container: ''
  name: geometry
  type: string
- container: set
  name: coordinates
  type: decimal
- container: ''
  name: properties
  type: string
- container: ''
  name: monitoringLocationIdentifier
  type: string
- container: ''
  name: monitoringLocationName
  type: string
- container: ''
  name: monitoringLocationTypeName
  type: string
- container: ''
  name: hucEightDigitCode
  type: string
- container: ''
  name: stateFIPSCode
  type: string
- container: ''
  name: countryCode
  type: string
- container: ''
  name: drainageAreaMeasure
  type: decimal
- container: ''
  name: drainageAreaMeasureUnitCode
  type: string
- container: ''
  name: siteWebAddress
  type: string
- container: ''
  name: observedPropertyId
  type: string
- container: ''
  name: observedPropertyName
  type: string
- container: ''
  name: phenomenonTime
  type: dateTime
- container: ''
  name: result
  type: decimal
- container: ''
  name: resultUnitCode
  type: string
- container: ''
  name: resultQualityCode
  type: string
property_count: 30
provider_name: U.S. Geological Survey
provider_slug: u-s-geological-survey
slug: usgs-water-data-api-context
source_filename: usgs-water-data-api-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"usgs\": \"https://www.usgs.gov/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"geo\": \"http://www.opengis.net/ont/geosparql#\",\n    \"Collection\": \"usgs:Collection\",\n    \"CollectionsList\": \"usgs:CollectionsList\",\n    \"ErrorResponse\": \"usgs:ErrorResponse\",\n    \"FeatureCollection\": \"usgs:FeatureCollection\",\n    \"LandingPage\": \"usgs:LandingPage\",\n    \"Link\": \"usgs:Link\",\n    \"MonitoringLocationCollection\": \"usgs:MonitoringLocationCollection\",\n    \"MonitoringLocationFeature\": \"usgs:MonitoringLocationFeature\",\n    \"MonitoringLocationProperties\": \"usgs:MonitoringLocationProperties\",\n    \"TimeSeriesCollection\": \"usgs:TimeSeriesCollection\",\n    \"TimeSeriesFeature\": \"usgs:TimeSeriesFeature\",\n    \"TimeSeriesProperties\": \"usgs:TimeSeriesProperties\",\n    \"id\":\
  \ {\n      \"@id\": \"usgs:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"title\": {\n      \"@id\": \"schema:name\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\"\n    },\n    \"links\": {\n      \"@id\": \"usgs:links\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"collections\": {\n      \"@id\": \"usgs:collections\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"code\": {\n      \"@id\": \"usgs:code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"usgs:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"features\": {\n      \"@id\": \"usgs:features\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"numberMatched\": {\n      \"@id\": \"usgs:numberMatched\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"numberReturned\": {\n      \"@id\": \"usgs:numberReturned\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"href\"\
  : {\n      \"@id\": \"usgs:href\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rel\": {\n      \"@id\": \"usgs:rel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"geometry\": {\n      \"@id\": \"usgs:geometry\",\n      \"@type\": \"xsd:string\"\n    },\n    \"coordinates\": {\n      \"@id\": \"usgs:coordinates\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"properties\": {\n      \"@id\": \"usgs:properties\",\n      \"@type\": \"xsd:string\"\n    },\n    \"monitoringLocationIdentifier\": {\n      \"@id\": \"usgs:monitoringLocationIdentifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"monitoringLocationName\": {\n      \"@id\": \"usgs:monitoringLocationName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"monitoringLocationTypeName\": {\n      \"@id\": \"usgs:monitoringLocationTypeName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"hucEightDigitCode\": {\n      \"@id\": \"usgs:hucEightDigitCode\",\n      \"@type\": \"xsd:string\"\n\
  \    },\n    \"stateFIPSCode\": {\n      \"@id\": \"usgs:stateFIPSCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"countryCode\": {\n      \"@id\": \"usgs:countryCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"drainageAreaMeasure\": {\n      \"@id\": \"usgs:drainageAreaMeasure\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"drainageAreaMeasureUnitCode\": {\n      \"@id\": \"usgs:drainageAreaMeasureUnitCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"siteWebAddress\": {\n      \"@id\": \"usgs:siteWebAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"observedPropertyId\": {\n      \"@id\": \"usgs:observedPropertyId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"observedPropertyName\": {\n      \"@id\": \"usgs:observedPropertyName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"phenomenonTime\": {\n      \"@id\": \"usgs:phenomenonTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"result\": {\n      \"@id\": \"usgs:result\",\n      \"@type\"\
  : \"xsd:decimal\"\n    },\n    \"resultUnitCode\": {\n      \"@id\": \"usgs:resultUnitCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resultQualityCode\": {\n      \"@id\": \"usgs:resultQualityCode\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/u-s-geological-survey/refs/heads/main/json-ld/usgs-water-data-api-context.jsonld
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
