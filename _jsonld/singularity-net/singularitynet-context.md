---
api_specs:
- filename: singularitynet-marketplace-openapi.yml
  format: yaml
  label: SingularityNET Daemon API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/singularity-net/refs/heads/main/openapi/singularitynet-marketplace-openapi.yml
class_count: 33
classes:
- Organization
- Service
- ServiceGroup
- PaymentChannel
- Pricing
- org_id
- service_id
- channel_id
- org_name
- display_name
- description
- short_description
- url
- tags
- is_available
- contacts
- email
- metadata_uri
- service_api_source
- groups
- rating
- average_rating
- total_users_rated
- group_id
- group_name
- endpoints
- pricing
- price_model
- price_in_cogs
- balance_in_cogs
- expiration
- signer
- nonce
context_file: json-ld/singularitynet-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/singularity-net/refs/heads/main/json-ld/singularitynet-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Singularitynet from SingularityNET.
layout: jsonld
name: Singularitynet Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: snet
  uri: https://singularitynet.io/vocab#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties: []
property_count: 0
provider_name: SingularityNET
provider_slug: singularity-net
slug: singularitynet-context
source_filename: singularitynet-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"snet\": \"https://singularitynet.io/vocab#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Organization\": \"schema:Organization\",\n    \"Service\": \"schema:SoftwareApplication\",\n    \"ServiceGroup\": \"snet:ServiceGroup\",\n    \"PaymentChannel\": \"snet:PaymentChannel\",\n    \"Pricing\": \"snet:Pricing\",\n\n    \"org_id\": \"@id\",\n    \"service_id\": \"@id\",\n    \"channel_id\": \"@id\",\n\n    \"org_name\": \"schema:name\",\n    \"display_name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"short_description\": \"schema:abstract\",\n    \"url\": \"schema:url\",\n    \"tags\": \"schema:keywords\",\n    \"is_available\": \"schema:isAvailable\",\n\n    \"contacts\": \"schema:contactPoint\",\n    \"email\": \"schema:email\",\n    \"metadata_uri\": \"snet:metadataUri\",\n    \"service_api_source\": \"snet:apiSource\",\n    \"groups\"\
  : \"snet:serviceGroups\",\n    \"rating\": \"schema:aggregateRating\",\n    \"average_rating\": \"schema:ratingValue\",\n    \"total_users_rated\": \"schema:ratingCount\",\n\n    \"group_id\": \"@id\",\n    \"group_name\": \"schema:name\",\n    \"endpoints\": \"snet:endpoints\",\n    \"pricing\": \"snet:pricing\",\n    \"price_model\": \"snet:priceModel\",\n    \"price_in_cogs\": \"snet:priceInCogs\",\n\n    \"balance_in_cogs\": \"snet:balanceInCogs\",\n    \"expiration\": \"snet:expirationBlock\",\n    \"signer\": \"snet:signerAddress\",\n    \"nonce\": \"snet:channelNonce\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/singularity-net/refs/heads/main/json-ld/singularitynet-context.jsonld
tags:
- Artificial Intelligence
- Blockchain
- Decentralized AI
- AI Marketplace
- Web3
- JSON-LD
- Linked Data
- Semantic Web
---
