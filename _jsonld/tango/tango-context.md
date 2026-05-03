---
api_specs:
- filename: tango-raas-api-openapi.yml
  format: yaml
  label: Tango RaaS API
  slug: raas-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tango/refs/heads/main/openapi/tango-raas-api-openapi.yml
class_count: 43
classes:
- Order
- referenceOrderID
- orderRefID
- customerIdentifier
- accountIdentifier
- amount
- currencyCode
- status
- lineItems
- createdAt
- LineItem
- referenceLineItemId
- utid
- rewardName
- brandCode
- brandName
- fulfillment
- Account
- accountIdentifierField
- displayName
- currentBalance
- Customer
- customerIdentifierField
- Brand
- brandCodeField
- description
- items
- CatalogItem
- valueType
- faceValue
- minValue
- maxValue
- countries
- credentialTypes
- ExchangeRate
- exchangeRate
- Recipient
- Sender
- Fulfillment
- fulfillmentType
- redemptionUrl
- cardNumber
- cardPin
context_file: json-ld/tango-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/tango/refs/heads/main/json-ld/tango-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Tango from Tango.
layout: jsonld
name: Tango Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: tango
  uri: https://www.tangocard.com/vocab#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties: []
property_count: 0
provider_name: Tango
provider_slug: tango
slug: tango-context
source_filename: tango-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"tango\": \"https://www.tangocard.com/vocab#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Order\": \"schema:Order\",\n    \"referenceOrderID\": \"schema:orderNumber\",\n    \"orderRefID\": \"tango:externalReferenceId\",\n    \"customerIdentifier\": \"schema:customer\",\n    \"accountIdentifier\": \"tango:accountIdentifier\",\n    \"amount\": \"schema:price\",\n    \"currencyCode\": \"schema:priceCurrency\",\n    \"status\": \"schema:orderStatus\",\n    \"lineItems\": \"schema:orderedItem\",\n    \"createdAt\": \"schema:orderDate\",\n\n    \"LineItem\": \"schema:OrderItem\",\n    \"referenceLineItemId\": \"schema:identifier\",\n    \"utid\": \"tango:universalTokenId\",\n    \"rewardName\": \"schema:name\",\n    \"brandCode\": \"tango:brandCode\",\n    \"brandName\": \"schema:brand\",\n    \"fulfillment\": \"tango:fulfillment\",\n\n    \"Account\": \"schema:BankAccount\"\
  ,\n    \"accountIdentifierField\": \"schema:identifier\",\n    \"displayName\": \"schema:name\",\n    \"currentBalance\": \"schema:amount\",\n\n    \"Customer\": \"schema:Organization\",\n    \"customerIdentifierField\": \"schema:identifier\",\n\n    \"Brand\": \"schema:Brand\",\n    \"brandCodeField\": \"schema:identifier\",\n    \"description\": \"schema:description\",\n    \"items\": \"schema:hasOfferCatalog\",\n\n    \"CatalogItem\": \"schema:Offer\",\n    \"valueType\": \"tango:valueType\",\n    \"faceValue\": \"schema:price\",\n    \"minValue\": \"schema:minPrice\",\n    \"maxValue\": \"schema:maxPrice\",\n    \"countries\": \"schema:areaServed\",\n    \"credentialTypes\": \"tango:credentialTypes\",\n\n    \"ExchangeRate\": \"schema:ExchangeRateSpecification\",\n    \"exchangeRate\": \"schema:currentExchangeRate\",\n\n    \"Recipient\": \"schema:Person\",\n    \"Sender\": \"schema:Person\",\n\n    \"Fulfillment\": \"tango:Fulfillment\",\n    \"fulfillmentType\": \"tango:fulfillmentType\"\
  ,\n    \"redemptionUrl\": \"schema:url\",\n    \"cardNumber\": \"tango:cardNumber\",\n    \"cardPin\": \"tango:cardPin\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/tango/refs/heads/main/json-ld/tango-context.jsonld
tags:
- Catalog Management
- Digital Rewards
- Gift Cards
- Incentives
- Loyalty
- Rewards As A Service
- JSON-LD
- Linked Data
- Semantic Web
---
