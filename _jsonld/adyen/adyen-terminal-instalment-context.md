---
class_count: 1
classes:
- Instalment
context_file: json-ld/adyen-terminal-instalment-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-terminal-instalment-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Terminal Instalment from Adyen.
layout: jsonld
name: Adyen Terminal Instalment Context
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
  name: InstalmentType
  type: string
- container: ''
  name: SequenceNumber
  type: integer
- container: ''
  name: PlanID
  type: string
- container: ''
  name: Period
  type: integer
- container: ''
  name: PeriodUnit
  type: string
- container: ''
  name: FirstPaymentDate
  type: date
- container: ''
  name: TotalNbOfPayments
  type: integer
- container: ''
  name: CumulativeAmount
  type: decimal
- container: ''
  name: FirstAmount
  type: decimal
- container: ''
  name: Charges
  type: decimal
property_count: 10
provider_name: Adyen
provider_slug: adyen
slug: adyen-terminal-instalment-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Instalment\": \"adyen:Instalment\",\n    \"InstalmentType\": {\n      \"@id\": \"adyen:InstalmentType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SequenceNumber\": {\n      \"@id\": \"adyen:SequenceNumber\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"PlanID\": {\n      \"@id\": \"adyen:PlanID\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Period\": {\n      \"@id\": \"adyen:Period\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"PeriodUnit\": {\n      \"@id\": \"adyen:PeriodUnit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"FirstPaymentDate\": {\n      \"@id\": \"adyen:FirstPaymentDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"TotalNbOfPayments\": {\n      \"@id\": \"adyen:TotalNbOfPayments\",\n   \
  \   \"@type\": \"xsd:integer\"\n    },\n    \"CumulativeAmount\": {\n      \"@id\": \"adyen:CumulativeAmount\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"FirstAmount\": {\n      \"@id\": \"adyen:FirstAmount\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"Charges\": {\n      \"@id\": \"adyen:Charges\",\n      \"@type\": \"xsd:decimal\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-terminal-instalment-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
