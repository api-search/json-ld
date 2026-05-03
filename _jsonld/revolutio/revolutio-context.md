---
api_specs:
- filename: revolutio-hazard-api-openapi.yml
  format: yaml
  label: Revolutio Hazard API
  slug: revolutio-hazard-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/revolutio/refs/heads/main/openapi/revolutio-hazard-api-openapi.yml
class_count: 29
classes:
- latitude
- longitude
- h
- units
- WindAnalysisResult
- region
- class
- criticalDirection
- terrainCategory
- topographicClass
- shieldingClass
- windSpeed
- SnowIceResult
- snowRegion
- snowElevationClass
- snowGroundLoad
- iceRegion
- SeismicResult
- hazardClass
- siteClass
- kp
- CombinedHazardResult
- wind
- snow
- ice
- seismic
- creditsUsed
- standard
- country
context_file: json-ld/revolutio-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/revolutio/refs/heads/main/json-ld/revolutio-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Revolutio from Revolutio.
layout: jsonld
name: Revolutio Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: geo
  uri: http://www.w3.org/2003/01/geo/wgs84_pos#
- prefix: rev
  uri: https://www.revolutio.com.au/vocab/
properties: []
property_count: 0
provider_name: Revolutio
provider_slug: revolutio
slug: revolutio-context
source_filename: revolutio-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"geo\": \"http://www.w3.org/2003/01/geo/wgs84_pos#\",\n    \"rev\": \"https://www.revolutio.com.au/vocab/\",\n\n    \"latitude\": \"geo:lat\",\n    \"longitude\": \"geo:long\",\n    \"h\": \"rev:structureHeight\",\n    \"units\": \"rev:units\",\n\n    \"WindAnalysisResult\": \"rev:WindAnalysisResult\",\n    \"region\": \"rev:windRegion\",\n    \"class\": \"rev:windClass\",\n    \"criticalDirection\": \"rev:criticalDirection\",\n    \"terrainCategory\": \"rev:terrainCategory\",\n    \"topographicClass\": \"rev:topographicClass\",\n    \"shieldingClass\": \"rev:shieldingClass\",\n    \"windSpeed\": \"rev:windSpeed\",\n\n    \"SnowIceResult\": \"rev:SnowIceResult\",\n    \"snowRegion\": \"rev:snowRegion\",\n    \"snowElevationClass\": \"rev:snowElevationClass\",\n    \"snowGroundLoad\": \"rev:snowGroundLoad\",\n    \"iceRegion\": \"rev:iceRegion\",\n\n    \"SeismicResult\": \"rev:SeismicResult\"\
  ,\n    \"hazardClass\": \"rev:seismicHazardClass\",\n    \"siteClass\": \"rev:seismicSiteClass\",\n    \"kp\": \"rev:probabilityFactor\",\n\n    \"CombinedHazardResult\": \"rev:CombinedHazardResult\",\n    \"wind\": \"rev:windAnalysis\",\n    \"snow\": \"rev:snowAnalysis\",\n    \"ice\": \"rev:iceAnalysis\",\n    \"seismic\": \"rev:seismicAnalysis\",\n    \"creditsUsed\": \"rev:creditsUsed\",\n\n    \"standard\": \"rev:designStandard\",\n    \"country\": \"schema:addressCountry\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/revolutio/refs/heads/main/json-ld/revolutio-context.jsonld
tags:
- Engineering
- Hazard
- Weather
- Structural Engineering
- Wind Analysis
- Construction
- JSON-LD
- Linked Data
- Semantic Web
---
