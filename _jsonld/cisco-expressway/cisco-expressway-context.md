---
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
