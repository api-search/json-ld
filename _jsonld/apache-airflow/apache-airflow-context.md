---
api_specs:
- filename: apache-airflow-openapi.yaml
  format: yaml
  label: Apache Airflow REST API
  slug: apache-airflow-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/apache-airflow/refs/heads/main/openapi/apache-airflow-openapi.yaml
class_count: 88
classes:
- Resource
- name
- ConfigOption
- DatasetEvent
- TaskState
- ImportError
- Provider
- description
- version
- Variable
- EventLog
- DAGDetail
- UserCollection
- EventLogCollection
- SLAMiss
- RelativeDelta
- CronExpression
- UpdateTaskInstancesState
- XComCollectionItem
- XCom
- DAGCollection
- BasicDAGRun
- ConnectionCollection
- Tag
- XComCollection
- Job
- ProviderCollection
- Connection
- ClearTaskInstances
- VariableCollectionItem
- DagScheduleDatasetReference
- Trigger
- ScheduleInterval
- DagWarning
- ConfigSection
- VersionInfo
- Task
- Pool
- ActionCollection
- ListDagRunsForm
- ActionResource
- HealthStatus
- ExtraLink
- ExtraLinkCollection
- PoolCollection
- RoleCollection
- ConnectionTest
- ConnectionCollectionItem
- SetDagRunNote
- User
- DAGRunCollection
- SetTaskInstanceNote
- ListTaskInstanceForm
- SchedulerStatus
- VariableCollection
- Color
- UserCollectionItem
- email
- Dataset
- TaskInstanceCollection
- TriggerRule
- Action
- HealthInfo
- CollectionInfo
- Role
- DAG
- MetadatabaseStatus
- ClearDagRun
- TaskInstance
- DatasetEventCollection
- TimeDelta
- DagWarningCollection
- PluginCollectionItem
- TaskOutletDatasetReference
- ClassReference
- DatasetCollection
- DagState
- UpdateTaskInstance
- Config
- ImportErrorCollection
- WeightRule
- UpdateDagRunState
- Timezone
- DAGRun
- PluginCollection
- TaskInstanceReference
- TaskInstanceReferenceCollection
- TaskCollection
context_file: json-ld/apache-airflow-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apache-airflow/refs/heads/main/json-ld/apache-airflow-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apache Airflow from Apache Airflow.
layout: jsonld
name: Apache Airflow Context
namespaces:
- prefix: airflow
  uri: https://airflow.apache.org/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: key
  type: string
- container: ''
  name: value
  type: string
- container: set
  name: createdDagruns
  type: string
- container: ''
  name: datasetId
  type: integer
- container: ''
  name: datasetUri
  type: string
- container: ''
  name: extra
  type: reference
- container: ''
  name: sourceDagId
  type: string
- container: ''
  name: sourceMapIndex
  type: integer
- container: ''
  name: sourceRunId
  type: string
- container: ''
  name: sourceTaskId
  type: string
- container: ''
  name: timestamp
  type: string
- container: ''
  name: filename
  type: string
- container: ''
  name: importErrorId
  type: integer
- container: ''
  name: stackTrace
  type: string
- container: ''
  name: packageName
  type: string
- container: ''
  name: dagId
  type: string
- container: ''
  name: event
  type: string
- container: ''
  name: eventLogId
  type: integer
- container: ''
  name: executionDate
  type: dateTime
- container: ''
  name: owner
  type: string
- container: ''
  name: taskId
  type: string
- container: ''
  name: when
  type: dateTime
- container: ''
  name: emailSent
  type: boolean
- container: ''
  name: notificationSent
  type: boolean
- container: ''
  name: Type
  type: string
- container: ''
  name: day
  type: integer
- container: ''
  name: days
  type: integer
- container: ''
  name: hour
  type: integer
- container: ''
  name: hours
  type: integer
- container: ''
  name: leapdays
  type: integer
- container: ''
  name: microsecond
  type: integer
- container: ''
  name: microseconds
  type: integer
- container: ''
  name: minute
  type: integer
- container: ''
  name: minutes
  type: integer
- container: ''
  name: month
  type: integer
- container: ''
  name: months
  type: integer
- container: ''
  name: second
  type: integer
- container: ''
  name: seconds
  type: integer
- container: ''
  name: year
  type: integer
- container: ''
  name: years
  type: integer
- container: ''
  name: dagRunId
  type: string
- container: ''
  name: dryRun
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
  name: includeUpstream
  type: boolean
- container: ''
  name: newState
  type: string
- container: ''
  name: dataIntervalEnd
  type: dateTime
- container: ''
  name: dataIntervalStart
  type: dateTime
- container: ''
  name: endDate
  type: dateTime
- container: ''
  name: logicalDate
  type: dateTime
- container: ''
  name: runId
  type: string
- container: ''
  name: startDate
  type: dateTime
- container: ''
  name: state
  type: string
- container: ''
  name: executorClass
  type: string
- container: ''
  name: hostname
  type: string
- container: ''
  name: id
  type: integer
- container: ''
  name: jobType
  type: string
- container: ''
  name: latestHeartbeat
  type: string
- container: ''
  name: unixname
  type: string
- container: set
  name: providers
  type: string
- container: ''
  name: includeParentdag
  type: boolean
- container: ''
  name: includeSubdags
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
- container: set
  name: taskIds
  type: string
- container: ''
  name: createdAt
  type: string
- container: ''
  name: updatedAt
  type: string
- container: ''
  name: classpath
  type: string
- container: ''
  name: createdDate
  type: string
- container: ''
  name: kwargs
  type: string
- container: ''
  name: triggererId
  type: integer
- container: ''
  name: message
  type: string
- container: ''
  name: warningType
  type: string
- container: set
  name: options
  type: string
- container: ''
  name: gitVersion
  type: string
- container: ''
  name: classRef
  type: string
- container: ''
  name: dependsOnPast
  type: boolean
- container: set
  name: downstreamTaskIds
  type: string
- container: ''
  name: executionTimeout
  type: string
- container: set
  name: extraLinks
  type: reference
- container: ''
  name: isMapped
  type: boolean
- container: ''
  name: pool
  type: string
- container: ''
  name: poolSlots
  type: decimal
- container: ''
  name: priorityWeight
  type: decimal
- container: ''
  name: queue
  type: string
- container: ''
  name: retries
  type: decimal
- container: ''
  name: retryDelay
  type: string
- container: ''
  name: retryExponentialBackoff
  type: boolean
- container: ''
  name: subDag
  type: string
- container: set
  name: templateFields
  type: string
- container: ''
  name: triggerRule
  type: string
- container: ''
  name: uiColor
  type: string
- container: ''
  name: uiFgcolor
  type: string
- container: ''
  name: waitForDownstream
  type: boolean
- container: ''
  name: weightRule
  type: string
- container: ''
  name: occupiedSlots
  type: integer
- container: ''
  name: openSlots
  type: integer
- container: ''
  name: queuedSlots
  type: integer
- container: ''
  name: slots
  type: integer
- container: ''
  name: usedSlots
  type: integer
- container: set
  name: dagIds
  type: string
- container: ''
  name: endDateGte
  type: dateTime
- container: ''
  name: endDateLte
  type: dateTime
- container: ''
  name: executionDateGte
  type: dateTime
- container: ''
  name: executionDateLte
  type: dateTime
- container: ''
  name: orderBy
  type: string
- container: ''
  name: pageLimit
  type: integer
- container: ''
  name: pageOffset
  type: integer
- container: ''
  name: startDateGte
  type: dateTime
- container: ''
  name: startDateLte
  type: dateTime
- container: set
  name: states
  type: string
- container: ''
  name: action
  type: reference
- container: ''
  name: resource
  type: reference
- container: ''
  name: href
  type: string
- container: ''
  name: status
  type: boolean
- container: ''
  name: connType
  type: string
- container: ''
  name: connectionId
  type: string
- container: ''
  name: host
  type: string
- container: ''
  name: login
  type: string
- container: ''
  name: port
  type: integer
- container: ''
  name: note
  type: string
- container: ''
  name: durationGte
  type: decimal
- container: ''
  name: durationLte
  type: decimal
- container: ''
  name: latestSchedulerHeartbeat
  type: string
- container: ''
  name: active
  type: boolean
- container: ''
  name: changedOn
  type: string
- container: ''
  name: createdOn
  type: string
- container: ''
  name: failedLoginCount
  type: integer
- container: ''
  name: firstName
  type: string
- container: ''
  name: lastLogin
  type: string
- container: ''
  name: lastName
  type: string
- container: ''
  name: loginCount
  type: integer
- container: set
  name: roles
  type: reference
- container: ''
  name: username
  type: string
- container: set
  name: consumingDags
  type: string
- container: set
  name: producingTasks
  type: string
- container: ''
  name: uri
  type: string
- container: ''
  name: metadatabase
  type: string
- container: ''
  name: scheduler
  type: string
- container: ''
  name: totalEntries
  type: integer
- container: set
  name: actions
  type: string
- container: ''
  name: defaultView
  type: string
- container: ''
  name: fileToken
  type: string
- container: ''
  name: fileloc
  type: string
- container: ''
  name: hasImportErrors
  type: boolean
- container: ''
  name: hasTaskConcurrencyLimits
  type: boolean
- container: ''
  name: isActive
  type: boolean
- container: ''
  name: isPaused
  type: boolean
- container: ''
  name: isSubdag
  type: boolean
- container: ''
  name: lastExpired
  type: dateTime
- container: ''
  name: lastParsedTime
  type: dateTime
- container: ''
  name: lastPickled
  type: dateTime
- container: ''
  name: maxActiveRuns
  type: integer
- container: ''
  name: maxActiveTasks
  type: integer
- container: ''
  name: nextDagrun
  type: dateTime
- container: ''
  name: nextDagrunCreateAfter
  type: dateTime
- container: ''
  name: nextDagrunDataIntervalEnd
  type: dateTime
- container: ''
  name: nextDagrunDataIntervalStart
  type: dateTime
- container: set
  name: owners
  type: string
- container: ''
  name: pickleId
  type: string
- container: ''
  name: rootDagId
  type: string
- container: ''
  name: scheduleInterval
  type: string
- container: ''
  name: schedulerLock
  type: boolean
- container: set
  name: tags
  type: string
- container: ''
  name: timetableDescription
  type: string
- container: ''
  name: duration
  type: decimal
- container: ''
  name: executorConfig
  type: string
- container: ''
  name: mapIndex
  type: integer
- container: ''
  name: maxTries
  type: integer
- container: ''
  name: operator
  type: string
- container: ''
  name: pid
  type: integer
- container: ''
  name: queuedWhen
  type: string
- container: ''
  name: renderedFields
  type: reference
- container: ''
  name: slaMiss
  type: string
- container: ''
  name: trigger
  type: string
- container: ''
  name: triggererJob
  type: string
- container: ''
  name: tryNumber
  type: integer
- container: set
  name: appbuilderMenuItems
  type: reference
- container: set
  name: appbuilderViews
  type: reference
- container: set
  name: executors
  type: string
- container: set
  name: flaskBlueprints
  type: reference
- container: set
  name: globalOperatorExtraLinks
  type: reference
- container: set
  name: hooks
  type: string
- container: set
  name: macros
  type: reference
- container: set
  name: operatorExtraLinks
  type: reference
- container: ''
  name: source
  type: string
- container: ''
  name: className
  type: string
- container: ''
  name: modulePath
  type: string
- container: set
  name: sections
  type: string
- container: ''
  name: conf
  type: reference
- container: ''
  name: externalTrigger
  type: boolean
- container: ''
  name: lastSchedulingDecision
  type: dateTime
- container: ''
  name: runType
  type: string
- container: set
  name: taskInstances
  type: string
- container: set
  name: tasks
  type: string
property_count: 197
provider_name: Apache Airflow
provider_slug: apache-airflow
slug: apache-airflow-context
source_filename: apache-airflow-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"airflow\": \"https://airflow.apache.org/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Resource\": \"airflow:Resource\",\n    \"name\": \"schema:name\",\n    \"ConfigOption\": \"airflow:ConfigOption\",\n    \"key\": {\n      \"@id\": \"airflow:key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"airflow:value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DatasetEvent\": \"airflow:DatasetEvent\",\n    \"createdDagruns\": {\n      \"@id\": \"airflow:created_dagruns\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"datasetId\": {\n      \"@id\": \"airflow:dataset_id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"datasetUri\": {\n      \"@id\": \"airflow:dataset_uri\",\n      \"@type\": \"xsd:string\"\n    },\n    \"extra\": {\n      \"@id\"\
  : \"airflow:extra\",\n      \"@type\": \"@id\"\n    },\n    \"sourceDagId\": {\n      \"@id\": \"airflow:source_dag_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sourceMapIndex\": {\n      \"@id\": \"airflow:source_map_index\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"sourceRunId\": {\n      \"@id\": \"airflow:source_run_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sourceTaskId\": {\n      \"@id\": \"airflow:source_task_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timestamp\": {\n      \"@id\": \"airflow:timestamp\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TaskState\": \"airflow:TaskState\",\n    \"ImportError\": \"airflow:ImportError\",\n    \"filename\": {\n      \"@id\": \"airflow:filename\",\n      \"@type\": \"xsd:string\"\n    },\n    \"importErrorId\": {\n      \"@id\": \"airflow:import_error_id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"stackTrace\": {\n      \"@id\": \"airflow:stack_trace\",\n      \"@type\": \"xsd:string\"\n\
  \    },\n    \"Provider\": \"airflow:Provider\",\n    \"description\": \"schema:description\",\n    \"packageName\": {\n      \"@id\": \"airflow:package_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"version\": \"schema:version\",\n    \"Variable\": \"airflow:Variable\",\n    \"EventLog\": \"airflow:EventLog\",\n    \"dagId\": {\n      \"@id\": \"airflow:dag_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"event\": {\n      \"@id\": \"airflow:event\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eventLogId\": {\n      \"@id\": \"airflow:event_log_id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"executionDate\": {\n      \"@id\": \"airflow:execution_date\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"owner\": {\n      \"@id\": \"airflow:owner\",\n      \"@type\": \"xsd:string\"\n    },\n    \"taskId\": {\n      \"@id\": \"airflow:task_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"when\": {\n      \"@id\": \"airflow:when\",\n      \"@type\": \"xsd:dateTime\"\
  \n    },\n    \"DAGDetail\": \"airflow:DAGDetail\",\n    \"UserCollection\": \"airflow:UserCollection\",\n    \"EventLogCollection\": \"airflow:EventLogCollection\",\n    \"SLAMiss\": \"airflow:SLAMiss\",\n    \"emailSent\": {\n      \"@id\": \"airflow:email_sent\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"notificationSent\": {\n      \"@id\": \"airflow:notification_sent\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"RelativeDelta\": \"airflow:RelativeDelta\",\n    \"Type\": {\n      \"@id\": \"airflow:__type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"day\": {\n      \"@id\": \"airflow:day\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"days\": {\n      \"@id\": \"airflow:days\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"hour\": {\n      \"@id\": \"airflow:hour\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"hours\": {\n      \"@id\": \"airflow:hours\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"leapdays\": {\n      \"@id\": \"airflow:leapdays\"\
  ,\n      \"@type\": \"xsd:integer\"\n    },\n    \"microsecond\": {\n      \"@id\": \"airflow:microsecond\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"microseconds\": {\n      \"@id\": \"airflow:microseconds\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"minute\": {\n      \"@id\": \"airflow:minute\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"minutes\": {\n      \"@id\": \"airflow:minutes\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"month\": {\n      \"@id\": \"airflow:month\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"months\": {\n      \"@id\": \"airflow:months\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"second\": {\n      \"@id\": \"airflow:second\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"seconds\": {\n      \"@id\": \"airflow:seconds\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"year\": {\n      \"@id\": \"airflow:year\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"years\": {\n      \"@id\": \"airflow:years\",\n      \"\
  @type\": \"xsd:integer\"\n    },\n    \"CronExpression\": \"airflow:CronExpression\",\n    \"UpdateTaskInstancesState\": \"airflow:UpdateTaskInstancesState\",\n    \"dagRunId\": {\n      \"@id\": \"airflow:dag_run_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dryRun\": {\n      \"@id\": \"airflow:dry_run\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"includeDownstream\": {\n      \"@id\": \"airflow:include_downstream\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"includeFuture\": {\n      \"@id\": \"airflow:include_future\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"includePast\": {\n      \"@id\": \"airflow:include_past\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"includeUpstream\": {\n      \"@id\": \"airflow:include_upstream\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"newState\": {\n      \"@id\": \"airflow:new_state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"XComCollectionItem\": \"airflow:XComCollectionItem\",\n    \"XCom\": \"airflow:XCom\"\
  ,\n    \"DAGCollection\": \"airflow:DAGCollection\",\n    \"BasicDAGRun\": \"airflow:BasicDAGRun\",\n    \"dataIntervalEnd\": {\n      \"@id\": \"airflow:data_interval_end\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"dataIntervalStart\": {\n      \"@id\": \"airflow:data_interval_start\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"endDate\": {\n      \"@id\": \"airflow:end_date\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"logicalDate\": {\n      \"@id\": \"airflow:logical_date\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"runId\": {\n      \"@id\": \"airflow:run_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startDate\": {\n      \"@id\": \"airflow:start_date\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"state\": {\n      \"@id\": \"airflow:state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ConnectionCollection\": \"airflow:ConnectionCollection\",\n    \"Tag\": \"airflow:Tag\",\n    \"XComCollection\": \"airflow:XComCollection\",\n    \"\
  Job\": \"airflow:Job\",\n    \"executorClass\": {\n      \"@id\": \"airflow:executor_class\",\n      \"@type\": \"xsd:string\"\n    },\n    \"hostname\": {\n      \"@id\": \"airflow:hostname\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"airflow:id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"jobType\": {\n      \"@id\": \"airflow:job_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"latestHeartbeat\": {\n      \"@id\": \"airflow:latest_heartbeat\",\n      \"@type\": \"xsd:string\"\n    },\n    \"unixname\": {\n      \"@id\": \"airflow:unixname\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ProviderCollection\": \"airflow:ProviderCollection\",\n    \"providers\": {\n      \"@id\": \"airflow:providers\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Connection\": \"airflow:Connection\",\n    \"ClearTaskInstances\": \"airflow:ClearTaskInstances\",\n    \"includeParentdag\": {\n      \"@id\": \"airflow:include_parentdag\"\
  ,\n      \"@type\": \"xsd:boolean\"\n    },\n    \"includeSubdags\": {\n      \"@id\": \"airflow:include_subdags\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"onlyFailed\": {\n      \"@id\": \"airflow:only_failed\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"onlyRunning\": {\n      \"@id\": \"airflow:only_running\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"resetDagRuns\": {\n      \"@id\": \"airflow:reset_dag_runs\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"taskIds\": {\n      \"@id\": \"airflow:task_ids\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"VariableCollectionItem\": \"airflow:VariableCollectionItem\",\n    \"DagScheduleDatasetReference\": \"airflow:DagScheduleDatasetReference\",\n    \"createdAt\": {\n      \"@id\": \"airflow:created_at\",\n      \"@type\": \"xsd:string\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"airflow:updated_at\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Trigger\": \"airflow:Trigger\"\
  ,\n    \"classpath\": {\n      \"@id\": \"airflow:classpath\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdDate\": {\n      \"@id\": \"airflow:created_date\",\n      \"@type\": \"xsd:string\"\n    },\n    \"kwargs\": {\n      \"@id\": \"airflow:kwargs\",\n      \"@type\": \"xsd:string\"\n    },\n    \"triggererId\": {\n      \"@id\": \"airflow:triggerer_id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"ScheduleInterval\": \"airflow:ScheduleInterval\",\n    \"DagWarning\": \"airflow:DagWarning\",\n    \"message\": {\n      \"@id\": \"airflow:message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"warningType\": {\n      \"@id\": \"airflow:warning_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ConfigSection\": \"airflow:ConfigSection\",\n    \"options\": {\n      \"@id\": \"airflow:options\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"VersionInfo\": \"airflow:VersionInfo\",\n    \"gitVersion\": {\n      \"@id\": \"airflow:git_version\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"Task\": \"airflow:Task\",\n    \"classRef\": {\n      \"@id\": \"airflow:class_ref\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dependsOnPast\": {\n      \"@id\": \"airflow:depends_on_past\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"downstreamTaskIds\": {\n      \"@id\": \"airflow:downstream_task_ids\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"executionTimeout\": {\n      \"@id\": \"airflow:execution_timeout\",\n      \"@type\": \"xsd:string\"\n    },\n    \"extraLinks\": {\n      \"@id\": \"airflow:extra_links\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"isMapped\": {\n      \"@id\": \"airflow:is_mapped\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"pool\": {\n      \"@id\": \"airflow:pool\",\n      \"@type\": \"xsd:string\"\n    },\n    \"poolSlots\": {\n      \"@id\": \"airflow:pool_slots\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"priorityWeight\"\
  : {\n      \"@id\": \"airflow:priority_weight\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"queue\": {\n      \"@id\": \"airflow:queue\",\n      \"@type\": \"xsd:string\"\n    },\n    \"retries\": {\n      \"@id\": \"airflow:retries\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"retryDelay\": {\n      \"@id\": \"airflow:retry_delay\",\n      \"@type\": \"xsd:string\"\n    },\n    \"retryExponentialBackoff\": {\n      \"@id\": \"airflow:retry_exponential_backoff\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"subDag\": {\n      \"@id\": \"airflow:sub_dag\",\n      \"@type\": \"xsd:string\"\n    },\n    \"templateFields\": {\n      \"@id\": \"airflow:template_fields\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"triggerRule\": {\n      \"@id\": \"airflow:trigger_rule\",\n      \"@type\": \"xsd:string\"\n    },\n    \"uiColor\": {\n      \"@id\": \"airflow:ui_color\",\n      \"@type\": \"xsd:string\"\n    },\n    \"uiFgcolor\": {\n     \
  \ \"@id\": \"airflow:ui_fgcolor\",\n      \"@type\": \"xsd:string\"\n    },\n    \"waitForDownstream\": {\n      \"@id\": \"airflow:wait_for_downstream\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"weightRule\": {\n      \"@id\": \"airflow:weight_rule\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Pool\": \"airflow:Pool\",\n    \"occupiedSlots\": {\n      \"@id\": \"airflow:occupied_slots\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"openSlots\": {\n      \"@id\": \"airflow:open_slots\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"queuedSlots\": {\n      \"@id\": \"airflow:queued_slots\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"slots\": {\n      \"@id\": \"airflow:slots\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"usedSlots\": {\n      \"@id\": \"airflow:used_slots\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"ActionCollection\": \"airflow:ActionCollection\",\n    \"ListDagRunsForm\": \"airflow:ListDagRunsForm\",\n    \"dagIds\": {\n      \"@id\"\
  : \"airflow:dag_ids\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"endDateGte\": {\n      \"@id\": \"airflow:end_date_gte\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"endDateLte\": {\n      \"@id\": \"airflow:end_date_lte\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"executionDateGte\": {\n      \"@id\": \"airflow:execution_date_gte\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"executionDateLte\": {\n      \"@id\": \"airflow:execution_date_lte\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"orderBy\": {\n      \"@id\": \"airflow:order_by\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pageLimit\": {\n      \"@id\": \"airflow:page_limit\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"pageOffset\": {\n      \"@id\": \"airflow:page_offset\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"startDateGte\": {\n      \"@id\": \"airflow:start_date_gte\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"startDateLte\": {\n\
  \      \"@id\": \"airflow:start_date_lte\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"states\": {\n      \"@id\": \"airflow:states\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ActionResource\": \"airflow:ActionResource\",\n    \"action\": {\n      \"@id\": \"airflow:action\",\n      \"@type\": \"@id\"\n    },\n    \"resource\": {\n      \"@id\": \"airflow:resource\",\n      \"@type\": \"@id\"\n    },\n    \"HealthStatus\": \"airflow:HealthStatus\",\n    \"ExtraLink\": \"airflow:ExtraLink\",\n    \"href\": {\n      \"@id\": \"airflow:href\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ExtraLinkCollection\": \"airflow:ExtraLinkCollection\",\n    \"PoolCollection\": \"airflow:PoolCollection\",\n    \"RoleCollection\": \"airflow:RoleCollection\",\n    \"ConnectionTest\": \"airflow:ConnectionTest\",\n    \"status\": {\n      \"@id\": \"airflow:status\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"ConnectionCollectionItem\": \"airflow:ConnectionCollectionItem\"\
  ,\n    \"connType\": {\n      \"@id\": \"airflow:conn_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"connectionId\": {\n      \"@id\": \"airflow:connection_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"host\": {\n      \"@id\": \"airflow:host\",\n      \"@type\": \"xsd:string\"\n    },\n    \"login\": {\n      \"@id\": \"airflow:login\",\n      \"@type\": \"xsd:string\"\n    },\n    \"port\": {\n      \"@id\": \"airflow:port\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"SetDagRunNote\": \"airflow:SetDagRunNote\",\n    \"note\": {\n      \"@id\": \"airflow:note\",\n      \"@type\": \"xsd:string\"\n    },\n    \"User\": \"airflow:User\",\n    \"DAGRunCollection\": \"airflow:DAGRunCollection\",\n    \"SetTaskInstanceNote\": \"airflow:SetTaskInstanceNote\",\n    \"ListTaskInstanceForm\": \"airflow:ListTaskInstanceForm\",\n    \"durationGte\": {\n      \"@id\": \"airflow:duration_gte\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"durationLte\": {\n      \"@id\":\
  \ \"airflow:duration_lte\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"SchedulerStatus\": \"airflow:SchedulerStatus\",\n    \"latestSchedulerHeartbeat\": {\n      \"@id\": \"airflow:latest_scheduler_heartbeat\",\n      \"@type\": \"xsd:string\"\n    },\n    \"VariableCollection\": \"airflow:VariableCollection\",\n    \"Color\": \"airflow:Color\",\n    \"UserCollectionItem\": \"airflow:UserCollectionItem\",\n    \"active\": {\n      \"@id\": \"airflow:active\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"changedOn\": {\n      \"@id\": \"airflow:changed_on\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdOn\": {\n      \"@id\": \"airflow:created_on\",\n      \"@type\": \"xsd:string\"\n    },\n    \"email\": \"schema:email\",\n    \"failedLoginCount\": {\n      \"@id\": \"airflow:failed_login_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"firstName\": {\n      \"@id\": \"airflow:first_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastLogin\": {\n \
  \     \"@id\": \"airflow:last_login\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastName\": {\n      \"@id\": \"airflow:last_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"loginCount\": {\n      \"@id\": \"airflow:login_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"roles\": {\n      \"@id\": \"airflow:roles\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"username\": {\n      \"@id\": \"airflow:username\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Dataset\": \"airflow:Dataset\",\n    \"consumingDags\": {\n      \"@id\": \"airflow:consuming_dags\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"producingTasks\": {\n      \"@id\": \"airflow:producing_tasks\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"uri\": {\n      \"@id\": \"airflow:uri\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TaskInstanceCollection\": \"airflow:TaskInstanceCollection\",\n   \
  \ \"TriggerRule\": \"airflow:TriggerRule\",\n    \"Action\": \"airflow:Action\",\n    \"HealthInfo\": \"airflow:HealthInfo\",\n    \"metadatabase\": {\n      \"@id\": \"airflow:metadatabase\",\n      \"@type\": \"xsd:string\"\n    },\n    \"scheduler\": {\n      \"@id\": \"airflow:scheduler\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CollectionInfo\": \"airflow:CollectionInfo\",\n    \"totalEntries\": {\n      \"@id\": \"airflow:total_entries\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"Role\": \"airflow:Role\",\n    \"actions\": {\n      \"@id\": \"airflow:actions\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DAG\": \"airflow:DAG\",\n    \"defaultView\": {\n      \"@id\": \"airflow:default_view\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fileToken\": {\n      \"@id\": \"airflow:file_token\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fileloc\": {\n      \"@id\": \"airflow:fileloc\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"hasImportErrors\": {\n      \"@id\": \"airflow:has_import_errors\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"hasTaskConcurrencyLimits\": {\n      \"@id\": \"airflow:has_task_concurrency_limits\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isActive\": {\n      \"@id\": \"airflow:is_active\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isPaused\": {\n      \"@id\": \"airflow:is_paused\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isSubdag\": {\n      \"@id\": \"airflow:is_subdag\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"lastExpired\": {\n      \"@id\": \"airflow:last_expired\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"lastParsedTime\": {\n      \"@id\": \"airflow:last_parsed_time\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"lastPickled\": {\n      \"@id\": \"airflow:last_pickled\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"maxActiveRuns\": {\n      \"@id\": \"airflow:max_active_runs\",\n      \"@type\": \"xsd:integer\"\n\
  \    },\n    \"maxActiveTasks\": {\n      \"@id\": \"airflow:max_active_tasks\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"nextDagrun\": {\n      \"@id\": \"airflow:next_dagrun\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"nextDagrunCreateAfter\": {\n      \"@id\": \"airflow:next_dagrun_create_after\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"nextDagrunDataIntervalEnd\": {\n      \"@id\": \"airflow:next_dagrun_data_interval_end\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"nextDagrunDataIntervalStart\": {\n      \"@id\": \"airflow:next_dagrun_data_interval_start\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"owners\": {\n      \"@id\": \"airflow:owners\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pickleId\": {\n      \"@id\": \"airflow:pickle_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rootDagId\": {\n      \"@id\": \"airflow:root_dag_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"scheduleInterval\"\
  : {\n      \"@id\": \"airflow:schedule_interval\",\n      \"@type\": \"xsd:string\"\n    },\n    \"schedulerLock\": {\n      \"@id\": \"airflow:scheduler_lock\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"tags\": {\n      \"@id\": \"airflow:tags\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timetableDescription\": {\n      \"@id\": \"airflow:timetable_description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MetadatabaseStatus\": \"airflow:MetadatabaseStatus\",\n    \"ClearDagRun\": \"airflow:ClearDagRun\",\n    \"TaskInstance\": \"airflow:TaskInstance\",\n    \"duration\": {\n      \"@id\": \"airflow:duration\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"executorConfig\": {\n      \"@id\": \"airflow:executor_config\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mapIndex\": {\n      \"@id\": \"airflow:map_index\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"maxTries\": {\n      \"@id\": \"airflow:max_tries\",\n      \"@type\"\
  : \"xsd:integer\"\n    },\n    \"operator\": {\n      \"@id\": \"airflow:operator\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pid\": {\n      \"@id\": \"airflow:pid\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"queuedWhen\": {\n      \"@id\": \"airflow:queued_when\",\n      \"@type\": \"xsd:string\"\n    },\n    \"renderedFields\": {\n      \"@id\": \"airflow:rendered_fields\",\n      \"@type\": \"@id\"\n    },\n    \"slaMiss\": {\n      \"@id\": \"airflow:sla_miss\",\n      \"@type\": \"xsd:string\"\n    },\n    \"trigger\": {\n      \"@id\": \"airflow:trigger\",\n      \"@type\": \"xsd:string\"\n    },\n    \"triggererJob\": {\n      \"@id\": \"airflow:triggerer_job\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tryNumber\": {\n      \"@id\": \"airflow:try_number\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"DatasetEventCollection\": \"airflow:DatasetEventCollection\",\n    \"TimeDelta\": \"airflow:TimeDelta\",\n    \"DagWarningCollection\": \"airflow:DagWarningCollection\"\
  ,\n    \"PluginCollectionItem\": \"airflow:PluginCollectionItem\",\n    \"appbuilderMenuItems\": {\n      \"@id\": \"airflow:appbuilder_menu_items\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"appbuilderViews\": {\n      \"@id\": \"airflow:appbuilder_views\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"executors\": {\n      \"@id\": \"airflow:executors\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"flaskBlueprints\": {\n      \"@id\": \"airflow:flask_blueprints\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"globalOperatorExtraLinks\": {\n      \"@id\": \"airflow:global_operator_extra_links\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"hooks\": {\n      \"@id\": \"airflow:hooks\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"macros\": {\n      \"@id\": \"airflow:macros\",\n      \"@container\":\
  \ \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"operatorExtraLinks\": {\n      \"@id\": \"airflow:operator_extra_links\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"source\": {\n      \"@id\": \"airflow:source\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TaskOutletDatasetReference\": \"airflow:TaskOutletDatasetReference\",\n    \"ClassReference\": \"airflow:ClassReference\",\n    \"className\": {\n      \"@id\": \"airflow:class_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"modulePath\": {\n      \"@id\": \"airflow:module_path\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DatasetCollection\": \"airflow:DatasetCollection\",\n    \"DagState\": \"airflow:DagState\",\n    \"UpdateTaskInstance\": \"airflow:UpdateTaskInstance\",\n    \"Config\": \"airflow:Config\",\n    \"sections\": {\n      \"@id\": \"airflow:sections\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ImportErrorCollection\": \"airflow:ImportErrorCollection\"\
  ,\n    \"WeightRule\": \"airflow:WeightRule\",\n    \"UpdateDagRunState\": \"airflow:UpdateDagRunState\",\n    \"Timezone\": \"airflow:Timezone\",\n    \"DAGRun\": \"airflow:DAGRun\",\n    \"conf\": {\n      \"@id\": \"airflow:conf\",\n      \"@type\": \"@id\"\n    },\n    \"externalTrigger\": {\n      \"@id\": \"airflow:external_trigger\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"lastSchedulingDecision\": {\n      \"@id\": \"airflow:last_scheduling_decision\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"runType\": {\n      \"@id\": \"airflow:run_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PluginCollection\": \"airflow:PluginCollection\",\n    \"TaskInstanceReference\": \"airflow:TaskInstanceReference\",\n    \"TaskInstanceReferenceCollection\": \"airflow:TaskInstanceReferenceCollection\",\n    \"taskInstances\": {\n      \"@id\": \"airflow:task_instances\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TaskCollection\": \"airflow:TaskCollection\"\
  ,\n    \"tasks\": {\n      \"@id\": \"airflow:tasks\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/apache-airflow/refs/heads/main/json-ld/apache-airflow-context.jsonld
tags:
- Apache
- DAG
- Data Pipeline
- ETL
- Open Source
- Orchestration
- Python
- Scheduling
- Workflow
- JSON-LD
- Linked Data
- Semantic Web
---
