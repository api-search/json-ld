---
api_specs:
- filename: urban-outfitters-affiliate-api-openapi.yml
  format: yaml
  label: Urban Outfitters Affiliate Program
  slug: affiliate-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/urban-outfitters/refs/heads/main/openapi/urban-outfitters-affiliate-api-openapi.yml
- filename: urban-outfitters-marketplace-api-openapi.yml
  format: yaml
  label: Urban Outfitters Marketplace (UO MRKT) Integration
  slug: marketplace-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/urban-outfitters/refs/heads/main/openapi/urban-outfitters-marketplace-api-openapi.yml
class_count: 26
classes:
- AffiliateLink
- AffiliateLinkCreate
- CommissionReport
- Creative
- CreativeListResponse
- InventoryUpdate
- InventoryUpdateResponse
- Order
- OrderItem
- OrderListResponse
- Product
- ProductSearchResponse
- SellerProduct
- SellerProductCreate
- SellerProductListResponse
- Shipment
- ShipmentCreate
- ShippingAddress
- brand
- category
- currency
- description
- imageUrl
- imageUrls
- name
- price
context_file: json-ld/urban-outfitters-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/urban-outfitters/refs/heads/main/json-ld/urban-outfitters-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Urban Outfitters from Urban Outfitters.
layout: jsonld
name: Urban Outfitters Context
namespaces:
- prefix: uo
  uri: https://www.urbanoutfitters.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: address1
  type: string
- container: ''
  name: address2
  type: string
- container: ''
  name: affiliateId
  type: string
- container: ''
  name: affiliateUrl
  type: string
- container: ''
  name: carrier
  type: string
- container: ''
  name: city
  type: string
- container: ''
  name: clickUrl
  type: string
- container: ''
  name: commissionRate
  type: decimal
- container: ''
  name: country
  type: string
- container: ''
  name: createdAt
  type: dateTime
- container: set
  name: creatives
  type: string
- container: ''
  name: end
  type: date
- container: ''
  name: endDate
  type: date
- container: ''
  name: estimatedDelivery
  type: date
- container: ''
  name: failed
  type: integer
- container: ''
  name: id
  type: string
- container: ''
  name: inStock
  type: boolean
- container: ''
  name: inventoryQuantity
  type: integer
- container: set
  name: items
  type: string
- container: ''
  name: limit
  type: integer
- container: ''
  name: offset
  type: integer
- container: ''
  name: orderId
  type: string
- container: set
  name: orders
  type: string
- container: ''
  name: period
  type: string
- container: ''
  name: postalCode
  type: string
- container: set
  name: products
  type: string
- container: ''
  name: quantity
  type: integer
- container: set
  name: results
  type: string
- container: ''
  name: salePrice
  type: decimal
- container: ''
  name: shippingAddress
  type: string
- container: ''
  name: size
  type: string
- container: set
  name: sizes
  type: string
- container: ''
  name: sku
  type: string
- container: ''
  name: start
  type: date
- container: ''
  name: startDate
  type: date
- container: ''
  name: state
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: targetUrl
  type: string
- container: ''
  name: total
  type: integer
- container: ''
  name: totalClicks
  type: integer
- container: ''
  name: totalCommission
  type: decimal
- container: ''
  name: totalRevenue
  type: decimal
- container: ''
  name: totalSales
  type: integer
- container: ''
  name: trackingId
  type: string
- container: ''
  name: trackingNumber
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: updated
  type: integer
- container: set
  name: updates
  type: string
property_count: 48
provider_name: Urban Outfitters
provider_slug: urban-outfitters
slug: urban-outfitters-context
source_filename: urban-outfitters-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"uo\": \"https://www.urbanoutfitters.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AffiliateLink\": \"uo:AffiliateLink\",\n    \"AffiliateLinkCreate\": \"uo:AffiliateLinkCreate\",\n    \"CommissionReport\": \"uo:CommissionReport\",\n    \"Creative\": \"uo:Creative\",\n    \"CreativeListResponse\": \"uo:CreativeListResponse\",\n    \"InventoryUpdate\": \"uo:InventoryUpdate\",\n    \"InventoryUpdateResponse\": \"uo:InventoryUpdateResponse\",\n    \"Order\": \"uo:Order\",\n    \"OrderItem\": \"uo:OrderItem\",\n    \"OrderListResponse\": \"uo:OrderListResponse\",\n    \"Product\": \"uo:Product\",\n    \"ProductSearchResponse\": \"uo:ProductSearchResponse\",\n    \"SellerProduct\": \"uo:SellerProduct\",\n    \"SellerProductCreate\": \"uo:SellerProductCreate\",\n    \"SellerProductListResponse\": \"uo:SellerProductListResponse\"\
  ,\n    \"Shipment\": \"uo:Shipment\",\n    \"ShipmentCreate\": \"uo:ShipmentCreate\",\n    \"ShippingAddress\": \"uo:ShippingAddress\",\n    \"address1\": {\n      \"@id\": \"uo:address1\",\n      \"@type\": \"xsd:string\"\n    },\n    \"address2\": {\n      \"@id\": \"uo:address2\",\n      \"@type\": \"xsd:string\"\n    },\n    \"affiliateId\": {\n      \"@id\": \"uo:affiliateId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"affiliateUrl\": {\n      \"@id\": \"uo:affiliateUrl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"brand\": \"schema:brand\",\n    \"carrier\": {\n      \"@id\": \"uo:carrier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"category\": \"schema:category\",\n    \"city\": {\n      \"@id\": \"uo:city\",\n      \"@type\": \"xsd:string\"\n    },\n    \"clickUrl\": {\n      \"@id\": \"uo:clickUrl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"commissionRate\": {\n      \"@id\": \"uo:commissionRate\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"country\"\
  : {\n      \"@id\": \"uo:country\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdAt\": {\n      \"@id\": \"uo:createdAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"creatives\": {\n      \"@id\": \"uo:creatives\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"currency\": \"schema:priceCurrency\",\n    \"description\": \"schema:description\",\n    \"end\": {\n      \"@id\": \"uo:end\",\n      \"@type\": \"xsd:date\"\n    },\n    \"endDate\": {\n      \"@id\": \"uo:endDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"estimatedDelivery\": {\n      \"@id\": \"uo:estimatedDelivery\",\n      \"@type\": \"xsd:date\"\n    },\n    \"failed\": {\n      \"@id\": \"uo:failed\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"id\": {\n      \"@id\": \"uo:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"imageUrl\": \"schema:image\",\n    \"imageUrls\": \"schema:image\",\n    \"inStock\": {\n      \"@id\": \"uo:inStock\",\n      \"@type\"\
  : \"xsd:boolean\"\n    },\n    \"inventoryQuantity\": {\n      \"@id\": \"uo:inventoryQuantity\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"items\": {\n      \"@id\": \"uo:items\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"limit\": {\n      \"@id\": \"uo:limit\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"name\": \"schema:name\",\n    \"offset\": {\n      \"@id\": \"uo:offset\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"orderId\": {\n      \"@id\": \"uo:orderId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"orders\": {\n      \"@id\": \"uo:orders\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"period\": {\n      \"@id\": \"uo:period\",\n      \"@type\": \"xsd:string\"\n    },\n    \"postalCode\": {\n      \"@id\": \"uo:postalCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"price\": \"schema:price\",\n    \"products\": {\n      \"@id\": \"uo:products\",\n      \"@container\": \"@set\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"quantity\": {\n      \"@id\": \"uo:quantity\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"results\": {\n      \"@id\": \"uo:results\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"salePrice\": {\n      \"@id\": \"uo:salePrice\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"shippingAddress\": {\n      \"@id\": \"uo:shippingAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"size\": {\n      \"@id\": \"uo:size\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sizes\": {\n      \"@id\": \"uo:sizes\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sku\": {\n      \"@id\": \"uo:sku\",\n      \"@type\": \"xsd:string\"\n    },\n    \"start\": {\n      \"@id\": \"uo:start\",\n      \"@type\": \"xsd:date\"\n    },\n    \"startDate\": {\n      \"@id\": \"uo:startDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"state\": {\n      \"@id\": \"uo:state\",\n  \
  \    \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"uo:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"targetUrl\": {\n      \"@id\": \"uo:targetUrl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"total\": {\n      \"@id\": \"uo:total\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"totalClicks\": {\n      \"@id\": \"uo:totalClicks\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"totalCommission\": {\n      \"@id\": \"uo:totalCommission\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"totalRevenue\": {\n      \"@id\": \"uo:totalRevenue\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"totalSales\": {\n      \"@id\": \"uo:totalSales\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"trackingId\": {\n      \"@id\": \"uo:trackingId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"trackingNumber\": {\n      \"@id\": \"uo:trackingNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"uo:type\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"updated\": {\n      \"@id\": \"uo:updated\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"updates\": {\n      \"@id\": \"uo:updates\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/urban-outfitters/refs/heads/main/json-ld/urban-outfitters-context.jsonld
tags:
- Retail
- Fashion
- Apparel
- Ecommerce
- Affiliate
- Marketplace
- JSON-LD
- Linked Data
- Semantic Web
---
