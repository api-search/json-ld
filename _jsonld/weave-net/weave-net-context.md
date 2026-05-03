---
api_specs:
- filename: weave-net-openapi.yml
  format: yaml
  label: Weave Net HTTP API
  slug: weave-net-http-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/weave-net/refs/heads/main/openapi/weave-net-openapi.yml
class_count: 8
classes:
- ConnectRequest
- ConnectionInfo
- DNSStatus
- IPAMStatus
- PeerInfo
- RouterStatus
- StatusResponse
- name
context_file: json-ld/weave-net-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/weave-net/refs/heads/main/json-ld/weave-net-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Weave Net from Weave Net.
layout: jsonld
name: Weave Net Context
namespaces:
- prefix: wn
  uri: https://github.com/weaveworks/weave/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: peer
  type: string
- container: ''
  name: replace
  type: string
- container: ''
  name: address
  type: string
- container: ''
  name: state
  type: string
- container: ''
  name: info
  type: string
- container: ''
  name: domain
  type: string
- container: set
  name: upstream
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: subnet
  type: string
- container: ''
  name: rangeNumIps
  type: integer
- container: ''
  name: ownedNumIps
  type: integer
- container: ''
  name: nickName
  type: string
- container: set
  name: connections
  type: string
- container: ''
  name: encryption
  type: boolean
- container: set
  name: peers
  type: string
- container: ''
  name: version
  type: string
- container: ''
  name: router
  type: string
- container: ''
  name: ipam
  type: string
- container: ''
  name: dns
  type: string
property_count: 19
provider_name: Weave Net
provider_slug: weave-net
slug: weave-net-context
source_filename: weave-net-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"wn\": \"https://github.com/weaveworks/weave/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ConnectRequest\": \"wn:ConnectRequest\",\n    \"ConnectionInfo\": \"wn:ConnectionInfo\",\n    \"DNSStatus\": \"wn:DNSStatus\",\n    \"IPAMStatus\": \"wn:IPAMStatus\",\n    \"PeerInfo\": \"wn:PeerInfo\",\n    \"RouterStatus\": \"wn:RouterStatus\",\n    \"StatusResponse\": \"wn:StatusResponse\",\n    \"peer\": {\n      \"@id\": \"wn:peer\",\n      \"@type\": \"xsd:string\"\n    },\n    \"replace\": {\n      \"@id\": \"wn:replace\",\n      \"@type\": \"xsd:string\"\n    },\n    \"address\": {\n      \"@id\": \"wn:address\",\n      \"@type\": \"xsd:string\"\n    },\n    \"state\": {\n      \"@id\": \"wn:state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"info\": {\n      \"@id\": \"wn:info\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"domain\": {\n      \"@id\": \"wn:domain\",\n      \"@type\": \"xsd:string\"\n    },\n    \"upstream\": {\n      \"@id\": \"wn:upstream\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"wn:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subnet\": {\n      \"@id\": \"wn:subnet\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rangeNumIps\": {\n      \"@id\": \"wn:range_num_ips\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"ownedNumIps\": {\n      \"@id\": \"wn:owned_num_ips\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"name\": \"schema:name\",\n    \"nickName\": {\n      \"@id\": \"wn:nick_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"connections\": {\n      \"@id\": \"wn:connections\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"encryption\": {\n      \"@id\": \"wn:encryption\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"peers\": {\n\
  \      \"@id\": \"wn:peers\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"version\": {\n      \"@id\": \"wn:version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"router\": {\n      \"@id\": \"wn:router\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ipam\": {\n      \"@id\": \"wn:ipam\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dns\": {\n      \"@id\": \"wn:dns\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/weave-net/refs/heads/main/json-ld/weave-net-context.jsonld
tags:
- Containers
- Networking
- Kubernetes
- Docker
- IPAM
- Open Source
- CNCF
- JSON-LD
- Linked Data
- Semantic Web
---
