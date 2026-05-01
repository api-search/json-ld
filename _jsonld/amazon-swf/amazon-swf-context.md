---
api_specs:
- filename: amazon-swf-openapi-original.yml
  format: yaml
  label: Amazon Simple Workflow Service API
  slug: amazon-swf-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-swf/refs/heads/main/openapi/amazon-swf-openapi-original.yml
class_count: 13
classes:
- Workflow
- ActivityTask
- DecisionTask
- WorkflowExecution
- Domain
- ActivityType
- WorkflowType
- taskList
- executionStatus
- closeStatus
- tagList
- runId
- workflowId
context_file: json-ld/amazon-swf-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-swf/refs/heads/main/json-ld/amazon-swf-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Swf from Amazon Simple Workflow Service.
layout: jsonld
name: Amazon Swf Context
namespaces:
- prefix: swf
  uri: https://aws.amazon.com/swf/vocab#
properties: []
property_count: 0
provider_name: Amazon Simple Workflow Service
provider_slug: amazon-swf
slug: amazon-swf-context
source_filename: amazon-swf-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"swf\": \"https://aws.amazon.com/swf/vocab#\",\n    \"Workflow\": \"swf:Workflow\",\n    \"ActivityTask\": \"swf:ActivityTask\",\n    \"DecisionTask\": \"swf:DecisionTask\",\n    \"WorkflowExecution\": \"swf:WorkflowExecution\",\n    \"Domain\": \"swf:Domain\",\n    \"ActivityType\": \"swf:ActivityType\",\n    \"WorkflowType\": \"swf:WorkflowType\",\n    \"taskList\": \"swf:taskList\",\n    \"executionStatus\": \"swf:executionStatus\",\n    \"closeStatus\": \"swf:closeStatus\",\n    \"tagList\": \"swf:tagList\",\n    \"runId\": \"swf:runId\",\n    \"workflowId\": \"swf:workflowId\"\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-swf/refs/heads/main/json-ld/amazon-swf-context.jsonld
tags:
- Automation
- Task Coordination
- Workflow
- JSON-LD
- Linked Data
- Semantic Web
---
