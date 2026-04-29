---
class_count: 0
classes: []
context_file: json-ld/amazon-aurora-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-aurora/refs/heads/main/json-ld/amazon-aurora-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Aurora from Amazon Aurora.
layout: jsonld
name: Amazon Aurora Context
namespaces:
- prefix: rds
  uri: https://docs.aws.amazon.com/AmazonRDS/latest/APIReference/
- prefix: aws
  uri: https://aws.amazon.com/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: rdfs
  uri: http://www.w3.org/2000/01/rdf-schema#
properties:
- container: ''
  name: DBCluster
  type: ''
- container: ''
  name: DBClusterMember
  type: ''
- container: ''
  name: DBInstance
  type: ''
- container: ''
  name: DBClusterSnapshot
  type: ''
property_count: 4
provider_name: Amazon Aurora
provider_slug: amazon-aurora
slug: amazon-aurora-context
source_filename: amazon-aurora-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"rds\": \"https://docs.aws.amazon.com/AmazonRDS/latest/APIReference/\",\n    \"aws\": \"https://aws.amazon.com/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"rdfs\": \"http://www.w3.org/2000/01/rdf-schema#\",\n\n    \"DBCluster\": {\n      \"@id\": \"rds:API_DBCluster\",\n      \"@context\": {\n        \"DBClusterIdentifier\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"DBClusterArn\": {\n          \"@id\": \"rds:DBClusterArn\",\n          \"@type\": \"xsd:string\"\n        },\n        \"Engine\": {\n          \"@id\": \"rds:Engine\",\n          \"@type\": \"xsd:string\"\n        },\n        \"EngineVersion\": {\n          \"@id\": \"schema:version\",\n          \"@type\": \"xsd:string\"\n        },\n        \"Status\": {\n          \"@id\"\
  : \"rds:DBClusterStatus\",\n          \"@type\": \"xsd:string\"\n        },\n        \"Endpoint\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"xsd:string\"\n        },\n        \"ReaderEndpoint\": {\n          \"@id\": \"rds:ReaderEndpoint\",\n          \"@type\": \"xsd:string\"\n        },\n        \"Port\": {\n          \"@id\": \"rds:Port\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"MasterUsername\": {\n          \"@id\": \"rds:MasterUsername\",\n          \"@type\": \"xsd:string\"\n        },\n        \"DatabaseName\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"StorageEncrypted\": {\n          \"@id\": \"rds:StorageEncrypted\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"DeletionProtection\": {\n          \"@id\": \"rds:DeletionProtection\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"BackupRetentionPeriod\": {\n          \"@id\": \"rds:BackupRetentionPeriod\"\
  ,\n          \"@type\": \"xsd:integer\"\n        },\n        \"ClusterCreateTime\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"AvailabilityZones\": {\n          \"@id\": \"rds:AvailabilityZones\",\n          \"@container\": \"@list\"\n        },\n        \"DBClusterMembers\": {\n          \"@id\": \"rds:DBClusterMembers\",\n          \"@container\": \"@list\"\n        },\n        \"VpcSecurityGroups\": {\n          \"@id\": \"rds:VpcSecurityGroups\",\n          \"@container\": \"@list\"\n        },\n        \"tags\": {\n          \"@id\": \"schema:keywords\",\n          \"@container\": \"@list\"\n        }\n      }\n    },\n\n    \"DBClusterMember\": {\n      \"@id\": \"rds:DBClusterMember\",\n      \"@context\": {\n        \"DBInstanceIdentifier\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"IsClusterWriter\": {\n          \"@id\": \"rds:IsClusterWriter\",\n  \
  \        \"@type\": \"xsd:boolean\"\n        },\n        \"PromotionTier\": {\n          \"@id\": \"rds:PromotionTier\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"DBInstance\": {\n      \"@id\": \"rds:API_DBInstance\",\n      \"@context\": {\n        \"DBInstanceIdentifier\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"DBInstanceClass\": {\n          \"@id\": \"rds:DBInstanceClass\",\n          \"@type\": \"xsd:string\"\n        },\n        \"Engine\": {\n          \"@id\": \"rds:Engine\",\n          \"@type\": \"xsd:string\"\n        },\n        \"DBInstanceStatus\": {\n          \"@id\": \"rds:DBInstanceStatus\",\n          \"@type\": \"xsd:string\"\n        },\n        \"DBClusterIdentifier\": {\n          \"@id\": \"rds:DBClusterIdentifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"AvailabilityZone\": {\n          \"@id\": \"rds:AvailabilityZone\",\n          \"@type\"\
  : \"xsd:string\"\n        },\n        \"InstanceCreateTime\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"DBClusterSnapshot\": {\n      \"@id\": \"rds:API_DBClusterSnapshot\",\n      \"@context\": {\n        \"DBClusterSnapshotIdentifier\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"DBClusterIdentifier\": {\n          \"@id\": \"rds:DBClusterIdentifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"SnapshotCreateTime\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"Engine\": {\n          \"@id\": \"rds:Engine\",\n          \"@type\": \"xsd:string\"\n        },\n        \"Status\": {\n          \"@id\": \"rds:SnapshotStatus\",\n          \"@type\": \"xsd:string\"\n        },\n        \"SnapshotType\": {\n          \"@id\": \"rds:SnapshotType\",\n          \"@type\": \"xsd:string\"\
  \n        },\n        \"StorageEncrypted\": {\n          \"@id\": \"rds:StorageEncrypted\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-aurora/refs/heads/main/json-ld/amazon-aurora-context.jsonld
tags:
- Amazon Aurora
- MySQL
- PostgreSQL
- Relational Database
- AWS
- JSON-LD
- Linked Data
- Semantic Web
---
