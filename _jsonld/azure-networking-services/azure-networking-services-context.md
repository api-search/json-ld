---
api_specs:
- filename: azure-networking-services-virtual-network-openapi.yaml
  format: yaml
  label: Azure Virtual Networks API
  slug: azure-virtual-networks-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/azure-networking-services/refs/heads/main/openapi/azure-networking-services-virtual-network-openapi.yaml
- filename: azure-networking-services-virtual-network-openapi.yaml
  format: yaml
  label: Azure Load Balancer API
  slug: azure-load-balancer-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/azure-networking-services/refs/heads/main/openapi/azure-networking-services-virtual-network-openapi.yaml
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
source_filename: azure-networking-services-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"azurenetworkingservices\": \"https://azure.microsoft.com/azure-networking-services/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AddressSpace\": \"azurenetworkingservices:AddressSpace\",\n    \"Delegation\": \"azurenetworkingservices:Delegation\",\n    \"DhcpOptions\": \"azurenetworkingservices:DhcpOptions\",\n    \"IPAddressAvailabilityResult\": \"azurenetworkingservices:IPAddressAvailabilityResult\",\n    \"NetworkIntentPolicy\": \"azurenetworkingservices:NetworkIntentPolicy\",\n    \"NetworkIntentPolicyConfiguration\": \"azurenetworkingservices:NetworkIntentPolicyConfiguration\",\n    \"PrepareNetworkPoliciesRequest\": \"azurenetworkingservices:PrepareNetworkPoliciesRequest\",\n    \"ResourceNavigationLink\": \"azurenetworkingservices:ResourceNavigationLink\",\n    \"ResourceNavigationLinkFormat\": \"azurenetworkingservices:ResourceNavigationLinkFormat\"\
  ,\n    \"ResourceNavigationLinksListResult\": \"azurenetworkingservices:ResourceNavigationLinksListResult\",\n    \"ServiceAssociationLink\": \"azurenetworkingservices:ServiceAssociationLink\",\n    \"ServiceAssociationLinkPropertiesFormat\": \"azurenetworkingservices:ServiceAssociationLinkPropertiesFormat\",\n    \"ServiceAssociationLinksListResult\": \"azurenetworkingservices:ServiceAssociationLinksListResult\",\n    \"ServiceDelegationPropertiesFormat\": \"azurenetworkingservices:ServiceDelegationPropertiesFormat\",\n    \"ServiceEndpointPropertiesFormat\": \"azurenetworkingservices:ServiceEndpointPropertiesFormat\",\n    \"Subnet\": \"azurenetworkingservices:Subnet\",\n    \"SubnetListResult\": \"azurenetworkingservices:SubnetListResult\",\n    \"SubnetPropertiesFormat\": \"azurenetworkingservices:SubnetPropertiesFormat\",\n    \"UnprepareNetworkPoliciesRequest\": \"azurenetworkingservices:UnprepareNetworkPoliciesRequest\",\n    \"VirtualNetwork\": \"azurenetworkingservices:VirtualNetwork\"\
  ,\n    \"addressPrefixes\": {\n      \"@id\": \"azurenetworkingservices:addressPrefixes\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"etag\": {\n      \"@id\": \"azurenetworkingservices:etag\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"properties\": {\n      \"@id\": \"azurenetworkingservices:properties\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dnsServers\": {\n      \"@id\": \"azurenetworkingservices:dnsServers\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"available\": {\n      \"@id\": \"azurenetworkingservices:available\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"availableIPAddresses\": {\n      \"@id\": \"azurenetworkingservices:availableIPAddresses\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"networkIntentPolicyName\": {\n      \"@id\": \"azurenetworkingservices:networkIntentPolicyName\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"sourceNetworkIntentPolicy\": {\n      \"@id\": \"azurenetworkingservices:sourceNetworkIntentPolicy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"networkIntentPolicyConfigurations\": {\n      \"@id\": \"azurenetworkingservices:networkIntentPolicyConfigurations\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"serviceName\": {\n      \"@id\": \"azurenetworkingservices:serviceName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"azurenetworkingservices:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"azurenetworkingservices:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"link\": {\n      \"@id\": \"azurenetworkingservices:link\",\n      \"@type\": \"xsd:string\"\n    },\n    \"linkedResourceType\": {\n      \"@id\": \"azurenetworkingservices:linkedResourceType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"provisioningState\": {\n      \"@id\": \"azurenetworkingservices:provisioningState\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"nextLink\": {\n      \"@id\": \"azurenetworkingservices:nextLink\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"azurenetworkingservices:value\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"allowDelete\": {\n      \"@id\": \"azurenetworkingservices:allowDelete\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"locations\": {\n      \"@id\": \"azurenetworkingservices:locations\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"actions\": {\n      \"@id\": \"azurenetworkingservices:actions\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"service\": {\n      \"@id\": \"azurenetworkingservices:service\",\n      \"@type\": \"xsd:string\"\n    },\n    \"addressPrefix\": {\n      \"@id\": \"azurenetworkingservices:addressPrefix\",\n      \"@type\": \"xsd:string\"\n    },\n    \"delegations\": {\n      \"@id\"\
  : \"azurenetworkingservices:delegations\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ipConfigurationProfiles\": {\n      \"@id\": \"azurenetworkingservices:ipConfigurationProfiles\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ipConfigurations\": {\n      \"@id\": \"azurenetworkingservices:ipConfigurations\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"natGateway\": {\n      \"@id\": \"azurenetworkingservices:natGateway\",\n      \"@type\": \"xsd:string\"\n    },\n    \"networkSecurityGroup\": {\n      \"@id\": \"azurenetworkingservices:networkSecurityGroup\",\n      \"@type\": \"xsd:string\"\n    },\n    \"privateEndpointNetworkPolicies\": {\n      \"@id\": \"azurenetworkingservices:privateEndpointNetworkPolicies\",\n      \"@type\": \"xsd:string\"\n    },\n    \"privateEndpoints\": {\n      \"@id\": \"azurenetworkingservices:privateEndpoints\",\n      \"@container\": \"@set\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"privateLinkServiceNetworkPolicies\": {\n      \"@id\": \"azurenetworkingservices:privateLinkServiceNetworkPolicies\",\n      \"@type\": \"xsd:string\"\n    },\n    \"purpose\": {\n      \"@id\": \"azurenetworkingservices:purpose\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resourceNavigationLinks\": {\n      \"@id\": \"azurenetworkingservices:resourceNavigationLinks\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"routeTable\": {\n      \"@id\": \"azurenetworkingservices:routeTable\",\n      \"@type\": \"xsd:string\"\n    },\n    \"serviceAssociationLinks\": {\n      \"@id\": \"azurenetworkingservices:serviceAssociationLinks\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"serviceEndpointPolicies\": {\n      \"@id\": \"azurenetworkingservices:serviceEndpointPolicies\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"serviceEndpoints\"\
  : {\n      \"@id\": \"azurenetworkingservices:serviceEndpoints\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/azure-networking-services/refs/heads/main/json-ld/azure-networking-services-context.jsonld
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
