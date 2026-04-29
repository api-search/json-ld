---
api_specs:
- filename: amazon-selling-partner-api-openapi.yml
  format: yaml
  label: Amazon Selling Partner API
  slug: selling-partner-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon/refs/heads/main/openapi/amazon-selling-partner-api-openapi.yml
- filename: amazon-advertising-api-openapi.yml
  format: yaml
  label: Amazon Advertising API
  slug: advertising-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon/refs/heads/main/openapi/amazon-advertising-api-openapi.yml
- filename: amazon-pay-api-openapi.yml
  format: yaml
  label: Amazon Pay API
  slug: pay-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon/refs/heads/main/openapi/amazon-pay-api-openapi.yml
class_count: 53
classes:
- Order
- OrderList
- OrderItem
- OrderItemList
- CatalogItem
- CatalogItemList
- ListingsItem
- ListingsItemPutRequest
- ListingsItemPatchRequest
- ListingsItemSubmissionResponse
- InventorySummaries
- Report
- ReportList
- ReportDocument
- url
- CreateReportSpecification
- CreateReportResponse
- TransactionList
- Money
- Pagination
- ErrorList
- Profile
- Campaign
- name
- CreateCampaignRequest
- UpdateCampaignRequest
- CampaignResponse
- description
- AdGroup
- CreateAdGroupRequest
- AdGroupResponse
- Keyword
- CreateKeywordRequest
- KeywordResponse
- Target
- CreateTargetRequest
- TargetResponse
- ReportRequest
- ReportRequestResponse
- ReportStatus
- Price
- MerchantMetadata
- StatusDetails
- Buyer
- Address
- CheckoutSession
- CreateCheckoutSessionRequest
- UpdateCheckoutSessionRequest
- Charge
- CreateChargeRequest
- ChargePermission
- Refund
- CreateRefundRequest
context_file: json-ld/amazon-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon/refs/heads/main/json-ld/amazon-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon from Amazon.
layout: jsonld
name: Amazon Context
namespaces:
- prefix: amz
  uri: https://amazon.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: AmazonOrderId
  type: string
- container: ''
  name: PurchaseDate
  type: string
- container: ''
  name: LastUpdateDate
  type: string
- container: ''
  name: OrderStatus
  type: string
- container: ''
  name: FulfillmentChannel
  type: string
- container: ''
  name: OrderTotal
  type: string
- container: ''
  name: NumberOfItemsShipped
  type: string
- container: ''
  name: NumberOfItemsUnshipped
  type: string
- container: ''
  name: ShipServiceLevel
  type: string
- container: ''
  name: MarketplaceId
  type: string
- container: ''
  name: payload
  type: string
- container: ''
  name: ASIN
  type: string
- container: ''
  name: OrderItemId
  type: string
- container: ''
  name: SellerSKU
  type: string
- container: ''
  name: Title
  type: string
- container: ''
  name: QuantityOrdered
  type: string
- container: ''
  name: QuantityShipped
  type: string
- container: ''
  name: ItemPrice
  type: string
- container: ''
  name: asin
  type: string
- container: ''
  name: attributes
  type: string
- container: set
  name: images
  type: string
- container: set
  name: salesRanks
  type: string
- container: ''
  name: numberOfResults
  type: string
- container: ''
  name: pagination
  type: string
- container: set
  name: items
  type: string
- container: ''
  name: sku
  type: string
- container: set
  name: summaries
  type: string
- container: set
  name: issues
  type: string
- container: set
  name: offers
  type: string
- container: ''
  name: productType
  type: string
- container: set
  name: patches
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: submissionId
  type: string
- container: set
  name: inventorySummaries
  type: string
- container: ''
  name: reportId
  type: string
- container: ''
  name: reportType
  type: string
- container: ''
  name: processingStatus
  type: string
- container: ''
  name: reportDocumentId
  type: string
- container: ''
  name: createdTime
  type: string
- container: set
  name: reports
  type: string
- container: ''
  name: nextToken
  type: string
- container: ''
  name: dataStartTime
  type: string
- container: ''
  name: dataEndTime
  type: string
- container: set
  name: marketplaceIds
  type: string
- container: set
  name: transactions
  type: string
- container: ''
  name: CurrencyCode
  type: string
- container: ''
  name: Amount
  type: string
- container: ''
  name: previousToken
  type: string
- container: set
  name: errors
  type: string
- container: ''
  name: profileId
  type: string
- container: ''
  name: countryCode
  type: string
- container: ''
  name: currencyCode
  type: string
- container: ''
  name: accountInfo
  type: string
- container: ''
  name: campaignId
  type: string
- container: ''
  name: state
  type: string
- container: ''
  name: dailyBudget
  type: string
- container: ''
  name: startDate
  type: string
- container: ''
  name: endDate
  type: string
- container: ''
  name: targetingType
  type: string
- container: ''
  name: premiumBidAdjustment
  type: string
- container: ''
  name: code
  type: string
- container: ''
  name: adGroupId
  type: string
- container: ''
  name: defaultBid
  type: string
- container: ''
  name: keywordId
  type: string
- container: ''
  name: keywordText
  type: string
- container: ''
  name: matchType
  type: string
- container: ''
  name: bid
  type: string
- container: ''
  name: targetId
  type: string
- container: ''
  name: expressionType
  type: string
- container: set
  name: expression
  type: string
- container: ''
  name: reportDate
  type: string
- container: ''
  name: metrics
  type: string
- container: ''
  name: segment
  type: string
- container: ''
  name: location
  type: string
- container: ''
  name: fileSize
  type: string
- container: ''
  name: amount
  type: string
- container: ''
  name: merchantReferenceId
  type: string
- container: ''
  name: merchantStoreName
  type: string
- container: ''
  name: noteToBuyer
  type: string
- container: ''
  name: reasonCode
  type: string
- container: ''
  name: reasonDescription
  type: string
- container: ''
  name: buyerId
  type: string
- container: ''
  name: email
  type: string
- container: ''
  name: addressLine1
  type: string
- container: ''
  name: addressLine2
  type: string
- container: ''
  name: addressLine3
  type: string
- container: ''
  name: city
  type: string
- container: ''
  name: stateOrRegion
  type: string
- container: ''
  name: postalCode
  type: string
- container: ''
  name: phoneNumber
  type: string
- container: ''
  name: checkoutSessionId
  type: string
- container: ''
  name: statusDetails
  type: string
- container: ''
  name: buyer
  type: string
- container: ''
  name: shippingAddress
  type: string
- container: ''
  name: billingAddress
  type: string
- container: ''
  name: paymentDetails
  type: string
- container: ''
  name: merchantMetadata
  type: string
- container: ''
  name: chargePermissionId
  type: string
- container: ''
  name: chargeId
  type: string
- container: ''
  name: creationTimestamp
  type: string
- container: ''
  name: expirationTimestamp
  type: string
- container: ''
  name: webCheckoutDetails
  type: string
- container: ''
  name: storeId
  type: string
- container: ''
  name: chargePermissionType
  type: string
- container: ''
  name: chargeAmount
  type: string
- container: ''
  name: captureAmount
  type: string
- container: ''
  name: refundedAmount
  type: string
- container: ''
  name: softDescriptor
  type: string
- container: ''
  name: captureNow
  type: string
- container: ''
  name: canHandlePendingAuthorization
  type: string
- container: ''
  name: limits
  type: string
- container: ''
  name: refundId
  type: string
- container: ''
  name: refundAmount
  type: string
property_count: 113
provider_name: Amazon
provider_slug: amazon
slug: amazon-context
source_filename: amazon-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"amz\": \"https://amazon.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Order\": \"amz:Order\",\n    \"AmazonOrderId\": {\n      \"@id\": \"amz:AmazonOrderId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PurchaseDate\": {\n      \"@id\": \"amz:PurchaseDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LastUpdateDate\": {\n      \"@id\": \"amz:LastUpdateDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"OrderStatus\": {\n      \"@id\": \"amz:OrderStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"FulfillmentChannel\": {\n      \"@id\": \"amz:FulfillmentChannel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"OrderTotal\": {\n      \"@id\": \"amz:OrderTotal\",\n      \"@type\": \"xsd:string\"\n    },\n    \"NumberOfItemsShipped\": {\n      \"@id\": \"amz:NumberOfItemsShipped\",\n     \
  \ \"@type\": \"xsd:string\"\n    },\n    \"NumberOfItemsUnshipped\": {\n      \"@id\": \"amz:NumberOfItemsUnshipped\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ShipServiceLevel\": {\n      \"@id\": \"amz:ShipServiceLevel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MarketplaceId\": {\n      \"@id\": \"amz:MarketplaceId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"OrderList\": \"amz:OrderList\",\n    \"payload\": {\n      \"@id\": \"amz:payload\",\n      \"@type\": \"xsd:string\"\n    },\n    \"OrderItem\": \"amz:OrderItem\",\n    \"ASIN\": {\n      \"@id\": \"amz:ASIN\",\n      \"@type\": \"xsd:string\"\n    },\n    \"OrderItemId\": {\n      \"@id\": \"amz:OrderItemId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SellerSKU\": {\n      \"@id\": \"amz:SellerSKU\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Title\": {\n      \"@id\": \"amz:Title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"QuantityOrdered\": {\n      \"@id\": \"amz:QuantityOrdered\",\n \
  \     \"@type\": \"xsd:string\"\n    },\n    \"QuantityShipped\": {\n      \"@id\": \"amz:QuantityShipped\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ItemPrice\": {\n      \"@id\": \"amz:ItemPrice\",\n      \"@type\": \"xsd:string\"\n    },\n    \"OrderItemList\": \"amz:OrderItemList\",\n    \"CatalogItem\": \"amz:CatalogItem\",\n    \"asin\": {\n      \"@id\": \"amz:asin\",\n      \"@type\": \"xsd:string\"\n    },\n    \"attributes\": {\n      \"@id\": \"amz:attributes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"images\": {\n      \"@id\": \"amz:images\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"salesRanks\": {\n      \"@id\": \"amz:salesRanks\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CatalogItemList\": \"amz:CatalogItemList\",\n    \"numberOfResults\": {\n      \"@id\": \"amz:numberOfResults\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pagination\": {\n      \"@id\": \"amz:pagination\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"items\": {\n      \"@id\": \"amz:items\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ListingsItem\": \"amz:ListingsItem\",\n    \"sku\": {\n      \"@id\": \"amz:sku\",\n      \"@type\": \"xsd:string\"\n    },\n    \"summaries\": {\n      \"@id\": \"amz:summaries\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"issues\": {\n      \"@id\": \"amz:issues\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"offers\": {\n      \"@id\": \"amz:offers\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ListingsItemPutRequest\": \"amz:ListingsItemPutRequest\",\n    \"productType\": {\n      \"@id\": \"amz:productType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ListingsItemPatchRequest\": \"amz:ListingsItemPatchRequest\",\n    \"patches\": {\n      \"@id\": \"amz:patches\",\n      \"@container\": \"@set\",\n\
  \      \"@type\": \"xsd:string\"\n    },\n    \"ListingsItemSubmissionResponse\": \"amz:ListingsItemSubmissionResponse\",\n    \"status\": {\n      \"@id\": \"amz:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"submissionId\": {\n      \"@id\": \"amz:submissionId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"InventorySummaries\": \"amz:InventorySummaries\",\n    \"inventorySummaries\": {\n      \"@id\": \"amz:inventorySummaries\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Report\": \"amz:Report\",\n    \"reportId\": {\n      \"@id\": \"amz:reportId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reportType\": {\n      \"@id\": \"amz:reportType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"processingStatus\": {\n      \"@id\": \"amz:processingStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reportDocumentId\": {\n      \"@id\": \"amz:reportDocumentId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdTime\": {\n\
  \      \"@id\": \"amz:createdTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ReportList\": \"amz:ReportList\",\n    \"reports\": {\n      \"@id\": \"amz:reports\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nextToken\": {\n      \"@id\": \"amz:nextToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ReportDocument\": \"amz:ReportDocument\",\n    \"url\": \"schema:url\",\n    \"CreateReportSpecification\": \"amz:CreateReportSpecification\",\n    \"dataStartTime\": {\n      \"@id\": \"amz:dataStartTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dataEndTime\": {\n      \"@id\": \"amz:dataEndTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"marketplaceIds\": {\n      \"@id\": \"amz:marketplaceIds\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreateReportResponse\": \"amz:CreateReportResponse\",\n    \"TransactionList\": \"amz:TransactionList\",\n    \"transactions\": {\n      \"@id\": \"amz:transactions\"\
  ,\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Money\": \"amz:Money\",\n    \"CurrencyCode\": {\n      \"@id\": \"amz:CurrencyCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Amount\": {\n      \"@id\": \"amz:Amount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Pagination\": \"amz:Pagination\",\n    \"previousToken\": {\n      \"@id\": \"amz:previousToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ErrorList\": \"amz:ErrorList\",\n    \"errors\": {\n      \"@id\": \"amz:errors\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Profile\": \"amz:Profile\",\n    \"profileId\": {\n      \"@id\": \"amz:profileId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"countryCode\": {\n      \"@id\": \"amz:countryCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"currencyCode\": {\n      \"@id\": \"amz:currencyCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accountInfo\": {\n      \"@id\": \"amz:accountInfo\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"Campaign\": \"amz:Campaign\",\n    \"campaignId\": {\n      \"@id\": \"amz:campaignId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"state\": {\n      \"@id\": \"amz:state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dailyBudget\": {\n      \"@id\": \"amz:dailyBudget\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startDate\": {\n      \"@id\": \"amz:startDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"endDate\": {\n      \"@id\": \"amz:endDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"targetingType\": {\n      \"@id\": \"amz:targetingType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"premiumBidAdjustment\": {\n      \"@id\": \"amz:premiumBidAdjustment\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreateCampaignRequest\": \"amz:CreateCampaignRequest\",\n    \"UpdateCampaignRequest\": \"amz:UpdateCampaignRequest\",\n    \"CampaignResponse\": \"amz:CampaignResponse\"\
  ,\n    \"code\": {\n      \"@id\": \"amz:code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\",\n    \"AdGroup\": \"amz:AdGroup\",\n    \"adGroupId\": {\n      \"@id\": \"amz:adGroupId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"defaultBid\": {\n      \"@id\": \"amz:defaultBid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreateAdGroupRequest\": \"amz:CreateAdGroupRequest\",\n    \"AdGroupResponse\": \"amz:AdGroupResponse\",\n    \"Keyword\": \"amz:Keyword\",\n    \"keywordId\": {\n      \"@id\": \"amz:keywordId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"keywordText\": {\n      \"@id\": \"amz:keywordText\",\n      \"@type\": \"xsd:string\"\n    },\n    \"matchType\": {\n      \"@id\": \"amz:matchType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bid\": {\n      \"@id\": \"amz:bid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreateKeywordRequest\": \"amz:CreateKeywordRequest\",\n    \"KeywordResponse\": \"amz:KeywordResponse\"\
  ,\n    \"Target\": \"amz:Target\",\n    \"targetId\": {\n      \"@id\": \"amz:targetId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"expressionType\": {\n      \"@id\": \"amz:expressionType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"expression\": {\n      \"@id\": \"amz:expression\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreateTargetRequest\": \"amz:CreateTargetRequest\",\n    \"TargetResponse\": \"amz:TargetResponse\",\n    \"ReportRequest\": \"amz:ReportRequest\",\n    \"reportDate\": {\n      \"@id\": \"amz:reportDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"metrics\": {\n      \"@id\": \"amz:metrics\",\n      \"@type\": \"xsd:string\"\n    },\n    \"segment\": {\n      \"@id\": \"amz:segment\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ReportRequestResponse\": \"amz:ReportRequestResponse\",\n    \"ReportStatus\": \"amz:ReportStatus\",\n    \"location\": {\n      \"@id\": \"amz:location\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"fileSize\": {\n      \"@id\": \"amz:fileSize\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Price\": \"amz:Price\",\n    \"amount\": {\n      \"@id\": \"amz:amount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MerchantMetadata\": \"amz:MerchantMetadata\",\n    \"merchantReferenceId\": {\n      \"@id\": \"amz:merchantReferenceId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"merchantStoreName\": {\n      \"@id\": \"amz:merchantStoreName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"noteToBuyer\": {\n      \"@id\": \"amz:noteToBuyer\",\n      \"@type\": \"xsd:string\"\n    },\n    \"StatusDetails\": \"amz:StatusDetails\",\n    \"reasonCode\": {\n      \"@id\": \"amz:reasonCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reasonDescription\": {\n      \"@id\": \"amz:reasonDescription\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Buyer\": \"amz:Buyer\",\n    \"buyerId\": {\n      \"@id\": \"amz:buyerId\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"email\": {\n      \"@id\": \"amz:email\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Address\": \"amz:Address\",\n    \"addressLine1\": {\n      \"@id\": \"amz:addressLine1\",\n      \"@type\": \"xsd:string\"\n    },\n    \"addressLine2\": {\n      \"@id\": \"amz:addressLine2\",\n      \"@type\": \"xsd:string\"\n    },\n    \"addressLine3\": {\n      \"@id\": \"amz:addressLine3\",\n      \"@type\": \"xsd:string\"\n    },\n    \"city\": {\n      \"@id\": \"amz:city\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stateOrRegion\": {\n      \"@id\": \"amz:stateOrRegion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"postalCode\": {\n      \"@id\": \"amz:postalCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"phoneNumber\": {\n      \"@id\": \"amz:phoneNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CheckoutSession\": \"amz:CheckoutSession\",\n    \"checkoutSessionId\": {\n      \"@id\": \"amz:checkoutSessionId\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"statusDetails\": {\n      \"@id\": \"amz:statusDetails\",\n      \"@type\": \"xsd:string\"\n    },\n    \"buyer\": {\n      \"@id\": \"amz:buyer\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shippingAddress\": {\n      \"@id\": \"amz:shippingAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"billingAddress\": {\n      \"@id\": \"amz:billingAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"paymentDetails\": {\n      \"@id\": \"amz:paymentDetails\",\n      \"@type\": \"xsd:string\"\n    },\n    \"merchantMetadata\": {\n      \"@id\": \"amz:merchantMetadata\",\n      \"@type\": \"xsd:string\"\n    },\n    \"chargePermissionId\": {\n      \"@id\": \"amz:chargePermissionId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"chargeId\": {\n      \"@id\": \"amz:chargeId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"creationTimestamp\": {\n      \"@id\": \"amz:creationTimestamp\",\n      \"@type\": \"xsd:string\"\n    },\n    \"expirationTimestamp\": {\n      \"\
  @id\": \"amz:expirationTimestamp\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreateCheckoutSessionRequest\": \"amz:CreateCheckoutSessionRequest\",\n    \"webCheckoutDetails\": {\n      \"@id\": \"amz:webCheckoutDetails\",\n      \"@type\": \"xsd:string\"\n    },\n    \"storeId\": {\n      \"@id\": \"amz:storeId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"chargePermissionType\": {\n      \"@id\": \"amz:chargePermissionType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"UpdateCheckoutSessionRequest\": \"amz:UpdateCheckoutSessionRequest\",\n    \"Charge\": \"amz:Charge\",\n    \"chargeAmount\": {\n      \"@id\": \"amz:chargeAmount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"captureAmount\": {\n      \"@id\": \"amz:captureAmount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"refundedAmount\": {\n      \"@id\": \"amz:refundedAmount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"softDescriptor\": {\n      \"@id\": \"amz:softDescriptor\",\n      \"@type\": \"\
  xsd:string\"\n    },\n    \"CreateChargeRequest\": \"amz:CreateChargeRequest\",\n    \"captureNow\": {\n      \"@id\": \"amz:captureNow\",\n      \"@type\": \"xsd:string\"\n    },\n    \"canHandlePendingAuthorization\": {\n      \"@id\": \"amz:canHandlePendingAuthorization\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ChargePermission\": \"amz:ChargePermission\",\n    \"limits\": {\n      \"@id\": \"amz:limits\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Refund\": \"amz:Refund\",\n    \"refundId\": {\n      \"@id\": \"amz:refundId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"refundAmount\": {\n      \"@id\": \"amz:refundAmount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreateRefundRequest\": \"amz:CreateRefundRequest\"\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon/refs/heads/main/json-ld/amazon-context.jsonld
tags:
- Amazon
- Advertising
- Alexa
- E-Commerce
- Marketplace
- Payments
- Voice
- JSON-LD
- Linked Data
- Semantic Web
---
