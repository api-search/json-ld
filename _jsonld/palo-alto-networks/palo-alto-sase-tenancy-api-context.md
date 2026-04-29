---
class_count: 3
classes:
- TenantServiceGroup
- TenantServiceGroupRequest
- TenantServiceGroupUpdate
context_file: json-ld/palo-alto-sase-tenancy-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/json-ld/palo-alto-sase-tenancy-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Palo Alto Sase Tenancy Api from Palo Alto Networks.
layout: jsonld
name: Palo Alto Sase Tenancy Api Context
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
  name: childCount
  type: integer
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
  name: id
  type: string
- container: ''
  name: parentId
  type: string
- container: ''
  name: region
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: supportAccountId
  type: string
- container: ''
  name: updatedAt
  type: dateTime
- container: ''
  name: vertical
  type: string
property_count: 11
provider_name: Palo Alto Networks
provider_slug: palo-alto-networks
slug: palo-alto-sase-tenancy-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"pan\": \"https://pan.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"TenantServiceGroup\": \"pan:TenantServiceGroup\",\n    \"TenantServiceGroupRequest\": \"pan:TenantServiceGroupRequest\",\n    \"TenantServiceGroupUpdate\": \"pan:TenantServiceGroupUpdate\",\n    \"childCount\": {\n      \"@id\": \"pan:child_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"displayName\": {\n      \"@id\": \"pan:display_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"pan:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"parentId\": {\n      \"@id\": \"pan:parent_id\",\n  \
  \    \"@type\": \"xsd:string\"\n    },\n    \"region\": {\n      \"@id\": \"pan:region\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"pan:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"supportAccountId\": {\n      \"@id\": \"pan:support_account_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"vertical\": {\n      \"@id\": \"pan:vertical\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/json-ld/palo-alto-sase-tenancy-api-context.jsonld
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
