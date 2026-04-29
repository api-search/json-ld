---
class_count: 1
classes:
- RestServiceError
context_file: json-ld/adyen-configuration-rest-service-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-configuration-rest-service-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Configuration Rest Service from Adyen.
layout: jsonld
name: Adyen Configuration Rest Service Context
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
  name: detail
  type: string
- container: ''
  name: errorCode
  type: string
- container: ''
  name: instance
  type: string
- container: set
  name: invalidFields
  type: string
- container: ''
  name: requestId
  type: string
- container: ''
  name: response
  type: string
- container: ''
  name: status
  type: integer
- container: ''
  name: title
  type: string
- container: ''
  name: type
  type: string
property_count: 9
provider_name: Adyen
provider_slug: adyen
slug: adyen-configuration-rest-service-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"RestServiceError\": \"adyen:RestServiceError\",\n    \"detail\": {\n      \"@id\": \"adyen:detail\",\n      \"@type\": \"xsd:string\"\n    },\n    \"errorCode\": {\n      \"@id\": \"adyen:errorCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"instance\": {\n      \"@id\": \"adyen:instance\",\n      \"@type\": \"xsd:string\"\n    },\n    \"invalidFields\": {\n      \"@id\": \"adyen:invalidFields\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"requestId\": {\n      \"@id\": \"adyen:requestId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"response\": {\n      \"@id\": \"adyen:response\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"adyen:status\",\n      \"\
  @type\": \"xsd:integer\"\n    },\n    \"title\": {\n      \"@id\": \"adyen:title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"adyen:type\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-configuration-rest-service-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
