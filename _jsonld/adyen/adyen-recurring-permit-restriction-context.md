---
class_count: 1
classes:
- PermitRestriction
context_file: json-ld/adyen-recurring-permit-restriction-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-recurring-permit-restriction-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Recurring Permit Restriction from Adyen.
layout: jsonld
name: Adyen Recurring Permit Restriction Context
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
  name: maxAmount
  type: string
- container: ''
  name: singleTransactionLimit
  type: string
- container: ''
  name: singleUse
  type: boolean
property_count: 3
provider_name: Adyen
provider_slug: adyen
slug: adyen-recurring-permit-restriction-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"PermitRestriction\": \"adyen:PermitRestriction\",\n    \"maxAmount\": {\n      \"@id\": \"adyen:maxAmount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"singleTransactionLimit\": {\n      \"@id\": \"adyen:singleTransactionLimit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"singleUse\": {\n      \"@id\": \"adyen:singleUse\",\n      \"@type\": \"xsd:boolean\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-recurring-permit-restriction-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
