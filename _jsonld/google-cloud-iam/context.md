---
api_specs:
- filename: openapi.yml
  format: yaml
  label: Google Cloud IAM API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-cloud-iam/refs/heads/main/openapi/openapi.yml
class_count: 3
classes:
- ServiceAccount
- Role
- ServiceAccountKey
context_file: json-ld/context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-cloud-iam/refs/heads/main/json-ld/context.jsonld
description: JSON-LD context defining the semantic vocabulary for context from Google Cloud IAM.
layout: jsonld
name: context Context
namespaces:
- prefix: gcloud
  uri: https://cloud.google.com/iam/docs/reference/rest/v1/
- prefix: name
  uri: https://schema.org/name
- prefix: displayName
  uri: https://schema.org/name
- prefix: description
  uri: https://schema.org/description
- prefix: email
  uri: https://schema.org/email
- prefix: projectId
  uri: https://schema.org/identifier
- prefix: uniqueId
  uri: https://schema.org/identifier
- prefix: disabled
  uri: https://schema.org/terminated
- prefix: title
  uri: https://schema.org/roleName
- prefix: includedPermissions
  uri: https://schema.org/hasDigitalDocumentPermission
- prefix: validAfterTime
  uri: https://schema.org/validFrom
- prefix: validBeforeTime
  uri: https://schema.org/validThrough
properties: []
property_count: 0
provider_name: Google Cloud IAM
provider_slug: google-cloud-iam
slug: context
source_filename: context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"gcloud\": \"https://cloud.google.com/iam/docs/reference/rest/v1/\",\n    \"ServiceAccount\": \"gcloud:projects.serviceAccounts\",\n    \"Role\": \"gcloud:roles\",\n    \"ServiceAccountKey\": \"gcloud:projects.serviceAccounts.keys\",\n    \"name\": \"https://schema.org/name\",\n    \"displayName\": \"https://schema.org/name\",\n    \"description\": \"https://schema.org/description\",\n    \"email\": \"https://schema.org/email\",\n    \"projectId\": \"https://schema.org/identifier\",\n    \"uniqueId\": \"https://schema.org/identifier\",\n    \"disabled\": \"https://schema.org/terminated\",\n    \"title\": \"https://schema.org/roleName\",\n    \"includedPermissions\": \"https://schema.org/hasDigitalDocumentPermission\",\n    \"validAfterTime\": \"https://schema.org/validFrom\",\n    \"validBeforeTime\": \"https://schema.org/validThrough\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-cloud-iam/refs/heads/main/json-ld/context.jsonld
tags:
- Access Management
- Google Cloud
- IAM
- Identity
- Permissions
- Security
- JSON-LD
- Linked Data
- Semantic Web
---
