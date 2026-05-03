---
api_specs:
- filename: restack-openapi.yml
  format: yaml
  label: Restack
  slug: restack
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/restack/refs/heads/main/openapi/restack-openapi.yml
class_count: 29
classes:
- aid
- runId
- agentName
- workflowName
- status
- AgentRun
- WorkflowRun
- Agent
- Workflow
- scheduleAgent
- scheduleWorkflow
- input
- output
- bearerToken
- SoftwareApplication
- name
- description
- url
- dateCreated
- dateModified
- version
- provider
- potentialAction
- result
- error
- Organization
- SoftwareSourceCode
- programmingLanguage
- codeRepository
context_file: json-ld/restack-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/restack/refs/heads/main/json-ld/restack-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Restack from Restack.
layout: jsonld
name: Restack Context
namespaces:
- prefix: restack
  uri: https://www.restack.io/vocab#
properties: []
property_count: 0
provider_name: Restack
provider_slug: restack
slug: restack-context
source_filename: restack-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"restack\": \"https://www.restack.io/vocab#\",\n    \"aid\": \"restack:aid\",\n    \"runId\": \"restack:runId\",\n    \"agentName\": \"restack:agentName\",\n    \"workflowName\": \"restack:workflowName\",\n    \"status\": \"restack:status\",\n    \"AgentRun\": \"restack:AgentRun\",\n    \"WorkflowRun\": \"restack:WorkflowRun\",\n    \"Agent\": \"restack:Agent\",\n    \"Workflow\": \"restack:Workflow\",\n    \"scheduleAgent\": \"restack:scheduleAgent\",\n    \"scheduleWorkflow\": \"restack:scheduleWorkflow\",\n    \"input\": \"restack:input\",\n    \"output\": \"restack:output\",\n    \"bearerToken\": \"restack:bearerToken\",\n    \"SoftwareApplication\": \"schema:SoftwareApplication\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"dateCreated\": \"schema:dateCreated\",\n    \"dateModified\": \"schema:dateModified\",\n    \"version\": \"schema:version\"\
  ,\n    \"provider\": \"schema:provider\",\n    \"potentialAction\": \"schema:potentialAction\",\n    \"result\": \"schema:result\",\n    \"error\": \"schema:error\",\n    \"Organization\": \"schema:Organization\",\n    \"SoftwareSourceCode\": \"schema:SoftwareSourceCode\",\n    \"programmingLanguage\": \"schema:programmingLanguage\",\n    \"codeRepository\": \"schema:codeRepository\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/restack/refs/heads/main/json-ld/restack-context.jsonld
tags:
- AI Agents
- Workflows
- Orchestration
- Enterprise
- Python
- JSON-LD
- Linked Data
- Semantic Web
---
