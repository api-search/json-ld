---
class_count: 0
classes: []
context_file: json-ld/tuf-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/tuf/refs/heads/main/json-ld/tuf-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Tuf from The Update Framework (TUF).
layout: jsonld
name: Tuf Context
namespaces:
- prefix: tuf
  uri: https://theupdateframework.io/vocabulary#
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: sec
  uri: https://w3id.org/security#
properties:
- container: ''
  name: RootMetadata
  type: ''
- container: ''
  name: TargetsMetadata
  type: ''
- container: ''
  name: SnapshotMetadata
  type: ''
- container: ''
  name: TimestampMetadata
  type: ''
- container: ''
  name: TargetFile
  type: ''
- container: ''
  name: MetaFile
  type: ''
- container: ''
  name: Key
  type: ''
- container: ''
  name: Role
  type: ''
- container: ''
  name: DelegatedRole
  type: ''
- container: ''
  name: Delegations
  type: ''
- container: ''
  name: Signature
  type: ''
- container: ''
  name: Hashes
  type: ''
property_count: 12
provider_name: The Update Framework (TUF)
provider_slug: tuf
slug: tuf-context
source_filename: tuf-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"tuf\": \"https://theupdateframework.io/vocabulary#\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"sec\": \"https://w3id.org/security#\",\n\n    \"RootMetadata\": {\n      \"@id\": \"tuf:RootMetadata\",\n      \"@context\": {\n        \"spec_version\": \"tuf:specVersion\",\n        \"version\": \"tuf:metadataVersion\",\n        \"expires\": {\n          \"@id\": \"dcterms:valid\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"consistent_snapshot\": \"tuf:consistentSnapshot\",\n        \"keys\": \"tuf:trustedKeys\",\n        \"roles\": \"tuf:roleDefinitions\"\n      }\n    },\n\n    \"TargetsMetadata\": {\n      \"@id\": \"tuf:TargetsMetadata\",\n      \"@context\": {\n        \"spec_version\": \"tuf:specVersion\",\n        \"version\": \"tuf:metadataVersion\",\n        \"expires\": {\n          \"@id\"\
  : \"dcterms:valid\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"targets\": \"tuf:targetFiles\",\n        \"delegations\": \"tuf:delegationConfiguration\"\n      }\n    },\n\n    \"SnapshotMetadata\": {\n      \"@id\": \"tuf:SnapshotMetadata\",\n      \"@context\": {\n        \"spec_version\": \"tuf:specVersion\",\n        \"version\": \"tuf:metadataVersion\",\n        \"expires\": {\n          \"@id\": \"dcterms:valid\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"meta\": \"tuf:metadataReferences\"\n      }\n    },\n\n    \"TimestampMetadata\": {\n      \"@id\": \"tuf:TimestampMetadata\",\n      \"@context\": {\n        \"spec_version\": \"tuf:specVersion\",\n        \"version\": \"tuf:metadataVersion\",\n        \"expires\": {\n          \"@id\": \"dcterms:valid\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"meta\": \"tuf:snapshotReference\"\n      }\n    },\n\n    \"TargetFile\": {\n      \"@id\": \"tuf:TargetFile\",\n      \"@context\"\
  : {\n        \"length\": \"tuf:fileLength\",\n        \"hashes\": \"tuf:fileHashes\",\n        \"custom\": \"tuf:customMetadata\"\n      }\n    },\n\n    \"MetaFile\": {\n      \"@id\": \"tuf:MetaFile\",\n      \"@context\": {\n        \"version\": \"tuf:metadataVersion\",\n        \"length\": \"tuf:fileLength\",\n        \"hashes\": \"tuf:fileHashes\"\n      }\n    },\n\n    \"Key\": {\n      \"@id\": \"sec:Key\",\n      \"@context\": {\n        \"keytype\": \"tuf:keyType\",\n        \"scheme\": \"tuf:signatureScheme\",\n        \"keyval\": \"sec:publicKeyJwk\"\n      }\n    },\n\n    \"Role\": {\n      \"@id\": \"tuf:Role\",\n      \"@context\": {\n        \"keyids\": {\n          \"@id\": \"tuf:authorizedKeyIds\",\n          \"@container\": \"@set\"\n        },\n        \"threshold\": \"tuf:signatureThreshold\"\n      }\n    },\n\n    \"DelegatedRole\": {\n      \"@id\": \"tuf:DelegatedRole\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"keyids\": {\n      \
  \    \"@id\": \"tuf:authorizedKeyIds\",\n          \"@container\": \"@set\"\n        },\n        \"threshold\": \"tuf:signatureThreshold\",\n        \"terminating\": \"tuf:terminatingDelegation\",\n        \"paths\": {\n          \"@id\": \"tuf:targetPathPatterns\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Delegations\": {\n      \"@id\": \"tuf:Delegations\",\n      \"@context\": {\n        \"keys\": \"tuf:delegationKeys\",\n        \"roles\": {\n          \"@id\": \"tuf:delegatedRoles\",\n          \"@container\": \"@list\"\n        }\n      }\n    },\n\n    \"Signature\": {\n      \"@id\": \"sec:Signature\",\n      \"@context\": {\n        \"keyid\": \"tuf:signingKeyId\",\n        \"sig\": \"sec:signatureValue\"\n      }\n    },\n\n    \"Hashes\": {\n      \"@id\": \"tuf:Hashes\",\n      \"@context\": {\n        \"sha256\": \"tuf:sha256Digest\",\n        \"sha512\": \"tuf:sha512Digest\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/tuf/refs/heads/main/json-ld/tuf-context.jsonld
tags:
- CNCF
- Cloud Native
- Graduated
- Security
- Software Supply Chain
- Software Updates
- Verification
- JSON-LD
- Linked Data
- Semantic Web
---
