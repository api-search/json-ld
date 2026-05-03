---
api_specs:
- filename: td-synnex-streamone-ion-openapi.yml
  format: yaml
  label: TD SYNNEX StreamOne Ion API
  slug: streamone-ion
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/td-synnex/refs/heads/main/openapi/td-synnex-streamone-ion-openapi.yml
class_count: 34
classes:
- StreamOnePartner
- CloudSubscription
- DistributionOrder
- TechnologyProduct
- ShoppingCart
- CartItem
- CloudProfile
- ProvisioningTemplate
- BusinessReport
- customerId
- companyName
- email
- phone
- address
- street
- city
- state
- postalCode
- country
- status
- orderId
- totalAmount
- currency
- productId
- vendor
- subscriptionId
- startDate
- endDate
- renewalDate
- autoRenew
- quantity
- unitPrice
- reportId
- generatedAt
context_file: json-ld/td-synnex-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/td-synnex/refs/heads/main/json-ld/td-synnex-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Td Synnex from TD SYNNEX.
layout: jsonld
name: Td Synnex Context
namespaces:
- prefix: tdsynnex
  uri: https://www.tdsynnex.com/vocabulary/
- prefix: streamone
  uri: https://docs.streamone.cloud/vocabulary/
properties:
- container: ''
  name: EndCustomer
  type: reference
property_count: 1
provider_name: TD SYNNEX
provider_slug: td-synnex
slug: td-synnex-context
source_filename: td-synnex-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"tdsynnex\": \"https://www.tdsynnex.com/vocabulary/\",\n    \"streamone\": \"https://docs.streamone.cloud/vocabulary/\",\n    \"StreamOnePartner\": \"tdsynnex:StreamOnePartner\",\n    \"EndCustomer\": {\n      \"@id\": \"schema:Organization\",\n      \"@type\": \"@id\"\n    },\n    \"CloudSubscription\": \"tdsynnex:CloudSubscription\",\n    \"DistributionOrder\": \"tdsynnex:DistributionOrder\",\n    \"TechnologyProduct\": \"tdsynnex:TechnologyProduct\",\n    \"ShoppingCart\": \"schema:ShoppingCart\",\n    \"CartItem\": \"schema:ItemList\",\n    \"CloudProfile\": \"tdsynnex:CloudProfile\",\n    \"ProvisioningTemplate\": \"tdsynnex:ProvisioningTemplate\",\n    \"BusinessReport\": \"schema:Report\",\n    \"customerId\": \"schema:identifier\",\n    \"companyName\": \"schema:legalName\",\n    \"email\": \"schema:email\",\n    \"phone\": \"schema:telephone\",\n    \"address\": \"schema:PostalAddress\",\n    \"street\"\
  : \"schema:streetAddress\",\n    \"city\": \"schema:addressLocality\",\n    \"state\": \"schema:addressRegion\",\n    \"postalCode\": \"schema:postalCode\",\n    \"country\": \"schema:addressCountry\",\n    \"status\": \"schema:status\",\n    \"orderId\": \"schema:orderNumber\",\n    \"totalAmount\": \"schema:totalPaymentDue\",\n    \"currency\": \"schema:priceCurrency\",\n    \"productId\": \"schema:productID\",\n    \"vendor\": \"schema:brand\",\n    \"subscriptionId\": \"tdsynnex:subscriptionIdentifier\",\n    \"startDate\": \"schema:startDate\",\n    \"endDate\": \"schema:endDate\",\n    \"renewalDate\": \"tdsynnex:renewalDate\",\n    \"autoRenew\": \"tdsynnex:autoRenew\",\n    \"quantity\": \"schema:quantity\",\n    \"unitPrice\": \"schema:price\",\n    \"reportId\": \"tdsynnex:reportIdentifier\",\n    \"generatedAt\": \"schema:dateCreated\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/td-synnex/refs/heads/main/json-ld/td-synnex-context.jsonld
tags:
- Technology Distribution
- IT Distribution
- Cloud
- Reseller
- StreamOne
- Fortune 100
- B2B
- JSON-LD
- Linked Data
- Semantic Web
---
