---
api_specs:
- filename: weaviate-openapi.yml
  format: yaml
  label: Weaviate REST API
  slug: weaviate-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/weaviate/refs/heads/main/openapi/weaviate-openapi.yml
class_count: 0
classes: []
context_file: json-ld/weaviate-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/weaviate/refs/heads/main/json-ld/weaviate-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Weaviate from Weaviate.
layout: jsonld
name: Weaviate Context
namespaces:
- prefix: weaviate
  uri: https://weaviate.io/api/ontology#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: Tenant
  type: reference
- container: ''
  name: name
  type: string
- container: ''
  name: activityStatus
  type: string
- container: ''
  name: ReplicationReplicateDetailsReplicaResponse
  type: reference
- container: ''
  name: id
  type: string
- container: ''
  name: shard
  type: string
- container: ''
  name: collection
  type: string
- container: ''
  name: sourceNode
  type: string
- container: ''
  name: targetNode
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: uncancelable
  type: boolean
- container: ''
  name: scheduledForCancel
  type: boolean
- container: ''
  name: scheduledForDelete
  type: boolean
- container: ''
  name: status
  type: ''
- container: ''
  name: statusHistory
  type: ''
- container: ''
  name: whenStartedUnixMs
  type: long
- container: ''
  name: ShardStatusGetResponse
  type: reference
- container: ''
  name: vectorQueueSize
  type: integer
- container: ''
  name: BatchReferenceResponse
  type: reference
- container: ''
  name: NestedProperty
  type: reference
- container: ''
  name: dataType
  type: ''
- container: ''
  name: description
  type: string
- container: ''
  name: indexFilterable
  type: boolean
- container: ''
  name: indexSearchable
  type: boolean
- container: ''
  name: indexRangeFilters
  type: boolean
- container: ''
  name: tokenization
  type: string
- container: ''
  name: nestedProperties
  type: ''
- container: ''
  name: textAnalyzer
  type: ''
- container: ''
  name: AsyncReplicationStatus
  type: reference
- container: ''
  name: objectsPropagated
  type: float
- container: ''
  name: startDiffTimeUnixMillis
  type: float
- container: ''
  name: VectorConfig
  type: reference
- container: ''
  name: vectorizer
  type: ''
- container: ''
  name: vectorIndexType
  type: string
- container: ''
  name: vectorIndexConfig
  type: ''
- container: ''
  name: RestoreConfig
  type: reference
- container: ''
  name: Endpoint
  type: string
- container: ''
  name: Bucket
  type: string
- container: ''
  name: Path
  type: string
- container: ''
  name: CPUPercentage
  type: integer
- container: ''
  name: rolesOptions
  type: string
- container: ''
  name: usersOptions
  type: string
- container: ''
  name: C11yWordsResponse
  type: reference
- container: ''
  name: concatenatedWord
  type: ''
- container: ''
  name: individualWords
  type: ''
- container: ''
  name: ReplicationReplicateDetailsReplicaStatus
  type: reference
- container: ''
  name: state
  type: string
- container: ''
  name: errors
  type: ''
- container: ''
  name: VectorWeights
  type: reference
- container: ''
  name: TokenizeResponse
  type: reference
- container: ''
  name: indexed
  type: ''
- container: ''
  name: query
  type: ''
- container: ''
  name: Statistics
  type: reference
- container: ''
  name: bootstrapped
  type: boolean
- container: ''
  name: dbLoaded
  type: boolean
- container: ''
  name: initialLastAppliedIndex
  type: float
- container: ''
  name: lastAppliedIndex
  type: float
- container: ''
  name: isVoter
  type: boolean
- container: ''
  name: leaderId
  type: ''
- container: ''
  name: leaderAddress
  type: ''
- container: ''
  name: open
  type: boolean
- container: ''
  name: ready
  type: boolean
- container: ''
  name: candidates
  type: ''
- container: ''
  name: raft
  type: ''
- container: ''
  name: C11yVector
  type: reference
- container: ''
  name: SingleRef
  type: reference
- container: ''
  name: class
  type: anyURI
- container: ''
  name: schema
  type: ''
- container: ''
  name: beacon
  type: anyURI
- container: ''
  name: href
  type: anyURI
- container: ''
  name: classification
  type: ''
- container: ''
  name: PropertyTokenizeRequest
  type: reference
- container: ''
  name: text
  type: string
- container: ''
  name: PropertySchema
  type: reference
- container: ''
  name: WhereFilter
  type: reference
- container: ''
  name: operands
  type: ''
- container: ''
  name: operator
  type: string
- container: ''
  name: path
  type: ''
- container: ''
  name: valueInt
  type: long
- container: ''
  name: valueNumber
  type: float
- container: ''
  name: valueBoolean
  type: boolean
- container: ''
  name: valueString
  type: string
- container: ''
  name: valueText
  type: string
- container: ''
  name: valueDate
  type: string
- container: ''
  name: valueIntArray
  type: ''
- container: ''
  name: valueNumberArray
  type: ''
- container: ''
  name: valueBooleanArray
  type: ''
- container: ''
  name: valueStringArray
  type: ''
- container: ''
  name: valueTextArray
  type: ''
- container: ''
  name: valueDateArray
  type: ''
- container: ''
  name: valueGeoRange
  type: ''
- container: ''
  name: Deprecation
  type: reference
- container: ''
  name: apiType
  type: string
- container: ''
  name: msg
  type: string
- container: ''
  name: mitigation
  type: string
- container: ''
  name: sinceVersion
  type: string
- container: ''
  name: plannedRemovalVersion
  type: string
- container: ''
  name: removedIn
  type: string
- container: ''
  name: removedTime
  type: dateTime
- container: ''
  name: sinceTime
  type: dateTime
- container: ''
  name: locations
  type: ''
- container: ''
  name: AdditionalProperties
  type: reference
- container: ''
  name: WhereFilterGeoRange
  type: reference
- container: ''
  name: geoCoordinates
  type: ''
- container: ''
  name: distance
  type: ''
- container: ''
  name: UserTypeOutput
  type: reference
- container: ''
  name: ReplicationReplicateReplicaRequest
  type: reference
- container: ''
  name: BackupRestoreRequest
  type: reference
- container: ''
  name: config
  type: ''
- container: ''
  name: include
  type: ''
- container: ''
  name: exclude
  type: ''
- container: ''
  name: node_mapping
  type: ''
- container: ''
  name: overwriteAlias
  type: boolean
- container: ''
  name: ClassificationMeta
  type: reference
- container: ''
  name: started
  type: dateTime
- container: ''
  name: completed
  type: dateTime
- container: ''
  name: count
  type: integer
- container: ''
  name: countSucceeded
  type: integer
- container: ''
  name: countFailed
  type: integer
- container: ''
  name: GraphQLError
  type: reference
- container: ''
  name: message
  type: string
- container: ''
  name: RaftStatistics
  type: reference
- container: ''
  name: appliedIndex
  type: string
- container: ''
  name: commitIndex
  type: string
- container: ''
  name: fsmPending
  type: string
- container: ''
  name: lastContact
  type: string
- container: ''
  name: lastLogIndex
  type: string
- container: ''
  name: lastLogTerm
  type: string
- container: ''
  name: lastSnapshotIndex
  type: string
- container: ''
  name: lastSnapshotTerm
  type: string
- container: ''
  name: latestConfiguration
  type: ''
- container: ''
  name: latestConfigurationIndex
  type: string
- container: ''
  name: numPeers
  type: string
- container: ''
  name: protocolVersion
  type: string
- container: ''
  name: protocolVersionMax
  type: string
- container: ''
  name: protocolVersionMin
  type: string
- container: ''
  name: snapshotVersionMax
  type: string
- container: ''
  name: snapshotVersionMin
  type: string
- container: ''
  name: term
  type: string
- container: ''
  name: NamespaceListResponse
  type: reference
- container: ''
  name: Alias
  type: reference
- container: ''
  name: alias
  type: string
- container: ''
  name: Class
  type: reference
- container: ''
  name: vectorConfig
  type: ''
- container: ''
  name: shardingConfig
  type: ''
- container: ''
  name: replicationConfig
  type: ''
- container: ''
  name: invertedIndexConfig
  type: ''
- container: ''
  name: multiTenancyConfig
  type: ''
- container: ''
  name: objectTtlConfig
  type: ''
- container: ''
  name: moduleConfig
  type: ''
- container: ''
  name: properties
  type: ''
- container: ''
  name: BM25Config
  type: reference
- container: ''
  name: k1
  type: float
- container: ''
  name: b
  type: float
- container: ''
  name: GraphQLResponses
  type: reference
- container: ''
  name: Schema
  type: reference
- container: ''
  name: classes
  type: ''
- container: ''
  name: maintainer
  type: string
- container: ''
  name: Classification
  type: reference
- container: ''
  name: classifyProperties
  type: ''
- container: ''
  name: basedOnProperties
  type: ''
- container: ''
  name: meta
  type: ''
- container: ''
  name: settings
  type: ''
- container: ''
  name: error
  type: string
- container: ''
  name: filters
  type: ''
- container: ''
  name: Object
  type: reference
- container: ''
  name: vectorWeights
  type: ''
- container: ''
  name: creationTimeUnix
  type: long
- container: ''
  name: lastUpdateTimeUnix
  type: long
- container: ''
  name: vector
  type: ''
- container: ''
  name: vectors
  type: ''
- container: ''
  name: tenant
  type: string
- container: ''
  name: additional
  type: ''
- container: ''
  name: RolesListResponse
  type: reference
- container: ''
  name: MultipleRef
  type: reference
- container: ''
  name: BatchDelete
  type: reference
- container: ''
  name: match
  type: ''
- container: ''
  name: output
  type: string
- container: ''
  name: deletionTimeUnixMilli
  type: long
- container: ''
  name: dryRun
  type: boolean
- container: ''
  name: DistributedTasks
  type: reference
- container: ''
  name: ClusterStatisticsResponse
  type: reference
- container: ''
  name: statistics
  type: ''
- container: ''
  name: synchronized
  type: boolean
- container: ''
  name: ReferenceMetaClassification
  type: reference
- container: ''
  name: overallCount
  type: float
- container: ''
  name: winningCount
  type: float
- container: ''
  name: losingCount
  type: float
- container: ''
  name: closestOverallDistance
  type: float
- container: ''
  name: winningDistance
  type: float
- container: ''
  name: meanWinningDistance
  type: float
- container: ''
  name: closestWinningDistance
  type: float
- container: ''
  name: closestLosingDistance
  type: float
- container: ''
  name: losingDistance
  type: float
- container: ''
  name: meanLosingDistance
  type: float
- container: ''
  name: ShardProgress
  type: reference
- container: ''
  name: objectsExported
  type: long
- container: ''
  name: skipReason
  type: string
- container: ''
  name: BackupConfig
  type: reference
- container: ''
  name: ChunkSize
  type: integer
- container: ''
  name: CompressionLevel
  type: string
- container: ''
  name: ReplicationReplicateForceDeleteRequest
  type: reference
- container: ''
  name: node
  type: string
- container: ''
  name: UserTypeInput
  type: reference
- container: ''
  name: Property
  type: reference
- container: ''
  name: indexInverted
  type: boolean
- container: ''
  name: disableDuplicatedReferences
  type: boolean
- container: ''
  name: ExportCreateRequest
  type: reference
- container: ''
  name: file_format
  type: string
- container: ''
  name: ReplicationReplicateReplicaResponse
  type: reference
- container: ''
  name: JsonObject
  type: reference
- container: ''
  name: AliasResponse
  type: reference
- container: ''
  name: aliases
  type: ''
- container: ''
  name: TextAnalyzerConfig
  type: reference
- container: ''
  name: asciiFold
  type: boolean
- container: ''
  name: asciiFoldIgnore
  type: ''
- container: ''
  name: stopwordPreset
  type: string
- container: ''
  name: PeerUpdate
  type: reference
- container: ''
  name: uri
  type: anyURI
- container: ''
  name: schemaHash
  type: string
- container: ''
  name: BackupCreateStatusResponse
  type: reference
- container: ''
  name: backend
  type: string
- container: ''
  name: startedAt
  type: dateTime
- container: ''
  name: completedAt
  type: dateTime
- container: ''
  name: size
  type: float
- container: ''
  name: DistributedTaskUnit
  type: reference
- container: ''
  name: nodeId
  type: string
- container: ''
  name: progress
  type: float
- container: ''
  name: updatedAt
  type: dateTime
- container: ''
  name: finishedAt
  type: dateTime
- container: ''
  name: NodesStatusResponse
  type: reference
- container: ''
  name: nodes
  type: ''
- container: ''
  name: ShardStatusList
  type: reference
- container: ''
  name: DBUserInfo
  type: reference
- container: ''
  name: roles
  type: ''
- container: ''
  name: userId
  type: string
- container: ''
  name: dbUserType
  type: string
- container: ''
  name: active
  type: boolean
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: apiKeyFirstLetters
  type: string
- container: ''
  name: lastUsedAt
  type: dateTime
- container: ''
  name: namespace
  type: string
- container: ''
  name: ObjectsGetResponse
  type: reference
- container: ''
  name: ExportStatusResponse
  type: reference
- container: ''
  name: tookInMs
  type: long
- container: ''
  name: shardStatus
  type: ''
- container: ''
  name: ReplicationShardingStateResponse
  type: reference
- container: ''
  name: shardingState
  type: ''
- container: ''
  name: BackupCreateRequest
  type: reference
- container: ''
  name: incremental_base_backup_id
  type: string
- container: ''
  name: NodeShardStatus
  type: reference
- container: ''
  name: objectCount
  type: float
- container: ''
  name: vectorIndexingStatus
  type: string
- container: ''
  name: compressed
  type: boolean
- container: ''
  name: vectorQueueLength
  type: float
- container: ''
  name: loaded
  type: boolean
- container: ''
  name: asyncReplicationStatus
  type: ''
- container: ''
  name: numberOfReplicas
  type: long
- container: ''
  name: replicationFactor
  type: long
- container: ''
  name: BatchDeleteResponse
  type: reference
- container: ''
  name: results
  type: ''
- container: ''
  name: Vector
  type: reference
- container: ''
  name: ReplicationConfig
  type: reference
- container: ''
  name: factor
  type: integer
- container: ''
  name: asyncEnabled
  type: boolean
- container: ''
  name: asyncConfig
  type: ''
- container: ''
  name: deletionStrategy
  type: string
- container: ''
  name: ErrorResponse
  type: reference
- container: ''
  name: Permission
  type: reference
- container: ''
  name: backups
  type: ''
- container: ''
  name: data
  type: ''
- container: ''
  name: users
  type: ''
- container: ''
  name: groups
  type: ''
- container: ''
  name: tenants
  type: ''
- container: ''
  name: collections
  type: ''
- container: ''
  name: replicate
  type: ''
- container: ''
  name: namespaces
  type: ''
- container: ''
  name: action
  type: string
- container: ''
  name: MultiTenancyConfig
  type: reference
- container: ''
  name: enabled
  type: boolean
- container: ''
  name: autoTenantCreation
  type: boolean
- container: ''
  name: autoTenantActivation
  type: boolean
- container: ''
  name: Namespace
  type: reference
- container: ''
  name: ReplicationScalePlan
  type: reference
- container: ''
  name: planId
  type: string
- container: ''
  name: shardScaleActions
  type: ''
- container: ''
  name: Meta
  type: reference
- container: ''
  name: hostname
  type: string
- container: ''
  name: version
  type: string
- container: ''
  name: modules
  type: ''
- container: ''
  name: grpcMaxMessageSize
  type: integer
- container: ''
  name: BackupRestoreStatusResponse
  type: reference
- container: ''
  name: C11yExtension
  type: reference
- container: ''
  name: concept
  type: string
- container: ''
  name: definition
  type: string
- container: ''
  name: weight
  type: float
- container: ''
  name: Link
  type: reference
- container: ''
  name: rel
  type: string
- container: ''
  name: documentationHref
  type: string
- container: ''
  name: ReplicationShardReplicas
  type: reference
- container: ''
  name: replicas
  type: ''
- container: ''
  name: ReplicationScaleApplyResponse
  type: reference
- container: ''
  name: operationIds
  type: ''
- container: ''
  name: UserApiKey
  type: reference
- container: ''
  name: apikey
  type: string
- container: ''
  name: GraphQLQuery
  type: reference
- container: ''
  name: operationName
  type: string
- container: ''
  name: variables
  type: ''
- container: ''
  name: GraphQLQueries
  type: reference
- container: ''
  name: BackupListResponse
  type: reference
- container: ''
  name: StopwordConfig
  type: reference
- container: ''
  name: preset
  type: string
- container: ''
  name: additions
  type: ''
- container: ''
  name: removals
  type: ''
- container: ''
  name: BackupRestoreResponse
  type: reference
- container: ''
  name: ShardStatus
  type: reference
- container: ''
  name: GroupType
  type: reference
- container: ''
  name: BatchReference
  type: reference
- container: ''
  name: from
  type: anyURI
- container: ''
  name: to
  type: anyURI
- container: ''
  name: UserOwnInfo
  type: reference
- container: ''
  name: username
  type: string
- container: ''
  name: ObjectTtlConfig
  type: reference
- container: ''
  name: defaultTtl
  type: integer
- container: ''
  name: deleteOn
  type: string
- container: ''
  name: filterExpiredObjects
  type: boolean
- container: ''
  name: ObjectsListResponse
  type: reference
- container: ''
  name: objects
  type: ''
- container: ''
  name: deprecations
  type: ''
- container: ''
  name: totalResults
  type: long
- container: ''
  name: TokenizeRequest
  type: reference
- container: ''
  name: analyzerConfig
  type: ''
- container: ''
  name: stopwords
  type: ''
- container: ''
  name: stopwordPresets
  type: ''
- container: ''
  name: InvertedIndexConfig
  type: reference
- container: ''
  name: cleanupIntervalSeconds
  type: float
- container: ''
  name: bm25
  type: ''
- container: ''
  name: indexTimestamps
  type: boolean
- container: ''
  name: indexNullState
  type: boolean
- container: ''
  name: indexPropertyLength
  type: boolean
- container: ''
  name: usingBlockMaxWAND
  type: boolean
- container: ''
  name: tokenizerUserDict
  type: ''
- container: ''
  name: NodeStatus
  type: reference
- container: ''
  name: gitHash
  type: string
- container: ''
  name: stats
  type: ''
- container: ''
  name: batchStats
  type: ''
- container: ''
  name: shards
  type: ''
- container: ''
  name: operationalMode
  type: string
- container: ''
  name: Vectors
  type: reference
- container: ''
  name: GeoCoordinates
  type: reference
- container: ''
  name: latitude
  type: float
- container: ''
  name: longitude
  type: float
- container: ''
  name: NodeStats
  type: reference
- container: ''
  name: shardCount
  type: float
- container: ''
  name: ReplicationReplicateDetailsReplicaStatusError
  type: reference
- container: ''
  name: whenErroredUnixMs
  type: long
- container: ''
  name: GraphQLResponse
  type: reference
- container: ''
  name: BatchStats
  type: reference
- container: ''
  name: queueLength
  type: float
- container: ''
  name: ratePerSecond
  type: float
- container: ''
  name: ReplicationShardingState
  type: reference
- container: ''
  name: C11yNearestNeighbors
  type: reference
- container: ''
  name: TokenizerUserDictConfig
  type: reference
- container: ''
  name: tokenizer
  type: string
- container: ''
  name: replacements
  type: ''
- container: ''
  name: ReplicationReplicateForceDeleteResponse
  type: reference
- container: ''
  name: deleted
  type: ''
- container: ''
  name: DistributedTask
  type: reference
- container: ''
  name: finishedNodes
  type: ''
- container: ''
  name: payload
  type: ''
- container: ''
  name: units
  type: ''
- container: ''
  name: ReplicationAsyncConfig
  type: reference
- container: ''
  name: maxWorkers
  type: long
- container: ''
  name: hashtreeHeight
  type: long
- container: ''
  name: frequency
  type: long
- container: ''
  name: frequencyWhilePropagating
  type: long
- container: ''
  name: aliveNodesCheckingFrequency
  type: long
- container: ''
  name: loggingFrequency
  type: long
- container: ''
  name: diffBatchSize
  type: long
- container: ''
  name: diffPerNodeTimeout
  type: long
- container: ''
  name: prePropagationTimeout
  type: long
- container: ''
  name: propagationTimeout
  type: long
- container: ''
  name: propagationLimit
  type: long
- container: ''
  name: propagationDelay
  type: long
- container: ''
  name: propagationConcurrency
  type: long
- container: ''
  name: propagationBatchSize
  type: long
- container: ''
  name: BackupCreateResponse
  type: reference
- container: ''
  name: bucket
  type: string
- container: ''
  name: Principal
  type: reference
- container: ''
  name: userType
  type: ''
- container: ''
  name: isGlobalOperator
  type: boolean
- container: ''
  name: Role
  type: reference
- container: ''
  name: permissions
  type: ''
- container: ''
  name: ExportCreateResponse
  type: reference
- container: ''
  name: PhoneNumber
  type: reference
- container: ''
  name: input
  type: string
- container: ''
  name: internationalFormatted
  type: string
- container: ''
  name: defaultCountry
  type: string
- container: ''
  name: countryCode
  type: float
- container: ''
  name: national
  type: float
- container: ''
  name: nationalFormatted
  type: string
- container: ''
  name: valid
  type: boolean
property_count: 402
provider_name: Weaviate
provider_slug: weaviate
slug: weaviate-context
source_filename: weaviate-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"weaviate\": \"https://weaviate.io/api/ontology#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Tenant\": {\n      \"@id\": \"weaviate:Tenant\",\n      \"@type\": \"@id\"\n    },\n    \"name\": {\n      \"@id\": \"weaviate:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"activityStatus\": {\n      \"@id\": \"weaviate:activityStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ReplicationReplicateDetailsReplicaResponse\": {\n      \"@id\": \"weaviate:ReplicationReplicateDetailsReplicaResponse\",\n      \"@type\": \"@id\"\n    },\n    \"id\": {\n      \"@id\": \"weaviate:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shard\": {\n      \"@id\": \"weaviate:shard\",\n      \"@type\": \"xsd:string\"\n    },\n    \"collection\": {\n      \"@id\": \"weaviate:collection\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sourceNode\": {\n      \"@id\": \"weaviate:sourceNode\",\n \
  \     \"@type\": \"xsd:string\"\n    },\n    \"targetNode\": {\n      \"@id\": \"weaviate:targetNode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"weaviate:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"uncancelable\": {\n      \"@id\": \"weaviate:uncancelable\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"scheduledForCancel\": {\n      \"@id\": \"weaviate:scheduledForCancel\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"scheduledForDelete\": {\n      \"@id\": \"weaviate:scheduledForDelete\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"status\": {\n      \"@id\": \"weaviate:status\"\n    },\n    \"statusHistory\": {\n      \"@id\": \"weaviate:statusHistory\"\n    },\n    \"whenStartedUnixMs\": {\n      \"@id\": \"weaviate:whenStartedUnixMs\",\n      \"@type\": \"xsd:long\"\n    },\n    \"ShardStatusGetResponse\": {\n      \"@id\": \"weaviate:ShardStatusGetResponse\",\n      \"@type\": \"@id\"\n    },\n    \"vectorQueueSize\": {\n\
  \      \"@id\": \"weaviate:vectorQueueSize\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"BatchReferenceResponse\": {\n      \"@id\": \"weaviate:BatchReferenceResponse\",\n      \"@type\": \"@id\"\n    },\n    \"NestedProperty\": {\n      \"@id\": \"weaviate:NestedProperty\",\n      \"@type\": \"@id\"\n    },\n    \"dataType\": {\n      \"@id\": \"weaviate:dataType\"\n    },\n    \"description\": {\n      \"@id\": \"weaviate:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"indexFilterable\": {\n      \"@id\": \"weaviate:indexFilterable\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"indexSearchable\": {\n      \"@id\": \"weaviate:indexSearchable\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"indexRangeFilters\": {\n      \"@id\": \"weaviate:indexRangeFilters\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"tokenization\": {\n      \"@id\": \"weaviate:tokenization\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nestedProperties\": {\n      \"@id\": \"weaviate:nestedProperties\"\
  \n    },\n    \"textAnalyzer\": {\n      \"@id\": \"weaviate:textAnalyzer\"\n    },\n    \"AsyncReplicationStatus\": {\n      \"@id\": \"weaviate:AsyncReplicationStatus\",\n      \"@type\": \"@id\"\n    },\n    \"objectsPropagated\": {\n      \"@id\": \"weaviate:objectsPropagated\",\n      \"@type\": \"xsd:float\"\n    },\n    \"startDiffTimeUnixMillis\": {\n      \"@id\": \"weaviate:startDiffTimeUnixMillis\",\n      \"@type\": \"xsd:float\"\n    },\n    \"VectorConfig\": {\n      \"@id\": \"weaviate:VectorConfig\",\n      \"@type\": \"@id\"\n    },\n    \"vectorizer\": {\n      \"@id\": \"weaviate:vectorizer\"\n    },\n    \"vectorIndexType\": {\n      \"@id\": \"weaviate:vectorIndexType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"vectorIndexConfig\": {\n      \"@id\": \"weaviate:vectorIndexConfig\"\n    },\n    \"RestoreConfig\": {\n      \"@id\": \"weaviate:RestoreConfig\",\n      \"@type\": \"@id\"\n    },\n    \"Endpoint\": {\n      \"@id\": \"weaviate:Endpoint\",\n      \"\
  @type\": \"xsd:string\"\n    },\n    \"Bucket\": {\n      \"@id\": \"weaviate:Bucket\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Path\": {\n      \"@id\": \"weaviate:Path\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CPUPercentage\": {\n      \"@id\": \"weaviate:CPUPercentage\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"rolesOptions\": {\n      \"@id\": \"weaviate:rolesOptions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"usersOptions\": {\n      \"@id\": \"weaviate:usersOptions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"C11yWordsResponse\": {\n      \"@id\": \"weaviate:C11yWordsResponse\",\n      \"@type\": \"@id\"\n    },\n    \"concatenatedWord\": {\n      \"@id\": \"weaviate:concatenatedWord\"\n    },\n    \"individualWords\": {\n      \"@id\": \"weaviate:individualWords\"\n    },\n    \"ReplicationReplicateDetailsReplicaStatus\": {\n      \"@id\": \"weaviate:ReplicationReplicateDetailsReplicaStatus\",\n      \"@type\": \"@id\"\n    },\n    \"state\"\
  : {\n      \"@id\": \"weaviate:state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"errors\": {\n      \"@id\": \"weaviate:errors\"\n    },\n    \"VectorWeights\": {\n      \"@id\": \"weaviate:VectorWeights\",\n      \"@type\": \"@id\"\n    },\n    \"TokenizeResponse\": {\n      \"@id\": \"weaviate:TokenizeResponse\",\n      \"@type\": \"@id\"\n    },\n    \"indexed\": {\n      \"@id\": \"weaviate:indexed\"\n    },\n    \"query\": {\n      \"@id\": \"weaviate:query\"\n    },\n    \"Statistics\": {\n      \"@id\": \"weaviate:Statistics\",\n      \"@type\": \"@id\"\n    },\n    \"bootstrapped\": {\n      \"@id\": \"weaviate:bootstrapped\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"dbLoaded\": {\n      \"@id\": \"weaviate:dbLoaded\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"initialLastAppliedIndex\": {\n      \"@id\": \"weaviate:initialLastAppliedIndex\",\n      \"@type\": \"xsd:float\"\n    },\n    \"lastAppliedIndex\": {\n      \"@id\": \"weaviate:lastAppliedIndex\",\n\
  \      \"@type\": \"xsd:float\"\n    },\n    \"isVoter\": {\n      \"@id\": \"weaviate:isVoter\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"leaderId\": {\n      \"@id\": \"weaviate:leaderId\"\n    },\n    \"leaderAddress\": {\n      \"@id\": \"weaviate:leaderAddress\"\n    },\n    \"open\": {\n      \"@id\": \"weaviate:open\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"ready\": {\n      \"@id\": \"weaviate:ready\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"candidates\": {\n      \"@id\": \"weaviate:candidates\"\n    },\n    \"raft\": {\n      \"@id\": \"weaviate:raft\"\n    },\n    \"C11yVector\": {\n      \"@id\": \"weaviate:C11yVector\",\n      \"@type\": \"@id\"\n    },\n    \"SingleRef\": {\n      \"@id\": \"weaviate:SingleRef\",\n      \"@type\": \"@id\"\n    },\n    \"class\": {\n      \"@id\": \"weaviate:class\",\n      \"@type\": \"xsd:anyURI\"\n    },\n    \"schema\": {\n      \"@id\": \"weaviate:schema\"\n    },\n    \"beacon\": {\n      \"@id\": \"weaviate:beacon\"\
  ,\n      \"@type\": \"xsd:anyURI\"\n    },\n    \"href\": {\n      \"@id\": \"weaviate:href\",\n      \"@type\": \"xsd:anyURI\"\n    },\n    \"classification\": {\n      \"@id\": \"weaviate:classification\"\n    },\n    \"PropertyTokenizeRequest\": {\n      \"@id\": \"weaviate:PropertyTokenizeRequest\",\n      \"@type\": \"@id\"\n    },\n    \"text\": {\n      \"@id\": \"weaviate:text\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PropertySchema\": {\n      \"@id\": \"weaviate:PropertySchema\",\n      \"@type\": \"@id\"\n    },\n    \"WhereFilter\": {\n      \"@id\": \"weaviate:WhereFilter\",\n      \"@type\": \"@id\"\n    },\n    \"operands\": {\n      \"@id\": \"weaviate:operands\"\n    },\n    \"operator\": {\n      \"@id\": \"weaviate:operator\",\n      \"@type\": \"xsd:string\"\n    },\n    \"path\": {\n      \"@id\": \"weaviate:path\"\n    },\n    \"valueInt\": {\n      \"@id\": \"weaviate:valueInt\",\n      \"@type\": \"xsd:long\"\n    },\n    \"valueNumber\": {\n      \"@id\"\
  : \"weaviate:valueNumber\",\n      \"@type\": \"xsd:float\"\n    },\n    \"valueBoolean\": {\n      \"@id\": \"weaviate:valueBoolean\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"valueString\": {\n      \"@id\": \"weaviate:valueString\",\n      \"@type\": \"xsd:string\"\n    },\n    \"valueText\": {\n      \"@id\": \"weaviate:valueText\",\n      \"@type\": \"xsd:string\"\n    },\n    \"valueDate\": {\n      \"@id\": \"weaviate:valueDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"valueIntArray\": {\n      \"@id\": \"weaviate:valueIntArray\"\n    },\n    \"valueNumberArray\": {\n      \"@id\": \"weaviate:valueNumberArray\"\n    },\n    \"valueBooleanArray\": {\n      \"@id\": \"weaviate:valueBooleanArray\"\n    },\n    \"valueStringArray\": {\n      \"@id\": \"weaviate:valueStringArray\"\n    },\n    \"valueTextArray\": {\n      \"@id\": \"weaviate:valueTextArray\"\n    },\n    \"valueDateArray\": {\n      \"@id\": \"weaviate:valueDateArray\"\n    },\n    \"valueGeoRange\"\
  : {\n      \"@id\": \"weaviate:valueGeoRange\"\n    },\n    \"Deprecation\": {\n      \"@id\": \"weaviate:Deprecation\",\n      \"@type\": \"@id\"\n    },\n    \"apiType\": {\n      \"@id\": \"weaviate:apiType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"msg\": {\n      \"@id\": \"weaviate:msg\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mitigation\": {\n      \"@id\": \"weaviate:mitigation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sinceVersion\": {\n      \"@id\": \"weaviate:sinceVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"plannedRemovalVersion\": {\n      \"@id\": \"weaviate:plannedRemovalVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"removedIn\": {\n      \"@id\": \"weaviate:removedIn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"removedTime\": {\n      \"@id\": \"weaviate:removedTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"sinceTime\": {\n      \"@id\": \"weaviate:sinceTime\",\n      \"@type\": \"xsd:dateTime\"\n   \
  \ },\n    \"locations\": {\n      \"@id\": \"weaviate:locations\"\n    },\n    \"AdditionalProperties\": {\n      \"@id\": \"weaviate:AdditionalProperties\",\n      \"@type\": \"@id\"\n    },\n    \"WhereFilterGeoRange\": {\n      \"@id\": \"weaviate:WhereFilterGeoRange\",\n      \"@type\": \"@id\"\n    },\n    \"geoCoordinates\": {\n      \"@id\": \"weaviate:geoCoordinates\"\n    },\n    \"distance\": {\n      \"@id\": \"weaviate:distance\"\n    },\n    \"UserTypeOutput\": {\n      \"@id\": \"weaviate:UserTypeOutput\",\n      \"@type\": \"@id\"\n    },\n    \"ReplicationReplicateReplicaRequest\": {\n      \"@id\": \"weaviate:ReplicationReplicateReplicaRequest\",\n      \"@type\": \"@id\"\n    },\n    \"BackupRestoreRequest\": {\n      \"@id\": \"weaviate:BackupRestoreRequest\",\n      \"@type\": \"@id\"\n    },\n    \"config\": {\n      \"@id\": \"weaviate:config\"\n    },\n    \"include\": {\n      \"@id\": \"weaviate:include\"\n    },\n    \"exclude\": {\n      \"@id\": \"weaviate:exclude\"\
  \n    },\n    \"node_mapping\": {\n      \"@id\": \"weaviate:node_mapping\"\n    },\n    \"overwriteAlias\": {\n      \"@id\": \"weaviate:overwriteAlias\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"ClassificationMeta\": {\n      \"@id\": \"weaviate:ClassificationMeta\",\n      \"@type\": \"@id\"\n    },\n    \"started\": {\n      \"@id\": \"weaviate:started\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"completed\": {\n      \"@id\": \"weaviate:completed\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"count\": {\n      \"@id\": \"weaviate:count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"countSucceeded\": {\n      \"@id\": \"weaviate:countSucceeded\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"countFailed\": {\n      \"@id\": \"weaviate:countFailed\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"GraphQLError\": {\n      \"@id\": \"weaviate:GraphQLError\",\n      \"@type\": \"@id\"\n    },\n    \"message\": {\n      \"@id\": \"weaviate:message\",\n  \
  \    \"@type\": \"xsd:string\"\n    },\n    \"RaftStatistics\": {\n      \"@id\": \"weaviate:RaftStatistics\",\n      \"@type\": \"@id\"\n    },\n    \"appliedIndex\": {\n      \"@id\": \"weaviate:appliedIndex\",\n      \"@type\": \"xsd:string\"\n    },\n    \"commitIndex\": {\n      \"@id\": \"weaviate:commitIndex\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fsmPending\": {\n      \"@id\": \"weaviate:fsmPending\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastContact\": {\n      \"@id\": \"weaviate:lastContact\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastLogIndex\": {\n      \"@id\": \"weaviate:lastLogIndex\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastLogTerm\": {\n      \"@id\": \"weaviate:lastLogTerm\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastSnapshotIndex\": {\n      \"@id\": \"weaviate:lastSnapshotIndex\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastSnapshotTerm\": {\n      \"@id\": \"weaviate:lastSnapshotTerm\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"latestConfiguration\": {\n      \"@id\": \"weaviate:latestConfiguration\"\n    },\n    \"latestConfigurationIndex\": {\n      \"@id\": \"weaviate:latestConfigurationIndex\",\n      \"@type\": \"xsd:string\"\n    },\n    \"numPeers\": {\n      \"@id\": \"weaviate:numPeers\",\n      \"@type\": \"xsd:string\"\n    },\n    \"protocolVersion\": {\n      \"@id\": \"weaviate:protocolVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"protocolVersionMax\": {\n      \"@id\": \"weaviate:protocolVersionMax\",\n      \"@type\": \"xsd:string\"\n    },\n    \"protocolVersionMin\": {\n      \"@id\": \"weaviate:protocolVersionMin\",\n      \"@type\": \"xsd:string\"\n    },\n    \"snapshotVersionMax\": {\n      \"@id\": \"weaviate:snapshotVersionMax\",\n      \"@type\": \"xsd:string\"\n    },\n    \"snapshotVersionMin\": {\n      \"@id\": \"weaviate:snapshotVersionMin\",\n      \"@type\": \"xsd:string\"\n    },\n    \"term\": {\n      \"@id\": \"weaviate:term\",\n\
  \      \"@type\": \"xsd:string\"\n    },\n    \"NamespaceListResponse\": {\n      \"@id\": \"weaviate:NamespaceListResponse\",\n      \"@type\": \"@id\"\n    },\n    \"Alias\": {\n      \"@id\": \"weaviate:Alias\",\n      \"@type\": \"@id\"\n    },\n    \"alias\": {\n      \"@id\": \"weaviate:alias\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Class\": {\n      \"@id\": \"weaviate:Class\",\n      \"@type\": \"@id\"\n    },\n    \"vectorConfig\": {\n      \"@id\": \"weaviate:vectorConfig\"\n    },\n    \"shardingConfig\": {\n      \"@id\": \"weaviate:shardingConfig\"\n    },\n    \"replicationConfig\": {\n      \"@id\": \"weaviate:replicationConfig\"\n    },\n    \"invertedIndexConfig\": {\n      \"@id\": \"weaviate:invertedIndexConfig\"\n    },\n    \"multiTenancyConfig\": {\n      \"@id\": \"weaviate:multiTenancyConfig\"\n    },\n    \"objectTtlConfig\": {\n      \"@id\": \"weaviate:objectTtlConfig\"\n    },\n    \"moduleConfig\": {\n      \"@id\": \"weaviate:moduleConfig\"\n   \
  \ },\n    \"properties\": {\n      \"@id\": \"weaviate:properties\"\n    },\n    \"BM25Config\": {\n      \"@id\": \"weaviate:BM25Config\",\n      \"@type\": \"@id\"\n    },\n    \"k1\": {\n      \"@id\": \"weaviate:k1\",\n      \"@type\": \"xsd:float\"\n    },\n    \"b\": {\n      \"@id\": \"weaviate:b\",\n      \"@type\": \"xsd:float\"\n    },\n    \"GraphQLResponses\": {\n      \"@id\": \"weaviate:GraphQLResponses\",\n      \"@type\": \"@id\"\n    },\n    \"Schema\": {\n      \"@id\": \"weaviate:Schema\",\n      \"@type\": \"@id\"\n    },\n    \"classes\": {\n      \"@id\": \"weaviate:classes\"\n    },\n    \"maintainer\": {\n      \"@id\": \"weaviate:maintainer\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Classification\": {\n      \"@id\": \"weaviate:Classification\",\n      \"@type\": \"@id\"\n    },\n    \"classifyProperties\": {\n      \"@id\": \"weaviate:classifyProperties\"\n    },\n    \"basedOnProperties\": {\n      \"@id\": \"weaviate:basedOnProperties\"\n    },\n  \
  \  \"meta\": {\n      \"@id\": \"weaviate:meta\"\n    },\n    \"settings\": {\n      \"@id\": \"weaviate:settings\"\n    },\n    \"error\": {\n      \"@id\": \"weaviate:error\",\n      \"@type\": \"xsd:string\"\n    },\n    \"filters\": {\n      \"@id\": \"weaviate:filters\"\n    },\n    \"Object\": {\n      \"@id\": \"weaviate:Object\",\n      \"@type\": \"@id\"\n    },\n    \"vectorWeights\": {\n      \"@id\": \"weaviate:vectorWeights\"\n    },\n    \"creationTimeUnix\": {\n      \"@id\": \"weaviate:creationTimeUnix\",\n      \"@type\": \"xsd:long\"\n    },\n    \"lastUpdateTimeUnix\": {\n      \"@id\": \"weaviate:lastUpdateTimeUnix\",\n      \"@type\": \"xsd:long\"\n    },\n    \"vector\": {\n      \"@id\": \"weaviate:vector\"\n    },\n    \"vectors\": {\n      \"@id\": \"weaviate:vectors\"\n    },\n    \"tenant\": {\n      \"@id\": \"weaviate:tenant\",\n      \"@type\": \"xsd:string\"\n    },\n    \"additional\": {\n      \"@id\": \"weaviate:additional\"\n    },\n    \"RolesListResponse\"\
  : {\n      \"@id\": \"weaviate:RolesListResponse\",\n      \"@type\": \"@id\"\n    },\n    \"MultipleRef\": {\n      \"@id\": \"weaviate:MultipleRef\",\n      \"@type\": \"@id\"\n    },\n    \"BatchDelete\": {\n      \"@id\": \"weaviate:BatchDelete\",\n      \"@type\": \"@id\"\n    },\n    \"match\": {\n      \"@id\": \"weaviate:match\"\n    },\n    \"output\": {\n      \"@id\": \"weaviate:output\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deletionTimeUnixMilli\": {\n      \"@id\": \"weaviate:deletionTimeUnixMilli\",\n      \"@type\": \"xsd:long\"\n    },\n    \"dryRun\": {\n      \"@id\": \"weaviate:dryRun\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"DistributedTasks\": {\n      \"@id\": \"weaviate:DistributedTasks\",\n      \"@type\": \"@id\"\n    },\n    \"ClusterStatisticsResponse\": {\n      \"@id\": \"weaviate:ClusterStatisticsResponse\",\n      \"@type\": \"@id\"\n    },\n    \"statistics\": {\n      \"@id\": \"weaviate:statistics\"\n    },\n    \"synchronized\": {\n\
  \      \"@id\": \"weaviate:synchronized\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"ReferenceMetaClassification\": {\n      \"@id\": \"weaviate:ReferenceMetaClassification\",\n      \"@type\": \"@id\"\n    },\n    \"overallCount\": {\n      \"@id\": \"weaviate:overallCount\",\n      \"@type\": \"xsd:float\"\n    },\n    \"winningCount\": {\n      \"@id\": \"weaviate:winningCount\",\n      \"@type\": \"xsd:float\"\n    },\n    \"losingCount\": {\n      \"@id\": \"weaviate:losingCount\",\n      \"@type\": \"xsd:float\"\n    },\n    \"closestOverallDistance\": {\n      \"@id\": \"weaviate:closestOverallDistance\",\n      \"@type\": \"xsd:float\"\n    },\n    \"winningDistance\": {\n      \"@id\": \"weaviate:winningDistance\",\n      \"@type\": \"xsd:float\"\n    },\n    \"meanWinningDistance\": {\n      \"@id\": \"weaviate:meanWinningDistance\",\n      \"@type\": \"xsd:float\"\n    },\n    \"closestWinningDistance\": {\n      \"@id\": \"weaviate:closestWinningDistance\",\n      \"\
  @type\": \"xsd:float\"\n    },\n    \"closestLosingDistance\": {\n      \"@id\": \"weaviate:closestLosingDistance\",\n      \"@type\": \"xsd:float\"\n    },\n    \"losingDistance\": {\n      \"@id\": \"weaviate:losingDistance\",\n      \"@type\": \"xsd:float\"\n    },\n    \"meanLosingDistance\": {\n      \"@id\": \"weaviate:meanLosingDistance\",\n      \"@type\": \"xsd:float\"\n    },\n    \"ShardProgress\": {\n      \"@id\": \"weaviate:ShardProgress\",\n      \"@type\": \"@id\"\n    },\n    \"objectsExported\": {\n      \"@id\": \"weaviate:objectsExported\",\n      \"@type\": \"xsd:long\"\n    },\n    \"skipReason\": {\n      \"@id\": \"weaviate:skipReason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"BackupConfig\": {\n      \"@id\": \"weaviate:BackupConfig\",\n      \"@type\": \"@id\"\n    },\n    \"ChunkSize\": {\n      \"@id\": \"weaviate:ChunkSize\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"CompressionLevel\": {\n      \"@id\": \"weaviate:CompressionLevel\",\n     \
  \ \"@type\": \"xsd:string\"\n    },\n    \"ReplicationReplicateForceDeleteRequest\": {\n      \"@id\": \"weaviate:ReplicationReplicateForceDeleteRequest\",\n      \"@type\": \"@id\"\n    },\n    \"node\": {\n      \"@id\": \"weaviate:node\",\n      \"@type\": \"xsd:string\"\n    },\n    \"UserTypeInput\": {\n      \"@id\": \"weaviate:UserTypeInput\",\n      \"@type\": \"@id\"\n    },\n    \"Property\": {\n      \"@id\": \"weaviate:Property\",\n      \"@type\": \"@id\"\n    },\n    \"indexInverted\": {\n      \"@id\": \"weaviate:indexInverted\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"disableDuplicatedReferences\": {\n      \"@id\": \"weaviate:disableDuplicatedReferences\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"ExportCreateRequest\": {\n      \"@id\": \"weaviate:ExportCreateRequest\",\n      \"@type\": \"@id\"\n    },\n    \"file_format\": {\n      \"@id\": \"weaviate:file_format\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ReplicationReplicateReplicaResponse\"\
  : {\n      \"@id\": \"weaviate:ReplicationReplicateReplicaResponse\",\n      \"@type\": \"@id\"\n    },\n    \"JsonObject\": {\n      \"@id\": \"weaviate:JsonObject\",\n      \"@type\": \"@id\"\n    },\n    \"AliasResponse\": {\n      \"@id\": \"weaviate:AliasResponse\",\n      \"@type\": \"@id\"\n    },\n    \"aliases\": {\n      \"@id\": \"weaviate:aliases\"\n    },\n    \"TextAnalyzerConfig\": {\n      \"@id\": \"weaviate:TextAnalyzerConfig\",\n      \"@type\": \"@id\"\n    },\n    \"asciiFold\": {\n      \"@id\": \"weaviate:asciiFold\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"asciiFoldIgnore\": {\n      \"@id\": \"weaviate:asciiFoldIgnore\"\n    },\n    \"stopwordPreset\": {\n      \"@id\": \"weaviate:stopwordPreset\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PeerUpdate\": {\n      \"@id\": \"weaviate:PeerUpdate\",\n      \"@type\": \"@id\"\n    },\n    \"uri\": {\n      \"@id\": \"weaviate:uri\",\n      \"@type\": \"xsd:anyURI\"\n    },\n    \"schemaHash\": {\n   \
  \   \"@id\": \"weaviate:schemaHash\",\n      \"@type\": \"xsd:string\"\n    },\n    \"BackupCreateStatusResponse\": {\n      \"@id\": \"weaviate:BackupCreateStatusResponse\",\n      \"@type\": \"@id\"\n    },\n    \"backend\": {\n      \"@id\": \"weaviate:backend\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startedAt\": {\n      \"@id\": \"weaviate:startedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"completedAt\": {\n      \"@id\": \"weaviate:completedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"size\": {\n      \"@id\": \"weaviate:size\",\n      \"@type\": \"xsd:float\"\n    },\n    \"DistributedTaskUnit\": {\n      \"@id\": \"weaviate:DistributedTaskUnit\",\n      \"@type\": \"@id\"\n    },\n    \"nodeId\": {\n      \"@id\": \"weaviate:nodeId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"progress\": {\n      \"@id\": \"weaviate:progress\",\n      \"@type\": \"xsd:float\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"weaviate:updatedAt\",\n      \"@type\"\
  : \"xsd:dateTime\"\n    },\n    \"finishedAt\": {\n      \"@id\": \"weaviate:finishedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"NodesStatusResponse\": {\n      \"@id\": \"weaviate:NodesStatusResponse\",\n      \"@type\": \"@id\"\n    },\n    \"nodes\": {\n      \"@id\": \"weaviate:nodes\"\n    },\n    \"ShardStatusList\": {\n      \"@id\": \"weaviate:ShardStatusList\",\n      \"@type\": \"@id\"\n    },\n    \"DBUserInfo\": {\n      \"@id\": \"weaviate:DBUserInfo\",\n      \"@type\": \"@id\"\n    },\n    \"roles\": {\n      \"@id\": \"weaviate:roles\"\n    },\n    \"userId\": {\n      \"@id\": \"weaviate:userId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dbUserType\": {\n      \"@id\": \"weaviate:dbUserType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"active\": {\n      \"@id\": \"weaviate:active\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"createdAt\": {\n      \"@id\": \"weaviate:createdAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"apiKeyFirstLetters\"\
  : {\n      \"@id\": \"weaviate:apiKeyFirstLetters\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastUsedAt\": {\n      \"@id\": \"weaviate:lastUsedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"namespace\": {\n      \"@id\": \"weaviate:namespace\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ObjectsGetResponse\": {\n      \"@id\": \"weaviate:ObjectsGetResponse\",\n      \"@type\": \"@id\"\n    },\n    \"ExportStatusResponse\": {\n      \"@id\": \"weaviate:ExportStatusResponse\",\n      \"@type\": \"@id\"\n    },\n    \"tookInMs\": {\n      \"@id\": \"weaviate:tookInMs\",\n      \"@type\": \"xsd:long\"\n    },\n    \"shardStatus\": {\n      \"@id\": \"weaviate:shardStatus\"\n    },\n    \"ReplicationShardingStateResponse\": {\n      \"@id\": \"weaviate:ReplicationShardingStateResponse\",\n      \"@type\": \"@id\"\n    },\n    \"shardingState\": {\n      \"@id\": \"weaviate:shardingState\"\n    },\n    \"BackupCreateRequest\": {\n      \"@id\": \"weaviate:BackupCreateRequest\"\
  ,\n      \"@type\": \"@id\"\n    },\n    \"incremental_base_backup_id\": {\n      \"@id\": \"weaviate:incremental_base_backup_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"NodeShardStatus\": {\n      \"@id\": \"weaviate:NodeShardStatus\",\n      \"@type\": \"@id\"\n    },\n    \"objectCount\": {\n      \"@id\": \"weaviate:objectCount\",\n      \"@type\": \"xsd:float\"\n    },\n    \"vectorIndexingStatus\": {\n      \"@id\": \"weaviate:vectorIndexingStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"compressed\": {\n      \"@id\": \"weaviate:compressed\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"vectorQueueLength\": {\n      \"@id\": \"weaviate:vectorQueueLength\",\n      \"@type\": \"xsd:float\"\n    },\n    \"loaded\": {\n      \"@id\": \"weaviate:loaded\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"asyncReplicationStatus\": {\n      \"@id\": \"weaviate:asyncReplicationStatus\"\n    },\n    \"numberOfReplicas\": {\n      \"@id\": \"weaviate:numberOfReplicas\"\
  ,\n      \"@type\": \"xsd:long\"\n    },\n    \"replicationFactor\": {\n      \"@id\": \"weaviate:replicationFactor\",\n      \"@type\": \"xsd:long\"\n    },\n    \"BatchDeleteResponse\": {\n      \"@id\": \"weaviate:BatchDeleteResponse\",\n      \"@type\": \"@id\"\n    },\n    \"results\": {\n      \"@id\": \"weaviate:results\"\n    },\n    \"Vector\": {\n      \"@id\": \"weaviate:Vector\",\n      \"@type\": \"@id\"\n    },\n    \"ReplicationConfig\": {\n      \"@id\": \"weaviate:ReplicationConfig\",\n      \"@type\": \"@id\"\n    },\n    \"factor\": {\n      \"@id\": \"weaviate:factor\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"asyncEnabled\": {\n      \"@id\": \"weaviate:asyncEnabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"asyncConfig\": {\n      \"@id\": \"weaviate:asyncConfig\"\n    },\n    \"deletionStrategy\": {\n      \"@id\": \"weaviate:deletionStrategy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ErrorResponse\": {\n      \"@id\": \"weaviate:ErrorResponse\"\
  ,\n      \"@type\": \"@id\"\n    },\n    \"Permission\": {\n      \"@id\": \"weaviate:Permission\",\n      \"@type\": \"@id\"\n    },\n    \"backups\": {\n      \"@id\": \"weaviate:backups\"\n    },\n    \"data\": {\n      \"@id\": \"weaviate:data\"\n    },\n    \"users\": {\n      \"@id\": \"weaviate:users\"\n    },\n    \"groups\": {\n      \"@id\": \"weaviate:groups\"\n    },\n    \"tenants\": {\n      \"@id\": \"weaviate:tenants\"\n    },\n    \"collections\": {\n      \"@id\": \"weaviate:collections\"\n    },\n    \"replicate\": {\n      \"@id\": \"weaviate:replicate\"\n    },\n    \"namespaces\": {\n      \"@id\": \"weaviate:namespaces\"\n    },\n    \"action\": {\n      \"@id\": \"weaviate:action\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MultiTenancyConfig\": {\n      \"@id\": \"weaviate:MultiTenancyConfig\",\n      \"@type\": \"@id\"\n    },\n    \"enabled\": {\n      \"@id\": \"weaviate:enabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"autoTenantCreation\":\
  \ {\n      \"@id\": \"weaviate:autoTenantCreation\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"autoTenantActivation\": {\n      \"@id\": \"weaviate:autoTenantActivation\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"Namespace\": {\n      \"@id\": \"weaviate:Namespace\",\n      \"@type\": \"@id\"\n    },\n    \"ReplicationScalePlan\": {\n      \"@id\": \"weaviate:ReplicationScalePlan\",\n      \"@type\": \"@id\"\n    },\n    \"planId\": {\n      \"@id\": \"weaviate:planId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shardScaleActions\": {\n      \"@id\": \"weaviate:shardScaleActions\"\n    },\n    \"Meta\": {\n      \"@id\": \"weaviate:Meta\",\n      \"@type\": \"@id\"\n    },\n    \"hostname\": {\n      \"@id\": \"weaviate:hostname\",\n      \"@type\": \"xsd:string\"\n    },\n    \"version\": {\n      \"@id\": \"weaviate:version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"modules\": {\n      \"@id\": \"weaviate:modules\"\n    },\n    \"grpcMaxMessageSize\": {\n\
  \      \"@id\": \"weaviate:grpcMaxMessageSize\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"BackupRestoreStatusResponse\": {\n      \"@id\": \"weaviate:BackupRestoreStatusResponse\",\n      \"@type\": \"@id\"\n    },\n    \"C11yExtension\": {\n      \"@id\": \"weaviate:C11yExtension\",\n      \"@type\": \"@id\"\n    },\n    \"concept\": {\n      \"@id\": \"weaviate:concept\",\n      \"@type\": \"xsd:string\"\n    },\n    \"definition\": {\n      \"@id\": \"weaviate:definition\",\n      \"@type\": \"xsd:string\"\n    },\n    \"weight\": {\n      \"@id\": \"weaviate:weight\",\n      \"@type\": \"xsd:float\"\n    },\n    \"Link\": {\n      \"@id\": \"weaviate:Link\",\n      \"@type\": \"@id\"\n    },\n    \"rel\": {\n      \"@id\": \"weaviate:rel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"documentationHref\": {\n      \"@id\": \"weaviate:documentationHref\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ReplicationShardReplicas\": {\n      \"@id\": \"weaviate:ReplicationShardReplicas\"\
  ,\n      \"@type\": \"@id\"\n    },\n    \"replicas\": {\n      \"@id\": \"weaviate:replicas\"\n    },\n    \"ReplicationScaleApplyResponse\": {\n      \"@id\": \"weaviate:ReplicationScaleApplyResponse\",\n      \"@type\": \"@id\"\n    },\n    \"operationIds\": {\n      \"@id\": \"weaviate:operationIds\"\n    },\n    \"UserApiKey\": {\n      \"@id\": \"weaviate:UserApiKey\",\n      \"@type\": \"@id\"\n    },\n    \"apikey\": {\n      \"@id\": \"weaviate:apikey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GraphQLQuery\": {\n      \"@id\": \"weaviate:GraphQLQuery\",\n      \"@type\": \"@id\"\n    },\n    \"operationName\": {\n      \"@id\": \"weaviate:operationName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"variables\": {\n      \"@id\": \"weaviate:variables\"\n    },\n    \"GraphQLQueries\": {\n      \"@id\": \"weaviate:GraphQLQueries\",\n      \"@type\": \"@id\"\n    },\n    \"BackupListResponse\": {\n      \"@id\": \"weaviate:BackupListResponse\",\n      \"@type\": \"@id\"\
  \n    },\n    \"StopwordConfig\": {\n      \"@id\": \"weaviate:StopwordConfig\",\n      \"@type\": \"@id\"\n    },\n    \"preset\": {\n      \"@id\": \"weaviate:preset\",\n      \"@type\": \"xsd:string\"\n    },\n    \"additions\": {\n      \"@id\": \"weaviate:additions\"\n    },\n    \"removals\": {\n      \"@id\": \"weaviate:removals\"\n    },\n    \"BackupRestoreResponse\": {\n      \"@id\": \"weaviate:BackupRestoreResponse\",\n      \"@type\": \"@id\"\n    },\n    \"ShardStatus\": {\n      \"@id\": \"weaviate:ShardStatus\",\n      \"@type\": \"@id\"\n    },\n    \"GroupType\": {\n      \"@id\": \"weaviate:GroupType\",\n      \"@type\": \"@id\"\n    },\n    \"BatchReference\": {\n      \"@id\": \"weaviate:BatchReference\",\n      \"@type\": \"@id\"\n    },\n    \"from\": {\n      \"@id\": \"weaviate:from\",\n      \"@type\": \"xsd:anyURI\"\n    },\n    \"to\": {\n      \"@id\": \"weaviate:to\",\n      \"@type\": \"xsd:anyURI\"\n    },\n    \"UserOwnInfo\": {\n      \"@id\": \"weaviate:UserOwnInfo\"\
  ,\n      \"@type\": \"@id\"\n    },\n    \"username\": {\n      \"@id\": \"weaviate:username\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ObjectTtlConfig\": {\n      \"@id\": \"weaviate:ObjectTtlConfig\",\n      \"@type\": \"@id\"\n    },\n    \"defaultTtl\": {\n      \"@id\": \"weaviate:defaultTtl\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"deleteOn\": {\n      \"@id\": \"weaviate:deleteOn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"filterExpiredObjects\": {\n      \"@id\": \"weaviate:filterExpiredObjects\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"ObjectsListResponse\": {\n      \"@id\": \"weaviate:ObjectsListResponse\",\n      \"@type\": \"@id\"\n    },\n    \"objects\": {\n      \"@id\": \"weaviate:objects\"\n    },\n    \"deprecations\": {\n      \"@id\": \"weaviate:deprecations\"\n    },\n    \"totalResults\": {\n      \"@id\": \"weaviate:totalResults\",\n      \"@type\": \"xsd:long\"\n    },\n    \"TokenizeRequest\": {\n      \"@id\": \"weaviate:TokenizeRequest\"\
  ,\n      \"@type\": \"@id\"\n    },\n    \"analyzerConfig\": {\n      \"@id\": \"weaviate:analyzerConfig\"\n    },\n    \"stopwords\": {\n      \"@id\": \"weaviate:stopwords\"\n    },\n    \"stopwordPresets\": {\n      \"@id\": \"weaviate:stopwordPresets\"\n    },\n    \"InvertedIndexConfig\": {\n      \"@id\": \"weaviate:InvertedIndexConfig\",\n      \"@type\": \"@id\"\n    },\n    \"cleanupIntervalSeconds\": {\n      \"@id\": \"weaviate:cleanupIntervalSeconds\",\n      \"@type\": \"xsd:float\"\n    },\n    \"bm25\": {\n      \"@id\": \"weaviate:bm25\"\n    },\n    \"indexTimestamps\": {\n      \"@id\": \"weaviate:indexTimestamps\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"indexNullState\": {\n      \"@id\": \"weaviate:indexNullState\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"indexPropertyLength\": {\n      \"@id\": \"weaviate:indexPropertyLength\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"usingBlockMaxWAND\": {\n      \"@id\": \"weaviate:usingBlockMaxWAND\",\n\
  \      \"@type\": \"xsd:boolean\"\n    },\n    \"tokenizerUserDict\": {\n      \"@id\": \"weaviate:tokenizerUserDict\"\n    },\n    \"NodeStatus\": {\n      \"@id\": \"weaviate:NodeStatus\",\n      \"@type\": \"@id\"\n    },\n    \"gitHash\": {\n      \"@id\": \"weaviate:gitHash\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stats\": {\n      \"@id\": \"weaviate:stats\"\n    },\n    \"batchStats\": {\n      \"@id\": \"weaviate:batchStats\"\n    },\n    \"shards\": {\n      \"@id\": \"weaviate:shards\"\n    },\n    \"operationalMode\": {\n      \"@id\": \"weaviate:operationalMode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Vectors\": {\n      \"@id\": \"weaviate:Vectors\",\n      \"@type\": \"@id\"\n    },\n    \"GeoCoordinates\": {\n      \"@id\": \"weaviate:GeoCoordinates\",\n      \"@type\": \"@id\"\n    },\n    \"latitude\": {\n      \"@id\": \"weaviate:latitude\",\n      \"@type\": \"xsd:float\"\n    },\n    \"longitude\": {\n      \"@id\": \"weaviate:longitude\",\n    \
  \  \"@type\": \"xsd:float\"\n    },\n    \"NodeStats\": {\n      \"@id\": \"weaviate:NodeStats\",\n      \"@type\": \"@id\"\n    },\n    \"shardCount\": {\n      \"@id\": \"weaviate:shardCount\",\n      \"@type\": \"xsd:float\"\n    },\n    \"ReplicationReplicateDetailsReplicaStatusError\": {\n      \"@id\": \"weaviate:ReplicationReplicateDetailsReplicaStatusError\",\n      \"@type\": \"@id\"\n    },\n    \"whenErroredUnixMs\": {\n      \"@id\": \"weaviate:whenErroredUnixMs\",\n      \"@type\": \"xsd:long\"\n    },\n    \"GraphQLResponse\": {\n      \"@id\": \"weaviate:GraphQLResponse\",\n      \"@type\": \"@id\"\n    },\n    \"BatchStats\": {\n      \"@id\": \"weaviate:BatchStats\",\n      \"@type\": \"@id\"\n    },\n    \"queueLength\": {\n      \"@id\": \"weaviate:queueLength\",\n      \"@type\": \"xsd:float\"\n    },\n    \"ratePerSecond\": {\n      \"@id\": \"weaviate:ratePerSecond\",\n      \"@type\": \"xsd:float\"\n    },\n    \"ReplicationShardingState\": {\n      \"@id\": \"weaviate:ReplicationShardingState\"\
  ,\n      \"@type\": \"@id\"\n    },\n    \"C11yNearestNeighbors\": {\n      \"@id\": \"weaviate:C11yNearestNeighbors\",\n      \"@type\": \"@id\"\n    },\n    \"TokenizerUserDictConfig\": {\n      \"@id\": \"weaviate:TokenizerUserDictConfig\",\n      \"@type\": \"@id\"\n    },\n    \"tokenizer\": {\n      \"@id\": \"weaviate:tokenizer\",\n      \"@type\": \"xsd:string\"\n    },\n    \"replacements\": {\n      \"@id\": \"weaviate:replacements\"\n    },\n    \"ReplicationReplicateForceDeleteResponse\": {\n      \"@id\": \"weaviate:ReplicationReplicateForceDeleteResponse\",\n      \"@type\": \"@id\"\n    },\n    \"deleted\": {\n      \"@id\": \"weaviate:deleted\"\n    },\n    \"DistributedTask\": {\n      \"@id\": \"weaviate:DistributedTask\",\n      \"@type\": \"@id\"\n    },\n    \"finishedNodes\": {\n      \"@id\": \"weaviate:finishedNodes\"\n    },\n    \"payload\": {\n      \"@id\": \"weaviate:payload\"\n    },\n    \"units\": {\n      \"@id\": \"weaviate:units\"\n    },\n    \"ReplicationAsyncConfig\"\
  : {\n      \"@id\": \"weaviate:ReplicationAsyncConfig\",\n      \"@type\": \"@id\"\n    },\n    \"maxWorkers\": {\n      \"@id\": \"weaviate:maxWorkers\",\n      \"@type\": \"xsd:long\"\n    },\n    \"hashtreeHeight\": {\n      \"@id\": \"weaviate:hashtreeHeight\",\n      \"@type\": \"xsd:long\"\n    },\n    \"frequency\": {\n      \"@id\": \"weaviate:frequency\",\n      \"@type\": \"xsd:long\"\n    },\n    \"frequenc\n\n# --- truncated at 32 KB (34 KB total) ---\n# Full source: https://raw.githubusercontent.com/api-evangelist/weaviate/refs/heads/main/json-ld/weaviate-context.jsonld\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/weaviate/refs/heads/main/json-ld/weaviate-context.jsonld
tags:
- Vector Database
- AI
- Machine Learning
- Semantic Search
- Open Source
- GraphQL
- Kubernetes
- JSON-LD
- Linked Data
- Semantic Web
---
