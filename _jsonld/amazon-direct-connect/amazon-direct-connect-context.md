---
api_specs:
- filename: amazon-direct-connect-openapi.yaml
  format: yaml
  label: Amazon Direct Connect API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-direct-connect/refs/heads/main/openapi/amazon-direct-connect-openapi.yaml
class_count: 19
classes:
- AssociatedGateway
- BGPPeer
- Connection
- CustomerAgreement
- DirectConnectGateway
- DirectConnectGatewayAssociation
- DirectConnectGatewayAttachment
- Interconnect
- Lag
- Location
- NewPrivateVirtualInterface
- NewPublicVirtualInterface
- NewTransitVirtualInterface
- ResourceTag
- RouteFilterPrefix
- Tag
- VirtualGateway
- VirtualInterface
- VirtualInterfaceTestHistory
context_file: json-ld/amazon-direct-connect-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-direct-connect/refs/heads/main/json-ld/amazon-direct-connect-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Direct Connect from Amazon Direct Connect.
layout: jsonld
name: Amazon Direct Connect Context
namespaces:
- prefix: amz
  uri: https://amazonaws.com/direct-connect/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: addressFamily
  type: string
- container: ''
  name: agreementName
  type: string
- container: ''
  name: allowedPrefixesToDirectConnectGateway
  type: string
- container: ''
  name: allowsHostedConnections
  type: string
- container: ''
  name: amazonAddress
  type: string
- container: ''
  name: amazonSideAsn
  type: string
- container: ''
  name: asn
  type: string
- container: ''
  name: associatedGateway
  type: string
- container: ''
  name: associationId
  type: string
- container: ''
  name: associationState
  type: string
- container: ''
  name: attachmentState
  type: string
- container: ''
  name: attachmentType
  type: string
- container: ''
  name: authKey
  type: string
- container: ''
  name: availableMacSecPortSpeeds
  type: string
- container: ''
  name: availablePortSpeeds
  type: string
- container: ''
  name: availableProviders
  type: string
- container: ''
  name: awsDevice
  type: string
- container: ''
  name: awsDeviceV2
  type: string
- container: ''
  name: awsLogicalDeviceId
  type: string
- container: ''
  name: bandwidth
  type: string
- container: ''
  name: bgpPeerId
  type: string
- container: ''
  name: bgpPeerState
  type: string
- container: ''
  name: bgpPeers
  type: string
- container: ''
  name: bgpStatus
  type: string
- container: ''
  name: cidr
  type: string
- container: ''
  name: connectionId
  type: string
- container: ''
  name: connectionName
  type: string
- container: ''
  name: connectionState
  type: string
- container: ''
  name: connections
  type: string
- container: ''
  name: connectionsBandwidth
  type: string
- container: ''
  name: customerAddress
  type: string
- container: ''
  name: customerRouterConfig
  type: string
- container: ''
  name: directConnectGatewayId
  type: string
- container: ''
  name: directConnectGatewayName
  type: string
- container: ''
  name: directConnectGatewayOwnerAccount
  type: string
- container: ''
  name: directConnectGatewayState
  type: string
- container: ''
  name: enableSiteLink
  type: string
- container: ''
  name: encryptionMode
  type: string
- container: ''
  name: endTime
  type: string
- container: ''
  name: hasLogicalRedundancy
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: interconnectId
  type: string
- container: ''
  name: interconnectName
  type: string
- container: ''
  name: interconnectState
  type: string
- container: ''
  name: jumboFrameCapable
  type: string
- container: ''
  name: key
  type: string
- container: ''
  name: lagId
  type: string
- container: ''
  name: lagName
  type: string
- container: ''
  name: lagState
  type: string
- container: ''
  name: loaIssueTime
  type: string
- container: ''
  name: location
  type: string
- container: ''
  name: locationCode
  type: string
- container: ''
  name: locationName
  type: string
- container: ''
  name: macSecCapable
  type: string
- container: ''
  name: macSecKeys
  type: string
- container: ''
  name: minimumLinks
  type: string
- container: ''
  name: mtu
  type: string
- container: ''
  name: numberOfConnections
  type: string
- container: ''
  name: ownerAccount
  type: string
- container: ''
  name: partnerName
  type: string
- container: ''
  name: portEncryptionStatus
  type: string
- container: ''
  name: providerName
  type: string
- container: ''
  name: region
  type: string
- container: ''
  name: resourceArn
  type: string
- container: ''
  name: routeFilterPrefixes
  type: string
- container: ''
  name: siteLinkEnabled
  type: string
- container: ''
  name: startTime
  type: string
- container: ''
  name: stateChangeError
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: tags
  type: string
- container: ''
  name: testDurationInMinutes
  type: string
- container: ''
  name: testId
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: value
  type: string
- container: ''
  name: virtualGatewayId
  type: string
- container: ''
  name: virtualGatewayOwnerAccount
  type: string
- container: ''
  name: virtualGatewayRegion
  type: string
- container: ''
  name: virtualGatewayState
  type: string
- container: ''
  name: virtualInterfaceId
  type: string
- container: ''
  name: virtualInterfaceName
  type: string
- container: ''
  name: virtualInterfaceOwnerAccount
  type: string
- container: ''
  name: virtualInterfaceRegion
  type: string
- container: ''
  name: virtualInterfaceState
  type: string
- container: ''
  name: virtualInterfaceType
  type: string
- container: ''
  name: vlan
  type: string
property_count: 85
provider_name: Amazon Direct Connect
provider_slug: amazon-direct-connect
slug: amazon-direct-connect-context
source_filename: amazon-direct-connect-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"amz\": \"https://amazonaws.com/direct-connect/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AssociatedGateway\": \"amz:AssociatedGateway\",\n    \"BGPPeer\": \"amz:BGPPeer\",\n    \"Connection\": \"amz:Connection\",\n    \"CustomerAgreement\": \"amz:CustomerAgreement\",\n    \"DirectConnectGateway\": \"amz:DirectConnectGateway\",\n    \"DirectConnectGatewayAssociation\": \"amz:DirectConnectGatewayAssociation\",\n    \"DirectConnectGatewayAttachment\": \"amz:DirectConnectGatewayAttachment\",\n    \"Interconnect\": \"amz:Interconnect\",\n    \"Lag\": \"amz:Lag\",\n    \"Location\": \"amz:Location\",\n    \"NewPrivateVirtualInterface\": \"amz:NewPrivateVirtualInterface\",\n    \"NewPublicVirtualInterface\": \"amz:NewPublicVirtualInterface\",\n    \"NewTransitVirtualInterface\": \"amz:NewTransitVirtualInterface\"\
  ,\n    \"ResourceTag\": \"amz:ResourceTag\",\n    \"RouteFilterPrefix\": \"amz:RouteFilterPrefix\",\n    \"Tag\": \"amz:Tag\",\n    \"VirtualGateway\": \"amz:VirtualGateway\",\n    \"VirtualInterface\": \"amz:VirtualInterface\",\n    \"VirtualInterfaceTestHistory\": \"amz:VirtualInterfaceTestHistory\",\n    \"addressFamily\": {\n      \"@id\": \"amz:addressFamily\",\n      \"@type\": \"xsd:string\"\n    },\n    \"agreementName\": {\n      \"@id\": \"amz:agreementName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"allowedPrefixesToDirectConnectGateway\": {\n      \"@id\": \"amz:allowedPrefixesToDirectConnectGateway\",\n      \"@type\": \"xsd:string\"\n    },\n    \"allowsHostedConnections\": {\n      \"@id\": \"amz:allowsHostedConnections\",\n      \"@type\": \"xsd:string\"\n    },\n    \"amazonAddress\": {\n      \"@id\": \"amz:amazonAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"amazonSideAsn\": {\n      \"@id\": \"amz:amazonSideAsn\",\n      \"@type\": \"xsd:string\"\n\
  \    },\n    \"asn\": {\n      \"@id\": \"amz:asn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"associatedGateway\": {\n      \"@id\": \"amz:associatedGateway\",\n      \"@type\": \"xsd:string\"\n    },\n    \"associationId\": {\n      \"@id\": \"amz:associationId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"associationState\": {\n      \"@id\": \"amz:associationState\",\n      \"@type\": \"xsd:string\"\n    },\n    \"attachmentState\": {\n      \"@id\": \"amz:attachmentState\",\n      \"@type\": \"xsd:string\"\n    },\n    \"attachmentType\": {\n      \"@id\": \"amz:attachmentType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"authKey\": {\n      \"@id\": \"amz:authKey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"availableMacSecPortSpeeds\": {\n      \"@id\": \"amz:availableMacSecPortSpeeds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"availablePortSpeeds\": {\n      \"@id\": \"amz:availablePortSpeeds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"availableProviders\"\
  : {\n      \"@id\": \"amz:availableProviders\",\n      \"@type\": \"xsd:string\"\n    },\n    \"awsDevice\": {\n      \"@id\": \"amz:awsDevice\",\n      \"@type\": \"xsd:string\"\n    },\n    \"awsDeviceV2\": {\n      \"@id\": \"amz:awsDeviceV2\",\n      \"@type\": \"xsd:string\"\n    },\n    \"awsLogicalDeviceId\": {\n      \"@id\": \"amz:awsLogicalDeviceId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bandwidth\": {\n      \"@id\": \"amz:bandwidth\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bgpPeerId\": {\n      \"@id\": \"amz:bgpPeerId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bgpPeerState\": {\n      \"@id\": \"amz:bgpPeerState\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bgpPeers\": {\n      \"@id\": \"amz:bgpPeers\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bgpStatus\": {\n      \"@id\": \"amz:bgpStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cidr\": {\n      \"@id\": \"amz:cidr\",\n      \"@type\": \"xsd:string\"\n    },\n    \"connectionId\"\
  : {\n      \"@id\": \"amz:connectionId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"connectionName\": {\n      \"@id\": \"amz:connectionName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"connectionState\": {\n      \"@id\": \"amz:connectionState\",\n      \"@type\": \"xsd:string\"\n    },\n    \"connections\": {\n      \"@id\": \"amz:connections\",\n      \"@type\": \"xsd:string\"\n    },\n    \"connectionsBandwidth\": {\n      \"@id\": \"amz:connectionsBandwidth\",\n      \"@type\": \"xsd:string\"\n    },\n    \"customerAddress\": {\n      \"@id\": \"amz:customerAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"customerRouterConfig\": {\n      \"@id\": \"amz:customerRouterConfig\",\n      \"@type\": \"xsd:string\"\n    },\n    \"directConnectGatewayId\": {\n      \"@id\": \"amz:directConnectGatewayId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"directConnectGatewayName\": {\n      \"@id\": \"amz:directConnectGatewayName\",\n      \"@type\": \"xsd:string\"\n \
  \   },\n    \"directConnectGatewayOwnerAccount\": {\n      \"@id\": \"amz:directConnectGatewayOwnerAccount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"directConnectGatewayState\": {\n      \"@id\": \"amz:directConnectGatewayState\",\n      \"@type\": \"xsd:string\"\n    },\n    \"enableSiteLink\": {\n      \"@id\": \"amz:enableSiteLink\",\n      \"@type\": \"xsd:string\"\n    },\n    \"encryptionMode\": {\n      \"@id\": \"amz:encryptionMode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"endTime\": {\n      \"@id\": \"amz:endTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"hasLogicalRedundancy\": {\n      \"@id\": \"amz:hasLogicalRedundancy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"amz:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"interconnectId\": {\n      \"@id\": \"amz:interconnectId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"interconnectName\": {\n      \"@id\": \"amz:interconnectName\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"interconnectState\": {\n      \"@id\": \"amz:interconnectState\",\n      \"@type\": \"xsd:string\"\n    },\n    \"jumboFrameCapable\": {\n      \"@id\": \"amz:jumboFrameCapable\",\n      \"@type\": \"xsd:string\"\n    },\n    \"key\": {\n      \"@id\": \"amz:key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lagId\": {\n      \"@id\": \"amz:lagId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lagName\": {\n      \"@id\": \"amz:lagName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lagState\": {\n      \"@id\": \"amz:lagState\",\n      \"@type\": \"xsd:string\"\n    },\n    \"loaIssueTime\": {\n      \"@id\": \"amz:loaIssueTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"location\": {\n      \"@id\": \"amz:location\",\n      \"@type\": \"xsd:string\"\n    },\n    \"locationCode\": {\n      \"@id\": \"amz:locationCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"locationName\": {\n      \"@id\": \"amz:locationName\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"macSecCapable\": {\n      \"@id\": \"amz:macSecCapable\",\n      \"@type\": \"xsd:string\"\n    },\n    \"macSecKeys\": {\n      \"@id\": \"amz:macSecKeys\",\n      \"@type\": \"xsd:string\"\n    },\n    \"minimumLinks\": {\n      \"@id\": \"amz:minimumLinks\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mtu\": {\n      \"@id\": \"amz:mtu\",\n      \"@type\": \"xsd:string\"\n    },\n    \"numberOfConnections\": {\n      \"@id\": \"amz:numberOfConnections\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ownerAccount\": {\n      \"@id\": \"amz:ownerAccount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"partnerName\": {\n      \"@id\": \"amz:partnerName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"portEncryptionStatus\": {\n      \"@id\": \"amz:portEncryptionStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"providerName\": {\n      \"@id\": \"amz:providerName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"region\": {\n      \"@id\": \"amz:region\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"resourceArn\": {\n      \"@id\": \"amz:resourceArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"routeFilterPrefixes\": {\n      \"@id\": \"amz:routeFilterPrefixes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"siteLinkEnabled\": {\n      \"@id\": \"amz:siteLinkEnabled\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startTime\": {\n      \"@id\": \"amz:startTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stateChangeError\": {\n      \"@id\": \"amz:stateChangeError\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"amz:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tags\": {\n      \"@id\": \"amz:tags\",\n      \"@type\": \"xsd:string\"\n    },\n    \"testDurationInMinutes\": {\n      \"@id\": \"amz:testDurationInMinutes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"testId\": {\n      \"@id\": \"amz:testId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n    \
  \  \"@id\": \"amz:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"amz:value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"virtualGatewayId\": {\n      \"@id\": \"amz:virtualGatewayId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"virtualGatewayOwnerAccount\": {\n      \"@id\": \"amz:virtualGatewayOwnerAccount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"virtualGatewayRegion\": {\n      \"@id\": \"amz:virtualGatewayRegion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"virtualGatewayState\": {\n      \"@id\": \"amz:virtualGatewayState\",\n      \"@type\": \"xsd:string\"\n    },\n    \"virtualInterfaceId\": {\n      \"@id\": \"amz:virtualInterfaceId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"virtualInterfaceName\": {\n      \"@id\": \"amz:virtualInterfaceName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"virtualInterfaceOwnerAccount\": {\n      \"@id\": \"amz:virtualInterfaceOwnerAccount\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"virtualInterfaceRegion\": {\n      \"@id\": \"amz:virtualInterfaceRegion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"virtualInterfaceState\": {\n      \"@id\": \"amz:virtualInterfaceState\",\n      \"@type\": \"xsd:string\"\n    },\n    \"virtualInterfaceType\": {\n      \"@id\": \"amz:virtualInterfaceType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"vlan\": {\n      \"@id\": \"amz:vlan\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-direct-connect/refs/heads/main/json-ld/amazon-direct-connect-context.jsonld
tags:
- AWS
- Dedicated Connection
- Direct Connect
- Hybrid Cloud
- Networking
- JSON-LD
- Linked Data
- Semantic Web
---
