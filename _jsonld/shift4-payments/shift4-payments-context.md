---
api_specs:
- filename: shift4-api-openapi.yml
  format: yaml
  label: Shift4 Payments API
  slug: shift4-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/shift4-payments/main/openapi/shift4-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/shift4-payments-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/shift4-payments/refs/heads/main/json-ld/shift4-payments-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Shift4 Payments from Shift4 Payments.
layout: jsonld
name: Shift4 Payments Context
namespaces:
- prefix: shift4
  uri: https://shift4.com/schemas/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: Customer
  type: ''
- container: ''
  name: Card
  type: ''
- container: ''
  name: Token
  type: ''
- container: ''
  name: Charge
  type: ''
- container: ''
  name: Refund
  type: ''
- container: ''
  name: Plan
  type: ''
- container: ''
  name: Subscription
  type: ''
- container: ''
  name: CheckoutSession
  type: ''
- container: ''
  name: Event
  type: ''
property_count: 9
provider_name: Shift4 Payments
provider_slug: shift4-payments
slug: shift4-payments-context
source_filename: shift4-payments-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"shift4\": \"https://shift4.com/schemas/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Customer\": {\n      \"@id\": \"shift4:Customer\",\n      \"@context\": {\n        \"id\": { \"@id\": \"shift4:customerId\", \"@type\": \"xsd:string\" },\n        \"email\": { \"@id\": \"schema:email\", \"@type\": \"xsd:string\" },\n        \"phoneNumber\": { \"@id\": \"schema:telephone\", \"@type\": \"xsd:string\" },\n        \"description\": { \"@id\": \"schema:description\", \"@type\": \"xsd:string\" },\n        \"defaultCardId\": { \"@id\": \"shift4:defaultCardId\", \"@type\": \"xsd:string\" },\n        \"created\": { \"@id\": \"schema:dateCreated\", \"@type\": \"xsd:integer\" },\n        \"deleted\": { \"@id\": \"shift4:deleted\", \"@type\": \"xsd:boolean\" },\n        \"metadata\": { \"@id\": \"shift4:metadata\", \"@type\": \"@json\" }\n      }\n    },\n    \"Card\": {\n   \
  \   \"@id\": \"shift4:Card\",\n      \"@context\": {\n        \"id\": { \"@id\": \"shift4:cardId\", \"@type\": \"xsd:string\" },\n        \"first6\": { \"@id\": \"shift4:first6\", \"@type\": \"xsd:string\" },\n        \"last4\": { \"@id\": \"shift4:last4\", \"@type\": \"xsd:string\" },\n        \"brand\": { \"@id\": \"shift4:cardBrand\", \"@type\": \"xsd:string\" },\n        \"type\": { \"@id\": \"shift4:cardType\", \"@type\": \"xsd:string\" },\n        \"expMonth\": { \"@id\": \"shift4:expMonth\", \"@type\": \"xsd:string\" },\n        \"expYear\": { \"@id\": \"shift4:expYear\", \"@type\": \"xsd:string\" },\n        \"cardholderName\": { \"@id\": \"schema:name\", \"@type\": \"xsd:string\" },\n        \"customerId\": { \"@id\": \"shift4:customer\", \"@type\": \"xsd:string\" },\n        \"country\": { \"@id\": \"schema:addressCountry\", \"@type\": \"xsd:string\" },\n        \"issuer\": { \"@id\": \"shift4:issuer\", \"@type\": \"xsd:string\" },\n        \"created\": { \"@id\": \"schema:dateCreated\"\
  , \"@type\": \"xsd:integer\" }\n      }\n    },\n    \"Token\": {\n      \"@id\": \"shift4:Token\",\n      \"@context\": {\n        \"id\": { \"@id\": \"shift4:tokenId\", \"@type\": \"xsd:string\" },\n        \"first6\": { \"@id\": \"shift4:first6\", \"@type\": \"xsd:string\" },\n        \"last4\": { \"@id\": \"shift4:last4\", \"@type\": \"xsd:string\" },\n        \"brand\": { \"@id\": \"shift4:cardBrand\", \"@type\": \"xsd:string\" },\n        \"used\": { \"@id\": \"shift4:used\", \"@type\": \"xsd:boolean\" },\n        \"created\": { \"@id\": \"schema:dateCreated\", \"@type\": \"xsd:integer\" }\n      }\n    },\n    \"Charge\": {\n      \"@id\": \"shift4:Charge\",\n      \"@context\": {\n        \"id\": { \"@id\": \"shift4:chargeId\", \"@type\": \"xsd:string\" },\n        \"amount\": { \"@id\": \"schema:price\", \"@type\": \"xsd:integer\" },\n        \"amountRefunded\": { \"@id\": \"shift4:amountRefunded\", \"@type\": \"xsd:integer\" },\n        \"currency\": { \"@id\": \"schema:priceCurrency\"\
  , \"@type\": \"xsd:string\" },\n        \"description\": { \"@id\": \"schema:description\", \"@type\": \"xsd:string\" },\n        \"status\": { \"@id\": \"shift4:status\", \"@type\": \"xsd:string\" },\n        \"type\": { \"@id\": \"shift4:chargeType\", \"@type\": \"xsd:string\" },\n        \"captured\": { \"@id\": \"shift4:captured\", \"@type\": \"xsd:boolean\" },\n        \"refunded\": { \"@id\": \"shift4:refunded\", \"@type\": \"xsd:boolean\" },\n        \"disputed\": { \"@id\": \"shift4:disputed\", \"@type\": \"xsd:boolean\" },\n        \"customerId\": { \"@id\": \"shift4:customer\", \"@type\": \"xsd:string\" },\n        \"subscriptionId\": { \"@id\": \"shift4:subscription\", \"@type\": \"xsd:string\" },\n        \"merchantAccountId\": { \"@id\": \"shift4:merchantAccount\", \"@type\": \"xsd:string\" },\n        \"created\": { \"@id\": \"schema:dateCreated\", \"@type\": \"xsd:integer\" },\n        \"metadata\": { \"@id\": \"shift4:metadata\", \"@type\": \"@json\" }\n      }\n    },\n\
  \    \"Refund\": {\n      \"@id\": \"shift4:Refund\",\n      \"@context\": {\n        \"id\": { \"@id\": \"shift4:refundId\", \"@type\": \"xsd:string\" },\n        \"amount\": { \"@id\": \"schema:price\", \"@type\": \"xsd:integer\" },\n        \"currency\": { \"@id\": \"schema:priceCurrency\", \"@type\": \"xsd:string\" },\n        \"charge\": { \"@id\": \"shift4:charge\", \"@type\": \"xsd:string\" },\n        \"reason\": { \"@id\": \"shift4:refundReason\", \"@type\": \"xsd:string\" },\n        \"status\": { \"@id\": \"shift4:status\", \"@type\": \"xsd:string\" },\n        \"created\": { \"@id\": \"schema:dateCreated\", \"@type\": \"xsd:integer\" },\n        \"metadata\": { \"@id\": \"shift4:metadata\", \"@type\": \"@json\" }\n      }\n    },\n    \"Plan\": {\n      \"@id\": \"shift4:Plan\",\n      \"@context\": {\n        \"id\": { \"@id\": \"shift4:planId\", \"@type\": \"xsd:string\" },\n        \"name\": { \"@id\": \"schema:name\", \"@type\": \"xsd:string\" },\n        \"amount\": {\
  \ \"@id\": \"schema:price\", \"@type\": \"xsd:integer\" },\n        \"currency\": { \"@id\": \"schema:priceCurrency\", \"@type\": \"xsd:string\" },\n        \"interval\": { \"@id\": \"shift4:interval\", \"@type\": \"xsd:string\" },\n        \"intervalCount\": { \"@id\": \"shift4:intervalCount\", \"@type\": \"xsd:integer\" },\n        \"billingCycles\": { \"@id\": \"shift4:billingCycles\", \"@type\": \"xsd:integer\" },\n        \"trialPeriodDays\": { \"@id\": \"shift4:trialPeriodDays\", \"@type\": \"xsd:integer\" },\n        \"statementDescription\": { \"@id\": \"shift4:statementDescription\", \"@type\": \"xsd:string\" },\n        \"created\": { \"@id\": \"schema:dateCreated\", \"@type\": \"xsd:integer\" }\n      }\n    },\n    \"Subscription\": {\n      \"@id\": \"shift4:Subscription\",\n      \"@context\": {\n        \"id\": { \"@id\": \"shift4:subscriptionId\", \"@type\": \"xsd:string\" },\n        \"planId\": { \"@id\": \"shift4:plan\", \"@type\": \"xsd:string\" },\n        \"customerId\"\
  : { \"@id\": \"shift4:customer\", \"@type\": \"xsd:string\" },\n        \"status\": { \"@id\": \"shift4:status\", \"@type\": \"xsd:string\" },\n        \"quantity\": { \"@id\": \"schema:quantity\", \"@type\": \"xsd:integer\" },\n        \"captureCharges\": { \"@id\": \"shift4:captureCharges\", \"@type\": \"xsd:boolean\" },\n        \"currentPeriodStart\": { \"@id\": \"shift4:currentPeriodStart\", \"@type\": \"xsd:integer\" },\n        \"currentPeriodEnd\": { \"@id\": \"shift4:currentPeriodEnd\", \"@type\": \"xsd:integer\" },\n        \"cancelAtPeriodEnd\": { \"@id\": \"shift4:cancelAtPeriodEnd\", \"@type\": \"xsd:boolean\" },\n        \"trialStart\": { \"@id\": \"shift4:trialStart\", \"@type\": \"xsd:integer\" },\n        \"trialEnd\": { \"@id\": \"shift4:trialEnd\", \"@type\": \"xsd:integer\" },\n        \"created\": { \"@id\": \"schema:dateCreated\", \"@type\": \"xsd:integer\" }\n      }\n    },\n    \"CheckoutSession\": {\n      \"@id\": \"shift4:CheckoutSession\",\n      \"@context\"\
  : {\n        \"id\": { \"@id\": \"shift4:sessionId\", \"@type\": \"xsd:string\" },\n        \"url\": { \"@id\": \"schema:url\", \"@type\": \"@id\" },\n        \"redirectUrl\": { \"@id\": \"shift4:redirectUrl\", \"@type\": \"@id\" },\n        \"status\": { \"@id\": \"shift4:status\", \"@type\": \"xsd:string\" },\n        \"action\": { \"@id\": \"shift4:action\", \"@type\": \"xsd:string\" },\n        \"currency\": { \"@id\": \"schema:priceCurrency\", \"@type\": \"xsd:string\" },\n        \"customer\": { \"@id\": \"shift4:customer\", \"@type\": \"xsd:string\" },\n        \"metadata\": { \"@id\": \"shift4:metadata\", \"@type\": \"@json\" }\n      }\n    },\n    \"Event\": {\n      \"@id\": \"shift4:Event\",\n      \"@context\": {\n        \"id\": { \"@id\": \"shift4:eventId\", \"@type\": \"xsd:string\" },\n        \"type\": { \"@id\": \"shift4:eventType\", \"@type\": \"xsd:string\" },\n        \"data\": { \"@id\": \"shift4:eventData\", \"@type\": \"@json\" },\n        \"created\": { \"@id\"\
  : \"schema:dateCreated\", \"@type\": \"xsd:integer\" }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/shift4-payments/refs/heads/main/json-ld/shift4-payments-context.jsonld
tags:
- Payments
- Fintech
- Commerce
- Checkout
- JSON-LD
- Linked Data
- Semantic Web
---
