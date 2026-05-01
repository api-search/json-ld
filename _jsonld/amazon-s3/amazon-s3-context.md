---
api_specs:
- filename: amazon-s3-rest-api-openapi.yml
  format: yaml
  label: Amazon S3 REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-s3/refs/heads/main/openapi/amazon-s3-rest-api-openapi.yml
- filename: amazon-s3-control-api-openapi.yml
  format: yaml
  label: Amazon S3 Control API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-s3/refs/heads/main/openapi/amazon-s3-control-api-openapi.yml
- filename: amazon-s3-tables-api-openapi.yml
  format: yaml
  label: Amazon S3 Tables API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-s3/refs/heads/main/openapi/amazon-s3-tables-api-openapi.yml
class_count: 10
classes:
- name
- description
- identifier
- url
- dateCreated
- dateModified
- contentType
- contentSize
- owner
- version
context_file: json-ld/amazon-s3-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-s3/refs/heads/main/json-ld/amazon-s3-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon S3 from Amazon S3.
layout: jsonld
name: Amazon S3 Context
namespaces:
- prefix: s3
  uri: https://docs.aws.amazon.com/AmazonS3/latest/API/
- prefix: aws
  uri: https://aws.amazon.com/
- prefix: iam
  uri: https://docs.aws.amazon.com/IAM/latest/UserGuide/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: schema
  uri: https://schema.org/
properties:
- container: ''
  name: Bucket
  type: ''
- container: ''
  name: S3Object
  type: ''
- container: ''
  name: Owner
  type: ''
- container: ''
  name: AccessPoint
  type: ''
- container: ''
  name: BatchJob
  type: ''
- container: ''
  name: TableBucket
  type: ''
- container: ''
  name: Table
  type: ''
- container: ''
  name: Tag
  type: ''
- container: ''
  name: Grant
  type: ''
- container: ''
  name: StorageLensConfiguration
  type: ''
- container: ''
  name: MultiRegionAccessPoint
  type: ''
property_count: 11
provider_name: Amazon S3
provider_slug: amazon-s3
slug: amazon-s3-context
source_filename: amazon-s3-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"@vocab\": \"https://schema.org/\",\n    \"s3\": \"https://docs.aws.amazon.com/AmazonS3/latest/API/\",\n    \"aws\": \"https://aws.amazon.com/\",\n    \"iam\": \"https://docs.aws.amazon.com/IAM/latest/UserGuide/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"schema\": \"https://schema.org/\",\n\n    \"Bucket\": {\n      \"@id\": \"s3:API_Types_Amazon_Simple_Storage_Service.html#Bucket\",\n      \"@context\": {\n        \"Name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"CreationDate\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"Region\": {\n          \"@id\": \"s3:BucketRegion\",\n          \"@type\": \"xsd:string\"\n        },\n        \"ARN\": {\n          \"@id\": \"aws:arn\",\n          \"@type\": \"@id\"\n        },\n        \"Owner\": {\n\
  \          \"@id\": \"schema:owner\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"S3Object\": {\n      \"@id\": \"s3:API_Types_Amazon_Simple_Storage_Service.html#Object\",\n      \"@context\": {\n        \"Key\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"Size\": {\n          \"@id\": \"schema:contentSize\",\n          \"@type\": \"xsd:long\"\n        },\n        \"ETag\": {\n          \"@id\": \"s3:ETag\",\n          \"@type\": \"xsd:string\"\n        },\n        \"LastModified\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"ContentType\": {\n          \"@id\": \"schema:encodingFormat\",\n          \"@type\": \"xsd:string\"\n        },\n        \"ContentLength\": {\n          \"@id\": \"schema:contentSize\",\n          \"@type\": \"xsd:long\"\n        },\n        \"StorageClass\": {\n          \"@id\": \"s3:StorageClass\",\n          \"@type\": \"\
  xsd:string\"\n        },\n        \"VersionId\": {\n          \"@id\": \"schema:version\",\n          \"@type\": \"xsd:string\"\n        },\n        \"BucketName\": {\n          \"@id\": \"s3:BucketName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"Owner\": {\n          \"@id\": \"schema:owner\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Owner\": {\n      \"@id\": \"s3:API_Types_Amazon_Simple_Storage_Service.html#Owner\",\n      \"@context\": {\n        \"DisplayName\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"ID\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"AccessPoint\": {\n      \"@id\": \"s3:API_Types_AWS_S3_Control.html#AccessPoint\",\n      \"@context\": {\n        \"Name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"Bucket\": {\n          \"@id\": \"\
  s3:BucketName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"NetworkOrigin\": {\n          \"@id\": \"s3:NetworkOrigin\",\n          \"@type\": \"xsd:string\"\n        },\n        \"AccessPointArn\": {\n          \"@id\": \"aws:arn\",\n          \"@type\": \"@id\"\n        },\n        \"Alias\": {\n          \"@id\": \"schema:alternateName\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"BatchJob\": {\n      \"@id\": \"s3:API_Types_AWS_S3_Control.html#JobDescriptor\",\n      \"@context\": {\n        \"JobId\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"Description\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"Status\": {\n          \"@id\": \"s3:JobStatus\",\n          \"@type\": \"xsd:string\"\n        },\n        \"Priority\": {\n          \"@id\": \"s3:JobPriority\",\n          \"@type\": \"xsd:integer\"\n        },\n\
  \        \"CreationTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"TerminationDate\": {\n          \"@id\": \"s3:TerminationDate\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"RoleArn\": {\n          \"@id\": \"iam:RoleArn\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"TableBucket\": {\n      \"@id\": \"s3:API_Operations_Amazon_S3_Tables.html#TableBucket\",\n      \"@context\": {\n        \"Name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"ARN\": {\n          \"@id\": \"aws:arn\",\n          \"@type\": \"@id\"\n        },\n        \"CreatedAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"OwnerAccountId\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"Table\": {\n      \"@id\": \"s3:API_Operations_Amazon_S3_Tables.html#Table\"\
  ,\n      \"@context\": {\n        \"Name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"TableARN\": {\n          \"@id\": \"aws:arn\",\n          \"@type\": \"@id\"\n        },\n        \"Namespace\": {\n          \"@id\": \"s3:Namespace\",\n          \"@type\": \"xsd:string\"\n        },\n        \"Format\": {\n          \"@id\": \"schema:encodingFormat\",\n          \"@type\": \"xsd:string\"\n        },\n        \"CreatedAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"ModifiedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"MetadataLocation\": {\n          \"@id\": \"s3:MetadataLocation\",\n          \"@type\": \"@id\"\n        },\n        \"WarehouseLocation\": {\n          \"@id\": \"s3:WarehouseLocation\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Tag\": {\n      \"@id\": \"s3:Tag\"\
  ,\n      \"@context\": {\n        \"Key\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"Value\": {\n          \"@id\": \"schema:value\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"Grant\": {\n      \"@id\": \"s3:Grant\",\n      \"@context\": {\n        \"Grantee\": {\n          \"@id\": \"s3:Grantee\",\n          \"@type\": \"@id\"\n        },\n        \"Permission\": {\n          \"@id\": \"s3:Permission\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"StorageLensConfiguration\": {\n      \"@id\": \"s3:API_Types_AWS_S3_Control.html#StorageLensConfiguration\",\n      \"@context\": {\n        \"Id\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"StorageLensArn\": {\n          \"@id\": \"aws:arn\",\n          \"@type\": \"@id\"\n        },\n        \"IsEnabled\": {\n          \"@id\": \"s3:IsEnabled\",\n          \"@type\"\
  : \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"MultiRegionAccessPoint\": {\n      \"@id\": \"s3:API_Types_AWS_S3_Control.html#MultiRegionAccessPoint\",\n      \"@context\": {\n        \"Name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"Alias\": {\n          \"@id\": \"schema:alternateName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"Status\": {\n          \"@id\": \"s3:Status\",\n          \"@type\": \"xsd:string\"\n        },\n        \"CreatedAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"identifier\": \"schema:identifier\",\n    \"url\": \"schema:url\",\n    \"dateCreated\": \"dcterms:created\",\n    \"dateModified\": \"dcterms:modified\",\n    \"contentType\": \"schema:encodingFormat\",\n    \"contentSize\": \"schema:contentSize\",\n    \"owner\"\
  : \"schema:owner\",\n    \"version\": \"schema:version\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-s3/refs/heads/main/json-ld/amazon-s3-context.jsonld
tags:
- Archive
- Backup
- Cloud Storage
- Data Storage
- Object Storage
- Scalable Storage
- JSON-LD
- Linked Data
- Semantic Web
---
