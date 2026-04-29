---
class_count: 3
classes:
- Transaction
- Card
- FileObject
context_file: json-ld/affirm-direct-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/affirm/refs/heads/main/json-ld/affirm-direct-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Affirm Direct from affirm.
layout: jsonld
name: Affirm Direct Context
namespaces:
- prefix: affirm
  uri: https://affirm.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: id
  type: string
- container: ''
  name: checkoutId
  type: string
- container: ''
  name: orderId
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: amount
  type: integer
- container: ''
  name: amountRefunded
  type: integer
- container: ''
  name: currency
  type: string
- container: ''
  name: created
  type: dateTime
- container: ''
  name: authorizationExpiration
  type: dateTime
- container: ''
  name: number
  type: string
- container: ''
  name: cvv
  type: string
- container: ''
  name: expiration
  type: string
- container: ''
  name: billing
  type: reference
- container: ''
  name: address
  type: reference
- container: ''
  name: line1
  type: string
- container: ''
  name: city
  type: string
- container: ''
  name: state
  type: string
- container: ''
  name: zipcode
  type: string
- container: ''
  name: country
  type: string
- container: ''
  name: filename
  type: string
- container: ''
  name: size
  type: integer
- container: ''
  name: contentType
  type: string
- container: ''
  name: purpose
  type: string
property_count: 23
provider_name: affirm
provider_slug: affirm
slug: affirm-direct-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"affirm\": \"https://affirm.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Transaction\": \"affirm:Transaction\",\n    \"id\": {\n      \"@id\": \"affirm:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"checkoutId\": {\n      \"@id\": \"affirm:checkout_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"orderId\": {\n      \"@id\": \"affirm:order_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"affirm:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"amount\": {\n      \"@id\": \"affirm:amount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"amountRefunded\": {\n      \"@id\": \"affirm:amount_refunded\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"currency\": {\n      \"@id\": \"affirm:currency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"created\"\
  : {\n      \"@id\": \"affirm:created\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"authorizationExpiration\": {\n      \"@id\": \"affirm:authorization_expiration\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"Card\": \"affirm:Card\",\n    \"number\": {\n      \"@id\": \"affirm:number\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cvv\": {\n      \"@id\": \"affirm:cvv\",\n      \"@type\": \"xsd:string\"\n    },\n    \"expiration\": {\n      \"@id\": \"affirm:expiration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"billing\": {\n      \"@id\": \"affirm:billing\",\n      \"@type\": \"@id\"\n    },\n    \"address\": {\n      \"@id\": \"affirm:address\",\n      \"@type\": \"@id\"\n    },\n    \"line1\": {\n      \"@id\": \"affirm:line1\",\n      \"@type\": \"xsd:string\"\n    },\n    \"city\": {\n      \"@id\": \"affirm:city\",\n      \"@type\": \"xsd:string\"\n    },\n    \"state\": {\n      \"@id\": \"affirm:state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"zipcode\"\
  : {\n      \"@id\": \"affirm:zipcode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"country\": {\n      \"@id\": \"affirm:country\",\n      \"@type\": \"xsd:string\"\n    },\n    \"FileObject\": \"affirm:FileObject\",\n    \"filename\": {\n      \"@id\": \"affirm:filename\",\n      \"@type\": \"xsd:string\"\n    },\n    \"size\": {\n      \"@id\": \"affirm:size\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"contentType\": {\n      \"@id\": \"affirm:content_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"purpose\": {\n      \"@id\": \"affirm:purpose\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/affirm/refs/heads/main/json-ld/affirm-direct-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
