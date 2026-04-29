---
api_specs:
- filename: amazon-efs-openapi.yml
  format: yaml
  label: Amazon EFS API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-efs/refs/heads/main/openapi/amazon-efs-openapi.yml
class_count: 4
classes:
- Amazon EFS FileSystem
- DescribeFileSystemsResponse
- FileSystem
- MountTarget
context_file: json-ld/amazon-efs-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-efs/refs/heads/main/json-ld/amazon-efs-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Efs from Amazon EFS.
layout: jsonld
name: Amazon Efs Context
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
- container: set
  name: FileSystems
  type: string
- container: ''
  name: Marker
  type: string
- container: ''
  name: NextMarker
  type: string
- container: ''
  name: FileSystemId
  type: string
- container: ''
  name: FileSystemArn
  type: string
- container: ''
  name: CreationToken
  type: string
- container: ''
  name: OwnerId
  type: string
- container: ''
  name: CreationTime
  type: dateTime
- container: ''
  name: LifeCycleState
  type: string
- container: ''
  name: Name
  type: string
- container: ''
  name: NumberOfMountTargets
  type: integer
- container: ''
  name: SizeInBytes
  type: reference
- container: ''
  name: Value
  type: integer
- container: ''
  name: Timestamp
  type: dateTime
- container: ''
  name: ValueInIA
  type: integer
- container: ''
  name: ValueInStandard
  type: integer
- container: ''
  name: PerformanceMode
  type: string
- container: ''
  name: Encrypted
  type: boolean
- container: ''
  name: KmsKeyId
  type: string
- container: ''
  name: ThroughputMode
  type: string
- container: ''
  name: ProvisionedThroughputInMibps
  type: decimal
- container: set
  name: Tags
  type: string
- container: ''
  name: Key
  type: string
- container: ''
  name: AvailabilityZoneId
  type: string
- container: ''
  name: AvailabilityZoneName
  type: string
- container: ''
  name: MountTargetId
  type: string
- container: ''
  name: SubnetId
  type: string
- container: ''
  name: IpAddress
  type: string
- container: ''
  name: NetworkInterfaceId
  type: string
- container: ''
  name: VpcId
  type: string
property_count: 30
provider_name: Amazon EFS
provider_slug: amazon-efs
slug: amazon-efs-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aws\": \"https://aws.amazon.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"pan\": \"https://aws.amazon.com/schema/\",\n    \"Amazon EFS FileSystem\": \"aws:Amazon EFS FileSystem\",\n    \"DescribeFileSystemsResponse\": \"aws:DescribeFileSystemsResponse\",\n    \"FileSystem\": \"aws:FileSystem\",\n    \"MountTarget\": \"aws:MountTarget\",\n    \"FileSystems\": {\n      \"@id\": \"pan:FileSystems\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Marker\": {\n      \"@id\": \"pan:Marker\",\n      \"@type\": \"xsd:string\"\n    },\n    \"NextMarker\": {\n      \"@id\": \"pan:NextMarker\",\n      \"@type\": \"xsd:string\"\n    },\n    \"FileSystemId\": {\n      \"@id\": \"pan:FileSystemId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"FileSystemArn\": {\n      \"@id\": \"pan:FileSystemArn\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"CreationToken\": {\n      \"@id\": \"pan:CreationToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"OwnerId\": {\n      \"@id\": \"pan:OwnerId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreationTime\": {\n      \"@id\": \"pan:CreationTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"LifeCycleState\": {\n      \"@id\": \"pan:LifeCycleState\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Name\": {\n      \"@id\": \"pan:Name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"NumberOfMountTargets\": {\n      \"@id\": \"pan:NumberOfMountTargets\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"SizeInBytes\": {\n      \"@id\": \"pan:SizeInBytes\",\n      \"@type\": \"@id\"\n    },\n    \"Value\": {\n      \"@id\": \"pan:Value\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"Timestamp\": {\n      \"@id\": \"pan:Timestamp\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"ValueInIA\": {\n      \"@id\": \"pan:ValueInIA\"\
  ,\n      \"@type\": \"xsd:integer\"\n    },\n    \"ValueInStandard\": {\n      \"@id\": \"pan:ValueInStandard\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"PerformanceMode\": {\n      \"@id\": \"pan:PerformanceMode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Encrypted\": {\n      \"@id\": \"pan:Encrypted\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"KmsKeyId\": {\n      \"@id\": \"pan:KmsKeyId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ThroughputMode\": {\n      \"@id\": \"pan:ThroughputMode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ProvisionedThroughputInMibps\": {\n      \"@id\": \"pan:ProvisionedThroughputInMibps\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"Tags\": {\n      \"@id\": \"pan:Tags\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Key\": {\n      \"@id\": \"pan:Key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AvailabilityZoneId\": {\n      \"@id\": \"pan:AvailabilityZoneId\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"AvailabilityZoneName\": {\n      \"@id\": \"pan:AvailabilityZoneName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MountTargetId\": {\n      \"@id\": \"pan:MountTargetId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SubnetId\": {\n      \"@id\": \"pan:SubnetId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"IpAddress\": {\n      \"@id\": \"pan:IpAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"NetworkInterfaceId\": {\n      \"@id\": \"pan:NetworkInterfaceId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"VpcId\": {\n      \"@id\": \"pan:VpcId\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-efs/refs/heads/main/json-ld/amazon-efs-context.jsonld
tags:
- Amazon Web Services
- AWS
- EFS
- Elastic File System
- File Storage
- NFS
- Serverless
- Storage
- JSON-LD
- Linked Data
- Semantic Web
---
