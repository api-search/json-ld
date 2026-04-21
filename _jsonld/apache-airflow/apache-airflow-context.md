---
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
