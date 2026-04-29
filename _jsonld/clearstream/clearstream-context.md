---
class_count: 0
classes: []
context_file: json-ld/clearstream-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/clearstream/refs/heads/main/json-ld/clearstream-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Clearstream from Clearstream.
layout: jsonld
name: Clearstream Context
namespaces:
- prefix: clearstream
  uri: https://www.clearstream.com/ns/
- prefix: iso20022
  uri: https://www.iso20022.org/standardsrepository/
- prefix: iso15022
  uri: https://www.iso20022.org/15022/
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
  name: SettlementInstruction
  type: ''
- container: ''
  name: CustodyAccount
  type: ''
- container: ''
  name: CorporateAction
  type: ''
- container: ''
  name: CollateralPosition
  type: ''
- container: ''
  name: FundOrder
  type: ''
- container: ''
  name: Statement
  type: ''
property_count: 6
provider_name: Clearstream
provider_slug: clearstream
slug: clearstream-context
source_filename: clearstream-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"clearstream\": \"https://www.clearstream.com/ns/\",\n    \"iso20022\": \"https://www.iso20022.org/standardsrepository/\",\n    \"iso15022\": \"https://www.iso20022.org/15022/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"fibo\": \"https://spec.edmcouncil.org/fibo/ontology/\",\n\n    \"SettlementInstruction\": {\n      \"@id\": \"clearstream:SettlementInstruction\",\n      \"@context\": {\n        \"messageId\": \"iso20022:MessageIdentification\",\n        \"messageType\": \"iso15022:MessageType\",\n        \"tradeDate\": {\n          \"@id\": \"iso20022:TradeDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"settlementDate\": {\n          \"@id\": \"iso20022:SettlementDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"isin\": \"fibo:ISIN\",\n        \"quantity\": \"iso20022:SettlementQuantity\"\
  ,\n        \"amount\": \"iso20022:SettlementAmount\",\n        \"currency\": \"iso20022:SettlementCurrency\",\n        \"deliveryType\": \"clearstream:delivery_type\",\n        \"counterparty\": \"iso20022:Counterparty\",\n        \"safekeepingAccount\": \"clearstream:safekeeping_account\"\n      }\n    },\n\n    \"CustodyAccount\": {\n      \"@id\": \"clearstream:CustodyAccount\",\n      \"@context\": {\n        \"accountNumber\": \"clearstream:account_number\",\n        \"accountName\": \"schema:name\",\n        \"ownerBic\": \"iso20022:BIC\",\n        \"openingDate\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:date\"\n        },\n        \"marketAccess\": {\n          \"@id\": \"clearstream:market_access\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"CorporateAction\": {\n      \"@id\": \"clearstream:CorporateAction\",\n      \"@context\": {\n        \"eventId\": \"iso20022:CorporateActionEventIdentification\",\n        \"eventType\"\
  : \"iso20022:EventType\",\n        \"isin\": \"fibo:ISIN\",\n        \"recordDate\": {\n          \"@id\": \"iso20022:RecordDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"exDate\": {\n          \"@id\": \"iso20022:ExDividendDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"paymentDate\": {\n          \"@id\": \"iso20022:PaymentDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"mandatoryVoluntary\": \"iso20022:MandatoryVoluntaryEventType\"\n      }\n    },\n\n    \"CollateralPosition\": {\n      \"@id\": \"clearstream:CollateralPosition\",\n      \"@context\": {\n        \"exposureId\": \"iso20022:ExposureIdentification\",\n        \"exposureType\": \"iso20022:ExposureType\",\n        \"collateralGiver\": \"iso20022:CollateralGiver\",\n        \"collateralTaker\": \"iso20022:CollateralTaker\",\n        \"marketValue\": \"iso20022:MarketValue\",\n        \"haircut\": \"clearstream:haircut\",\n        \"currency\": \"iso20022:Currency\"\n\
  \      }\n    },\n\n    \"FundOrder\": {\n      \"@id\": \"clearstream:FundOrder\",\n      \"@context\": {\n        \"orderId\": \"iso20022:OrderReference\",\n        \"orderType\": \"iso20022:OrderType\",\n        \"isin\": \"fibo:ISIN\",\n        \"tradeDate\": {\n          \"@id\": \"iso20022:TradeDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"amount\": \"iso20022:NetAmount\",\n        \"units\": \"iso20022:UnitsNumber\",\n        \"investor\": \"iso20022:Investor\"\n      }\n    },\n\n    \"Statement\": {\n      \"@id\": \"clearstream:Statement\",\n      \"@context\": {\n        \"statementId\": \"iso20022:StatementIdentification\",\n        \"statementType\": \"iso20022:StatementType\",\n        \"asOfDate\": {\n          \"@id\": \"iso20022:StatementDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"account\": \"clearstream:account_number\",\n        \"format\": \"schema:encodingFormat\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/clearstream/refs/heads/main/json-ld/clearstream-context.jsonld
tags:
- Capital Markets
- Collateral Management
- Custody
- Financial Services
- ISO 15022
- ISO 20022
- Post-Trade Infrastructure
- Securities
- Settlement
- SWIFT
- JSON-LD
- Linked Data
- Semantic Web
---
