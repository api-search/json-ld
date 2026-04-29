---
class_count: 1
classes:
- ReconciliationResponse
context_file: json-ld/adyen-terminal-reconciliation-response-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-terminal-reconciliation-response-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Terminal Reconciliation Response from Adyen.
layout: jsonld
name: Adyen Terminal Reconciliation Response Context
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
  name: Response
  type: string
- container: ''
  name: ReconciliationType
  type: string
- container: ''
  name: POIReconciliationID
  type: integer
- container: set
  name: TransactionTotals
  type: string
property_count: 4
provider_name: Adyen
provider_slug: adyen
slug: adyen-terminal-reconciliation-response-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ReconciliationResponse\": \"adyen:ReconciliationResponse\",\n    \"Response\": {\n      \"@id\": \"adyen:Response\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ReconciliationType\": {\n      \"@id\": \"adyen:ReconciliationType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"POIReconciliationID\": {\n      \"@id\": \"adyen:POIReconciliationID\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"TransactionTotals\": {\n      \"@id\": \"adyen:TransactionTotals\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-terminal-reconciliation-response-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
