---
api_specs:
- filename: ssh-key-management-openapi.yml
  format: yaml
  label: OpenSSH Key Management API
  slug: openssh-management
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/ssh/refs/heads/main/openapi/ssh-key-management-openapi.yml
class_count: 15
classes:
- SSHKey
- SSHCertificate
- KnownHost
- AuthorizedKey
- id
- keyType
- publicKey
- fingerprint
- comment
- certificate
- serialNumber
- certType
- hostname
- username
- options
context_file: json-ld/ssh-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/ssh/refs/heads/main/json-ld/ssh-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Ssh from SSH.
layout: jsonld
name: Ssh Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: ssh
  uri: https://www.openssh.com/vocab/
- prefix: sec
  uri: https://w3id.org/security#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: userId
  type: reference
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: lastUsedAt
  type: dateTime
- container: list
  name: principals
  type: ''
- container: ''
  name: validAfter
  type: dateTime
- container: ''
  name: validBefore
  type: dateTime
property_count: 6
provider_name: SSH
provider_slug: ssh
slug: ssh-context
source_filename: ssh-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"ssh\": \"https://www.openssh.com/vocab/\",\n    \"sec\": \"https://w3id.org/security#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"SSHKey\": \"sec:Key\",\n    \"SSHCertificate\": \"sec:Certificate\",\n    \"KnownHost\": \"ssh:KnownHost\",\n    \"AuthorizedKey\": \"ssh:AuthorizedKey\",\n\n    \"id\": \"schema:identifier\",\n    \"userId\": {\n      \"@id\": \"ssh:owner\",\n      \"@type\": \"@id\"\n    },\n    \"keyType\": \"sec:algorithm\",\n    \"publicKey\": \"sec:publicKeyPem\",\n    \"fingerprint\": \"sec:fingerprint\",\n    \"comment\": \"schema:description\",\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"lastUsedAt\": {\n      \"@id\": \"ssh:lastUsed\",\n      \"@type\": \"xsd:dateTime\"\n    },\n\n    \"certificate\": \"sec:certificate\",\n    \"serialNumber\": \"sec:serialNumber\",\n    \"\
  principals\": {\n      \"@id\": \"ssh:authorizedPrincipals\",\n      \"@container\": \"@list\"\n    },\n    \"validAfter\": {\n      \"@id\": \"schema:validFrom\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"validBefore\": {\n      \"@id\": \"schema:validThrough\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"certType\": \"ssh:certificateType\",\n\n    \"hostname\": \"schema:name\",\n    \"username\": \"schema:identifier\",\n    \"options\": \"ssh:authorizedKeyOptions\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/ssh/refs/heads/main/json-ld/ssh-context.jsonld
tags:
- SSH
- Secure Shell
- Remote Access
- Cryptography
- Network Security
- System Administration
- JSON-LD
- Linked Data
- Semantic Web
---
