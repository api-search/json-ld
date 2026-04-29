---
class_count: 5
classes:
- SplitConfigurationList
- SplitConfigurationLogic
- SplitConfigurationRule
- SplitConfiguration
- description
context_file: json-ld/adyen-management-split-configuration-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-split-configuration-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Management Split Configuration from Adyen.
layout: jsonld
name: Adyen Management Split Configuration Context
namespaces:
- prefix: adyen
  uri: https://docs.adyen.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: set
  name: data
  type: string
- container: ''
  name: acquiringFees
  type: string
- container: ''
  name: additionalCommission
  type: string
- container: ''
  name: adyenCommission
  type: string
- container: ''
  name: adyenFees
  type: string
- container: ''
  name: adyenMarkup
  type: string
- container: ''
  name: chargeback
  type: string
- container: ''
  name: chargebackCostAllocation
  type: string
- container: ''
  name: commission
  type: string
- container: ''
  name: interchange
  type: string
- container: ''
  name: paymentFee
  type: string
- container: ''
  name: remainder
  type: string
- container: ''
  name: schemeFee
  type: string
- container: ''
  name: splitLogicId
  type: string
- container: ''
  name: surcharge
  type: string
- container: ''
  name: tip
  type: string
- container: ''
  name: currency
  type: string
- container: ''
  name: fundingSource
  type: string
- container: ''
  name: paymentMethod
  type: string
- container: ''
  name: ruleId
  type: string
- container: ''
  name: shopperInteraction
  type: string
- container: ''
  name: splitLogic
  type: string
- container: set
  name: rules
  type: string
- container: ''
  name: splitConfigurationId
  type: string
- container: set
  name: stores
  type: string
property_count: 25
provider_name: Adyen
provider_slug: adyen
slug: adyen-management-split-configuration-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"SplitConfigurationList\": \"adyen:SplitConfigurationList\",\n    \"SplitConfigurationLogic\": \"adyen:SplitConfigurationLogic\",\n    \"SplitConfigurationRule\": \"adyen:SplitConfigurationRule\",\n    \"SplitConfiguration\": \"adyen:SplitConfiguration\",\n    \"data\": {\n      \"@id\": \"adyen:data\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"acquiringFees\": {\n      \"@id\": \"adyen:acquiringFees\",\n      \"@type\": \"xsd:string\"\n    },\n    \"additionalCommission\": {\n      \"@id\": \"adyen:additionalCommission\",\n      \"@type\": \"xsd:string\"\n    },\n    \"adyenCommission\": {\n      \"@id\": \"adyen:adyenCommission\",\n      \"@type\": \"xsd:string\"\n    },\n    \"adyenFees\":\
  \ {\n      \"@id\": \"adyen:adyenFees\",\n      \"@type\": \"xsd:string\"\n    },\n    \"adyenMarkup\": {\n      \"@id\": \"adyen:adyenMarkup\",\n      \"@type\": \"xsd:string\"\n    },\n    \"chargeback\": {\n      \"@id\": \"adyen:chargeback\",\n      \"@type\": \"xsd:string\"\n    },\n    \"chargebackCostAllocation\": {\n      \"@id\": \"adyen:chargebackCostAllocation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"commission\": {\n      \"@id\": \"adyen:commission\",\n      \"@type\": \"xsd:string\"\n    },\n    \"interchange\": {\n      \"@id\": \"adyen:interchange\",\n      \"@type\": \"xsd:string\"\n    },\n    \"paymentFee\": {\n      \"@id\": \"adyen:paymentFee\",\n      \"@type\": \"xsd:string\"\n    },\n    \"remainder\": {\n      \"@id\": \"adyen:remainder\",\n      \"@type\": \"xsd:string\"\n    },\n    \"schemeFee\": {\n      \"@id\": \"adyen:schemeFee\",\n      \"@type\": \"xsd:string\"\n    },\n    \"splitLogicId\": {\n      \"@id\": \"adyen:splitLogicId\",\n      \"\
  @type\": \"xsd:string\"\n    },\n    \"surcharge\": {\n      \"@id\": \"adyen:surcharge\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tip\": {\n      \"@id\": \"adyen:tip\",\n      \"@type\": \"xsd:string\"\n    },\n    \"currency\": {\n      \"@id\": \"adyen:currency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fundingSource\": {\n      \"@id\": \"adyen:fundingSource\",\n      \"@type\": \"xsd:string\"\n    },\n    \"paymentMethod\": {\n      \"@id\": \"adyen:paymentMethod\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ruleId\": {\n      \"@id\": \"adyen:ruleId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shopperInteraction\": {\n      \"@id\": \"adyen:shopperInteraction\",\n      \"@type\": \"xsd:string\"\n    },\n    \"splitLogic\": {\n      \"@id\": \"adyen:splitLogic\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\",\n    \"rules\": {\n      \"@id\": \"adyen:rules\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"splitConfigurationId\": {\n      \"@id\": \"adyen:splitConfigurationId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stores\": {\n      \"@id\": \"adyen:stores\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-split-configuration-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
