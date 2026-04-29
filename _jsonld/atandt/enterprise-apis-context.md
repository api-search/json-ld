---
class_count: 0
classes: []
context_file: json-ld/enterprise-apis-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/atandt/refs/heads/main/json-ld/enterprise-apis-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Enterprise Apis from AT&T.
layout: jsonld
name: Enterprise Apis Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: address
  uri: https://api.att.com/vocab/address
- prefix: qualificationId
  uri: https://api.att.com/vocab/qualificationId
- prefix: qualificationDate
  uri: https://api.att.com/vocab/qualificationDate
- prefix: serviceQualificationItems
  uri: https://api.att.com/vocab/serviceQualificationItems
- prefix: externalId
  uri: https://api.att.com/vocab/externalId
- prefix: description
  uri: https://api.att.com/vocab/description
- prefix: requestedStartDate
  uri: https://api.att.com/vocab/requestedStartDate
- prefix: orderItem
  uri: https://api.att.com/vocab/orderItem
- prefix: id
  uri: https://api.att.com/vocab/id
- prefix: state
  uri: https://api.att.com/vocab/state
- prefix: completionDate
  uri: https://api.att.com/vocab/completionDate
properties:
- container: ''
  name: orderDate
  type: dateTime
property_count: 1
provider_name: AT&T
provider_slug: atandt
slug: enterprise-apis-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"@vocab\": \"https://api.att.com/vocab/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"address\": \"https://api.att.com/vocab/address\",\n    \"qualificationId\": \"https://api.att.com/vocab/qualificationId\",\n    \"qualificationDate\": \"https://api.att.com/vocab/qualificationDate\",\n    \"serviceQualificationItems\": \"https://api.att.com/vocab/serviceQualificationItems\",\n    \"externalId\": \"https://api.att.com/vocab/externalId\",\n    \"description\": \"https://api.att.com/vocab/description\",\n    \"requestedStartDate\": \"https://api.att.com/vocab/requestedStartDate\",\n    \"orderItem\": \"https://api.att.com/vocab/orderItem\",\n    \"id\": \"https://api.att.com/vocab/id\",\n    \"state\": \"https://api.att.com/vocab/state\",\n    \"orderDate\": {\n      \"@id\": \"https://api.att.com/vocab/orderDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"completionDate\": \"https://api.att.com/vocab/completionDate\"\
  \n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/atandt/refs/heads/main/json-ld/enterprise-apis-context.jsonld
tags:
- Telecommunications
- Fortune 100
- Wireless
- Wireline
- Broadband
- Enterprise
- 5G
- Network
- JSON-LD
- Linked Data
- Semantic Web
---
