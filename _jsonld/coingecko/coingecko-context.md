---
api_specs:
- filename: coingecko-crypto-market-data-api-openapi.yml
  format: yaml
  label: CoinGecko Crypto Market Data API
  slug: crypto-market-data-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/coingecko/refs/heads/main/openapi/coingecko-crypto-market-data-api-openapi.yml
- filename: coingecko-pro-api-openapi.yml
  format: yaml
  label: CoinGecko Pro API
  slug: pro-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/coingecko/refs/heads/main/openapi/coingecko-pro-api-openapi.yml
- filename: coingecko-onchain-dex-api-openapi.yml
  format: yaml
  label: CoinGecko Onchain DEX API
  slug: onchain-dex-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/coingecko/refs/heads/main/openapi/coingecko-onchain-dex-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/coingecko-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/coingecko/refs/heads/main/json-ld/coingecko-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Coingecko from CoinGecko.
layout: jsonld
name: Coingecko Context
namespaces:
- prefix: cg
  uri: https://api.coingecko.com/api/v3/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Coin
  type: ''
- container: ''
  name: MarketData
  type: ''
- container: ''
  name: Exchange
  type: ''
- container: ''
  name: NFTCollection
  type: ''
- container: ''
  name: LiquidityPool
  type: ''
- container: ''
  name: AssetPlatform
  type: ''
- container: ''
  name: DerivativeTicker
  type: ''
property_count: 7
provider_name: CoinGecko
provider_slug: coingecko
slug: coingecko-context
source_filename: coingecko-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"cg\": \"https://api.coingecko.com/api/v3/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Coin\": {\n      \"@id\": \"cg:Coin\",\n      \"@context\": {\n        \"id\": \"cg:coinId\",\n        \"symbol\": \"cg:symbol\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"image\": {\n          \"@id\": \"schema:image\",\n          \"@type\": \"@id\"\n        },\n        \"homepage\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"genesisDate\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:date\"\n        },\n        \"categories\": {\n          \"@id\": \"schema:category\",\n          \"@container\": \"@set\"\n        },\n        \"marketCapRank\": {\n          \"@id\": \"cg:marketCapRank\",\n          \"\
  @type\": \"xsd:integer\"\n        },\n        \"lastUpdated\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"MarketData\": {\n      \"@id\": \"cg:MarketData\",\n      \"@context\": {\n        \"currentPrice\": \"cg:currentPrice\",\n        \"marketCap\": \"cg:marketCap\",\n        \"totalVolume\": \"cg:totalVolume\",\n        \"circulatingSupply\": \"cg:circulatingSupply\",\n        \"totalSupply\": \"cg:totalSupply\",\n        \"maxSupply\": \"cg:maxSupply\",\n        \"allTimeHigh\": \"cg:allTimeHigh\",\n        \"allTimeLow\": \"cg:allTimeLow\",\n        \"priceChange24h\": \"cg:priceChange24h\",\n        \"priceChangePercentage24h\": \"cg:priceChangePercentage24h\",\n        \"fullyDilutedValuation\": \"cg:fullyDilutedValuation\"\n      }\n    },\n\n    \"Exchange\": {\n      \"@id\": \"cg:Exchange\",\n      \"@context\": {\n        \"id\": \"cg:exchangeId\",\n        \"name\": \"schema:name\",\n        \"description\"\
  : \"schema:description\",\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"country\": \"schema:addressCountry\",\n        \"yearEstablished\": {\n          \"@id\": \"schema:foundingDate\",\n          \"@type\": \"xsd:gYear\"\n        },\n        \"trustScore\": \"cg:trustScore\",\n        \"trustScoreRank\": \"cg:trustScoreRank\",\n        \"tradeVolume24hBtc\": \"cg:tradeVolume24hBtc\",\n        \"image\": {\n          \"@id\": \"schema:logo\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"NFTCollection\": {\n      \"@id\": \"cg:NFTCollection\",\n      \"@context\": {\n        \"id\": \"cg:nftId\",\n        \"contractAddress\": \"cg:contractAddress\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"symbol\": \"cg:symbol\",\n        \"floorPrice\": \"cg:floorPrice\",\n        \"marketCap\": \"cg:marketCap\",\n        \"volume24h\": \"cg:volume24h\",\n     \
  \   \"totalSupply\": \"cg:totalSupply\",\n        \"numberOfUniqueAddresses\": \"cg:numberOfUniqueAddresses\",\n        \"nativeCurrency\": \"cg:nativeCurrency\",\n        \"assetPlatformId\": \"cg:assetPlatformId\"\n      }\n    },\n\n    \"LiquidityPool\": {\n      \"@id\": \"cg:LiquidityPool\",\n      \"@context\": {\n        \"address\": \"cg:contractAddress\",\n        \"name\": \"schema:name\",\n        \"baseTokenPriceUsd\": \"cg:baseTokenPriceUsd\",\n        \"quoteTokenPriceUsd\": \"cg:quoteTokenPriceUsd\",\n        \"reserveInUsd\": \"cg:reserveInUsd\",\n        \"fdvUsd\": \"cg:fullyDilutedValuation\",\n        \"poolCreatedAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"baseToken\": {\n          \"@id\": \"cg:baseToken\",\n          \"@type\": \"@id\"\n        },\n        \"quoteToken\": {\n          \"@id\": \"cg:quoteToken\",\n          \"@type\": \"@id\"\n        },\n        \"dex\": {\n          \"@id\": \"\
  cg:dex\",\n          \"@type\": \"@id\"\n        },\n        \"network\": {\n          \"@id\": \"cg:network\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"AssetPlatform\": {\n      \"@id\": \"cg:AssetPlatform\",\n      \"@context\": {\n        \"id\": \"cg:platformId\",\n        \"name\": \"schema:name\",\n        \"chainIdentifier\": \"cg:chainIdentifier\",\n        \"nativeCoinId\": \"cg:nativeCoinId\",\n        \"shortname\": \"schema:alternateName\"\n      }\n    },\n\n    \"DerivativeTicker\": {\n      \"@id\": \"cg:DerivativeTicker\",\n      \"@context\": {\n        \"market\": \"cg:market\",\n        \"symbol\": \"cg:symbol\",\n        \"price\": \"cg:price\",\n        \"contractType\": \"cg:contractType\",\n        \"openInterest\": \"cg:openInterest\",\n        \"volume24h\": \"cg:volume24h\",\n        \"fundingRate\": \"cg:fundingRate\",\n        \"basis\": \"cg:basis\",\n        \"spread\": \"cg:spread\",\n        \"lastTradedAt\": {\n          \"@id\"\
  : \"cg:lastTradedAt\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"expiredAt\": {\n          \"@id\": \"cg:expiredAt\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/coingecko/refs/heads/main/json-ld/coingecko-context.jsonld
tags:
- Aggregator
- Blockchain
- Cryptocurrency
- Decentralized Exchanges
- DeFi
- DEX
- Exchanges
- Liquidity Pools
- Market Data
- NFTs
- Onchain Data
- Prices
- JSON-LD
- Linked Data
- Semantic Web
---
