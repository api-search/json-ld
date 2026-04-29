---
class_count: 5
classes:
- Environment
- KxEnvironment
- KxCluster
- KxDatabase
- KxUser
context_file: json-ld/amazon-finspace-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-finspace/refs/heads/main/json-ld/amazon-finspace-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Finspace from Amazon FinSpace.
layout: jsonld
name: Amazon Finspace Context
namespaces:
- prefix: finspace
  uri: https://aws.amazon.com/finspace/vocabulary/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: environmentId
  type: string
- container: ''
  name: name
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: environmentUrl
  type: anyURI
- container: ''
  name: environmentArn
  type: string
- container: ''
  name: awsAccountId
  type: string
- container: ''
  name: kmsKeyId
  type: string
- container: ''
  name: federationMode
  type: string
- container: ''
  name: clusterName
  type: string
- container: ''
  name: clusterType
  type: string
- container: ''
  name: capacityConfiguration
  type: ''
- container: ''
  name: databaseName
  type: string
- container: ''
  name: databaseArn
  type: string
- container: ''
  name: userArn
  type: string
- container: ''
  name: userName
  type: string
- container: ''
  name: iamRole
  type: string
- container: ''
  name: tags
  type: ''
- container: ''
  name: createdTimestamp
  type: dateTime
- container: ''
  name: lastModifiedTimestamp
  type: dateTime
- container: ''
  name: createTimestamp
  type: dateTime
- container: ''
  name: updateTimestamp
  type: dateTime
property_count: 22
provider_name: Amazon FinSpace
provider_slug: amazon-finspace
slug: amazon-finspace-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"finspace\": \"https://aws.amazon.com/finspace/vocabulary/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Environment\": \"finspace:Environment\",\n    \"KxEnvironment\": \"finspace:KxEnvironment\",\n    \"KxCluster\": \"finspace:KxCluster\",\n    \"KxDatabase\": \"finspace:KxDatabase\",\n    \"KxUser\": \"finspace:KxUser\",\n    \"environmentId\": {\n      \"@id\": \"finspace:environmentId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"finspace:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"environmentUrl\": {\n      \"@id\": \"finspace:environmentUrl\",\n      \"@type\": \"xsd:anyURI\"\n    },\n    \"environmentArn\": {\n      \"\
  @id\": \"finspace:environmentArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"awsAccountId\": {\n      \"@id\": \"finspace:awsAccountId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"kmsKeyId\": {\n      \"@id\": \"finspace:kmsKeyId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"federationMode\": {\n      \"@id\": \"finspace:federationMode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"clusterName\": {\n      \"@id\": \"finspace:clusterName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"clusterType\": {\n      \"@id\": \"finspace:clusterType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"capacityConfiguration\": {\n      \"@id\": \"finspace:capacityConfiguration\"\n    },\n    \"databaseName\": {\n      \"@id\": \"finspace:databaseName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"databaseArn\": {\n      \"@id\": \"finspace:databaseArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"userArn\": {\n      \"@id\": \"finspace:userArn\",\n      \"@type\": \"\
  xsd:string\"\n    },\n    \"userName\": {\n      \"@id\": \"finspace:userName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"iamRole\": {\n      \"@id\": \"finspace:iamRole\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tags\": {\n      \"@id\": \"schema:keywords\"\n    },\n    \"createdTimestamp\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"lastModifiedTimestamp\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"createTimestamp\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updateTimestamp\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-finspace/refs/heads/main/json-ld/amazon-finspace-context.jsonld
tags:
- AWS
- Capital Markets
- Data Analytics
- Data Management
- Financial Services
- JSON-LD
- Linked Data
- Semantic Web
---
