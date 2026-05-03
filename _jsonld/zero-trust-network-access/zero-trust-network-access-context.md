---
class_count: 24
classes:
- AccessPolicy
- Application
- Connector
- DevicePosture
- IdentityProvider
- Subject
- Tunnel
- Resource
- id
- name
- description
- decision
- enabled
- subjects
- resources
- conditions
- device_posture
- mfa
- geo
- time_window
- risk_score_max
- session
- max_duration_seconds
- reauth_interval_seconds
context_file: json-ld/zero-trust-network-access-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/zero-trust-network-access/refs/heads/main/json-ld/zero-trust-network-access-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Zero Trust Network Access from Zero Trust Network Access.
layout: jsonld
name: Zero Trust Network Access Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: ztna
  uri: https://api-evangelist.com/zero-trust-network-access/vocab#
properties: []
property_count: 0
provider_name: Zero Trust Network Access
provider_slug: zero-trust-network-access
slug: zero-trust-network-access-context
source_filename: zero-trust-network-access-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"ztna\": \"https://api-evangelist.com/zero-trust-network-access/vocab#\",\n    \"AccessPolicy\": \"ztna:AccessPolicy\",\n    \"Application\": \"ztna:Application\",\n    \"Connector\": \"ztna:Connector\",\n    \"DevicePosture\": \"ztna:DevicePosture\",\n    \"IdentityProvider\": \"ztna:IdentityProvider\",\n    \"Subject\": \"ztna:Subject\",\n    \"Tunnel\": \"ztna:Tunnel\",\n    \"Resource\": \"ztna:Resource\",\n    \"id\": \"@id\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"decision\": \"ztna:decision\",\n    \"enabled\": \"ztna:enabled\",\n    \"subjects\": \"ztna:subjects\",\n    \"resources\": \"ztna:resources\",\n    \"conditions\": \"ztna:conditions\",\n    \"device_posture\": \"ztna:devicePosture\",\n    \"mfa\": \"ztna:mfaRequired\",\n    \"geo\": \"ztna:geoAllowList\",\n    \"time_window\": \"schema:eligibleRegion\",\n    \"risk_score_max\"\
  : \"ztna:riskScoreMax\",\n    \"session\": \"ztna:session\",\n    \"max_duration_seconds\": \"ztna:sessionMaxDuration\",\n    \"reauth_interval_seconds\": \"ztna:reauthInterval\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/zero-trust-network-access/refs/heads/main/json-ld/zero-trust-network-access-context.jsonld
tags:
- Access Control
- Cloud Security
- Cybersecurity
- Identity Management
- Network Access
- Network Security
- Security
- VPN Replacement
- Zero Trust
- ZTNA
- JSON-LD
- Linked Data
- Semantic Web
---
