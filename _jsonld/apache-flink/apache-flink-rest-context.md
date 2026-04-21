---
class_count: 52
classes:
- AggregatedMetricsResponseBody
- AggregatedTaskDetailsInfo
- AggregationMode
- ApplicationStatus
- AsynchronousOperationInfo
- AsynchronousOperationResult
- CheckpointAlignment
- CheckpointAlignmentSummary
- CheckpointConfigInfo
- CheckpointDuration
- CheckpointDurationSummary
- CheckpointInfo
- CheckpointStatistics
- CheckpointStatisticsSummary
- CheckpointStatsStatus
- CheckpointTriggerRequestBody
- CheckpointType
- CheckpointingStatistics
- ClusterDataSetEntry
- ClusterDataSetListResponseBody
- ClusterOverviewWithVersion
- CompletedCheckpointStatistics
- CompletedSubtaskCheckpointStatistics
- ConfigurationInfoEntry
- ConfigurationInfo
- Counts
- DashboardConfiguration
- EnvironmentInfo
- ExceptionInfo
- ExecutionConfigInfo
- ExecutionState
- ExternalizedCheckpointInfo
- FailedCheckpointStatistics
- FailureLabel
- Features
- GarbageCollectorInfo
- name
- HardwareDescription
- Id
- IntermediateDataSetID
- IOMetricsInfo
- JarEntryInfo
- description
- JarFileInfo
- JarListInfo
- JarPlanRequestBody
- JarRunRequestBody
- JarRunResponseBody
- JarUploadResponseBody
- JobAccumulator
- JobAccumulatorsInfo
- JobClientHeartbeatRequestBody
context_file: json-ld/apache-flink-rest-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apache-flink/refs/heads/main/json-ld/apache-flink-rest-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apache Flink Rest from Apache Flink.
layout: jsonld
name: Apache Flink Rest Context
namespaces:
- prefix: flink
  uri: https://flink.apache.org/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: metrics
  type: string
- container: ''
  name: status-duration
  type: string
- container: ''
  name: failure-cause
  type: string
- container: ''
  name: operation
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: buffered
  type: integer
- container: ''
  name: duration
  type: integer
- container: ''
  name: persisted
  type: integer
- container: ''
  name: processed
  type: integer
- container: ''
  name: aligned_checkpoint_timeout
  type: integer
- container: ''
  name: changelog_periodic_materialization_interval
  type: integer
- container: ''
  name: changelog_storage
  type: string
- container: ''
  name: checkpoint_storage
  type: string
- container: ''
  name: checkpoints_after_tasks_finish
  type: boolean
- container: ''
  name: externalization
  type: string
- container: ''
  name: interval
  type: integer
- container: ''
  name: max_concurrent
  type: integer
- container: ''
  name: min_pause
  type: integer
- container: ''
  name: mode
  type: string
- container: ''
  name: state_backend
  type: string
- container: ''
  name: state_changelog_enabled
  type: boolean
- container: ''
  name: timeout
  type: integer
- container: ''
  name: tolerable_failed_checkpoints
  type: integer
- container: ''
  name: unaligned_checkpoints
  type: boolean
- container: ''
  name: async
  type: integer
- container: ''
  name: sync
  type: integer
- container: ''
  name: checkpointId
  type: integer
- container: ''
  name: failureCause
  type: string
- container: ''
  name: alignment_buffered
  type: integer
- container: ''
  name: checkpoint_type
  type: string
- container: ''
  name: checkpointed_size
  type: integer
- container: ''
  name: className
  type: string
- container: ''
  name: end_to_end_duration
  type: integer
- container: ''
  name: id
  type: integer
- container: ''
  name: is_savepoint
  type: boolean
- container: ''
  name: latest_ack_timestamp
  type: integer
- container: ''
  name: num_acknowledged_subtasks
  type: integer
- container: ''
  name: num_subtasks
  type: integer
- container: ''
  name: persisted_data
  type: integer
- container: ''
  name: processed_data
  type: integer
- container: ''
  name: savepointFormat
  type: string
- container: ''
  name: state_size
  type: integer
- container: ''
  name: tasks
  type: string
- container: ''
  name: trigger_timestamp
  type: integer
- container: ''
  name: checkpointType
  type: string
- container: ''
  name: triggerId
  type: string
- container: ''
  name: counts
  type: string
- container: set
  name: history
  type: string
- container: ''
  name: latest
  type: string
- container: ''
  name: summary
  type: string
- container: ''
  name: isComplete
  type: boolean
- container: set
  name: dataSets
  type: string
- container: ''
  name: flink-commit
  type: string
- container: ''
  name: flink-version
  type: string
- container: ''
  name: jobs-cancelled
  type: integer
- container: ''
  name: jobs-failed
  type: integer
- container: ''
  name: jobs-finished
  type: integer
- container: ''
  name: jobs-running
  type: integer
- container: ''
  name: slots-available
  type: integer
- container: ''
  name: slots-free-and-blocked
  type: integer
- container: ''
  name: slots-total
  type: integer
- container: ''
  name: taskmanagers
  type: integer
- container: ''
  name: taskmanagers-blocked
  type: integer
- container: ''
  name: key
  type: string
- container: ''
  name: value
  type: string
- container: ''
  name: completed
  type: integer
- container: ''
  name: failed
  type: integer
- container: ''
  name: in_progress
  type: integer
- container: ''
  name: restored
  type: integer
- container: ''
  name: total
  type: integer
- container: ''
  name: features
  type: string
- container: ''
  name: flink-revision
  type: string
- container: ''
  name: refresh-interval
  type: integer
- container: ''
  name: timezone-name
  type: string
- container: ''
  name: timezone-offset
  type: integer
- container: set
  name: classpath
  type: string
- container: ''
  name: jvm
  type: string
- container: ''
  name: endpoint
  type: string
- container: ''
  name: exceptionName
  type: string
- container: ''
  name: failureLabels
  type: string
- container: ''
  name: stacktrace
  type: string
- container: ''
  name: taskManagerId
  type: string
- container: ''
  name: taskName
  type: string
- container: ''
  name: timestamp
  type: integer
- container: ''
  name: job-parallelism
  type: integer
- container: ''
  name: object-reuse-mode
  type: boolean
- container: ''
  name: restart-strategy
  type: string
- container: ''
  name: user-config
  type: string
- container: ''
  name: delete_on_cancellation
  type: boolean
- container: ''
  name: enabled
  type: boolean
- container: ''
  name: web-cancel
  type: boolean
- container: ''
  name: web-history
  type: boolean
- container: ''
  name: web-rescale
  type: boolean
- container: ''
  name: web-submit
  type: boolean
- container: ''
  name: count
  type: integer
- container: ''
  name: time
  type: integer
- container: ''
  name: cpuCores
  type: integer
- container: ''
  name: freeMemory
  type: integer
- container: ''
  name: managedMemory
  type: integer
- container: ''
  name: physicalMemory
  type: integer
- container: ''
  name: accumulated-backpressured-time
  type: integer
- container: ''
  name: accumulated-busy-time
  type: integer
- container: ''
  name: accumulated-idle-time
  type: integer
- container: ''
  name: read-bytes
  type: integer
- container: ''
  name: read-bytes-complete
  type: boolean
- container: ''
  name: read-records
  type: integer
- container: ''
  name: read-records-complete
  type: boolean
- container: ''
  name: write-bytes
  type: integer
- container: ''
  name: write-bytes-complete
  type: boolean
- container: ''
  name: write-records
  type: integer
- container: ''
  name: write-records-complete
  type: boolean
- container: set
  name: entry
  type: string
- container: ''
  name: uploaded
  type: integer
- container: ''
  name: address
  type: string
- container: set
  name: files
  type: string
- container: ''
  name: entryClass
  type: string
- container: ''
  name: flinkConfiguration
  type: string
- container: ''
  name: jobId
  type: string
- container: ''
  name: parallelism
  type: integer
- container: set
  name: programArgsList
  type: string
- container: ''
  name: allowNonRestoredState
  type: boolean
- container: ''
  name: claimMode
  type: string
- container: ''
  name: restoreMode
  type: string
- container: ''
  name: savepointPath
  type: string
- container: ''
  name: jobid
  type: string
- container: ''
  name: filename
  type: string
- container: set
  name: job-accumulators
  type: string
- container: ''
  name: serialized-user-task-accumulators
  type: string
- container: set
  name: user-task-accumulators
  type: string
- container: ''
  name: expiredTimestamp
  type: integer
property_count: 130
provider_name: Apache Flink
provider_slug: apache-flink
slug: apache-flink-rest-context
tags:
- Apache
- Batch Processing
- Big Data
- Open Source
- Real-Time Analytics
- Stateful Computing
- Stream Processing
- JSON-LD
- Linked Data
- Semantic Web
---
