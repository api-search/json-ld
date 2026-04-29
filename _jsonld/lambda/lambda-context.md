---
class_count: 0
classes: []
context_file: json-ld/lambda-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/lambda/refs/heads/main/json-ld/lambda-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Lambda from Lambda.
layout: jsonld
name: Lambda Context
namespaces:
- prefix: lambda
  uri: https://cloud.lambdalabs.com/api/v1/
properties:
- container: ''
  name: Instance
  type: ''
- container: ''
  name: Region
  type: ''
- container: ''
  name: SshKey
  type: ''
- container: ''
  name: FileSystem
  type: ''
property_count: 4
provider_name: Lambda
provider_slug: lambda
slug: lambda-context
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"lambda\": \"https://cloud.lambdalabs.com/api/v1/\",\n    \"Instance\": {\n      \"@id\": \"lambda:Instance\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"ip\": \"lambda:ipAddress\",\n        \"status\": \"lambda:instanceStatus\",\n        \"ssh_key_names\": \"lambda:sshKeyNames\",\n        \"file_system_names\": \"lambda:fileSystemNames\",\n        \"region\": \"lambda:region\",\n        \"instance_type\": \"lambda:instanceType\",\n        \"hostname\": \"lambda:hostname\",\n        \"jupyter_token\": \"lambda:jupyterToken\",\n        \"jupyter_url\": \"schema:url\"\n      }\n    },\n    \"Region\": {\n      \"@id\": \"lambda:Region\",\n      \"@context\": {\n        \"name\": \"schema:identifier\",\n        \"description\": \"schema:name\"\n      }\n    },\n    \"SshKey\": {\n      \"@id\": \"lambda:SshKey\",\n      \"@context\": {\n     \
  \   \"id\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"public_key\": \"lambda:publicKey\"\n      }\n    },\n    \"FileSystem\": {\n      \"@id\": \"lambda:FileSystem\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"created\": \"schema:dateCreated\",\n        \"mount_point\": \"lambda:mountPoint\",\n        \"region\": \"lambda:region\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/lambda/refs/heads/main/json-ld/lambda-context.jsonld
tags:
- Artificial Intelligence
- Cloud Computing
- Compute
- Deep Learning
- GPU
- Machine Learning
- JSON-LD
- Linked Data
- Semantic Web
---
