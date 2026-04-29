---
class_count: 13
classes:
- CreateGraphInput
- CreateGraphSnapshotInput
- CreateGraphUsingImportTaskInput
- CreatePrivateGraphEndpointInput
- GraphOutput
- GraphSnapshotOutput
- ImportTaskOutput
- ListGraphSnapshotsOutput
- ListGraphsOutput
- ListImportTasksOutput
- PrivateGraphEndpointOutput
- RestoreGraphFromSnapshotInput
- UpdateGraphInput
context_file: json-ld/amazon-neptune-analytics-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-neptune/refs/heads/main/json-ld/amazon-neptune-analytics-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Neptune Analytics from Amazon Neptune.
layout: jsonld
name: Amazon Neptune Analytics Context
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
  name: arn
  type: string
- container: ''
  name: buildNumber
  type: string
- container: ''
  name: createTime
  type: dateTime
- container: ''
  name: deletionProtection
  type: boolean
- container: ''
  name: dictionaryEntryCount
  type: integer
- container: ''
  name: dimension
  type: integer
- container: ''
  name: endpoint
  type: string
- container: ''
  name: errorCount
  type: integer
- container: ''
  name: errorDetails
  type: string
- container: ''
  name: format
  type: string
- container: ''
  name: graphId
  type: string
- container: ''
  name: graphIdentifier
  type: string
- container: ''
  name: graphName
  type: string
- container: set
  name: graphSnapshots
  type: reference
- container: set
  name: graphs
  type: reference
- container: ''
  name: id
  type: string
- container: ''
  name: importOptions
  type: reference
- container: ''
  name: importTaskDetails
  type: reference
- container: ''
  name: kmsKeyIdentifier
  type: string
- container: ''
  name: name
  type: ''
- container: ''
  name: nextToken
  type: string
- container: ''
  name: progressPercentage
  type: integer
- container: ''
  name: provisionedMemory
  type: integer
- container: ''
  name: publicConnectivity
  type: boolean
- container: ''
  name: replicaCount
  type: integer
- container: ''
  name: roleArn
  type: string
- container: ''
  name: snapshotCreateTime
  type: dateTime
- container: ''
  name: snapshotName
  type: string
- container: ''
  name: source
  type: string
- container: ''
  name: sourceGraphId
  type: string
- container: ''
  name: sourceSnapshotId
  type: string
- container: ''
  name: startTime
  type: dateTime
- container: ''
  name: statementCount
  type: integer
- container: ''
  name: status
  type: string
- container: ''
  name: statusReason
  type: string
- container: set
  name: subnetIds
  type: string
- container: ''
  name: tags
  type: reference
- container: ''
  name: taskId
  type: string
- container: set
  name: tasks
  type: reference
- container: ''
  name: timeElapsedSeconds
  type: integer
- container: ''
  name: vectorSearchConfiguration
  type: reference
- container: ''
  name: vpcEndpointId
  type: string
- container: ''
  name: vpcId
  type: string
- container: set
  name: vpcSecurityGroupIds
  type: string
property_count: 44
provider_name: Amazon Neptune
provider_slug: amazon-neptune
slug: amazon-neptune-analytics-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"neptune\": \"https://neptune.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"CreateGraphInput\": \"neptune:CreateGraphInput\",\n    \"CreateGraphSnapshotInput\": \"neptune:CreateGraphSnapshotInput\",\n    \"CreateGraphUsingImportTaskInput\": \"neptune:CreateGraphUsingImportTaskInput\",\n    \"CreatePrivateGraphEndpointInput\": \"neptune:CreatePrivateGraphEndpointInput\",\n    \"GraphOutput\": \"neptune:GraphOutput\",\n    \"GraphSnapshotOutput\": \"neptune:GraphSnapshotOutput\",\n    \"ImportTaskOutput\": \"neptune:ImportTaskOutput\",\n    \"ListGraphSnapshotsOutput\": \"neptune:ListGraphSnapshotsOutput\",\n    \"ListGraphsOutput\": \"neptune:ListGraphsOutput\",\n    \"ListImportTasksOutput\": \"neptune:ListImportTasksOutput\",\n    \"PrivateGraphEndpointOutput\": \"neptune:PrivateGraphEndpointOutput\",\n \
  \   \"RestoreGraphFromSnapshotInput\": \"neptune:RestoreGraphFromSnapshotInput\",\n    \"UpdateGraphInput\": \"neptune:UpdateGraphInput\",\n    \"arn\": {\n      \"@id\": \"neptune:arn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"buildNumber\": {\n      \"@id\": \"neptune:buildNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createTime\": {\n      \"@id\": \"neptune:createTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"deletionProtection\": {\n      \"@id\": \"neptune:deletionProtection\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"dictionaryEntryCount\": {\n      \"@id\": \"neptune:dictionaryEntryCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"dimension\": {\n      \"@id\": \"neptune:dimension\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"endpoint\": {\n      \"@id\": \"neptune:endpoint\",\n      \"@type\": \"xsd:string\"\n    },\n    \"errorCount\": {\n      \"@id\": \"neptune:errorCount\",\n      \"@type\": \"xsd:integer\"\n    },\n   \
  \ \"errorDetails\": {\n      \"@id\": \"neptune:errorDetails\",\n      \"@type\": \"xsd:string\"\n    },\n    \"format\": {\n      \"@id\": \"neptune:format\",\n      \"@type\": \"xsd:string\"\n    },\n    \"graphId\": {\n      \"@id\": \"neptune:graphId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"graphIdentifier\": {\n      \"@id\": \"neptune:graphIdentifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"graphName\": {\n      \"@id\": \"neptune:graphName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"graphSnapshots\": {\n      \"@id\": \"neptune:graphSnapshots\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"graphs\": {\n      \"@id\": \"neptune:graphs\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"id\": {\n      \"@id\": \"neptune:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"importOptions\": {\n      \"@id\": \"neptune:importOptions\",\n      \"@type\": \"@id\"\n    },\n    \"importTaskDetails\": {\n  \
  \    \"@id\": \"neptune:importTaskDetails\",\n      \"@type\": \"@id\"\n    },\n    \"kmsKeyIdentifier\": {\n      \"@id\": \"neptune:kmsKeyIdentifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\"\n    },\n    \"nextToken\": {\n      \"@id\": \"neptune:nextToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"progressPercentage\": {\n      \"@id\": \"neptune:progressPercentage\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"provisionedMemory\": {\n      \"@id\": \"neptune:provisionedMemory\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"publicConnectivity\": {\n      \"@id\": \"neptune:publicConnectivity\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"replicaCount\": {\n      \"@id\": \"neptune:replicaCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"roleArn\": {\n      \"@id\": \"neptune:roleArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"snapshotCreateTime\": {\n      \"@id\": \"neptune:snapshotCreateTime\"\
  ,\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"snapshotName\": {\n      \"@id\": \"neptune:snapshotName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"source\": {\n      \"@id\": \"neptune:source\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sourceGraphId\": {\n      \"@id\": \"neptune:sourceGraphId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sourceSnapshotId\": {\n      \"@id\": \"neptune:sourceSnapshotId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startTime\": {\n      \"@id\": \"neptune:startTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"statementCount\": {\n      \"@id\": \"neptune:statementCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"status\": {\n      \"@id\": \"neptune:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"statusReason\": {\n      \"@id\": \"neptune:statusReason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subnetIds\": {\n      \"@id\": \"neptune:subnetIds\",\n      \"@container\": \"@set\",\n      \"\
  @type\": \"xsd:string\"\n    },\n    \"tags\": {\n      \"@id\": \"neptune:tags\",\n      \"@type\": \"@id\"\n    },\n    \"taskId\": {\n      \"@id\": \"neptune:taskId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tasks\": {\n      \"@id\": \"neptune:tasks\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"timeElapsedSeconds\": {\n      \"@id\": \"neptune:timeElapsedSeconds\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"vectorSearchConfiguration\": {\n      \"@id\": \"neptune:vectorSearchConfiguration\",\n      \"@type\": \"@id\"\n    },\n    \"vpcEndpointId\": {\n      \"@id\": \"neptune:vpcEndpointId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"vpcId\": {\n      \"@id\": \"neptune:vpcId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"vpcSecurityGroupIds\": {\n      \"@id\": \"neptune:vpcSecurityGroupIds\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-neptune/refs/heads/main/json-ld/amazon-neptune-analytics-context.jsonld
tags:
- AWS
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
