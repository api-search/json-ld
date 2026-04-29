---
class_count: 8
classes:
- VerificationResponse
- Session
- createdAt
- VerificationRequest
- email
- SessionList
- WebhookConfig
- url
context_file: json-ld/agechecker-net-age-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/agechecker-net/refs/heads/main/json-ld/agechecker-net-age-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Agechecker Net Age from AgeChecker.Net.
layout: jsonld
name: Agechecker Net Age Context
namespaces:
- prefix: agechecker-net
  uri: https://agechecker-net.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: result
  type: string
- container: ''
  name: sessionId
  type: string
- container: ''
  name: requiresPhotoId
  type: boolean
- container: ''
  name: ageVerified
  type: boolean
- container: ''
  name: minimumAge
  type: integer
- container: ''
  name: redirectUrl
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: completedAt
  type: dateTime
- container: ''
  name: firstName
  type: string
- container: ''
  name: lastName
  type: string
- container: ''
  name: birthDate
  type: date
- container: ''
  name: address
  type: string
- container: ''
  name: city
  type: string
- container: ''
  name: state
  type: string
- container: ''
  name: zip
  type: string
- container: ''
  name: country
  type: string
- container: ''
  name: phone
  type: string
- container: ''
  name: ipAddress
  type: string
- container: set
  name: sessions
  type: string
- container: ''
  name: total
  type: integer
- container: ''
  name: limit
  type: integer
- container: ''
  name: offset
  type: integer
- container: ''
  name: id
  type: string
- container: set
  name: events
  type: string
- container: ''
  name: secret
  type: string
property_count: 25
provider_name: AgeChecker.Net
provider_slug: agechecker-net
slug: agechecker-net-age-context
source_filename: agechecker-net-age-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"agechecker-net\": \"https://agechecker-net.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"VerificationResponse\": \"agechecker-net:VerificationResponse\",\n    \"result\": {\n      \"@id\": \"agechecker-net:result\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sessionId\": {\n      \"@id\": \"agechecker-net:session_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"requiresPhotoId\": {\n      \"@id\": \"agechecker-net:requires_photo_id\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"ageVerified\": {\n      \"@id\": \"agechecker-net:age_verified\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"minimumAge\": {\n      \"@id\": \"agechecker-net:minimum_age\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"redirectUrl\": {\n      \"@id\": \"agechecker-net:redirect_url\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"Session\": \"agechecker-net:Session\",\n    \"status\": {\n      \"@id\": \"agechecker-net:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdAt\": \"schema:dateCreated\",\n    \"completedAt\": {\n      \"@id\": \"agechecker-net:completed_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"VerificationRequest\": \"agechecker-net:VerificationRequest\",\n    \"firstName\": {\n      \"@id\": \"agechecker-net:first_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastName\": {\n      \"@id\": \"agechecker-net:last_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"birthDate\": {\n      \"@id\": \"agechecker-net:birth_date\",\n      \"@type\": \"xsd:date\"\n    },\n    \"address\": {\n      \"@id\": \"agechecker-net:address\",\n      \"@type\": \"xsd:string\"\n    },\n    \"city\": {\n      \"@id\": \"agechecker-net:city\",\n      \"@type\": \"xsd:string\"\n    },\n    \"state\": {\n      \"@id\": \"agechecker-net:state\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"zip\": {\n      \"@id\": \"agechecker-net:zip\",\n      \"@type\": \"xsd:string\"\n    },\n    \"country\": {\n      \"@id\": \"agechecker-net:country\",\n      \"@type\": \"xsd:string\"\n    },\n    \"email\": \"schema:email\",\n    \"phone\": {\n      \"@id\": \"agechecker-net:phone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ipAddress\": {\n      \"@id\": \"agechecker-net:ip_address\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SessionList\": \"agechecker-net:SessionList\",\n    \"sessions\": {\n      \"@id\": \"agechecker-net:sessions\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"total\": {\n      \"@id\": \"agechecker-net:total\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"limit\": {\n      \"@id\": \"agechecker-net:limit\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"offset\": {\n      \"@id\": \"agechecker-net:offset\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"WebhookConfig\": \"agechecker-net:WebhookConfig\"\
  ,\n    \"id\": {\n      \"@id\": \"agechecker-net:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"url\": \"schema:url\",\n    \"events\": {\n      \"@id\": \"agechecker-net:events\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"secret\": {\n      \"@id\": \"agechecker-net:secret\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/agechecker-net/refs/heads/main/json-ld/agechecker-net-age-context.jsonld
tags:
- Age Verification
- Identity
- Compliance
- Regulatory
- E-Commerce
- JSON-LD
- Linked Data
- Semantic Web
---
