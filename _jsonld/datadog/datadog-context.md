---
api_specs:
- filename: datadog-api-openapi.yml
  format: yaml
  label: Datadog API
  slug: datadog-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/datadog/refs/heads/main/openapi/datadog-api-openapi.yml
- filename: datadog-metrics-openapi.yml
  format: yaml
  label: Datadog Metrics API
  slug: datadog-metrics-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/datadog/refs/heads/main/openapi/datadog-metrics-openapi.yml
- filename: datadog-logs-openapi.yml
  format: yaml
  label: Datadog Logs API
  slug: datadog-logs-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/datadog/refs/heads/main/openapi/datadog-logs-openapi.yml
- filename: datadog-events-openapi.yml
  format: yaml
  label: Datadog Events API
  slug: datadog-events-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/datadog/refs/heads/main/openapi/datadog-events-openapi.yml
- filename: datadog-monitors-openapi.yml
  format: yaml
  label: Datadog Monitors API
  slug: datadog-monitors-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/datadog/refs/heads/main/openapi/datadog-monitors-openapi.yml
- filename: datadog-incidents-openapi.yml
  format: yaml
  label: Datadog Incidents API
  slug: datadog-incidents-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/datadog/refs/heads/main/openapi/datadog-incidents-openapi.yml
class_count: 60
classes:
- APIErrorResponse
- APIKeyCreateAttributes
- APIKeyCreateData
- APIKeyCreateRequest
- APIKeyRelationships
- APIKeyResponse
- APIKeyUpdateAttributes
- APIKeyUpdateData
- APIKeyUpdateRequest
- Creator
- Datadog Event
- Datadog Log Event
- Datadog Metric Series
- Datadog Monitor
- DeletedMonitor
- Event
- EventAttributes
- EventCreateAttributes
- EventCreateRequest
- EventCreateResponse
- EventResponse
- EventsListResponse
- EventsSearchRequest
- HTTPLogItem
- Incident
- IncidentAttributes
- IncidentCreateAttributes
- IncidentCreateRequest
- IncidentResponse
- IncidentTeamCreateRequest
- IncidentTeamUpdateRequest
- IncidentUpdateAttributes
- IncidentUpdateRequest
- IncidentsResponse
- IntakePayloadAccepted
- Log
- LogAttributes
- LogsAggregateRequest
- LogsCompute
- LogsGroupBy
- LogsListRequest
- LogsListResponse
- LogsQueryFilter
- MetricPayload
- MetricPoint
- MetricQueryDefinition
- MetricResource
- MetricSeries
- MetricTimeseriesQuery
- MetricTimeseriesResponse
- Monitor
- MonitorGroupState
- MonitorMuteSettings
- MonitorOptions
- MonitorState
- MonitorThresholds
- MonitorUnmuteSettings
- MonitorUpdateRequest
- QueryFormula
- TimeseriesResult
context_file: json-ld/datadog-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/datadog/refs/heads/main/json-ld/datadog-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Datadog from Datadog.
layout: jsonld
name: Datadog Context
namespaces:
- prefix: dd
  uri: https://docs.datadoghq.com/api/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: aggregation
  type: string
- container: ''
  name: aggregation_key
  type: string
- container: ''
  name: alert_type
  type: string
- container: ''
  name: alias
  type: string
- container: ''
  name: all_scopes
  type: boolean
- container: ''
  name: attributes
  type: string
- container: ''
  name: category
  type: string
- container: set
  name: compute
  type: string
- container: ''
  name: content
  type: string
- container: ''
  name: created
  type: dateTime
- container: ''
  name: created_by
  type: string
- container: ''
  name: creator
  type: string
- container: ''
  name: critical
  type: string
- container: ''
  name: critical_recovery
  type: string
- container: ''
  name: customer_impact_duration
  type: integer
- container: ''
  name: customer_impact_end
  type: dateTime
- container: ''
  name: customer_impact_scope
  type: string
- container: ''
  name: customer_impact_start
  type: dateTime
- container: ''
  name: customer_impacted
  type: boolean
- container: ''
  name: data
  type: string
- container: ''
  name: data_source
  type: string
- container: ''
  name: ddsource
  type: string
- container: ''
  name: ddtags
  type: string
- container: ''
  name: deleted
  type: dateTime
- container: ''
  name: deleted_monitor_id
  type: string
- container: ''
  name: detected
  type: dateTime
- container: ''
  name: email
  type: string
- container: ''
  name: end
  type: string
- container: set
  name: errors
  type: string
- container: ''
  name: escalation_message
  type: string
- container: ''
  name: evaluation_delay
  type: integer
- container: ''
  name: event_id
  type: string
- container: ''
  name: facet
  type: string
- container: ''
  name: fields
  type: reference
- container: ''
  name: filter
  type: reference
- container: ''
  name: formula
  type: string
- container: ''
  name: from
  type: string
- container: set
  name: group_by
  type: string
- container: set
  name: group_tags
  type: string
- container: ''
  name: groups
  type: reference
- container: ''
  name: handle
  type: string
- container: ''
  name: host
  type: string
- container: ''
  name: hostname
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: include_tags
  type: boolean
- container: set
  name: included
  type: string
- container: set
  name: indexes
  type: string
- container: ''
  name: interval
  type: string
- container: ''
  name: last_notified_ts
  type: string
- container: ''
  name: last_resolved_ts
  type: string
- container: ''
  name: last_triggered_ts
  type: string
- container: ''
  name: limit
  type: integer
- container: ''
  name: links
  type: reference
- container: ''
  name: message
  type: string
- container: ''
  name: meta
  type: reference
- container: ''
  name: metric
  type: string
- container: ''
  name: modified
  type: dateTime
- container: ''
  name: modified_by
  type: string
- container: ''
  name: name
  type: string
- container: ''
  name: new_group_delay
  type: integer
- container: ''
  name: no_data_timeframe
  type: integer
- container: set
  name: notification_handles
  type: string
- container: ''
  name: notify_audit
  type: boolean
- container: ''
  name: notify_no_data
  type: boolean
- container: ''
  name: ok
  type: string
- container: ''
  name: options
  type: reference
- container: ''
  name: page
  type: reference
- container: set
  name: points
  type: string
- container: ''
  name: priority
  type: string
- container: ''
  name: public_id
  type: integer
- container: ''
  name: query
  type: string
- container: ''
  name: query_index
  type: integer
- container: ''
  name: relationships
  type: reference
- container: ''
  name: remote_config_read_enabled
  type: boolean
- container: ''
  name: renotify_interval
  type: integer
- container: set
  name: renotify_statuses
  type: string
- container: ''
  name: require_full_window
  type: boolean
- container: ''
  name: resolved
  type: dateTime
- container: set
  name: resources
  type: string
- container: set
  name: restricted_roles
  type: string
- container: ''
  name: scope
  type: string
- container: set
  name: series
  type: string
- container: ''
  name: service
  type: string
- container: ''
  name: severity
  type: string
- container: ''
  name: silenced
  type: reference
- container: ''
  name: sort
  type: string
- container: ''
  name: source
  type: string
- container: ''
  name: source_type_name
  type: string
- container: ''
  name: state
  type: string
- container: ''
  name: status
  type: string
- container: set
  name: tags
  type: string
- container: ''
  name: thresholds
  type: string
- container: ''
  name: time_to_detect
  type: integer
- container: ''
  name: time_to_internal_response
  type: integer
- container: ''
  name: time_to_repair
  type: integer
- container: ''
  name: timeout_h
  type: integer
- container: ''
  name: timestamp
  type: dateTime
- container: ''
  name: title
  type: string
- container: ''
  name: to
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: unit
  type: string
- container: ''
  name: unknown
  type: string
- container: ''
  name: value
  type: string
- container: set
  name: values
  type: string
- container: ''
  name: warning
  type: string
- container: ''
  name: warning_recovery
  type: string
property_count: 106
provider_name: Datadog
provider_slug: datadog
slug: datadog-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"dd\": \"https://docs.datadoghq.com/api/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"APIErrorResponse\": \"dd:APIErrorResponse\",\n    \"APIKeyCreateAttributes\": \"dd:APIKeyCreateAttributes\",\n    \"APIKeyCreateData\": \"dd:APIKeyCreateData\",\n    \"APIKeyCreateRequest\": \"dd:APIKeyCreateRequest\",\n    \"APIKeyRelationships\": \"dd:APIKeyRelationships\",\n    \"APIKeyResponse\": \"dd:APIKeyResponse\",\n    \"APIKeyUpdateAttributes\": \"dd:APIKeyUpdateAttributes\",\n    \"APIKeyUpdateData\": \"dd:APIKeyUpdateData\",\n    \"APIKeyUpdateRequest\": \"dd:APIKeyUpdateRequest\",\n    \"Creator\": \"dd:Creator\",\n    \"Datadog Event\": \"dd:Datadog Event\",\n    \"Datadog Log Event\": \"dd:Datadog Log Event\",\n    \"Datadog Metric Series\": \"dd:Datadog Metric Series\",\n    \"Datadog Monitor\": \"dd:Datadog Monitor\",\n    \"DeletedMonitor\": \"dd:DeletedMonitor\"\
  ,\n    \"Event\": \"dd:Event\",\n    \"EventAttributes\": \"dd:EventAttributes\",\n    \"EventCreateAttributes\": \"dd:EventCreateAttributes\",\n    \"EventCreateRequest\": \"dd:EventCreateRequest\",\n    \"EventCreateResponse\": \"dd:EventCreateResponse\",\n    \"EventResponse\": \"dd:EventResponse\",\n    \"EventsListResponse\": \"dd:EventsListResponse\",\n    \"EventsSearchRequest\": \"dd:EventsSearchRequest\",\n    \"HTTPLogItem\": \"dd:HTTPLogItem\",\n    \"Incident\": \"dd:Incident\",\n    \"IncidentAttributes\": \"dd:IncidentAttributes\",\n    \"IncidentCreateAttributes\": \"dd:IncidentCreateAttributes\",\n    \"IncidentCreateRequest\": \"dd:IncidentCreateRequest\",\n    \"IncidentResponse\": \"dd:IncidentResponse\",\n    \"IncidentTeamCreateRequest\": \"dd:IncidentTeamCreateRequest\",\n    \"IncidentTeamUpdateRequest\": \"dd:IncidentTeamUpdateRequest\",\n    \"IncidentUpdateAttributes\": \"dd:IncidentUpdateAttributes\",\n    \"IncidentUpdateRequest\": \"dd:IncidentUpdateRequest\"\
  ,\n    \"IncidentsResponse\": \"dd:IncidentsResponse\",\n    \"IntakePayloadAccepted\": \"dd:IntakePayloadAccepted\",\n    \"Log\": \"dd:Log\",\n    \"LogAttributes\": \"dd:LogAttributes\",\n    \"LogsAggregateRequest\": \"dd:LogsAggregateRequest\",\n    \"LogsCompute\": \"dd:LogsCompute\",\n    \"LogsGroupBy\": \"dd:LogsGroupBy\",\n    \"LogsListRequest\": \"dd:LogsListRequest\",\n    \"LogsListResponse\": \"dd:LogsListResponse\",\n    \"LogsQueryFilter\": \"dd:LogsQueryFilter\",\n    \"MetricPayload\": \"dd:MetricPayload\",\n    \"MetricPoint\": \"dd:MetricPoint\",\n    \"MetricQueryDefinition\": \"dd:MetricQueryDefinition\",\n    \"MetricResource\": \"dd:MetricResource\",\n    \"MetricSeries\": \"dd:MetricSeries\",\n    \"MetricTimeseriesQuery\": \"dd:MetricTimeseriesQuery\",\n    \"MetricTimeseriesResponse\": \"dd:MetricTimeseriesResponse\",\n    \"Monitor\": \"dd:Monitor\",\n    \"MonitorGroupState\": \"dd:MonitorGroupState\",\n    \"MonitorMuteSettings\": \"dd:MonitorMuteSettings\"\
  ,\n    \"MonitorOptions\": \"dd:MonitorOptions\",\n    \"MonitorState\": \"dd:MonitorState\",\n    \"MonitorThresholds\": \"dd:MonitorThresholds\",\n    \"MonitorUnmuteSettings\": \"dd:MonitorUnmuteSettings\",\n    \"MonitorUpdateRequest\": \"dd:MonitorUpdateRequest\",\n    \"QueryFormula\": \"dd:QueryFormula\",\n    \"TimeseriesResult\": \"dd:TimeseriesResult\",\n    \"aggregation\": {\n      \"@id\": \"dd:aggregation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"aggregation_key\": {\n      \"@id\": \"dd:aggregation_key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"alert_type\": {\n      \"@id\": \"dd:alert_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"alias\": {\n      \"@id\": \"dd:alias\",\n      \"@type\": \"xsd:string\"\n    },\n    \"all_scopes\": {\n      \"@id\": \"dd:all_scopes\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"attributes\": {\n      \"@id\": \"dd:attributes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"category\": {\n      \"@id\":\
  \ \"dd:category\",\n      \"@type\": \"xsd:string\"\n    },\n    \"compute\": {\n      \"@id\": \"dd:compute\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"content\": {\n      \"@id\": \"dd:content\",\n      \"@type\": \"xsd:string\"\n    },\n    \"created\": {\n      \"@id\": \"dd:created\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"created_by\": {\n      \"@id\": \"dd:created_by\",\n      \"@type\": \"xsd:string\"\n    },\n    \"creator\": {\n      \"@id\": \"dd:creator\",\n      \"@type\": \"xsd:string\"\n    },\n    \"critical\": {\n      \"@id\": \"dd:critical\",\n      \"@type\": \"xsd:string\"\n    },\n    \"critical_recovery\": {\n      \"@id\": \"dd:critical_recovery\",\n      \"@type\": \"xsd:string\"\n    },\n    \"customer_impact_duration\": {\n      \"@id\": \"dd:customer_impact_duration\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"customer_impact_end\": {\n      \"@id\": \"dd:customer_impact_end\",\n      \"@type\": \"xsd:dateTime\"\
  \n    },\n    \"customer_impact_scope\": {\n      \"@id\": \"dd:customer_impact_scope\",\n      \"@type\": \"xsd:string\"\n    },\n    \"customer_impact_start\": {\n      \"@id\": \"dd:customer_impact_start\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"customer_impacted\": {\n      \"@id\": \"dd:customer_impacted\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"data\": {\n      \"@id\": \"dd:data\",\n      \"@type\": \"xsd:string\"\n    },\n    \"data_source\": {\n      \"@id\": \"dd:data_source\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ddsource\": {\n      \"@id\": \"dd:ddsource\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ddtags\": {\n      \"@id\": \"dd:ddtags\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deleted\": {\n      \"@id\": \"dd:deleted\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"deleted_monitor_id\": {\n      \"@id\": \"dd:deleted_monitor_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"detected\": {\n      \"@id\": \"dd:detected\"\
  ,\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"email\": {\n      \"@id\": \"dd:email\",\n      \"@type\": \"xsd:string\"\n    },\n    \"end\": {\n      \"@id\": \"dd:end\",\n      \"@type\": \"xsd:string\"\n    },\n    \"errors\": {\n      \"@id\": \"dd:errors\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"escalation_message\": {\n      \"@id\": \"dd:escalation_message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"evaluation_delay\": {\n      \"@id\": \"dd:evaluation_delay\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"event_id\": {\n      \"@id\": \"dd:event_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"facet\": {\n      \"@id\": \"dd:facet\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fields\": {\n      \"@id\": \"dd:fields\",\n      \"@type\": \"@id\"\n    },\n    \"filter\": {\n      \"@id\": \"dd:filter\",\n      \"@type\": \"@id\"\n    },\n    \"formula\": {\n      \"@id\": \"dd:formula\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"from\": {\n      \"@id\": \"dd:from\",\n      \"@type\": \"xsd:string\"\n    },\n    \"group_by\": {\n      \"@id\": \"dd:group_by\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"group_tags\": {\n      \"@id\": \"dd:group_tags\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"groups\": {\n      \"@id\": \"dd:groups\",\n      \"@type\": \"@id\"\n    },\n    \"handle\": {\n      \"@id\": \"dd:handle\",\n      \"@type\": \"xsd:string\"\n    },\n    \"host\": {\n      \"@id\": \"dd:host\",\n      \"@type\": \"xsd:string\"\n    },\n    \"hostname\": {\n      \"@id\": \"dd:hostname\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"dd:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"include_tags\": {\n      \"@id\": \"dd:include_tags\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"included\": {\n      \"@id\": \"dd:included\",\n      \"@container\": \"@set\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"indexes\": {\n      \"@id\": \"dd:indexes\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"interval\": {\n      \"@id\": \"dd:interval\",\n      \"@type\": \"xsd:string\"\n    },\n    \"last_notified_ts\": {\n      \"@id\": \"dd:last_notified_ts\",\n      \"@type\": \"xsd:string\"\n    },\n    \"last_resolved_ts\": {\n      \"@id\": \"dd:last_resolved_ts\",\n      \"@type\": \"xsd:string\"\n    },\n    \"last_triggered_ts\": {\n      \"@id\": \"dd:last_triggered_ts\",\n      \"@type\": \"xsd:string\"\n    },\n    \"limit\": {\n      \"@id\": \"dd:limit\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"links\": {\n      \"@id\": \"dd:links\",\n      \"@type\": \"@id\"\n    },\n    \"message\": {\n      \"@id\": \"dd:message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"meta\": {\n      \"@id\": \"dd:meta\",\n      \"@type\": \"@id\"\n    },\n    \"metric\": {\n      \"@id\": \"dd:metric\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"modified\": {\n      \"@id\": \"dd:modified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"modified_by\": {\n      \"@id\": \"dd:modified_by\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"dd:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"new_group_delay\": {\n      \"@id\": \"dd:new_group_delay\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"no_data_timeframe\": {\n      \"@id\": \"dd:no_data_timeframe\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"notification_handles\": {\n      \"@id\": \"dd:notification_handles\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"notify_audit\": {\n      \"@id\": \"dd:notify_audit\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"notify_no_data\": {\n      \"@id\": \"dd:notify_no_data\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"ok\": {\n      \"@id\": \"dd:ok\",\n      \"@type\": \"xsd:string\"\n    },\n    \"options\": {\n      \"@id\"\
  : \"dd:options\",\n      \"@type\": \"@id\"\n    },\n    \"page\": {\n      \"@id\": \"dd:page\",\n      \"@type\": \"@id\"\n    },\n    \"points\": {\n      \"@id\": \"dd:points\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"priority\": {\n      \"@id\": \"dd:priority\",\n      \"@type\": \"xsd:string\"\n    },\n    \"public_id\": {\n      \"@id\": \"dd:public_id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"query\": {\n      \"@id\": \"dd:query\",\n      \"@type\": \"xsd:string\"\n    },\n    \"query_index\": {\n      \"@id\": \"dd:query_index\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"relationships\": {\n      \"@id\": \"dd:relationships\",\n      \"@type\": \"@id\"\n    },\n    \"remote_config_read_enabled\": {\n      \"@id\": \"dd:remote_config_read_enabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"renotify_interval\": {\n      \"@id\": \"dd:renotify_interval\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"renotify_statuses\"\
  : {\n      \"@id\": \"dd:renotify_statuses\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"require_full_window\": {\n      \"@id\": \"dd:require_full_window\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"resolved\": {\n      \"@id\": \"dd:resolved\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"resources\": {\n      \"@id\": \"dd:resources\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"restricted_roles\": {\n      \"@id\": \"dd:restricted_roles\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"scope\": {\n      \"@id\": \"dd:scope\",\n      \"@type\": \"xsd:string\"\n    },\n    \"series\": {\n      \"@id\": \"dd:series\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"service\": {\n      \"@id\": \"dd:service\",\n      \"@type\": \"xsd:string\"\n    },\n    \"severity\": {\n      \"@id\": \"dd:severity\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"silenced\": {\n      \"@id\": \"dd:silenced\",\n      \"@type\": \"@id\"\n    },\n    \"sort\": {\n      \"@id\": \"dd:sort\",\n      \"@type\": \"xsd:string\"\n    },\n    \"source\": {\n      \"@id\": \"dd:source\",\n      \"@type\": \"xsd:string\"\n    },\n    \"source_type_name\": {\n      \"@id\": \"dd:source_type_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"state\": {\n      \"@id\": \"dd:state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"dd:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tags\": {\n      \"@id\": \"dd:tags\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"thresholds\": {\n      \"@id\": \"dd:thresholds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"time_to_detect\": {\n      \"@id\": \"dd:time_to_detect\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"time_to_internal_response\": {\n      \"@id\": \"dd:time_to_internal_response\",\n      \"@type\": \"\
  xsd:integer\"\n    },\n    \"time_to_repair\": {\n      \"@id\": \"dd:time_to_repair\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"timeout_h\": {\n      \"@id\": \"dd:timeout_h\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"timestamp\": {\n      \"@id\": \"dd:timestamp\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"title\": {\n      \"@id\": \"dd:title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"to\": {\n      \"@id\": \"dd:to\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"dd:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"unit\": {\n      \"@id\": \"dd:unit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"unknown\": {\n      \"@id\": \"dd:unknown\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"dd:value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"values\": {\n      \"@id\": \"dd:values\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"warning\": {\n\
  \      \"@id\": \"dd:warning\",\n      \"@type\": \"xsd:string\"\n    },\n    \"warning_recovery\": {\n      \"@id\": \"dd:warning_recovery\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/datadog/refs/heads/main/json-ld/datadog-context.jsonld
tags:
- Analytics
- Dashboards
- Monitoring
- Platform
- T1
- Visualizations
- JSON-LD
- Linked Data
- Semantic Web
---
