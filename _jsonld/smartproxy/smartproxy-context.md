---
api_specs:
- filename: smartproxy-openapi.yml
  format: yaml
  label: Smartproxy Account Management API
  slug: proxy-management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/smartproxy/refs/heads/main/openapi/smartproxy-openapi.yml
class_count: 11
classes:
- name
- description
- ProxyAccount
- SubUser
- username
- ProxyEndpoint
- host
- protocol
- location
- Subscription
- WhitelistedIp
context_file: json-ld/smartproxy-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/smartproxy/refs/heads/main/json-ld/smartproxy-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Smartproxy from Smartproxy.
layout: jsonld
name: Smartproxy Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: smartproxy
  uri: https://api-evangelist.github.io/smartproxy/vocab#
properties:
- container: ''
  name: url
  type: reference
- container: ''
  name: created
  type: dateTime
- container: ''
  name: status
  type: string
- container: ''
  name: serviceType
  type: string
- container: ''
  name: port
  type: integer
- container: ''
  name: trafficLimit
  type: schema:QuantitativeValue
- container: ''
  name: trafficUsed
  type: schema:QuantitativeValue
- container: ''
  name: ipAddress
  type: string
property_count: 8
provider_name: Smartproxy
provider_slug: smartproxy
slug: smartproxy-context
source_filename: smartproxy-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"smartproxy\": \"https://api-evangelist.github.io/smartproxy/vocab#\",\n\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    },\n    \"created\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n\n    \"ProxyAccount\": \"schema:Account\",\n    \"SubUser\": \"schema:Person\",\n    \"username\": \"schema:name\",\n    \"status\": {\n      \"@id\": \"smartproxy:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"serviceType\": {\n      \"@id\": \"smartproxy:serviceType\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"ProxyEndpoint\": \"schema:EntryPoint\",\n    \"host\": \"schema:url\",\n    \"port\": {\n      \"@id\": \"schema:portableDevice\",\n      \"@type\": \"xsd:integer\"\n    },\n\
  \    \"protocol\": \"schema:encodingFormat\",\n    \"location\": \"schema:addressCountry\",\n\n    \"Subscription\": \"schema:Offer\",\n    \"trafficLimit\": {\n      \"@id\": \"smartproxy:trafficLimit\",\n      \"@type\": \"schema:QuantitativeValue\"\n    },\n    \"trafficUsed\": {\n      \"@id\": \"smartproxy:trafficUsed\",\n      \"@type\": \"schema:QuantitativeValue\"\n    },\n\n    \"WhitelistedIp\": \"schema:DefinedTerm\",\n    \"ipAddress\": {\n      \"@id\": \"smartproxy:ipAddress\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/smartproxy/refs/heads/main/json-ld/smartproxy-context.jsonld
tags:
- Proxies
- Web Scraping
- Data Collection
- Residential Proxies
- Datacenter Proxies
- Mobile Proxies
- Network Infrastructure
- JSON-LD
- Linked Data
- Semantic Web
---
