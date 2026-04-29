---
api_specs:
- filename: cubefs-s3-api-openapi.yml
  format: yaml
  label: CubeFS S3-Compatible API
  slug: cubefs-s3-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/cubefs/refs/heads/main/openapi/cubefs-s3-api-openapi.yml
- filename: cubefs-master-api-openapi.yml
  format: yaml
  label: CubeFS Master API
  slug: cubefs-master-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/cubefs/refs/heads/main/openapi/cubefs-master-api-openapi.yml
class_count: 3
classes:
- name
- description
- id
context_file: json-ld/cubefs-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/cubefs/refs/heads/main/json-ld/cubefs-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Cubefs from CubeFS.
layout: jsonld
name: Cubefs Context
namespaces:
- prefix: cubefs
  uri: https://cubefs.io/vocab#
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: rdfs
  uri: http://www.w3.org/2000/01/rdf-schema#
- prefix: skos
  uri: http://www.w3.org/2004/02/skos/core#
- prefix: cncf
  uri: https://www.cncf.io/projects/
properties:
- container: ''
  name: Volume
  type: ''
- container: ''
  name: DataPartition
  type: ''
- container: ''
  name: MetaPartition
  type: ''
- container: ''
  name: DataNode
  type: ''
- container: ''
  name: MetaNode
  type: ''
- container: ''
  name: User
  type: ''
- container: ''
  name: Cluster
  type: ''
- container: ''
  name: created
  type: dateTime
- container: ''
  name: modified
  type: dateTime
property_count: 9
provider_name: CubeFS
provider_slug: cubefs
slug: cubefs-context
source_filename: cubefs-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"cubefs\": \"https://cubefs.io/vocab#\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"rdfs\": \"http://www.w3.org/2000/01/rdf-schema#\",\n    \"skos\": \"http://www.w3.org/2004/02/skos/core#\",\n    \"cncf\": \"https://www.cncf.io/projects/\",\n\n    \"Volume\": {\n      \"@id\": \"cubefs:Volume\",\n      \"@context\": {\n        \"name\": \"dcterms:title\",\n        \"owner\": {\n          \"@id\": \"cubefs:owner\",\n          \"@type\": \"@id\"\n        },\n        \"capacity\": {\n          \"@id\": \"cubefs:capacity\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"replicaNum\": {\n          \"@id\": \"cubefs:replicaNum\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"volType\": \"cubefs:volumeType\",\n        \"status\": \"cubefs:volumeStatus\",\n        \"createTime\": {\n          \"\
  @id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"usedSize\": {\n          \"@id\": \"cubefs:usedSize\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"totalSize\": {\n          \"@id\": \"cubefs:totalSize\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"dataPartitions\": {\n          \"@id\": \"cubefs:dataPartitions\",\n          \"@container\": \"@set\"\n        },\n        \"metaPartitions\": {\n          \"@id\": \"cubefs:metaPartitions\",\n          \"@container\": \"@set\"\n        }\n      },\n      \"rdfs:label\": \"CubeFS Volume\",\n      \"rdfs:comment\": \"A CubeFS volume, the top-level storage namespace supporting POSIX, HDFS, and S3-compatible access protocols.\",\n      \"skos:broader\": \"schema:Dataset\",\n      \"skos:exactMatch\": \"schema:StorageObject\"\n    },\n\n    \"DataPartition\": {\n      \"@id\": \"cubefs:DataPartition\",\n      \"@context\": {\n        \"partitionID\": {\n          \"@id\"\
  : \"cubefs:partitionID\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"status\": \"cubefs:partitionStatus\",\n        \"replicaNum\": {\n          \"@id\": \"cubefs:replicaNum\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"hosts\": {\n          \"@id\": \"cubefs:replicaHosts\",\n          \"@container\": \"@set\"\n        },\n        \"total\": {\n          \"@id\": \"cubefs:totalBytes\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"used\": {\n          \"@id\": \"cubefs:usedBytes\",\n          \"@type\": \"xsd:integer\"\n        }\n      },\n      \"rdfs:label\": \"Data Partition\",\n      \"rdfs:comment\": \"A CubeFS data partition that stores replicated data blocks across data nodes.\",\n      \"skos:broader\": \"cubefs:Volume\"\n    },\n\n    \"MetaPartition\": {\n      \"@id\": \"cubefs:MetaPartition\",\n      \"@context\": {\n        \"partitionID\": {\n          \"@id\": \"cubefs:partitionID\",\n          \"@type\": \"xsd:integer\"\
  \n        },\n        \"start\": {\n          \"@id\": \"cubefs:inodeRangeStart\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"end\": {\n          \"@id\": \"cubefs:inodeRangeEnd\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"inodeCount\": {\n          \"@id\": \"cubefs:inodeCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"hosts\": {\n          \"@id\": \"cubefs:replicaHosts\",\n          \"@container\": \"@set\"\n        },\n        \"leader\": {\n          \"@id\": \"cubefs:raftLeader\",\n          \"@type\": \"@id\"\n        }\n      },\n      \"rdfs:label\": \"Metadata Partition\",\n      \"rdfs:comment\": \"A CubeFS metadata partition that stores inode and directory entry data across metadata nodes.\",\n      \"skos:broader\": \"cubefs:Volume\"\n    },\n\n    \"DataNode\": {\n      \"@id\": \"cubefs:DataNode\",\n      \"@context\": {\n        \"addr\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n     \
  \   },\n        \"status\": \"cubefs:nodeStatus\",\n        \"isWritable\": \"cubefs:isWritable\",\n        \"totalWeight\": {\n          \"@id\": \"cubefs:totalBytes\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"usedWeight\": {\n          \"@id\": \"cubefs:usedBytes\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"availableSpace\": {\n          \"@id\": \"cubefs:availableBytes\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"dataPartitionCount\": {\n          \"@id\": \"cubefs:partitionCount\",\n          \"@type\": \"xsd:integer\"\n        }\n      },\n      \"rdfs:label\": \"Data Node\",\n      \"rdfs:comment\": \"A CubeFS storage node that hosts data partition replicas on local disk.\",\n      \"skos:broader\": \"schema:ComputerServer\",\n      \"skos:related\": \"cubefs:DataPartition\"\n    },\n\n    \"MetaNode\": {\n      \"@id\": \"cubefs:MetaNode\",\n      \"@context\": {\n        \"addr\": {\n          \"@id\": \"schema:url\",\n\
  \          \"@type\": \"@id\"\n        },\n        \"status\": \"cubefs:nodeStatus\",\n        \"isWritable\": \"cubefs:isWritable\",\n        \"totalWeight\": {\n          \"@id\": \"cubefs:totalBytes\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"usedWeight\": {\n          \"@id\": \"cubefs:usedBytes\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"metaPartitionCount\": {\n          \"@id\": \"cubefs:partitionCount\",\n          \"@type\": \"xsd:integer\"\n        }\n      },\n      \"rdfs:label\": \"Metadata Node\",\n      \"rdfs:comment\": \"A CubeFS node that stores and manages metadata partitions containing file system inodes and directory entries.\",\n      \"skos:broader\": \"schema:ComputerServer\",\n      \"skos:related\": \"cubefs:MetaPartition\"\n    },\n\n    \"User\": {\n      \"@id\": \"cubefs:User\",\n      \"@context\": {\n        \"user_id\": \"dcterms:identifier\",\n        \"access_key\": \"cubefs:accessKey\",\n        \"secret_key\"\
  : \"cubefs:secretKey\",\n        \"own_vols\": {\n          \"@id\": \"cubefs:ownedVolumes\",\n          \"@container\": \"@set\"\n        },\n        \"authorized_vols\": \"cubefs:authorizedVolumes\",\n        \"user_type\": \"cubefs:userType\",\n        \"create_time\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      },\n      \"rdfs:label\": \"CubeFS User\",\n      \"rdfs:comment\": \"A CubeFS user account with S3-compatible credentials and volume ownership/access rights.\",\n      \"skos:broader\": \"schema:Person\",\n      \"skos:related\": \"cubefs:Volume\"\n    },\n\n    \"Cluster\": {\n      \"@id\": \"cubefs:Cluster\",\n      \"@context\": {\n        \"Name\": \"dcterms:title\",\n        \"LeaderAddr\": {\n          \"@id\": \"cubefs:leaderAddress\",\n          \"@type\": \"@id\"\n        },\n        \"DataNodes\": {\n          \"@id\": \"cubefs:dataNodes\",\n          \"@container\": \"@set\"\n        },\n        \"MetaNodes\"\
  : {\n          \"@id\": \"cubefs:metaNodes\",\n          \"@container\": \"@set\"\n        }\n      },\n      \"rdfs:label\": \"CubeFS Cluster\",\n      \"rdfs:comment\": \"A CubeFS distributed storage cluster comprising data nodes, metadata nodes, and managed volumes.\",\n      \"skos:broader\": \"schema:SoftwareApplication\",\n      \"skos:exactMatch\": \"cncf:cubefs\"\n    },\n\n    \"name\": \"dcterms:title\",\n    \"description\": \"dcterms:description\",\n    \"created\": {\n      \"@id\": \"dcterms:created\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"modified\": {\n      \"@id\": \"dcterms:modified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"id\": \"dcterms:identifier\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/cubefs/refs/heads/main/json-ld/cubefs-context.jsonld
tags:
- Cloud Native
- CNCF Graduated
- Distributed File System
- Kubernetes
- Object Storage
- POSIX
- S3 Compatible
- Storage
- JSON-LD
- Linked Data
- Semantic Web
---
