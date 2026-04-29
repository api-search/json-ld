---
class_count: 4
classes:
- Amazon ECR Repository
- CreateRepositoryResponse
- DescribeRepositoriesResponse
- Repository
context_file: json-ld/amazon-ecr-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-ecr/refs/heads/main/json-ld/amazon-ecr-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Ecr from Amazon ECR.
layout: jsonld
name: Amazon Ecr Context
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
  name: repositoryArn
  type: string
- container: ''
  name: registryId
  type: string
- container: ''
  name: repositoryName
  type: string
- container: ''
  name: repositoryUri
  type: reference
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: imageTagMutability
  type: string
- container: ''
  name: imageScanningConfiguration
  type: reference
- container: ''
  name: scanOnPush
  type: boolean
- container: ''
  name: encryptionConfiguration
  type: reference
- container: ''
  name: encryptionType
  type: string
- container: ''
  name: kmsKey
  type: string
- container: ''
  name: imageCount
  type: integer
- container: ''
  name: repositoryPolicy
  type: string
- container: ''
  name: lifecyclePolicy
  type: reference
- container: ''
  name: lifecyclePolicyText
  type: string
- container: ''
  name: lastEvaluatedAt
  type: dateTime
- container: set
  name: tags
  type: string
- container: ''
  name: Key
  type: string
- container: ''
  name: Value
  type: string
- container: ''
  name: repository
  type: string
- container: set
  name: repositories
  type: string
- container: ''
  name: nextToken
  type: string
property_count: 22
provider_name: Amazon ECR
provider_slug: amazon-ecr
slug: amazon-ecr-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aws\": \"https://aws.amazon.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"pan\": \"https://aws.amazon.com/schema/\",\n    \"Amazon ECR Repository\": \"aws:Amazon ECR Repository\",\n    \"CreateRepositoryResponse\": \"aws:CreateRepositoryResponse\",\n    \"DescribeRepositoriesResponse\": \"aws:DescribeRepositoriesResponse\",\n    \"Repository\": \"aws:Repository\",\n    \"repositoryArn\": {\n      \"@id\": \"pan:repositoryArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"registryId\": {\n      \"@id\": \"pan:registryId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"repositoryName\": {\n      \"@id\": \"pan:repositoryName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"repositoryUri\": {\n      \"@id\": \"pan:repositoryUri\",\n      \"@type\": \"@id\"\n    },\n    \"createdAt\": {\n      \"@id\"\
  : \"pan:createdAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"imageTagMutability\": {\n      \"@id\": \"pan:imageTagMutability\",\n      \"@type\": \"xsd:string\"\n    },\n    \"imageScanningConfiguration\": {\n      \"@id\": \"pan:imageScanningConfiguration\",\n      \"@type\": \"@id\"\n    },\n    \"scanOnPush\": {\n      \"@id\": \"pan:scanOnPush\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"encryptionConfiguration\": {\n      \"@id\": \"pan:encryptionConfiguration\",\n      \"@type\": \"@id\"\n    },\n    \"encryptionType\": {\n      \"@id\": \"pan:encryptionType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"kmsKey\": {\n      \"@id\": \"pan:kmsKey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"imageCount\": {\n      \"@id\": \"pan:imageCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"repositoryPolicy\": {\n      \"@id\": \"pan:repositoryPolicy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lifecyclePolicy\": {\n      \"@id\": \"pan:lifecyclePolicy\"\
  ,\n      \"@type\": \"@id\"\n    },\n    \"lifecyclePolicyText\": {\n      \"@id\": \"pan:lifecyclePolicyText\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastEvaluatedAt\": {\n      \"@id\": \"pan:lastEvaluatedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"tags\": {\n      \"@id\": \"pan:tags\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Key\": {\n      \"@id\": \"pan:Key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Value\": {\n      \"@id\": \"pan:Value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"repository\": {\n      \"@id\": \"pan:repository\",\n      \"@type\": \"xsd:string\"\n    },\n    \"repositories\": {\n      \"@id\": \"pan:repositories\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nextToken\": {\n      \"@id\": \"pan:nextToken\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-ecr/refs/heads/main/json-ld/amazon-ecr-context.jsonld
tags:
- Amazon Web Services
- AWS
- Container Images
- Container Registry
- Containers
- Docker
- ECR
- OCI
- JSON-LD
- Linked Data
- Semantic Web
---
