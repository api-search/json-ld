---
api_specs:
- filename: index.htm
  format: yaml
  label: The Bureau of Economic Analysis API
  slug: the-bureau-of-economic-analysis
  spec_type: OpenAPI
  url: https://apps.bea.gov/API/docs/index.htm
class_count: 8
classes:
- BEAAPI
- DatasetName
- DatasetDescription
- DataValue
- SeriesCode
- LineNumber
- LineDescription
- TableName
context_file: json-ld/the-bureau-of-economic-analysis-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/the-bureau-of-economic-analysis/refs/heads/main/json-ld/the-bureau-of-economic-analysis-context.jsonld
description: JSON-LD context defining the semantic vocabulary for The Bureau Of Economic Analysis from The Bureau of Economic Analysis.
layout: jsonld
name: The Bureau Of Economic Analysis Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: bea
  uri: https://apps.bea.gov/api/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: skos
  uri: http://www.w3.org/2004/02/skos/core#
properties:
- container: ''
  name: TimePeriod
  type: string
- container: ''
  name: UnitOfMeasure
  type: ''
- container: ''
  name: Statistic
  type: ''
- container: ''
  name: GeoFips
  type: ''
- container: ''
  name: GeoName
  type: ''
- container: ''
  name: Dataset
  type: schema:Dataset
- container: ''
  name: GovernmentOrganization
  type: ''
- container: ''
  name: BEA
  type: ''
- container: set
  name: datasets
  type: ''
- container: set
  name: parameters
  type: ''
- container: set
  name: data
  type: ''
- container: set
  name: notes
  type: ''
- container: ''
  name: NIPA
  type: ''
- container: ''
  name: GDPbyIndustry
  type: ''
- container: ''
  name: Regional
  type: ''
- container: ''
  name: ITA
  type: ''
- container: ''
  name: IIP
  type: ''
- container: ''
  name: MNE
  type: ''
- container: ''
  name: FixedAssets
  type: ''
- container: ''
  name: InputOutput
  type: ''
property_count: 20
provider_name: The Bureau of Economic Analysis
provider_slug: the-bureau-of-economic-analysis
slug: the-bureau-of-economic-analysis-context
source_filename: the-bureau-of-economic-analysis-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"bea\": \"https://apps.bea.gov/api/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"skos\": \"http://www.w3.org/2004/02/skos/core#\",\n\n    \"BEAAPI\": \"bea:BEAAPI\",\n    \"DatasetName\": \"bea:DatasetName\",\n    \"DatasetDescription\": \"dcterms:description\",\n    \"DataValue\": \"bea:DataValue\",\n    \"TimePeriod\": {\n      \"@id\": \"dcterms:temporal\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SeriesCode\": \"bea:SeriesCode\",\n    \"LineNumber\": \"bea:LineNumber\",\n    \"LineDescription\": \"dcterms:description\",\n    \"TableName\": \"bea:TableName\",\n    \"UnitOfMeasure\": {\n      \"@id\": \"schema:unitText\"\n    },\n    \"Statistic\": {\n      \"@id\": \"schema:StatisticalVariable\"\n    },\n    \"GeoFips\": {\n      \"@id\": \"schema:addressRegion\"\n    },\n    \"GeoName\": {\n      \"@id\":\
  \ \"schema:name\"\n    },\n    \"Dataset\": {\n      \"@id\": \"schema:Dataset\",\n      \"@type\": \"schema:Dataset\"\n    },\n    \"GovernmentOrganization\": {\n      \"@id\": \"schema:GovernmentOrganization\"\n    },\n    \"BEA\": {\n      \"@id\": \"schema:GovernmentOrganization\",\n      \"schema:name\": \"Bureau of Economic Analysis\",\n      \"schema:url\": \"https://www.bea.gov\"\n    },\n\n    \"datasets\": {\n      \"@id\": \"schema:dataset\",\n      \"@container\": \"@set\"\n    },\n    \"parameters\": {\n      \"@id\": \"bea:parameters\",\n      \"@container\": \"@set\"\n    },\n    \"data\": {\n      \"@id\": \"schema:DataDownload\",\n      \"@container\": \"@set\"\n    },\n    \"notes\": {\n      \"@id\": \"schema:description\",\n      \"@container\": \"@set\"\n    },\n\n    \"NIPA\": {\n      \"@id\": \"bea:NIPA\",\n      \"skos:prefLabel\": \"National Income and Product Accounts\"\n    },\n    \"GDPbyIndustry\": {\n      \"@id\": \"bea:GDPbyIndustry\",\n      \"skos:prefLabel\"\
  : \"GDP by Industry\"\n    },\n    \"Regional\": {\n      \"@id\": \"bea:Regional\",\n      \"skos:prefLabel\": \"Regional Economic Data\"\n    },\n    \"ITA\": {\n      \"@id\": \"bea:ITA\",\n      \"skos:prefLabel\": \"International Transactions Accounts\"\n    },\n    \"IIP\": {\n      \"@id\": \"bea:IIP\",\n      \"skos:prefLabel\": \"International Investment Position\"\n    },\n    \"MNE\": {\n      \"@id\": \"bea:MNE\",\n      \"skos:prefLabel\": \"Multinational Enterprises\"\n    },\n    \"FixedAssets\": {\n      \"@id\": \"bea:FixedAssets\",\n      \"skos:prefLabel\": \"Fixed Assets\"\n    },\n    \"InputOutput\": {\n      \"@id\": \"bea:InputOutput\",\n      \"skos:prefLabel\": \"Input-Output Tables\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/the-bureau-of-economic-analysis/refs/heads/main/json-ld/the-bureau-of-economic-analysis-context.jsonld
tags:
- Economics
- Federal Government
- GDP
- National Accounts
- Open Data
- Statistics
- JSON-LD
- Linked Data
- Semantic Web
---
