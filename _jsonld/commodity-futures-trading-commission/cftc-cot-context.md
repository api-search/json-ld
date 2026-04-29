---
api_specs:
- filename: cftc-cot-openapi.yml
  format: yaml
  label: CFTC Commitments of Traders SODA API
  slug: cftc-cot-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/commodity-futures-trading-commission/refs/heads/main/openapi/cftc-cot-openapi.yml
class_count: 0
classes: []
context_file: json-ld/cftc-cot-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/commodity-futures-trading-commission/refs/heads/main/json-ld/cftc-cot-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Cftc Cot from Commodity Futures Trading Commission.
layout: jsonld
name: Cftc Cot Context
namespaces:
- prefix: cftc
  uri: https://publicreporting.cftc.gov/vocabulary#
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: CotReport
  type: ''
- container: ''
  name: LegacyCot
  type: ''
- container: ''
  name: DisaggregatedCot
  type: ''
- container: ''
  name: TffCot
  type: ''
- container: ''
  name: SupplementalCot
  type: ''
property_count: 5
provider_name: Commodity Futures Trading Commission
provider_slug: commodity-futures-trading-commission
slug: cftc-cot-context
source_filename: cftc-cot-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"cftc\": \"https://publicreporting.cftc.gov/vocabulary#\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"CotReport\": {\n      \"@id\": \"cftc:CommitmentsOfTradersReport\",\n      \"@context\": {\n        \"marketAndExchange\": \"cftc:marketAndExchangeNames\",\n        \"reportDate\": {\n          \"@id\": \"dcterms:date\",\n          \"@type\": \"xsd:date\"\n        },\n        \"contractMarketCode\": \"cftc:contractMarketCode\",\n        \"marketCode\": \"cftc:marketCode\",\n        \"regionCode\": \"cftc:regionCode\",\n        \"commodityCode\": \"cftc:commodityCode\",\n        \"openInterest\": {\n          \"@id\": \"cftc:openInterest\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"LegacyCot\": {\n      \"@id\": \"cftc:LegacyCot\",\n      \"@context\": {\n        \"noncommercialLong\"\
  : \"cftc:noncommPositionsLongAll\",\n        \"noncommercialShort\": \"cftc:noncommPositionsShortAll\",\n        \"commercialLong\": \"cftc:commPositionsLongAll\",\n        \"commercialShort\": \"cftc:commPositionsShortAll\",\n        \"nonReportableLong\": \"cftc:nonreptPositionsLongAll\",\n        \"nonReportableShort\": \"cftc:nonreptPositionsShortAll\"\n      }\n    },\n\n    \"DisaggregatedCot\": {\n      \"@id\": \"cftc:DisaggregatedCot\",\n      \"@context\": {\n        \"producerMerchantLong\": \"cftc:prodMercPositionsLongAll\",\n        \"producerMerchantShort\": \"cftc:prodMercPositionsShortAll\",\n        \"swapDealerLong\": \"cftc:swapPositionsLongAll\",\n        \"swapDealerShort\": \"cftc:swapPositionsShortAll\",\n        \"managedMoneyLong\": \"cftc:mMoneyPositionsLongAll\",\n        \"managedMoneyShort\": \"cftc:mMoneyPositionsShortAll\",\n        \"otherReportableLong\": \"cftc:otherReptPositionsLong\",\n        \"otherReportableShort\": \"cftc:otherReptPositionsShort\"\
  \n      }\n    },\n\n    \"TffCot\": {\n      \"@id\": \"cftc:TffCot\",\n      \"@context\": {\n        \"dealerLong\": \"cftc:dealerPositionsLongAll\",\n        \"dealerShort\": \"cftc:dealerPositionsShortAll\",\n        \"assetManagerLong\": \"cftc:assetMgrPositionsLong\",\n        \"assetManagerShort\": \"cftc:assetMgrPositionsShort\",\n        \"leveragedFundLong\": \"cftc:levMoneyPositionsLong\",\n        \"leveragedFundShort\": \"cftc:levMoneyPositionsShort\",\n        \"otherReportableLong\": \"cftc:otherReptPositionsLong\",\n        \"otherReportableShort\": \"cftc:otherReptPositionsShort\"\n      }\n    },\n\n    \"SupplementalCot\": {\n      \"@id\": \"cftc:SupplementalCot\",\n      \"@context\": {\n        \"commodityIndexTraderLong\": \"cftc:citPositionsLongAll\",\n        \"commodityIndexTraderShort\": \"cftc:citPositionsShortAll\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/commodity-futures-trading-commission/refs/heads/main/json-ld/cftc-cot-context.jsonld
tags:
- CFTC
- Commitments of Traders
- Federal Government
- Financial
- Futures
- Open Data
- SODA
- Trading
- JSON-LD
- Linked Data
- Semantic Web
---
