---
class_count: 1
classes:
- PaginatedAccountHoldersResponse
context_file: json-ld/adyen-configuration-paginated-account-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-configuration-paginated-account-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Configuration Paginated Account from Adyen.
layout: jsonld
name: Adyen Configuration Paginated Account Context
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
  name: accountHolders
  type: string
- container: ''
  name: hasNext
  type: boolean
- container: ''
  name: hasPrevious
  type: boolean
property_count: 3
provider_name: Adyen
provider_slug: adyen
slug: adyen-configuration-paginated-account-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"PaginatedAccountHoldersResponse\": \"adyen:PaginatedAccountHoldersResponse\",\n    \"accountHolders\": {\n      \"@id\": \"adyen:accountHolders\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"hasNext\": {\n      \"@id\": \"adyen:hasNext\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"hasPrevious\": {\n      \"@id\": \"adyen:hasPrevious\",\n      \"@type\": \"xsd:boolean\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-configuration-paginated-account-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
