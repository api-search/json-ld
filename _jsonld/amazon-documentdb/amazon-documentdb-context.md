---
api_specs:
- filename: amazon-documentdb-openapi.yml
  format: yaml
  label: Amazon DocumentDB API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-documentdb/refs/heads/main/openapi/amazon-documentdb-openapi.yml
class_count: 3
classes:
- Amazon DocumentDB DBCluster
- CreateDBClusterResult
- DescribeDBClustersResult
context_file: json-ld/amazon-documentdb-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-documentdb/refs/heads/main/json-ld/amazon-documentdb-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Documentdb from Amazon DocumentDB.
layout: jsonld
name: Amazon Documentdb Context
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
  name: DBCluster
  type: string
- container: ''
  name: DBClusterIdentifier
  type: string
- container: ''
  name: DBClusterArn
  type: string
- container: ''
  name: Status
  type: string
- container: ''
  name: Engine
  type: string
- container: ''
  name: EngineVersion
  type: string
- container: ''
  name: Endpoint
  type: string
- container: ''
  name: ReaderEndpoint
  type: string
- container: ''
  name: Port
  type: integer
- container: ''
  name: MasterUsername
  type: string
- container: ''
  name: DBSubnetGroup
  type: string
- container: ''
  name: StorageEncrypted
  type: boolean
- container: ''
  name: KmsKeyId
  type: string
- container: ''
  name: BackupRetentionPeriod
  type: integer
- container: ''
  name: PreferredBackupWindow
  type: string
- container: ''
  name: PreferredMaintenanceWindow
  type: string
- container: ''
  name: ClusterCreateTime
  type: dateTime
- container: set
  name: DBClusterMembers
  type: string
- container: set
  name: VpcSecurityGroups
  type: string
- container: ''
  name: DeletionProtection
  type: boolean
- container: set
  name: EnabledCloudwatchLogsExports
  type: string
- container: ''
  name: DBInstanceIdentifier
  type: string
- container: ''
  name: IsClusterWriter
  type: boolean
- container: ''
  name: DBClusterParameterGroupStatus
  type: string
- container: ''
  name: PromotionTier
  type: integer
- container: ''
  name: VpcSecurityGroupId
  type: string
- container: set
  name: DBClusters
  type: string
- container: ''
  name: Marker
  type: string
property_count: 28
provider_name: Amazon DocumentDB
provider_slug: amazon-documentdb
slug: amazon-documentdb-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aws\": \"https://aws.amazon.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"pan\": \"https://aws.amazon.com/schema/\",\n    \"Amazon DocumentDB DBCluster\": \"aws:Amazon DocumentDB DBCluster\",\n    \"CreateDBClusterResult\": \"aws:CreateDBClusterResult\",\n    \"DBCluster\": {\n      \"@id\": \"pan:DBCluster\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DescribeDBClustersResult\": \"aws:DescribeDBClustersResult\",\n    \"DBClusterIdentifier\": {\n      \"@id\": \"pan:DBClusterIdentifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DBClusterArn\": {\n      \"@id\": \"pan:DBClusterArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Status\": {\n      \"@id\": \"pan:Status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Engine\": {\n      \"@id\": \"pan:Engine\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"EngineVersion\": {\n      \"@id\": \"pan:EngineVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Endpoint\": {\n      \"@id\": \"pan:Endpoint\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ReaderEndpoint\": {\n      \"@id\": \"pan:ReaderEndpoint\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Port\": {\n      \"@id\": \"pan:Port\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"MasterUsername\": {\n      \"@id\": \"pan:MasterUsername\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DBSubnetGroup\": {\n      \"@id\": \"pan:DBSubnetGroup\",\n      \"@type\": \"xsd:string\"\n    },\n    \"StorageEncrypted\": {\n      \"@id\": \"pan:StorageEncrypted\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"KmsKeyId\": {\n      \"@id\": \"pan:KmsKeyId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"BackupRetentionPeriod\": {\n      \"@id\": \"pan:BackupRetentionPeriod\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"PreferredBackupWindow\": {\n      \"@id\"\
  : \"pan:PreferredBackupWindow\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PreferredMaintenanceWindow\": {\n      \"@id\": \"pan:PreferredMaintenanceWindow\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ClusterCreateTime\": {\n      \"@id\": \"pan:ClusterCreateTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"DBClusterMembers\": {\n      \"@id\": \"pan:DBClusterMembers\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"VpcSecurityGroups\": {\n      \"@id\": \"pan:VpcSecurityGroups\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DeletionProtection\": {\n      \"@id\": \"pan:DeletionProtection\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"EnabledCloudwatchLogsExports\": {\n      \"@id\": \"pan:EnabledCloudwatchLogsExports\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DBInstanceIdentifier\": {\n      \"@id\": \"pan:DBInstanceIdentifier\",\n      \"@type\": \"\
  xsd:string\"\n    },\n    \"IsClusterWriter\": {\n      \"@id\": \"pan:IsClusterWriter\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"DBClusterParameterGroupStatus\": {\n      \"@id\": \"pan:DBClusterParameterGroupStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PromotionTier\": {\n      \"@id\": \"pan:PromotionTier\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"VpcSecurityGroupId\": {\n      \"@id\": \"pan:VpcSecurityGroupId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DBClusters\": {\n      \"@id\": \"pan:DBClusters\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Marker\": {\n      \"@id\": \"pan:Marker\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-documentdb/refs/heads/main/json-ld/amazon-documentdb-context.jsonld
tags:
- Amazon Web Services
- AWS
- Database
- Document Database
- DocumentDB
- Managed Database
- MongoDB
- NoSQL
- JSON-LD
- Linked Data
- Semantic Web
---
