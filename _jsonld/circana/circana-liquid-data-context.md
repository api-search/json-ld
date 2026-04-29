---
api_specs:
- filename: circana-liquid-data.yaml
  format: yaml
  label: Circana Liquid Data API
  slug: liquid-data-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/circana/refs/heads/main/openapi/circana-liquid-data.yaml
class_count: 16
classes:
- POSRecord
- MarketShareRecord
- ConsumerPurchaseRecord
- ConsumerSegment
- CategoryDetail
- CategorySummary
- BrandDetail
- BrandSummary
- RetailerSummary
- ReportDetail
- ExportDetail
- DataCoverage
- MarketPresence
- name
- description
- url
context_file: json-ld/circana-liquid-data-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/circana/refs/heads/main/json-ld/circana-liquid-data-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Circana Liquid Data from Circana.
layout: jsonld
name: Circana Liquid Data Context
namespaces:
- prefix: circana
  uri: https://www.circana.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: period
  type: string
- container: ''
  name: category
  type: string
- container: ''
  name: brand
  type: string
- container: ''
  name: upc
  type: string
- container: ''
  name: dollarSales
  type: double
- container: ''
  name: unitSales
  type: integer
- container: ''
  name: volumeSales
  type: double
- container: ''
  name: avgPrice
  type: double
- container: ''
  name: distributionPct
  type: double
- container: ''
  name: dollarShare
  type: double
- container: ''
  name: unitShare
  type: double
- container: ''
  name: shareChange
  type: double
- container: ''
  name: segment
  type: string
- container: ''
  name: penetrationPct
  type: double
- container: ''
  name: buyRate
  type: double
- container: ''
  name: avgSpend
  type: double
- container: ''
  name: tripsPerBuyer
  type: double
- container: ''
  name: channel
  type: string
- container: ''
  name: segmentId
  type: string
- container: ''
  name: sizePct
  type: double
- container: ''
  name: avgBasketSize
  type: double
- container: set
  name: preferredChannels
  type: string
- container: set
  name: keyCategories
  type: string
- container: ''
  name: categoryId
  type: string
- container: ''
  name: parentId
  type: string
- container: ''
  name: industry
  type: string
- container: ''
  name: level
  type: integer
- container: ''
  name: subcategoryCount
  type: integer
- container: ''
  name: brandId
  type: string
- container: ''
  name: manufacturer
  type: string
- container: ''
  name: upcCount
  type: integer
- container: set
  name: categories
  type: string
- container: ''
  name: retailerId
  type: string
- container: ''
  name: storeCount
  type: integer
- container: ''
  name: geographicCoverage
  type: string
- container: ''
  name: reportId
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: completedAt
  type: dateTime
- container: ''
  name: reportType
  type: string
- container: ''
  name: rowCount
  type: integer
- container: ''
  name: exportId
  type: string
- container: ''
  name: format
  type: string
- container: ''
  name: downloadUrl
  type: reference
- container: ''
  name: fileSizeBytes
  type: integer
- container: ''
  name: posAvailable
  type: boolean
- container: ''
  name: panelAvailable
  type: boolean
- container: ''
  name: earliestDate
  type: date
- container: ''
  name: latestDate
  type: date
- container: ''
  name: channels
  type: integer
- container: ''
  name: retailers
  type: integer
property_count: 51
provider_name: Circana
provider_slug: circana
slug: circana-liquid-data-context
source_filename: circana-liquid-data-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"circana\": \"https://www.circana.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"POSRecord\": \"circana:POSRecord\",\n    \"MarketShareRecord\": \"circana:MarketShareRecord\",\n    \"ConsumerPurchaseRecord\": \"circana:ConsumerPurchaseRecord\",\n    \"ConsumerSegment\": \"circana:ConsumerSegment\",\n    \"CategoryDetail\": \"circana:CategoryDetail\",\n    \"CategorySummary\": \"circana:CategorySummary\",\n    \"BrandDetail\": \"circana:BrandDetail\",\n    \"BrandSummary\": \"circana:BrandSummary\",\n    \"RetailerSummary\": \"circana:RetailerSummary\",\n    \"ReportDetail\": \"circana:ReportDetail\",\n    \"ExportDetail\": \"circana:ExportDetail\",\n    \"DataCoverage\": \"circana:DataCoverage\",\n    \"MarketPresence\": \"circana:MarketPresence\",\n\n    \"name\": \"schema:name\",\n    \"description\": \"\
  schema:description\",\n    \"url\": \"schema:url\",\n\n    \"period\": {\n      \"@id\": \"circana:period\",\n      \"@type\": \"xsd:string\"\n    },\n    \"category\": {\n      \"@id\": \"circana:category\",\n      \"@type\": \"xsd:string\"\n    },\n    \"brand\": {\n      \"@id\": \"circana:brand\",\n      \"@type\": \"xsd:string\"\n    },\n    \"upc\": {\n      \"@id\": \"circana:upc\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dollarSales\": {\n      \"@id\": \"circana:dollar_sales\",\n      \"@type\": \"xsd:double\"\n    },\n    \"unitSales\": {\n      \"@id\": \"circana:unit_sales\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"volumeSales\": {\n      \"@id\": \"circana:volume_sales\",\n      \"@type\": \"xsd:double\"\n    },\n    \"avgPrice\": {\n      \"@id\": \"circana:avg_price\",\n      \"@type\": \"xsd:double\"\n    },\n    \"distributionPct\": {\n      \"@id\": \"circana:distribution_pct\",\n      \"@type\": \"xsd:double\"\n    },\n    \"dollarShare\": {\n      \"\
  @id\": \"circana:dollar_share\",\n      \"@type\": \"xsd:double\"\n    },\n    \"unitShare\": {\n      \"@id\": \"circana:unit_share\",\n      \"@type\": \"xsd:double\"\n    },\n    \"shareChange\": {\n      \"@id\": \"circana:share_change\",\n      \"@type\": \"xsd:double\"\n    },\n    \"segment\": {\n      \"@id\": \"circana:segment\",\n      \"@type\": \"xsd:string\"\n    },\n    \"penetrationPct\": {\n      \"@id\": \"circana:penetration_pct\",\n      \"@type\": \"xsd:double\"\n    },\n    \"buyRate\": {\n      \"@id\": \"circana:buy_rate\",\n      \"@type\": \"xsd:double\"\n    },\n    \"avgSpend\": {\n      \"@id\": \"circana:avg_spend\",\n      \"@type\": \"xsd:double\"\n    },\n    \"tripsPerBuyer\": {\n      \"@id\": \"circana:trips_per_buyer\",\n      \"@type\": \"xsd:double\"\n    },\n    \"channel\": {\n      \"@id\": \"circana:channel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"segmentId\": {\n      \"@id\": \"circana:segment_id\",\n      \"@type\": \"xsd:string\"\n\
  \    },\n    \"sizePct\": {\n      \"@id\": \"circana:size_pct\",\n      \"@type\": \"xsd:double\"\n    },\n    \"avgBasketSize\": {\n      \"@id\": \"circana:avg_basket_size\",\n      \"@type\": \"xsd:double\"\n    },\n    \"preferredChannels\": {\n      \"@id\": \"circana:preferred_channels\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"keyCategories\": {\n      \"@id\": \"circana:key_categories\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"categoryId\": {\n      \"@id\": \"circana:category_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"parentId\": {\n      \"@id\": \"circana:parent_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"industry\": {\n      \"@id\": \"circana:industry\",\n      \"@type\": \"xsd:string\"\n    },\n    \"level\": {\n      \"@id\": \"circana:level\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"subcategoryCount\": {\n      \"@id\": \"circana:subcategory_count\",\n      \"\
  @type\": \"xsd:integer\"\n    },\n    \"brandId\": {\n      \"@id\": \"circana:brand_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"manufacturer\": {\n      \"@id\": \"circana:manufacturer\",\n      \"@type\": \"xsd:string\"\n    },\n    \"upcCount\": {\n      \"@id\": \"circana:upc_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"categories\": {\n      \"@id\": \"circana:categories\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"retailerId\": {\n      \"@id\": \"circana:retailer_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"storeCount\": {\n      \"@id\": \"circana:store_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"geographicCoverage\": {\n      \"@id\": \"circana:geographic_coverage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reportId\": {\n      \"@id\": \"circana:report_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"circana:status\",\n      \"@type\": \"xsd:string\"\n\
  \    },\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"completedAt\": {\n      \"@id\": \"circana:completed_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"reportType\": {\n      \"@id\": \"circana:report_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rowCount\": {\n      \"@id\": \"circana:row_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"exportId\": {\n      \"@id\": \"circana:export_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"format\": {\n      \"@id\": \"circana:format\",\n      \"@type\": \"xsd:string\"\n    },\n    \"downloadUrl\": {\n      \"@id\": \"circana:download_url\",\n      \"@type\": \"@id\"\n    },\n    \"fileSizeBytes\": {\n      \"@id\": \"circana:file_size_bytes\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"posAvailable\": {\n      \"@id\": \"circana:pos_available\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"panelAvailable\": {\n      \"@id\": \"circana:panel_available\"\
  ,\n      \"@type\": \"xsd:boolean\"\n    },\n    \"earliestDate\": {\n      \"@id\": \"circana:earliest_date\",\n      \"@type\": \"xsd:date\"\n    },\n    \"latestDate\": {\n      \"@id\": \"circana:latest_date\",\n      \"@type\": \"xsd:date\"\n    },\n    \"channels\": {\n      \"@id\": \"circana:channels\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"retailers\": {\n      \"@id\": \"circana:retailers\",\n      \"@type\": \"xsd:integer\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/circana/refs/heads/main/json-ld/circana-liquid-data-context.jsonld
tags:
- Analytics
- Consumer Data
- Market Research
- Retail
- CPG
- Point Of Sale
- Consumer Insights
- Business Intelligence
- JSON-LD
- Linked Data
- Semantic Web
---
