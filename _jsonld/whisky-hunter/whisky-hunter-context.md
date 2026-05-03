---
api_specs:
- filename: whisky-hunter-openapi.yml
  format: yaml
  label: Whisky Hunter API
  slug: whisky-hunter
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/whisky-hunter/refs/heads/main/openapi/whisky-hunter-openapi.yml
class_count: 40
classes:
- WhiskyAuction
- WhiskyDistillery
- AuctionDataPoint
- DistilleryDataPoint
- auctionSlug
- distillerySlug
- tradingVolume
- lotsCount
- allAuctionsLotsCount
- winningBidMax
- winningBidMin
- winningBidMean
- reservePrice
- currency
- scotchWhisky
- singleMalt
- blendedWhisky
- bourbon
- japaneseWhisky
- name
- description
- url
- identifier
- startDate
- endDate
- price
- priceCurrency
- seller
- winner
- numberOfItems
- category
- location
- countryOfOrigin
- AuctionEvent
- WinAction
- BuyAction
- Organization
- Product
- Offer
- PriceSpecification
context_file: json-ld/whisky-hunter-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/whisky-hunter/refs/heads/main/json-ld/whisky-hunter-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Whisky Hunter from Whisky Hunter.
layout: jsonld
name: Whisky Hunter Context
namespaces:
- prefix: wh
  uri: https://whiskyhunter.net/vocab#
- prefix: gs1
  uri: https://www.gs1.org/voc/
properties: []
property_count: 0
provider_name: Whisky Hunter
provider_slug: whisky-hunter
slug: whisky-hunter-context
source_filename: whisky-hunter-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"wh\": \"https://whiskyhunter.net/vocab#\",\n    \"gs1\": \"https://www.gs1.org/voc/\",\n\n    \"WhiskyAuction\": \"wh:WhiskyAuction\",\n    \"WhiskyDistillery\": \"wh:WhiskyDistillery\",\n    \"AuctionDataPoint\": \"wh:AuctionDataPoint\",\n    \"DistilleryDataPoint\": \"wh:DistilleryDataPoint\",\n\n    \"auctionSlug\": \"wh:auctionSlug\",\n    \"distillerySlug\": \"wh:distillerySlug\",\n    \"tradingVolume\": \"wh:tradingVolume\",\n    \"lotsCount\": \"wh:lotsCount\",\n    \"allAuctionsLotsCount\": \"wh:allAuctionsLotsCount\",\n    \"winningBidMax\": \"wh:winningBidMax\",\n    \"winningBidMin\": \"wh:winningBidMin\",\n    \"winningBidMean\": \"wh:winningBidMean\",\n    \"reservePrice\": \"wh:reservePrice\",\n    \"currency\": \"wh:currency\",\n    \"scotchWhisky\": \"wh:scotchWhisky\",\n    \"singleMalt\": \"wh:singleMalt\",\n    \"blendedWhisky\": \"wh:blendedWhisky\",\n    \"bourbon\": \"wh:bourbon\",\n\
  \    \"japaneseWhisky\": \"wh:japaneseWhisky\",\n\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"identifier\": \"schema:identifier\",\n    \"startDate\": \"schema:startDate\",\n    \"endDate\": \"schema:endDate\",\n    \"price\": \"schema:price\",\n    \"priceCurrency\": \"schema:priceCurrency\",\n    \"seller\": \"schema:seller\",\n    \"winner\": \"schema:winner\",\n    \"numberOfItems\": \"schema:numberOfItems\",\n    \"category\": \"schema:category\",\n    \"location\": \"schema:location\",\n    \"countryOfOrigin\": \"schema:countryOfOrigin\",\n\n    \"AuctionEvent\": \"schema:AuctionEvent\",\n    \"WinAction\": \"schema:WinAction\",\n    \"BuyAction\": \"schema:BuyAction\",\n    \"Organization\": \"schema:Organization\",\n    \"Product\": \"schema:Product\",\n    \"Offer\": \"schema:Offer\",\n    \"PriceSpecification\": \"schema:PriceSpecification\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/whisky-hunter/refs/heads/main/json-ld/whisky-hunter-context.jsonld
tags:
- Whisky
- Spirits
- Auctions
- Market Data
- Collectors
- Investors
- JSON-LD
- Linked Data
- Semantic Web
---
