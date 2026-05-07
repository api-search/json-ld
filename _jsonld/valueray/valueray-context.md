---
api_specs:
- filename: valueray-symbol-data-openapi.yml
  format: yaml
  label: ValueRay Symbol Data API
  slug: symbol-data-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/valueray/refs/heads/main/openapi/valueray-symbol-data-openapi.yml
class_count: 76
classes:
- SymbolData
- code
- name
- isin
- exchange
- currency
- country
- country_origin
- type
- sector
- industry
- peer_group
- etf_category
- keywords
- market_cap_in_millions
- last_update
- dividends
- technical
- risk
- support_resistance
- zigzag_pivot_points
- changepoints
- performance
- sentiment
- rate
- yield
- payout_ratio
- growth_5y
- streak_years
- next_payment
- last_price
- 52w_high
- 52w_low
- ema_20
- sma_50
- sma_200
- atr
- volatility
- current_volume
- average_volume_20d
- hurst_exponent
- trend_correlation
- safety_score
- beta
- alpha
- sharpe_ratio
- max_drawdown
- value_at_risk
- tail_risk
- rsi
- vro_score
- buy_signal
- sector_rotation
- industry_rotation
- market_regime
- level
- strength
- from
- to
- date
- price
- direction
- metric
- value
- 1d
- 1w
- 1m
- 3m
- 6m
- ytd
- 1y
- 3y
- 5y
- cagr
- relative_strength
- disclaimer
context_file: json-ld/valueray-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/valueray/refs/heads/main/json-ld/valueray-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Valueray from ValueRay.
layout: jsonld
name: Valueray Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: fibo
  uri: https://spec.edmcouncil.org/fibo/ontology/
- prefix: valueray
  uri: https://www.valueray.com/vocab#
properties:
- container: ''
  name: field_explanations
  type: reference
property_count: 1
provider_name: ValueRay
provider_slug: valueray
slug: valueray-context
source_filename: valueray-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"fibo\": \"https://spec.edmcouncil.org/fibo/ontology/\",\n    \"valueray\": \"https://www.valueray.com/vocab#\",\n    \"SymbolData\": \"valueray:SymbolData\",\n    \"code\": \"schema:tickerSymbol\",\n    \"name\": \"schema:name\",\n    \"isin\": \"schema:identifier\",\n    \"exchange\": \"schema:exchange\",\n    \"currency\": \"schema:currency\",\n    \"country\": \"schema:countryOfOrigin\",\n    \"country_origin\": \"schema:countryOfOrigin\",\n    \"type\": \"schema:additionalType\",\n    \"sector\": \"schema:industry\",\n    \"industry\": \"schema:industry\",\n    \"peer_group\": \"valueray:peerGroup\",\n    \"etf_category\": \"valueray:etfCategory\",\n    \"keywords\": \"schema:keywords\",\n    \"market_cap_in_millions\": \"valueray:marketCapMillions\",\n    \"last_update\": \"schema:dateModified\",\n    \"dividends\": \"valueray:dividends\",\n    \"technical\": \"valueray:technical\"\
  ,\n    \"risk\": \"valueray:risk\",\n    \"support_resistance\": \"valueray:supportResistance\",\n    \"zigzag_pivot_points\": \"valueray:zigzagPivotPoints\",\n    \"changepoints\": \"valueray:changepoints\",\n    \"performance\": \"valueray:performance\",\n    \"sentiment\": \"valueray:sentiment\",\n    \"rate\": \"schema:dividendYield\",\n    \"yield\": \"schema:dividendYield\",\n    \"payout_ratio\": \"valueray:payoutRatio\",\n    \"growth_5y\": \"valueray:fiveYearDividendGrowth\",\n    \"streak_years\": \"valueray:dividendStreakYears\",\n    \"next_payment\": \"valueray:nextDividendPayment\",\n    \"last_price\": \"schema:price\",\n    \"52w_high\": \"valueray:fiftyTwoWeekHigh\",\n    \"52w_low\": \"valueray:fiftyTwoWeekLow\",\n    \"ema_20\": \"valueray:ema20\",\n    \"sma_50\": \"valueray:sma50\",\n    \"sma_200\": \"valueray:sma200\",\n    \"atr\": \"valueray:averageTrueRange\",\n    \"volatility\": \"valueray:volatility\",\n    \"current_volume\": \"schema:tradingVolume\",\n  \
  \  \"average_volume_20d\": \"valueray:averageVolume20d\",\n    \"hurst_exponent\": \"valueray:hurstExponent\",\n    \"trend_correlation\": \"valueray:trendCorrelation\",\n    \"safety_score\": \"valueray:safetyScore\",\n    \"beta\": \"fibo:Beta\",\n    \"alpha\": \"valueray:alpha\",\n    \"sharpe_ratio\": \"valueray:sharpeRatio\",\n    \"max_drawdown\": \"valueray:maxDrawdown\",\n    \"value_at_risk\": \"valueray:valueAtRisk\",\n    \"tail_risk\": \"valueray:tailRisk\",\n    \"rsi\": \"valueray:relativeStrengthIndex\",\n    \"vro_score\": \"valueray:vroScore\",\n    \"buy_signal\": \"valueray:buySignal\",\n    \"sector_rotation\": \"valueray:sectorRotation\",\n    \"industry_rotation\": \"valueray:industryRotation\",\n    \"market_regime\": \"valueray:marketRegime\",\n    \"level\": \"valueray:priceLevel\",\n    \"strength\": \"valueray:strengthRating\",\n    \"from\": \"valueray:fromDate\",\n    \"to\": \"valueray:toDate\",\n    \"date\": \"schema:date\",\n    \"price\": \"schema:price\"\
  ,\n    \"direction\": \"valueray:direction\",\n    \"metric\": \"valueray:metric\",\n    \"value\": \"schema:value\",\n    \"1d\": \"valueray:return1d\",\n    \"1w\": \"valueray:return1w\",\n    \"1m\": \"valueray:return1m\",\n    \"3m\": \"valueray:return3m\",\n    \"6m\": \"valueray:return6m\",\n    \"ytd\": \"valueray:returnYtd\",\n    \"1y\": \"valueray:return1y\",\n    \"3y\": \"valueray:return3y\",\n    \"5y\": \"valueray:return5y\",\n    \"cagr\": \"valueray:cagr\",\n    \"relative_strength\": \"valueray:relativeStrength\",\n    \"disclaimer\": \"valueray:disclaimer\",\n    \"field_explanations\": {\n      \"@id\": \"valueray:fieldExplanations\",\n      \"@type\": \"@id\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/valueray/refs/heads/main/json-ld/valueray-context.jsonld
tags:
- AI/LLM
- ETF
- Financial Data
- Quantitative
- Stocks
- Technical Analysis
- JSON-LD
- Linked Data
- Semantic Web
---
