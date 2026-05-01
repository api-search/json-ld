---
api_specs:
- filename: amazon-neptune-management-openapi.yml
  format: yaml
  label: Amazon Neptune Management API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-neptune/refs/heads/main/openapi/amazon-neptune-management-openapi.yml
- filename: amazon-neptune-data-openapi.yml
  format: yaml
  label: Amazon Neptune Data API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-neptune/refs/heads/main/openapi/amazon-neptune-data-openapi.yml
- filename: amazon-neptune-gremlin-openapi.yml
  format: yaml
  label: Neptune Gremlin API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-neptune/refs/heads/main/openapi/amazon-neptune-gremlin-openapi.yml
- filename: amazon-neptune-sparql-openapi.yml
  format: yaml
  label: Neptune SPARQL API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-neptune/refs/heads/main/openapi/amazon-neptune-sparql-openapi.yml
- filename: amazon-neptune-opencypher-openapi.yml
  format: yaml
  label: Neptune openCypher API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-neptune/refs/heads/main/openapi/amazon-neptune-opencypher-openapi.yml
- filename: amazon-neptune-streams-openapi.yml
  format: yaml
  label: Neptune Streams API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-neptune/refs/heads/main/openapi/amazon-neptune-streams-openapi.yml
- filename: amazon-neptune-loader-openapi.yml
  format: yaml
  label: Neptune Loader API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-neptune/refs/heads/main/openapi/amazon-neptune-loader-openapi.yml
- filename: amazon-neptune-ml-openapi.yml
  format: yaml
  label: Neptune ML API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-neptune/refs/heads/main/openapi/amazon-neptune-ml-openapi.yml
- filename: amazon-neptune-analytics-openapi.yml
  format: yaml
  label: Neptune Analytics API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-neptune/refs/heads/main/openapi/amazon-neptune-analytics-openapi.yml
class_count: 14
classes:
- CreateDBClusterRequest
- CreateDBInstanceRequest
- DBCluster
- DBClusterMember
- DBClusterRole
- DBClusterSnapshot
- DBInstance
- DescribeDBClusterSnapshotsResponse
- DescribeDBClustersResponse
- DescribeDBInstancesResponse
- DescribeDBSubnetGroupsResponse
- ModifyDBClusterRequest
- ModifyDBInstanceRequest
- RestoreDBClusterFromSnapshotRequest
context_file: json-ld/amazon-neptune-management-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-neptune/refs/heads/main/json-ld/amazon-neptune-management-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Neptune Management from Amazon Neptune.
layout: jsonld
name: Amazon Neptune Management Context
namespaces:
- prefix: neptune
  uri: https://neptune.dev/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: DBSubnetGroup
  type: string
- container: ''
  name: Address
  type: string
- container: ''
  name: AllocatedStorage
  type: integer
- container: ''
  name: ApplyImmediately
  type: boolean
- container: set
  name: AssociatedRoles
  type: string
- container: ''
  name: AutoMinorVersionUpgrade
  type: boolean
- container: ''
  name: AvailabilityZone
  type: string
- container: ''
  name: BackupRetentionPeriod
  type: integer
- container: ''
  name: ClusterCreateTime
  type: dateTime
- container: ''
  name: DBClusterArn
  type: string
- container: ''
  name: DBClusterIdentifier
  type: string
- container: set
  name: DBClusterMembers
  type: string
- container: ''
  name: DBClusterParameterGroup
  type: string
- container: ''
  name: DBClusterParameterGroupName
  type: string
- container: ''
  name: DBClusterParameterGroupStatus
  type: string
- container: ''
  name: DBClusterSnapshotArn
  type: string
- container: ''
  name: DBClusterSnapshotIdentifier
  type: string
- container: set
  name: DBClusterSnapshots
  type: string
- container: set
  name: DBClusters
  type: string
- container: ''
  name: DBInstanceArn
  type: string
- container: ''
  name: DBInstanceClass
  type: string
- container: ''
  name: DBInstanceIdentifier
  type: string
- container: ''
  name: DBInstanceStatus
  type: string
- container: set
  name: DBInstances
  type: string
- container: ''
  name: DBSubnetGroupArn
  type: string
- container: ''
  name: DBSubnetGroupDescription
  type: string
- container: ''
  name: DBSubnetGroupName
  type: string
- container: set
  name: DBSubnetGroups
  type: string
- container: ''
  name: DeletionProtection
  type: boolean
- container: ''
  name: Endpoint
  type: reference
- container: ''
  name: Engine
  type: string
- container: ''
  name: EngineVersion
  type: string
- container: ''
  name: IAMDatabaseAuthenticationEnabled
  type: boolean
- container: ''
  name: IsClusterWriter
  type: boolean
- container: ''
  name: KmsKeyId
  type: string
- container: ''
  name: Marker
  type: string
- container: ''
  name: MasterUsername
  type: string
- container: ''
  name: MultiAZ
  type: boolean
- container: ''
  name: NewDBClusterIdentifier
  type: string
- container: ''
  name: NewDBInstanceIdentifier
  type: string
- container: ''
  name: Port
  type: integer
- container: ''
  name: PreferredBackupWindow
  type: string
- container: ''
  name: PreferredMaintenanceWindow
  type: string
- container: ''
  name: PromotionTier
  type: integer
- container: ''
  name: PubliclyAccessible
  type: boolean
- container: ''
  name: ReaderEndpoint
  type: string
- container: ''
  name: RoleArn
  type: string
- container: ''
  name: SnapshotCreateTime
  type: dateTime
- container: ''
  name: SnapshotIdentifier
  type: string
- container: ''
  name: SnapshotType
  type: string
- container: ''
  name: Status
  type: string
- container: ''
  name: StorageEncrypted
  type: boolean
- container: ''
  name: SubnetGroupStatus
  type: string
- container: set
  name: Subnets
  type: reference
- container: ''
  name: VpcId
  type: string
- container: set
  name: VpcSecurityGroupIds
  type: string
property_count: 56
provider_name: Amazon Neptune
provider_slug: amazon-neptune
slug: amazon-neptune-management-context
source_filename: amazon-neptune-management-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"neptune\": \"https://neptune.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"CreateDBClusterRequest\": \"neptune:CreateDBClusterRequest\",\n    \"CreateDBInstanceRequest\": \"neptune:CreateDBInstanceRequest\",\n    \"DBCluster\": \"neptune:DBCluster\",\n    \"DBClusterMember\": \"neptune:DBClusterMember\",\n    \"DBClusterRole\": \"neptune:DBClusterRole\",\n    \"DBClusterSnapshot\": \"neptune:DBClusterSnapshot\",\n    \"DBInstance\": \"neptune:DBInstance\",\n    \"DBSubnetGroup\": {\n      \"@id\": \"neptune:DBSubnetGroup\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DescribeDBClusterSnapshotsResponse\": \"neptune:DescribeDBClusterSnapshotsResponse\",\n    \"DescribeDBClustersResponse\": \"neptune:DescribeDBClustersResponse\",\n    \"DescribeDBInstancesResponse\": \"neptune:DescribeDBInstancesResponse\"\
  ,\n    \"DescribeDBSubnetGroupsResponse\": \"neptune:DescribeDBSubnetGroupsResponse\",\n    \"ModifyDBClusterRequest\": \"neptune:ModifyDBClusterRequest\",\n    \"ModifyDBInstanceRequest\": \"neptune:ModifyDBInstanceRequest\",\n    \"RestoreDBClusterFromSnapshotRequest\": \"neptune:RestoreDBClusterFromSnapshotRequest\",\n    \"Address\": {\n      \"@id\": \"neptune:Address\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AllocatedStorage\": {\n      \"@id\": \"neptune:AllocatedStorage\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"ApplyImmediately\": {\n      \"@id\": \"neptune:ApplyImmediately\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"AssociatedRoles\": {\n      \"@id\": \"neptune:AssociatedRoles\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AutoMinorVersionUpgrade\": {\n      \"@id\": \"neptune:AutoMinorVersionUpgrade\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"AvailabilityZone\": {\n      \"@id\": \"neptune:AvailabilityZone\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"BackupRetentionPeriod\": {\n      \"@id\": \"neptune:BackupRetentionPeriod\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"ClusterCreateTime\": {\n      \"@id\": \"neptune:ClusterCreateTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"DBClusterArn\": {\n      \"@id\": \"neptune:DBClusterArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DBClusterIdentifier\": {\n      \"@id\": \"neptune:DBClusterIdentifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DBClusterMembers\": {\n      \"@id\": \"neptune:DBClusterMembers\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DBClusterParameterGroup\": {\n      \"@id\": \"neptune:DBClusterParameterGroup\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DBClusterParameterGroupName\": {\n      \"@id\": \"neptune:DBClusterParameterGroupName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DBClusterParameterGroupStatus\": {\n      \"@id\": \"neptune:DBClusterParameterGroupStatus\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"DBClusterSnapshotArn\": {\n      \"@id\": \"neptune:DBClusterSnapshotArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DBClusterSnapshotIdentifier\": {\n      \"@id\": \"neptune:DBClusterSnapshotIdentifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DBClusterSnapshots\": {\n      \"@id\": \"neptune:DBClusterSnapshots\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DBClusters\": {\n      \"@id\": \"neptune:DBClusters\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DBInstanceArn\": {\n      \"@id\": \"neptune:DBInstanceArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DBInstanceClass\": {\n      \"@id\": \"neptune:DBInstanceClass\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DBInstanceIdentifier\": {\n      \"@id\": \"neptune:DBInstanceIdentifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DBInstanceStatus\": {\n      \"@id\": \"neptune:DBInstanceStatus\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"DBInstances\": {\n      \"@id\": \"neptune:DBInstances\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DBSubnetGroupArn\": {\n      \"@id\": \"neptune:DBSubnetGroupArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DBSubnetGroupDescription\": {\n      \"@id\": \"neptune:DBSubnetGroupDescription\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DBSubnetGroupName\": {\n      \"@id\": \"neptune:DBSubnetGroupName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DBSubnetGroups\": {\n      \"@id\": \"neptune:DBSubnetGroups\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DeletionProtection\": {\n      \"@id\": \"neptune:DeletionProtection\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"Endpoint\": {\n      \"@id\": \"neptune:Endpoint\",\n      \"@type\": \"@id\"\n    },\n    \"Engine\": {\n      \"@id\": \"neptune:Engine\",\n      \"@type\": \"xsd:string\"\n   \
  \ },\n    \"EngineVersion\": {\n      \"@id\": \"neptune:EngineVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"IAMDatabaseAuthenticationEnabled\": {\n      \"@id\": \"neptune:IAMDatabaseAuthenticationEnabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"IsClusterWriter\": {\n      \"@id\": \"neptune:IsClusterWriter\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"KmsKeyId\": {\n      \"@id\": \"neptune:KmsKeyId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Marker\": {\n      \"@id\": \"neptune:Marker\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MasterUsername\": {\n      \"@id\": \"neptune:MasterUsername\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MultiAZ\": {\n      \"@id\": \"neptune:MultiAZ\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"NewDBClusterIdentifier\": {\n      \"@id\": \"neptune:NewDBClusterIdentifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"NewDBInstanceIdentifier\": {\n      \"@id\": \"neptune:NewDBInstanceIdentifier\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"Port\": {\n      \"@id\": \"neptune:Port\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"PreferredBackupWindow\": {\n      \"@id\": \"neptune:PreferredBackupWindow\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PreferredMaintenanceWindow\": {\n      \"@id\": \"neptune:PreferredMaintenanceWindow\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PromotionTier\": {\n      \"@id\": \"neptune:PromotionTier\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"PubliclyAccessible\": {\n      \"@id\": \"neptune:PubliclyAccessible\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"ReaderEndpoint\": {\n      \"@id\": \"neptune:ReaderEndpoint\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RoleArn\": {\n      \"@id\": \"neptune:RoleArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SnapshotCreateTime\": {\n      \"@id\": \"neptune:SnapshotCreateTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"SnapshotIdentifier\": {\n     \
  \ \"@id\": \"neptune:SnapshotIdentifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SnapshotType\": {\n      \"@id\": \"neptune:SnapshotType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Status\": {\n      \"@id\": \"neptune:Status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"StorageEncrypted\": {\n      \"@id\": \"neptune:StorageEncrypted\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"SubnetGroupStatus\": {\n      \"@id\": \"neptune:SubnetGroupStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Subnets\": {\n      \"@id\": \"neptune:Subnets\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"VpcId\": {\n      \"@id\": \"neptune:VpcId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"VpcSecurityGroupIds\": {\n      \"@id\": \"neptune:VpcSecurityGroupIds\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-neptune/refs/heads/main/json-ld/amazon-neptune-management-context.jsonld
tags:
- Database
- Graph Database
- Gremlin
- Neptune
- Property Graph
- RDF
- SPARQL
- JSON-LD
- Linked Data
- Semantic Web
---
