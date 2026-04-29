---
api_specs:
- filename: amazon-privatelink-openapi.yaml
  format: yaml
  label: AWS PrivateLink API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-privatelink/refs/heads/main/openapi/amazon-privatelink-openapi.yaml
class_count: 18
classes:
- RejectVpcEndpointConnectionsRequest
- DescribeVpcEndpointsResult
- VpcEndpoint
- CreateVpcEndpointServiceConfigurationResult
- ServiceConfiguration
- ModifyVpcEndpointServicePermissionsRequest
- CreateVpcEndpointServiceConfigurationRequest
- ModifyVpcEndpointRequest
- VpcEndpointConnection
- CreateVpcEndpointResult
- DeleteVpcEndpointServiceConfigurationsRequest
- DescribeVpcEndpointServicesResult
- AcceptVpcEndpointConnectionsRequest
- CreateVpcEndpointRequest
- DeleteVpcEndpointsRequest
- DescribeVpcEndpointConnectionsResult
- ModifyVpcEndpointServiceConfigurationRequest
- ServiceDetail
context_file: json-ld/amazon-privatelink-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-privatelink/refs/heads/main/json-ld/amazon-privatelink-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Privatelink from Amazon PrivateLink.
layout: jsonld
name: Amazon Privatelink Context
namespaces:
- prefix: pl
  uri: https://ec2.amazonaws.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: ServiceId
  type: string
- container: set
  name: VpcEndpointId
  type: string
- container: set
  name: VpcEndpoints
  type: string
- container: ''
  name: NextToken
  type: string
- container: ''
  name: VpcEndpointType
  type: string
- container: ''
  name: VpcId
  type: string
- container: ''
  name: ServiceName
  type: string
- container: ''
  name: State
  type: string
- container: ''
  name: PolicyDocument
  type: string
- container: set
  name: SubnetIds
  type: string
- container: set
  name: NetworkInterfaceIds
  type: string
- container: set
  name: DnsEntries
  type: string
- container: set
  name: AddAllowedPrincipals
  type: string
- container: set
  name: RemoveAllowedPrincipals
  type: string
- container: set
  name: NetworkLoadBalancerArn
  type: string
- container: set
  name: GatewayLoadBalancerArn
  type: string
- container: ''
  name: AcceptanceRequired
  type: boolean
- container: ''
  name: PrivateDnsName
  type: string
- container: ''
  name: ResetPolicy
  type: boolean
- container: ''
  name: VpcEndpointOwner
  type: string
- container: ''
  name: VpcEndpointState
  type: string
- container: ''
  name: CreationTimestamp
  type: dateTime
- container: set
  name: ServiceNames
  type: string
- container: set
  name: ServiceDetails
  type: string
- container: set
  name: SubnetId
  type: string
- container: set
  name: SecurityGroupId
  type: string
- container: ''
  name: PrivateDnsEnabled
  type: boolean
- container: set
  name: ServiceType
  type: string
- container: ''
  name: ServiceState
  type: string
- container: set
  name: AvailabilityZones
  type: string
- container: set
  name: NetworkLoadBalancerArns
  type: string
- container: set
  name: VpcEndpointConnections
  type: string
- container: ''
  name: Owner
  type: string
- container: set
  name: BaseEndpointDnsNames
  type: string
property_count: 34
provider_name: Amazon PrivateLink
provider_slug: amazon-privatelink
slug: amazon-privatelink-context
source_filename: amazon-privatelink-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"pl\": \"https://ec2.amazonaws.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"RejectVpcEndpointConnectionsRequest\": \"pl:RejectVpcEndpointConnectionsRequest\",\n    \"ServiceId\": {\n      \"@id\": \"pl:ServiceId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"VpcEndpointId\": {\n      \"@id\": \"pl:VpcEndpointId\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DescribeVpcEndpointsResult\": \"pl:DescribeVpcEndpointsResult\",\n    \"VpcEndpoints\": {\n      \"@id\": \"pl:VpcEndpoints\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"NextToken\": {\n      \"@id\": \"pl:NextToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"VpcEndpoint\": \"pl:VpcEndpoint\",\n    \"VpcEndpointType\": {\n      \"@id\": \"pl:VpcEndpointType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"VpcId\"\
  : {\n      \"@id\": \"pl:VpcId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ServiceName\": {\n      \"@id\": \"pl:ServiceName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"State\": {\n      \"@id\": \"pl:State\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PolicyDocument\": {\n      \"@id\": \"pl:PolicyDocument\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SubnetIds\": {\n      \"@id\": \"pl:SubnetIds\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"NetworkInterfaceIds\": {\n      \"@id\": \"pl:NetworkInterfaceIds\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DnsEntries\": {\n      \"@id\": \"pl:DnsEntries\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreateVpcEndpointServiceConfigurationResult\": \"pl:CreateVpcEndpointServiceConfigurationResult\",\n    \"ServiceConfiguration\": \"pl:ServiceConfiguration\",\n    \"ModifyVpcEndpointServicePermissionsRequest\"\
  : \"pl:ModifyVpcEndpointServicePermissionsRequest\",\n    \"AddAllowedPrincipals\": {\n      \"@id\": \"pl:AddAllowedPrincipals\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RemoveAllowedPrincipals\": {\n      \"@id\": \"pl:RemoveAllowedPrincipals\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreateVpcEndpointServiceConfigurationRequest\": \"pl:CreateVpcEndpointServiceConfigurationRequest\",\n    \"NetworkLoadBalancerArn\": {\n      \"@id\": \"pl:NetworkLoadBalancerArn\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GatewayLoadBalancerArn\": {\n      \"@id\": \"pl:GatewayLoadBalancerArn\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AcceptanceRequired\": {\n      \"@id\": \"pl:AcceptanceRequired\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"PrivateDnsName\": {\n      \"@id\": \"pl:PrivateDnsName\",\n      \"@type\": \"xsd:string\"\n\
  \    },\n    \"ModifyVpcEndpointRequest\": \"pl:ModifyVpcEndpointRequest\",\n    \"ResetPolicy\": {\n      \"@id\": \"pl:ResetPolicy\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"VpcEndpointConnection\": \"pl:VpcEndpointConnection\",\n    \"VpcEndpointOwner\": {\n      \"@id\": \"pl:VpcEndpointOwner\",\n      \"@type\": \"xsd:string\"\n    },\n    \"VpcEndpointState\": {\n      \"@id\": \"pl:VpcEndpointState\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreationTimestamp\": {\n      \"@id\": \"pl:CreationTimestamp\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"CreateVpcEndpointResult\": \"pl:CreateVpcEndpointResult\",\n    \"DeleteVpcEndpointServiceConfigurationsRequest\": \"pl:DeleteVpcEndpointServiceConfigurationsRequest\",\n    \"DescribeVpcEndpointServicesResult\": \"pl:DescribeVpcEndpointServicesResult\",\n    \"ServiceNames\": {\n      \"@id\": \"pl:ServiceNames\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ServiceDetails\":\
  \ {\n      \"@id\": \"pl:ServiceDetails\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AcceptVpcEndpointConnectionsRequest\": \"pl:AcceptVpcEndpointConnectionsRequest\",\n    \"CreateVpcEndpointRequest\": \"pl:CreateVpcEndpointRequest\",\n    \"SubnetId\": {\n      \"@id\": \"pl:SubnetId\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SecurityGroupId\": {\n      \"@id\": \"pl:SecurityGroupId\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PrivateDnsEnabled\": {\n      \"@id\": \"pl:PrivateDnsEnabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"DeleteVpcEndpointsRequest\": \"pl:DeleteVpcEndpointsRequest\",\n    \"ServiceType\": {\n      \"@id\": \"pl:ServiceType\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ServiceState\": {\n      \"@id\": \"pl:ServiceState\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AvailabilityZones\": {\n  \
  \    \"@id\": \"pl:AvailabilityZones\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"NetworkLoadBalancerArns\": {\n      \"@id\": \"pl:NetworkLoadBalancerArns\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DescribeVpcEndpointConnectionsResult\": \"pl:DescribeVpcEndpointConnectionsResult\",\n    \"VpcEndpointConnections\": {\n      \"@id\": \"pl:VpcEndpointConnections\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ModifyVpcEndpointServiceConfigurationRequest\": \"pl:ModifyVpcEndpointServiceConfigurationRequest\",\n    \"ServiceDetail\": \"pl:ServiceDetail\",\n    \"Owner\": {\n      \"@id\": \"pl:Owner\",\n      \"@type\": \"xsd:string\"\n    },\n    \"BaseEndpointDnsNames\": {\n      \"@id\": \"pl:BaseEndpointDnsNames\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-privatelink/refs/heads/main/json-ld/amazon-privatelink-context.jsonld
tags:
- AWS
- Networking
- Private Connectivity
- Security
- VPC
- Zero Trust
- Endpoint Services
- JSON-LD
- Linked Data
- Semantic Web
---
