---
api_specs:
- filename: amazon-cloudformation-openapi.yml
  format: yaml
  label: Amazon CloudFormation API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-cloudformation/refs/heads/main/openapi/amazon-cloudformation-openapi.yml
class_count: 16
classes:
- Stack
- description
- ChangeSet
- StackResource
- Parameter
- Output
- Tag
- RollbackConfiguration
- StackDriftInformation
- StackResourceDriftInformation
- Change
- CreateStackOutput
- DescribeStacksOutput
- UpdateStackOutput
- ListStacksOutput
- CreateChangeSetOutput
context_file: json-ld/amazon-cloudformation-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-cloudformation/refs/heads/main/json-ld/amazon-cloudformation-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Cloudformation from Amazon CloudFormation.
layout: jsonld
name: Amazon Cloudformation Context
namespaces:
- prefix: cloudformation
  uri: https://aws.amazon.com/cloudformation/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: stackId
  type: string
- container: ''
  name: stackName
  type: string
- container: ''
  name: changeSetId
  type: string
- container: set
  name: parameters
  type: string
- container: ''
  name: creationTime
  type: dateTime
- container: ''
  name: deletionTime
  type: dateTime
- container: ''
  name: lastUpdatedTime
  type: dateTime
- container: ''
  name: rollbackConfiguration
  type: string
- container: ''
  name: stackStatus
  type: string
- container: ''
  name: stackStatusReason
  type: string
- container: ''
  name: disableRollback
  type: boolean
- container: set
  name: notificationARNs
  type: string
- container: ''
  name: timeoutInMinutes
  type: integer
- container: set
  name: capabilities
  type: string
- container: set
  name: outputs
  type: string
- container: ''
  name: roleARN
  type: string
- container: set
  name: tags
  type: string
- container: ''
  name: enableTerminationProtection
  type: boolean
- container: ''
  name: driftInformation
  type: string
- container: ''
  name: changeSetName
  type: string
- container: ''
  name: executionStatus
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: statusReason
  type: string
- container: set
  name: changes
  type: string
- container: ''
  name: logicalResourceId
  type: string
- container: ''
  name: physicalResourceId
  type: string
- container: ''
  name: resourceType
  type: string
- container: ''
  name: timestamp
  type: dateTime
- container: ''
  name: resourceStatus
  type: string
- container: ''
  name: resourceStatusReason
  type: string
- container: ''
  name: parameterKey
  type: string
- container: ''
  name: parameterValue
  type: string
- container: ''
  name: usePreviousValue
  type: boolean
- container: ''
  name: resolvedValue
  type: string
- container: ''
  name: outputKey
  type: string
- container: ''
  name: outputValue
  type: string
- container: ''
  name: exportName
  type: string
- container: ''
  name: key
  type: string
- container: ''
  name: value
  type: string
- container: set
  name: rollbackTriggers
  type: string
- container: ''
  name: monitoringTimeInMinutes
  type: integer
- container: ''
  name: stackDriftStatus
  type: string
- container: ''
  name: lastCheckTimestamp
  type: dateTime
- container: ''
  name: stackResourceDriftStatus
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: resourceChange
  type: string
- container: set
  name: stacks
  type: string
- container: ''
  name: nextToken
  type: string
- container: set
  name: stackSummaries
  type: string
- container: ''
  name: id
  type: string
property_count: 50
provider_name: Amazon CloudFormation
provider_slug: amazon-cloudformation
slug: amazon-cloudformation-context
source_filename: amazon-cloudformation-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"cloudformation\": \"https://aws.amazon.com/cloudformation/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Stack\": \"cloudformation:Stack\",\n    \"stackId\": {\n      \"@id\": \"cloudformation:stack_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stackName\": {\n      \"@id\": \"cloudformation:stack_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"changeSetId\": {\n      \"@id\": \"cloudformation:change_set_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\",\n    \"parameters\": {\n      \"@id\": \"cloudformation:parameters\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"creationTime\": {\n      \"@id\": \"cloudformation:creation_time\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"deletionTime\": {\n      \"@id\": \"\
  cloudformation:deletion_time\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"lastUpdatedTime\": {\n      \"@id\": \"cloudformation:last_updated_time\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"rollbackConfiguration\": {\n      \"@id\": \"cloudformation:rollback_configuration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stackStatus\": {\n      \"@id\": \"cloudformation:stack_status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stackStatusReason\": {\n      \"@id\": \"cloudformation:stack_status_reason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"disableRollback\": {\n      \"@id\": \"cloudformation:disable_rollback\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"notificationARNs\": {\n      \"@id\": \"cloudformation:notification_a_r_ns\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timeoutInMinutes\": {\n      \"@id\": \"cloudformation:timeout_in_minutes\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"capabilities\"\
  : {\n      \"@id\": \"cloudformation:capabilities\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"outputs\": {\n      \"@id\": \"cloudformation:outputs\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"roleARN\": {\n      \"@id\": \"cloudformation:role_a_r_n\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tags\": {\n      \"@id\": \"cloudformation:tags\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"enableTerminationProtection\": {\n      \"@id\": \"cloudformation:enable_termination_protection\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"driftInformation\": {\n      \"@id\": \"cloudformation:drift_information\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ChangeSet\": \"cloudformation:ChangeSet\",\n    \"changeSetName\": {\n      \"@id\": \"cloudformation:change_set_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"executionStatus\": {\n      \"@id\": \"cloudformation:execution_status\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"cloudformation:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"statusReason\": {\n      \"@id\": \"cloudformation:status_reason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"changes\": {\n      \"@id\": \"cloudformation:changes\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"StackResource\": \"cloudformation:StackResource\",\n    \"logicalResourceId\": {\n      \"@id\": \"cloudformation:logical_resource_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"physicalResourceId\": {\n      \"@id\": \"cloudformation:physical_resource_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resourceType\": {\n      \"@id\": \"cloudformation:resource_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timestamp\": {\n      \"@id\": \"cloudformation:timestamp\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"resourceStatus\": {\n      \"@id\": \"cloudformation:resource_status\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"resourceStatusReason\": {\n      \"@id\": \"cloudformation:resource_status_reason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Parameter\": \"cloudformation:Parameter\",\n    \"parameterKey\": {\n      \"@id\": \"cloudformation:parameter_key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"parameterValue\": {\n      \"@id\": \"cloudformation:parameter_value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"usePreviousValue\": {\n      \"@id\": \"cloudformation:use_previous_value\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"resolvedValue\": {\n      \"@id\": \"cloudformation:resolved_value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Output\": \"cloudformation:Output\",\n    \"outputKey\": {\n      \"@id\": \"cloudformation:output_key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"outputValue\": {\n      \"@id\": \"cloudformation:output_value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"exportName\": {\n \
  \     \"@id\": \"cloudformation:export_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Tag\": \"cloudformation:Tag\",\n    \"key\": {\n      \"@id\": \"cloudformation:key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"cloudformation:value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RollbackConfiguration\": \"cloudformation:RollbackConfiguration\",\n    \"rollbackTriggers\": {\n      \"@id\": \"cloudformation:rollback_triggers\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"monitoringTimeInMinutes\": {\n      \"@id\": \"cloudformation:monitoring_time_in_minutes\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"StackDriftInformation\": \"cloudformation:StackDriftInformation\",\n    \"stackDriftStatus\": {\n      \"@id\": \"cloudformation:stack_drift_status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastCheckTimestamp\": {\n      \"@id\": \"cloudformation:last_check_timestamp\",\n      \"@type\"\
  : \"xsd:dateTime\"\n    },\n    \"StackResourceDriftInformation\": \"cloudformation:StackResourceDriftInformation\",\n    \"stackResourceDriftStatus\": {\n      \"@id\": \"cloudformation:stack_resource_drift_status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Change\": \"cloudformation:Change\",\n    \"type\": {\n      \"@id\": \"cloudformation:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resourceChange\": {\n      \"@id\": \"cloudformation:resource_change\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreateStackOutput\": \"cloudformation:CreateStackOutput\",\n    \"DescribeStacksOutput\": \"cloudformation:DescribeStacksOutput\",\n    \"stacks\": {\n      \"@id\": \"cloudformation:stacks\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nextToken\": {\n      \"@id\": \"cloudformation:next_token\",\n      \"@type\": \"xsd:string\"\n    },\n    \"UpdateStackOutput\": \"cloudformation:UpdateStackOutput\",\n    \"ListStacksOutput\": \"\
  cloudformation:ListStacksOutput\",\n    \"stackSummaries\": {\n      \"@id\": \"cloudformation:stack_summaries\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreateChangeSetOutput\": \"cloudformation:CreateChangeSetOutput\",\n    \"id\": {\n      \"@id\": \"cloudformation:id\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-cloudformation/refs/heads/main/json-ld/amazon-cloudformation-context.jsonld
tags:
- CloudFormation
- Infrastructure as Code
- DevOps
- IaC
- JSON-LD
- Linked Data
- Semantic Web
---
