---
class_count: 17
classes:
- Address
- AddressGroup
- AddressGroupList
- AddressGroupRequest
- AddressList
- AddressRequest
- DeleteResponse
- Job
- NatRule
- NatRuleList
- NatRuleRequest
- SecurityRule
- SecurityRuleList
- SecurityRuleRequest
- Service
- ServiceList
- ServiceRequest
context_file: json-ld/palo-alto-strata-cloud-manager-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/json-ld/palo-alto-strata-cloud-manager-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Palo Alto Strata Cloud Manager Api from Palo Alto Networks.
layout: jsonld
name: Palo Alto Strata Cloud Manager Api Context
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
  name: action
  type: string
- container: set
  name: application
  type: string
- container: ''
  name: biDirectional
  type: boolean
- container: set
  name: category
  type: string
- container: set
  name: data
  type: reference
- container: ''
  name: description
  type: string
- container: set
  name: destination
  type: string
- container: ''
  name: destinationTranslation
  type: reference
- container: ''
  name: details
  type: reference
- container: ''
  name: disabled
  type: boolean
- container: ''
  name: dynamic
  type: reference
- container: ''
  name: dynamicIpAndPort
  type: reference
- container: ''
  name: endTs
  type: dateTime
- container: ''
  name: filter
  type: string
- container: ''
  name: folder
  type: string
- container: ''
  name: fqdn
  type: string
- container: set
  name: from
  type: string
- container: set
  name: group
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: ipNetmask
  type: string
- container: ''
  name: ipRange
  type: string
- container: ''
  name: ipWildcard
  type: string
- container: ''
  name: limit
  type: integer
- container: ''
  name: logSetting
  type: string
- container: ''
  name: name
  type: string
- container: ''
  name: natType
  type: string
- container: ''
  name: offset
  type: integer
- container: ''
  name: percent
  type: integer
- container: ''
  name: port
  type: string
- container: ''
  name: position
  type: string
- container: ''
  name: profileSetting
  type: reference
- container: ''
  name: protocol
  type: reference
- container: ''
  name: result
  type: string
- container: ''
  name: service
  type: string
- container: ''
  name: snippet
  type: string
- container: set
  name: source
  type: string
- container: ''
  name: sourcePort
  type: string
- container: ''
  name: sourceTranslation
  type: reference
- container: set
  name: sourceUser
  type: string
- container: ''
  name: startTs
  type: dateTime
- container: set
  name: static
  type: string
- container: ''
  name: staticIp
  type: reference
- container: ''
  name: status
  type: string
- container: set
  name: tag
  type: string
- container: ''
  name: tcp
  type: reference
- container: set
  name: to
  type: string
- container: ''
  name: total
  type: integer
- container: set
  name: translatedAddress
  type: string
- container: ''
  name: translatedPort
  type: integer
- container: ''
  name: type
  type: string
- container: ''
  name: udp
  type: reference
property_count: 51
provider_name: Palo Alto Networks
provider_slug: palo-alto-networks
slug: palo-alto-strata-cloud-manager-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"pan\": \"https://pan.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Address\": \"pan:Address\",\n    \"AddressGroup\": \"pan:AddressGroup\",\n    \"AddressGroupList\": \"pan:AddressGroupList\",\n    \"AddressGroupRequest\": \"pan:AddressGroupRequest\",\n    \"AddressList\": \"pan:AddressList\",\n    \"AddressRequest\": \"pan:AddressRequest\",\n    \"DeleteResponse\": \"pan:DeleteResponse\",\n    \"Job\": \"pan:Job\",\n    \"NatRule\": \"pan:NatRule\",\n    \"NatRuleList\": \"pan:NatRuleList\",\n    \"NatRuleRequest\": \"pan:NatRuleRequest\",\n    \"SecurityRule\": \"pan:SecurityRule\",\n    \"SecurityRuleList\": \"pan:SecurityRuleList\",\n    \"SecurityRuleRequest\": \"pan:SecurityRuleRequest\",\n    \"Service\": \"pan:Service\",\n    \"ServiceList\": \"pan:ServiceList\",\n    \"ServiceRequest\": \"pan:ServiceRequest\"\
  ,\n    \"action\": {\n      \"@id\": \"pan:action\",\n      \"@type\": \"xsd:string\"\n    },\n    \"application\": {\n      \"@id\": \"pan:application\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"biDirectional\": {\n      \"@id\": \"pan:bi_directional\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"category\": {\n      \"@id\": \"pan:category\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"data\": {\n      \"@id\": \"pan:data\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"destination\": {\n      \"@id\": \"pan:destination\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"destinationTranslation\": {\n      \"@id\": \"pan:destination_translation\",\n      \"@type\": \"@id\"\n    },\n    \"details\": {\n      \"@id\": \"pan:details\",\n      \"\
  @type\": \"@id\"\n    },\n    \"disabled\": {\n      \"@id\": \"pan:disabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"dynamic\": {\n      \"@id\": \"pan:dynamic\",\n      \"@type\": \"@id\"\n    },\n    \"dynamicIpAndPort\": {\n      \"@id\": \"pan:dynamic_ip_and_port\",\n      \"@type\": \"@id\"\n    },\n    \"endTs\": {\n      \"@id\": \"pan:end_ts\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"filter\": {\n      \"@id\": \"pan:filter\",\n      \"@type\": \"xsd:string\"\n    },\n    \"folder\": {\n      \"@id\": \"pan:folder\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fqdn\": {\n      \"@id\": \"pan:fqdn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"from\": {\n      \"@id\": \"pan:from\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"group\": {\n      \"@id\": \"pan:group\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"pan:id\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"ipNetmask\": {\n      \"@id\": \"pan:ip_netmask\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ipRange\": {\n      \"@id\": \"pan:ip_range\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ipWildcard\": {\n      \"@id\": \"pan:ip_wildcard\",\n      \"@type\": \"xsd:string\"\n    },\n    \"limit\": {\n      \"@id\": \"pan:limit\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"logSetting\": {\n      \"@id\": \"pan:log_setting\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"natType\": {\n      \"@id\": \"pan:nat_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"offset\": {\n      \"@id\": \"pan:offset\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"percent\": {\n      \"@id\": \"pan:percent\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"port\": {\n      \"@id\": \"pan:port\",\n      \"@type\": \"xsd:string\"\n    },\n    \"position\": {\n      \"@id\": \"pan:position\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"profileSetting\": {\n      \"@id\": \"pan:profile_setting\",\n      \"@type\": \"@id\"\n    },\n    \"protocol\": {\n      \"@id\": \"pan:protocol\",\n      \"@type\": \"@id\"\n    },\n    \"result\": {\n      \"@id\": \"pan:result\",\n      \"@type\": \"xsd:string\"\n    },\n    \"service\": {\n      \"@id\": \"pan:service\",\n      \"@type\": \"xsd:string\"\n    },\n    \"snippet\": {\n      \"@id\": \"pan:snippet\",\n      \"@type\": \"xsd:string\"\n    },\n    \"source\": {\n      \"@id\": \"pan:source\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sourcePort\": {\n      \"@id\": \"pan:source_port\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sourceTranslation\": {\n      \"@id\": \"pan:source_translation\",\n      \"@type\": \"@id\"\n    },\n    \"sourceUser\": {\n      \"@id\": \"pan:source_user\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startTs\":\
  \ {\n      \"@id\": \"pan:start_ts\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"static\": {\n      \"@id\": \"pan:static\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"staticIp\": {\n      \"@id\": \"pan:static_ip\",\n      \"@type\": \"@id\"\n    },\n    \"status\": {\n      \"@id\": \"pan:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tag\": {\n      \"@id\": \"pan:tag\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tcp\": {\n      \"@id\": \"pan:tcp\",\n      \"@type\": \"@id\"\n    },\n    \"to\": {\n      \"@id\": \"pan:to\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"total\": {\n      \"@id\": \"pan:total\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"translatedAddress\": {\n      \"@id\": \"pan:translated_address\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"translatedPort\": {\n      \"@id\": \"pan:translated_port\"\
  ,\n      \"@type\": \"xsd:integer\"\n    },\n    \"type\": {\n      \"@id\": \"pan:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"udp\": {\n      \"@id\": \"pan:udp\",\n      \"@type\": \"@id\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/json-ld/palo-alto-strata-cloud-manager-api-context.jsonld
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
