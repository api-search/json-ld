---
class_count: 13
classes:
- portfolioId
- portfolioName
- totalMarketValue
- asOfDate
- benchmarkId
- managerId
- riskMetrics
- var95
- var99
- trackingError
- factorExposures
- stressTests
- positions
context_file: json-ld/blackrock-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/blackrock/refs/heads/main/json-ld/blackrock-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Blackrock from BlackRock.
layout: jsonld
name: Blackrock Context
namespaces:
- prefix: aladdin
  uri: https://www.blackrock.com/aladdin/ontology/
- prefix: currency
  uri: https://schema.org/currency
properties: []
property_count: 0
provider_name: BlackRock
provider_slug: blackrock
slug: blackrock-context
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"aladdin\": \"https://www.blackrock.com/aladdin/ontology/\",\n    \"portfolioId\": \"aladdin:portfolioId\",\n    \"portfolioName\": \"name\",\n    \"totalMarketValue\": \"aladdin:totalMarketValue\",\n    \"asOfDate\": \"aladdin:asOfDate\",\n    \"benchmarkId\": \"aladdin:benchmarkId\",\n    \"managerId\": \"aladdin:managerId\",\n    \"riskMetrics\": \"aladdin:riskMetrics\",\n    \"var95\": \"aladdin:var95\",\n    \"var99\": \"aladdin:var99\",\n    \"trackingError\": \"aladdin:trackingError\",\n    \"factorExposures\": \"aladdin:factorExposures\",\n    \"stressTests\": \"aladdin:stressTests\",\n    \"currency\": \"https://schema.org/currency\",\n    \"positions\": \"aladdin:positions\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/blackrock/refs/heads/main/json-ld/blackrock-context.jsonld
tags:
- Asset Management
- Finance
- FinTech
- Investment Management
- Portfolio Management
- Risk Analytics
- JSON-LD
- Linked Data
- Semantic Web
---
