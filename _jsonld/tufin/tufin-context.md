---
api_specs:
- filename: tufin-securetrack-openapi.yml
  format: yaml
  label: Tufin SecureTrack API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tufin/refs/heads/main/openapi/tufin-securetrack-openapi.yml
- filename: tufin-securechange-openapi.yml
  format: yaml
  label: Tufin SecureChange API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tufin/refs/heads/main/openapi/tufin-securechange-openapi.yml
class_count: 0
classes: []
context_file: json-ld/tufin-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/tufin/refs/heads/main/json-ld/tufin-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Tufin from Tufin.
layout: jsonld
name: Tufin Context
namespaces:
- prefix: tufin
  uri: https://www.tufin.com/vocabulary#
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: netsec
  uri: https://www.tufin.com/network-security#
properties:
- container: ''
  name: Device
  type: ''
- container: ''
  name: Rule
  type: ''
- container: ''
  name: Ticket
  type: ''
- container: ''
  name: Task
  type: ''
- container: ''
  name: NetworkObject
  type: ''
- container: ''
  name: TopologyPath
  type: ''
property_count: 6
provider_name: Tufin
provider_slug: tufin
slug: tufin-context
source_filename: tufin-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"tufin\": \"https://www.tufin.com/vocabulary#\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"netsec\": \"https://www.tufin.com/network-security#\",\n\n    \"Device\": {\n      \"@id\": \"tufin:Device\",\n      \"@context\": {\n        \"id\": \"tufin:deviceId\",\n        \"name\": \"schema:name\",\n        \"ip\": \"netsec:ipAddress\",\n        \"vendor\": \"schema:manufacturer\",\n        \"model\": \"schema:model\",\n        \"version\": \"schema:softwareVersion\",\n        \"domain\": \"tufin:managementDomain\",\n        \"topology\": \"tufin:participatesInTopology\",\n        \"managedBy\": \"tufin:managedBySystem\"\n      }\n    },\n\n    \"Rule\": {\n      \"@id\": \"tufin:FirewallRule\",\n      \"@context\": {\n        \"id\": \"tufin:ruleId\",\n        \"name\": \"schema:name\",\n        \"enabled\": \"tufin:isEnabled\"\
  ,\n        \"action\": \"netsec:firewallAction\",\n        \"sources\": {\n          \"@id\": \"netsec:sourceObjects\",\n          \"@container\": \"@set\"\n        },\n        \"destinations\": {\n          \"@id\": \"netsec:destinationObjects\",\n          \"@container\": \"@set\"\n        },\n        \"services\": {\n          \"@id\": \"netsec:serviceObjects\",\n          \"@container\": \"@set\"\n        },\n        \"comment\": \"schema:description\",\n        \"lastHit\": {\n          \"@id\": \"tufin:lastHitTime\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Ticket\": {\n      \"@id\": \"tufin:ChangeTicket\",\n      \"@context\": {\n        \"id\": \"tufin:ticketId\",\n        \"subject\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"status\": \"schema:actionStatus\",\n        \"priority\": \"schema:importance\",\n        \"requester\": \"schema:agent\",\n        \"created\": {\n          \"@id\": \"dcterms:created\"\
  ,\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"modified\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"workflow\": \"tufin:workflowDefinition\",\n        \"tasks\": {\n          \"@id\": \"tufin:workflowTasks\",\n          \"@container\": \"@list\"\n        }\n      }\n    },\n\n    \"Task\": {\n      \"@id\": \"tufin:WorkflowTask\",\n      \"@context\": {\n        \"id\": \"tufin:taskId\",\n        \"name\": \"schema:name\",\n        \"type\": \"tufin:taskType\",\n        \"status\": \"schema:actionStatus\",\n        \"assignee\": \"schema:assignee\",\n        \"dueDate\": {\n          \"@id\": \"schema:scheduledTime\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"NetworkObject\": {\n      \"@id\": \"netsec:NetworkObject\",\n      \"@context\": {\n        \"id\": \"tufin:objectId\",\n        \"name\": \"schema:name\",\n        \"type\": \"netsec:objectType\",\n        \"ip\":\
  \ \"netsec:ipAddress\",\n        \"netmask\": \"netsec:networkMask\"\n      }\n    },\n\n    \"TopologyPath\": {\n      \"@id\": \"netsec:TopologyPath\",\n      \"@context\": {\n        \"traffic_allowed\": \"netsec:trafficAllowed\",\n        \"is_fully_routed\": \"netsec:isFullyRouted\",\n        \"device_info\": {\n          \"@id\": \"netsec:traversedDevices\",\n          \"@container\": \"@list\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/tufin/refs/heads/main/json-ld/tufin-context.jsonld
tags:
- Cloud Security
- Compliance
- Firewall Management
- Network Security
- Network Topology
- Policy Orchestration
- Risk Management
- Security Policy Management
- Zero Trust
- JSON-LD
- Linked Data
- Semantic Web
---
