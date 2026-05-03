---
api_specs:
- filename: upvest-investment-api-openapi.yml
  format: yaml
  label: Upvest Investment API
  slug: investment-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/upvest/refs/heads/main/openapi/upvest-investment-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/upvest-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/upvest/refs/heads/main/json-ld/upvest-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Upvest from Upvest.
layout: jsonld
name: Upvest Context
namespaces:
- prefix: upvest
  uri: https://upvest.co/ns/
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
  name: User
  type: ''
- container: ''
  name: Account
  type: ''
- container: ''
  name: Instrument
  type: ''
- container: ''
  name: Order
  type: ''
- container: ''
  name: Portfolio
  type: ''
- container: ''
  name: Position
  type: ''
- container: ''
  name: SavingsPlan
  type: ''
- container: ''
  name: Execution
  type: ''
- container: ''
  name: CorporateAction
  type: ''
- container: ''
  name: WebhookEvent
  type: ''
property_count: 10
provider_name: Upvest
provider_slug: upvest
slug: upvest-context
source_filename: upvest-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"upvest\": \"https://upvest.co/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"fibo\": \"https://spec.edmcouncil.org/fibo/ontology/\",\n\n    \"User\": {\n      \"@id\": \"upvest:User\",\n      \"@context\": {\n        \"firstName\": \"schema:givenName\",\n        \"lastName\": \"schema:familyName\",\n        \"email\": \"schema:email\",\n        \"dateOfBirth\": {\n          \"@id\": \"schema:birthDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"nationality\": \"schema:nationality\",\n        \"address\": \"schema:address\",\n        \"status\": \"upvest:userStatus\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n       \
  \ }\n      }\n    },\n\n    \"Account\": {\n      \"@id\": \"upvest:InvestmentAccount\",\n      \"@context\": {\n        \"userId\": {\n          \"@id\": \"upvest:accountHolder\",\n          \"@type\": \"@id\"\n        },\n        \"accountGroupId\": {\n          \"@id\": \"upvest:accountGroup\",\n          \"@type\": \"@id\"\n        },\n        \"type\": \"upvest:accountType\",\n        \"status\": \"upvest:accountStatus\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Instrument\": {\n      \"@id\": \"upvest:FinancialInstrument\",\n      \"@context\": {\n        \"isin\": \"upvest:isin\",\n        \"wkn\": \"upvest:wkn\",\n        \"name\": \"schema:name\",\n        \"type\": \"upvest:instrumentType\",\n        \"currency\": \"schema:currency\",\n        \"exchanges\": {\n          \"@id\": \"upvest:tradedOn\",\n          \"@container\": \"@set\"\n        },\n        \"tradeable\": \"upvest:isTradeable\"\
  ,\n        \"fractionalTradingEnabled\": \"upvest:fractionalTradingEnabled\"\n      }\n    },\n\n    \"Order\": {\n      \"@id\": \"upvest:Order\",\n      \"@context\": {\n        \"accountId\": {\n          \"@id\": \"upvest:orderAccount\",\n          \"@type\": \"@id\"\n        },\n        \"instrumentId\": {\n          \"@id\": \"upvest:orderInstrument\",\n          \"@type\": \"@id\"\n        },\n        \"side\": \"upvest:orderSide\",\n        \"type\": \"upvest:orderType\",\n        \"status\": \"upvest:orderStatus\",\n        \"quantity\": {\n          \"@id\": \"upvest:orderQuantity\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"cashAmount\": {\n          \"@id\": \"upvest:cashAmount\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"limitPrice\": {\n          \"@id\": \"upvest:limitPrice\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"currency\": \"schema:currency\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\"\
  ,\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Portfolio\": {\n      \"@id\": \"upvest:Portfolio\",\n      \"@context\": {\n        \"accountId\": {\n          \"@id\": \"upvest:portfolioAccount\",\n          \"@type\": \"@id\"\n        },\n        \"name\": \"schema:name\",\n        \"status\": \"upvest:portfolioStatus\",\n        \"allocations\": {\n          \"@id\": \"upvest:targetAllocations\",\n          \"@container\": \"@set\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Position\": {\n      \"@id\": \"upvest:Position\",\n      \"@context\": {\n        \"accountId\": {\n          \"@id\": \"upvest:positionAccount\",\n          \"@type\": \"@id\"\n        },\n        \"instrumentId\": {\n          \"@id\": \"upvest:positionInstrument\",\n          \"@type\": \"@id\"\n        },\n        \"quantity\": {\n          \"@id\": \"upvest:holdingQuantity\"\
  ,\n          \"@type\": \"xsd:decimal\"\n        },\n        \"averageBuyInPrice\": {\n          \"@id\": \"upvest:averageCostBasis\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"currency\": \"schema:currency\"\n      }\n    },\n\n    \"SavingsPlan\": {\n      \"@id\": \"upvest:SavingsPlan\",\n      \"@context\": {\n        \"accountId\": {\n          \"@id\": \"upvest:savingsAccount\",\n          \"@type\": \"@id\"\n        },\n        \"portfolioId\": {\n          \"@id\": \"upvest:savingsPortfolio\",\n          \"@type\": \"@id\"\n        },\n        \"instrumentId\": {\n          \"@id\": \"upvest:savingsInstrument\",\n          \"@type\": \"@id\"\n        },\n        \"cashAmount\": {\n          \"@id\": \"upvest:recurringAmount\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"currency\": \"schema:currency\",\n        \"frequency\": \"schema:repeatFrequency\",\n        \"status\": \"upvest:savingsPlanStatus\",\n        \"nextExecutionDate\": {\n   \
  \       \"@id\": \"upvest:nextExecution\",\n          \"@type\": \"xsd:date\"\n        }\n      }\n    },\n\n    \"Execution\": {\n      \"@id\": \"upvest:Execution\",\n      \"@context\": {\n        \"orderId\": {\n          \"@id\": \"upvest:executionOrder\",\n          \"@type\": \"@id\"\n        },\n        \"quantity\": {\n          \"@id\": \"upvest:executedQuantity\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"price\": {\n          \"@id\": \"upvest:executionPrice\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"executedAt\": {\n          \"@id\": \"upvest:executionTimestamp\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"CorporateAction\": {\n      \"@id\": \"upvest:CorporateAction\",\n      \"@context\": {\n        \"instrumentId\": {\n          \"@id\": \"upvest:affectedInstrument\",\n          \"@type\": \"@id\"\n        },\n        \"type\": \"upvest:corporateActionType\",\n        \"recordDate\": {\n         \
  \ \"@id\": \"upvest:recordDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"exDate\": {\n          \"@id\": \"upvest:exDate\",\n          \"@type\": \"xsd:date\"\n        }\n      }\n    },\n\n    \"WebhookEvent\": {\n      \"@id\": \"upvest:WebhookEvent\",\n      \"@context\": {\n        \"eventType\": \"upvest:eventType\",\n        \"object\": {\n          \"@id\": \"upvest:affectedResource\",\n          \"@type\": \"@id\"\n        },\n        \"webhookId\": {\n          \"@id\": \"upvest:webhookSubscription\",\n          \"@type\": \"@id\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/upvest/refs/heads/main/json-ld/upvest-context.jsonld
tags:
- Banking Infrastructure
- Fintech
- Investments
- Securities
- JSON-LD
- Linked Data
- Semantic Web
---
