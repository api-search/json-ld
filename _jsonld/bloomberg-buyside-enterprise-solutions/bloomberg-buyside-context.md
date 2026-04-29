---
class_count: 0
classes: []
context_file: json-ld/bloomberg-buyside-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/bloomberg-buyside-enterprise-solutions/refs/heads/main/json-ld/bloomberg-buyside-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Bloomberg Buyside from Bloomberg Buyside Enterprise Solutions.
layout: jsonld
name: Bloomberg Buyside Context
namespaces:
- prefix: bloomberg
  uri: https://www.bloomberg.com/schemas/buyside/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: fibo
  uri: https://spec.edmcouncil.org/fibo/ontology/
properties:
- container: ''
  name: Portfolio
  type: ''
- container: ''
  name: Holding
  type: ''
- container: ''
  name: Security
  type: ''
- container: ''
  name: Order
  type: ''
- container: ''
  name: Execution
  type: ''
- container: ''
  name: CorporateAction
  type: ''
- container: ''
  name: YieldCurve
  type: ''
- container: ''
  name: Benchmark
  type: ''
- container: ''
  name: ComplianceRule
  type: ''
property_count: 9
provider_name: Bloomberg Buyside Enterprise Solutions
provider_slug: bloomberg-buyside-enterprise-solutions
slug: bloomberg-buyside-context
source_filename: bloomberg-buyside-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"bloomberg\": \"https://www.bloomberg.com/schemas/buyside/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"fibo\": \"https://spec.edmcouncil.org/fibo/ontology/\",\n\n    \"Portfolio\": {\n      \"@id\": \"bloomberg:Portfolio\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"type\": \"bloomberg:portfolioType\",\n        \"status\": \"bloomberg:portfolioStatus\",\n        \"currency\": \"bloomberg:baseCurrency\",\n        \"benchmarkId\": \"bloomberg:benchmarkId\",\n        \"manager\": \"bloomberg:portfolioManager\",\n        \"inceptionDate\": {\n          \"@id\": \"bloomberg:inceptionDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"totalMarketValue\": {\n          \"@id\": \"bloomberg:totalMarketValue\",\n          \"@type\": \"\
  xsd:decimal\"\n        },\n        \"holdingsCount\": {\n          \"@id\": \"bloomberg:holdingsCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Holding\": {\n      \"@id\": \"bloomberg:Holding\",\n      \"@context\": {\n        \"security\": \"bloomberg:securityIdentifier\",\n        \"name\": \"schema:name\",\n        \"assetClass\": \"bloomberg:assetClass\",\n        \"quantity\": {\n          \"@id\": \"bloomberg:quantity\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"marketValue\": {\n          \"@id\": \"bloomberg:marketValue\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"costBasis\": {\n          \"@id\": \"bloomberg:costBasis\",\n          \"@type\": \"xsd:decimal\"\n        },\n\
  \        \"weight\": {\n          \"@id\": \"bloomberg:portfolioWeight\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"unrealizedGainLoss\": {\n          \"@id\": \"bloomberg:unrealizedGainLoss\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"sector\": \"bloomberg:gicsSector\",\n        \"country\": \"bloomberg:countryOfRisk\",\n        \"currency\": \"bloomberg:tradingCurrency\"\n      }\n    },\n\n    \"Security\": {\n      \"@id\": \"bloomberg:Security\",\n      \"@context\": {\n        \"ticker\": \"bloomberg:ticker\",\n        \"name\": \"schema:name\",\n        \"assetClass\": \"bloomberg:assetClass\",\n        \"securityType\": \"bloomberg:securityType\",\n        \"exchange\": \"bloomberg:primaryExchange\",\n        \"country\": \"bloomberg:countryOfDomicile\",\n        \"currency\": \"bloomberg:tradingCurrency\",\n        \"issuer\": \"bloomberg:issuerName\",\n        \"issueDate\": {\n          \"@id\": \"bloomberg:issueDate\",\n          \"@type\"\
  : \"xsd:date\"\n        },\n        \"maturityDate\": {\n          \"@id\": \"bloomberg:maturityDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"couponRate\": {\n          \"@id\": \"bloomberg:couponRate\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"marketCap\": {\n          \"@id\": \"bloomberg:marketCapitalization\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"active\": {\n          \"@id\": \"bloomberg:isActive\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"Order\": {\n      \"@id\": \"bloomberg:Order\",\n      \"@context\": {\n        \"security\": \"bloomberg:securityIdentifier\",\n        \"side\": \"bloomberg:orderSide\",\n        \"orderType\": \"bloomberg:orderType\",\n        \"quantity\": {\n          \"@id\": \"bloomberg:orderQuantity\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"filledQuantity\": {\n          \"@id\": \"bloomberg:filledQuantity\",\n          \"@type\": \"xsd:decimal\"\
  \n        },\n        \"limitPrice\": {\n          \"@id\": \"bloomberg:limitPrice\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"stopPrice\": {\n          \"@id\": \"bloomberg:stopPrice\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"averageFillPrice\": {\n          \"@id\": \"bloomberg:averageFillPrice\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"status\": \"bloomberg:orderStatus\",\n        \"timeInForce\": \"bloomberg:timeInForce\",\n        \"portfolioId\": \"bloomberg:portfolioId\",\n        \"brokerId\": \"bloomberg:brokerId\",\n        \"algorithm\": \"bloomberg:algorithmName\",\n        \"trader\": \"bloomberg:traderId\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Execution\": {\n      \"@id\": \"bloomberg:Execution\",\n      \"@context\": {\n        \"orderId\": \"bloomberg:orderId\",\n        \"security\": \"bloomberg:securityIdentifier\"\
  ,\n        \"side\": \"bloomberg:orderSide\",\n        \"quantity\": {\n          \"@id\": \"bloomberg:executedQuantity\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"price\": {\n          \"@id\": \"bloomberg:executionPrice\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"commission\": {\n          \"@id\": \"bloomberg:commission\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"netAmount\": {\n          \"@id\": \"bloomberg:netAmount\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"venue\": \"bloomberg:executionVenue\",\n        \"broker\": \"bloomberg:executingBroker\",\n        \"settlementDate\": {\n          \"@id\": \"bloomberg:settlementDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"executedAt\": {\n          \"@id\": \"bloomberg:executionTimestamp\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"CorporateAction\": {\n      \"@id\": \"bloomberg:CorporateAction\",\n    \
  \  \"@context\": {\n        \"actionType\": \"bloomberg:corporateActionType\",\n        \"announcementDate\": {\n          \"@id\": \"bloomberg:announcementDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"effectiveDate\": {\n          \"@id\": \"bloomberg:effectiveDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"recordDate\": {\n          \"@id\": \"bloomberg:recordDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"paymentDate\": {\n          \"@id\": \"bloomberg:paymentDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"amount\": {\n          \"@id\": \"bloomberg:actionAmount\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"currency\": \"bloomberg:actionCurrency\",\n        \"description\": \"schema:description\"\n      }\n    },\n\n    \"YieldCurve\": {\n      \"@id\": \"bloomberg:YieldCurve\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"currency\": \"bloomberg:curveCurrency\",\n \
  \       \"type\": \"bloomberg:curveType\",\n        \"country\": \"bloomberg:curveCountry\",\n        \"asOfDate\": {\n          \"@id\": \"bloomberg:curveDate\",\n          \"@type\": \"xsd:date\"\n        }\n      }\n    },\n\n    \"Benchmark\": {\n      \"@id\": \"bloomberg:Benchmark\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"ticker\": \"bloomberg:ticker\",\n        \"assetClass\": \"bloomberg:assetClass\",\n        \"currency\": \"bloomberg:baseCurrency\",\n        \"provider\": \"bloomberg:indexProvider\"\n      }\n    },\n\n    \"ComplianceRule\": {\n      \"@id\": \"bloomberg:ComplianceRule\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"type\": \"bloomberg:complianceRuleType\",\n        \"status\": \"bloomberg:ruleStatus\",\n        \"threshold\": {\n          \"@id\": \"bloomberg:ruleThreshold\",\n          \"@type\": \"xsd:decimal\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/bloomberg-buyside-enterprise-solutions/refs/heads/main/json-ld/bloomberg-buyside-context.jsonld
tags:
- Analytics
- Asset Management
- Buy-Side
- Enterprise Solutions
- Financial Services
- Market Data
- Portfolio Management
- Trading
- JSON-LD
- Linked Data
- Semantic Web
---
