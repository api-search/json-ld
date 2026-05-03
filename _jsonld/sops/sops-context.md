---
class_count: 4
classes:
- EncryptedFile
- KeyManagementService
- CreationRule
- KeyGroup
context_file: json-ld/sops-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/sops/refs/heads/main/json-ld/sops-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Sops from SOPS.
layout: jsonld
name: Sops Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: sops
  uri: https://getsops.io/vocab/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: version
  type: string
- container: ''
  name: lastmodified
  type: dateTime
- container: ''
  name: mac
  type: string
- container: set
  name: kms
  type: ''
- container: set
  name: gcp_kms
  type: ''
- container: set
  name: azure_kv
  type: ''
- container: set
  name: age
  type: ''
- container: set
  name: pgp
  type: ''
- container: ''
  name: arn
  type: string
- container: ''
  name: fp
  type: string
- container: ''
  name: enc
  type: string
property_count: 11
provider_name: SOPS
provider_slug: sops
slug: sops-context
source_filename: sops-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"sops\": \"https://getsops.io/vocab/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"EncryptedFile\": \"sops:EncryptedFile\",\n    \"KeyManagementService\": \"sops:KeyManagementService\",\n    \"CreationRule\": \"sops:CreationRule\",\n    \"KeyGroup\": \"sops:KeyGroup\",\n\n    \"version\": {\n      \"@id\": \"schema:version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastmodified\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"mac\": {\n      \"@id\": \"sops:messageAuthenticationCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"kms\": {\n      \"@id\": \"sops:awsKmsKey\",\n      \"@container\": \"@set\"\n    },\n    \"gcp_kms\": {\n      \"@id\": \"sops:gcpKmsKey\",\n      \"@container\": \"@set\"\n    },\n    \"azure_kv\": {\n      \"@id\": \"sops:azureKeyVault\",\n      \"@container\": \"@set\"\n    },\n\
  \    \"age\": {\n      \"@id\": \"sops:ageKey\",\n      \"@container\": \"@set\"\n    },\n    \"pgp\": {\n      \"@id\": \"sops:pgpKey\",\n      \"@container\": \"@set\"\n    },\n    \"arn\": {\n      \"@id\": \"sops:keyArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fp\": {\n      \"@id\": \"sops:pgpFingerprint\",\n      \"@type\": \"xsd:string\"\n    },\n    \"enc\": {\n      \"@id\": \"sops:encryptedDataKey\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/sops/refs/heads/main/json-ld/sops-context.jsonld
tags:
- Secrets Management
- Encryption
- Configuration Management
- DevOps
- Security
- Kubernetes
- CNCF
- JSON-LD
- Linked Data
- Semantic Web
---
