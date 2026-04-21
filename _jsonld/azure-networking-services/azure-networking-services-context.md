---
class_count: 21
classes:
- AddressSpace
- Delegation
- DhcpOptions
- IPAddressAvailabilityResult
- NetworkIntentPolicy
- NetworkIntentPolicyConfiguration
- PrepareNetworkPoliciesRequest
- ResourceNavigationLink
- ResourceNavigationLinkFormat
- ResourceNavigationLinksListResult
- ServiceAssociationLink
- ServiceAssociationLinkPropertiesFormat
- ServiceAssociationLinksListResult
- ServiceDelegationPropertiesFormat
- ServiceEndpointPropertiesFormat
- Subnet
- SubnetListResult
- SubnetPropertiesFormat
- UnprepareNetworkPoliciesRequest
- VirtualNetwork
- name
context_file: json-ld/azure-networking-services-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/azure-networking-services/refs/heads/main/json-ld/azure-networking-services-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Azure Networking Services from Azure Networking Services.
layout: jsonld
name: Azure Networking Services Context
namespaces:
- prefix: azurenetworkingservices
  uri: https://azure.microsoft.com/azure-networking-services/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: set
  name: addressPrefixes
  type: string
- container: ''
  name: etag
  type: string
- container: ''
  name: properties
  type: string
- container: set
  name: dnsServers
  type: string
- container: ''
  name: available
  type: boolean
- container: set
  name: availableIPAddresses
  type: string
- container: ''
  name: networkIntentPolicyName
  type: string
- container: ''
  name: sourceNetworkIntentPolicy
  type: string
- container: set
  name: networkIntentPolicyConfigurations
  type: string
- container: ''
  name: serviceName
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: link
  type: string
- container: ''
  name: linkedResourceType
  type: string
- container: ''
  name: provisioningState
  type: string
- container: ''
  name: nextLink
  type: string
- container: set
  name: value
  type: string
- container: ''
  name: allowDelete
  type: boolean
- container: set
  name: locations
  type: string
- container: set
  name: actions
  type: string
- container: ''
  name: service
  type: string
- container: ''
  name: addressPrefix
  type: string
- container: set
  name: delegations
  type: string
- container: set
  name: ipConfigurationProfiles
  type: string
- container: set
  name: ipConfigurations
  type: string
- container: ''
  name: natGateway
  type: string
- container: ''
  name: networkSecurityGroup
  type: string
- container: ''
  name: privateEndpointNetworkPolicies
  type: string
- container: set
  name: privateEndpoints
  type: string
- container: ''
  name: privateLinkServiceNetworkPolicies
  type: string
- container: ''
  name: purpose
  type: string
- container: set
  name: resourceNavigationLinks
  type: string
- container: ''
  name: routeTable
  type: string
- container: set
  name: serviceAssociationLinks
  type: string
- container: set
  name: serviceEndpointPolicies
  type: string
- container: set
  name: serviceEndpoints
  type: string
property_count: 36
provider_name: Azure Networking Services
provider_slug: azure-networking-services
slug: azure-networking-services-context
tags:
- Azure
- Cloud
- Infrastructure
- Microsoft
- Networking
- JSON-LD
- Linked Data
- Semantic Web
---
