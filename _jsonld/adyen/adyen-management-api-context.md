---
class_count: 3
classes:
- ApiCredentialLinks
- ApiCredential
- description
context_file: json-ld/adyen-management-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Management Api from Adyen.
layout: jsonld
name: Adyen Management Api Context
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
  name: allowedOrigins
  type: string
- container: ''
  name: company
  type: string
- container: ''
  name: generateApiKey
  type: string
- container: ''
  name: generateClientKey
  type: string
- container: ''
  name: merchant
  type: string
- container: ''
  name: self
  type: string
- container: ''
  name: Links
  type: string
- container: ''
  name: active
  type: boolean
- container: set
  name: allowedIpAddresses
  type: string
- container: ''
  name: clientKey
  type: string
- container: ''
  name: id
  type: string
- container: set
  name: roles
  type: string
- container: ''
  name: username
  type: string
property_count: 13
provider_name: Adyen
provider_slug: adyen
slug: adyen-management-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ApiCredentialLinks\": \"adyen:ApiCredentialLinks\",\n    \"ApiCredential\": \"adyen:ApiCredential\",\n    \"allowedOrigins\": {\n      \"@id\": \"adyen:allowedOrigins\",\n      \"@type\": \"xsd:string\"\n    },\n    \"company\": {\n      \"@id\": \"adyen:company\",\n      \"@type\": \"xsd:string\"\n    },\n    \"generateApiKey\": {\n      \"@id\": \"adyen:generateApiKey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"generateClientKey\": {\n      \"@id\": \"adyen:generateClientKey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"merchant\": {\n      \"@id\": \"adyen:merchant\",\n      \"@type\": \"xsd:string\"\n    },\n    \"self\": {\n      \"@id\": \"adyen:self\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Links\": {\n\
  \      \"@id\": \"adyen:_links\",\n      \"@type\": \"xsd:string\"\n    },\n    \"active\": {\n      \"@id\": \"adyen:active\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"allowedIpAddresses\": {\n      \"@id\": \"adyen:allowedIpAddresses\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"clientKey\": {\n      \"@id\": \"adyen:clientKey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\",\n    \"id\": {\n      \"@id\": \"adyen:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"roles\": {\n      \"@id\": \"adyen:roles\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"username\": {\n      \"@id\": \"adyen:username\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-api-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
