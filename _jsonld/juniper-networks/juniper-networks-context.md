---
api_specs:
- filename: juniper-networks-apstra-openapi.yml
  format: yaml
  label: Juniper Apstra API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/juniper-networks/refs/heads/main/openapi/juniper-networks-apstra-openapi.yml
- filename: juniper-networks-junos-telemetry-asyncapi.yml
  format: yaml
  label: Junos XML API
  slug: ''
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/juniper-networks/refs/heads/main/asyncapi/juniper-networks-junos-telemetry-asyncapi.yml
- filename: juniper-networks-mist-openapi.yml
  format: yaml
  label: Juniper Mist API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/juniper-networks/refs/heads/main/openapi/juniper-networks-mist-openapi.yml
- filename: juniper-networks-contrail-openapi.yml
  format: yaml
  label: Juniper Contrail API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/juniper-networks/refs/heads/main/openapi/juniper-networks-contrail-openapi.yml
- filename: juniper-networks-junos-space-openapi.yml
  format: yaml
  label: Junos Space REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/juniper-networks/refs/heads/main/openapi/juniper-networks-junos-space-openapi.yml
- filename: juniper-networks-vsrx-openapi.yml
  format: yaml
  label: Juniper vSRX REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/juniper-networks/refs/heads/main/openapi/juniper-networks-vsrx-openapi.yml
class_count: 85
classes:
- ietf
- Organization
- Site
- Device
- AccessPoint
- Switch
- Gateway
- Router
- Firewall
- Blueprint
- VirtualNetwork
- SecurityPolicy
- SecurityZone
- NetworkPolicy
- WirelessLAN
- ClientSession
- Alarm
- Anomaly
- TelemetryStream
- InterfaceStats
- BgpPeer
- IpsecVpn
- NatRule
- ResourcePool
- RackType
- Template
- MarvisAction
- name
- description
- dateCreated
- dateModified
- identifier
- status
- severity
- siteId
- orgId
- deviceId
- macAddress
- serialNumber
- ipAddress
- firmwareVersion
- deviceModel
- deviceType
- ssid
- band
- channel
- rssi
- signalToNoise
- txRate
- rxRate
- blueprintId
- blueprintVersion
- design
- anomalyType
- expectedState
- actualState
- vxlanVni
- routeTarget
- forwardingMode
- subnet
- gateway
- fromZone
- toZone
- sourceAddress
- destinationAddress
- application
- action
- ikeGateway
- tunnelInterface
- encryptionAlgorithm
- interfaceName
- ingressPackets
- egressPackets
- ingressBytes
- egressBytes
- operationalState
- peerAddress
- peerAs
- localAs
- receivedPrefixes
- advertisedPrefixes
- latitude
- longitude
- timezone
- countryCode
context_file: json-ld/juniper-networks-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/juniper-networks/refs/heads/main/json-ld/juniper-networks-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Juniper Networks from Juniper Networks.
layout: jsonld
name: Juniper Networks Context
namespaces:
- prefix: juniper
  uri: https://www.juniper.net/documentation/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: mist
  uri: https://api.mist.com/api/v1/
- prefix: apstra
  uri: https://www.juniper.net/documentation/product/us/en/juniper-apstra/schema/
properties:
- container: ''
  name: url
  type: reference
- container: ''
  name: belongsToSite
  type: reference
- container: ''
  name: belongsToOrg
  type: reference
- container: ''
  name: assignedDevice
  type: reference
- container: ''
  name: connectedTo
  type: reference
- container: ''
  name: managedBy
  type: reference
- container: ''
  name: deployedFrom
  type: reference
- container: ''
  name: detectedAnomaly
  type: reference
property_count: 8
provider_name: Juniper Networks
provider_slug: juniper-networks
slug: juniper-networks-context
source_filename: juniper-networks-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"juniper\": \"https://www.juniper.net/documentation/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"mist\": \"https://api.mist.com/api/v1/\",\n    \"apstra\": \"https://www.juniper.net/documentation/product/us/en/juniper-apstra/schema/\",\n    \"ietf\": \"urn:ietf:params:xml:ns:yang:\",\n\n    \"Organization\": \"schema:Organization\",\n    \"Site\": \"juniper:Site\",\n    \"Device\": \"juniper:Device\",\n    \"AccessPoint\": \"juniper:AccessPoint\",\n    \"Switch\": \"juniper:Switch\",\n    \"Gateway\": \"juniper:Gateway\",\n    \"Router\": \"juniper:Router\",\n    \"Firewall\": \"juniper:Firewall\",\n    \"Blueprint\": \"apstra:Blueprint\",\n    \"VirtualNetwork\": \"juniper:VirtualNetwork\",\n    \"SecurityPolicy\": \"juniper:SecurityPolicy\",\n    \"SecurityZone\": \"juniper:SecurityZone\",\n    \"NetworkPolicy\": \"juniper:NetworkPolicy\",\n    \"WirelessLAN\": \"juniper:WirelessLAN\",\n    \"ClientSession\"\
  : \"juniper:ClientSession\",\n    \"Alarm\": \"juniper:Alarm\",\n    \"Anomaly\": \"apstra:Anomaly\",\n    \"TelemetryStream\": \"juniper:TelemetryStream\",\n    \"InterfaceStats\": \"juniper:InterfaceStats\",\n    \"BgpPeer\": \"juniper:BgpPeer\",\n    \"IpsecVpn\": \"juniper:IpsecVpn\",\n    \"NatRule\": \"juniper:NatRule\",\n    \"ResourcePool\": \"apstra:ResourcePool\",\n    \"RackType\": \"apstra:RackType\",\n    \"Template\": \"apstra:Template\",\n    \"MarvisAction\": \"mist:MarvisAction\",\n\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": {\"@id\": \"schema:url\", \"@type\": \"@id\"},\n    \"dateCreated\": \"schema:dateCreated\",\n    \"dateModified\": \"schema:dateModified\",\n    \"identifier\": \"schema:identifier\",\n    \"status\": \"juniper:status\",\n    \"severity\": \"juniper:severity\",\n\n    \"siteId\": \"juniper:siteId\",\n    \"orgId\": \"juniper:orgId\",\n    \"deviceId\": \"juniper:deviceId\",\n    \"macAddress\": \"juniper:macAddress\"\
  ,\n    \"serialNumber\": \"juniper:serialNumber\",\n    \"ipAddress\": \"juniper:ipAddress\",\n    \"firmwareVersion\": \"juniper:firmwareVersion\",\n    \"deviceModel\": \"juniper:deviceModel\",\n    \"deviceType\": \"juniper:deviceType\",\n\n    \"ssid\": \"juniper:ssid\",\n    \"band\": \"juniper:band\",\n    \"channel\": \"juniper:channel\",\n    \"rssi\": \"juniper:rssi\",\n    \"signalToNoise\": \"juniper:signalToNoise\",\n    \"txRate\": \"juniper:txRate\",\n    \"rxRate\": \"juniper:rxRate\",\n\n    \"blueprintId\": \"apstra:blueprintId\",\n    \"blueprintVersion\": \"apstra:blueprintVersion\",\n    \"design\": \"apstra:design\",\n    \"anomalyType\": \"apstra:anomalyType\",\n    \"expectedState\": \"apstra:expectedState\",\n    \"actualState\": \"apstra:actualState\",\n\n    \"vxlanVni\": \"juniper:vxlanVni\",\n    \"routeTarget\": \"juniper:routeTarget\",\n    \"forwardingMode\": \"juniper:forwardingMode\",\n    \"subnet\": \"juniper:subnet\",\n    \"gateway\": \"juniper:gateway\"\
  ,\n\n    \"fromZone\": \"juniper:fromZone\",\n    \"toZone\": \"juniper:toZone\",\n    \"sourceAddress\": \"juniper:sourceAddress\",\n    \"destinationAddress\": \"juniper:destinationAddress\",\n    \"application\": \"juniper:application\",\n    \"action\": \"juniper:action\",\n\n    \"ikeGateway\": \"juniper:ikeGateway\",\n    \"tunnelInterface\": \"juniper:tunnelInterface\",\n    \"encryptionAlgorithm\": \"juniper:encryptionAlgorithm\",\n\n    \"interfaceName\": \"juniper:interfaceName\",\n    \"ingressPackets\": \"juniper:ingressPackets\",\n    \"egressPackets\": \"juniper:egressPackets\",\n    \"ingressBytes\": \"juniper:ingressBytes\",\n    \"egressBytes\": \"juniper:egressBytes\",\n    \"operationalState\": \"juniper:operationalState\",\n\n    \"peerAddress\": \"juniper:peerAddress\",\n    \"peerAs\": \"juniper:peerAs\",\n    \"localAs\": \"juniper:localAs\",\n    \"receivedPrefixes\": \"juniper:receivedPrefixes\",\n    \"advertisedPrefixes\": \"juniper:advertisedPrefixes\",\n\n\
  \    \"latitude\": \"schema:latitude\",\n    \"longitude\": \"schema:longitude\",\n    \"timezone\": \"juniper:timezone\",\n    \"countryCode\": \"juniper:countryCode\",\n\n    \"belongsToSite\": {\"@id\": \"juniper:belongsToSite\", \"@type\": \"@id\"},\n    \"belongsToOrg\": {\"@id\": \"juniper:belongsToOrg\", \"@type\": \"@id\"},\n    \"assignedDevice\": {\"@id\": \"juniper:assignedDevice\", \"@type\": \"@id\"},\n    \"connectedTo\": {\"@id\": \"juniper:connectedTo\", \"@type\": \"@id\"},\n    \"managedBy\": {\"@id\": \"juniper:managedBy\", \"@type\": \"@id\"},\n    \"deployedFrom\": {\"@id\": \"apstra:deployedFrom\", \"@type\": \"@id\"},\n    \"detectedAnomaly\": {\"@id\": \"apstra:detectedAnomaly\", \"@type\": \"@id\"}\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/juniper-networks/refs/heads/main/json-ld/juniper-networks-context.jsonld
tags:
- Automation
- Cloud
- Data Center
- Enterprise
- Networking
- SDN
- Security
- JSON-LD
- Linked Data
- Semantic Web
---
