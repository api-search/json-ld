---
class_count: 0
classes: []
context_file: json-ld/murex-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/murex/refs/heads/main/json-ld/murex-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Murex from Murex.
layout: jsonld
name: Murex Context
namespaces:
- prefix: murex
  uri: https://docs.murex.com/schemas/
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
  name: Trade
  type: ''
- container: ''
  name: Position
  type: ''
- container: ''
  name: Order
  type: ''
- container: ''
  name: Instrument
  type: ''
- container: ''
  name: Portfolio
  type: ''
- container: ''
  name: VaRResult
  type: ''
- container: ''
  name: RiskLimit
  type: ''
- container: ''
  name: Settlement
  type: ''
- container: ''
  name: Confirmation
  type: ''
- container: ''
  name: MarginCall
  type: ''
- container: ''
  name: CurveData
  type: ''
property_count: 11
provider_name: Murex
provider_slug: murex
slug: murex-context
source_filename: murex-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"murex\": \"https://docs.murex.com/schemas/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"fibo\": \"https://spec.edmcouncil.org/fibo/ontology/\",\n\n    \"Trade\": {\n      \"@id\": \"murex:Trade\",\n      \"@context\": {\n        \"tradeId\": \"murex:tradeId\",\n        \"externalTradeId\": \"murex:externalTradeId\",\n        \"status\": \"murex:tradeStatus\",\n        \"side\": \"murex:tradeSide\",\n        \"assetClass\": \"murex:assetClass\",\n        \"instrumentId\": \"murex:instrumentId\",\n        \"instrumentName\": \"schema:name\",\n        \"instrumentType\": \"murex:instrumentType\",\n        \"quantity\": {\n          \"@id\": \"murex:quantity\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"price\": {\n          \"@id\": \"murex:price\",\n          \"@type\": \"xsd:decimal\"\n        },\n\
  \        \"currency\": \"murex:currency\",\n        \"portfolioId\": \"murex:portfolioId\",\n        \"counterpartyName\": \"schema:name\",\n        \"tradeDate\": {\n          \"@id\": \"murex:tradeDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"valueDate\": {\n          \"@id\": \"murex:valueDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"maturityDate\": {\n          \"@id\": \"murex:maturityDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Position\": {\n      \"@id\": \"murex:Position\",\n      \"@context\": {\n        \"positionId\": \"murex:positionId\",\n        \"portfolioId\": \"murex:portfolioId\",\n        \"portfolioName\": \"schema:name\",\n        \"instrumentId\": \"murex:instrumentId\",\n        \"assetClass\": \"murex:assetClass\",\n        \"quantity\": {\n          \"@id\": \"murex:quantity\"\
  ,\n          \"@type\": \"xsd:decimal\"\n        },\n        \"marketValue\": {\n          \"@id\": \"murex:marketValue\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"unrealizedPnL\": {\n          \"@id\": \"murex:unrealizedPnL\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"realizedPnL\": {\n          \"@id\": \"murex:realizedPnL\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"currency\": \"murex:currency\",\n        \"asOfDate\": {\n          \"@id\": \"murex:asOfDate\",\n          \"@type\": \"xsd:date\"\n        }\n      }\n    },\n\n    \"Order\": {\n      \"@id\": \"murex:Order\",\n      \"@context\": {\n        \"orderId\": \"murex:orderId\",\n        \"status\": \"murex:orderStatus\",\n        \"side\": \"murex:tradeSide\",\n        \"instrumentId\": \"murex:instrumentId\",\n        \"quantity\": {\n          \"@id\": \"murex:quantity\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"price\": {\n          \"@id\": \"\
  murex:price\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"orderType\": \"murex:orderType\",\n        \"timeInForce\": \"murex:timeInForce\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Instrument\": {\n      \"@id\": \"murex:Instrument\",\n      \"@context\": {\n        \"instrumentId\": \"murex:instrumentId\",\n        \"name\": \"schema:name\",\n        \"assetClass\": \"murex:assetClass\",\n        \"instrumentType\": \"murex:instrumentType\",\n        \"currency\": \"murex:currency\",\n        \"isin\": \"murex:isin\",\n        \"ticker\": \"murex:ticker\",\n        \"maturityDate\": {\n          \"@id\": \"murex:maturityDate\",\n          \"@type\": \"xsd:date\"\n        }\n      }\n    },\n\n    \"Portfolio\": {\n      \"@id\": \"murex:Portfolio\",\n      \"@context\": {\n        \"portfolioId\": \"murex:portfolioId\",\n        \"name\": \"schema:name\",\n        \"\
  deskId\": \"murex:deskId\",\n        \"deskName\": \"schema:name\",\n        \"currency\": \"murex:currency\",\n        \"entity\": \"murex:legalEntity\"\n      }\n    },\n\n    \"VaRResult\": {\n      \"@id\": \"murex:VaRResult\",\n      \"@context\": {\n        \"method\": \"murex:varMethod\",\n        \"confidenceLevel\": {\n          \"@id\": \"murex:confidenceLevel\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"holdingPeriod\": {\n          \"@id\": \"murex:holdingPeriod\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"varAmount\": {\n          \"@id\": \"murex:varAmount\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"currency\": \"murex:currency\",\n        \"asOfDate\": {\n          \"@id\": \"murex:asOfDate\",\n          \"@type\": \"xsd:date\"\n        }\n      }\n    },\n\n    \"RiskLimit\": {\n      \"@id\": \"murex:RiskLimit\",\n      \"@context\": {\n        \"limitId\": \"murex:limitId\",\n        \"name\": \"schema:name\",\n\
  \        \"limitType\": \"murex:limitType\",\n        \"limitValue\": {\n          \"@id\": \"murex:limitValue\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"currentUtilization\": {\n          \"@id\": \"murex:currentUtilization\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"status\": \"murex:limitStatus\"\n      }\n    },\n\n    \"Settlement\": {\n      \"@id\": \"murex:Settlement\",\n      \"@context\": {\n        \"settlementId\": \"murex:settlementId\",\n        \"tradeId\": \"murex:tradeId\",\n        \"status\": \"murex:settlementStatus\",\n        \"amount\": {\n          \"@id\": \"murex:amount\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"currency\": \"murex:currency\",\n        \"direction\": \"murex:direction\",\n        \"settlementDate\": {\n          \"@id\": \"murex:settlementDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"paymentMethod\": \"murex:paymentMethod\"\n      }\n    },\n\n    \"Confirmation\"\
  : {\n      \"@id\": \"murex:Confirmation\",\n      \"@context\": {\n        \"confirmationId\": \"murex:confirmationId\",\n        \"tradeId\": \"murex:tradeId\",\n        \"status\": \"murex:confirmationStatus\",\n        \"confirmationType\": \"murex:confirmationType\",\n        \"counterpartyName\": \"schema:name\",\n        \"sentAt\": {\n          \"@id\": \"murex:sentAt\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"matchedAt\": {\n          \"@id\": \"murex:matchedAt\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"MarginCall\": {\n      \"@id\": \"murex:MarginCall\",\n      \"@context\": {\n        \"marginCallId\": \"murex:marginCallId\",\n        \"agreementId\": \"murex:agreementId\",\n        \"direction\": \"murex:direction\",\n        \"callAmount\": {\n          \"@id\": \"murex:callAmount\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"currency\": \"murex:currency\",\n        \"exposure\": {\n          \"@id\"\
  : \"murex:exposure\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"status\": \"murex:marginCallStatus\",\n        \"callDate\": {\n          \"@id\": \"murex:callDate\",\n          \"@type\": \"xsd:date\"\n        }\n      }\n    },\n\n    \"CurveData\": {\n      \"@id\": \"murex:CurveData\",\n      \"@context\": {\n        \"curveId\": \"murex:curveId\",\n        \"name\": \"schema:name\",\n        \"currency\": \"murex:currency\",\n        \"curveType\": \"murex:curveType\",\n        \"asOfDate\": {\n          \"@id\": \"murex:asOfDate\",\n          \"@type\": \"xsd:date\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/murex/refs/heads/main/json-ld/murex-context.jsonld
tags:
- Capital Markets
- Enterprise Software
- Financial Services
- Fintech
- Risk Management
- Trading
- JSON-LD
- Linked Data
- Semantic Web
---
