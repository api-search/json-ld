---
class_count: 1
classes:
- VerificationDeadline
context_file: json-ld/adyen-configuration-verification-deadline-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-configuration-verification-deadline-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Configuration Verification Deadline from Adyen.
layout: jsonld
name: Adyen Configuration Verification Deadline Context
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
  name: capabilities
  type: string
- container: set
  name: entityIds
  type: string
- container: ''
  name: expiresAt
  type: dateTime
property_count: 3
provider_name: Adyen
provider_slug: adyen
slug: adyen-configuration-verification-deadline-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"VerificationDeadline\": \"adyen:VerificationDeadline\",\n    \"capabilities\": {\n      \"@id\": \"adyen:capabilities\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"entityIds\": {\n      \"@id\": \"adyen:entityIds\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"expiresAt\": {\n      \"@id\": \"adyen:expiresAt\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-configuration-verification-deadline-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
