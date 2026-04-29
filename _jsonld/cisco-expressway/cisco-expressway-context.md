---
api_specs:
- filename: cisco-expressway-configuration-api-openapi.yml
  format: yaml
  label: Cisco Expressway Configuration API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/cisco-expressway/refs/heads/main/openapi/cisco-expressway-configuration-api-openapi.yml
- filename: cisco-expressway-status-api-openapi.yml
  format: yaml
  label: Cisco Expressway Status API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/cisco-expressway/refs/heads/main/openapi/cisco-expressway-status-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/cisco-expressway-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/cisco-expressway/refs/heads/main/json-ld/cisco-expressway-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Cisco Expressway from Cisco Expressway.
layout: jsonld
name: Cisco Expressway Context
namespaces:
- prefix: cisco
  uri: https://developer.cisco.com/ns/expressway#
- prefix: uc
  uri: https://www.itu.int/rec/T-REC-H.323/ns#
- prefix: sip
  uri: https://www.ietf.org/rfc/rfc3261#
- prefix: snmp
  uri: https://www.ietf.org/rfc/rfc3411#
- prefix: ice
  uri: https://www.ietf.org/rfc/rfc8445#
- prefix: turn
  uri: https://www.ietf.org/rfc/rfc8656#
- prefix: tls
  uri: https://www.ietf.org/rfc/rfc8446#
- prefix: dns
  uri: https://www.ietf.org/rfc/rfc1035#
- prefix: ntp
  uri: https://www.ietf.org/rfc/rfc5905#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
properties:
- container: ''
  name: ExpresswaySystem
  type: reference
- container: ''
  name: SystemName
  type: string
- container: ''
  name: SoftwareVersion
  type: string
- container: ''
  name: SerialNumber
  type: string
- container: ''
  name: IPv4Address
  type: string
- container: ''
  name: IPv6Address
  type: string
- container: ''
  name: Uptime
  type: string
- container: ''
  name: Zone
  type: reference
- container: ''
  name: NeighborZone
  type: reference
- container: ''
  name: TraversalServerZone
  type: reference
- container: ''
  name: TraversalClientZone
  type: reference
- container: ''
  name: DNSZone
  type: reference
- container: ''
  name: ENUMZone
  type: reference
- container: ''
  name: ZoneName
  type: string
- container: ''
  name: HopCount
  type: integer
- container: ''
  name: PeerAddress
  type: string
- container: ''
  name: MediaEncryptionMode
  type: string
- container: ''
  name: SearchRule
  type: reference
- container: ''
  name: AliasPatternType
  type: string
- container: ''
  name: AliasPatternString
  type: string
- container: ''
  name: TargetZone
  type: reference
- container: ''
  name: Priority
  type: integer
- container: ''
  name: Transform
  type: reference
- container: ''
  name: PatternType
  type: string
- container: ''
  name: PatternString
  type: string
- container: ''
  name: ReplaceString
  type: string
- container: ''
  name: Call
  type: reference
- container: ''
  name: SourceAlias
  type: string
- container: ''
  name: DestinationAlias
  type: string
- container: ''
  name: CallType
  type: string
- container: ''
  name: StartTime
  type: dateTime
- container: ''
  name: EndTime
  type: dateTime
- container: ''
  name: Duration
  type: integer
- container: ''
  name: Registration
  type: reference
- container: ''
  name: DeviceType
  type: string
- container: ''
  name: ContactAddress
  type: string
- container: ''
  name: Subzone
  type: string
- container: ''
  name: Alarm
  type: reference
- container: ''
  name: AlarmId
  type: string
- container: ''
  name: Severity
  type: string
- container: ''
  name: Title
  type: string
- container: ''
  name: Description
  type: string
- container: ''
  name: TimeRaised
  type: dateTime
- container: ''
  name: DnsServer
  type: reference
- container: ''
  name: NtpServer
  type: reference
- container: ''
  name: Address
  type: string
- container: ''
  name: SmartLicense
  type: reference
- container: ''
  name: RegistrationStatus
  type: string
- container: ''
  name: AuthorizationStatus
  type: string
- container: ''
  name: TurnRelay
  type: reference
- container: ''
  name: SIPConfiguration
  type: reference
- container: ''
  name: SIPMode
  type: string
- container: ''
  name: H323Mode
  type: string
property_count: 53
provider_name: Cisco Expressway
provider_slug: cisco-expressway
slug: cisco-expressway-context
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"cisco\": \"https://developer.cisco.com/ns/expressway#\",\n    \"uc\": \"https://www.itu.int/rec/T-REC-H.323/ns#\",\n    \"sip\": \"https://www.ietf.org/rfc/rfc3261#\",\n    \"snmp\": \"https://www.ietf.org/rfc/rfc3411#\",\n    \"ice\": \"https://www.ietf.org/rfc/rfc8445#\",\n    \"turn\": \"https://www.ietf.org/rfc/rfc8656#\",\n    \"tls\": \"https://www.ietf.org/rfc/rfc8446#\",\n    \"dns\": \"https://www.ietf.org/rfc/rfc1035#\",\n    \"ntp\": \"https://www.ietf.org/rfc/rfc5905#\",\n\n    \"ExpresswaySystem\": {\n      \"@id\": \"cisco:ExpresswaySystem\",\n      \"@type\": \"@id\",\n      \"description\": \"A Cisco Expressway session border controller node providing firewall traversal and collaboration services\"\n    },\n    \"SystemName\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\",\n      \"description\": \"Name assigned to the Expressway node\"\n    },\n    \"SoftwareVersion\"\
  : {\n      \"@id\": \"schema:softwareVersion\",\n      \"@type\": \"xsd:string\",\n      \"description\": \"Currently installed software version\"\n    },\n    \"SerialNumber\": {\n      \"@id\": \"schema:serialNumber\",\n      \"@type\": \"xsd:string\",\n      \"description\": \"Hardware or VM serial number\"\n    },\n    \"IPv4Address\": {\n      \"@id\": \"cisco:ipv4Address\",\n      \"@type\": \"xsd:string\",\n      \"description\": \"IPv4 network address of the Expressway\"\n    },\n    \"IPv6Address\": {\n      \"@id\": \"cisco:ipv6Address\",\n      \"@type\": \"xsd:string\",\n      \"description\": \"IPv6 network address of the Expressway\"\n    },\n    \"Uptime\": {\n      \"@id\": \"cisco:uptime\",\n      \"@type\": \"xsd:string\",\n      \"description\": \"Time elapsed since last restart\"\n    },\n\n    \"Zone\": {\n      \"@id\": \"cisco:Zone\",\n      \"@type\": \"@id\",\n      \"description\": \"A zone defining a connection to an external system for call routing and firewall\
  \ traversal\"\n    },\n    \"NeighborZone\": {\n      \"@id\": \"cisco:NeighborZone\",\n      \"@type\": \"@id\",\n      \"description\": \"A zone connecting to a neighboring system such as another Expressway or Unified CM\"\n    },\n    \"TraversalServerZone\": {\n      \"@id\": \"cisco:TraversalServerZone\",\n      \"@type\": \"@id\",\n      \"description\": \"A zone providing firewall traversal services on Expressway-E\"\n    },\n    \"TraversalClientZone\": {\n      \"@id\": \"cisco:TraversalClientZone\",\n      \"@type\": \"@id\",\n      \"description\": \"A zone connecting to a traversal server across a firewall from Expressway-C\"\n    },\n    \"DNSZone\": {\n      \"@id\": \"cisco:DNSZone\",\n      \"@type\": \"@id\",\n      \"description\": \"A zone enabling endpoint discovery through DNS lookups\"\n    },\n    \"ENUMZone\": {\n      \"@id\": \"cisco:ENUMZone\",\n      \"@type\": \"@id\",\n      \"description\": \"A zone enabling endpoint discovery through ENUM DNS lookups\"\n\
  \    },\n    \"ZoneName\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"HopCount\": {\n      \"@id\": \"cisco:hopCount\",\n      \"@type\": \"xsd:integer\",\n      \"description\": \"Maximum forwarding iterations for a search request\"\n    },\n    \"PeerAddress\": {\n      \"@id\": \"cisco:peerAddress\",\n      \"@type\": \"xsd:string\",\n      \"description\": \"Address of a connected peer system\"\n    },\n    \"MediaEncryptionMode\": {\n      \"@id\": \"cisco:mediaEncryptionMode\",\n      \"@type\": \"xsd:string\",\n      \"description\": \"Media encryption enforcement mode for calls\"\n    },\n\n    \"SearchRule\": {\n      \"@id\": \"cisco:SearchRule\",\n      \"@type\": \"@id\",\n      \"description\": \"A rule defining how search requests are routed to target zones based on alias pattern matching\"\n    },\n    \"AliasPatternType\": {\n      \"@id\": \"cisco:aliasPatternType\",\n      \"@type\": \"xsd:string\",\n      \"description\": \"Pattern\
  \ matching type: Prefix, Suffix, Regex, or Exact\"\n    },\n    \"AliasPatternString\": {\n      \"@id\": \"cisco:aliasPatternString\",\n      \"@type\": \"xsd:string\",\n      \"description\": \"Pattern to match against destination alias\"\n    },\n    \"TargetZone\": {\n      \"@id\": \"cisco:targetZone\",\n      \"@type\": \"@id\",\n      \"description\": \"Zone to which matching requests are forwarded\"\n    },\n    \"Priority\": {\n      \"@id\": \"cisco:priority\",\n      \"@type\": \"xsd:integer\",\n      \"description\": \"Evaluation priority where lower numbers are processed first\"\n    },\n\n    \"Transform\": {\n      \"@id\": \"cisco:Transform\",\n      \"@type\": \"@id\",\n      \"description\": \"A pre-search transform that modifies destination aliases before routing\"\n    },\n    \"PatternType\": {\n      \"@id\": \"cisco:patternType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PatternString\": {\n      \"@id\": \"cisco:patternString\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"ReplaceString\": {\n      \"@id\": \"cisco:replaceString\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"Call\": {\n      \"@id\": \"cisco:Call\",\n      \"@type\": \"@id\",\n      \"description\": \"A voice or video call traversing the Expressway\"\n    },\n    \"SourceAlias\": {\n      \"@id\": \"cisco:sourceAlias\",\n      \"@type\": \"xsd:string\",\n      \"description\": \"Alias of the calling endpoint\"\n    },\n    \"DestinationAlias\": {\n      \"@id\": \"cisco:destinationAlias\",\n      \"@type\": \"xsd:string\",\n      \"description\": \"Alias of the called endpoint\"\n    },\n    \"CallType\": {\n      \"@id\": \"cisco:callType\",\n      \"@type\": \"xsd:string\",\n      \"description\": \"Protocol type of the call: SIP, H.323, or Interworked\"\n    },\n    \"StartTime\": {\n      \"@id\": \"schema:startDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"EndTime\": {\n      \"@id\": \"schema:endDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n \
  \   \"Duration\": {\n      \"@id\": \"schema:duration\",\n      \"@type\": \"xsd:integer\"\n    },\n\n    \"Registration\": {\n      \"@id\": \"cisco:Registration\",\n      \"@type\": \"@id\",\n      \"description\": \"A device registration with the Expressway\"\n    },\n    \"DeviceType\": {\n      \"@id\": \"cisco:deviceType\",\n      \"@type\": \"xsd:string\",\n      \"description\": \"Type or model of the registered device\"\n    },\n    \"ContactAddress\": {\n      \"@id\": \"cisco:contactAddress\",\n      \"@type\": \"xsd:string\",\n      \"description\": \"Network contact address including IP and port\"\n    },\n    \"Subzone\": {\n      \"@id\": \"cisco:subzone\",\n      \"@type\": \"xsd:string\",\n      \"description\": \"Subzone assignment for the registered device\"\n    },\n\n    \"Alarm\": {\n      \"@id\": \"cisco:Alarm\",\n      \"@type\": \"@id\",\n      \"description\": \"A system alarm indicating a condition requiring attention\"\n    },\n    \"AlarmId\": {\n      \"\
  @id\": \"schema:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Severity\": {\n      \"@id\": \"cisco:severity\",\n      \"@type\": \"xsd:string\",\n      \"description\": \"Alarm severity: Critical, Warning, or Information\"\n    },\n    \"Title\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TimeRaised\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n\n    \"DnsServer\": {\n      \"@id\": \"cisco:DnsServer\",\n      \"@type\": \"@id\",\n      \"description\": \"A DNS server configured on the Expressway\"\n    },\n    \"NtpServer\": {\n      \"@id\": \"cisco:NtpServer\",\n      \"@type\": \"@id\",\n      \"description\": \"An NTP server configured for time synchronization\"\n    },\n    \"Address\": {\n      \"@id\": \"cisco:address\",\n      \"@type\": \"xsd:string\",\n      \"description\"\
  : \"IP address or hostname\"\n    },\n\n    \"SmartLicense\": {\n      \"@id\": \"cisco:SmartLicense\",\n      \"@type\": \"@id\",\n      \"description\": \"Cisco Smart Licensing status and entitlement information\"\n    },\n    \"RegistrationStatus\": {\n      \"@id\": \"cisco:registrationStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AuthorizationStatus\": {\n      \"@id\": \"cisco:authorizationStatus\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"TurnRelay\": {\n      \"@id\": \"cisco:TurnRelay\",\n      \"@type\": \"@id\",\n      \"description\": \"An active TURN relay allocation for media traversal\"\n    },\n\n    \"SIPConfiguration\": {\n      \"@id\": \"cisco:SIPConfiguration\",\n      \"@type\": \"@id\",\n      \"description\": \"SIP protocol configuration settings\"\n    },\n    \"SIPMode\": {\n      \"@id\": \"sip:sipMode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"H323Mode\": {\n      \"@id\": \"uc:h323Mode\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/cisco-expressway/refs/heads/main/json-ld/cisco-expressway-context.jsonld
tags:
- Collaboration
- Firewall Traversal
- H.323
- Session Border Controller
- SIP
- Unified Communications
- Video Conferencing
- JSON-LD
- Linked Data
- Semantic Web
---
