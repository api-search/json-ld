---
api_specs:
- filename: openapi.yml
  format: yaml
  label: Google Cloud Secret Manager API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-cloud-secret-manager/refs/heads/main/openapi/openapi.yml
class_count: 2
classes:
- Secret
- SecretVersion
context_file: json-ld/context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-cloud-secret-manager/refs/heads/main/json-ld/context.jsonld
description: JSON-LD context defining the semantic vocabulary for context from Google Cloud Secret Manager.
layout: jsonld
name: context Context
namespaces:
- prefix: gcloud
  uri: https://cloud.google.com/secret-manager/docs/reference/rest/v1/
- prefix: name
  uri: https://schema.org/name
- prefix: description
  uri: https://schema.org/description
- prefix: createTime
  uri: https://schema.org/dateCreated
- prefix: expireTime
  uri: https://schema.org/expires
- prefix: labels
  uri: https://schema.org/keywords
- prefix: state
  uri: https://schema.org/status
- prefix: replication
  uri: https://schema.org/distribution
- prefix: rotation
  uri: https://schema.org/repeatFrequency
- prefix: etag
  uri: https://schema.org/version
- prefix: topics
  uri: https://schema.org/about
properties: []
property_count: 0
provider_name: Google Cloud Secret Manager
provider_slug: google-cloud-secret-manager
slug: context
source_filename: context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"gcloud\": \"https://cloud.google.com/secret-manager/docs/reference/rest/v1/\",\n    \"Secret\": \"gcloud:projects.secrets\",\n    \"SecretVersion\": \"gcloud:projects.secrets.versions\",\n    \"name\": \"https://schema.org/name\",\n    \"description\": \"https://schema.org/description\",\n    \"createTime\": \"https://schema.org/dateCreated\",\n    \"expireTime\": \"https://schema.org/expires\",\n    \"labels\": \"https://schema.org/keywords\",\n    \"state\": \"https://schema.org/status\",\n    \"replication\": \"https://schema.org/distribution\",\n    \"rotation\": \"https://schema.org/repeatFrequency\",\n    \"etag\": \"https://schema.org/version\",\n    \"topics\": \"https://schema.org/about\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-cloud-secret-manager/refs/heads/main/json-ld/context.jsonld
tags:
- Configuration
- Credentials
- Google Cloud
- Key Management
- Secrets
- Security
- JSON-LD
- Linked Data
- Semantic Web
---
