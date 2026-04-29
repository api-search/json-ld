---
api_specs:
- filename: blpapi-core.yml
  format: yaml
  label: Bloomberg BLPAPI Core
  slug: bloomberg-blpapi-core
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/bloomberg/refs/heads/main/openapi/blpapi-core.yml
class_count: 0
classes: []
context_file: json-ld/bloomberg-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/bloomberg/refs/heads/main/json-ld/bloomberg-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Bloomberg from Bloomberg.
layout: jsonld
name: Bloomberg Context
namespaces:
- prefix: bbg
  uri: https://www.bloomberg.com/ns/
- prefix: blpapi
  uri: https://bloomberg.github.io/blpapi-docs/ns/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: fibo-fnd
  uri: https://spec.edmcouncil.org/fibo/ontology/FND/
- prefix: fibo-sec
  uri: https://spec.edmcouncil.org/fibo/ontology/SEC/
properties:
- container: ''
  name: Security
  type: ''
- container: ''
  name: PricingSnapshot
  type: ''
- container: ''
  name: Fundamentals
  type: ''
- container: ''
  name: ReferenceData
  type: ''
- container: ''
  name: EsgScores
  type: ''
- container: ''
  name: CreditRating
  type: ''
- container: ''
  name: DividendData
  type: ''
- container: ''
  name: ReferenceDataResponse
  type: ''
- container: ''
  name: SecurityDataElement
  type: ''
- container: ''
  name: HistoricalDataResponse
  type: ''
- container: ''
  name: HistoricalDataPoint
  type: ''
- container: ''
  name: IntradayBar
  type: ''
- container: ''
  name: TickEvent
  type: ''
- container: ''
  name: MarketDataSubscriptionEvent
  type: ''
- container: ''
  name: FieldOverride
  type: ''
- container: ''
  name: FieldException
  type: ''
- container: ''
  name: SecurityError
  type: ''
property_count: 17
provider_name: Bloomberg
provider_slug: bloomberg
slug: bloomberg-context
source_filename: bloomberg-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"bbg\": \"https://www.bloomberg.com/ns/\",\n    \"blpapi\": \"https://bloomberg.github.io/blpapi-docs/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"fibo-fnd\": \"https://spec.edmcouncil.org/fibo/ontology/FND/\",\n    \"fibo-sec\": \"https://spec.edmcouncil.org/fibo/ontology/SEC/\",\n\n    \"Security\": {\n      \"@id\": \"fibo-sec:Security\",\n      \"@context\": {\n        \"bbuid\": \"bbg:bbuid\",\n        \"figi\": {\n          \"@id\": \"bbg:figi\",\n          \"@type\": \"xsd:string\"\n        },\n        \"ticker\": \"bbg:ticker\",\n        \"isin\": {\n          \"@id\": \"fibo-sec:ISIN\",\n          \"@type\": \"xsd:string\"\n        },\n        \"cusip\": {\n          \"@id\": \"bbg:cusip\",\n          \"@type\": \"xsd:string\"\n        },\n        \"sedol\": {\n          \"@id\": \"bbg:sedol\",\n       \
  \   \"@type\": \"xsd:string\"\n        },\n        \"name\": \"schema:name\",\n        \"shortName\": \"schema:alternateName\",\n        \"longCompanyName\": \"bbg:longCompanyName\",\n        \"securityDescription\": \"bbg:securityDescription\",\n        \"securityType\": \"bbg:securityType\",\n        \"exchange\": \"bbg:exchangeCode\",\n        \"currency\": \"bbg:currency\",\n        \"country\": {\n          \"@id\": \"schema:addressCountry\",\n          \"@type\": \"xsd:string\"\n        },\n        \"sector\": \"bbg:gicsSector\",\n        \"industryGroup\": \"bbg:gicsIndustryGroup\",\n        \"industry\": \"bbg:bicsIndustry\",\n        \"subIndustry\": \"bbg:gicsSubIndustry\",\n        \"marketCap\": {\n          \"@id\": \"bbg:marketCap\",\n          \"@type\": \"xsd:double\"\n        },\n        \"sharesOutstanding\": {\n          \"@id\": \"bbg:sharesOutstanding\",\n          \"@type\": \"xsd:double\"\n        },\n        \"active\": {\n          \"@id\": \"bbg:active\",\n  \
  \        \"@type\": \"xsd:boolean\"\n        },\n        \"pricing\": {\n          \"@id\": \"bbg:pricing\",\n          \"@type\": \"@id\"\n        },\n        \"fundamentals\": {\n          \"@id\": \"bbg:fundamentals\",\n          \"@type\": \"@id\"\n        },\n        \"referenceData\": {\n          \"@id\": \"bbg:referenceData\",\n          \"@type\": \"@id\"\n        },\n        \"esgScores\": {\n          \"@id\": \"bbg:esgScores\",\n          \"@type\": \"@id\"\n        },\n        \"creditRatings\": {\n          \"@id\": \"bbg:creditRating\",\n          \"@container\": \"@set\"\n        },\n        \"dividends\": {\n          \"@id\": \"bbg:dividends\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"PricingSnapshot\": {\n      \"@id\": \"blpapi:PricingSnapshot\",\n      \"@context\": {\n        \"lastPrice\": {\n          \"@id\": \"blpapi:pxLast\",\n          \"@type\": \"xsd:double\"\n        },\n        \"bidPrice\": {\n          \"@id\": \"blpapi:pxBid\"\
  ,\n          \"@type\": \"xsd:double\"\n        },\n        \"askPrice\": {\n          \"@id\": \"blpapi:pxAsk\",\n          \"@type\": \"xsd:double\"\n        },\n        \"midPrice\": {\n          \"@id\": \"blpapi:pxMid\",\n          \"@type\": \"xsd:double\"\n        },\n        \"openPrice\": {\n          \"@id\": \"blpapi:pxOpen\",\n          \"@type\": \"xsd:double\"\n        },\n        \"highPrice\": {\n          \"@id\": \"blpapi:pxHigh\",\n          \"@type\": \"xsd:double\"\n        },\n        \"lowPrice\": {\n          \"@id\": \"blpapi:pxLow\",\n          \"@type\": \"xsd:double\"\n        },\n        \"volume\": {\n          \"@id\": \"blpapi:volume\",\n          \"@type\": \"xsd:long\"\n        },\n        \"vwap\": {\n          \"@id\": \"blpapi:vwap\",\n          \"@type\": \"xsd:double\"\n        },\n        \"previousClose\": {\n          \"@id\": \"blpapi:previousClose\",\n          \"@type\": \"xsd:double\"\n        },\n        \"priceChange\": {\n          \"@id\"\
  : \"blpapi:netChg\",\n          \"@type\": \"xsd:double\"\n        },\n        \"priceChangePct\": {\n          \"@id\": \"blpapi:chgPct1d\",\n          \"@type\": \"xsd:double\"\n        },\n        \"fiftyTwoWeekHigh\": {\n          \"@id\": \"blpapi:high52Week\",\n          \"@type\": \"xsd:double\"\n        },\n        \"fiftyTwoWeekLow\": {\n          \"@id\": \"blpapi:low52Week\",\n          \"@type\": \"xsd:double\"\n        },\n        \"asOf\": {\n          \"@id\": \"blpapi:asOf\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Fundamentals\": {\n      \"@id\": \"blpapi:Fundamentals\",\n      \"@context\": {\n        \"earningsPerShare\": {\n          \"@id\": \"blpapi:epsAnnualized\",\n          \"@type\": \"xsd:double\"\n        },\n        \"priceToEarnings\": {\n          \"@id\": \"blpapi:peRatio\",\n          \"@type\": \"xsd:double\"\n        },\n        \"priceToBook\": {\n          \"@id\": \"blpapi:pxToBookRatio\",\n          \"@type\":\
  \ \"xsd:double\"\n        },\n        \"returnOnEquity\": {\n          \"@id\": \"blpapi:returnComEqy\",\n          \"@type\": \"xsd:double\"\n        },\n        \"debtToEquity\": {\n          \"@id\": \"blpapi:totDebtToComEqy\",\n          \"@type\": \"xsd:double\"\n        },\n        \"revenuePerShare\": {\n          \"@id\": \"blpapi:salesRevTurn\",\n          \"@type\": \"xsd:double\"\n        },\n        \"dividendYield\": {\n          \"@id\": \"blpapi:eqyDvdYldInd\",\n          \"@type\": \"xsd:double\"\n        },\n        \"beta\": {\n          \"@id\": \"blpapi:betaRaw\",\n          \"@type\": \"xsd:double\"\n        },\n        \"fiscalYearEnd\": {\n          \"@id\": \"blpapi:fiscalYearEnd\",\n          \"@type\": \"xsd:date\"\n        }\n      }\n    },\n\n    \"ReferenceData\": {\n      \"@id\": \"blpapi:ReferenceData\",\n      \"@context\": {\n        \"businessDescription\": \"bbg:businessDescription\",\n        \"numberOfEmployees\": {\n          \"@id\": \"bbg:numberOfEmployees\"\
  ,\n          \"@type\": \"xsd:integer\"\n        },\n        \"yearFounded\": {\n          \"@id\": \"bbg:yearFounded\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"headquarters\": \"bbg:headquarters\",\n        \"website\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"ceo\": \"bbg:ceo\",\n        \"bloombergIndustryGroup\": \"bbg:bicsIndustryGroup\",\n        \"bloombergSubIndustry\": \"bbg:bicsSubIndustry\",\n        \"companyAddress\": {\n          \"@id\": \"schema:address\",\n          \"@container\": \"@list\"\n        },\n        \"lei\": {\n          \"@id\": \"bbg:lei\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"EsgScores\": {\n      \"@id\": \"bbg:EsgScores\",\n      \"@context\": {\n        \"overallScore\": {\n          \"@id\": \"bbg:esgOverallScore\",\n          \"@type\": \"xsd:double\"\n        },\n        \"environmentalScore\": {\n          \"@id\": \"bbg:esgEnvironmentalScore\"\
  ,\n          \"@type\": \"xsd:double\"\n        },\n        \"socialScore\": {\n          \"@id\": \"bbg:esgSocialScore\",\n          \"@type\": \"xsd:double\"\n        },\n        \"governanceScore\": {\n          \"@id\": \"bbg:esgGovernanceScore\",\n          \"@type\": \"xsd:double\"\n        },\n        \"disclosureScore\": {\n          \"@id\": \"bbg:esgDisclosureScore\",\n          \"@type\": \"xsd:double\"\n        },\n        \"asOfDate\": {\n          \"@id\": \"dcterms:date\",\n          \"@type\": \"xsd:date\"\n        }\n      }\n    },\n\n    \"CreditRating\": {\n      \"@id\": \"bbg:CreditRating\",\n      \"@context\": {\n        \"agency\": \"bbg:ratingAgency\",\n        \"rating\": \"bbg:ratingSymbol\",\n        \"outlook\": \"bbg:ratingOutlook\",\n        \"ratedAt\": {\n          \"@id\": \"bbg:ratedAt\",\n          \"@type\": \"xsd:date\"\n        },\n        \"ratingType\": \"bbg:ratingType\"\n      }\n    },\n\n    \"DividendData\": {\n      \"@id\": \"bbg:DividendData\"\
  ,\n      \"@context\": {\n        \"indicatedAnnualDividend\": {\n          \"@id\": \"bbg:indicatedAnnualDividend\",\n          \"@type\": \"xsd:double\"\n        },\n        \"dividendFrequency\": \"bbg:dividendFrequency\",\n        \"exDividendDate\": {\n          \"@id\": \"bbg:exDividendDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"dividendPayDate\": {\n          \"@id\": \"bbg:dividendPayDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"dividendAmount\": {\n          \"@id\": \"bbg:dividendAmount\",\n          \"@type\": \"xsd:double\"\n        }\n      }\n    },\n\n    \"ReferenceDataResponse\": {\n      \"@id\": \"blpapi:ReferenceDataResponse\",\n      \"@context\": {\n        \"securityData\": {\n          \"@id\": \"blpapi:securityData\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"SecurityDataElement\": {\n      \"@id\": \"blpapi:SecurityDataElement\",\n      \"@context\": {\n        \"security\": \"bbg:ticker\"\
  ,\n        \"sequenceNumber\": {\n          \"@id\": \"blpapi:sequenceNumber\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"fieldData\": \"blpapi:fieldData\",\n        \"fieldExceptions\": {\n          \"@id\": \"blpapi:fieldException\",\n          \"@container\": \"@set\"\n        },\n        \"securityError\": {\n          \"@id\": \"blpapi:securityError\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"HistoricalDataResponse\": {\n      \"@id\": \"blpapi:HistoricalDataResponse\",\n      \"@context\": {\n        \"securityData\": {\n          \"@id\": \"blpapi:securityData\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"HistoricalDataPoint\": {\n      \"@id\": \"blpapi:HistoricalDataPoint\",\n      \"@context\": {\n        \"date\": {\n          \"@id\": \"dcterms:date\",\n          \"@type\": \"xsd:date\"\n        }\n      }\n    },\n\n    \"IntradayBar\": {\n      \"@id\": \"blpapi:IntradayBar\",\n      \"@context\": {\n  \
  \      \"time\": {\n          \"@id\": \"blpapi:barTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"open\": {\n          \"@id\": \"blpapi:barOpen\",\n          \"@type\": \"xsd:double\"\n        },\n        \"high\": {\n          \"@id\": \"blpapi:barHigh\",\n          \"@type\": \"xsd:double\"\n        },\n        \"low\": {\n          \"@id\": \"blpapi:barLow\",\n          \"@type\": \"xsd:double\"\n        },\n        \"close\": {\n          \"@id\": \"blpapi:barClose\",\n          \"@type\": \"xsd:double\"\n        },\n        \"volume\": {\n          \"@id\": \"blpapi:barVolume\",\n          \"@type\": \"xsd:long\"\n        },\n        \"value\": {\n          \"@id\": \"blpapi:barValue\",\n          \"@type\": \"xsd:double\"\n        },\n        \"numEvents\": {\n          \"@id\": \"blpapi:barNumEvents\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"TickEvent\": {\n      \"@id\": \"blpapi:TickEvent\",\n      \"@context\": {\n  \
  \      \"time\": {\n          \"@id\": \"blpapi:tickTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"type\": \"blpapi:tickType\",\n        \"value\": {\n          \"@id\": \"blpapi:tickValue\",\n          \"@type\": \"xsd:double\"\n        },\n        \"size\": {\n          \"@id\": \"blpapi:tickSize\",\n          \"@type\": \"xsd:long\"\n        },\n        \"conditionCodes\": \"blpapi:conditionCodes\",\n        \"exchangeCode\": \"blpapi:exchangeCode\"\n      }\n    },\n\n    \"MarketDataSubscriptionEvent\": {\n      \"@id\": \"blpapi:MarketDataSubscriptionEvent\",\n      \"@context\": {\n        \"security\": \"bbg:ticker\",\n        \"correlationId\": {\n          \"@id\": \"blpapi:correlationId\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"eventType\": \"blpapi:eventType\",\n        \"fields\": \"blpapi:subscriptionFields\",\n        \"timestamp\": {\n          \"@id\": \"blpapi:eventTimestamp\",\n          \"@type\": \"xsd:dateTime\"\n     \
  \   },\n        \"isDelayed\": {\n          \"@id\": \"blpapi:isDelayed\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"FieldOverride\": {\n      \"@id\": \"blpapi:FieldOverride\",\n      \"@context\": {\n        \"fieldId\": \"blpapi:overrideFieldId\",\n        \"value\": \"blpapi:overrideValue\"\n      }\n    },\n\n    \"FieldException\": {\n      \"@id\": \"blpapi:FieldException\",\n      \"@context\": {\n        \"fieldId\": \"blpapi:exceptionFieldId\",\n        \"errorInfo\": {\n          \"@id\": \"blpapi:errorInfo\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"SecurityError\": {\n      \"@id\": \"blpapi:SecurityError\",\n      \"@context\": {\n        \"source\": \"blpapi:errorSource\",\n        \"code\": {\n          \"@id\": \"blpapi:errorCode\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"category\": \"blpapi:errorCategory\",\n        \"message\": \"blpapi:errorMessage\",\n        \"subcategory\": \"blpapi:errorSubcategory\"\
  \n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/bloomberg/refs/heads/main/json-ld/bloomberg-context.jsonld
tags:
- Analytics
- Business Intelligence
- Data License
- Enterprise
- Execution Management
- Financial Services
- Market Data
- News
- Quantitative Analysis
- Trading
- Transaction Cost Analysis
- JSON-LD
- Linked Data
- Semantic Web
---
