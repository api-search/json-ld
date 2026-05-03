---
api_specs:
- filename: tikv-http-api-openapi.yml
  format: yaml
  label: TiKV HTTP Management API
  slug: tikv-http-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tikv/refs/heads/main/openapi/tikv-http-api-openapi.yml
class_count: 14
classes:
- region_id
- start_key
- end_key
- store_id
- region_epoch
- approximate_size
- approximate_keys
- written_bytes
- read_bytes
- git_hash
- TiKVRegion
- TiKVPeer
- TiKVNode
- TiKVCluster
context_file: json-ld/tikv-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/tikv/refs/heads/main/json-ld/tikv-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Tikv from TiKV.
layout: jsonld
name: Tikv Context
namespaces:
- prefix: tikv
  uri: https://tikv.org/vocab/
properties: []
property_count: 0
provider_name: TiKV
provider_slug: tikv
slug: tikv-context
source_filename: tikv-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"tikv\": \"https://tikv.org/vocab/\",\n    \"region_id\": \"tikv:regionId\",\n    \"start_key\": \"tikv:startKey\",\n    \"end_key\": \"tikv:endKey\",\n    \"store_id\": \"tikv:storeId\",\n    \"region_epoch\": \"tikv:regionEpoch\",\n    \"approximate_size\": \"tikv:approximateSize\",\n    \"approximate_keys\": \"tikv:approximateKeys\",\n    \"written_bytes\": \"tikv:writtenBytes\",\n    \"read_bytes\": \"tikv:readBytes\",\n    \"git_hash\": \"tikv:gitHash\",\n    \"TiKVRegion\": \"tikv:Region\",\n    \"TiKVPeer\": \"tikv:Peer\",\n    \"TiKVNode\": \"tikv:Node\",\n    \"TiKVCluster\": \"tikv:Cluster\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/tikv/refs/heads/main/json-ld/tikv-context.jsonld
tags:
- ACID
- CNCF
- Database
- Distributed Systems
- Key-Value Store
- Open Source
- Rust
- JSON-LD
- Linked Data
- Semantic Web
---
