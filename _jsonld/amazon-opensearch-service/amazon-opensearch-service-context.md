---
class_count: 0
classes: []
context_file: json-ld/amazon-opensearch-service-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-opensearch-service/refs/heads/main/json-ld/amazon-opensearch-service-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Opensearch Service from Amazon OpenSearch Service.
layout: jsonld
name: Amazon Opensearch Service Context
namespaces:
- prefix: opensearch
  uri: https://docs.aws.amazon.com/opensearch-service/latest/APIReference/
- prefix: aws
  uri: https://aws.amazon.com/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Domain
  type: ''
- container: ''
  name: ClusterConfig
  type: ''
- container: ''
  name: EBSOptions
  type: ''
property_count: 3
provider_name: Amazon OpenSearch Service
provider_slug: amazon-opensearch-service
slug: amazon-opensearch-service-context
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"opensearch\": \"https://docs.aws.amazon.com/opensearch-service/latest/APIReference/\",\n    \"aws\": \"https://aws.amazon.com/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Domain\": {\n      \"@id\": \"opensearch:API_DescribeDomain\",\n      \"@context\": {\n        \"DomainId\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"DomainName\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"ARN\": {\n          \"@id\": \"opensearch:domainArn\",\n          \"@type\": \"xsd:string\"\n        },\n        \"Created\": {\n          \"@id\": \"opensearch:created\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"Deleted\": {\n          \"@id\": \"opensearch:deleted\",\n          \"@type\"\
  : \"xsd:boolean\"\n        },\n        \"Endpoint\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"EngineVersion\": {\n          \"@id\": \"schema:version\",\n          \"@type\": \"xsd:string\"\n        },\n        \"ClusterConfig\": {\n          \"@id\": \"opensearch:clusterConfig\",\n          \"@type\": \"opensearch:ClusterConfig\"\n        },\n        \"EBSOptions\": {\n          \"@id\": \"opensearch:ebsOptions\",\n          \"@type\": \"opensearch:EBSOptions\"\n        },\n        \"AccessPolicies\": {\n          \"@id\": \"opensearch:accessPolicies\",\n          \"@type\": \"xsd:string\"\n        },\n        \"EncryptionAtRestOptions\": {\n          \"@id\": \"opensearch:encryptionAtRest\",\n          \"@type\": \"opensearch:EncryptionAtRestOptions\"\n        },\n        \"NodeToNodeEncryptionOptions\": {\n          \"@id\": \"opensearch:nodeToNodeEncryption\",\n          \"@type\": \"opensearch:NodeToNodeEncryptionOptions\"\n      \
  \  },\n        \"tags\": {\n          \"@id\": \"schema:keywords\",\n          \"@container\": \"@list\"\n        }\n      }\n    },\n\n    \"ClusterConfig\": {\n      \"@id\": \"opensearch:ClusterConfig\",\n      \"@context\": {\n        \"InstanceType\": {\n          \"@id\": \"opensearch:instanceType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"InstanceCount\": {\n          \"@id\": \"opensearch:instanceCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"DedicatedMasterEnabled\": {\n          \"@id\": \"opensearch:dedicatedMasterEnabled\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"DedicatedMasterType\": {\n          \"@id\": \"opensearch:dedicatedMasterType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"DedicatedMasterCount\": {\n          \"@id\": \"opensearch:dedicatedMasterCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"ZoneAwarenessEnabled\": {\n          \"@id\": \"opensearch:zoneAwarenessEnabled\"\
  ,\n          \"@type\": \"xsd:boolean\"\n        },\n        \"WarmEnabled\": {\n          \"@id\": \"opensearch:warmEnabled\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"WarmType\": {\n          \"@id\": \"opensearch:warmType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"WarmCount\": {\n          \"@id\": \"opensearch:warmCount\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"EBSOptions\": {\n      \"@id\": \"opensearch:EBSOptions\",\n      \"@context\": {\n        \"EBSEnabled\": {\n          \"@id\": \"opensearch:ebsEnabled\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"VolumeType\": {\n          \"@id\": \"opensearch:volumeType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"VolumeSize\": {\n          \"@id\": \"opensearch:volumeSize\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"Iops\": {\n          \"@id\": \"opensearch:iops\",\n          \"@type\": \"xsd:integer\"\n \
  \       },\n        \"Throughput\": {\n          \"@id\": \"opensearch:throughput\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-opensearch-service/refs/heads/main/json-ld/amazon-opensearch-service-context.jsonld
tags:
- Analytics
- AWS
- Elasticsearch
- Full-Text Search
- Log Analytics
- OpenSearch
- Search
- JSON-LD
- Linked Data
- Semantic Web
---
