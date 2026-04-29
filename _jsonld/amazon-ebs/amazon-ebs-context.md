---
api_specs:
- filename: amazon-ebs-openapi.yml
  format: yaml
  label: Amazon EBS API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-ebs/refs/heads/main/openapi/amazon-ebs-openapi.yml
class_count: 3
classes:
- Amazon EBS Volume
- DescribeVolumesResult
- Volume
context_file: json-ld/amazon-ebs-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-ebs/refs/heads/main/json-ld/amazon-ebs-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Ebs from Amazon EBS.
layout: jsonld
name: Amazon Ebs Context
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
  name: volumeId
  type: string
- container: ''
  name: size
  type: integer
- container: ''
  name: volumeType
  type: string
- container: ''
  name: state
  type: string
- container: ''
  name: availabilityZone
  type: string
- container: ''
  name: createTime
  type: dateTime
- container: ''
  name: encrypted
  type: boolean
- container: ''
  name: kmsKeyId
  type: string
- container: ''
  name: iops
  type: integer
- container: ''
  name: throughput
  type: integer
- container: ''
  name: snapshotId
  type: string
- container: ''
  name: multiAttachEnabled
  type: boolean
- container: set
  name: attachments
  type: string
- container: set
  name: tags
  type: string
- container: ''
  name: instanceId
  type: string
- container: ''
  name: device
  type: string
- container: ''
  name: attachTime
  type: dateTime
- container: ''
  name: deleteOnTermination
  type: boolean
- container: ''
  name: Key
  type: string
- container: ''
  name: Value
  type: string
- container: ''
  name: key
  type: string
- container: ''
  name: value
  type: string
- container: set
  name: volumeSet
  type: string
- container: ''
  name: nextToken
  type: string
property_count: 24
provider_name: Amazon EBS
provider_slug: amazon-ebs
slug: amazon-ebs-context
source_filename: amazon-ebs-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aws\": \"https://aws.amazon.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"pan\": \"https://aws.amazon.com/schema/\",\n    \"Amazon EBS Volume\": \"aws:Amazon EBS Volume\",\n    \"DescribeVolumesResult\": \"aws:DescribeVolumesResult\",\n    \"Volume\": \"aws:Volume\",\n    \"volumeId\": {\n      \"@id\": \"pan:volumeId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"size\": {\n      \"@id\": \"pan:size\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"volumeType\": {\n      \"@id\": \"pan:volumeType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"state\": {\n      \"@id\": \"pan:state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"availabilityZone\": {\n      \"@id\": \"pan:availabilityZone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createTime\": {\n      \"@id\": \"pan:createTime\",\n\
  \      \"@type\": \"xsd:dateTime\"\n    },\n    \"encrypted\": {\n      \"@id\": \"pan:encrypted\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"kmsKeyId\": {\n      \"@id\": \"pan:kmsKeyId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"iops\": {\n      \"@id\": \"pan:iops\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"throughput\": {\n      \"@id\": \"pan:throughput\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"snapshotId\": {\n      \"@id\": \"pan:snapshotId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"multiAttachEnabled\": {\n      \"@id\": \"pan:multiAttachEnabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"attachments\": {\n      \"@id\": \"pan:attachments\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tags\": {\n      \"@id\": \"pan:tags\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"instanceId\": {\n      \"@id\": \"pan:instanceId\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"device\": {\n      \"@id\": \"pan:device\",\n      \"@type\": \"xsd:string\"\n    },\n    \"attachTime\": {\n      \"@id\": \"pan:attachTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"deleteOnTermination\": {\n      \"@id\": \"pan:deleteOnTermination\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"Key\": {\n      \"@id\": \"pan:Key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Value\": {\n      \"@id\": \"pan:Value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"key\": {\n      \"@id\": \"pan:key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"pan:value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"volumeSet\": {\n      \"@id\": \"pan:volumeSet\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nextToken\": {\n      \"@id\": \"pan:nextToken\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-ebs/refs/heads/main/json-ld/amazon-ebs-context.jsonld
tags:
- Amazon Web Services
- AWS
- Block Storage
- EBS
- EC2
- Snapshots
- Storage
- Volumes
- JSON-LD
- Linked Data
- Semantic Web
---
