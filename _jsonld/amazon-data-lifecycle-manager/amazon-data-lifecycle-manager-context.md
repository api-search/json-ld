---
api_specs:
- filename: amazon-data-lifecycle-manager-openapi.yml
  format: yaml
  label: Amazon Data Lifecycle Manager API
  slug: amazon-dlm-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-data-lifecycle-manager/refs/heads/main/openapi/amazon-data-lifecycle-manager-openapi.yml
class_count: 0
classes: []
context_file: json-ld/amazon-data-lifecycle-manager-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-data-lifecycle-manager/refs/heads/main/json-ld/amazon-data-lifecycle-manager-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Data Lifecycle Manager from Amazon Data Lifecycle Manager.
layout: jsonld
name: Amazon Data Lifecycle Manager Context
namespaces:
- prefix: aws
  uri: https://aws.amazon.com/ebs/data-lifecycle-manager/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: LifecyclePolicy
  type: ''
- container: ''
  name: LifecyclePolicySummary
  type: ''
- container: ''
  name: PolicyDetails
  type: ''
- container: ''
  name: Schedule
  type: ''
- container: ''
  name: CreateRule
  type: ''
- container: ''
  name: RetainRule
  type: ''
- container: ''
  name: Tag
  type: ''
- container: ''
  name: PolicyId
  type: string
- container: ''
  name: Description
  type: string
- container: ''
  name: State
  type: string
- container: ''
  name: StatusMessage
  type: string
- container: ''
  name: ExecutionRoleArn
  type: string
- container: ''
  name: PolicyType
  type: string
- container: ''
  name: PolicySummary
  type: string
- container: set
  name: ResourceTypes
  type: ''
- container: set
  name: TargetTags
  type: ''
- container: set
  name: Schedules
  type: ''
- container: set
  name: Policies
  type: ''
- container: ''
  name: Name
  type: string
- container: ''
  name: Interval
  type: integer
- container: ''
  name: IntervalUnit
  type: string
- container: set
  name: Times
  type: ''
- container: ''
  name: CronExpression
  type: string
- container: ''
  name: Count
  type: integer
- container: set
  name: TagsToAdd
  type: ''
- container: ''
  name: CopyTags
  type: boolean
- container: ''
  name: Key
  type: string
- container: ''
  name: Value
  type: string
- container: ''
  name: Tags
  type: ''
- container: ''
  name: DateCreated
  type: dateTime
- container: ''
  name: DateModified
  type: dateTime
- container: ''
  name: message
  type: string
- container: ''
  name: code
  type: string
- container: ''
  name: requestId
  type: string
property_count: 34
provider_name: Amazon Data Lifecycle Manager
provider_slug: amazon-data-lifecycle-manager
slug: amazon-data-lifecycle-manager-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aws\": \"https://aws.amazon.com/ebs/data-lifecycle-manager/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"LifecyclePolicy\": {\"@id\": \"aws:LifecyclePolicy\"},\n    \"LifecyclePolicySummary\": {\"@id\": \"aws:LifecyclePolicySummary\"},\n    \"PolicyDetails\": {\"@id\": \"aws:PolicyDetails\"},\n    \"Schedule\": {\"@id\": \"aws:Schedule\"},\n    \"CreateRule\": {\"@id\": \"aws:CreateRule\"},\n    \"RetainRule\": {\"@id\": \"aws:RetainRule\"},\n    \"Tag\": {\"@id\": \"aws:Tag\"},\n\n    \"PolicyId\": {\"@id\": \"aws:policyId\", \"@type\": \"xsd:string\"},\n    \"Description\": {\"@id\": \"schema:description\", \"@type\": \"xsd:string\"},\n    \"State\": {\"@id\": \"aws:state\", \"@type\": \"xsd:string\"},\n    \"StatusMessage\": {\"@id\": \"aws:statusMessage\", \"@type\": \"xsd:string\"},\n    \"ExecutionRoleArn\": {\"@id\": \"aws:executionRoleArn\", \"@type\": \"\
  xsd:string\"},\n    \"PolicyType\": {\"@id\": \"aws:policyType\", \"@type\": \"xsd:string\"},\n    \"PolicySummary\": {\"@id\": \"aws:policySummary\", \"@type\": \"xsd:string\"},\n    \"ResourceTypes\": {\"@id\": \"aws:resourceTypes\", \"@container\": \"@set\"},\n    \"TargetTags\": {\"@id\": \"aws:targetTags\", \"@container\": \"@set\"},\n    \"Schedules\": {\"@id\": \"aws:schedules\", \"@container\": \"@set\"},\n    \"Policies\": {\"@id\": \"aws:policies\", \"@container\": \"@set\"},\n\n    \"Name\": {\"@id\": \"schema:name\", \"@type\": \"xsd:string\"},\n    \"Interval\": {\"@id\": \"aws:interval\", \"@type\": \"xsd:integer\"},\n    \"IntervalUnit\": {\"@id\": \"aws:intervalUnit\", \"@type\": \"xsd:string\"},\n    \"Times\": {\"@id\": \"aws:times\", \"@container\": \"@set\"},\n    \"CronExpression\": {\"@id\": \"aws:cronExpression\", \"@type\": \"xsd:string\"},\n    \"Count\": {\"@id\": \"aws:retainCount\", \"@type\": \"xsd:integer\"},\n    \"TagsToAdd\": {\"@id\": \"aws:tagsToAdd\"\
  , \"@container\": \"@set\"},\n    \"CopyTags\": {\"@id\": \"aws:copyTags\", \"@type\": \"xsd:boolean\"},\n\n    \"Key\": {\"@id\": \"aws:tagKey\", \"@type\": \"xsd:string\"},\n    \"Value\": {\"@id\": \"aws:tagValue\", \"@type\": \"xsd:string\"},\n    \"Tags\": {\"@id\": \"aws:tags\"},\n\n    \"DateCreated\": {\"@id\": \"schema:dateCreated\", \"@type\": \"xsd:dateTime\"},\n    \"DateModified\": {\"@id\": \"schema:dateModified\", \"@type\": \"xsd:dateTime\"},\n\n    \"message\": {\"@id\": \"schema:description\", \"@type\": \"xsd:string\"},\n    \"code\": {\"@id\": \"aws:errorCode\", \"@type\": \"xsd:string\"},\n    \"requestId\": {\"@id\": \"aws:requestId\", \"@type\": \"xsd:string\"}\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-data-lifecycle-manager/refs/heads/main/json-ld/amazon-data-lifecycle-manager-context.jsonld
tags:
- AWS
- Backup
- EBS Snapshots
- Lifecycle Management
- Storage
- Automation
- Compliance
- JSON-LD
- Linked Data
- Semantic Web
---
