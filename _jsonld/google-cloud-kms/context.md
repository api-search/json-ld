---
api_specs:
- filename: openapi.yml
  format: yaml
  label: Google Cloud KMS API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-cloud-kms/refs/heads/main/openapi/openapi.yml
class_count: 3
classes:
- KeyRing
- CryptoKey
- CryptoKeyVersion
context_file: json-ld/context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-cloud-kms/refs/heads/main/json-ld/context.jsonld
description: JSON-LD context defining the semantic vocabulary for context from Google Cloud KMS.
layout: jsonld
name: context Context
namespaces:
- prefix: gcloud
  uri: https://cloud.google.com/kms/docs/reference/rest/v1/
- prefix: name
  uri: https://schema.org/name
- prefix: description
  uri: https://schema.org/description
- prefix: createTime
  uri: https://schema.org/dateCreated
- prefix: purpose
  uri: https://schema.org/purpose
- prefix: state
  uri: https://schema.org/status
- prefix: algorithm
  uri: https://schema.org/algorithm
- prefix: protectionLevel
  uri: https://schema.org/securityClearance
- prefix: labels
  uri: https://schema.org/keywords
- prefix: nextRotationTime
  uri: https://schema.org/scheduledTime
- prefix: rotationPeriod
  uri: https://schema.org/repeatFrequency
properties: []
property_count: 0
provider_name: Google Cloud KMS
provider_slug: google-cloud-kms
slug: context
source_filename: context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"gcloud\": \"https://cloud.google.com/kms/docs/reference/rest/v1/\",\n    \"KeyRing\": \"gcloud:projects.locations.keyRings\",\n    \"CryptoKey\": \"gcloud:projects.locations.keyRings.cryptoKeys\",\n    \"CryptoKeyVersion\": \"gcloud:projects.locations.keyRings.cryptoKeys.cryptoKeyVersions\",\n    \"name\": \"https://schema.org/name\",\n    \"description\": \"https://schema.org/description\",\n    \"createTime\": \"https://schema.org/dateCreated\",\n    \"purpose\": \"https://schema.org/purpose\",\n    \"state\": \"https://schema.org/status\",\n    \"algorithm\": \"https://schema.org/algorithm\",\n    \"protectionLevel\": \"https://schema.org/securityClearance\",\n    \"labels\": \"https://schema.org/keywords\",\n    \"nextRotationTime\": \"https://schema.org/scheduledTime\",\n    \"rotationPeriod\": \"https://schema.org/repeatFrequency\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-cloud-kms/refs/heads/main/json-ld/context.jsonld
tags:
- Cryptography
- Encryption
- Google Cloud
- Key Management
- KMS
- Security
- JSON-LD
- Linked Data
- Semantic Web
---
