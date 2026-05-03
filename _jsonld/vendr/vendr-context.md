---
api_specs:
- filename: vendr-openapi.yml
  format: yaml
  label: Vendr OpenPrice API
  slug: vendr-openapi
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/vendr/refs/heads/main/openapi/vendr-openapi.yml
class_count: 32
classes:
- CatalogProduct
- PricingEstimate
- PurchaseScope
- NegotiationInsight
- WebhookSubscription
- productId
- productName
- company
- description
- categories
- tiers
- addOns
- priceRange
- p25
- median
- p75
- currency
- unitPrice
- confidence
- sampleSize
- negotiationInsights
- discountPotential
- leverageTiming
- tips
- tier
- licenses
- termMonths
- billingCadence
- webhookId
- url
- events
- status
context_file: json-ld/vendr-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/vendr/refs/heads/main/json-ld/vendr-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Vendr from Vendr.
layout: jsonld
name: Vendr Context
namespaces:
- prefix: vendr
  uri: https://api.vendr.com/vocab/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: createdAt
  type: dateTime
property_count: 1
provider_name: Vendr
provider_slug: vendr
slug: vendr-context
source_filename: vendr-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"vendr\": \"https://api.vendr.com/vocab/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"CatalogProduct\": \"vendr:CatalogProduct\",\n    \"PricingEstimate\": \"vendr:PricingEstimate\",\n    \"PurchaseScope\": \"vendr:PurchaseScope\",\n    \"NegotiationInsight\": \"vendr:NegotiationInsight\",\n    \"WebhookSubscription\": \"vendr:WebhookSubscription\",\n\n    \"productId\": \"schema:identifier\",\n    \"productName\": \"schema:name\",\n    \"company\": \"schema:brand\",\n    \"description\": \"schema:description\",\n    \"categories\": \"schema:category\",\n    \"tiers\": \"vendr:hasTier\",\n    \"addOns\": \"vendr:hasAddOn\",\n\n    \"priceRange\": \"schema:priceRange\",\n    \"p25\": \"vendr:priceP25\",\n    \"median\": \"vendr:priceMedian\",\n    \"p75\": \"vendr:priceP75\",\n    \"currency\": \"schema:priceCurrency\",\n\n    \"unitPrice\": \"schema:unitPrice\",\n    \"confidence\": \"\
  vendr:confidenceScore\",\n    \"sampleSize\": \"vendr:contractSampleSize\",\n\n    \"negotiationInsights\": \"vendr:negotiationInsights\",\n    \"discountPotential\": \"vendr:discountPotential\",\n    \"leverageTiming\": \"vendr:leverageTiming\",\n    \"tips\": \"vendr:negotiationTip\",\n\n    \"tier\": \"vendr:productTier\",\n    \"licenses\": \"vendr:licenseCount\",\n    \"termMonths\": \"vendr:contractTermMonths\",\n    \"billingCadence\": \"vendr:billingCadence\",\n\n    \"webhookId\": \"schema:identifier\",\n    \"url\": \"schema:url\",\n    \"events\": \"vendr:subscribedEvents\",\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"status\": \"schema:status\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/vendr/refs/heads/main/json-ld/vendr-context.jsonld
tags:
- Pricing
- Procurement
- SaaS
- Software Spend Management
- Negotiation
- JSON-LD
- Linked Data
- Semantic Web
---
