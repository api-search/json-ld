---
api_specs:
- filename: completedns-v2-openapi.yml
  format: yaml
  label: CompleteDNS API v2
  slug: dns-history-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/completedns/refs/heads/main/openapi/completedns-v2-openapi.yml
- filename: completedns-v1-openapi.yml
  format: yaml
  label: CompleteDNS API v1
  slug: ns-history-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/completedns/refs/heads/main/openapi/completedns-v1-openapi.yml
class_count: 0
classes: []
context_file: json-ld/completedns-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/completedns/refs/heads/main/json-ld/completedns-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Completedns from CompleteDNS.
layout: jsonld
name: Completedns Context
namespaces:
- prefix: completedns
  uri: https://api.completedns.com/v2/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: DnsHistory
  type: ''
- container: ''
  name: DnsEvent
  type: ''
- container: ''
  name: NameserverChange
  type: ''
property_count: 3
provider_name: CompleteDNS
provider_slug: completedns
slug: completedns-context
source_filename: completedns-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"completedns\": \"https://api.completedns.com/v2/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"DnsHistory\": {\n      \"@id\": \"completedns:DnsHistory\",\n      \"@context\": {\n        \"domain\": \"schema:name\",\n        \"drops\": {\n          \"@id\": \"completedns:drops\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"changes\": {\n          \"@id\": \"completedns:changes\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"years\": {\n          \"@id\": \"completedns:years\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"wasParked\": {\n          \"@id\": \"completedns:was_parked\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"events\": {\n          \"@id\": \"completedns:events\",\n          \"@container\": \"@list\"\n        }\n      }\n    },\n\n \
  \   \"DnsEvent\": {\n      \"@id\": \"completedns:DnsEvent\",\n      \"@context\": {\n        \"date\": {\n          \"@id\": \"dcterms:date\",\n          \"@type\": \"xsd:date\"\n        },\n        \"type\": \"completedns:eventType\",\n        \"nameservers\": {\n          \"@id\": \"completedns:nameservers\",\n          \"@container\": \"@set\"\n        },\n        \"changes\": {\n          \"@id\": \"completedns:changeSet\",\n          \"@container\": \"@list\"\n        }\n      }\n    },\n\n    \"NameserverChange\": {\n      \"@id\": \"completedns:NameserverChange\",\n      \"@context\": {\n        \"action\": \"completedns:action\",\n        \"nameserver\": \"completedns:nameserver\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/completedns/refs/heads/main/json-ld/completedns-context.jsonld
tags:
- DNS
- DNS History
- Domain Intelligence
- Domains
- Nameservers
- Threat Intelligence
- JSON-LD
- Linked Data
- Semantic Web
---
