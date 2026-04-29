---
api_specs:
- filename: amazon-rds-openapi.yml
  format: yaml
  label: Amazon RDS API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-rds/refs/heads/main/openapi/amazon-rds-openapi.yml
class_count: 0
classes: []
context_file: json-ld/amazon-rds-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-rds/refs/heads/main/json-ld/amazon-rds-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Rds from Amazon RDS.
layout: jsonld
name: Amazon Rds Context
namespaces:
- prefix: rds
  uri: https://docs.aws.amazon.com/AmazonRDS/latest/APIReference/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: DBInstance
  type: ''
- container: ''
  name: DBCluster
  type: ''
- container: ''
  name: DBSnapshot
  type: ''
property_count: 3
provider_name: Amazon RDS
provider_slug: amazon-rds
slug: amazon-rds-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"rds\": \"https://docs.aws.amazon.com/AmazonRDS/latest/APIReference/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"DBInstance\": {\n      \"@id\": \"rds:DBInstance\",\n      \"@context\": {\n        \"dBInstanceIdentifier\": \"rds:dBInstanceIdentifier\",\n        \"dBInstanceClass\": \"rds:dBInstanceClass\",\n        \"engine\": \"rds:engine\",\n        \"engineVersion\": \"rds:engineVersion\",\n        \"dBInstanceStatus\": \"rds:dBInstanceStatus\",\n        \"masterUsername\": \"rds:masterUsername\",\n        \"dBName\": \"rds:dBName\",\n        \"endpoint\": \"rds:endpoint\",\n        \"allocatedStorage\": {\n          \"@id\": \"rds:allocatedStorage\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"instanceCreateTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\
  \n        },\n        \"availabilityZone\": \"rds:availabilityZone\",\n        \"multiAZ\": {\n          \"@id\": \"rds:multiAZ\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"storageType\": \"rds:storageType\",\n        \"storageEncrypted\": {\n          \"@id\": \"rds:storageEncrypted\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"dBInstanceArn\": {\n          \"@id\": \"rds:dBInstanceArn\",\n          \"@type\": \"@id\"\n        },\n        \"tags\": {\n          \"@id\": \"rds:tags\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"DBCluster\": {\n      \"@id\": \"rds:DBCluster\",\n      \"@context\": {\n        \"dBClusterIdentifier\": \"rds:dBClusterIdentifier\",\n        \"dBClusterArn\": {\n          \"@id\": \"rds:dBClusterArn\",\n          \"@type\": \"@id\"\n        },\n        \"status\": \"rds:status\",\n        \"engine\": \"rds:engine\",\n        \"engineVersion\": \"rds:engineVersion\",\n        \"databaseName\"\
  : \"rds:databaseName\",\n        \"masterUsername\": \"rds:masterUsername\",\n        \"endpoint\": \"rds:endpoint\",\n        \"readerEndpoint\": \"rds:readerEndpoint\",\n        \"port\": {\n          \"@id\": \"rds:port\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"clusterCreateTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"multiAZ\": {\n          \"@id\": \"rds:multiAZ\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"storageEncrypted\": {\n          \"@id\": \"rds:storageEncrypted\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"dBClusterMembers\": {\n          \"@id\": \"rds:dBClusterMembers\",\n          \"@container\": \"@set\"\n        },\n        \"availabilityZones\": {\n          \"@id\": \"rds:availabilityZones\",\n          \"@container\": \"@list\"\n        },\n        \"tags\": {\n          \"@id\": \"rds:tags\",\n          \"@container\": \"@set\"\n        }\n\
  \      }\n    },\n\n    \"DBSnapshot\": {\n      \"@id\": \"rds:DBSnapshot\",\n      \"@context\": {\n        \"dBSnapshotIdentifier\": \"rds:dBSnapshotIdentifier\",\n        \"dBInstanceIdentifier\": \"rds:dBInstanceIdentifier\",\n        \"snapshotCreateTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"engine\": \"rds:engine\",\n        \"engineVersion\": \"rds:engineVersion\",\n        \"status\": \"rds:status\",\n        \"allocatedStorage\": {\n          \"@id\": \"rds:allocatedStorage\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"availabilityZone\": \"rds:availabilityZone\",\n        \"snapshotType\": \"rds:snapshotType\",\n        \"encrypted\": {\n          \"@id\": \"rds:encrypted\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"dBSnapshotArn\": {\n          \"@id\": \"rds:dBSnapshotArn\",\n          \"@type\": \"@id\"\n        },\n        \"tags\": {\n          \"@id\": \"rds:tags\"\
  ,\n          \"@container\": \"@set\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-rds/refs/heads/main/json-ld/amazon-rds-context.jsonld
tags:
- AWS
- Cloud Databases
- Database Service
- DBaaS
- Managed Databases
- Relational Databases
- JSON-LD
- Linked Data
- Semantic Web
---
