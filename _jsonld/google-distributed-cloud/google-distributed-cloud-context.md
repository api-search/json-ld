---
api_specs:
- filename: distributed-cloud-edge-network-api-openapi.yml
  format: yaml
  label: Distributed Cloud Edge Network API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-distributed-cloud/refs/heads/main/openapi/distributed-cloud-edge-network-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/google-distributed-cloud-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-distributed-cloud/refs/heads/main/json-ld/google-distributed-cloud-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Google Distributed Cloud from Google Distributed Cloud.
layout: jsonld
name: Google Distributed Cloud Context
namespaces:
- prefix: gdc
  uri: https://cloud.google.com/distributed-cloud/ns/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Network
  type: ''
- container: ''
  name: Subnet
  type: ''
- container: ''
  name: Router
  type: ''
- container: ''
  name: Zone
  type: ''
property_count: 4
provider_name: Google Distributed Cloud
provider_slug: google-distributed-cloud
slug: google-distributed-cloud-context
source_filename: google-distributed-cloud-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"gdc\": \"https://cloud.google.com/distributed-cloud/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Network\": {\n      \"@id\": \"gdc:Network\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"mtu\": \"gdc:mtu\",\n        \"labels\": \"gdc:labels\",\n        \"createTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updateTime\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Subnet\": {\n      \"@id\": \"gdc:Subnet\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"network\": {\n          \"@id\": \"gdc:network\",\n          \"@type\": \"\
  @id\"\n        },\n        \"ipv4Cidr\": \"gdc:ipv4Cidr\",\n        \"ipv6Cidr\": \"gdc:ipv6Cidr\",\n        \"vlanId\": \"gdc:vlanId\",\n        \"createTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Router\": {\n      \"@id\": \"gdc:Router\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"network\": {\n          \"@id\": \"gdc:network\",\n          \"@type\": \"@id\"\n        },\n        \"bgpPeers\": \"gdc:bgpPeers\",\n        \"createTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Zone\": {\n      \"@id\": \"gdc:Zone\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"displayName\": \"schema:alternateName\",\n        \"location\": \"schema:location\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-distributed-cloud/refs/heads/main/json-ld/google-distributed-cloud-context.jsonld
tags:
- Distributed Infrastructure
- Edge Computing
- Hardware
- Hybrid Cloud
- Kubernetes
- On-Premises
- JSON-LD
- Linked Data
- Semantic Web
---
