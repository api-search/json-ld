---
class_count: 0
classes: []
context_file: json-ld/sm-energy-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/sm-energy/refs/heads/main/json-ld/sm-energy-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Sm Energy from SM Energy.
layout: jsonld
name: Sm Energy Context
namespaces:
- prefix: sm
  uri: https://www.sm-energy.com/vocab#
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: EnergyCompany
  type: ''
- container: ''
  name: OilGasAsset
  type: ''
- container: ''
  name: ProvedReserves
  type: ''
- container: ''
  name: ProductionReport
  type: ''
- container: ''
  name: Well
  type: ''
- container: ''
  name: HedgingPosition
  type: ''
property_count: 6
provider_name: SM Energy
provider_slug: sm-energy
slug: sm-energy-context
source_filename: sm-energy-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"sm\": \"https://www.sm-energy.com/vocab#\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"EnergyCompany\": {\n      \"@id\": \"schema:Organization\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\"\n        },\n        \"tickerSymbol\": {\n          \"@id\": \"schema:tickerSymbol\"\n        },\n        \"exchange\": {\n          \"@id\": \"sm:exchange\"\n        },\n        \"foundingDate\": {\n          \"@id\": \"schema:foundingDate\"\n        },\n        \"numberOfEmployees\": {\n          \"@id\": \"schema:numberOfEmployees\"\n        },\n        \"headquarters\": {\n          \"@id\": \"schema:location\"\n        },\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"description\": {\n          \"@id\": \"dcterms:description\"\
  \n        }\n      }\n    },\n\n    \"OilGasAsset\": {\n      \"@id\": \"sm:OilGasAsset\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\"\n        },\n        \"basin\": {\n          \"@id\": \"sm:basin\"\n        },\n        \"state\": {\n          \"@id\": \"schema:addressRegion\"\n        },\n        \"netAcres\": {\n          \"@id\": \"sm:netAcres\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"netProducingWells\": {\n          \"@id\": \"sm:netProducingWells\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"dailyProductionMboepd\": {\n          \"@id\": \"sm:dailyProductionMboepd\",\n          \"@type\": \"xsd:decimal\"\n        }\n      }\n    },\n\n    \"ProvedReserves\": {\n      \"@id\": \"sm:ProvedReserves\",\n      \"@context\": {\n        \"reportingDate\": {\n          \"@id\": \"dcterms:date\",\n          \"@type\": \"xsd:date\"\n        },\n        \"totalMMBoe\": {\n          \"@id\": \"sm:totalMMBoe\",\n \
  \         \"@type\": \"xsd:decimal\"\n        },\n        \"oilPercent\": {\n          \"@id\": \"sm:oilPercent\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"naturalGasPercent\": {\n          \"@id\": \"sm:naturalGasPercent\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"nglPercent\": {\n          \"@id\": \"sm:nglPercent\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"pdpPercent\": {\n          \"@id\": \"sm:pdpPercent\",\n          \"@type\": \"xsd:decimal\"\n        }\n      }\n    },\n\n    \"ProductionReport\": {\n      \"@id\": \"sm:ProductionReport\",\n      \"@context\": {\n        \"period\": {\n          \"@id\": \"dcterms:temporal\"\n        },\n        \"totalMboepd\": {\n          \"@id\": \"sm:totalMboepd\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"oilMbopd\": {\n          \"@id\": \"sm:oilMbopd\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"naturalGasMmcfpd\": {\n          \"@id\": \"\
  sm:naturalGasMmcfpd\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"nglMbopd\": {\n          \"@id\": \"sm:nglMbopd\",\n          \"@type\": \"xsd:decimal\"\n        }\n      }\n    },\n\n    \"Well\": {\n      \"@id\": \"sm:Well\",\n      \"@context\": {\n        \"apiNumber\": {\n          \"@id\": \"schema:identifier\"\n        },\n        \"wellName\": {\n          \"@id\": \"schema:name\"\n        },\n        \"wellType\": {\n          \"@id\": \"sm:wellType\"\n        },\n        \"basin\": {\n          \"@id\": \"sm:basin\"\n        },\n        \"spudDate\": {\n          \"@id\": \"sm:spudDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"completionDate\": {\n          \"@id\": \"sm:completionDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"workingInterestPercent\": {\n          \"@id\": \"sm:workingInterestPercent\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"lateralLengthFt\": {\n          \"@id\": \"sm:lateralLengthFt\"\
  ,\n          \"@type\": \"xsd:decimal\"\n        }\n      }\n    },\n\n    \"HedgingPosition\": {\n      \"@id\": \"sm:HedgingPosition\",\n      \"@context\": {\n        \"commodity\": {\n          \"@id\": \"sm:commodity\"\n        },\n        \"instrumentType\": {\n          \"@id\": \"sm:instrumentType\"\n        },\n        \"periodStart\": {\n          \"@id\": \"schema:startDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"periodEnd\": {\n          \"@id\": \"schema:endDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"volumeMboepd\": {\n          \"@id\": \"sm:volumeMboepd\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"fixedPricePerBbl\": {\n          \"@id\": \"sm:fixedPricePerBbl\",\n          \"@type\": \"xsd:decimal\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/sm-energy/refs/heads/main/json-ld/sm-energy-context.jsonld
tags:
- Oil and Gas
- Energy
- Exploration
- Production
- Permian Basin
- JSON-LD
- Linked Data
- Semantic Web
---
