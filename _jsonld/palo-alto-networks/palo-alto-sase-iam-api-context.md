---
class_count: 7
classes:
- AccessPolicy
- AccessPolicyRequest
- Role
- ServiceAccount
- ServiceAccountCredentials
- ServiceAccountRequest
- ServiceAccountUpdate
context_file: json-ld/palo-alto-sase-iam-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/json-ld/palo-alto-sase-iam-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Palo Alto Sase Iam Api from Palo Alto Networks.
layout: jsonld
name: Palo Alto Sase Iam Api Context
namespaces:
- prefix: pan
  uri: https://pan.dev/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: clientId
  type: string
- container: ''
  name: clientSecret
  type: string
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: description
  type: string
- container: ''
  name: displayName
  type: string
- container: ''
  name: expiresAt
  type: dateTime
- container: ''
  name: id
  type: string
- container: ''
  name: keyCount
  type: integer
- container: ''
  name: keyId
  type: string
- container: ''
  name: name
  type: string
- container: set
  name: permissions
  type: string
- container: ''
  name: principalId
  type: string
- container: ''
  name: principalType
  type: string
- container: ''
  name: roleId
  type: string
- container: ''
  name: roleName
  type: string
- container: ''
  name: tsgId
  type: string
- container: ''
  name: updatedAt
  type: dateTime
property_count: 17
provider_name: Palo Alto Networks
provider_slug: palo-alto-networks
slug: palo-alto-sase-iam-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"pan\": \"https://pan.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AccessPolicy\": \"pan:AccessPolicy\",\n    \"AccessPolicyRequest\": \"pan:AccessPolicyRequest\",\n    \"Role\": \"pan:Role\",\n    \"ServiceAccount\": \"pan:ServiceAccount\",\n    \"ServiceAccountCredentials\": \"pan:ServiceAccountCredentials\",\n    \"ServiceAccountRequest\": \"pan:ServiceAccountRequest\",\n    \"ServiceAccountUpdate\": \"pan:ServiceAccountUpdate\",\n    \"clientId\": {\n      \"@id\": \"pan:client_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"clientSecret\": {\n      \"@id\": \"pan:client_secret\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"\
  @type\": \"xsd:string\"\n    },\n    \"displayName\": {\n      \"@id\": \"pan:display_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"expiresAt\": {\n      \"@id\": \"pan:expires_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"id\": {\n      \"@id\": \"pan:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"keyCount\": {\n      \"@id\": \"pan:key_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"keyId\": {\n      \"@id\": \"pan:key_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"permissions\": {\n      \"@id\": \"pan:permissions\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"principalId\": {\n      \"@id\": \"pan:principal_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"principalType\": {\n      \"@id\": \"pan:principal_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"roleId\": {\n      \"@id\": \"pan:role_id\",\n \
  \     \"@type\": \"xsd:string\"\n    },\n    \"roleName\": {\n      \"@id\": \"pan:role_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tsgId\": {\n      \"@id\": \"pan:tsg_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/json-ld/palo-alto-sase-iam-api-context.jsonld
tags:
- Cloud Security
- Cybersecurity
- Firewall
- Network Security
- SASE
- SOAR
- Threat Intelligence
- XDR
- JSON-LD
- Linked Data
- Semantic Web
---
