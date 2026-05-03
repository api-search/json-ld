---
api_specs:
- filename: toast-orders-openapi.yaml
  format: yaml
  label: Toast Orders API
  slug: toast-orders
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/toast/refs/heads/main/openapi/toast-orders-openapi.yaml
- filename: toast-menus-openapi.yaml
  format: yaml
  label: Toast Menus API
  slug: toast-menus
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/toast/refs/heads/main/openapi/toast-menus-openapi.yaml
- filename: toast-labor-openapi.yaml
  format: yaml
  label: Toast Labor API
  slug: toast-labor
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/toast/refs/heads/main/openapi/toast-labor-openapi.yaml
- filename: toast-restaurants-openapi.yaml
  format: yaml
  label: Toast Restaurants API
  slug: toast-restaurants
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/toast/refs/heads/main/openapi/toast-restaurants-openapi.yaml
- filename: toast-stock-openapi.yaml
  format: yaml
  label: Toast Stock API
  slug: toast-stock
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/toast/refs/heads/main/openapi/toast-stock-openapi.yaml
- filename: toast-partners-openapi.yaml
  format: yaml
  label: Toast Partners API
  slug: toast-partners
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/toast/refs/heads/main/openapi/toast-partners-openapi.yaml
- filename: toast-authentication-openapi.yaml
  format: yaml
  label: Toast Authentication API
  slug: toast-authentication
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/toast/refs/heads/main/openapi/toast-authentication-openapi.yaml
class_count: 31
classes:
- ApplicableDiscount
- ApplicableDiscountsRequest
- AppliedDiscount
- AppliedDiscountReason
- AppliedDiscountTrigger
- AppliedLoyaltyInfo
- AppliedPackagingInfo
- AppliedPackagingItem
- AppliedServiceCharge
- AppliedTaxRate
- Check
- ConfigReference
- CurbsidePickupInfo
- Customer
- DeliveryInfo
- DeliveryServiceInfo
- Device
- ExternalReference
- Fulfillment
- GiftCardInfo
- LoyaltyDetails
- MarketplaceFacilitatorTaxInfo
- Order
- OrderResponse
- Payment
- Refund
- RefundDetails
- Selection
- ToastReference
- UpdatePaymentRequest
- VoidInformation
context_file: json-ld/toast-orders-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/toast/refs/heads/main/json-ld/toast-orders-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Toast Orders from Toast.
layout: jsonld
name: Toast Orders Context
namespaces:
- prefix: toast
  uri: https://developer.toasttab.com/schema/
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
  name: administrativeArea
  type: string
- container: set
  name: applicableChecks
  type: string
- container: set
  name: applicableSelections
  type: string
- container: ''
  name: city
  type: string
- container: ''
  name: comment
  type: string
- container: ''
  name: country
  type: string
- container: ''
  name: deliveredDate
  type: dateTime
- container: ''
  name: deliveryEmployee
  type: reference
- container: ''
  name: deliveryState
  type: string
- container: ''
  name: description
  type: ''
- container: ''
  name: discount
  type: reference
- container: ''
  name: discountReason
  type: reference
- container: ''
  name: dispatchedDate
  type: dateTime
- container: ''
  name: entityType
  type: string
- container: ''
  name: facilitatorCollectAndRemitTaxOrder
  type: boolean
- container: ''
  name: guid
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: latitude
  type: decimal
- container: ''
  name: longitude
  type: decimal
- container: ''
  name: name
  type: ''
- container: ''
  name: notes
  type: string
- container: ''
  name: order
  type: reference
- container: set
  name: orders
  type: string
- container: ''
  name: promoCode
  type: string
- container: ''
  name: quantity
  type: decimal
- container: ''
  name: referenceId
  type: string
- container: ''
  name: refundAmount
  type: decimal
- container: ''
  name: refundBusinessDate
  type: integer
- container: ''
  name: refundDate
  type: dateTime
- container: ''
  name: refundTransaction
  type: reference
- container: ''
  name: selection
  type: string
- container: ''
  name: state
  type: string
- container: ''
  name: taxRefundAmount
  type: decimal
- container: set
  name: taxes
  type: string
- container: ''
  name: tipAmount
  type: decimal
- container: ''
  name: tipRefundAmount
  type: decimal
- container: ''
  name: unit
  type: string
- container: ''
  name: vendor
  type: string
- container: ''
  name: voidApprover
  type: reference
- container: ''
  name: voidBusinessDate
  type: integer
- container: ''
  name: voidDate
  type: dateTime
- container: ''
  name: voidReason
  type: reference
- container: ''
  name: voidUser
  type: reference
- container: ''
  name: zipCode
  type: string
property_count: 46
provider_name: Toast
provider_slug: toast
slug: toast-orders-context
source_filename: toast-orders-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"toast\": \"https://developer.toasttab.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ApplicableDiscount\": \"toast:ApplicableDiscount\",\n    \"ApplicableDiscountsRequest\": \"toast:ApplicableDiscountsRequest\",\n    \"AppliedDiscount\": \"toast:AppliedDiscount\",\n    \"AppliedDiscountReason\": \"toast:AppliedDiscountReason\",\n    \"AppliedDiscountTrigger\": \"toast:AppliedDiscountTrigger\",\n    \"AppliedLoyaltyInfo\": \"toast:AppliedLoyaltyInfo\",\n    \"AppliedPackagingInfo\": \"toast:AppliedPackagingInfo\",\n    \"AppliedPackagingItem\": \"toast:AppliedPackagingItem\",\n    \"AppliedServiceCharge\": \"toast:AppliedServiceCharge\",\n    \"AppliedTaxRate\": \"toast:AppliedTaxRate\",\n    \"Check\": \"toast:Check\",\n    \"ConfigReference\": \"toast:ConfigReference\",\n    \"CurbsidePickupInfo\": \"toast:CurbsidePickupInfo\"\
  ,\n    \"Customer\": \"toast:Customer\",\n    \"DeliveryInfo\": \"toast:DeliveryInfo\",\n    \"DeliveryServiceInfo\": \"toast:DeliveryServiceInfo\",\n    \"Device\": \"toast:Device\",\n    \"ExternalReference\": \"toast:ExternalReference\",\n    \"Fulfillment\": \"toast:Fulfillment\",\n    \"GiftCardInfo\": \"toast:GiftCardInfo\",\n    \"LoyaltyDetails\": \"toast:LoyaltyDetails\",\n    \"MarketplaceFacilitatorTaxInfo\": \"toast:MarketplaceFacilitatorTaxInfo\",\n    \"Order\": \"toast:Order\",\n    \"OrderResponse\": \"toast:OrderResponse\",\n    \"Payment\": \"toast:Payment\",\n    \"Refund\": \"toast:Refund\",\n    \"RefundDetails\": \"toast:RefundDetails\",\n    \"Selection\": \"toast:Selection\",\n    \"ToastReference\": \"toast:ToastReference\",\n    \"UpdatePaymentRequest\": \"toast:UpdatePaymentRequest\",\n    \"VoidInformation\": \"toast:VoidInformation\",\n    \"address1\": {\n      \"@id\": \"toast:address1\",\n      \"@type\": \"xsd:string\"\n    },\n    \"address2\": {\n   \
  \   \"@id\": \"toast:address2\",\n      \"@type\": \"xsd:string\"\n    },\n    \"administrativeArea\": {\n      \"@id\": \"toast:administrativeArea\",\n      \"@type\": \"xsd:string\"\n    },\n    \"applicableChecks\": {\n      \"@id\": \"toast:applicableChecks\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"applicableSelections\": {\n      \"@id\": \"toast:applicableSelections\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"city\": {\n      \"@id\": \"toast:city\",\n      \"@type\": \"xsd:string\"\n    },\n    \"comment\": {\n      \"@id\": \"toast:comment\",\n      \"@type\": \"xsd:string\"\n    },\n    \"country\": {\n      \"@id\": \"toast:country\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deliveredDate\": {\n      \"@id\": \"toast:deliveredDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"deliveryEmployee\": {\n      \"@id\": \"toast:deliveryEmployee\",\n      \"@type\": \"@id\"\n    },\n    \"\
  deliveryState\": {\n      \"@id\": \"toast:deliveryState\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\"\n    },\n    \"discount\": {\n      \"@id\": \"toast:discount\",\n      \"@type\": \"@id\"\n    },\n    \"discountReason\": {\n      \"@id\": \"toast:discountReason\",\n      \"@type\": \"@id\"\n    },\n    \"dispatchedDate\": {\n      \"@id\": \"toast:dispatchedDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"entityType\": {\n      \"@id\": \"toast:entityType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"facilitatorCollectAndRemitTaxOrder\": {\n      \"@id\": \"toast:facilitatorCollectAndRemitTaxOrder\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"guid\": {\n      \"@id\": \"toast:guid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"toast:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"latitude\": {\n      \"@id\": \"toast:latitude\",\n      \"@type\": \"xsd:decimal\"\n\
  \    },\n    \"longitude\": {\n      \"@id\": \"toast:longitude\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\"\n    },\n    \"notes\": {\n      \"@id\": \"toast:notes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"order\": {\n      \"@id\": \"toast:order\",\n      \"@type\": \"@id\"\n    },\n    \"orders\": {\n      \"@id\": \"toast:orders\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"promoCode\": {\n      \"@id\": \"toast:promoCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"quantity\": {\n      \"@id\": \"toast:quantity\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"referenceId\": {\n      \"@id\": \"toast:referenceId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"refundAmount\": {\n      \"@id\": \"toast:refundAmount\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"refundBusinessDate\": {\n      \"@id\": \"toast:refundBusinessDate\",\n      \"@type\": \"xsd:integer\"\n    },\n\
  \    \"refundDate\": {\n      \"@id\": \"toast:refundDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"refundTransaction\": {\n      \"@id\": \"toast:refundTransaction\",\n      \"@type\": \"@id\"\n    },\n    \"selection\": {\n      \"@id\": \"toast:selection\",\n      \"@type\": \"xsd:string\"\n    },\n    \"state\": {\n      \"@id\": \"toast:state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"taxRefundAmount\": {\n      \"@id\": \"toast:taxRefundAmount\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"taxes\": {\n      \"@id\": \"toast:taxes\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tipAmount\": {\n      \"@id\": \"toast:tipAmount\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"tipRefundAmount\": {\n      \"@id\": \"toast:tipRefundAmount\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"unit\": {\n      \"@id\": \"toast:unit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"vendor\": {\n      \"@id\": \"toast:vendor\",\n\
  \      \"@type\": \"xsd:string\"\n    },\n    \"voidApprover\": {\n      \"@id\": \"toast:voidApprover\",\n      \"@type\": \"@id\"\n    },\n    \"voidBusinessDate\": {\n      \"@id\": \"toast:voidBusinessDate\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"voidDate\": {\n      \"@id\": \"toast:voidDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"voidReason\": {\n      \"@id\": \"toast:voidReason\",\n      \"@type\": \"@id\"\n    },\n    \"voidUser\": {\n      \"@id\": \"toast:voidUser\",\n      \"@type\": \"@id\"\n    },\n    \"zipCode\": {\n      \"@id\": \"toast:zipCode\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/toast/refs/heads/main/json-ld/toast-orders-context.jsonld
tags:
- Food Service
- Point of Sale
- Restaurants
- Hospitality
- JSON-LD
- Linked Data
- Semantic Web
---
