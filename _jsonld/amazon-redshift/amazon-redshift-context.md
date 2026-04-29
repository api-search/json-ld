---
api_specs:
- filename: amazon-redshift-data-api-openapi.yml
  format: yaml
  label: Amazon Redshift Data API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-redshift/refs/heads/main/openapi/amazon-redshift-data-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/amazon-redshift-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-redshift/refs/heads/main/json-ld/amazon-redshift-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Redshift from Amazon Redshift.
layout: jsonld
name: Amazon Redshift Context
namespaces:
- prefix: aws
  uri: https://aws.amazon.com/ns/
- prefix: redshift
  uri: https://aws.amazon.com/ns/redshift/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Cluster
  type: ''
- container: ''
  name: Endpoint
  type: ''
- container: ''
  name: Workgroup
  type: ''
- container: ''
  name: Namespace
  type: ''
- container: ''
  name: Snapshot
  type: ''
- container: ''
  name: StatementExecution
  type: ''
property_count: 6
provider_name: Amazon Redshift
provider_slug: amazon-redshift
slug: amazon-redshift-context
source_filename: amazon-redshift-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aws\": \"https://aws.amazon.com/ns/\",\n    \"redshift\": \"https://aws.amazon.com/ns/redshift/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Cluster\": {\n      \"@id\": \"redshift:Cluster\",\n      \"@context\": {\n        \"clusterIdentifier\": {\n          \"@id\": \"redshift:clusterIdentifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"clusterStatus\": {\n          \"@id\": \"redshift:clusterStatus\",\n          \"@type\": \"xsd:string\"\n        },\n        \"nodeType\": {\n          \"@id\": \"redshift:nodeType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"numberOfNodes\": {\n          \"@id\": \"redshift:numberOfNodes\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"dbName\": {\n          \"@id\": \"redshift:dbName\",\n          \"@type\": \"xsd:string\"\n\
  \        },\n        \"masterUsername\": {\n          \"@id\": \"redshift:masterUsername\",\n          \"@type\": \"xsd:string\"\n        },\n        \"endpoint\": {\n          \"@id\": \"redshift:endpoint\",\n          \"@type\": \"@id\"\n        },\n        \"clusterCreateTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"vpcId\": {\n          \"@id\": \"redshift:vpcId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"availabilityZone\": {\n          \"@id\": \"redshift:availabilityZone\",\n          \"@type\": \"xsd:string\"\n        },\n        \"encrypted\": {\n          \"@id\": \"redshift:encrypted\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"kmsKeyId\": {\n          \"@id\": \"redshift:kmsKeyId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"publiclyAccessible\": {\n          \"@id\": \"redshift:publiclyAccessible\",\n          \"@type\": \"xsd:boolean\"\n        },\n  \
  \      \"enhancedVpcRouting\": {\n          \"@id\": \"redshift:enhancedVpcRouting\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"clusterVersion\": {\n          \"@id\": \"schema:softwareVersion\",\n          \"@type\": \"xsd:string\"\n        },\n        \"clusterNamespaceArn\": {\n          \"@id\": \"aws:arn\",\n          \"@type\": \"@id\"\n        },\n        \"tags\": {\n          \"@id\": \"schema:keywords\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Endpoint\": {\n      \"@id\": \"redshift:Endpoint\",\n      \"@context\": {\n        \"address\": {\n          \"@id\": \"redshift:endpointAddress\",\n          \"@type\": \"xsd:string\"\n        },\n        \"port\": {\n          \"@id\": \"redshift:endpointPort\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"Workgroup\": {\n      \"@id\": \"redshift:Workgroup\",\n      \"@context\": {\n        \"workgroupName\": {\n          \"@id\": \"schema:name\",\n \
  \         \"@type\": \"xsd:string\"\n        },\n        \"workgroupArn\": {\n          \"@id\": \"aws:arn\",\n          \"@type\": \"@id\"\n        },\n        \"namespaceName\": {\n          \"@id\": \"redshift:namespaceName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"status\": {\n          \"@id\": \"redshift:workgroupStatus\",\n          \"@type\": \"xsd:string\"\n        },\n        \"baseCapacity\": {\n          \"@id\": \"redshift:baseCapacity\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"maxCapacity\": {\n          \"@id\": \"redshift:maxCapacity\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"endpoint\": {\n          \"@id\": \"redshift:endpoint\",\n          \"@type\": \"@id\"\n        },\n        \"publiclyAccessible\": {\n          \"@id\": \"redshift:publiclyAccessible\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"enhancedVpcRouting\": {\n          \"@id\": \"redshift:enhancedVpcRouting\",\n          \"\
  @type\": \"xsd:boolean\"\n        },\n        \"creationDate\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Namespace\": {\n      \"@id\": \"redshift:Namespace\",\n      \"@context\": {\n        \"namespaceName\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"namespaceArn\": {\n          \"@id\": \"aws:arn\",\n          \"@type\": \"@id\"\n        },\n        \"namespaceId\": {\n          \"@id\": \"redshift:namespaceId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"dbName\": {\n          \"@id\": \"redshift:dbName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"adminUsername\": {\n          \"@id\": \"redshift:adminUsername\",\n          \"@type\": \"xsd:string\"\n        },\n        \"status\": {\n          \"@id\": \"redshift:namespaceStatus\",\n          \"@type\": \"xsd:string\"\n        },\n        \"kmsKeyId\": {\n       \
  \   \"@id\": \"redshift:kmsKeyId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"creationDate\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"iamRoles\": {\n          \"@id\": \"redshift:iamRoles\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Snapshot\": {\n      \"@id\": \"redshift:Snapshot\",\n      \"@context\": {\n        \"snapshotIdentifier\": {\n          \"@id\": \"redshift:snapshotIdentifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"clusterIdentifier\": {\n          \"@id\": \"redshift:clusterIdentifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"snapshotCreateTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"status\": {\n          \"@id\": \"redshift:snapshotStatus\",\n          \"@type\": \"xsd:string\"\n        },\n        \"snapshotType\": {\n          \"@id\": \"redshift:snapshotType\"\
  ,\n          \"@type\": \"xsd:string\"\n        },\n        \"nodeType\": {\n          \"@id\": \"redshift:nodeType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"numberOfNodes\": {\n          \"@id\": \"redshift:numberOfNodes\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"dbName\": {\n          \"@id\": \"redshift:dbName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"masterUsername\": {\n          \"@id\": \"redshift:masterUsername\",\n          \"@type\": \"xsd:string\"\n        },\n        \"encrypted\": {\n          \"@id\": \"redshift:encrypted\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"totalBackupSizeInMegaBytes\": {\n          \"@id\": \"redshift:totalBackupSizeInMegaBytes\",\n          \"@type\": \"xsd:double\"\n        },\n        \"currentBackupRateInMegaBytesPerSecond\": {\n          \"@id\": \"redshift:currentBackupRateInMegaBytesPerSecond\",\n          \"@type\": \"xsd:double\"\n        }\n      }\n    },\n\
  \n    \"StatementExecution\": {\n      \"@id\": \"redshift:StatementExecution\",\n      \"@context\": {\n        \"statementId\": {\n          \"@id\": \"redshift:statementId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"statementName\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"status\": {\n          \"@id\": \"redshift:statementStatus\",\n          \"@type\": \"xsd:string\"\n        },\n        \"queryString\": {\n          \"@id\": \"redshift:queryString\",\n          \"@type\": \"xsd:string\"\n        },\n        \"database\": {\n          \"@id\": \"redshift:database\",\n          \"@type\": \"xsd:string\"\n        },\n        \"clusterIdentifier\": {\n          \"@id\": \"redshift:clusterIdentifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"workgroupName\": {\n          \"@id\": \"redshift:workgroupName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"createdAt\": {\n     \
  \     \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"duration\": {\n          \"@id\": \"redshift:durationNanoseconds\",\n          \"@type\": \"xsd:long\"\n        },\n        \"resultRows\": {\n          \"@id\": \"redshift:resultRows\",\n          \"@type\": \"xsd:long\"\n        },\n        \"resultSize\": {\n          \"@id\": \"redshift:resultSizeBytes\",\n          \"@type\": \"xsd:long\"\n        },\n        \"hasResultSet\": {\n          \"@id\": \"redshift:hasResultSet\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"error\": {\n          \"@id\": \"redshift:errorMessage\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-redshift/refs/heads/main/json-ld/amazon-redshift-context.jsonld
tags:
- Analytics
- Big Data
- Cloud
- Data Lake
- Data Warehouse
- ETL
- Machine Learning
- Serverless
- SQL
- JSON-LD
- Linked Data
- Semantic Web
---
