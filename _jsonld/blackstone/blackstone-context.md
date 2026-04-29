---
class_count: 13
classes:
- fundId
- fundName
- strategy
- vintage
- nav
- navDate
- irr
- moic
- committedCapital
- calledCapital
- accountId
- investorName
- investorType
context_file: json-ld/blackstone-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/blackstone/refs/heads/main/json-ld/blackstone-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Blackstone from Blackstone.
layout: jsonld
name: Blackstone Context
namespaces:
- prefix: blackstone
  uri: https://www.blackstone.com/ontology/
- prefix: currency
  uri: https://schema.org/currency
properties: []
property_count: 0
provider_name: Blackstone
provider_slug: blackstone
slug: blackstone-context
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"blackstone\": \"https://www.blackstone.com/ontology/\",\n    \"fundId\": \"blackstone:fundId\",\n    \"fundName\": \"name\",\n    \"strategy\": \"blackstone:investmentStrategy\",\n    \"vintage\": \"blackstone:vintageYear\",\n    \"nav\": \"blackstone:netAssetValue\",\n    \"navDate\": \"blackstone:navDate\",\n    \"irr\": \"blackstone:internalRateOfReturn\",\n    \"moic\": \"blackstone:multipleOnInvestedCapital\",\n    \"committedCapital\": \"blackstone:committedCapital\",\n    \"calledCapital\": \"blackstone:calledCapital\",\n    \"accountId\": \"blackstone:accountId\",\n    \"investorName\": \"blackstone:investorName\",\n    \"investorType\": \"blackstone:investorType\",\n    \"currency\": \"https://schema.org/currency\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/blackstone/refs/heads/main/json-ld/blackstone-context.jsonld
tags:
- Alternative Assets
- Finance
- Investment Management
- Private Equity
- Real Estate
- JSON-LD
- Linked Data
- Semantic Web
---
