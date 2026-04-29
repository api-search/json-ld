---
api_specs:
- filename: amazon-rds-openapi.yml
  format: yaml
  label: Amazon RDS API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-rds/refs/heads/main/openapi/amazon-rds-openapi.yml
class_count: 12
classes:
- Amazon RDS DB Instance
- CreateDBClusterResponse
- CreateDBInstanceResponse
- CreateDBSnapshotResponse
- DBCluster
- DBInstance
- DBSnapshot
- DescribeDBClustersResponse
- DescribeDBInstancesResponse
- DescribeDBSnapshotsResponse
- ModifyDBInstanceResponse
- Tag
context_file: json-ld/amazon-rds-context-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-rds/refs/heads/main/json-ld/amazon-rds-context-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Rds from Amazon RDS.
layout: jsonld
name: Amazon Rds Context
namespaces:
- prefix: aws
  uri: https://aws.amazon.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: dBInstanceIdentifier
  type: string
- container: ''
  name: dBInstanceClass
  type: string
- container: ''
  name: engine
  type: string
- container: ''
  name: engineVersion
  type: string
- container: ''
  name: dBInstanceStatus
  type: string
- container: ''
  name: masterUsername
  type: string
- container: ''
  name: dBName
  type: string
- container: ''
  name: endpoint
  type: string
- container: ''
  name: allocatedStorage
  type: integer
- container: ''
  name: instanceCreateTime
  type: dateTime
- container: ''
  name: preferredBackupWindow
  type: string
- container: ''
  name: backupRetentionPeriod
  type: integer
- container: set
  name: vpcSecurityGroups
  type: string
- container: ''
  name: availabilityZone
  type: string
- container: ''
  name: dBSubnetGroup
  type: string
- container: ''
  name: multiAZ
  type: boolean
- container: ''
  name: autoMinorVersionUpgrade
  type: boolean
- container: ''
  name: storageType
  type: string
- container: ''
  name: storageEncrypted
  type: boolean
- container: ''
  name: publiclyAccessible
  type: boolean
- container: ''
  name: cACertificateIdentifier
  type: string
- container: ''
  name: dBInstanceArn
  type: string
- container: set
  name: tags
  type: string
- container: ''
  name: port
  type: integer
- container: ''
  name: dBClusterIdentifier
  type: string
- container: ''
  name: licenseModel
  type: string
- container: ''
  name: dBCluster
  type: string
- container: ''
  name: dBInstance
  type: string
- container: ''
  name: dBSnapshot
  type: string
- container: ''
  name: dBClusterArn
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: databaseName
  type: string
- container: ''
  name: readerEndpoint
  type: string
- container: set
  name: dBClusterMembers
  type: string
- container: set
  name: availabilityZones
  type: string
- container: ''
  name: clusterCreateTime
  type: dateTime
- container: ''
  name: dBSnapshotIdentifier
  type: string
- container: ''
  name: snapshotCreateTime
  type: dateTime
- container: ''
  name: vpcId
  type: string
- container: ''
  name: snapshotType
  type: string
- container: ''
  name: encrypted
  type: boolean
- container: ''
  name: dBSnapshotArn
  type: string
- container: set
  name: dBClusters
  type: string
- container: ''
  name: marker
  type: string
- container: set
  name: dBInstances
  type: string
- container: set
  name: dBSnapshots
  type: string
- container: ''
  name: key
  type: string
- container: ''
  name: value
  type: string
property_count: 48
provider_name: Amazon RDS
provider_slug: amazon-rds
slug: amazon-rds-context-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aws\": \"https://aws.amazon.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Amazon RDS DB Instance\": \"aws:Amazon RDS DB Instance\",\n    \"CreateDBClusterResponse\": \"aws:CreateDBClusterResponse\",\n    \"CreateDBInstanceResponse\": \"aws:CreateDBInstanceResponse\",\n    \"CreateDBSnapshotResponse\": \"aws:CreateDBSnapshotResponse\",\n    \"DBCluster\": \"aws:DBCluster\",\n    \"DBInstance\": \"aws:DBInstance\",\n    \"DBSnapshot\": \"aws:DBSnapshot\",\n    \"DescribeDBClustersResponse\": \"aws:DescribeDBClustersResponse\",\n    \"DescribeDBInstancesResponse\": \"aws:DescribeDBInstancesResponse\",\n    \"DescribeDBSnapshotsResponse\": \"aws:DescribeDBSnapshotsResponse\",\n    \"ModifyDBInstanceResponse\": \"aws:ModifyDBInstanceResponse\",\n    \"Tag\": \"aws:Tag\",\n    \"dBInstanceIdentifier\": {\n    \
  \  \"@id\": \"aws:dBInstanceIdentifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dBInstanceClass\": {\n      \"@id\": \"aws:dBInstanceClass\",\n      \"@type\": \"xsd:string\"\n    },\n    \"engine\": {\n      \"@id\": \"aws:engine\",\n      \"@type\": \"xsd:string\"\n    },\n    \"engineVersion\": {\n      \"@id\": \"aws:engineVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dBInstanceStatus\": {\n      \"@id\": \"aws:dBInstanceStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"masterUsername\": {\n      \"@id\": \"aws:masterUsername\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dBName\": {\n      \"@id\": \"aws:dBName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"endpoint\": {\n      \"@id\": \"aws:endpoint\",\n      \"@type\": \"xsd:string\"\n    },\n    \"allocatedStorage\": {\n      \"@id\": \"aws:allocatedStorage\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"instanceCreateTime\": {\n      \"@id\": \"aws:instanceCreateTime\",\n      \"@type\"\
  : \"xsd:dateTime\"\n    },\n    \"preferredBackupWindow\": {\n      \"@id\": \"aws:preferredBackupWindow\",\n      \"@type\": \"xsd:string\"\n    },\n    \"backupRetentionPeriod\": {\n      \"@id\": \"aws:backupRetentionPeriod\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"vpcSecurityGroups\": {\n      \"@id\": \"aws:vpcSecurityGroups\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"availabilityZone\": {\n      \"@id\": \"aws:availabilityZone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dBSubnetGroup\": {\n      \"@id\": \"aws:dBSubnetGroup\",\n      \"@type\": \"xsd:string\"\n    },\n    \"multiAZ\": {\n      \"@id\": \"aws:multiAZ\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"autoMinorVersionUpgrade\": {\n      \"@id\": \"aws:autoMinorVersionUpgrade\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"storageType\": {\n      \"@id\": \"aws:storageType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"storageEncrypted\": {\n      \"\
  @id\": \"aws:storageEncrypted\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"publiclyAccessible\": {\n      \"@id\": \"aws:publiclyAccessible\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"cACertificateIdentifier\": {\n      \"@id\": \"aws:cACertificateIdentifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dBInstanceArn\": {\n      \"@id\": \"aws:dBInstanceArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tags\": {\n      \"@id\": \"aws:tags\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"port\": {\n      \"@id\": \"aws:port\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"dBClusterIdentifier\": {\n      \"@id\": \"aws:dBClusterIdentifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"licenseModel\": {\n      \"@id\": \"aws:licenseModel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dBCluster\": {\n      \"@id\": \"aws:dBCluster\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dBInstance\": {\n      \"@id\": \"aws:dBInstance\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"dBSnapshot\": {\n      \"@id\": \"aws:dBSnapshot\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dBClusterArn\": {\n      \"@id\": \"aws:dBClusterArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"aws:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"databaseName\": {\n      \"@id\": \"aws:databaseName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"readerEndpoint\": {\n      \"@id\": \"aws:readerEndpoint\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dBClusterMembers\": {\n      \"@id\": \"aws:dBClusterMembers\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"availabilityZones\": {\n      \"@id\": \"aws:availabilityZones\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"clusterCreateTime\": {\n      \"@id\": \"aws:clusterCreateTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"dBSnapshotIdentifier\": {\n      \"\
  @id\": \"aws:dBSnapshotIdentifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"snapshotCreateTime\": {\n      \"@id\": \"aws:snapshotCreateTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"vpcId\": {\n      \"@id\": \"aws:vpcId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"snapshotType\": {\n      \"@id\": \"aws:snapshotType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"encrypted\": {\n      \"@id\": \"aws:encrypted\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"dBSnapshotArn\": {\n      \"@id\": \"aws:dBSnapshotArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dBClusters\": {\n      \"@id\": \"aws:dBClusters\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"marker\": {\n      \"@id\": \"aws:marker\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dBInstances\": {\n      \"@id\": \"aws:dBInstances\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dBSnapshots\": {\n      \"@id\": \"aws:dBSnapshots\"\
  ,\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"key\": {\n      \"@id\": \"aws:key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"aws:value\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-rds/refs/heads/main/json-ld/amazon-rds-context-context.jsonld
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
