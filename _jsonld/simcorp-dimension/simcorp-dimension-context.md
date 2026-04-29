---
class_count: 0
classes: []
context_file: json-ld/simcorp-dimension-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/simcorp-dimension/refs/heads/main/json-ld/simcorp-dimension-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Simcorp Dimension from SimCorp Dimension.
layout: jsonld
name: Simcorp Dimension Context
namespaces:
- prefix: sim
  uri: https://thesim.dev/ns/
- prefix: schema
  uri: https://schema.org/
- prefix: fibo
  uri: https://spec.edmcouncil.org/fibo/ontology/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Portfolio
  type: ''
- container: ''
  name: Instrument
  type: ''
- container: ''
  name: Position
  type: ''
- container: ''
  name: Benchmark
  type: ''
- container: ''
  name: Issuer
  type: ''
- container: ''
  name: Exchange
  type: ''
- container: ''
  name: ValuationSummary
  type: ''
- container: ''
  name: Rating
  type: ''
property_count: 8
provider_name: SimCorp Dimension
provider_slug: simcorp-dimension
slug: simcorp-dimension-context
source_filename: simcorp-dimension-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"sim\": \"https://thesim.dev/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"fibo\": \"https://spec.edmcouncil.org/fibo/ontology/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Portfolio\": {\n      \"@id\": \"sim:Portfolio\",\n      \"@context\": {\n        \"portfolioId\": \"sim:portfolioId\",\n        \"portfolioCode\": {\n          \"@id\": \"sim:portfolioCode\",\n          \"@type\": \"xsd:string\"\n        },\n        \"portfolioName\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"portfolioType\": \"sim:portfolioType\",\n        \"portfolioStatus\": \"sim:portfolioStatus\",\n        \"baseCurrency\": {\n          \"@id\": \"sim:baseCurrency\",\n          \"@type\": \"xsd:string\"\n        },\n        \"inceptionDate\": {\n          \"@id\": \"sim:inceptionDate\",\n          \"@type\": \"xsd:date\"\
  \n        },\n        \"terminationDate\": {\n          \"@id\": \"sim:terminationDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"legalEntity\": {\n          \"@id\": \"sim:legalEntity\",\n          \"@type\": \"xsd:string\"\n        },\n        \"investmentManager\": {\n          \"@id\": \"sim:investmentManager\",\n          \"@type\": \"xsd:string\"\n        },\n        \"custodian\": {\n          \"@id\": \"sim:custodian\",\n          \"@type\": \"xsd:string\"\n        },\n        \"benchmark\": {\n          \"@id\": \"sim:benchmark\",\n          \"@type\": \"@id\"\n        },\n        \"investmentStrategy\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"assetClasses\": {\n          \"@id\": \"sim:assetClasses\",\n          \"@container\": \"@set\"\n        },\n        \"accountingMethod\": \"sim:accountingMethod\",\n        \"reportingCurrency\": {\n          \"@id\": \"sim:reportingCurrency\",\n       \
  \   \"@type\": \"xsd:string\"\n        },\n        \"positions\": {\n          \"@id\": \"sim:hasPosition\",\n          \"@container\": \"@set\"\n        },\n        \"createdDate\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"modifiedDate\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Instrument\": {\n      \"@id\": \"sim:Instrument\",\n      \"@context\": {\n        \"instrumentId\": \"sim:instrumentId\",\n        \"instrumentCode\": {\n          \"@id\": \"sim:instrumentCode\",\n          \"@type\": \"xsd:string\"\n        },\n        \"instrumentName\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"instrumentType\": \"sim:instrumentType\",\n        \"instrumentStatus\": \"sim:instrumentStatus\",\n        \"assetClass\": \"sim:assetClass\",\n        \"isin\": {\n          \"@id\": \"sim:isin\",\n\
  \          \"@type\": \"xsd:string\"\n        },\n        \"cusip\": {\n          \"@id\": \"sim:cusip\",\n          \"@type\": \"xsd:string\"\n        },\n        \"sedol\": {\n          \"@id\": \"sim:sedol\",\n          \"@type\": \"xsd:string\"\n        },\n        \"ticker\": {\n          \"@id\": \"sim:ticker\",\n          \"@type\": \"xsd:string\"\n        },\n        \"figi\": {\n          \"@id\": \"sim:figi\",\n          \"@type\": \"xsd:string\"\n        },\n        \"currency\": {\n          \"@id\": \"sim:currency\",\n          \"@type\": \"xsd:string\"\n        },\n        \"country\": {\n          \"@id\": \"sim:country\",\n          \"@type\": \"xsd:string\"\n        },\n        \"issuer\": {\n          \"@id\": \"sim:issuedBy\",\n          \"@type\": \"@id\"\n        },\n        \"exchange\": {\n          \"@id\": \"sim:listedOn\",\n          \"@type\": \"@id\"\n        },\n        \"couponRate\": {\n          \"@id\": \"sim:couponRate\",\n          \"@type\": \"xsd:decimal\"\
  \n        },\n        \"maturityDate\": {\n          \"@id\": \"sim:maturityDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"parValue\": {\n          \"@id\": \"sim:parValue\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"strikePrice\": {\n          \"@id\": \"sim:strikePrice\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"expirationDate\": {\n          \"@id\": \"sim:expirationDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"ratings\": {\n          \"@id\": \"sim:hasRating\",\n          \"@container\": \"@set\"\n        },\n        \"classifications\": {\n          \"@id\": \"sim:hasClassification\",\n          \"@type\": \"@id\"\n        },\n        \"createdDate\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"modifiedDate\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Position\": {\n\
  \      \"@id\": \"sim:Position\",\n      \"@context\": {\n        \"positionId\": \"sim:positionId\",\n        \"instrumentCode\": {\n          \"@id\": \"sim:holdsInstrument\",\n          \"@type\": \"xsd:string\"\n        },\n        \"instrumentName\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"quantity\": {\n          \"@id\": \"sim:quantity\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"marketValue\": {\n          \"@id\": \"sim:marketValue\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"costValue\": {\n          \"@id\": \"sim:costValue\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"accruedInterest\": {\n          \"@id\": \"sim:accruedInterest\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"unrealizedGainLoss\": {\n          \"@id\": \"sim:unrealizedGainLoss\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"weight\": {\n          \"@id\": \"sim:weight\"\
  ,\n          \"@type\": \"xsd:decimal\"\n        },\n        \"positionDate\": {\n          \"@id\": \"sim:positionDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"statusLevel\": \"sim:statusLevel\",\n        \"positionCurrency\": {\n          \"@id\": \"sim:positionCurrency\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"Benchmark\": {\n      \"@id\": \"sim:Benchmark\",\n      \"@context\": {\n        \"benchmarkCode\": {\n          \"@id\": \"sim:benchmarkCode\",\n          \"@type\": \"xsd:string\"\n        },\n        \"benchmarkName\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"benchmarkType\": \"sim:benchmarkType\"\n      }\n    },\n\n    \"Issuer\": {\n      \"@id\": \"sim:Issuer\",\n      \"@context\": {\n        \"issuerCode\": {\n          \"@id\": \"sim:issuerCode\",\n          \"@type\": \"xsd:string\"\n        },\n        \"issuerName\": {\n          \"@id\": \"schema:name\"\
  ,\n          \"@type\": \"xsd:string\"\n        },\n        \"issuerType\": \"sim:issuerType\",\n        \"issuerCountry\": {\n          \"@id\": \"sim:issuerCountry\",\n          \"@type\": \"xsd:string\"\n        },\n        \"creditRating\": {\n          \"@id\": \"sim:creditRating\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"Exchange\": {\n      \"@id\": \"sim:Exchange\",\n      \"@context\": {\n        \"exchangeCode\": {\n          \"@id\": \"sim:exchangeCode\",\n          \"@type\": \"xsd:string\"\n        },\n        \"exchangeName\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"listingDate\": {\n          \"@id\": \"sim:listingDate\",\n          \"@type\": \"xsd:date\"\n        }\n      }\n    },\n\n    \"ValuationSummary\": {\n      \"@id\": \"sim:ValuationSummary\",\n      \"@context\": {\n        \"valuationDate\": {\n          \"@id\": \"sim:valuationDate\",\n          \"@type\": \"xsd:date\"\
  \n        },\n        \"totalMarketValue\": {\n          \"@id\": \"sim:totalMarketValue\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"totalCostValue\": {\n          \"@id\": \"sim:totalCostValue\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"cashBalance\": {\n          \"@id\": \"sim:cashBalance\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"netAssetValue\": {\n          \"@id\": \"sim:netAssetValue\",\n          \"@type\": \"xsd:decimal\"\n        }\n      }\n    },\n\n    \"Rating\": {\n      \"@id\": \"sim:Rating\",\n      \"@context\": {\n        \"agency\": {\n          \"@id\": \"sim:ratingAgency\",\n          \"@type\": \"xsd:string\"\n        },\n        \"rating\": {\n          \"@id\": \"sim:ratingValue\",\n          \"@type\": \"xsd:string\"\n        },\n        \"ratingDate\": {\n          \"@id\": \"sim:ratingDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"outlook\": \"sim:ratingOutlook\"\n      }\n   \
  \ }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/simcorp-dimension/refs/heads/main/json-ld/simcorp-dimension-context.jsonld
tags:
- Accounting
- Asset Management
- Compliance
- Data Distribution
- Enterprise Software
- Financial Data
- Financial Technology
- Investment Management
- Portfolio Management
- Risk Management
- SimCorp One
- Streaming
- Trading
- JSON-LD
- Linked Data
- Semantic Web
---
