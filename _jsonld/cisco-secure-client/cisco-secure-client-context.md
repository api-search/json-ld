---
class_count: 18
classes:
- Endpoint
- User
- Device
- VPNConnection
- Tunnel
- PostureAssessment
- PolicyProfile
- Application
- DNSPolicy
- MFAEvent
- name
- ipAddress
- macAddress
- osVersion
- clientVersion
- tunnelGroup
- complianceState
- createdAt
context_file: json-ld/cisco-secure-client-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/cisco-secure-client/refs/heads/main/json-ld/cisco-secure-client-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Cisco Secure Client from Cisco Secure Client.
layout: jsonld
name: Cisco Secure Client Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: csc
  uri: https://developer.cisco.com/vocab/secure-client/
properties: []
property_count: 0
provider_name: Cisco Secure Client
provider_slug: cisco-secure-client
slug: cisco-secure-client-context
source_filename: cisco-secure-client-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://apievangelist.com/vocab/cisco-secure-client/\",\n    \"schema\": \"https://schema.org/\",\n    \"csc\": \"https://developer.cisco.com/vocab/secure-client/\",\n    \"Endpoint\": \"csc:Endpoint\",\n    \"User\": \"schema:Person\",\n    \"Device\": \"schema:Product\",\n    \"VPNConnection\": \"csc:VPNConnection\",\n    \"Tunnel\": \"csc:Tunnel\",\n    \"PostureAssessment\": \"csc:PostureAssessment\",\n    \"PolicyProfile\": \"csc:PolicyProfile\",\n    \"Application\": \"csc:ZTNAApplication\",\n    \"DNSPolicy\": \"csc:DNSPolicy\",\n    \"MFAEvent\": \"csc:MFAEvent\",\n    \"name\": \"schema:name\",\n    \"ipAddress\": \"csc:ipAddress\",\n    \"macAddress\": \"csc:macAddress\",\n    \"osVersion\": \"csc:osVersion\",\n    \"clientVersion\": \"csc:clientVersion\",\n    \"tunnelGroup\": \"csc:tunnelGroup\",\n    \"complianceState\": \"csc:complianceState\",\n    \"createdAt\": \"schema:dateCreated\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/cisco-secure-client/refs/heads/main/json-ld/cisco-secure-client-context.jsonld
tags:
- Endpoint Security
- Remote Access
- Security
- VPN
- Zero Trust
- JSON-LD
- Linked Data
- Semantic Web
---
