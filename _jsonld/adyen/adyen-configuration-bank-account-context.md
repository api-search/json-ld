---
class_count: 5
classes:
- BankAccountIdentificationTypeRequirement
- BankAccountIdentificationValidationRequest
- BankAccountModel
- BankAccount
- description
context_file: json-ld/adyen-configuration-bank-account-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-configuration-bank-account-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Configuration Bank Account from Adyen.
layout: jsonld
name: Adyen Configuration Bank Account Context
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
  name: bankAccountIdentificationTypes
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: accountIdentification
  type: string
- container: ''
  name: formFactor
  type: string
property_count: 4
provider_name: Adyen
provider_slug: adyen
slug: adyen-configuration-bank-account-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"BankAccountIdentificationTypeRequirement\": \"adyen:BankAccountIdentificationTypeRequirement\",\n    \"BankAccountIdentificationValidationRequest\": \"adyen:BankAccountIdentificationValidationRequest\",\n    \"BankAccountModel\": \"adyen:BankAccountModel\",\n    \"BankAccount\": \"adyen:BankAccount\",\n    \"bankAccountIdentificationTypes\": {\n      \"@id\": \"adyen:bankAccountIdentificationTypes\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\",\n    \"type\": {\n      \"@id\": \"adyen:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accountIdentification\": {\n      \"@id\": \"adyen:accountIdentification\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"formFactor\": {\n      \"@id\": \"adyen:formFactor\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-configuration-bank-account-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
