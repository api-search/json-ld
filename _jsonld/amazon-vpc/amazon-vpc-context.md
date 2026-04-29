---
class_count: 0
classes: []
context_file: json-ld/amazon-vpc-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-vpc/refs/heads/main/json-ld/amazon-vpc-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Vpc from Amazon VPC.
layout: jsonld
name: Amazon Vpc Context
namespaces:
- prefix: vpc
  uri: https://docs.aws.amazon.com/AWSEC2/latest/APIReference/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Vpc
  type: ''
- container: ''
  name: Subnet
  type: ''
- container: ''
  name: InternetGateway
  type: ''
- container: ''
  name: NatGateway
  type: ''
- container: ''
  name: RouteTable
  type: ''
- container: ''
  name: NetworkAcl
  type: ''
property_count: 6
provider_name: Amazon VPC
provider_slug: amazon-vpc
slug: amazon-vpc-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"vpc\": \"https://docs.aws.amazon.com/AWSEC2/latest/APIReference/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Vpc\": {\n      \"@id\": \"vpc:Vpc\",\n      \"@context\": {\n        \"vpcId\": \"vpc:vpcId\",\n        \"cidrBlock\": \"vpc:cidrBlock\",\n        \"state\": \"vpc:state\",\n        \"dhcpOptionsId\": \"vpc:dhcpOptionsId\",\n        \"instanceTenancy\": \"vpc:instanceTenancy\",\n        \"isDefault\": \"vpc:isDefault\",\n        \"ownerId\": \"vpc:ownerId\",\n        \"tags\": {\n          \"@id\": \"vpc:tags\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Subnet\": {\n      \"@id\": \"vpc:Subnet\",\n      \"@context\": {\n        \"subnetId\": \"vpc:subnetId\",\n        \"subnetArn\": \"vpc:subnetArn\",\n        \"vpcId\": \"vpc:vpcId\",\n        \"cidrBlock\": \"vpc:cidrBlock\"\
  ,\n        \"availabilityZone\": \"vpc:availabilityZone\",\n        \"availabilityZoneId\": \"vpc:availabilityZoneId\",\n        \"state\": \"vpc:state\",\n        \"availableIpAddressCount\": \"vpc:availableIpAddressCount\",\n        \"defaultForAz\": \"vpc:defaultForAz\",\n        \"mapPublicIpOnLaunch\": \"vpc:mapPublicIpOnLaunch\",\n        \"tags\": {\n          \"@id\": \"vpc:tags\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"InternetGateway\": {\n      \"@id\": \"vpc:InternetGateway\",\n      \"@context\": {\n        \"internetGatewayId\": \"vpc:internetGatewayId\",\n        \"attachments\": {\n          \"@id\": \"vpc:attachments\",\n          \"@container\": \"@set\"\n        },\n        \"ownerId\": \"vpc:ownerId\",\n        \"tags\": {\n          \"@id\": \"vpc:tags\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"NatGateway\": {\n      \"@id\": \"vpc:NatGateway\",\n      \"@context\": {\n        \"natGatewayId\": \"vpc:natGatewayId\"\
  ,\n        \"subnetId\": \"vpc:subnetId\",\n        \"vpcId\": \"vpc:vpcId\",\n        \"state\": \"vpc:state\",\n        \"connectivityType\": \"vpc:connectivityType\",\n        \"createTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"natGatewayAddresses\": {\n          \"@id\": \"vpc:natGatewayAddresses\",\n          \"@container\": \"@set\"\n        },\n        \"tags\": {\n          \"@id\": \"vpc:tags\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"RouteTable\": {\n      \"@id\": \"vpc:RouteTable\",\n      \"@context\": {\n        \"routeTableId\": \"vpc:routeTableId\",\n        \"vpcId\": \"vpc:vpcId\",\n        \"routes\": {\n          \"@id\": \"vpc:routes\",\n          \"@container\": \"@set\"\n        },\n        \"associations\": {\n          \"@id\": \"vpc:associations\",\n          \"@container\": \"@set\"\n        },\n        \"ownerId\": \"vpc:ownerId\",\n        \"tags\": {\n   \
  \       \"@id\": \"vpc:tags\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"NetworkAcl\": {\n      \"@id\": \"vpc:NetworkAcl\",\n      \"@context\": {\n        \"networkAclId\": \"vpc:networkAclId\",\n        \"vpcId\": \"vpc:vpcId\",\n        \"isDefault\": \"vpc:isDefault\",\n        \"entries\": {\n          \"@id\": \"vpc:entries\",\n          \"@container\": \"@set\"\n        },\n        \"associations\": {\n          \"@id\": \"vpc:associations\",\n          \"@container\": \"@set\"\n        },\n        \"tags\": {\n          \"@id\": \"vpc:tags\",\n          \"@container\": \"@set\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-vpc/refs/heads/main/json-ld/amazon-vpc-context.jsonld
tags:
- AWS
- Networking
- Private Cloud
- Security
- Subnets
- VPC
- JSON-LD
- Linked Data
- Semantic Web
---
