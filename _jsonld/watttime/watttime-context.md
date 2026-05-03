---
api_specs:
- filename: watttime-openapi.yml
  format: yaml
  label: WattTime API
  slug: watttime
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/watttime/refs/heads/main/openapi/watttime-openapi.yml
class_count: 13
classes:
- DataMeta
- DataPoint
- DataResponse
- ForecastMeta
- ForecastResponse
- GridMapsResponse
- HistoricalDownloadResponse
- LoginResponse
- MyAccessResponse
- RegionAccess
- RegionResponse
- RegisterRequest
- RegisterResponse
context_file: json-ld/watttime-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/watttime/refs/heads/main/json-ld/watttime-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Watttime from WattTime.
layout: jsonld
name: Watttime Context
namespaces:
- prefix: wt
  uri: https://watttime.org/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: region
  type: string
- container: ''
  name: signalType
  type: string
- container: ''
  name: model
  type: reference
- container: ''
  name: date
  type: string
- container: ''
  name: units
  type: string
- container: ''
  name: pointTime
  type: dateTime
- container: ''
  name: value
  type: double
- container: ''
  name: version
  type: ''
- container: ''
  name: meta
  type: reference
- container: set
  name: data
  type: ''
- container: ''
  name: generatedAt
  type: dateTime
- container: ''
  name: type
  type: string
- container: set
  name: features
  type: ''
- container: ''
  name: downloadUrl
  type: reference
- container: ''
  name: token
  type: string
- container: set
  name: regions
  type: ''
- container: ''
  name: regionFullName
  type: string
- container: ''
  name: dataStart
  type: dateTime
- container: ''
  name: access
  type: string
- container: ''
  name: username
  type: string
- container: ''
  name: password
  type: string
- container: ''
  name: email
  type: ''
- container: ''
  name: org
  type: string
- container: ''
  name: user
  type: string
- container: ''
  name: ok
  type: string
property_count: 25
provider_name: WattTime
provider_slug: watttime
slug: watttime-context
source_filename: watttime-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"wt\": \"https://watttime.org/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"DataMeta\": \"wt:DataMeta\",\n    \"DataPoint\": \"wt:DataPoint\",\n    \"DataResponse\": \"wt:DataResponse\",\n    \"ForecastMeta\": \"wt:ForecastMeta\",\n    \"ForecastResponse\": \"wt:ForecastResponse\",\n    \"GridMapsResponse\": \"wt:GridMapsResponse\",\n    \"HistoricalDownloadResponse\": \"wt:HistoricalDownloadResponse\",\n    \"LoginResponse\": \"wt:LoginResponse\",\n    \"MyAccessResponse\": \"wt:MyAccessResponse\",\n    \"RegionAccess\": \"wt:RegionAccess\",\n    \"RegionResponse\": \"wt:RegionResponse\",\n    \"RegisterRequest\": \"wt:RegisterRequest\",\n    \"RegisterResponse\": \"wt:RegisterResponse\",\n    \"region\": {\n      \"@id\": \"wt:region\",\n      \"@type\": \"xsd:string\"\n    },\n    \"signalType\": {\n      \"\
  @id\": \"wt:signal_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"model\": {\n      \"@id\": \"wt:model\",\n      \"@type\": \"@id\"\n    },\n    \"date\": {\n      \"@id\": \"wt:date\",\n      \"@type\": \"xsd:string\"\n    },\n    \"units\": {\n      \"@id\": \"wt:units\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pointTime\": {\n      \"@id\": \"wt:point_time\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"value\": {\n      \"@id\": \"wt:value\",\n      \"@type\": \"xsd:double\"\n    },\n    \"version\": {\n      \"@id\": \"schema:version\"\n    },\n    \"meta\": {\n      \"@id\": \"wt:meta\",\n      \"@type\": \"@id\"\n    },\n    \"data\": {\n      \"@id\": \"wt:data\",\n      \"@container\": \"@set\"\n    },\n    \"generatedAt\": {\n      \"@id\": \"wt:generated_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"type\": {\n      \"@id\": \"wt:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"features\": {\n      \"@id\": \"wt:features\",\n      \"@container\"\
  : \"@set\"\n    },\n    \"downloadUrl\": {\n      \"@id\": \"wt:download_url\",\n      \"@type\": \"@id\"\n    },\n    \"token\": {\n      \"@id\": \"wt:token\",\n      \"@type\": \"xsd:string\"\n    },\n    \"regions\": {\n      \"@id\": \"wt:regions\",\n      \"@container\": \"@set\"\n    },\n    \"regionFullName\": {\n      \"@id\": \"wt:region_full_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dataStart\": {\n      \"@id\": \"wt:data_start\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"access\": {\n      \"@id\": \"wt:access\",\n      \"@type\": \"xsd:string\"\n    },\n    \"username\": {\n      \"@id\": \"wt:username\",\n      \"@type\": \"xsd:string\"\n    },\n    \"password\": {\n      \"@id\": \"wt:password\",\n      \"@type\": \"xsd:string\"\n    },\n    \"email\": {\n      \"@id\": \"schema:email\"\n    },\n    \"org\": {\n      \"@id\": \"wt:org\",\n      \"@type\": \"xsd:string\"\n    },\n    \"user\": {\n      \"@id\": \"wt:user\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"ok\": {\n      \"@id\": \"wt:ok\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/watttime/refs/heads/main/json-ld/watttime-context.jsonld
tags:
- Emissions
- Climate
- Carbon
- Energy
- Electricity Grid
- Sustainability
- Clean Energy
- JSON-LD
- Linked Data
- Semantic Web
---
