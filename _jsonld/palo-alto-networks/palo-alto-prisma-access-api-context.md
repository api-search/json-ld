---
class_count: 7
classes:
- IKEGateway
- IPSecTunnel
- JobStatus
- MobileAgentInfrastructureSettings
- RemoteNetwork
- SecurityRule
- ServiceConnection
context_file: json-ld/palo-alto-prisma-access-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/json-ld/palo-alto-prisma-access-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Palo Alto Prisma Access Api from Palo Alto Networks.
layout: jsonld
name: Palo Alto Prisma Access Api Context
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
  name: addresses
  type: string
- container: ''
  name: antiReplay
  type: boolean
- container: set
  name: application
  type: string
- container: ''
  name: authentication
  type: reference
- container: ''
  name: autoKey
  type: reference
- container: set
  name: category
  type: string
- container: ''
  name: certificate
  type: reference
- container: ''
  name: description
  type: string
- container: set
  name: destination
  type: string
- container: ''
  name: destinationIp
  type: string
- container: set
  name: details
  type: string
- container: ''
  name: disabled
  type: boolean
- container: set
  name: dnsServers
  type: string
- container: set
  name: dnsSuffix
  type: string
- container: ''
  name: dynamic
  type: boolean
- container: ''
  name: ecmpLoadBalancing
  type: string
- container: ''
  name: enable
  type: boolean
- container: ''
  name: endTs
  type: dateTime
- container: ''
  name: folder
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
- container: set
  name: ikeGateway
  type: reference
- container: ''
  name: ip
  type: string
- container: set
  name: ipPool
  type: string
- container: ''
  name: ipsecCryptoProfile
  type: string
- container: ''
  name: ipsecTunnel
  type: string
- container: ''
  name: licenseType
  type: string
- container: ''
  name: localCertificate
  type: string
- container: ''
  name: localId
  type: reference
- container: ''
  name: logSetting
  type: string
- container: ''
  name: name
  type: string
- container: ''
  name: natPool
  type: string
- container: ''
  name: peerAddress
  type: reference
- container: ''
  name: peerId
  type: reference
- container: ''
  name: position
  type: string
- container: ''
  name: preSharedKey
  type: string
- container: ''
  name: profileSetting
  type: reference
- container: ''
  name: proxyId
  type: string
- container: ''
  name: qosEnabled
  type: boolean
- container: ''
  name: region
  type: string
- container: set
  name: regions
  type: reference
- container: ''
  name: result
  type: string
- container: set
  name: service
  type: string
- container: set
  name: source
  type: string
- container: set
  name: sourceUser
  type: string
- container: ''
  name: spnName
  type: string
- container: ''
  name: startTs
  type: dateTime
- container: ''
  name: status
  type: string
- container: set
  name: subnets
  type: string
- container: set
  name: tag
  type: string
- container: set
  name: to
  type: string
- container: ''
  name: tunnelMonitor
  type: reference
- container: ''
  name: type
  type: string
- container: ''
  name: version
  type: string
property_count: 56
provider_name: Palo Alto Networks
provider_slug: palo-alto-networks
slug: palo-alto-prisma-access-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"pan\": \"https://pan.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"IKEGateway\": \"pan:IKEGateway\",\n    \"IPSecTunnel\": \"pan:IPSecTunnel\",\n    \"JobStatus\": \"pan:JobStatus\",\n    \"MobileAgentInfrastructureSettings\": \"pan:MobileAgentInfrastructureSettings\",\n    \"RemoteNetwork\": \"pan:RemoteNetwork\",\n    \"SecurityRule\": \"pan:SecurityRule\",\n    \"ServiceConnection\": \"pan:ServiceConnection\",\n    \"action\": {\n      \"@id\": \"pan:action\",\n      \"@type\": \"xsd:string\"\n    },\n    \"addresses\": {\n      \"@id\": \"pan:addresses\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"antiReplay\": {\n      \"@id\": \"pan:anti_replay\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"application\": {\n      \"@id\": \"pan:application\",\n      \"@container\"\
  : \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"authentication\": {\n      \"@id\": \"pan:authentication\",\n      \"@type\": \"@id\"\n    },\n    \"autoKey\": {\n      \"@id\": \"pan:auto_key\",\n      \"@type\": \"@id\"\n    },\n    \"category\": {\n      \"@id\": \"pan:category\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"certificate\": {\n      \"@id\": \"pan:certificate\",\n      \"@type\": \"@id\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"destination\": {\n      \"@id\": \"pan:destination\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"destinationIp\": {\n      \"@id\": \"pan:destination_ip\",\n      \"@type\": \"xsd:string\"\n    },\n    \"details\": {\n      \"@id\": \"pan:details\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"disabled\": {\n      \"@id\": \"pan:disabled\",\n   \
  \   \"@type\": \"xsd:boolean\"\n    },\n    \"dnsServers\": {\n      \"@id\": \"pan:dns_servers\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dnsSuffix\": {\n      \"@id\": \"pan:dns_suffix\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dynamic\": {\n      \"@id\": \"pan:dynamic\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"ecmpLoadBalancing\": {\n      \"@id\": \"pan:ecmp_load_balancing\",\n      \"@type\": \"xsd:string\"\n    },\n    \"enable\": {\n      \"@id\": \"pan:enable\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"endTs\": {\n      \"@id\": \"pan:end_ts\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"folder\": {\n      \"@id\": \"pan:folder\",\n      \"@type\": \"xsd:string\"\n    },\n    \"from\": {\n      \"@id\": \"pan:from\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"group\": {\n      \"@id\": \"pan:group\",\n      \"@container\": \"@set\",\n \
  \     \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"pan:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ikeGateway\": {\n      \"@id\": \"pan:ike_gateway\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"ip\": {\n      \"@id\": \"pan:ip\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ipPool\": {\n      \"@id\": \"pan:ip_pool\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ipsecCryptoProfile\": {\n      \"@id\": \"pan:ipsec_crypto_profile\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ipsecTunnel\": {\n      \"@id\": \"pan:ipsec_tunnel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"licenseType\": {\n      \"@id\": \"pan:license_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"localCertificate\": {\n      \"@id\": \"pan:local_certificate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"localId\": {\n      \"@id\": \"pan:local_id\",\n      \"@type\": \"@id\"\n    },\n    \"logSetting\"\
  : {\n      \"@id\": \"pan:log_setting\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"natPool\": {\n      \"@id\": \"pan:nat_pool\",\n      \"@type\": \"xsd:string\"\n    },\n    \"peerAddress\": {\n      \"@id\": \"pan:peer_address\",\n      \"@type\": \"@id\"\n    },\n    \"peerId\": {\n      \"@id\": \"pan:peer_id\",\n      \"@type\": \"@id\"\n    },\n    \"position\": {\n      \"@id\": \"pan:position\",\n      \"@type\": \"xsd:string\"\n    },\n    \"preSharedKey\": {\n      \"@id\": \"pan:pre_shared_key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"profileSetting\": {\n      \"@id\": \"pan:profile_setting\",\n      \"@type\": \"@id\"\n    },\n    \"proxyId\": {\n      \"@id\": \"pan:proxy_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"qosEnabled\": {\n      \"@id\": \"pan:qos_enabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"region\": {\n      \"@id\": \"pan:region\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"regions\": {\n      \"@id\": \"pan:regions\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"result\": {\n      \"@id\": \"pan:result\",\n      \"@type\": \"xsd:string\"\n    },\n    \"service\": {\n      \"@id\": \"pan:service\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"source\": {\n      \"@id\": \"pan:source\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sourceUser\": {\n      \"@id\": \"pan:source_user\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"spnName\": {\n      \"@id\": \"pan:spn_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startTs\": {\n      \"@id\": \"pan:start_ts\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"status\": {\n      \"@id\": \"pan:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subnets\": {\n      \"@id\": \"pan:subnets\",\n      \"@container\"\
  : \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tag\": {\n      \"@id\": \"pan:tag\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"to\": {\n      \"@id\": \"pan:to\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tunnelMonitor\": {\n      \"@id\": \"pan:tunnel_monitor\",\n      \"@type\": \"@id\"\n    },\n    \"type\": {\n      \"@id\": \"pan:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"version\": {\n      \"@id\": \"schema:version\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/json-ld/palo-alto-prisma-access-api-context.jsonld
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
