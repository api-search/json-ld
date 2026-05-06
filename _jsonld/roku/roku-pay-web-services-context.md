---
api_specs:
- filename: roku-external-control-protocol.yaml
  format: yaml
  label: Roku External Control Protocol (ECP)
  slug: external-control-protocol
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/roku/refs/heads/main/openapi/roku-external-control-protocol.yaml
- filename: roku-pay-web-services.yaml
  format: yaml
  label: Roku Pay Web Services
  slug: pay
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/roku/refs/heads/main/openapi/roku-pay-web-services.yaml
- filename: roku-nabu-cloud.yaml
  format: yaml
  label: Roku Nabu Cloud
  slug: nabu-cloud
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/roku/refs/heads/main/openapi/roku-nabu-cloud.yaml
class_count: 7
classes:
- CancelSubscriptionRequest
- IssueCreditRequest
- RefundSubscriptionRequest
- RefundValidation
- SubscriptionResult
- TransactionValidation
- UpdateBillCycleRequest
context_file: json-ld/roku-pay-web-services-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/roku/refs/heads/main/json-ld/roku-pay-web-services-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Roku Pay Web Services from Roku.
layout: jsonld
name: Roku Pay Web Services Context
namespaces:
- prefix: roku
  uri: https://developer.roku.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: amount
  type: float
- container: ''
  name: cancellationDate
  type: dateTime
- container: ''
  name: currency
  type: string
- container: ''
  name: effectiveDate
  type: dateTime
- container: ''
  name: errorCode
  type: integer
- container: ''
  name: errorMessage
  type: string
- container: ''
  name: expirationDate
  type: dateTime
- container: ''
  name: isEntitled
  type: boolean
- container: ''
  name: nextBillDate
  type: dateTime
- container: ''
  name: partnerAPIKey
  type: string
- container: ''
  name: productCode
  type: string
- container: ''
  name: productId
  type: string
- container: ''
  name: productName
  type: string
- container: ''
  name: purchaseChannel
  type: string
- container: ''
  name: purchaseContext
  type: string
- container: ''
  name: purchaseDate
  type: dateTime
- container: ''
  name: purchaseStatus
  type: string
- container: ''
  name: reason
  type: string
- container: ''
  name: refundAmount
  type: float
- container: ''
  name: refundDate
  type: dateTime
- container: ''
  name: refundId
  type: string
- container: ''
  name: refundReason
  type: string
- container: ''
  name: rokuCustomerId
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: tax
  type: float
- container: ''
  name: transactionId
  type: string
property_count: 26
provider_name: Roku
provider_slug: roku
slug: roku-pay-web-services-context
source_filename: roku-pay-web-services-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"roku\": \"https://developer.roku.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"CancelSubscriptionRequest\": \"roku:CancelSubscriptionRequest\",\n    \"IssueCreditRequest\": \"roku:IssueCreditRequest\",\n    \"RefundSubscriptionRequest\": \"roku:RefundSubscriptionRequest\",\n    \"RefundValidation\": \"roku:RefundValidation\",\n    \"SubscriptionResult\": \"roku:SubscriptionResult\",\n    \"TransactionValidation\": \"roku:TransactionValidation\",\n    \"UpdateBillCycleRequest\": \"roku:UpdateBillCycleRequest\",\n    \"amount\": {\n      \"@id\": \"roku:amount\",\n      \"@type\": \"xsd:float\"\n    },\n    \"cancellationDate\": {\n      \"@id\": \"roku:cancellationDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"currency\": {\n      \"@id\": \"roku:currency\",\n      \"@type\": \"xsd:string\"\n  \
  \  },\n    \"effectiveDate\": {\n      \"@id\": \"roku:effectiveDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"errorCode\": {\n      \"@id\": \"roku:errorCode\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"errorMessage\": {\n      \"@id\": \"roku:errorMessage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"expirationDate\": {\n      \"@id\": \"roku:expirationDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"isEntitled\": {\n      \"@id\": \"roku:isEntitled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"nextBillDate\": {\n      \"@id\": \"roku:nextBillDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"partnerAPIKey\": {\n      \"@id\": \"roku:partnerAPIKey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"productCode\": {\n      \"@id\": \"roku:productCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"productId\": {\n      \"@id\": \"roku:productId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"productName\": {\n      \"@id\": \"roku:productName\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"purchaseChannel\": {\n      \"@id\": \"roku:purchaseChannel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"purchaseContext\": {\n      \"@id\": \"roku:purchaseContext\",\n      \"@type\": \"xsd:string\"\n    },\n    \"purchaseDate\": {\n      \"@id\": \"roku:purchaseDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"purchaseStatus\": {\n      \"@id\": \"roku:purchaseStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reason\": {\n      \"@id\": \"roku:reason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"refundAmount\": {\n      \"@id\": \"roku:refundAmount\",\n      \"@type\": \"xsd:float\"\n    },\n    \"refundDate\": {\n      \"@id\": \"roku:refundDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"refundId\": {\n      \"@id\": \"roku:refundId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"refundReason\": {\n      \"@id\": \"roku:refundReason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rokuCustomerId\"\
  : {\n      \"@id\": \"roku:rokuCustomerId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"roku:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tax\": {\n      \"@id\": \"roku:tax\",\n      \"@type\": \"xsd:float\"\n    },\n    \"transactionId\": {\n      \"@id\": \"roku:transactionId\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/roku/refs/heads/main/json-ld/roku-pay-web-services-context.jsonld
tags:
- Streaming
- Television
- Media
- Entertainment
- Connected TV
- Consumer Electronics
- JSON-LD
- Linked Data
- Semantic Web
---
