---
api_specs:
- filename: amazon-ec2-openapi.yml
  format: yaml
  label: Amazon EC2 API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-ec2/refs/heads/main/openapi/amazon-ec2-openapi.yml
class_count: 6
classes:
- Amazon EC2 Instance
- CreateImageResponse
- DescribeInstancesResponse
- Instance
- RunInstancesResponse
- Tag
context_file: json-ld/amazon-ec2-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-ec2/refs/heads/main/json-ld/amazon-ec2-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Ec2 from Amazon EC2.
layout: jsonld
name: Amazon Ec2 Context
namespaces:
- prefix: aws
  uri: https://aws.amazon.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: pan
  uri: https://aws.amazon.com/schema/
properties:
- container: ''
  name: instanceId
  type: string
- container: ''
  name: imageId
  type: string
- container: ''
  name: instanceType
  type: string
- container: ''
  name: keyName
  type: string
- container: ''
  name: launchTime
  type: dateTime
- container: ''
  name: placement
  type: reference
- container: ''
  name: availabilityZone
  type: string
- container: ''
  name: monitoring
  type: reference
- container: ''
  name: state
  type: string
- container: ''
  name: instanceState
  type: reference
- container: ''
  name: code
  type: integer
- container: ''
  name: name
  type: string
- container: ''
  name: subnetId
  type: string
- container: ''
  name: vpcId
  type: string
- container: ''
  name: privateIpAddress
  type: string
- container: ''
  name: publicIpAddress
  type: string
- container: ''
  name: architecture
  type: string
- container: ''
  name: rootDeviceType
  type: string
- container: set
  name: tags
  type: string
- container: set
  name: securityGroups
  type: string
- container: ''
  name: groupId
  type: string
- container: ''
  name: groupName
  type: string
- container: ''
  name: reservationId
  type: string
- container: ''
  name: ownerId
  type: string
- container: set
  name: instances
  type: string
- container: ''
  name: rootDeviceName
  type: string
- container: set
  name: blockDeviceMappings
  type: string
- container: ''
  name: platform
  type: string
- container: ''
  name: ebsOptimized
  type: boolean
- container: ''
  name: enaSupport
  type: boolean
- container: ''
  name: key
  type: string
- container: ''
  name: value
  type: string
- container: set
  name: reservationSet
  type: string
- container: ''
  name: nextToken
  type: string
- container: set
  name: instancesSet
  type: string
property_count: 35
provider_name: Amazon EC2
provider_slug: amazon-ec2
slug: amazon-ec2-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aws\": \"https://aws.amazon.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"pan\": \"https://aws.amazon.com/schema/\",\n    \"Amazon EC2 Instance\": \"aws:Amazon EC2 Instance\",\n    \"CreateImageResponse\": \"aws:CreateImageResponse\",\n    \"DescribeInstancesResponse\": \"aws:DescribeInstancesResponse\",\n    \"Instance\": \"aws:Instance\",\n    \"RunInstancesResponse\": \"aws:RunInstancesResponse\",\n    \"Tag\": \"aws:Tag\",\n    \"instanceId\": {\n      \"@id\": \"pan:instanceId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"imageId\": {\n      \"@id\": \"pan:imageId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"instanceType\": {\n      \"@id\": \"pan:instanceType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"keyName\": {\n      \"@id\": \"pan:keyName\",\n      \"@type\": \"xsd:string\"\n\
  \    },\n    \"launchTime\": {\n      \"@id\": \"pan:launchTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"placement\": {\n      \"@id\": \"pan:placement\",\n      \"@type\": \"@id\"\n    },\n    \"availabilityZone\": {\n      \"@id\": \"pan:availabilityZone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"monitoring\": {\n      \"@id\": \"pan:monitoring\",\n      \"@type\": \"@id\"\n    },\n    \"state\": {\n      \"@id\": \"pan:state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"instanceState\": {\n      \"@id\": \"pan:instanceState\",\n      \"@type\": \"@id\"\n    },\n    \"code\": {\n      \"@id\": \"pan:code\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subnetId\": {\n      \"@id\": \"pan:subnetId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"vpcId\": {\n      \"@id\": \"pan:vpcId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"privateIpAddress\": {\n      \"\
  @id\": \"pan:privateIpAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"publicIpAddress\": {\n      \"@id\": \"pan:publicIpAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"architecture\": {\n      \"@id\": \"pan:architecture\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rootDeviceType\": {\n      \"@id\": \"pan:rootDeviceType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tags\": {\n      \"@id\": \"pan:tags\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"securityGroups\": {\n      \"@id\": \"pan:securityGroups\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"groupId\": {\n      \"@id\": \"pan:groupId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"groupName\": {\n      \"@id\": \"pan:groupName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reservationId\": {\n      \"@id\": \"pan:reservationId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ownerId\": {\n      \"@id\": \"pan:ownerId\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"instances\": {\n      \"@id\": \"pan:instances\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rootDeviceName\": {\n      \"@id\": \"pan:rootDeviceName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"blockDeviceMappings\": {\n      \"@id\": \"pan:blockDeviceMappings\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"platform\": {\n      \"@id\": \"pan:platform\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ebsOptimized\": {\n      \"@id\": \"pan:ebsOptimized\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"enaSupport\": {\n      \"@id\": \"pan:enaSupport\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"key\": {\n      \"@id\": \"pan:key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"pan:value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reservationSet\": {\n      \"@id\": \"pan:reservationSet\",\n      \"@container\"\
  : \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nextToken\": {\n      \"@id\": \"pan:nextToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"instancesSet\": {\n      \"@id\": \"pan:instancesSet\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-ec2/refs/heads/main/json-ld/amazon-ec2-context.jsonld
tags:
- AWS
- Cloud Computing
- Compute
- IaaS
- Infrastructure
- Virtual Machines
- JSON-LD
- Linked Data
- Semantic Web
---
