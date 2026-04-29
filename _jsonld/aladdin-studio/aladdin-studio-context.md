---
class_count: 18
classes:
- Security
- SecurityResearch
- Order
- Dataset
- PortfolioRisk
- OrderList
- OrderRequest
- PortfolioAnalytics
- QueryRequest
- Position
- PositionList
- QueryResult
- Portfolio
- FactorExposure
- ConnectionList
- PortfolioList
- DatasetList
- Connection
context_file: json-ld/aladdin-studio-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/aladdin-studio/refs/heads/main/json-ld/aladdin-studio-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Aladdin Studio from Aladdin Studio.
layout: jsonld
name: Aladdin Studio Context
namespaces:
- prefix: aladdin
  uri: https://blackrock.com/aladdin/schema/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: schema
  type: string
- container: ''
  name: accountName
  type: string
- container: ''
  name: analystCount
  type: integer
- container: ''
  name: asOfDate
  type: date
- container: ''
  name: assetClass
  type: string
- container: ''
  name: averagePrice
  type: decimal
- container: ''
  name: benchmarkId
  type: string
- container: ''
  name: beta
  type: decimal
- container: set
  name: columns
  type: string
- container: ''
  name: connectionId
  type: string
- container: set
  name: connections
  type: string
- container: ''
  name: consensusDate
  type: date
- container: ''
  name: contribution
  type: decimal
- container: ''
  name: country
  type: string
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: currency
  type: string
- container: ''
  name: cusip
  type: string
- container: ''
  name: database
  type: string
- container: ''
  name: datasetId
  type: string
- container: set
  name: datasets
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: excessReturn
  type: decimal
- container: ''
  name: exchange
  type: string
- container: ''
  name: exposure
  type: decimal
- container: set
  name: factorExposures
  type: string
- container: ''
  name: factorName
  type: string
- container: ''
  name: filledAt
  type: dateTime
- container: ''
  name: filledQuantity
  type: decimal
- container: ''
  name: fromDate
  type: date
- container: ''
  name: inceptionDate
  type: date
- container: ''
  name: informationRatio
  type: decimal
- container: ''
  name: isin
  type: string
- container: ''
  name: lastUpdated
  type: dateTime
- container: ''
  name: limitPrice
  type: decimal
- container: ''
  name: marketValue
  type: decimal
- container: ''
  name: maxRows
  type: integer
- container: ''
  name: name
  type: string
- container: ''
  name: orderId
  type: string
- container: ''
  name: orderType
  type: string
- container: set
  name: orders
  type: string
- container: ''
  name: page
  type: integer
- container: ''
  name: pageSize
  type: integer
- container: ''
  name: portfolioId
  type: string
- container: set
  name: portfolios
  type: string
- container: set
  name: positions
  type: string
- container: ''
  name: priceTarget
  type: decimal
- container: ''
  name: quantity
  type: decimal
- container: ''
  name: queryId
  type: string
- container: ''
  name: rating
  type: string
- container: ''
  name: riskModel
  type: string
- container: ''
  name: rowCount
  type: integer
- container: set
  name: rows
  type: string
- container: ''
  name: sector
  type: string
- container: ''
  name: securityId
  type: string
- container: ''
  name: securityName
  type: string
- container: ''
  name: sharpeRatio
  type: decimal
- container: ''
  name: side
  type: string
- container: ''
  name: sql
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: strategy
  type: string
- container: ''
  name: ticker
  type: string
- container: ''
  name: timeout
  type: integer
- container: ''
  name: toDate
  type: date
- container: ''
  name: totalCount
  type: integer
- container: ''
  name: totalMarketValue
  type: decimal
- container: ''
  name: totalReturn
  type: decimal
- container: ''
  name: trackingError
  type: decimal
- container: ''
  name: type
  type: string
- container: ''
  name: var95
  type: decimal
- container: ''
  name: volatility
  type: decimal
- container: ''
  name: warehouse
  type: string
- container: ''
  name: weight
  type: decimal
property_count: 72
provider_name: Aladdin Studio
provider_slug: aladdin-studio
slug: aladdin-studio-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aladdin\": \"https://blackrock.com/aladdin/schema/\",\n    \"schema\": {\n      \"@id\": \"aladdin:schema\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Security\": \"aladdin:Security\",\n    \"SecurityResearch\": \"aladdin:SecurityResearch\",\n    \"Order\": \"aladdin:Order\",\n    \"Dataset\": \"aladdin:Dataset\",\n    \"PortfolioRisk\": \"aladdin:PortfolioRisk\",\n    \"OrderList\": \"aladdin:OrderList\",\n    \"OrderRequest\": \"aladdin:OrderRequest\",\n    \"PortfolioAnalytics\": \"aladdin:PortfolioAnalytics\",\n    \"QueryRequest\": \"aladdin:QueryRequest\",\n    \"Position\": \"aladdin:Position\",\n    \"PositionList\": \"aladdin:PositionList\",\n    \"QueryResult\": \"aladdin:QueryResult\",\n    \"Portfolio\": \"aladdin:Portfolio\",\n    \"FactorExposure\": \"aladdin:FactorExposure\",\n    \"ConnectionList\": \"\
  aladdin:ConnectionList\",\n    \"PortfolioList\": \"aladdin:PortfolioList\",\n    \"DatasetList\": \"aladdin:DatasetList\",\n    \"Connection\": \"aladdin:Connection\",\n    \"accountName\": {\n      \"@id\": \"aladdin:accountName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"analystCount\": {\n      \"@id\": \"aladdin:analystCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"asOfDate\": {\n      \"@id\": \"aladdin:asOfDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"assetClass\": {\n      \"@id\": \"aladdin:assetClass\",\n      \"@type\": \"xsd:string\"\n    },\n    \"averagePrice\": {\n      \"@id\": \"aladdin:averagePrice\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"benchmarkId\": {\n      \"@id\": \"aladdin:benchmarkId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"beta\": {\n      \"@id\": \"aladdin:beta\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"columns\": {\n      \"@id\": \"aladdin:columns\",\n      \"@container\": \"@set\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"connectionId\": {\n      \"@id\": \"aladdin:connectionId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"connections\": {\n      \"@id\": \"aladdin:connections\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"consensusDate\": {\n      \"@id\": \"aladdin:consensusDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"contribution\": {\n      \"@id\": \"aladdin:contribution\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"country\": {\n      \"@id\": \"aladdin:country\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdAt\": {\n      \"@id\": \"aladdin:createdAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"currency\": {\n      \"@id\": \"aladdin:currency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cusip\": {\n      \"@id\": \"aladdin:cusip\",\n      \"@type\": \"xsd:string\"\n    },\n    \"database\": {\n      \"@id\": \"aladdin:database\",\n      \"@type\": \"xsd:string\"\n    },\n    \"datasetId\"\
  : {\n      \"@id\": \"aladdin:datasetId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"datasets\": {\n      \"@id\": \"aladdin:datasets\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"excessReturn\": {\n      \"@id\": \"aladdin:excessReturn\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"exchange\": {\n      \"@id\": \"aladdin:exchange\",\n      \"@type\": \"xsd:string\"\n    },\n    \"exposure\": {\n      \"@id\": \"aladdin:exposure\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"factorExposures\": {\n      \"@id\": \"aladdin:factorExposures\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"factorName\": {\n      \"@id\": \"aladdin:factorName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"filledAt\": {\n      \"@id\": \"aladdin:filledAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"filledQuantity\"\
  : {\n      \"@id\": \"aladdin:filledQuantity\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"fromDate\": {\n      \"@id\": \"aladdin:fromDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"inceptionDate\": {\n      \"@id\": \"aladdin:inceptionDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"informationRatio\": {\n      \"@id\": \"aladdin:informationRatio\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"isin\": {\n      \"@id\": \"aladdin:isin\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastUpdated\": {\n      \"@id\": \"aladdin:lastUpdated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"limitPrice\": {\n      \"@id\": \"aladdin:limitPrice\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"marketValue\": {\n      \"@id\": \"aladdin:marketValue\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"maxRows\": {\n      \"@id\": \"aladdin:maxRows\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"orderId\": {\n      \"@id\": \"aladdin:orderId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"orderType\": {\n      \"@id\": \"aladdin:orderType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"orders\": {\n      \"@id\": \"aladdin:orders\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"page\": {\n      \"@id\": \"aladdin:page\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"pageSize\": {\n      \"@id\": \"aladdin:pageSize\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"portfolioId\": {\n      \"@id\": \"aladdin:portfolioId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"portfolios\": {\n      \"@id\": \"aladdin:portfolios\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"positions\": {\n      \"@id\": \"aladdin:positions\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"priceTarget\": {\n      \"@id\": \"aladdin:priceTarget\",\n      \"@type\": \"xsd:decimal\"\
  \n    },\n    \"quantity\": {\n      \"@id\": \"aladdin:quantity\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"queryId\": {\n      \"@id\": \"aladdin:queryId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rating\": {\n      \"@id\": \"aladdin:rating\",\n      \"@type\": \"xsd:string\"\n    },\n    \"riskModel\": {\n      \"@id\": \"aladdin:riskModel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rowCount\": {\n      \"@id\": \"aladdin:rowCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"rows\": {\n      \"@id\": \"aladdin:rows\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sector\": {\n      \"@id\": \"aladdin:sector\",\n      \"@type\": \"xsd:string\"\n    },\n    \"securityId\": {\n      \"@id\": \"aladdin:securityId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"securityName\": {\n      \"@id\": \"aladdin:securityName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sharpeRatio\": {\n      \"@id\": \"aladdin:sharpeRatio\"\
  ,\n      \"@type\": \"xsd:decimal\"\n    },\n    \"side\": {\n      \"@id\": \"aladdin:side\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sql\": {\n      \"@id\": \"aladdin:sql\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"aladdin:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"strategy\": {\n      \"@id\": \"aladdin:strategy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ticker\": {\n      \"@id\": \"aladdin:ticker\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timeout\": {\n      \"@id\": \"aladdin:timeout\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"toDate\": {\n      \"@id\": \"aladdin:toDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"totalCount\": {\n      \"@id\": \"aladdin:totalCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"totalMarketValue\": {\n      \"@id\": \"aladdin:totalMarketValue\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"totalReturn\": {\n      \"@id\": \"aladdin:totalReturn\",\n\
  \      \"@type\": \"xsd:decimal\"\n    },\n    \"trackingError\": {\n      \"@id\": \"aladdin:trackingError\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"type\": {\n      \"@id\": \"aladdin:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"var95\": {\n      \"@id\": \"aladdin:var95\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"volatility\": {\n      \"@id\": \"aladdin:volatility\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"warehouse\": {\n      \"@id\": \"aladdin:warehouse\",\n      \"@type\": \"xsd:string\"\n    },\n    \"weight\": {\n      \"@id\": \"aladdin:weight\",\n      \"@type\": \"xsd:decimal\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/aladdin-studio/refs/heads/main/json-ld/aladdin-studio-context.jsonld
tags:
- Financial
- Investment Management
- Portfolio Analytics
- Risk Management
- Asset Management
- BlackRock
- Data Cloud
- JSON-LD
- Linked Data
- Semantic Web
---
