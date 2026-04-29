---
class_count: 1
classes:
- MigrationData
context_file: json-ld/adyen-accounts-migration-data-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-accounts-migration-data-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Accounts Migration Data from Adyen.
layout: jsonld
name: Adyen Accounts Migration Data Context
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
  name: accountHolderId
  type: string
- container: ''
  name: balancePlatform
  type: string
- container: ''
  name: migrated
  type: boolean
- container: set
  name: migratedAccounts
  type: string
- container: set
  name: migratedShareholders
  type: string
- container: set
  name: migratedStores
  type: string
- container: ''
  name: migrationDate
  type: dateTime
property_count: 7
provider_name: Adyen
provider_slug: adyen
slug: adyen-accounts-migration-data-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"MigrationData\": \"adyen:MigrationData\",\n    \"accountHolderId\": {\n      \"@id\": \"adyen:accountHolderId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"balancePlatform\": {\n      \"@id\": \"adyen:balancePlatform\",\n      \"@type\": \"xsd:string\"\n    },\n    \"migrated\": {\n      \"@id\": \"adyen:migrated\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"migratedAccounts\": {\n      \"@id\": \"adyen:migratedAccounts\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"migratedShareholders\": {\n      \"@id\": \"adyen:migratedShareholders\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"migratedStores\": {\n      \"@id\": \"adyen:migratedStores\",\n  \
  \    \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"migrationDate\": {\n      \"@id\": \"adyen:migrationDate\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-accounts-migration-data-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
