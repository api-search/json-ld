---
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
