---
class_count: 11
classes:
- Connector
- ConnectorGroup
- ConnectorGroupRequest
- ConnectorRequest
- FQDNRule
- FQDNRuleRequest
- LicenseInfo
- SubnetRule
- SubnetRuleRequest
- ZTNAApplication
- ZTNAApplicationRequest
context_file: json-ld/palo-alto-ztna-connector-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/json-ld/palo-alto-ztna-connector-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Palo Alto Ztna Connector Api from Palo Alto Networks.
layout: jsonld
name: Palo Alto Ztna Connector Api Context
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
  name: activeUsers
  type: integer
- container: ''
  name: appId
  type: string
- container: ''
  name: connectorCount
  type: integer
- container: ''
  name: connectorId
  type: string
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: description
  type: string
- container: ''
  name: enabled
  type: boolean
- container: ''
  name: expiresAt
  type: dateTime
- container: set
  name: features
  type: string
- container: ''
  name: fqdn
  type: string
- container: ''
  name: fqdnPattern
  type: string
- container: ''
  name: groupId
  type: string
- container: ''
  name: hostname
  type: string
- container: ''
  name: ipAddress
  type: string
- container: ''
  name: lastSeenAt
  type: dateTime
- container: ''
  name: licensedUsers
  type: integer
- container: ''
  name: name
  type: string
- container: set
  name: ports
  type: integer
- container: set
  name: protocols
  type: string
- container: ''
  name: region
  type: string
- container: ''
  name: ruleId
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: subnet
  type: string
- container: ''
  name: subscriptionId
  type: string
- container: ''
  name: version
  type: string
property_count: 25
provider_name: Palo Alto Networks
provider_slug: palo-alto-networks
slug: palo-alto-ztna-connector-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"pan\": \"https://pan.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Connector\": \"pan:Connector\",\n    \"ConnectorGroup\": \"pan:ConnectorGroup\",\n    \"ConnectorGroupRequest\": \"pan:ConnectorGroupRequest\",\n    \"ConnectorRequest\": \"pan:ConnectorRequest\",\n    \"FQDNRule\": \"pan:FQDNRule\",\n    \"FQDNRuleRequest\": \"pan:FQDNRuleRequest\",\n    \"LicenseInfo\": \"pan:LicenseInfo\",\n    \"SubnetRule\": \"pan:SubnetRule\",\n    \"SubnetRuleRequest\": \"pan:SubnetRuleRequest\",\n    \"ZTNAApplication\": \"pan:ZTNAApplication\",\n    \"ZTNAApplicationRequest\": \"pan:ZTNAApplicationRequest\",\n    \"activeUsers\": {\n      \"@id\": \"pan:active_users\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"appId\": {\n      \"@id\": \"pan:app_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"connectorCount\"\
  : {\n      \"@id\": \"pan:connector_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"connectorId\": {\n      \"@id\": \"pan:connector_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"enabled\": {\n      \"@id\": \"pan:enabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"expiresAt\": {\n      \"@id\": \"pan:expires_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"features\": {\n      \"@id\": \"pan:features\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fqdn\": {\n      \"@id\": \"pan:fqdn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fqdnPattern\": {\n      \"@id\": \"pan:fqdn_pattern\",\n      \"@type\": \"xsd:string\"\n    },\n    \"groupId\": {\n      \"@id\": \"pan:group_id\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"hostname\": {\n      \"@id\": \"pan:hostname\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ipAddress\": {\n      \"@id\": \"pan:ip_address\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastSeenAt\": {\n      \"@id\": \"pan:last_seen_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"licensedUsers\": {\n      \"@id\": \"pan:licensed_users\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ports\": {\n      \"@id\": \"pan:ports\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"protocols\": {\n      \"@id\": \"pan:protocols\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"region\": {\n      \"@id\": \"pan:region\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ruleId\": {\n      \"@id\": \"pan:rule_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"pan:status\",\n\
  \      \"@type\": \"xsd:string\"\n    },\n    \"subnet\": {\n      \"@id\": \"pan:subnet\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subscriptionId\": {\n      \"@id\": \"pan:subscription_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"version\": {\n      \"@id\": \"schema:version\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/json-ld/palo-alto-ztna-connector-api-context.jsonld
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
