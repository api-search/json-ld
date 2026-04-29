---
class_count: 0
classes: []
context_file: json-ld/bloomberg-emsx-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/bloomberg-emsx/refs/heads/main/json-ld/bloomberg-emsx-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Bloomberg Emsx from Bloomberg EMSX.
layout: jsonld
name: Bloomberg Emsx Context
namespaces:
- prefix: emsx
  uri: https://www.bloomberg.com/schemas/emsx/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: fibo
  uri: https://spec.edmcouncil.org/fibo/ontology/FND/
properties:
- container: ''
  name: Order
  type: ''
- container: ''
  name: Route
  type: ''
- container: ''
  name: Fill
  type: ''
- container: ''
  name: Broker
  type: ''
- container: ''
  name: BrokerStrategy
  type: ''
- container: ''
  name: Team
  type: ''
property_count: 6
provider_name: Bloomberg EMSX
provider_slug: bloomberg-emsx
slug: bloomberg-emsx-context
source_filename: bloomberg-emsx-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"emsx\": \"https://www.bloomberg.com/schemas/emsx/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"fibo\": \"https://spec.edmcouncil.org/fibo/ontology/FND/\",\n\n    \"Order\": {\n      \"@id\": \"emsx:Order\",\n      \"@context\": {\n        \"sequenceNumber\": \"emsx:sequenceNumber\",\n        \"ticker\": \"emsx:ticker\",\n        \"side\": \"emsx:side\",\n        \"amount\": {\n          \"@id\": \"emsx:amount\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"orderType\": \"emsx:orderType\",\n        \"limitPrice\": {\n          \"@id\": \"emsx:limitPrice\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"stopPrice\": {\n          \"@id\": \"emsx:stopPrice\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"timeInForce\": \"emsx:timeInForce\",\n        \"status\": \"emsx:orderStatus\"\
  ,\n        \"filledAmount\": {\n          \"@id\": \"emsx:filledAmount\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"averagePrice\": {\n          \"@id\": \"emsx:averagePrice\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"remainingAmount\": {\n          \"@id\": \"emsx:remainingAmount\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"assetClass\": \"emsx:assetClass\",\n        \"exchange\": \"emsx:exchange\",\n        \"currency\": \"emsx:currency\",\n        \"account\": \"emsx:account\",\n        \"notes\": \"schema:description\",\n        \"traderName\": \"schema:name\",\n        \"createdTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"lastModifiedTime\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Route\": {\n      \"@id\": \"emsx:Route\",\n      \"@context\": {\n        \"routeId\": \"emsx:routeId\"\
  ,\n        \"orderSequenceNumber\": \"emsx:orderSequenceNumber\",\n        \"ticker\": \"emsx:ticker\",\n        \"side\": \"emsx:side\",\n        \"amount\": {\n          \"@id\": \"emsx:amount\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"filledAmount\": {\n          \"@id\": \"emsx:filledAmount\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"averagePrice\": {\n          \"@id\": \"emsx:averagePrice\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"broker\": \"emsx:brokerCode\",\n        \"brokerName\": \"schema:name\",\n        \"strategy\": \"emsx:strategy\",\n        \"status\": \"emsx:routeStatus\",\n        \"limitPrice\": {\n          \"@id\": \"emsx:limitPrice\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"exchange\": \"emsx:exchange\",\n        \"createdTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"lastModifiedTime\": {\n          \"@id\": \"dcterms:modified\"\
  ,\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"lastFillTime\": {\n          \"@id\": \"emsx:lastFillTime\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Fill\": {\n      \"@id\": \"emsx:Fill\",\n      \"@context\": {\n        \"fillId\": \"emsx:fillId\",\n        \"orderSequenceNumber\": \"emsx:orderSequenceNumber\",\n        \"routeId\": \"emsx:routeId\",\n        \"ticker\": \"emsx:ticker\",\n        \"side\": \"emsx:side\",\n        \"fillAmount\": {\n          \"@id\": \"emsx:fillAmount\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"fillPrice\": {\n          \"@id\": \"emsx:fillPrice\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"broker\": \"emsx:brokerCode\",\n        \"brokerName\": \"schema:name\",\n        \"exchange\": \"emsx:exchange\",\n        \"currency\": \"emsx:currency\",\n        \"settlementDate\": {\n          \"@id\": \"emsx:settlementDate\",\n          \"@type\": \"xsd:date\"\n      \
  \  },\n        \"tradeDate\": {\n          \"@id\": \"emsx:tradeDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"fillTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"account\": \"emsx:account\",\n        \"isManual\": {\n          \"@id\": \"emsx:isManual\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"contraParty\": \"emsx:contraParty\"\n      }\n    },\n\n    \"Broker\": {\n      \"@id\": \"emsx:Broker\",\n      \"@context\": {\n        \"code\": \"emsx:brokerCode\",\n        \"name\": \"schema:name\",\n        \"assetClasses\": \"emsx:assetClasses\",\n        \"supportsAlgoTrading\": {\n          \"@id\": \"emsx:supportsAlgoTrading\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"isActive\": {\n          \"@id\": \"emsx:isActive\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"BrokerStrategy\": {\n      \"@id\": \"emsx:BrokerStrategy\",\n     \
  \ \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\"\n      }\n    },\n\n    \"Team\": {\n      \"@id\": \"emsx:Team\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/bloomberg-emsx/refs/heads/main/json-ld/bloomberg-emsx-context.jsonld
tags:
- Bloomberg
- Execution Management
- Financial Services
- Order Management
- Trading
- JSON-LD
- Linked Data
- Semantic Web
---
