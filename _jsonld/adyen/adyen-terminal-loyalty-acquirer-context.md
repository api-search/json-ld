---
class_count: 1
classes:
- LoyaltyAcquirerData
context_file: json-ld/adyen-terminal-loyalty-acquirer-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-terminal-loyalty-acquirer-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Terminal Loyalty Acquirer from Adyen.
layout: jsonld
name: Adyen Terminal Loyalty Acquirer Context
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
- container: ''
  name: LoyaltyAcquirerID
  type: string
- container: ''
  name: ApprovalCode
  type: string
- container: ''
  name: LoyaltyTransactionID
  type: string
- container: ''
  name: HostReconciliationID
  type: string
property_count: 4
provider_name: Adyen
provider_slug: adyen
slug: adyen-terminal-loyalty-acquirer-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"LoyaltyAcquirerData\": \"adyen:LoyaltyAcquirerData\",\n    \"LoyaltyAcquirerID\": {\n      \"@id\": \"adyen:LoyaltyAcquirerID\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ApprovalCode\": {\n      \"@id\": \"adyen:ApprovalCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LoyaltyTransactionID\": {\n      \"@id\": \"adyen:LoyaltyTransactionID\",\n      \"@type\": \"xsd:string\"\n    },\n    \"HostReconciliationID\": {\n      \"@id\": \"adyen:HostReconciliationID\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-terminal-loyalty-acquirer-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
