---
class_count: 29
classes:
- PortfolioCompany
- FundingRound
- VentureCapitalFirm
- Investor
- Executive
- name
- description
- sector
- status
- stage
- headquarters
- city
- state
- country
- totalFunding
- valuation
- fundingRounds
- sequoiaFund
- leadInvestor
- amount
- leadInvestors
- postMoneyValuation
- executives
- title
- exitDetails
- acquirer
- acquisitionPrice
- ticker
- exchange
context_file: json-ld/sequoia-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/sequoia-capital/refs/heads/main/json-ld/sequoia-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Sequoia from Sequoia Capital.
layout: jsonld
name: Sequoia Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: fibo
  uri: https://spec.edmcouncil.org/fibo/ontology/
- prefix: vc
  uri: https://api-evangelist.github.io/sequoia-capital/vocab/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: website
  type: reference
- container: ''
  name: founded
  type: integer
- container: ''
  name: date
  type: date
- container: ''
  name: linkedin
  type: reference
property_count: 4
provider_name: Sequoia Capital
provider_slug: sequoia-capital
slug: sequoia-context
source_filename: sequoia-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"fibo\": \"https://spec.edmcouncil.org/fibo/ontology/\",\n    \"vc\": \"https://api-evangelist.github.io/sequoia-capital/vocab/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"PortfolioCompany\": \"schema:Organization\",\n    \"FundingRound\": \"vc:FundingRound\",\n    \"VentureCapitalFirm\": \"vc:VentureCapitalFirm\",\n    \"Investor\": \"schema:Person\",\n    \"Executive\": \"schema:Person\",\n\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"website\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    },\n    \"sector\": \"schema:industry\",\n    \"founded\": {\n      \"@id\": \"schema:foundingDate\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"status\": \"vc:companyStatus\",\n    \"stage\": \"vc:fundingStage\",\n\n    \"headquarters\": \"schema:address\",\n    \"city\": \"schema:addressLocality\",\n    \"state\"\
  : \"schema:addressRegion\",\n    \"country\": \"schema:addressCountry\",\n\n    \"totalFunding\": \"vc:totalFundingAmount\",\n    \"valuation\": \"vc:valuation\",\n    \"fundingRounds\": \"vc:fundingRounds\",\n    \"sequoiaFund\": \"vc:investingFund\",\n    \"leadInvestor\": \"vc:isLeadInvestor\",\n\n    \"amount\": \"vc:investmentAmount\",\n    \"date\": {\n      \"@id\": \"schema:datePublished\",\n      \"@type\": \"xsd:date\"\n    },\n    \"leadInvestors\": \"vc:leadInvestors\",\n    \"postMoneyValuation\": \"vc:postMoneyValuation\",\n\n    \"executives\": \"schema:employee\",\n    \"title\": \"schema:jobTitle\",\n    \"linkedin\": {\n      \"@id\": \"schema:sameAs\",\n      \"@type\": \"@id\"\n    },\n\n    \"exitDetails\": \"vc:exitDetails\",\n    \"acquirer\": \"vc:acquirer\",\n    \"acquisitionPrice\": \"vc:acquisitionPrice\",\n    \"ticker\": \"vc:stockTicker\",\n    \"exchange\": \"vc:stockExchange\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/sequoia-capital/refs/heads/main/json-ld/sequoia-context.jsonld
tags:
- Venture Capital
- Investment
- Startup Funding
- Private Equity
- Portfolio Management
- JSON-LD
- Linked Data
- Semantic Web
---
