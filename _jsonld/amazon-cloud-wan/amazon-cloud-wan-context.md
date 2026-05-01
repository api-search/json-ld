---
class_count: 7
classes:
- CoreNetwork
- description
- ListCoreNetworksResponse
- CreateCoreNetworkRequest
- CreateCoreNetworkResponse
- GetCoreNetworkResponse
- DeleteCoreNetworkResponse
context_file: json-ld/amazon-cloud-wan-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-cloud-wan/refs/heads/main/json-ld/amazon-cloud-wan-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Cloud Wan from Amazon Cloud WAN.
layout: jsonld
name: Amazon Cloud Wan Context
namespaces:
- prefix: cloudwan
  uri: https://aws.amazon.com/cloud-wan/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: coreNetworkId
  type: string
- container: ''
  name: coreNetworkArn
  type: string
- container: ''
  name: globalNetworkId
  type: string
- container: ''
  name: state
  type: string
- container: ''
  name: createdAt
  type: dateTime
- container: set
  name: coreNetworks
  type: ''
- container: ''
  name: nextToken
  type: string
- container: set
  name: tags
  type: ''
- container: ''
  name: coreNetwork
  type: string
property_count: 9
provider_name: Amazon Cloud WAN
provider_slug: amazon-cloud-wan
slug: amazon-cloud-wan-context
source_filename: amazon-cloud-wan-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"cloudwan\": \"https://aws.amazon.com/cloud-wan/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"CoreNetwork\": \"cloudwan:CoreNetwork\",\n    \"coreNetworkId\": {\n      \"@id\": \"cloudwan:core_network_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"coreNetworkArn\": {\n      \"@id\": \"cloudwan:core_network_arn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"globalNetworkId\": {\n      \"@id\": \"cloudwan:global_network_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\",\n    \"state\": {\n      \"@id\": \"cloudwan:state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdAt\": {\n      \"@id\": \"cloudwan:created_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"ListCoreNetworksResponse\": \"cloudwan:ListCoreNetworksResponse\",\n    \"coreNetworks\"\
  : {\n      \"@id\": \"cloudwan:core_networks\",\n      \"@container\": \"@set\"\n    },\n    \"nextToken\": {\n      \"@id\": \"cloudwan:next_token\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreateCoreNetworkRequest\": \"cloudwan:CreateCoreNetworkRequest\",\n    \"tags\": {\n      \"@id\": \"cloudwan:tags\",\n      \"@container\": \"@set\"\n    },\n    \"CreateCoreNetworkResponse\": \"cloudwan:CreateCoreNetworkResponse\",\n    \"coreNetwork\": {\n      \"@id\": \"cloudwan:core_network\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetCoreNetworkResponse\": \"cloudwan:GetCoreNetworkResponse\",\n    \"DeleteCoreNetworkResponse\": \"cloudwan:DeleteCoreNetworkResponse\"\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-cloud-wan/refs/heads/main/json-ld/amazon-cloud-wan-context.jsonld
tags:
- Cloud WAN
- Networking
- Wide Area Network
- SD-WAN
- JSON-LD
- Linked Data
- Semantic Web
---
