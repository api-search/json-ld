---
class_count: 0
classes: []
context_file: json-ld/bloomberg-news-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/bloomberg-news/refs/heads/main/json-ld/bloomberg-news-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Bloomberg News from Bloomberg News.
layout: jsonld
name: Bloomberg News Context
namespaces:
- prefix: bloomberg
  uri: https://bloomberg.com/ns/
- prefix: schema
  uri: https://schema.org/
- prefix: fibo
  uri: https://spec.edmcouncil.org/fibo/ontology/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: NewsArticle
  type: ''
- container: ''
  name: Author
  type: ''
- container: ''
  name: Topic
  type: ''
- container: ''
  name: MarketData
  type: ''
- container: ''
  name: SecurityIdentifier
  type: ''
- container: ''
  name: PricingData
  type: ''
- container: ''
  name: ReferenceData
  type: ''
- container: ''
  name: HistoricalDataPoint
  type: ''
- container: ''
  name: IntradayBar
  type: ''
- container: ''
  name: MediaAttachment
  type: ''
property_count: 10
provider_name: Bloomberg News
provider_slug: bloomberg-news
slug: bloomberg-news-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"bloomberg\": \"https://bloomberg.com/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"fibo\": \"https://spec.edmcouncil.org/fibo/ontology/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"NewsArticle\": {\n      \"@id\": \"schema:NewsArticle\",\n      \"@context\": {\n        \"storyId\": {\n          \"@id\": \"bloomberg:storyId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"headline\": {\n          \"@id\": \"schema:headline\",\n          \"@type\": \"xsd:string\"\n        },\n        \"subHeadline\": {\n          \"@id\": \"schema:alternativeHeadline\",\n          \"@type\": \"xsd:string\"\n        },\n        \"summary\": {\n          \"@id\": \"schema:abstract\",\n          \"@type\": \"xsd:string\"\n        },\n        \"body\": {\n          \"@id\": \"schema:articleBody\",\n          \"@type\": \"xsd:string\"\n        },\n      \
  \  \"publishedAt\": {\n          \"@id\": \"schema:datePublished\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"schema:dateModified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"authors\": {\n          \"@id\": \"schema:author\",\n          \"@container\": \"@list\"\n        },\n        \"source\": {\n          \"@id\": \"schema:sourceOrganization\",\n          \"@type\": \"xsd:string\"\n        },\n        \"language\": {\n          \"@id\": \"schema:inLanguage\",\n          \"@type\": \"xsd:string\"\n        },\n        \"wordCount\": {\n          \"@id\": \"schema:wordCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"articleType\": {\n          \"@id\": \"bloomberg:articleType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"urgency\": {\n          \"@id\": \"bloomberg:urgency\",\n\
  \          \"@type\": \"xsd:string\"\n        },\n        \"topics\": {\n          \"@id\": \"schema:about\",\n          \"@container\": \"@set\"\n        },\n        \"securities\": {\n          \"@id\": \"bloomberg:mentionedSecurities\",\n          \"@container\": \"@set\"\n        },\n        \"regions\": {\n          \"@id\": \"schema:contentLocation\",\n          \"@container\": \"@set\"\n        },\n        \"sectors\": {\n          \"@id\": \"bloomberg:industrySector\",\n          \"@container\": \"@set\"\n        },\n        \"tags\": {\n          \"@id\": \"schema:keywords\",\n          \"@container\": \"@set\"\n        },\n        \"media\": {\n          \"@id\": \"schema:associatedMedia\",\n          \"@container\": \"@set\"\n        },\n        \"relatedStories\": {\n          \"@id\": \"schema:relatedLink\",\n          \"@container\": \"@set\"\n        },\n        \"copyright\": {\n          \"@id\": \"schema:copyrightNotice\",\n          \"@type\": \"xsd:string\"\n      \
  \  }\n      }\n    },\n\n    \"Author\": {\n      \"@id\": \"schema:Person\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"email\": {\n          \"@id\": \"schema:email\",\n          \"@type\": \"xsd:string\"\n        },\n        \"bio\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Topic\": {\n      \"@id\": \"schema:DefinedTerm\",\n      \"@context\": {\n        \"code\": {\n          \"@id\": \"schema:termCode\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"MarketData\": {\n      \"@id\": \"bloomberg:MarketData\",\n      \"@context\": {\n        \"security\": {\n          \"@id\": \"bloomberg:security\"\
  ,\n          \"@type\": \"@id\"\n        },\n        \"timestamp\": {\n          \"@id\": \"dcterms:date\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"pricing\": {\n          \"@id\": \"bloomberg:pricingData\"\n        },\n        \"volume\": {\n          \"@id\": \"bloomberg:volumeData\"\n        },\n        \"referenceData\": {\n          \"@id\": \"bloomberg:referenceData\"\n        },\n        \"historicalData\": {\n          \"@id\": \"bloomberg:historicalData\",\n          \"@container\": \"@list\"\n        },\n        \"intradayBar\": {\n          \"@id\": \"bloomberg:intradayBar\",\n          \"@container\": \"@list\"\n        }\n      }\n    },\n\n    \"SecurityIdentifier\": {\n      \"@id\": \"bloomberg:SecurityIdentifier\",\n      \"@context\": {\n        \"ticker\": {\n          \"@id\": \"bloomberg:ticker\",\n          \"@type\": \"xsd:string\"\n        },\n        \"figi\": {\n          \"@id\": \"bloomberg:figi\",\n          \"@type\": \"xsd:string\"\n\
  \        },\n        \"isin\": {\n          \"@id\": \"bloomberg:isin\",\n          \"@type\": \"xsd:string\"\n        },\n        \"cusip\": {\n          \"@id\": \"bloomberg:cusip\",\n          \"@type\": \"xsd:string\"\n        },\n        \"sedol\": {\n          \"@id\": \"bloomberg:sedol\",\n          \"@type\": \"xsd:string\"\n        },\n        \"bloombergId\": {\n          \"@id\": \"bloomberg:uniqueId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"assetClass\": {\n          \"@id\": \"bloomberg:assetClass\",\n          \"@type\": \"xsd:string\"\n        },\n        \"exchange\": {\n          \"@id\": \"bloomberg:exchange\",\n          \"@type\": \"xsd:string\"\n        },\n        \"country\": {\n          \"@id\": \"schema:addressCountry\",\n          \"@type\": \"xsd:string\"\n        },\n        \"currency\": {\n          \"@id\": \"schema:currency\",\n\
  \          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"PricingData\": {\n      \"@id\": \"bloomberg:PricingData\",\n      \"@context\": {\n        \"lastPrice\": {\n          \"@id\": \"bloomberg:lastPrice\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"bid\": {\n          \"@id\": \"bloomberg:bid\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"ask\": {\n          \"@id\": \"bloomberg:ask\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"mid\": {\n          \"@id\": \"bloomberg:mid\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"open\": {\n          \"@id\": \"bloomberg:open\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"high\": {\n          \"@id\": \"bloomberg:high\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"low\": {\n          \"@id\": \"bloomberg:low\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"close\": {\n          \"@id\": \"bloomberg:close\",\n\
  \          \"@type\": \"xsd:decimal\"\n        },\n        \"previousClose\": {\n          \"@id\": \"bloomberg:previousClose\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"vwap\": {\n          \"@id\": \"bloomberg:vwap\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"change\": {\n          \"@id\": \"bloomberg:change\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"changePercent\": {\n          \"@id\": \"bloomberg:changePercent\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"bidSize\": {\n          \"@id\": \"bloomberg:bidSize\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"askSize\": {\n          \"@id\": \"bloomberg:askSize\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"lastTradeTime\": {\n          \"@id\": \"bloomberg:lastTradeTime\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"ReferenceData\": {\n      \"@id\": \"bloomberg:ReferenceData\",\n      \"@context\"\
  : {\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"shortName\": {\n          \"@id\": \"schema:alternateName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"marketCap\": {\n          \"@id\": \"bloomberg:marketCap\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"sharesOutstanding\": {\n          \"@id\": \"bloomberg:sharesOutstanding\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"peRatio\": {\n          \"@id\": \"bloomberg:peRatio\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"dividendYield\": {\n          \"@id\": \"bloomberg:dividendYield\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"earningsPerShare\": {\n          \"@id\": \"bloomberg:earningsPerShare\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"sector\": {\n          \"@id\": \"bloomberg:sector\",\n          \"@type\": \"xsd:string\"\n        },\n        \"industryGroup\"\
  : {\n          \"@id\": \"bloomberg:industryGroup\",\n          \"@type\": \"xsd:string\"\n        },\n        \"beta\": {\n          \"@id\": \"bloomberg:beta\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"week52High\": {\n          \"@id\": \"bloomberg:week52High\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"week52Low\": {\n          \"@id\": \"bloomberg:week52Low\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"creditRating\": {\n          \"@id\": \"bloomberg:creditRating\",\n          \"@type\": \"xsd:string\"\n        },\n        \"couponRate\": {\n          \"@id\": \"bloomberg:couponRate\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"maturityDate\": {\n          \"@id\": \"bloomberg:maturityDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"yieldToMaturity\": {\n          \"@id\": \"bloomberg:yieldToMaturity\",\n          \"@type\": \"xsd:decimal\"\n        }\n      }\n    },\n\n    \"HistoricalDataPoint\"\
  : {\n      \"@id\": \"bloomberg:HistoricalDataPoint\",\n      \"@context\": {\n        \"date\": {\n          \"@id\": \"dcterms:date\",\n          \"@type\": \"xsd:date\"\n        },\n        \"open\": {\n          \"@id\": \"bloomberg:open\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"high\": {\n          \"@id\": \"bloomberg:high\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"low\": {\n          \"@id\": \"bloomberg:low\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"close\": {\n          \"@id\": \"bloomberg:close\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"volume\": {\n          \"@id\": \"bloomberg:volume\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"IntradayBar\": {\n      \"@id\": \"bloomberg:IntradayBar\",\n      \"@context\": {\n        \"time\": {\n          \"@id\": \"dcterms:date\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"open\": {\n          \"@id\"\
  : \"bloomberg:open\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"high\": {\n          \"@id\": \"bloomberg:high\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"low\": {\n          \"@id\": \"bloomberg:low\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"close\": {\n          \"@id\": \"bloomberg:close\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"volume\": {\n          \"@id\": \"bloomberg:volume\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"numEvents\": {\n          \"@id\": \"bloomberg:numEvents\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"MediaAttachment\": {\n      \"@id\": \"schema:MediaObject\",\n      \"@context\": {\n        \"type\": {\n          \"@id\": \"schema:encodingFormat\",\n          \"@type\": \"xsd:string\"\n        },\n        \"url\": {\n          \"@id\": \"schema:contentUrl\",\n          \"@type\": \"@id\"\n        },\n        \"caption\": {\n  \
  \        \"@id\": \"schema:caption\",\n          \"@type\": \"xsd:string\"\n        },\n        \"credit\": {\n          \"@id\": \"schema:creditText\",\n          \"@type\": \"xsd:string\"\n        },\n        \"mimeType\": {\n          \"@id\": \"schema:encodingFormat\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/bloomberg-news/refs/heads/main/json-ld/bloomberg-news-context.jsonld
tags:
- Analytics
- Business Intelligence
- Financial Services
- Market Data
- News
- JSON-LD
- Linked Data
- Semantic Web
---
