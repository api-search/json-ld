---
class_count: 1
classes:
- MigratedStores
context_file: json-ld/adyen-accounts-migrated-stores-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-accounts-migrated-stores-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Accounts Migrated Stores from Adyen.
layout: jsonld
name: Adyen Accounts Migrated Stores Context
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
  name: businessLineId
  type: string
- container: ''
  name: storeCode
  type: string
- container: ''
  name: storeId
  type: string
- container: ''
  name: storeReference
  type: string
property_count: 4
provider_name: Adyen
provider_slug: adyen
slug: adyen-accounts-migrated-stores-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"MigratedStores\": \"adyen:MigratedStores\",\n    \"businessLineId\": {\n      \"@id\": \"adyen:businessLineId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"storeCode\": {\n      \"@id\": \"adyen:storeCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"storeId\": {\n      \"@id\": \"adyen:storeId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"storeReference\": {\n      \"@id\": \"adyen:storeReference\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-accounts-migrated-stores-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
