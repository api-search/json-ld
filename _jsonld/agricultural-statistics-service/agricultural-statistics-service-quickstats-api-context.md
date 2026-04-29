---
class_count: 5
classes:
- Statistics Record
- Statistics Response
- Parameter Values Response
- Count Response
- Error Response
context_file: json-ld/agricultural-statistics-service-quickstats-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/agricultural-statistics-service/refs/heads/main/json-ld/agricultural-statistics-service-quickstats-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Agricultural Statistics Service Quickstats Api from Agricultural Statistics Service.
layout: jsonld
name: Agricultural Statistics Service Quickstats Api Context
namespaces:
- prefix: nass
  uri: https://nass.usda.gov/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: sourceDesc
  type: string
- container: ''
  name: sectorDesc
  type: string
- container: ''
  name: groupDesc
  type: string
- container: ''
  name: commodityDesc
  type: string
- container: ''
  name: classDesc
  type: string
- container: ''
  name: statisticcatDesc
  type: string
- container: ''
  name: unitDesc
  type: string
- container: ''
  name: shortDesc
  type: string
- container: ''
  name: domainDesc
  type: string
- container: ''
  name: aggLevelDesc
  type: string
- container: ''
  name: stateAlpha
  type: string
- container: ''
  name: stateName
  type: string
- container: ''
  name: countyName
  type: string
- container: ''
  name: year
  type: integer
- container: ''
  name: freqDesc
  type: string
- container: ''
  name: referencePeriodDesc
  type: string
- container: ''
  name: value
  type: string
- container: ''
  name: CVPct
  type: string
- container: set
  name: data
  type: string
- container: set
  name: paramValues
  type: string
- container: ''
  name: count
  type: integer
- container: ''
  name: error
  type: string
- container: ''
  name: message
  type: string
property_count: 23
provider_name: Agricultural Statistics Service
provider_slug: agricultural-statistics-service
slug: agricultural-statistics-service-quickstats-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"nass\": \"https://nass.usda.gov/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Statistics Record\": \"nass:Statistics Record\",\n    \"sourceDesc\": {\n      \"@id\": \"nass:source_desc\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sectorDesc\": {\n      \"@id\": \"nass:sector_desc\",\n      \"@type\": \"xsd:string\"\n    },\n    \"groupDesc\": {\n      \"@id\": \"nass:group_desc\",\n      \"@type\": \"xsd:string\"\n    },\n    \"commodityDesc\": {\n      \"@id\": \"nass:commodity_desc\",\n      \"@type\": \"xsd:string\"\n    },\n    \"classDesc\": {\n      \"@id\": \"nass:class_desc\",\n      \"@type\": \"xsd:string\"\n    },\n    \"statisticcatDesc\": {\n      \"@id\": \"nass:statisticcat_desc\",\n      \"@type\": \"xsd:string\"\n    },\n    \"unitDesc\": {\n      \"@id\": \"nass:unit_desc\",\n      \"\
  @type\": \"xsd:string\"\n    },\n    \"shortDesc\": {\n      \"@id\": \"nass:short_desc\",\n      \"@type\": \"xsd:string\"\n    },\n    \"domainDesc\": {\n      \"@id\": \"nass:domain_desc\",\n      \"@type\": \"xsd:string\"\n    },\n    \"aggLevelDesc\": {\n      \"@id\": \"nass:agg_level_desc\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stateAlpha\": {\n      \"@id\": \"nass:state_alpha\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stateName\": {\n      \"@id\": \"nass:state_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"countyName\": {\n      \"@id\": \"nass:county_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"year\": {\n      \"@id\": \"nass:year\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"freqDesc\": {\n      \"@id\": \"nass:freq_desc\",\n      \"@type\": \"xsd:string\"\n    },\n    \"referencePeriodDesc\": {\n      \"@id\": \"nass:reference_period_desc\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"nass:value\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"CVPct\": {\n      \"@id\": \"nass:CV_pct\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Statistics Response\": \"nass:Statistics Response\",\n    \"data\": {\n      \"@id\": \"nass:data\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Parameter Values Response\": \"nass:Parameter Values Response\",\n    \"paramValues\": {\n      \"@id\": \"nass:param_values\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Count Response\": \"nass:Count Response\",\n    \"count\": {\n      \"@id\": \"nass:count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"Error Response\": \"nass:Error Response\",\n    \"error\": {\n      \"@id\": \"nass:error\",\n      \"@type\": \"xsd:string\"\n    },\n    \"message\": {\n      \"@id\": \"nass:message\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/agricultural-statistics-service/refs/heads/main/json-ld/agricultural-statistics-service-quickstats-api-context.jsonld
tags:
- Agriculture
- Federal Government
- Statistics
- Open Data
- Geospatial
- JSON-LD
- Linked Data
- Semantic Web
---
