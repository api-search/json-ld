---
api_specs:
- filename: apache-flink-rest-openapi-original.yml
  format: yaml
  label: Apache Flink REST API
  slug: apache-flink-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/apache-flink/refs/heads/main/openapi/apache-flink-rest-openapi-original.yml
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
source_filename: apache-flink-rest-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"flink\": \"https://flink.apache.org/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AggregatedMetricsResponseBody\": \"flink:AggregatedMetricsResponseBody\",\n    \"AggregatedTaskDetailsInfo\": \"flink:AggregatedTaskDetailsInfo\",\n    \"metrics\": {\n      \"@id\": \"flink:metrics\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status-duration\": {\n      \"@id\": \"flink:status-duration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AggregationMode\": \"flink:AggregationMode\",\n    \"ApplicationStatus\": \"flink:ApplicationStatus\",\n    \"AsynchronousOperationInfo\": \"flink:AsynchronousOperationInfo\",\n    \"failure-cause\": {\n      \"@id\": \"flink:failure-cause\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AsynchronousOperationResult\": \"flink:AsynchronousOperationResult\",\n    \"operation\"\
  : {\n      \"@id\": \"flink:operation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"flink:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CheckpointAlignment\": \"flink:CheckpointAlignment\",\n    \"buffered\": {\n      \"@id\": \"flink:buffered\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"duration\": {\n      \"@id\": \"flink:duration\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"persisted\": {\n      \"@id\": \"flink:persisted\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"processed\": {\n      \"@id\": \"flink:processed\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"CheckpointAlignmentSummary\": \"flink:CheckpointAlignmentSummary\",\n    \"CheckpointConfigInfo\": \"flink:CheckpointConfigInfo\",\n    \"aligned_checkpoint_timeout\": {\n      \"@id\": \"flink:aligned_checkpoint_timeout\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"changelog_periodic_materialization_interval\": {\n      \"@id\": \"flink:changelog_periodic_materialization_interval\"\
  ,\n      \"@type\": \"xsd:integer\"\n    },\n    \"changelog_storage\": {\n      \"@id\": \"flink:changelog_storage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"checkpoint_storage\": {\n      \"@id\": \"flink:checkpoint_storage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"checkpoints_after_tasks_finish\": {\n      \"@id\": \"flink:checkpoints_after_tasks_finish\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"externalization\": {\n      \"@id\": \"flink:externalization\",\n      \"@type\": \"xsd:string\"\n    },\n    \"interval\": {\n      \"@id\": \"flink:interval\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"max_concurrent\": {\n      \"@id\": \"flink:max_concurrent\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"min_pause\": {\n      \"@id\": \"flink:min_pause\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"mode\": {\n      \"@id\": \"flink:mode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"state_backend\": {\n      \"@id\": \"flink:state_backend\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"state_changelog_enabled\": {\n      \"@id\": \"flink:state_changelog_enabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"timeout\": {\n      \"@id\": \"flink:timeout\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"tolerable_failed_checkpoints\": {\n      \"@id\": \"flink:tolerable_failed_checkpoints\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"unaligned_checkpoints\": {\n      \"@id\": \"flink:unaligned_checkpoints\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"CheckpointDuration\": \"flink:CheckpointDuration\",\n    \"async\": {\n      \"@id\": \"flink:async\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"sync\": {\n      \"@id\": \"flink:sync\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"CheckpointDurationSummary\": \"flink:CheckpointDurationSummary\",\n    \"CheckpointInfo\": \"flink:CheckpointInfo\",\n    \"checkpointId\": {\n      \"@id\": \"flink:checkpointId\",\n      \"@type\": \"xsd:integer\"\n\
  \    },\n    \"failureCause\": {\n      \"@id\": \"flink:failureCause\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CheckpointStatistics\": \"flink:CheckpointStatistics\",\n    \"alignment_buffered\": {\n      \"@id\": \"flink:alignment_buffered\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"checkpoint_type\": {\n      \"@id\": \"flink:checkpoint_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"checkpointed_size\": {\n      \"@id\": \"flink:checkpointed_size\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"className\": {\n      \"@id\": \"flink:className\",\n      \"@type\": \"xsd:string\"\n    },\n    \"end_to_end_duration\": {\n      \"@id\": \"flink:end_to_end_duration\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"id\": {\n      \"@id\": \"flink:id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"is_savepoint\": {\n      \"@id\": \"flink:is_savepoint\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"latest_ack_timestamp\": {\n      \"@id\": \"flink:latest_ack_timestamp\"\
  ,\n      \"@type\": \"xsd:integer\"\n    },\n    \"num_acknowledged_subtasks\": {\n      \"@id\": \"flink:num_acknowledged_subtasks\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"num_subtasks\": {\n      \"@id\": \"flink:num_subtasks\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"persisted_data\": {\n      \"@id\": \"flink:persisted_data\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"processed_data\": {\n      \"@id\": \"flink:processed_data\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"savepointFormat\": {\n      \"@id\": \"flink:savepointFormat\",\n      \"@type\": \"xsd:string\"\n    },\n    \"state_size\": {\n      \"@id\": \"flink:state_size\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"tasks\": {\n      \"@id\": \"flink:tasks\",\n      \"@type\": \"xsd:string\"\n    },\n    \"trigger_timestamp\": {\n      \"@id\": \"flink:trigger_timestamp\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"CheckpointStatisticsSummary\": \"flink:CheckpointStatisticsSummary\"\
  ,\n    \"CheckpointStatsStatus\": \"flink:CheckpointStatsStatus\",\n    \"CheckpointTriggerRequestBody\": \"flink:CheckpointTriggerRequestBody\",\n    \"checkpointType\": {\n      \"@id\": \"flink:checkpointType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"triggerId\": {\n      \"@id\": \"flink:triggerId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CheckpointType\": \"flink:CheckpointType\",\n    \"CheckpointingStatistics\": \"flink:CheckpointingStatistics\",\n    \"counts\": {\n      \"@id\": \"flink:counts\",\n      \"@type\": \"xsd:string\"\n    },\n    \"history\": {\n      \"@id\": \"flink:history\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"latest\": {\n      \"@id\": \"flink:latest\",\n      \"@type\": \"xsd:string\"\n    },\n    \"summary\": {\n      \"@id\": \"flink:summary\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ClusterDataSetEntry\": \"flink:ClusterDataSetEntry\",\n    \"isComplete\": {\n      \"@id\": \"flink:isComplete\"\
  ,\n      \"@type\": \"xsd:boolean\"\n    },\n    \"ClusterDataSetListResponseBody\": \"flink:ClusterDataSetListResponseBody\",\n    \"dataSets\": {\n      \"@id\": \"flink:dataSets\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ClusterOverviewWithVersion\": \"flink:ClusterOverviewWithVersion\",\n    \"flink-commit\": {\n      \"@id\": \"flink:flink-commit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"flink-version\": {\n      \"@id\": \"flink:flink-version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"jobs-cancelled\": {\n      \"@id\": \"flink:jobs-cancelled\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"jobs-failed\": {\n      \"@id\": \"flink:jobs-failed\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"jobs-finished\": {\n      \"@id\": \"flink:jobs-finished\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"jobs-running\": {\n      \"@id\": \"flink:jobs-running\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"slots-available\"\
  : {\n      \"@id\": \"flink:slots-available\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"slots-free-and-blocked\": {\n      \"@id\": \"flink:slots-free-and-blocked\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"slots-total\": {\n      \"@id\": \"flink:slots-total\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"taskmanagers\": {\n      \"@id\": \"flink:taskmanagers\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"taskmanagers-blocked\": {\n      \"@id\": \"flink:taskmanagers-blocked\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"CompletedCheckpointStatistics\": \"flink:CompletedCheckpointStatistics\",\n    \"CompletedSubtaskCheckpointStatistics\": \"flink:CompletedSubtaskCheckpointStatistics\",\n    \"ConfigurationInfoEntry\": \"flink:ConfigurationInfoEntry\",\n    \"key\": {\n      \"@id\": \"flink:key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"flink:value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ConfigurationInfo\"\
  : \"flink:ConfigurationInfo\",\n    \"Counts\": \"flink:Counts\",\n    \"completed\": {\n      \"@id\": \"flink:completed\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"failed\": {\n      \"@id\": \"flink:failed\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"in_progress\": {\n      \"@id\": \"flink:in_progress\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"restored\": {\n      \"@id\": \"flink:restored\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"total\": {\n      \"@id\": \"flink:total\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"DashboardConfiguration\": \"flink:DashboardConfiguration\",\n    \"features\": {\n      \"@id\": \"flink:features\",\n      \"@type\": \"xsd:string\"\n    },\n    \"flink-revision\": {\n      \"@id\": \"flink:flink-revision\",\n      \"@type\": \"xsd:string\"\n    },\n    \"refresh-interval\": {\n      \"@id\": \"flink:refresh-interval\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"timezone-name\": {\n      \"@id\": \"flink:timezone-name\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"timezone-offset\": {\n      \"@id\": \"flink:timezone-offset\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"EnvironmentInfo\": \"flink:EnvironmentInfo\",\n    \"classpath\": {\n      \"@id\": \"flink:classpath\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"jvm\": {\n      \"@id\": \"flink:jvm\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ExceptionInfo\": \"flink:ExceptionInfo\",\n    \"endpoint\": {\n      \"@id\": \"flink:endpoint\",\n      \"@type\": \"xsd:string\"\n    },\n    \"exceptionName\": {\n      \"@id\": \"flink:exceptionName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"failureLabels\": {\n      \"@id\": \"flink:failureLabels\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stacktrace\": {\n      \"@id\": \"flink:stacktrace\",\n      \"@type\": \"xsd:string\"\n    },\n    \"taskManagerId\": {\n      \"@id\": \"flink:taskManagerId\",\n      \"@type\": \"xsd:string\"\n   \
  \ },\n    \"taskName\": {\n      \"@id\": \"flink:taskName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timestamp\": {\n      \"@id\": \"flink:timestamp\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"ExecutionConfigInfo\": \"flink:ExecutionConfigInfo\",\n    \"job-parallelism\": {\n      \"@id\": \"flink:job-parallelism\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"object-reuse-mode\": {\n      \"@id\": \"flink:object-reuse-mode\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"restart-strategy\": {\n      \"@id\": \"flink:restart-strategy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"user-config\": {\n      \"@id\": \"flink:user-config\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ExecutionState\": \"flink:ExecutionState\",\n    \"ExternalizedCheckpointInfo\": \"flink:ExternalizedCheckpointInfo\",\n    \"delete_on_cancellation\": {\n      \"@id\": \"flink:delete_on_cancellation\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"enabled\": {\n      \"@id\"\
  : \"flink:enabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"FailedCheckpointStatistics\": \"flink:FailedCheckpointStatistics\",\n    \"FailureLabel\": \"flink:FailureLabel\",\n    \"Features\": \"flink:Features\",\n    \"web-cancel\": {\n      \"@id\": \"flink:web-cancel\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"web-history\": {\n      \"@id\": \"flink:web-history\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"web-rescale\": {\n      \"@id\": \"flink:web-rescale\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"web-submit\": {\n      \"@id\": \"flink:web-submit\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"GarbageCollectorInfo\": \"flink:GarbageCollectorInfo\",\n    \"count\": {\n      \"@id\": \"flink:count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"name\": \"schema:name\",\n    \"time\": {\n      \"@id\": \"flink:time\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"HardwareDescription\": \"flink:HardwareDescription\",\n    \"cpuCores\": {\n\
  \      \"@id\": \"flink:cpuCores\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"freeMemory\": {\n      \"@id\": \"flink:freeMemory\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"managedMemory\": {\n      \"@id\": \"flink:managedMemory\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"physicalMemory\": {\n      \"@id\": \"flink:physicalMemory\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"Id\": \"flink:Id\",\n    \"IntermediateDataSetID\": \"flink:IntermediateDataSetID\",\n    \"IOMetricsInfo\": \"flink:IOMetricsInfo\",\n    \"accumulated-backpressured-time\": {\n      \"@id\": \"flink:accumulated-backpressured-time\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"accumulated-busy-time\": {\n      \"@id\": \"flink:accumulated-busy-time\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"accumulated-idle-time\": {\n      \"@id\": \"flink:accumulated-idle-time\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"read-bytes\": {\n      \"@id\": \"flink:read-bytes\",\n  \
  \    \"@type\": \"xsd:integer\"\n    },\n    \"read-bytes-complete\": {\n      \"@id\": \"flink:read-bytes-complete\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"read-records\": {\n      \"@id\": \"flink:read-records\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"read-records-complete\": {\n      \"@id\": \"flink:read-records-complete\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"write-bytes\": {\n      \"@id\": \"flink:write-bytes\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"write-bytes-complete\": {\n      \"@id\": \"flink:write-bytes-complete\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"write-records\": {\n      \"@id\": \"flink:write-records\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"write-records-complete\": {\n      \"@id\": \"flink:write-records-complete\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"JarEntryInfo\": \"flink:JarEntryInfo\",\n    \"description\": \"schema:description\",\n    \"JarFileInfo\": \"flink:JarFileInfo\",\n   \
  \ \"entry\": {\n      \"@id\": \"flink:entry\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"uploaded\": {\n      \"@id\": \"flink:uploaded\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"JarListInfo\": \"flink:JarListInfo\",\n    \"address\": {\n      \"@id\": \"flink:address\",\n      \"@type\": \"xsd:string\"\n    },\n    \"files\": {\n      \"@id\": \"flink:files\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"JarPlanRequestBody\": \"flink:JarPlanRequestBody\",\n    \"entryClass\": {\n      \"@id\": \"flink:entryClass\",\n      \"@type\": \"xsd:string\"\n    },\n    \"flinkConfiguration\": {\n      \"@id\": \"flink:flinkConfiguration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"jobId\": {\n      \"@id\": \"flink:jobId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"parallelism\": {\n      \"@id\": \"flink:parallelism\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"programArgsList\": {\n      \"\
  @id\": \"flink:programArgsList\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"JarRunRequestBody\": \"flink:JarRunRequestBody\",\n    \"allowNonRestoredState\": {\n      \"@id\": \"flink:allowNonRestoredState\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"claimMode\": {\n      \"@id\": \"flink:claimMode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"restoreMode\": {\n      \"@id\": \"flink:restoreMode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"savepointPath\": {\n      \"@id\": \"flink:savepointPath\",\n      \"@type\": \"xsd:string\"\n    },\n    \"JarRunResponseBody\": \"flink:JarRunResponseBody\",\n    \"jobid\": {\n      \"@id\": \"flink:jobid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"JarUploadResponseBody\": \"flink:JarUploadResponseBody\",\n    \"filename\": {\n      \"@id\": \"flink:filename\",\n      \"@type\": \"xsd:string\"\n    },\n    \"JobAccumulator\": \"flink:JobAccumulator\",\n    \"JobAccumulatorsInfo\": \"\
  flink:JobAccumulatorsInfo\",\n    \"job-accumulators\": {\n      \"@id\": \"flink:job-accumulators\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"serialized-user-task-accumulators\": {\n      \"@id\": \"flink:serialized-user-task-accumulators\",\n      \"@type\": \"xsd:string\"\n    },\n    \"user-task-accumulators\": {\n      \"@id\": \"flink:user-task-accumulators\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"JobClientHeartbeatRequestBody\": \"flink:JobClientHeartbeatRequestBody\",\n    \"expiredTimestamp\": {\n      \"@id\": \"flink:expiredTimestamp\",\n      \"@type\": \"xsd:integer\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/apache-flink/refs/heads/main/json-ld/apache-flink-rest-context.jsonld
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
