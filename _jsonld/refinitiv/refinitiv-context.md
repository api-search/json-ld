---
api_specs:
- filename: refinitiv-data-platform-openapi.yml
  format: yaml
  label: Refinitiv Data Platform (RDP) API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/refinitiv/refs/heads/main/openapi/refinitiv-data-platform-openapi.yml
- filename: refinitiv-real-time-websocket-asyncapi.yml
  format: yaml
  label: Refinitiv Real-Time WebSocket API
  slug: ''
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/refinitiv/refs/heads/main/asyncapi/refinitiv-real-time-websocket-asyncapi.yml
- filename: refinitiv-datascope-select-openapi.yml
  format: yaml
  label: LSEG DataScope Select - REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/refinitiv/refs/heads/main/openapi/refinitiv-datascope-select-openapi.yml
- filename: refinitiv-world-check-one-openapi.yml
  format: yaml
  label: World-Check One API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/refinitiv/refs/heads/main/openapi/refinitiv-world-check-one-openapi.yml
- filename: refinitiv-qual-id-openapi.yml
  format: yaml
  label: Qual-ID API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/refinitiv/refs/heads/main/openapi/refinitiv-qual-id-openapi.yml
- filename: refinitiv-permid-entity-search-openapi.yml
  format: yaml
  label: PermID Entity Search API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/refinitiv/refs/heads/main/openapi/refinitiv-permid-entity-search-openapi.yml
class_count: 0
classes: []
context_file: json-ld/refinitiv-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/refinitiv/refs/heads/main/json-ld/refinitiv-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Refinitiv from Refinitiv.
layout: jsonld
name: Refinitiv Context
namespaces:
- prefix: refinitiv
  uri: https://api.refinitiv.com/schemas/
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
  name: FinancialInstrument
  type: ''
- container: ''
  name: Organization
  type: ''
- container: ''
  name: PricingData
  type: ''
- container: ''
  name: ESGScore
  type: ''
- container: ''
  name: NewsArticle
  type: ''
- container: ''
  name: ScreeningCase
  type: ''
- container: ''
  name: VerificationRecord
  type: ''
property_count: 7
provider_name: Refinitiv
provider_slug: refinitiv
slug: refinitiv-context
source_filename: refinitiv-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"refinitiv\": \"https://api.refinitiv.com/schemas/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"fibo\": \"https://spec.edmcouncil.org/fibo/ontology/\",\n\n    \"FinancialInstrument\": {\n      \"@id\": \"refinitiv:FinancialInstrument\",\n      \"@context\": {\n        \"ric\": {\n          \"@id\": \"refinitiv:ric\",\n          \"@type\": \"xsd:string\"\n        },\n        \"isin\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"cusip\": {\n          \"@id\": \"refinitiv:cusip\",\n          \"@type\": \"xsd:string\"\n        },\n        \"sedol\": {\n          \"@id\": \"refinitiv:sedol\",\n          \"@type\": \"xsd:string\"\n        },\n        \"ticker\": {\n          \"@id\": \"refinitiv:ticker\",\n          \"@type\": \"xsd:string\"\n        },\n       \
  \ \"permId\": {\n          \"@id\": \"refinitiv:permId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"lei\": {\n          \"@id\": \"refinitiv:lei\",\n          \"@type\": \"xsd:string\"\n        },\n        \"displayName\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"currency\": {\n          \"@id\": \"schema:priceCurrency\",\n          \"@type\": \"xsd:string\"\n        },\n        \"exchangeCode\": {\n          \"@id\": \"refinitiv:exchangeCode\",\n          \"@type\": \"xsd:string\"\n        },\n        \"exchangeName\": {\n          \"@id\": \"refinitiv:exchangeName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"assetClass\": {\n          \"@id\": \"refinitiv:assetClass\",\n          \"@type\": \"xsd:string\"\n        },\n        \"country\": {\n          \"@id\": \"schema:countryOfOrigin\",\n          \"@type\": \"xsd:string\"\n        },\n        \"status\": {\n          \"@id\": \"refinitiv:tradingStatus\"\
  ,\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"Organization\": {\n      \"@id\": \"schema:Organization\",\n      \"@context\": {\n        \"permId\": {\n          \"@id\": \"refinitiv:permId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"organizationName\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"lei\": {\n          \"@id\": \"refinitiv:lei\",\n          \"@type\": \"xsd:string\"\n        },\n        \"primaryRIC\": {\n          \"@id\": \"refinitiv:ric\",\n          \"@type\": \"xsd:string\"\n        },\n        \"hasURL\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"isIncorporatedIn\": {\n          \"@id\": \"schema:foundingLocation\",\n          \"@type\": \"xsd:string\"\n        },\n        \"isDomiciledIn\": {\n          \"@id\": \"refinitiv:domicile\",\n          \"@type\": \"xsd:string\"\n        },\n        \"orgSubtype\": {\n  \
  \        \"@id\": \"refinitiv:organizationType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"hasActivityStatus\": {\n          \"@id\": \"refinitiv:activityStatus\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"PricingData\": {\n      \"@id\": \"refinitiv:PricingData\",\n      \"@context\": {\n        \"bid\": {\n          \"@id\": \"refinitiv:bidPrice\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"ask\": {\n          \"@id\": \"refinitiv:askPrice\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"last\": {\n          \"@id\": \"refinitiv:lastPrice\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"open\": {\n          \"@id\": \"refinitiv:openPrice\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"high\": {\n          \"@id\": \"refinitiv:highPrice\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"low\": {\n          \"@id\": \"refinitiv:lowPrice\",\n          \"@type\"\
  : \"xsd:decimal\"\n        },\n        \"close\": {\n          \"@id\": \"refinitiv:closePrice\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"volume\": {\n          \"@id\": \"refinitiv:tradingVolume\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"timestamp\": {\n          \"@id\": \"dcterms:date\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"ESGScore\": {\n      \"@id\": \"refinitiv:ESGScore\",\n      \"@context\": {\n        \"instrumentId\": {\n          \"@id\": \"refinitiv:instrumentId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"companyName\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"periodEndDate\": {\n          \"@id\": \"refinitiv:periodEndDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"esgScore\": {\n          \"@id\": \"refinitiv:esgScore\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"esgCombinedScore\"\
  : {\n          \"@id\": \"refinitiv:esgCombinedScore\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"environmentPillarScore\": {\n          \"@id\": \"refinitiv:environmentPillarScore\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"socialPillarScore\": {\n          \"@id\": \"refinitiv:socialPillarScore\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"governancePillarScore\": {\n          \"@id\": \"refinitiv:governancePillarScore\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"esgGrade\": {\n          \"@id\": \"refinitiv:esgGrade\",\n          \"@type\": \"xsd:string\"\n        },\n        \"controversiesScore\": {\n          \"@id\": \"refinitiv:controversiesScore\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"co2Emissions\": {\n          \"@id\": \"refinitiv:co2Emissions\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"industry\": {\n          \"@id\": \"schema:industry\",\n          \"@type\"\
  : \"xsd:string\"\n        },\n        \"country\": {\n          \"@id\": \"schema:countryOfOrigin\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"NewsArticle\": {\n      \"@id\": \"schema:NewsArticle\",\n      \"@context\": {\n        \"storyId\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"title\": {\n          \"@id\": \"schema:headline\",\n          \"@type\": \"xsd:string\"\n        },\n        \"body\": {\n          \"@id\": \"schema:articleBody\",\n          \"@type\": \"xsd:string\"\n        },\n        \"versionCreated\": {\n          \"@id\": \"schema:datePublished\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"sourceCode\": {\n          \"@id\": \"refinitiv:sourceCode\",\n          \"@type\": \"xsd:string\"\n        },\n        \"sourceName\": {\n          \"@id\": \"schema:publisher\",\n          \"@type\": \"xsd:string\"\n        },\n        \"language\": {\n        \
  \  \"@id\": \"schema:inLanguage\",\n          \"@type\": \"xsd:string\"\n        },\n        \"urgency\": {\n          \"@id\": \"refinitiv:urgency\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"ScreeningCase\": {\n      \"@id\": \"refinitiv:ScreeningCase\",\n      \"@context\": {\n        \"caseSystemId\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"caseId\": {\n          \"@id\": \"refinitiv:caseId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"entityType\": {\n          \"@id\": \"refinitiv:entityType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"groupId\": {\n          \"@id\": \"refinitiv:groupId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"creationDate\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"modificationDate\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\"\
  : \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"VerificationRecord\": {\n      \"@id\": \"refinitiv:VerificationRecord\",\n      \"@context\": {\n        \"transactionId\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"countryCode\": {\n          \"@id\": \"schema:addressCountry\",\n          \"@type\": \"xsd:string\"\n        },\n        \"recordStatus\": {\n          \"@id\": \"refinitiv:verificationStatus\",\n          \"@type\": \"xsd:string\"\n        },\n        \"uploadedDt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/refinitiv/refs/heads/main/json-ld/refinitiv-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
