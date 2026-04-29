---
api_specs:
- filename: moodys-data-buffet-api-openapi.yml
  format: yaml
  label: Moody's Data Buffet API
  slug: data-buffet-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/moodys/refs/heads/main/openapi/moodys-data-buffet-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/moodys-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/moodys/refs/heads/main/json-ld/moodys-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Moodys from Moody's.
layout: jsonld
name: Moodys Context
namespaces:
- prefix: moodys
  uri: https://economy.com/ns/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: qb
  uri: http://purl.org/linked-data/cube#
- prefix: sdmx
  uri: http://purl.org/linked-data/sdmx/2009/measure#
properties:
- container: ''
  name: TimeSeries
  type: ''
- container: ''
  name: Observation
  type: ''
- container: ''
  name: Basket
  type: ''
- container: ''
  name: Order
  type: ''
- container: ''
  name: Vintage
  type: ''
- container: ''
  name: SearchResult
  type: ''
property_count: 6
provider_name: Moody's
provider_slug: moodys
slug: moodys-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"moodys\": \"https://economy.com/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"qb\": \"http://purl.org/linked-data/cube#\",\n    \"sdmx\": \"http://purl.org/linked-data/sdmx/2009/measure#\",\n\n    \"TimeSeries\": {\n      \"@id\": \"moodys:TimeSeries\",\n      \"@context\": {\n        \"mnemonic\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\",\n          \"@comment\": \"The unique Data Buffet series mnemonic identifier, mapped to schema:identifier for universal resource identification.\"\n        },\n        \"description\": {\n          \"@id\": \"dcterms:description\",\n          \"@type\": \"xsd:string\",\n          \"@comment\": \"Human-readable description of the time series, mapped to dcterms:description.\"\n        },\n        \"frequency\": {\n          \"@id\": \"schema:frequency\"\
  ,\n          \"@type\": \"xsd:string\",\n          \"@comment\": \"The temporal frequency of observations (Annual, Quarterly, Monthly, Weekly, Daily), mapped to schema:frequency.\"\n        },\n        \"source\": {\n          \"@id\": \"dcterms:source\",\n          \"@type\": \"xsd:string\",\n          \"@comment\": \"The original data source or statistical agency, mapped to dcterms:source.\"\n        },\n        \"geography\": {\n          \"@id\": \"schema:spatialCoverage\",\n          \"@type\": \"xsd:string\",\n          \"@comment\": \"The geographic area the series covers, mapped to schema:spatialCoverage for spatial context.\"\n        },\n        \"geographyCode\": {\n          \"@id\": \"moodys:geographyCode\",\n          \"@type\": \"xsd:string\",\n          \"@comment\": \"Standardized geographic code (ISO 3166 or FIPS), specific to Moody's geographic classification.\"\n        },\n        \"units\": {\n          \"@id\": \"schema:unitCode\",\n          \"@type\": \"xsd:string\"\
  ,\n          \"@comment\": \"The unit of measurement for series values, mapped to schema:unitCode.\"\n        },\n        \"category\": {\n          \"@id\": \"schema:category\",\n          \"@type\": \"xsd:string\",\n          \"@comment\": \"The broad economic or demographic category, mapped to schema:category.\"\n        },\n        \"startDate\": {\n          \"@id\": \"schema:startDate\",\n          \"@type\": \"xsd:date\",\n          \"@comment\": \"The earliest observation date in the data range, mapped to schema:startDate.\"\n        },\n        \"endDate\": {\n          \"@id\": \"schema:endDate\",\n          \"@type\": \"xsd:date\",\n          \"@comment\": \"The latest observation or forecast date, mapped to schema:endDate.\"\n        },\n        \"lastUpdated\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\",\n          \"@comment\": \"When the series was last updated in the Data Buffet repository, mapped to dcterms:modified.\"\n        },\n\
  \        \"isForecast\": {\n          \"@id\": \"moodys:isForecast\",\n          \"@type\": \"xsd:boolean\",\n          \"@comment\": \"Whether the series includes Moody's Analytics forecast data. Specific to Moody's model-generated projections.\"\n        },\n        \"data\": {\n          \"@id\": \"moodys:observations\",\n          \"@container\": \"@list\",\n          \"@comment\": \"Ordered list of time series observations, using @list to preserve chronological ordering.\"\n        }\n      }\n    },\n\n    \"Observation\": {\n      \"@id\": \"qb:Observation\",\n      \"@context\": {\n        \"date\": {\n          \"@id\": \"dcterms:date\",\n          \"@type\": \"xsd:date\",\n          \"@comment\": \"The observation date, mapped to dcterms:date. For coarser frequencies represents the period start date.\"\n        },\n        \"value\": {\n          \"@id\": \"sdmx:obsValue\",\n          \"@type\": \"xsd:decimal\",\n          \"@comment\": \"The observed or forecast value, mapped\
  \ to the SDMX observation value measure for statistical data interoperability.\"\n        },\n        \"status\": {\n          \"@id\": \"moodys:observationStatus\",\n          \"@type\": \"xsd:string\",\n          \"@comment\": \"Whether the data point is History, Forecast, or Preliminary. Specific to Moody's data classification.\"\n        }\n      }\n    },\n\n    \"Basket\": {\n      \"@id\": \"moodys:Basket\",\n      \"@context\": {\n        \"basketId\": {\n          \"@id\": \"@id\",\n          \"@comment\": \"Maps the basket identifier to JSON-LD @id, making each basket uniquely addressable as a linked data resource.\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\",\n          \"@comment\": \"User-defined basket name, mapped to schema:name.\"\n        },\n        \"description\": {\n          \"@id\": \"dcterms:description\",\n          \"@type\": \"xsd:string\",\n          \"@comment\": \"Optional description of the basket\
  \ contents and purpose.\"\n        },\n        \"series\": {\n          \"@id\": \"moodys:containsSeries\",\n          \"@container\": \"@set\",\n          \"@comment\": \"The set of series requests in the basket. Uses @set as ordering is not significant.\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\",\n          \"@comment\": \"When the basket was created, mapped to dcterms:created.\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\",\n          \"@comment\": \"When the basket was last modified, mapped to dcterms:modified.\"\n        }\n      }\n    },\n\n    \"Order\": {\n      \"@id\": \"moodys:Order\",\n      \"@context\": {\n        \"orderId\": {\n          \"@id\": \"@id\",\n          \"@comment\": \"Maps the order identifier to JSON-LD @id, making each order uniquely addressable.\"\n        },\n        \"basketId\": {\n          \"@id\":\
  \ \"moodys:fromBasket\",\n          \"@type\": \"@id\",\n          \"@comment\": \"Reference to the basket from which the order was generated, linked as an @id for resource linking.\"\n        },\n        \"status\": {\n          \"@id\": \"schema:eventStatus\",\n          \"@type\": \"xsd:string\",\n          \"@comment\": \"Current processing status of the order (Pending, Processing, Complete, Failed), mapped to schema:eventStatus.\"\n        },\n        \"fileType\": {\n          \"@id\": \"schema:encodingFormat\",\n          \"@type\": \"xsd:string\",\n          \"@comment\": \"The output file format for the order, mapped to schema:encodingFormat.\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\",\n          \"@comment\": \"When the order was created.\"\n        },\n        \"completedAt\": {\n          \"@id\": \"moodys:completedAt\",\n          \"@type\": \"xsd:dateTime\",\n          \"@comment\": \"When order\
  \ processing completed. Specific to Moody's order lifecycle.\"\n        },\n        \"downloadUrl\": {\n          \"@id\": \"schema:contentUrl\",\n          \"@type\": \"@id\",\n          \"@comment\": \"URL to download the order output, mapped to schema:contentUrl.\"\n        }\n      }\n    },\n\n    \"Vintage\": {\n      \"@id\": \"moodys:Vintage\",\n      \"@context\": {\n        \"vintageDate\": {\n          \"@id\": \"dcterms:issued\",\n          \"@type\": \"xsd:date\",\n          \"@comment\": \"The date this data vintage was published, mapped to dcterms:issued for publication date semantics.\"\n        },\n        \"description\": {\n          \"@id\": \"dcterms:description\",\n          \"@type\": \"xsd:string\",\n          \"@comment\": \"Description of the vintage release context.\"\n        }\n      }\n    },\n\n    \"SearchResult\": {\n      \"@id\": \"moodys:SearchResult\",\n      \"@context\": {\n        \"mnemonic\": {\n          \"@id\": \"schema:identifier\",\n     \
  \     \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"dcterms:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"hasForecast\": {\n          \"@id\": \"moodys:hasForecast\",\n          \"@type\": \"xsd:boolean\",\n          \"@comment\": \"Whether the series includes Moody's Analytics forecast data.\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/moodys/refs/heads/main/json-ld/moodys-context.jsonld
tags:
- Climate Risk
- Compliance
- Credit Risk
- Economic Data
- Entity Verification
- Financial Analytics
- Insurance
- KYC
- Risk
- Screening
- JSON-LD
- Linked Data
- Semantic Web
---
