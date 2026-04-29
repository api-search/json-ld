---
class_count: 128
classes:
- DagStatsCollectionResponse
- ExternalLogUrlResponse
- ConfigOption
- BackfillPostBody
- TaskDependencyCollectionResponse
- XComResponseString
- DAGWarningResponse
- LastAssetEventResponse
- DAGWarningCollectionResponse
- MaterializeAssetBody
- HITLDetailHistory
- DagTagResponse
- ProviderResponse
- EventLogCollectionResponse
- EventLogResponse
- BulkDeleteAction_BulkTaskInstanceBody_
- BulkActionResponse
- TriggerResponse
- DagRunAssetReference
- ConfigSection
- DAGRunCollectionResponse
- BulkBody_PoolBody_
- CreateAssetEventsBody
- HITLDetailResponse
- BulkBody_BulkTaskInstanceBody_
- StructuredLogMessage
- ImportErrorCollectionResponse
- ExternalViewResponse
- DagStatsStateResponse
- BulkBody_VariableBody_
- ConnectionCollectionResponse
- BulkResponse
- JobCollectionResponse
- Config
- ConnectionBody
- VariableResponse
- DAGTagCollectionResponse
- BulkCreateAction_VariableBody_
- TriggerDAGRunPostBody
- TaskInstancesBatchBody
- ExtraLinkCollectionResponse
- TaskCollectionResponse
- DAGRunResponse
- BulkDeleteAction_VariableBody_
- ReactAppResponse
- QueuedEventCollectionResponse
- TriggererInfoResponse
- VersionInfo
- DryRunBackfillResponse
- PoolCollectionResponse
- TaskInletAssetReference
- TaskInstanceCollectionResponse
- DagScheduleAssetReference
- UpdateHITLDetailPayload
- VariableBody
- DAGSourceResponse
- BackfillCollectionResponse
- DAGRunPatchBody
- TaskInstanceResponse
- HITLDetail
- XComResponseNative
- XComResponse
- XComUpdateBody
- QueuedEventResponse
- AssetWatcherResponse
- BulkUpdateAction_PoolBody_
- ConnectionTestResponse
- TaskOutletAssetReference
- PoolBody
- DagProcessorInfoResponse
- XComCollectionResponse
- DagStatsResponse
- FastAPIRootMiddlewareResponse
- DAGVersionCollectionResponse
- AppBuilderViewResponse
- DAGPatchBody
- BulkCreateAction_PoolBody_
- PluginResponse
- TaskResponse
- SchedulerInfoResponse
- ImportErrorResponse
- TaskInstancesLogResponse
- HITLUser
- VariableCollectionResponse
- TaskInstanceHistoryResponse
- TimeDelta
- PoolPatchBody
- ClearTaskInstancesBody
- BaseInfoResponse
- DAGCollectionResponse
- ProviderCollectionResponse
- JobResponse
- HTTPExceptionResponse
- BulkCreateAction_BulkTaskInstanceBody_
- BulkBody_ConnectionBody_
- XComCreateBody
- BulkUpdateAction_ConnectionBody_
- PatchTaskInstanceBody
- PluginCollectionResponse
- HITLDetailCollection
- AssetAliasResponse
- AssetEventCollectionResponse
- TaskDependencyResponse
- PoolResponse
- DAGDetailsResponse
- BulkTaskInstanceBody
- AssetEventResponse
- DAGRunClearBody
- AssetCollectionResponse
- BulkUpdateAction_VariableBody_
- DAGRunsBatchBody
- AssetResponse
- BackfillResponse
- BulkDeleteAction_PoolBody_
- AppBuilderMenuItemResponse
- BulkDeleteAction_ConnectionBody_
- BulkUpdateAction_BulkTaskInstanceBody_
- FastAPIAppResponse
- TaskInstanceHistoryCollectionResponse
- PluginImportErrorCollectionResponse
- AssetAliasCollectionResponse
- BulkCreateAction_ConnectionBody_
- DAGResponse
- PluginImportErrorResponse
- ConnectionResponse
- DryRunBackfillCollectionResponse
- DagVersionResponse
- HealthInfoResponse
context_file: json-ld/airflow-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/airflow/refs/heads/main/json-ld/airflow-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Airflow from Apache Airflow.
layout: jsonld
name: Airflow Context
namespaces:
- prefix: airflow
  uri: https://airflow.apache.org/schema/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: schema
  type: ''
- container: ''
  name: dags
  type: ''
- container: ''
  name: totalEntries
  type: integer
- container: ''
  name: url
  type: ''
- container: ''
  name: key
  type: ''
- container: ''
  name: value
  type: ''
- container: ''
  name: dagId
  type: ''
- container: ''
  name: fromDate
  type: dateTime
- container: ''
  name: toDate
  type: dateTime
- container: ''
  name: runBackwards
  type: boolean
- container: ''
  name: dagRunConf
  type: ''
- container: ''
  name: reprocessBehavior
  type: ''
- container: ''
  name: maxActiveRuns
  type: ''
- container: ''
  name: runOnLatestVersion
  type: boolean
- container: ''
  name: dependencies
  type: ''
- container: ''
  name: timestamp
  type: dateTime
- container: ''
  name: logicalDate
  type: ''
- container: ''
  name: mapIndex
  type: ''
- container: ''
  name: taskId
  type: ''
- container: ''
  name: runId
  type: ''
- container: ''
  name: dagDisplayName
  type: ''
- container: ''
  name: taskDisplayName
  type: ''
- container: ''
  name: runAfter
  type: dateTime
- container: ''
  name: warningType
  type: ''
- container: ''
  name: message
  type: ''
- container: ''
  name: id
  type: ''
- container: ''
  name: dagWarnings
  type: ''
- container: ''
  name: dagRunId
  type: ''
- container: ''
  name: dataIntervalStart
  type: ''
- container: ''
  name: dataIntervalEnd
  type: ''
- container: ''
  name: conf
  type: ''
- container: ''
  name: note
  type: ''
- container: ''
  name: partitionKey
  type: ''
- container: ''
  name: options
  type: ''
- container: ''
  name: subject
  type: ''
- container: ''
  name: body
  type: ''
- container: ''
  name: defaults
  type: ''
- container: ''
  name: multiple
  type: boolean
- container: ''
  name: params
  type: ''
- container: ''
  name: assignedUsers
  type: ''
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: respondedByUser
  type: ''
- container: ''
  name: respondedAt
  type: ''
- container: ''
  name: chosenOptions
  type: ''
- container: ''
  name: paramsInput
  type: ''
- container: ''
  name: responseReceived
  type: boolean
- container: ''
  name: taskInstance
  type: ''
- container: ''
  name: name
  type: ''
- container: ''
  name: packageName
  type: ''
- container: ''
  name: description
  type: ''
- container: ''
  name: version
  type: ''
- container: ''
  name: documentationUrl
  type: ''
- container: ''
  name: eventLogs
  type: ''
- container: ''
  name: eventLogId
  type: integer
- container: ''
  name: when
  type: dateTime
- container: ''
  name: tryNumber
  type: integer
- container: ''
  name: event
  type: ''
- container: ''
  name: owner
  type: ''
- container: ''
  name: extra
  type: ''
- container: ''
  name: action
  type: ''
- container: ''
  name: entities
  type: ''
- container: ''
  name: actionOnNonExistence
  type: ''
- container: ''
  name: success
  type: ''
- container: ''
  name: errors
  type: ''
- container: ''
  name: classpath
  type: ''
- container: ''
  name: kwargs
  type: ''
- container: ''
  name: createdDate
  type: dateTime
- container: ''
  name: queue
  type: ''
- container: ''
  name: triggererId
  type: ''
- container: ''
  name: startDate
  type: ''
- container: ''
  name: endDate
  type: ''
- container: ''
  name: state
  type: ''
- container: ''
  name: dagRuns
  type: ''
- container: ''
  name: actions
  type: ''
- container: ''
  name: assetId
  type: integer
- container: ''
  name: respondedBy
  type: ''
- container: ''
  name: importErrors
  type: ''
- container: ''
  name: icon
  type: ''
- container: ''
  name: iconDarkMode
  type: ''
- container: ''
  name: urlRoute
  type: ''
- container: ''
  name: category
  type: ''
- container: ''
  name: href
  type: ''
- container: ''
  name: destination
  type: ''
- container: ''
  name: count
  type: integer
- container: ''
  name: connections
  type: ''
- container: ''
  name: create
  type: ''
- container: ''
  name: update
  type: ''
- container: ''
  name: delete
  type: ''
- container: ''
  name: jobs
  type: ''
- container: ''
  name: sections
  type: ''
- container: ''
  name: connectionId
  type: ''
- container: ''
  name: connType
  type: ''
- container: ''
  name: host
  type: ''
- container: ''
  name: login
  type: ''
- container: ''
  name: port
  type: ''
- container: ''
  name: password
  type: ''
- container: ''
  name: teamName
  type: ''
- container: ''
  name: isEncrypted
  type: boolean
- container: ''
  name: tags
  type: ''
- container: ''
  name: actionOnExistence
  type: ''
- container: ''
  name: dagIds
  type: ''
- container: ''
  name: dagRunIds
  type: ''
- container: ''
  name: taskIds
  type: ''
- container: ''
  name: runAfterGte
  type: ''
- container: ''
  name: runAfterGt
  type: ''
- container: ''
  name: runAfterLte
  type: ''
- container: ''
  name: runAfterLt
  type: ''
- container: ''
  name: logicalDateGte
  type: ''
- container: ''
  name: logicalDateGt
  type: ''
- container: ''
  name: logicalDateLte
  type: ''
- container: ''
  name: logicalDateLt
  type: ''
- container: ''
  name: startDateGte
  type: ''
- container: ''
  name: startDateGt
  type: ''
- container: ''
  name: startDateLte
  type: ''
- container: ''
  name: startDateLt
  type: ''
- container: ''
  name: endDateGte
  type: ''
- container: ''
  name: endDateGt
  type: ''
- container: ''
  name: endDateLte
  type: ''
- container: ''
  name: endDateLt
  type: ''
- container: ''
  name: durationGte
  type: ''
- container: ''
  name: durationGt
  type: ''
- container: ''
  name: durationLte
  type: ''
- container: ''
  name: durationLt
  type: ''
- container: ''
  name: pool
  type: ''
- container: ''
  name: executor
  type: ''
- container: ''
  name: pageOffset
  type: integer
- container: ''
  name: pageLimit
  type: integer
- container: ''
  name: orderBy
  type: ''
- container: ''
  name: extraLinks
  type: ''
- container: ''
  name: tasks
  type: ''
- container: ''
  name: queuedAt
  type: ''
- container: ''
  name: duration
  type: ''
- container: ''
  name: lastSchedulingDecision
  type: ''
- container: ''
  name: runType
  type: ''
- container: ''
  name: triggeredBy
  type: ''
- container: ''
  name: triggeringUserName
  type: ''
- container: ''
  name: dagVersions
  type: ''
- container: ''
  name: bundleVersion
  type: ''
- container: ''
  name: bundleUrl
  type: ''
- container: ''
  name: queuedEvents
  type: ''
- container: ''
  name: status
  type: ''
- container: ''
  name: latestTriggererHeartbeat
  type: ''
- container: ''
  name: gitVersion
  type: ''
- container: ''
  name: partitionDate
  type: ''
- container: ''
  name: pools
  type: ''
- container: ''
  name: updatedAt
  type: dateTime
- container: ''
  name: taskInstances
  type: ''
- container: ''
  name: nextCursor
  type: ''
- container: ''
  name: previousCursor
  type: ''
- container: ''
  name: content
  type: ''
- container: ''
  name: versionNumber
  type: integer
- container: ''
  name: backfills
  type: ''
- container: ''
  name: maxTries
  type: integer
- container: ''
  name: hostname
  type: ''
- container: ''
  name: unixname
  type: ''
- container: ''
  name: poolSlots
  type: integer
- container: ''
  name: priorityWeight
  type: ''
- container: ''
  name: operator
  type: ''
- container: ''
  name: operatorName
  type: ''
- container: ''
  name: queuedWhen
  type: ''
- container: ''
  name: scheduledWhen
  type: ''
- container: ''
  name: pid
  type: ''
- container: ''
  name: executorConfig
  type: ''
- container: ''
  name: renderedMapIndex
  type: ''
- container: ''
  name: renderedFields
  type: ''
- container: ''
  name: trigger
  type: ''
- container: ''
  name: triggererJob
  type: ''
- container: ''
  name: dagVersion
  type: ''
- container: ''
  name: triggerId
  type: integer
- container: ''
  name: updateMask
  type: ''
- container: ''
  name: slots
  type: integer
- container: ''
  name: includeDeferred
  type: boolean
- container: ''
  name: latestDagProcessorHeartbeat
  type: ''
- container: ''
  name: xcomEntries
  type: ''
- container: ''
  name: stats
  type: ''
- container: ''
  name: middleware
  type: ''
- container: ''
  name: view
  type: ''
- container: ''
  name: label
  type: ''
- container: ''
  name: isPaused
  type: boolean
- container: ''
  name: macros
  type: ''
- container: ''
  name: flaskBlueprints
  type: ''
- container: ''
  name: fastapiApps
  type: ''
- container: ''
  name: fastapiRootMiddlewares
  type: ''
- container: ''
  name: externalViews
  type: ''
- container: ''
  name: reactApps
  type: ''
- container: ''
  name: appbuilderViews
  type: ''
- container: ''
  name: appbuilderMenuItems
  type: ''
- container: ''
  name: globalOperatorExtraLinks
  type: ''
- container: ''
  name: operatorExtraLinks
  type: ''
- container: ''
  name: source
  type: ''
- container: ''
  name: listeners
  type: ''
- container: ''
  name: timetables
  type: ''
- container: ''
  name: triggerRule
  type: ''
- container: ''
  name: dependsOnPast
  type: boolean
- container: ''
  name: waitForDownstream
  type: boolean
- container: ''
  name: retries
  type: ''
- container: ''
  name: executionTimeout
  type: ''
- container: ''
  name: retryDelay
  type: ''
- container: ''
  name: retryExponentialBackoff
  type: decimal
- container: ''
  name: weightRule
  type: ''
- container: ''
  name: uiColor
  type: ''
- container: ''
  name: uiFgcolor
  type: ''
- container: ''
  name: templateFields
  type: ''
- container: ''
  name: downstreamTaskIds
  type: ''
- container: ''
  name: docMd
  type: ''
- container: ''
  name: classRef
  type: ''
- container: ''
  name: isMapped
  type: ''
- container: ''
  name: latestSchedulerHeartbeat
  type: ''
- container: ''
  name: importErrorId
  type: integer
- container: ''
  name: filename
  type: ''
- container: ''
  name: bundleName
  type: ''
- container: ''
  name: stackTrace
  type: ''
- container: ''
  name: continuationToken
  type: ''
- container: ''
  name: variables
  type: ''
- container: ''
  name: Type
  type: ''
- container: ''
  name: days
  type: integer
- container: ''
  name: seconds
  type: integer
- container: ''
  name: microseconds
  type: integer
- container: ''
  name: dryRun
  type: boolean
- container: ''
  name: onlyFailed
  type: boolean
- container: ''
  name: onlyRunning
  type: boolean
- container: ''
  name: resetDagRuns
  type: boolean
- container: ''
  name: includeUpstream
  type: boolean
- container: ''
  name: includeDownstream
  type: boolean
- container: ''
  name: includeFuture
  type: boolean
- container: ''
  name: includePast
  type: boolean
- container: ''
  name: preventRunningTask
  type: boolean
- container: ''
  name: providers
  type: ''
- container: ''
  name: jobType
  type: ''
- container: ''
  name: latestHeartbeat
  type: ''
- container: ''
  name: executorClass
  type: ''
- container: ''
  name: detail
  type: ''
- container: ''
  name: newState
  type: ''
- container: ''
  name: plugins
  type: ''
- container: ''
  name: hitlDetails
  type: ''
- container: ''
  name: group
  type: ''
- container: ''
  name: assetEvents
  type: ''
- container: ''
  name: reason
  type: ''
- container: ''
  name: occupiedSlots
  type: integer
- container: ''
  name: runningSlots
  type: integer
- container: ''
  name: queuedSlots
  type: integer
- container: ''
  name: scheduledSlots
  type: integer
- container: ''
  name: openSlots
  type: integer
- container: ''
  name: deferredSlots
  type: integer
- container: ''
  name: isStale
  type: boolean
- container: ''
  name: lastParsedTime
  type: ''
- container: ''
  name: lastParseDuration
  type: ''
- container: ''
  name: lastExpired
  type: ''
- container: ''
  name: relativeFileloc
  type: ''
- container: ''
  name: fileloc
  type: ''
- container: ''
  name: timetableSummary
  type: ''
- container: ''
  name: timetableDescription
  type: ''
- container: ''
  name: timetablePartitioned
  type: boolean
- container: ''
  name: timetablePeriodic
  type: boolean
- container: ''
  name: maxActiveTasks
  type: integer
- container: ''
  name: maxConsecutiveFailedDagRuns
  type: integer
- container: ''
  name: hasTaskConcurrencyLimits
  type: boolean
- container: ''
  name: hasImportErrors
  type: boolean
- container: ''
  name: nextDagrunLogicalDate
  type: ''
- container: ''
  name: nextDagrunDataIntervalStart
  type: ''
- container: ''
  name: nextDagrunDataIntervalEnd
  type: ''
- container: ''
  name: nextDagrunRunAfter
  type: ''
- container: ''
  name: allowedRunTypes
  type: ''
- container: ''
  name: owners
  type: ''
- container: ''
  name: catchup
  type: boolean
- container: ''
  name: dagRunTimeout
  type: ''
- container: ''
  name: assetExpression
  type: ''
- container: ''
  name: isPausedUponCreation
  type: ''
- container: ''
  name: renderTemplateAsNativeObj
  type: boolean
- container: ''
  name: templateSearchPath
  type: ''
- container: ''
  name: timezone
  type: ''
- container: ''
  name: lastParsed
  type: ''
- container: ''
  name: defaultArgs
  type: ''
- container: ''
  name: ownerLinks
  type: ''
- container: ''
  name: isFavorite
  type: boolean
- container: ''
  name: activeRunsCount
  type: integer
- container: ''
  name: isBackfillable
  type: boolean
- container: ''
  name: fileToken
  type: ''
- container: ''
  name: concurrency
  type: integer
- container: ''
  name: latestDagVersion
  type: ''
- container: ''
  name: uri
  type: ''
- container: ''
  name: sourceTaskId
  type: ''
- container: ''
  name: sourceDagId
  type: ''
- container: ''
  name: sourceRunId
  type: ''
- container: ''
  name: sourceMapIndex
  type: integer
- container: ''
  name: createdDagruns
  type: ''
- container: ''
  name: assets
  type: ''
- container: ''
  name: states
  type: ''
- container: ''
  name: confContains
  type: ''
- container: ''
  name: scheduledDags
  type: ''
- container: ''
  name: producingTasks
  type: ''
- container: ''
  name: consumingTasks
  type: ''
- container: ''
  name: aliases
  type: ''
- container: ''
  name: watchers
  type: ''
- container: ''
  name: lastAssetEvent
  type: ''
- container: ''
  name: completedAt
  type: ''
- container: ''
  name: app
  type: ''
- container: ''
  name: urlPrefix
  type: ''
- container: ''
  name: assetAliases
  type: ''
- container: ''
  name: error
  type: ''
- container: ''
  name: metadatabase
  type: ''
- container: ''
  name: scheduler
  type: ''
- container: ''
  name: triggerer
  type: ''
- container: ''
  name: dagProcessor
  type: ''
property_count: 304
provider_name: Apache Airflow
provider_slug: airflow
slug: airflow-context
source_filename: airflow-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"airflow\": \"https://airflow.apache.org/schema/\",\n    \"schema\": {\n      \"@id\": \"airflow:schema\"\n    },\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"DagStatsCollectionResponse\": \"airflow:DagStatsCollectionResponse\",\n    \"ExternalLogUrlResponse\": \"airflow:ExternalLogUrlResponse\",\n    \"ConfigOption\": \"airflow:ConfigOption\",\n    \"BackfillPostBody\": \"airflow:BackfillPostBody\",\n    \"TaskDependencyCollectionResponse\": \"airflow:TaskDependencyCollectionResponse\",\n    \"XComResponseString\": \"airflow:XComResponseString\",\n    \"DAGWarningResponse\": \"airflow:DAGWarningResponse\",\n    \"LastAssetEventResponse\": \"airflow:LastAssetEventResponse\",\n    \"DAGWarningCollectionResponse\": \"airflow:DAGWarningCollectionResponse\",\n    \"MaterializeAssetBody\": \"airflow:MaterializeAssetBody\",\n    \"HITLDetailHistory\": \"airflow:HITLDetailHistory\",\n    \"DagTagResponse\": \"airflow:DagTagResponse\"\
  ,\n    \"ProviderResponse\": \"airflow:ProviderResponse\",\n    \"EventLogCollectionResponse\": \"airflow:EventLogCollectionResponse\",\n    \"EventLogResponse\": \"airflow:EventLogResponse\",\n    \"BulkDeleteAction_BulkTaskInstanceBody_\": \"airflow:BulkDeleteAction_BulkTaskInstanceBody_\",\n    \"BulkActionResponse\": \"airflow:BulkActionResponse\",\n    \"TriggerResponse\": \"airflow:TriggerResponse\",\n    \"DagRunAssetReference\": \"airflow:DagRunAssetReference\",\n    \"ConfigSection\": \"airflow:ConfigSection\",\n    \"DAGRunCollectionResponse\": \"airflow:DAGRunCollectionResponse\",\n    \"BulkBody_PoolBody_\": \"airflow:BulkBody_PoolBody_\",\n    \"CreateAssetEventsBody\": \"airflow:CreateAssetEventsBody\",\n    \"HITLDetailResponse\": \"airflow:HITLDetailResponse\",\n    \"BulkBody_BulkTaskInstanceBody_\": \"airflow:BulkBody_BulkTaskInstanceBody_\",\n    \"StructuredLogMessage\": \"airflow:StructuredLogMessage\",\n    \"ImportErrorCollectionResponse\": \"airflow:ImportErrorCollectionResponse\"\
  ,\n    \"ExternalViewResponse\": \"airflow:ExternalViewResponse\",\n    \"DagStatsStateResponse\": \"airflow:DagStatsStateResponse\",\n    \"BulkBody_VariableBody_\": \"airflow:BulkBody_VariableBody_\",\n    \"ConnectionCollectionResponse\": \"airflow:ConnectionCollectionResponse\",\n    \"BulkResponse\": \"airflow:BulkResponse\",\n    \"JobCollectionResponse\": \"airflow:JobCollectionResponse\",\n    \"Config\": \"airflow:Config\",\n    \"ConnectionBody\": \"airflow:ConnectionBody\",\n    \"VariableResponse\": \"airflow:VariableResponse\",\n    \"DAGTagCollectionResponse\": \"airflow:DAGTagCollectionResponse\",\n    \"BulkCreateAction_VariableBody_\": \"airflow:BulkCreateAction_VariableBody_\",\n    \"TriggerDAGRunPostBody\": \"airflow:TriggerDAGRunPostBody\",\n    \"TaskInstancesBatchBody\": \"airflow:TaskInstancesBatchBody\",\n    \"ExtraLinkCollectionResponse\": \"airflow:ExtraLinkCollectionResponse\",\n    \"TaskCollectionResponse\": \"airflow:TaskCollectionResponse\",\n    \"DAGRunResponse\"\
  : \"airflow:DAGRunResponse\",\n    \"BulkDeleteAction_VariableBody_\": \"airflow:BulkDeleteAction_VariableBody_\",\n    \"ReactAppResponse\": \"airflow:ReactAppResponse\",\n    \"QueuedEventCollectionResponse\": \"airflow:QueuedEventCollectionResponse\",\n    \"TriggererInfoResponse\": \"airflow:TriggererInfoResponse\",\n    \"VersionInfo\": \"airflow:VersionInfo\",\n    \"DryRunBackfillResponse\": \"airflow:DryRunBackfillResponse\",\n    \"PoolCollectionResponse\": \"airflow:PoolCollectionResponse\",\n    \"TaskInletAssetReference\": \"airflow:TaskInletAssetReference\",\n    \"TaskInstanceCollectionResponse\": \"airflow:TaskInstanceCollectionResponse\",\n    \"DagScheduleAssetReference\": \"airflow:DagScheduleAssetReference\",\n    \"UpdateHITLDetailPayload\": \"airflow:UpdateHITLDetailPayload\",\n    \"VariableBody\": \"airflow:VariableBody\",\n    \"DAGSourceResponse\": \"airflow:DAGSourceResponse\",\n    \"BackfillCollectionResponse\": \"airflow:BackfillCollectionResponse\",\n    \"\
  DAGRunPatchBody\": \"airflow:DAGRunPatchBody\",\n    \"TaskInstanceResponse\": \"airflow:TaskInstanceResponse\",\n    \"HITLDetail\": \"airflow:HITLDetail\",\n    \"XComResponseNative\": \"airflow:XComResponseNative\",\n    \"XComResponse\": \"airflow:XComResponse\",\n    \"XComUpdateBody\": \"airflow:XComUpdateBody\",\n    \"QueuedEventResponse\": \"airflow:QueuedEventResponse\",\n    \"AssetWatcherResponse\": \"airflow:AssetWatcherResponse\",\n    \"BulkUpdateAction_PoolBody_\": \"airflow:BulkUpdateAction_PoolBody_\",\n    \"ConnectionTestResponse\": \"airflow:ConnectionTestResponse\",\n    \"TaskOutletAssetReference\": \"airflow:TaskOutletAssetReference\",\n    \"PoolBody\": \"airflow:PoolBody\",\n    \"DagProcessorInfoResponse\": \"airflow:DagProcessorInfoResponse\",\n    \"XComCollectionResponse\": \"airflow:XComCollectionResponse\",\n    \"DagStatsResponse\": \"airflow:DagStatsResponse\",\n    \"FastAPIRootMiddlewareResponse\": \"airflow:FastAPIRootMiddlewareResponse\",\n    \"DAGVersionCollectionResponse\"\
  : \"airflow:DAGVersionCollectionResponse\",\n    \"AppBuilderViewResponse\": \"airflow:AppBuilderViewResponse\",\n    \"DAGPatchBody\": \"airflow:DAGPatchBody\",\n    \"BulkCreateAction_PoolBody_\": \"airflow:BulkCreateAction_PoolBody_\",\n    \"PluginResponse\": \"airflow:PluginResponse\",\n    \"TaskResponse\": \"airflow:TaskResponse\",\n    \"SchedulerInfoResponse\": \"airflow:SchedulerInfoResponse\",\n    \"ImportErrorResponse\": \"airflow:ImportErrorResponse\",\n    \"TaskInstancesLogResponse\": \"airflow:TaskInstancesLogResponse\",\n    \"HITLUser\": \"airflow:HITLUser\",\n    \"VariableCollectionResponse\": \"airflow:VariableCollectionResponse\",\n    \"TaskInstanceHistoryResponse\": \"airflow:TaskInstanceHistoryResponse\",\n    \"TimeDelta\": \"airflow:TimeDelta\",\n    \"PoolPatchBody\": \"airflow:PoolPatchBody\",\n    \"ClearTaskInstancesBody\": \"airflow:ClearTaskInstancesBody\",\n    \"BaseInfoResponse\": \"airflow:BaseInfoResponse\",\n    \"DAGCollectionResponse\": \"airflow:DAGCollectionResponse\"\
  ,\n    \"ProviderCollectionResponse\": \"airflow:ProviderCollectionResponse\",\n    \"JobResponse\": \"airflow:JobResponse\",\n    \"HTTPExceptionResponse\": \"airflow:HTTPExceptionResponse\",\n    \"BulkCreateAction_BulkTaskInstanceBody_\": \"airflow:BulkCreateAction_BulkTaskInstanceBody_\",\n    \"BulkBody_ConnectionBody_\": \"airflow:BulkBody_ConnectionBody_\",\n    \"XComCreateBody\": \"airflow:XComCreateBody\",\n    \"BulkUpdateAction_ConnectionBody_\": \"airflow:BulkUpdateAction_ConnectionBody_\",\n    \"PatchTaskInstanceBody\": \"airflow:PatchTaskInstanceBody\",\n    \"PluginCollectionResponse\": \"airflow:PluginCollectionResponse\",\n    \"HITLDetailCollection\": \"airflow:HITLDetailCollection\",\n    \"AssetAliasResponse\": \"airflow:AssetAliasResponse\",\n    \"AssetEventCollectionResponse\": \"airflow:AssetEventCollectionResponse\",\n    \"TaskDependencyResponse\": \"airflow:TaskDependencyResponse\",\n    \"PoolResponse\": \"airflow:PoolResponse\",\n    \"DAGDetailsResponse\"\
  : \"airflow:DAGDetailsResponse\",\n    \"BulkTaskInstanceBody\": \"airflow:BulkTaskInstanceBody\",\n    \"AssetEventResponse\": \"airflow:AssetEventResponse\",\n    \"DAGRunClearBody\": \"airflow:DAGRunClearBody\",\n    \"AssetCollectionResponse\": \"airflow:AssetCollectionResponse\",\n    \"BulkUpdateAction_VariableBody_\": \"airflow:BulkUpdateAction_VariableBody_\",\n    \"DAGRunsBatchBody\": \"airflow:DAGRunsBatchBody\",\n    \"AssetResponse\": \"airflow:AssetResponse\",\n    \"BackfillResponse\": \"airflow:BackfillResponse\",\n    \"BulkDeleteAction_PoolBody_\": \"airflow:BulkDeleteAction_PoolBody_\",\n    \"AppBuilderMenuItemResponse\": \"airflow:AppBuilderMenuItemResponse\",\n    \"BulkDeleteAction_ConnectionBody_\": \"airflow:BulkDeleteAction_ConnectionBody_\",\n    \"BulkUpdateAction_BulkTaskInstanceBody_\": \"airflow:BulkUpdateAction_BulkTaskInstanceBody_\",\n    \"FastAPIAppResponse\": \"airflow:FastAPIAppResponse\",\n    \"TaskInstanceHistoryCollectionResponse\": \"airflow:TaskInstanceHistoryCollectionResponse\"\
  ,\n    \"PluginImportErrorCollectionResponse\": \"airflow:PluginImportErrorCollectionResponse\",\n    \"AssetAliasCollectionResponse\": \"airflow:AssetAliasCollectionResponse\",\n    \"BulkCreateAction_ConnectionBody_\": \"airflow:BulkCreateAction_ConnectionBody_\",\n    \"DAGResponse\": \"airflow:DAGResponse\",\n    \"PluginImportErrorResponse\": \"airflow:PluginImportErrorResponse\",\n    \"ConnectionResponse\": \"airflow:ConnectionResponse\",\n    \"DryRunBackfillCollectionResponse\": \"airflow:DryRunBackfillCollectionResponse\",\n    \"DagVersionResponse\": \"airflow:DagVersionResponse\",\n    \"HealthInfoResponse\": \"airflow:HealthInfoResponse\",\n    \"dags\": {\n      \"@id\": \"airflow:dags\"\n    },\n    \"totalEntries\": {\n      \"@id\": \"airflow:total_entries\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"url\": {\n      \"@id\": \"schema:url\"\n    },\n    \"key\": {\n      \"@id\": \"airflow:key\"\n    },\n    \"value\": {\n      \"@id\": \"airflow:value\"\n    },\n\
  \    \"dagId\": {\n      \"@id\": \"airflow:dag_id\"\n    },\n    \"fromDate\": {\n      \"@id\": \"airflow:from_date\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"toDate\": {\n      \"@id\": \"airflow:to_date\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"runBackwards\": {\n      \"@id\": \"airflow:run_backwards\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"dagRunConf\": {\n      \"@id\": \"airflow:dag_run_conf\"\n    },\n    \"reprocessBehavior\": {\n      \"@id\": \"airflow:reprocess_behavior\"\n    },\n    \"maxActiveRuns\": {\n      \"@id\": \"airflow:max_active_runs\"\n    },\n    \"runOnLatestVersion\": {\n      \"@id\": \"airflow:run_on_latest_version\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"dependencies\": {\n      \"@id\": \"airflow:dependencies\"\n    },\n    \"timestamp\": {\n      \"@id\": \"airflow:timestamp\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"logicalDate\": {\n      \"@id\": \"airflow:logical_date\"\n    },\n    \"mapIndex\"\
  : {\n      \"@id\": \"airflow:map_index\"\n    },\n    \"taskId\": {\n      \"@id\": \"airflow:task_id\"\n    },\n    \"runId\": {\n      \"@id\": \"airflow:run_id\"\n    },\n    \"dagDisplayName\": {\n      \"@id\": \"airflow:dag_display_name\"\n    },\n    \"taskDisplayName\": {\n      \"@id\": \"airflow:task_display_name\"\n    },\n    \"runAfter\": {\n      \"@id\": \"airflow:run_after\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"warningType\": {\n      \"@id\": \"airflow:warning_type\"\n    },\n    \"message\": {\n      \"@id\": \"airflow:message\"\n    },\n    \"id\": {\n      \"@id\": \"airflow:id\"\n    },\n    \"dagWarnings\": {\n      \"@id\": \"airflow:dag_warnings\"\n    },\n    \"dagRunId\": {\n      \"@id\": \"airflow:dag_run_id\"\n    },\n    \"dataIntervalStart\": {\n      \"@id\": \"airflow:data_interval_start\"\n    },\n    \"dataIntervalEnd\": {\n      \"@id\": \"airflow:data_interval_end\"\n    },\n    \"conf\": {\n      \"@id\": \"airflow:conf\"\n    },\n \
  \   \"note\": {\n      \"@id\": \"airflow:note\"\n    },\n    \"partitionKey\": {\n      \"@id\": \"airflow:partition_key\"\n    },\n    \"options\": {\n      \"@id\": \"airflow:options\"\n    },\n    \"subject\": {\n      \"@id\": \"airflow:subject\"\n    },\n    \"body\": {\n      \"@id\": \"airflow:body\"\n    },\n    \"defaults\": {\n      \"@id\": \"airflow:defaults\"\n    },\n    \"multiple\": {\n      \"@id\": \"airflow:multiple\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"params\": {\n      \"@id\": \"airflow:params\"\n    },\n    \"assignedUsers\": {\n      \"@id\": \"airflow:assigned_users\"\n    },\n    \"createdAt\": {\n      \"@id\": \"airflow:created_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"respondedByUser\": {\n      \"@id\": \"airflow:responded_by_user\"\n    },\n    \"respondedAt\": {\n      \"@id\": \"airflow:responded_at\"\n    },\n    \"chosenOptions\": {\n      \"@id\": \"airflow:chosen_options\"\n    },\n    \"paramsInput\": {\n      \"@id\"\
  : \"airflow:params_input\"\n    },\n    \"responseReceived\": {\n      \"@id\": \"airflow:response_received\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"taskInstance\": {\n      \"@id\": \"airflow:task_instance\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\"\n    },\n    \"packageName\": {\n      \"@id\": \"airflow:package_name\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\"\n    },\n    \"version\": {\n      \"@id\": \"airflow:version\"\n    },\n    \"documentationUrl\": {\n      \"@id\": \"airflow:documentation_url\"\n    },\n    \"eventLogs\": {\n      \"@id\": \"airflow:event_logs\"\n    },\n    \"eventLogId\": {\n      \"@id\": \"airflow:event_log_id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"when\": {\n      \"@id\": \"airflow:when\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"tryNumber\": {\n      \"@id\": \"airflow:try_number\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"event\": {\n      \"@id\": \"airflow:event\"\
  \n    },\n    \"owner\": {\n      \"@id\": \"airflow:owner\"\n    },\n    \"extra\": {\n      \"@id\": \"airflow:extra\"\n    },\n    \"action\": {\n      \"@id\": \"airflow:action\"\n    },\n    \"entities\": {\n      \"@id\": \"airflow:entities\"\n    },\n    \"actionOnNonExistence\": {\n      \"@id\": \"airflow:action_on_non_existence\"\n    },\n    \"success\": {\n      \"@id\": \"airflow:success\"\n    },\n    \"errors\": {\n      \"@id\": \"airflow:errors\"\n    },\n    \"classpath\": {\n      \"@id\": \"airflow:classpath\"\n    },\n    \"kwargs\": {\n      \"@id\": \"airflow:kwargs\"\n    },\n    \"createdDate\": {\n      \"@id\": \"airflow:created_date\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"queue\": {\n      \"@id\": \"airflow:queue\"\n    },\n    \"triggererId\": {\n      \"@id\": \"airflow:triggerer_id\"\n    },\n    \"startDate\": {\n      \"@id\": \"airflow:start_date\"\n    },\n    \"endDate\": {\n      \"@id\": \"airflow:end_date\"\n    },\n    \"state\": {\n\
  \      \"@id\": \"airflow:state\"\n    },\n    \"dagRuns\": {\n      \"@id\": \"airflow:dag_runs\"\n    },\n    \"actions\": {\n      \"@id\": \"airflow:actions\"\n    },\n    \"assetId\": {\n      \"@id\": \"airflow:asset_id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"respondedBy\": {\n      \"@id\": \"airflow:responded_by\"\n    },\n    \"importErrors\": {\n      \"@id\": \"airflow:import_errors\"\n    },\n    \"icon\": {\n      \"@id\": \"airflow:icon\"\n    },\n    \"iconDarkMode\": {\n      \"@id\": \"airflow:icon_dark_mode\"\n    },\n    \"urlRoute\": {\n      \"@id\": \"airflow:url_route\"\n    },\n    \"category\": {\n      \"@id\": \"airflow:category\"\n    },\n    \"href\": {\n      \"@id\": \"airflow:href\"\n    },\n    \"destination\": {\n      \"@id\": \"airflow:destination\"\n    },\n    \"count\": {\n      \"@id\": \"airflow:count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"connections\": {\n      \"@id\": \"airflow:connections\"\n    },\n    \"create\":\
  \ {\n      \"@id\": \"airflow:create\"\n    },\n    \"update\": {\n      \"@id\": \"airflow:update\"\n    },\n    \"delete\": {\n      \"@id\": \"airflow:delete\"\n    },\n    \"jobs\": {\n      \"@id\": \"airflow:jobs\"\n    },\n    \"sections\": {\n      \"@id\": \"airflow:sections\"\n    },\n    \"connectionId\": {\n      \"@id\": \"airflow:connection_id\"\n    },\n    \"connType\": {\n      \"@id\": \"airflow:conn_type\"\n    },\n    \"host\": {\n      \"@id\": \"airflow:host\"\n    },\n    \"login\": {\n      \"@id\": \"airflow:login\"\n    },\n    \"port\": {\n      \"@id\": \"airflow:port\"\n    },\n    \"password\": {\n      \"@id\": \"airflow:password\"\n    },\n    \"teamName\": {\n      \"@id\": \"airflow:team_name\"\n    },\n    \"isEncrypted\": {\n      \"@id\": \"airflow:is_encrypted\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"tags\": {\n      \"@id\": \"airflow:tags\"\n    },\n    \"actionOnExistence\": {\n      \"@id\": \"airflow:action_on_existence\"\n    },\n\
  \    \"dagIds\": {\n      \"@id\": \"airflow:dag_ids\"\n    },\n    \"dagRunIds\": {\n      \"@id\": \"airflow:dag_run_ids\"\n    },\n    \"taskIds\": {\n      \"@id\": \"airflow:task_ids\"\n    },\n    \"runAfterGte\": {\n      \"@id\": \"airflow:run_after_gte\"\n    },\n    \"runAfterGt\": {\n      \"@id\": \"airflow:run_after_gt\"\n    },\n    \"runAfterLte\": {\n      \"@id\": \"airflow:run_after_lte\"\n    },\n    \"runAfterLt\": {\n      \"@id\": \"airflow:run_after_lt\"\n    },\n    \"logicalDateGte\": {\n      \"@id\": \"airflow:logical_date_gte\"\n    },\n    \"logicalDateGt\": {\n      \"@id\": \"airflow:logical_date_gt\"\n    },\n    \"logicalDateLte\": {\n      \"@id\": \"airflow:logical_date_lte\"\n    },\n    \"logicalDateLt\": {\n      \"@id\": \"airflow:logical_date_lt\"\n    },\n    \"startDateGte\": {\n      \"@id\": \"airflow:start_date_gte\"\n    },\n    \"startDateGt\": {\n      \"@id\": \"airflow:start_date_gt\"\n    },\n    \"startDateLte\": {\n      \"@id\": \"\
  airflow:start_date_lte\"\n    },\n    \"startDateLt\": {\n      \"@id\": \"airflow:start_date_lt\"\n    },\n    \"endDateGte\": {\n      \"@id\": \"airflow:end_date_gte\"\n    },\n    \"endDateGt\": {\n      \"@id\": \"airflow:end_date_gt\"\n    },\n    \"endDateLte\": {\n      \"@id\": \"airflow:end_date_lte\"\n    },\n    \"endDateLt\": {\n      \"@id\": \"airflow:end_date_lt\"\n    },\n    \"durationGte\": {\n      \"@id\": \"airflow:duration_gte\"\n    },\n    \"durationGt\": {\n      \"@id\": \"airflow:duration_gt\"\n    },\n    \"durationLte\": {\n      \"@id\": \"airflow:duration_lte\"\n    },\n    \"durationLt\": {\n      \"@id\": \"airflow:duration_lt\"\n    },\n    \"pool\": {\n      \"@id\": \"airflow:pool\"\n    },\n    \"executor\": {\n      \"@id\": \"airflow:executor\"\n    },\n    \"pageOffset\": {\n      \"@id\": \"airflow:page_offset\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"pageLimit\": {\n      \"@id\": \"airflow:page_limit\",\n      \"@type\": \"xsd:integer\"\
  \n    },\n    \"orderBy\": {\n      \"@id\": \"airflow:order_by\"\n    },\n    \"extraLinks\": {\n      \"@id\": \"airflow:extra_links\"\n    },\n    \"tasks\": {\n      \"@id\": \"airflow:tasks\"\n    },\n    \"queuedAt\": {\n      \"@id\": \"airflow:queued_at\"\n    },\n    \"duration\": {\n      \"@id\": \"airflow:duration\"\n    },\n    \"lastSchedulingDecision\": {\n      \"@id\": \"airflow:last_scheduling_decision\"\n    },\n    \"runType\": {\n      \"@id\": \"airflow:run_type\"\n    },\n    \"triggeredBy\": {\n      \"@id\": \"airflow:triggered_by\"\n    },\n    \"triggeringUserName\": {\n      \"@id\": \"airflow:triggering_user_name\"\n    },\n    \"dagVersions\": {\n      \"@id\": \"airflow:dag_versions\"\n    },\n    \"bundleVersion\": {\n      \"@id\": \"airflow:bundle_version\"\n    },\n    \"bundleUrl\": {\n      \"@id\": \"airflow:bundle_url\"\n    },\n    \"queuedEvents\": {\n      \"@id\": \"airflow:queued_events\"\n    },\n    \"status\": {\n      \"@id\": \"airflow:status\"\
  \n    },\n    \"latestTriggererHeartbeat\": {\n      \"@id\": \"airflow:latest_triggerer_heartbeat\"\n    },\n    \"gitVersion\": {\n      \"@id\": \"airflow:git_version\"\n    },\n    \"partitionDate\": {\n      \"@id\": \"airflow:partition_date\"\n    },\n    \"pools\": {\n      \"@id\": \"airflow:pools\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"airflow:updated_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"taskInstances\": {\n      \"@id\": \"airflow:task_instances\"\n    },\n    \"nextCursor\": {\n      \"@id\": \"airflow:next_cursor\"\n    },\n    \"previousCursor\": {\n      \"@id\": \"airflow:previous_cursor\"\n    },\n    \"content\": {\n      \"@id\": \"airflow:content\"\n    },\n    \"versionNumber\": {\n      \"@id\": \"airflow:version_number\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"backfills\": {\n      \"@id\": \"airflow:backfills\"\n    },\n    \"maxTries\": {\n      \"@id\": \"airflow:max_tries\",\n      \"@type\": \"xsd:integer\"\n    },\n   \
  \ \"hostname\": {\n      \"@id\": \"airflow:hostname\"\n    },\n    \"unixname\": {\n      \"@id\": \"airflow:unixname\"\n    },\n    \"poolSlots\": {\n      \"@id\": \"airflow:pool_slots\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"priorityWeight\": {\n      \"@id\": \"airflow:priority_weight\"\n    },\n    \"operator\": {\n      \"@id\": \"airflow:operator\"\n    },\n    \"operatorName\": {\n      \"@id\": \"airflow:operator_name\"\n    },\n    \"queuedWhen\": {\n      \"@id\": \"airflow:queued_when\"\n    },\n    \"scheduledWhen\": {\n      \"@id\": \"airflow:scheduled_when\"\n    },\n    \"pid\": {\n      \"@id\": \"airflow:pid\"\n    },\n    \"executorConfig\": {\n      \"@id\": \"airflow:executor_config\"\n    },\n    \"renderedMapIndex\": {\n      \"@id\": \"airflow:rendered_map_index\"\n    },\n    \"renderedFields\": {\n      \"@id\": \"airflow:rendered_fields\"\n    },\n    \"trigger\": {\n      \"@id\": \"airflow:trigger\"\n    },\n    \"triggererJob\": {\n      \"@id\"\
  : \"airflow:triggerer_job\"\n    },\n    \"dagVersion\": {\n      \"@id\": \"airflow:dag_version\"\n    },\n    \"triggerId\": {\n      \"@id\": \"airflow:trigger_id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"updateMask\": {\n      \"@id\": \"airflow:update_mask\"\n    },\n    \"slots\": {\n      \"@id\": \"airflow:slots\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"includeDeferred\": {\n      \"@id\": \"airflow:include_deferred\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"latestDagProcessorHeartbeat\": {\n      \"@id\": \"airflow:latest_dag_processor_heartbeat\"\n    },\n    \"xcomEntries\": {\n      \"@id\": \"airflow:xcom_entries\"\n    },\n    \"stats\": {\n      \"@id\": \"airflow:stats\"\n    },\n    \"middleware\": {\n      \"@id\": \"airflow:middleware\"\n    },\n    \"view\": {\n      \"@id\": \"airflow:view\"\n    },\n    \"label\": {\n      \"@id\": \"airflow:label\"\n    },\n    \"isPaused\": {\n      \"@id\": \"airflow:is_paused\",\n      \"@type\": \"\
  xsd:boolean\"\n    },\n    \"macros\": {\n      \"@id\": \"airflow:macros\"\n    },\n    \"flaskBlueprints\": {\n      \"@id\": \"airflow:flask_blueprints\"\n    },\n    \"fastapiApps\": {\n      \"@id\": \"airflow:fastapi_apps\"\n    },\n    \"fastapiRootMiddlewares\": {\n      \"@id\": \"airflow:fastapi_root_middlewares\"\n    },\n    \"externalViews\": {\n      \"@id\": \"airflow:external_views\"\n    },\n    \"reactApps\": {\n      \"@id\": \"airflow:react_apps\"\n    },\n    \"appbuilderViews\": {\n      \"@id\": \"airflow:appbuilder_views\"\n    },\n    \"appbuilderMenuItems\": {\n      \"@id\": \"airflow:appbuilder_menu_items\"\n    },\n    \"globalOperatorExtraLinks\": {\n      \"@id\": \"airflow:global_operator_extra_links\"\n    },\n    \"operatorExtraLinks\": {\n      \"@id\": \"airflow:operator_extra_links\"\n    },\n    \"source\": {\n      \"@id\": \"airflow:source\"\n    },\n    \"listeners\": {\n      \"@id\": \"airflow:listeners\"\n    },\n    \"timetables\": {\n     \
  \ \"@id\": \"airflow:timetables\"\n    },\n    \"triggerRule\": {\n      \"@id\": \"airflow:trigger_rule\"\n    },\n    \"dependsOnPast\": {\n      \"@id\": \"airflow:depends_on_past\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"waitForDownstream\": {\n      \"@id\": \"airflow:wait_for_downstream\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"retries\": {\n      \"@id\": \"airflow:retries\"\n    },\n    \"executionTimeout\": {\n      \"@id\": \"airflow:execution_timeout\"\n    },\n    \"retryDelay\": {\n      \"@id\": \"airflow:retry_delay\"\n    },\n    \"retryExponentialBackoff\": {\n      \"@id\": \"airflow:retry_exponential_backoff\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"weightRule\": {\n      \"@id\": \"airflow:weight_rule\"\n    },\n    \"uiColor\": {\n      \"@id\": \"airflow:ui_color\"\n    },\n    \"uiFgcolor\": {\n      \"@id\": \"airflow:ui_fgcolor\"\n    },\n    \"templateFields\": {\n      \"@id\": \"airflow:template_fields\"\n    },\n    \"downstreamTaskIds\"\
  : {\n      \"@id\": \"airflow:downstream_task_ids\"\n    },\n    \"docMd\": {\n      \"@id\": \"airflow:doc_md\"\n    },\n    \"classRef\": {\n      \"@id\": \"airflow:class_ref\"\n    },\n    \"isMapped\": {\n      \"@id\": \"airflow:is_mapped\"\n    },\n    \"latestSchedulerHeartbeat\": {\n      \"@id\": \"airflow:latest_scheduler_heartbeat\"\n    },\n    \"importErrorId\": {\n      \"@id\": \"airflow:import_error_id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"filename\": {\n      \"@id\": \"airflow:filename\"\n    },\n    \"bundleName\": {\n      \"@id\": \"airflow:bundle_name\"\n    },\n    \"stackTrace\": {\n      \"@id\": \"airflow:stack_trace\"\n    },\n    \"continuationToken\": {\n      \"@id\": \"airflow:continuation_token\"\n    },\n    \"variables\": {\n      \"@id\": \"airflow:variables\"\n    },\n    \"Type\": {\n      \"@id\": \"airflow:__type\"\n    },\n    \"days\": {\n      \"@id\": \"airflow:days\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"seconds\":\
  \ {\n      \"@id\": \"airflow:seconds\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"microseconds\": {\n      \"@id\": \"airflow:microseconds\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"dryRun\": {\n      \"@id\": \"airflow:dry_run\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"onlyFailed\": {\n      \"@id\": \"airflow:only_failed\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"onlyRunning\": {\n      \"@id\": \"airflow:only_running\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"resetDagRuns\": {\n      \"@id\": \"airflow:reset_dag_runs\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"includeUpstream\": {\n      \"@id\": \"airflow:include_upstream\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"includeDownstream\": {\n      \"@id\": \"airflow:include_downstream\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"includeFuture\": {\n      \"@id\": \"airflow:include_future\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"includePast\": {\n      \"@id\"\
  : \"airflow:include_past\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"preventRunningTask\": {\n      \"@id\": \"airflow:prevent_running_task\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"providers\": {\n      \"@id\": \"airflow:providers\"\n    },\n    \"jobType\": {\n      \"@id\": \"airflow:job_type\"\n    },\n    \"latestHeartbeat\": {\n      \"@id\": \"airflow:latest_heartbeat\"\n    },\n    \"executorClass\": {\n      \"@id\": \"airflow:executor_class\"\n    },\n    \"detail\": {\n      \"@id\": \"airflow:detail\"\n    },\n    \"newState\": {\n      \"@id\": \"airflow:new_state\"\n    },\n    \"plugins\": {\n      \"@id\": \"airflow:plugins\"\n    },\n    \"hitlDetails\": {\n      \"@id\": \"airflow:hitl_details\"\n    },\n    \"group\": {\n      \"@id\": \"airflow:group\"\n    },\n    \"assetEvents\": {\n      \"@id\": \"airflow:asset_events\"\n    },\n    \"reason\": {\n      \"@id\": \"airflow:reason\"\n    },\n    \"occupiedSlots\": {\n      \"@id\": \"airflow:occupied_slots\"\
  ,\n      \"@type\": \"xsd:integer\"\n    },\n    \"runningSlots\": {\n      \"@id\": \"airflow:running_slots\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"queuedSlots\": {\n      \"@id\": \"airflow:queued_slots\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"scheduledSlots\": {\n      \"@id\": \"airflow:scheduled_slots\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"openSlots\": {\n      \"@id\": \"airflow:open_slots\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"deferredSlots\": {\n      \"@id\": \"airflow:deferred_slots\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"isStale\": {\n      \"@id\": \"airflow:is_stale\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"lastParsedTime\": {\n      \"@id\": \"airflow:last_parsed_time\"\n    },\n    \"lastParseDuration\": {\n      \"@id\": \"airflow:last_parse_duration\"\n    },\n    \"lastExpired\": {\n      \"@id\": \"airflow:last_expired\"\n    },\n    \"relativeFileloc\": {\n      \"@id\": \"airflow:relative_fileloc\"\
  \n    },\n    \"fileloc\": {\n      \"@id\": \"airflow:fileloc\"\n    },\n    \"timetableSummary\": {\n      \"@id\": \"airflow:timetable_summary\"\n    },\n    \"timetableDescription\": {\n      \"@id\": \"airflow:timetable_description\"\n    },\n    \"timetablePartitioned\": {\n      \"@id\": \"airflow:timetable_partitioned\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"timetablePeriodic\": {\n      \"@id\": \"airflow:timetable_periodic\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"maxActiveTasks\": {\n      \"@id\": \"airflow:max_active_tasks\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"maxConsecutiveFailedDagRuns\": {\n      \"@id\": \"airflow:max_consecutive_failed_dag_runs\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"hasTaskConcurrencyLimits\": {\n      \"@id\": \"airflow:has_task_concurrency_limits\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"hasImportErrors\": {\n      \"@id\": \"airflow:has_import_errors\",\n      \"@type\": \"xsd:boolean\"\n  \
  \  },\n    \"nextDagrunLogicalDate\": {\n      \"@id\": \"airflow:next_dagrun_logical_date\"\n    },\n    \"nextDagrunDataIntervalStart\": {\n      \"@id\": \"airflow:next_dagrun_data_interval_start\"\n    },\n    \"nextDagrunDataIntervalEnd\": {\n      \"@id\": \"airflow:next_dagrun_data_interval_end\"\n    },\n    \"nextDagrunRunAfter\": {\n      \"@id\": \"airflow:next_dagrun_run_after\"\n    },\n    \"allowedRunTypes\": {\n      \"@id\": \"airflow:allowed_run_types\"\n    },\n    \"owners\": {\n      \"@id\": \"airflow:owners\"\n    },\n    \"catchup\": {\n      \"@id\": \"airflow:catchup\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"dagRunTimeout\": {\n      \"@id\": \"airflow:dag_run_timeout\"\n    },\n    \"assetExpression\": {\n      \"@id\": \"airflow:asset_expression\"\n    },\n    \"isPausedUponCreation\": {\n      \"@id\": \"airflow:is_paused_upon_creation\"\n    },\n    \"renderTemplateAsNativeObj\": {\n      \"@id\": \"airflow:render_template_as_native_obj\",\n    \
  \  \"@type\": \"xsd:boolean\"\n    },\n    \"templateSearchPath\": {\n      \"@id\": \"airflow:template_search_path\"\n    },\n    \"timezone\": {\n      \"@id\": \"airflow:timezone\"\n    },\n    \"lastParsed\": {\n      \"@id\": \"airflow:last_parsed\"\n    },\n    \"defaultArgs\": {\n      \"@id\": \"airflow:default_args\"\n    },\n    \"ownerLinks\": {\n      \"@id\": \"airflow:owner_links\"\n    },\n    \"isFavorite\": {\n      \"@id\": \"airflow:is_favorite\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"activeRunsCount\": {\n      \"@id\": \"airflow:active_runs_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"isBackfillable\": {\n      \"@id\": \"airflow:is_backfillable\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"fileToken\": {\n      \"@id\": \"airflow:file_token\"\n    },\n    \"concurrency\": {\n      \"@id\": \"airflow:concurrency\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"latestDagVersion\": {\n      \"@id\": \"airflow:latest_dag_version\"\n  \
  \  },\n    \"uri\": {\n      \"@id\": \"airflow:uri\"\n    },\n    \"sourceTaskId\": {\n      \"@id\": \"airflow:source_task_id\"\n    },\n    \"sourceDagId\": {\n      \"@id\": \"airflow:source_dag_id\"\n    },\n    \"sourceRunId\": {\n      \"@id\": \"airflow:source_run_id\"\n    },\n    \"sourceMapIndex\": {\n      \"@id\": \"airflow:source_map_index\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"createdDagruns\": {\n      \"@id\": \"airflow:created_dagruns\"\n    },\n    \"assets\": {\n      \"@id\": \"airflow:assets\"\n    },\n    \"states\": {\n      \"@id\": \"airflow:states\"\n    },\n    \"confContains\": {\n      \"@id\": \"airflow:conf_contains\"\n    },\n    \"scheduledDags\": {\n      \"@id\": \"airflow:scheduled_dags\"\n    },\n    \"producingTasks\": {\n      \"@id\": \"airflow:producing_tasks\"\n    },\n    \"consumingTasks\": {\n      \"@id\": \"airflow:consuming_tasks\"\n    },\n    \"aliases\": {\n      \"@id\": \"airflow:aliases\"\n    },\n    \"watchers\": {\n\
  \      \"@id\": \"airflow:watchers\"\n    },\n    \"lastAssetEvent\": {\n      \"@id\": \"airflow:last_asset_event\"\n    },\n    \"completedAt\": {\n      \"@id\": \"airflow:completed_at\"\n    },\n    \"app\": {\n      \"@id\": \"airflow:app\"\n    },\n    \"urlPrefix\": {\n      \"@id\": \"airflow:url_prefix\"\n    },\n    \"assetAliases\": {\n      \"@id\": \"airflow:asset_aliases\"\n    },\n    \"error\": {\n      \"@id\": \"airflow:error\"\n    },\n    \"metadatabase\": {\n      \"@id\": \"airflow:metadatabase\"\n    },\n    \"scheduler\": {\n      \"@id\": \"airflow:scheduler\"\n    },\n    \"triggerer\": {\n      \"@id\": \"airflow:triggerer\"\n    },\n    \"dagProcessor\": {\n      \"@id\": \"airflow:dag_processor\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/airflow/refs/heads/main/json-ld/airflow-context.jsonld
tags:
- Workflow Orchestration
- Data Pipeline
- Open Source
- Apache
- DAG
- Scheduling
- ETL
- Data Engineering
- JSON-LD
- Linked Data
- Semantic Web
---
