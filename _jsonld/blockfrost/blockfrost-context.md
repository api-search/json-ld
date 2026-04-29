---
api_specs:
- filename: blockfrost-openapi.yaml
  format: yaml
  label: Blockfrost API
  slug: blockfrost
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/blockfrost/refs/heads/main/openapi/blockfrost-openapi.yaml
class_count: 22
classes:
- hash
- url
- block_content_addresses
- block_content_array
- block_content
- block_content_txs_cbor
- block_content_txs
- drep_delegators
- drep_metadata
- drep
- drep_updates
- drep_votes
- dreps
- genesis_content
- onchain_metadata_cip25
- onchain_metadata_cip68_ft_333
- onchain_metadata_cip68_nft_222
- onchain_metadata_cip68_rft_444
- proposal_parameters
- proposal
- proposal_withdrawals
- proposals
context_file: json-ld/blockfrost-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/blockfrost/refs/heads/main/json-ld/blockfrost-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Blockfrost from Blockfrost.
layout: jsonld
name: Blockfrost Context
namespaces:
- prefix: blockfrost
  uri: https://blockfrost.io/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: time
  type: integer
- container: ''
  name: height
  type: integer
- container: ''
  name: slot
  type: integer
- container: ''
  name: epoch
  type: integer
- container: ''
  name: epoch_slot
  type: integer
- container: ''
  name: slot_leader
  type: string
- container: ''
  name: size
  type: integer
- container: ''
  name: tx_count
  type: integer
- container: ''
  name: output
  type: string
- container: ''
  name: fees
  type: string
- container: ''
  name: block_vrf
  type: string
- container: ''
  name: op_cert
  type: string
- container: ''
  name: op_cert_counter
  type: string
- container: ''
  name: previous_block
  type: string
- container: ''
  name: next_block
  type: string
- container: ''
  name: confirmations
  type: integer
- container: ''
  name: drep_id
  type: string
- container: ''
  name: hex
  type: string
- container: ''
  name: json_metadata
  type: string
- container: ''
  name: bytes
  type: string
- container: ''
  name: error
  type: string
- container: ''
  name: amount
  type: string
- container: ''
  name: active
  type: boolean
- container: ''
  name: active_epoch
  type: integer
- container: ''
  name: has_script
  type: boolean
- container: ''
  name: retired
  type: boolean
- container: ''
  name: expired
  type: boolean
- container: ''
  name: last_active_epoch
  type: integer
- container: ''
  name: active_slots_coefficient
  type: decimal
- container: ''
  name: update_quorum
  type: integer
- container: ''
  name: max_lovelace_supply
  type: string
- container: ''
  name: network_magic
  type: integer
- container: ''
  name: epoch_length
  type: integer
- container: ''
  name: system_start
  type: integer
- container: ''
  name: slots_per_kes_period
  type: integer
- container: ''
  name: slot_length
  type: integer
- container: ''
  name: max_kes_evolutions
  type: integer
- container: ''
  name: security_param
  type: integer
- container: ''
  name: id
  type: string
- container: ''
  name: tx_hash
  type: string
- container: ''
  name: cert_index
  type: integer
- container: ''
  name: parameters
  type: string
- container: ''
  name: governance_type
  type: string
- container: ''
  name: governance_description
  type: string
- container: ''
  name: deposit
  type: string
- container: ''
  name: return_address
  type: string
- container: ''
  name: ratified_epoch
  type: integer
- container: ''
  name: enacted_epoch
  type: integer
- container: ''
  name: dropped_epoch
  type: integer
- container: ''
  name: expired_epoch
  type: integer
- container: ''
  name: expiration
  type: integer
property_count: 51
provider_name: Blockfrost
provider_slug: blockfrost
slug: blockfrost-context
source_filename: blockfrost-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"blockfrost\": \"https://blockfrost.io/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"time\": {\n      \"@id\": \"blockfrost:time\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"height\": {\n      \"@id\": \"blockfrost:height\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"hash\": \"dcterms:identifier\",\n    \"slot\": {\n      \"@id\": \"blockfrost:slot\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"epoch\": {\n      \"@id\": \"blockfrost:epoch\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"epoch_slot\": {\n      \"@id\": \"blockfrost:epoch_slot\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"slot_leader\": {\n      \"@id\": \"blockfrost:slot_leader\",\n      \"@type\": \"xsd:string\"\n    },\n    \"size\": {\n      \"@id\": \"blockfrost:size\",\n      \"@type\": \"xsd:integer\"\n    },\n\
  \    \"tx_count\": {\n      \"@id\": \"blockfrost:tx_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"output\": {\n      \"@id\": \"blockfrost:output\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fees\": {\n      \"@id\": \"blockfrost:fees\",\n      \"@type\": \"xsd:string\"\n    },\n    \"block_vrf\": {\n      \"@id\": \"blockfrost:block_vrf\",\n      \"@type\": \"xsd:string\"\n    },\n    \"op_cert\": {\n      \"@id\": \"blockfrost:op_cert\",\n      \"@type\": \"xsd:string\"\n    },\n    \"op_cert_counter\": {\n      \"@id\": \"blockfrost:op_cert_counter\",\n      \"@type\": \"xsd:string\"\n    },\n    \"previous_block\": {\n      \"@id\": \"blockfrost:previous_block\",\n      \"@type\": \"xsd:string\"\n    },\n    \"next_block\": {\n      \"@id\": \"blockfrost:next_block\",\n      \"@type\": \"xsd:string\"\n    },\n    \"confirmations\": {\n      \"@id\": \"blockfrost:confirmations\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"drep_id\": {\n      \"@id\": \"blockfrost:drep_id\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"hex\": {\n      \"@id\": \"blockfrost:hex\",\n      \"@type\": \"xsd:string\"\n    },\n    \"url\": \"schema:url\",\n    \"json_metadata\": {\n      \"@id\": \"blockfrost:json_metadata\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bytes\": {\n      \"@id\": \"blockfrost:bytes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"error\": {\n      \"@id\": \"blockfrost:error\",\n      \"@type\": \"xsd:string\"\n    },\n    \"amount\": {\n      \"@id\": \"blockfrost:amount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"active\": {\n      \"@id\": \"blockfrost:active\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"active_epoch\": {\n      \"@id\": \"blockfrost:active_epoch\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"has_script\": {\n      \"@id\": \"blockfrost:has_script\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"retired\": {\n      \"@id\": \"blockfrost:retired\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"\
  expired\": {\n      \"@id\": \"blockfrost:expired\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"last_active_epoch\": {\n      \"@id\": \"blockfrost:last_active_epoch\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"active_slots_coefficient\": {\n      \"@id\": \"blockfrost:active_slots_coefficient\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"update_quorum\": {\n      \"@id\": \"blockfrost:update_quorum\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"max_lovelace_supply\": {\n      \"@id\": \"blockfrost:max_lovelace_supply\",\n      \"@type\": \"xsd:string\"\n    },\n    \"network_magic\": {\n      \"@id\": \"blockfrost:network_magic\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"epoch_length\": {\n      \"@id\": \"blockfrost:epoch_length\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"system_start\": {\n      \"@id\": \"blockfrost:system_start\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"slots_per_kes_period\": {\n      \"@id\": \"blockfrost:slots_per_kes_period\"\
  ,\n      \"@type\": \"xsd:integer\"\n    },\n    \"slot_length\": {\n      \"@id\": \"blockfrost:slot_length\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"max_kes_evolutions\": {\n      \"@id\": \"blockfrost:max_kes_evolutions\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"security_param\": {\n      \"@id\": \"blockfrost:security_param\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"id\": {\n      \"@id\": \"blockfrost:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tx_hash\": {\n      \"@id\": \"blockfrost:tx_hash\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cert_index\": {\n      \"@id\": \"blockfrost:cert_index\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"parameters\": {\n      \"@id\": \"blockfrost:parameters\",\n      \"@type\": \"xsd:string\"\n    },\n    \"governance_type\": {\n      \"@id\": \"blockfrost:governance_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"governance_description\": {\n      \"@id\": \"blockfrost:governance_description\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"deposit\": {\n      \"@id\": \"blockfrost:deposit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"return_address\": {\n      \"@id\": \"blockfrost:return_address\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ratified_epoch\": {\n      \"@id\": \"blockfrost:ratified_epoch\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"enacted_epoch\": {\n      \"@id\": \"blockfrost:enacted_epoch\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"dropped_epoch\": {\n      \"@id\": \"blockfrost:dropped_epoch\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"expired_epoch\": {\n      \"@id\": \"blockfrost:expired_epoch\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"expiration\": {\n      \"@id\": \"blockfrost:expiration\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"block_content_addresses\": \"blockfrost:block_content_addresses\",\n    \"block_content_array\": \"blockfrost:block_content_array\",\n    \"block_content\": \"blockfrost:block_content\"\
  ,\n    \"block_content_txs_cbor\": \"blockfrost:block_content_txs_cbor\",\n    \"block_content_txs\": \"blockfrost:block_content_txs\",\n    \"drep_delegators\": \"blockfrost:drep_delegators\",\n    \"drep_metadata\": \"blockfrost:drep_metadata\",\n    \"drep\": \"blockfrost:drep\",\n    \"drep_updates\": \"blockfrost:drep_updates\",\n    \"drep_votes\": \"blockfrost:drep_votes\",\n    \"dreps\": \"blockfrost:dreps\",\n    \"genesis_content\": \"blockfrost:genesis_content\",\n    \"onchain_metadata_cip25\": \"blockfrost:onchain_metadata_cip25\",\n    \"onchain_metadata_cip68_ft_333\": \"blockfrost:onchain_metadata_cip68_ft_333\",\n    \"onchain_metadata_cip68_nft_222\": \"blockfrost:onchain_metadata_cip68_nft_222\",\n    \"onchain_metadata_cip68_rft_444\": \"blockfrost:onchain_metadata_cip68_rft_444\",\n    \"proposal_parameters\": \"blockfrost:proposal_parameters\",\n    \"proposal\": \"blockfrost:proposal\",\n    \"proposal_withdrawals\": \"blockfrost:proposal_withdrawals\",\n    \"\
  proposals\": \"blockfrost:proposals\"\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/blockfrost/refs/heads/main/json-ld/blockfrost-context.jsonld
tags:
- Blockchain
- Cardano
- Cryptocurrency
- DApps
- NFT
- Web3
- JSON-LD
- Linked Data
- Semantic Web
---
