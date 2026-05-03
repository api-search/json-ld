---
api_specs:
- filename: quicknode-ipfs-openapi.yml
  format: yaml
  label: QuickNode IPFS API
  slug: ipfs
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/quicknode/refs/heads/main/openapi/quicknode-ipfs-openapi.yml
- filename: quicknode-streams-openapi.yml
  format: yaml
  label: QuickNode Streams API
  slug: streams
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/quicknode/refs/heads/main/openapi/quicknode-streams-openapi.yml
- filename: quicknode-key-value-store-openapi.yml
  format: yaml
  label: QuickNode Key-Value Store API
  slug: key-value-store
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/quicknode/refs/heads/main/openapi/quicknode-key-value-store-openapi.yml
class_count: 5
classes:
- name
- description
- url
- provider
- category
context_file: json-ld/quicknode-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/quicknode/refs/heads/main/json-ld/quicknode-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Quicknode from QuickNode.
layout: jsonld
name: Quicknode Context
namespaces: []
properties:
- container: ''
  name: documentation
  type: reference
- container: ''
  name: termsOfService
  type: reference
property_count: 2
provider_name: QuickNode
provider_slug: quicknode
slug: quicknode-context
source_filename: quicknode-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"name\": \"name\",\n    \"description\": \"description\",\n    \"url\": \"url\",\n    \"provider\": \"provider\",\n    \"category\": \"category\",\n    \"documentation\": {\n      \"@id\": \"https://schema.org/documentation\",\n      \"@type\": \"@id\"\n    },\n    \"termsOfService\": {\n      \"@id\": \"https://schema.org/termsOfService\",\n      \"@type\": \"@id\"\n    }\n  },\n  \"@type\": \"WebAPI\",\n  \"name\": \"QuickNode Blockchain Infrastructure APIs\",\n  \"description\": \"QuickNode is a blockchain infrastructure platform that exposes RPC, REST, and gRPC APIs across 77+ blockchains, plus services for IPFS pinning, key-value storage, real-time streams, and webhooks.\",\n  \"url\": \"https://api.quicknode.com\",\n  \"documentation\": \"https://www.quicknode.com/docs/welcome\",\n  \"termsOfService\": \"https://www.quicknode.com/terms-of-service\",\n  \"provider\": {\n    \"@type\": \"Organization\"\
  ,\n    \"name\": \"QuickNode\",\n    \"url\": \"https://www.quicknode.com/\"\n  },\n  \"category\": [\n    \"Blockchain\",\n    \"Web3\",\n    \"Infrastructure\",\n    \"RPC\",\n    \"IPFS\",\n    \"Streaming Data\"\n  ],\n  \"audience\": {\n    \"@type\": \"Audience\",\n    \"audienceType\": \"Web3 Developers, dApp Builders, Indexers\"\n  },\n  \"potentialAction\": [\n    {\n      \"@type\": \"ConsumeAction\",\n      \"name\": \"Pin to IPFS\",\n      \"target\": \"https://api.quicknode.com/ipfs/rest/v1/pinning\"\n    },\n    {\n      \"@type\": \"ConsumeAction\",\n      \"name\": \"Read Key from Key-Value Store\",\n      \"target\": \"https://api.quicknode.com/kv/rest/v1/databases/{database}/keys/{key}\"\n    },\n    {\n      \"@type\": \"ConsumeAction\",\n      \"name\": \"List Streams\",\n      \"target\": \"https://api.quicknode.com/streams/rest/v1/streams\"\n    }\n  ]\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/quicknode/refs/heads/main/json-ld/quicknode-context.jsonld
tags:
- Blockchain
- Web3
- Infrastructure
- RPC
- IPFS
- Streaming Data
- Webhooks
- Key-Value Store
- JSON-LD
- Linked Data
- Semantic Web
---
