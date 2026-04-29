---
class_count: 2
classes:
- DefenseReasonsRequest
- DefenseReasonsResponse
context_file: json-ld/adyen-disputes-defense-reasons-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-disputes-defense-reasons-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Disputes Defense Reasons from Adyen.
layout: jsonld
name: Adyen Disputes Defense Reasons Context
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
  name: disputePspReference
  type: string
- container: ''
  name: merchantAccountCode
  type: string
- container: set
  name: defenseReasons
  type: string
- container: ''
  name: disputeServiceResult
  type: string
property_count: 4
provider_name: Adyen
provider_slug: adyen
slug: adyen-disputes-defense-reasons-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"DefenseReasonsRequest\": \"adyen:DefenseReasonsRequest\",\n    \"DefenseReasonsResponse\": \"adyen:DefenseReasonsResponse\",\n    \"disputePspReference\": {\n      \"@id\": \"adyen:disputePspReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"merchantAccountCode\": {\n      \"@id\": \"adyen:merchantAccountCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"defenseReasons\": {\n      \"@id\": \"adyen:defenseReasons\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"disputeServiceResult\": {\n      \"@id\": \"adyen:disputeServiceResult\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-disputes-defense-reasons-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
