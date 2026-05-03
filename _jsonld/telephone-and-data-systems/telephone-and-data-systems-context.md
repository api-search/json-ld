---
class_count: 3
classes:
- name
- description
- url
context_file: json-ld/telephone-and-data-systems-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/telephone-and-data-systems/refs/heads/main/json-ld/telephone-and-data-systems-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Telephone And Data Systems from Telephone and Data Systems.
layout: jsonld
name: Telephone And Data Systems Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: tds
  uri: https://www.tdsinc.com/vocabulary/
properties:
- container: ''
  name: provider
  type: schema:Organization
- container: ''
  name: TelecomService
  type: ''
- container: ''
  name: BroadbandService
  type: ''
- container: ''
  name: WirelessInfrastructure
  type: ''
- container: ''
  name: Subsidiary
  type: ''
- container: ''
  name: TDSTelecom
  type: schema:Organization
- container: ''
  name: ArrayDigitalInfrastructure
  type: schema:Organization
property_count: 7
provider_name: Telephone and Data Systems
provider_slug: telephone-and-data-systems
slug: telephone-and-data-systems-context
source_filename: telephone-and-data-systems-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"tds\": \"https://www.tdsinc.com/vocabulary/\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"provider\": {\n      \"@id\": \"schema:provider\",\n      \"@type\": \"schema:Organization\"\n    },\n    \"TelecomService\": {\n      \"@id\": \"schema:Service\",\n      \"@context\": {\n        \"serviceType\": \"schema:serviceType\",\n        \"areaServed\": \"schema:areaServed\",\n        \"provider\": \"schema:provider\"\n      }\n    },\n    \"BroadbandService\": {\n      \"@id\": \"tds:BroadbandService\",\n      \"@context\": {\n        \"downloadSpeed\": \"tds:downloadSpeed\",\n        \"uploadSpeed\": \"tds:uploadSpeed\",\n        \"technology\": \"tds:technology\"\n      }\n    },\n    \"WirelessInfrastructure\": {\n      \"@id\": \"tds:WirelessInfrastructure\",\n      \"@context\": {\n        \"towerCount\": \"\
  tds:towerCount\",\n        \"spectrumBands\": \"tds:spectrumBands\",\n        \"coverageArea\": \"schema:areaServed\"\n      }\n    },\n    \"Subsidiary\": {\n      \"@id\": \"schema:Organization\",\n      \"@context\": {\n        \"parentOrganization\": \"schema:parentOrganization\",\n        \"legalName\": \"schema:legalName\"\n      }\n    },\n    \"TDSTelecom\": {\n      \"@id\": \"tds:TDSTelecom\",\n      \"@type\": \"schema:Organization\",\n      \"@context\": {\n        \"statesServed\": \"tds:statesServed\",\n        \"communitiesServed\": \"tds:communitiesServed\"\n      }\n    },\n    \"ArrayDigitalInfrastructure\": {\n      \"@id\": \"tds:ArrayDigitalInfrastructure\",\n      \"@type\": \"schema:Organization\",\n      \"@context\": {\n        \"towersOwned\": \"tds:towersOwned\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/telephone-and-data-systems/refs/heads/main/json-ld/telephone-and-data-systems-context.jsonld
tags:
- Broadband
- Fiber Internet
- Fortune 500
- Rural Connectivity
- Telecommunications
- Wireless Infrastructure
- JSON-LD
- Linked Data
- Semantic Web
---
