---
api_specs:
- filename: nomad-http-api-openapi.yml
  format: yaml
  label: HashiCorp Nomad HTTP API
  slug: http-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/nomad/refs/heads/main/openapi/nomad-http-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/nomad-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/nomad/refs/heads/main/json-ld/nomad-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Nomad from HashiCorp Nomad.
layout: jsonld
name: Nomad Context
namespaces:
- prefix: nomad
  uri: https://developer.hashicorp.com/nomad/ns#
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Job
  type: ''
- container: ''
  name: TaskGroup
  type: ''
- container: ''
  name: Task
  type: ''
- container: ''
  name: Allocation
  type: ''
- container: ''
  name: Evaluation
  type: ''
- container: ''
  name: Deployment
  type: ''
- container: ''
  name: Node
  type: ''
- container: ''
  name: NodePool
  type: ''
- container: ''
  name: Service
  type: ''
- container: ''
  name: Namespace
  type: ''
- container: ''
  name: Variable
  type: ''
- container: ''
  name: ACLPolicy
  type: ''
- container: ''
  name: ACLToken
  type: ''
property_count: 13
provider_name: HashiCorp Nomad
provider_slug: nomad
slug: nomad-context
source_filename: nomad-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"nomad\": \"https://developer.hashicorp.com/nomad/ns#\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Job\": {\n      \"@id\": \"nomad:Job\",\n      \"@context\": {\n        \"ID\": \"nomad:jobId\",\n        \"Name\": \"schema:name\",\n        \"Namespace\": \"nomad:namespace\",\n        \"Type\": \"nomad:jobType\",\n        \"Priority\": \"nomad:priority\",\n        \"Region\": \"nomad:region\",\n        \"Datacenters\": {\n          \"@id\": \"nomad:datacenters\",\n          \"@container\": \"@set\"\n        },\n        \"NodePool\": \"nomad:nodePool\",\n        \"Status\": \"nomad:status\",\n        \"StatusDescription\": \"schema:description\",\n        \"Stable\": \"nomad:stable\",\n        \"Version\": \"schema:version\",\n        \"SubmitTime\": {\n          \"@id\": \"dcterms:dateSubmitted\",\n          \"@type\"\
  : \"xsd:long\"\n        },\n        \"Meta\": \"nomad:metadata\",\n        \"TaskGroups\": {\n          \"@id\": \"nomad:taskGroups\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"TaskGroup\": {\n      \"@id\": \"nomad:TaskGroup\",\n      \"@context\": {\n        \"Name\": \"schema:name\",\n        \"Count\": \"nomad:count\",\n        \"Tasks\": {\n          \"@id\": \"nomad:tasks\",\n          \"@container\": \"@set\"\n        },\n        \"Networks\": {\n          \"@id\": \"nomad:networks\",\n          \"@container\": \"@set\"\n        },\n        \"Services\": {\n          \"@id\": \"nomad:services\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Task\": {\n      \"@id\": \"nomad:Task\",\n      \"@context\": {\n        \"Name\": \"schema:name\",\n        \"Driver\": \"nomad:driver\",\n        \"Config\": \"nomad:taskConfig\",\n        \"Env\": \"nomad:environment\",\n        \"Resources\": \"nomad:resources\",\n        \"Leader\"\
  : \"nomad:leader\"\n      }\n    },\n\n    \"Allocation\": {\n      \"@id\": \"nomad:Allocation\",\n      \"@context\": {\n        \"ID\": \"nomad:allocationId\",\n        \"Name\": \"schema:name\",\n        \"Namespace\": \"nomad:namespace\",\n        \"NodeID\": \"nomad:nodeId\",\n        \"NodeName\": \"nomad:nodeName\",\n        \"JobID\": \"nomad:jobId\",\n        \"TaskGroup\": \"nomad:taskGroup\",\n        \"DesiredStatus\": \"nomad:desiredStatus\",\n        \"ClientStatus\": \"nomad:clientStatus\",\n        \"ClientDescription\": \"schema:description\",\n        \"DeploymentID\": \"nomad:deploymentId\",\n        \"CreateTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:long\"\n        },\n        \"ModifyTime\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:long\"\n        }\n      }\n    },\n\n    \"Evaluation\": {\n      \"@id\": \"nomad:Evaluation\",\n      \"@context\": {\n        \"ID\": \"nomad:evaluationId\",\n     \
  \   \"Priority\": \"nomad:priority\",\n        \"Type\": \"nomad:evaluationType\",\n        \"TriggeredBy\": \"nomad:triggeredBy\",\n        \"Namespace\": \"nomad:namespace\",\n        \"JobID\": \"nomad:jobId\",\n        \"NodeID\": \"nomad:nodeId\",\n        \"DeploymentID\": \"nomad:deploymentId\",\n        \"Status\": \"nomad:status\",\n        \"StatusDescription\": \"schema:description\",\n        \"CreateTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:long\"\n        },\n        \"ModifyTime\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:long\"\n        }\n      }\n    },\n\n    \"Deployment\": {\n      \"@id\": \"nomad:Deployment\",\n      \"@context\": {\n        \"ID\": \"nomad:deploymentId\",\n        \"Namespace\": \"nomad:namespace\",\n        \"JobID\": \"nomad:jobId\",\n        \"JobVersion\": \"nomad:jobVersion\",\n        \"Status\": \"nomad:status\",\n        \"StatusDescription\": \"schema:description\",\n \
  \       \"TaskGroups\": \"nomad:deploymentTaskGroups\"\n      }\n    },\n\n    \"Node\": {\n      \"@id\": \"nomad:Node\",\n      \"@context\": {\n        \"ID\": \"nomad:nodeId\",\n        \"Datacenter\": \"nomad:datacenter\",\n        \"Name\": \"schema:name\",\n        \"NodeClass\": \"nomad:nodeClass\",\n        \"NodePool\": \"nomad:nodePool\",\n        \"Drain\": \"nomad:drain\",\n        \"SchedulingEligibility\": \"nomad:schedulingEligibility\",\n        \"Status\": \"nomad:status\",\n        \"StatusDescription\": \"schema:description\",\n        \"HTTPAddr\": {\n          \"@id\": \"nomad:httpAddress\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"NodePool\": {\n      \"@id\": \"nomad:NodePool\",\n      \"@context\": {\n        \"Name\": \"schema:name\",\n        \"Description\": \"schema:description\",\n        \"Meta\": \"nomad:metadata\"\n      }\n    },\n\n    \"Service\": {\n      \"@id\": \"nomad:Service\",\n      \"@context\": {\n        \"ServiceName\"\
  : \"schema:name\",\n        \"Namespace\": \"nomad:namespace\",\n        \"NodeID\": \"nomad:nodeId\",\n        \"Datacenter\": \"nomad:datacenter\",\n        \"JobID\": \"nomad:jobId\",\n        \"AllocID\": \"nomad:allocationId\",\n        \"Tags\": {\n          \"@id\": \"schema:keywords\",\n          \"@container\": \"@set\"\n        },\n        \"Address\": \"nomad:address\",\n        \"Port\": \"nomad:port\"\n      }\n    },\n\n    \"Namespace\": {\n      \"@id\": \"nomad:Namespace\",\n      \"@context\": {\n        \"Name\": \"schema:name\",\n        \"Description\": \"schema:description\",\n        \"Quota\": \"nomad:quota\",\n        \"Meta\": \"nomad:metadata\"\n      }\n    },\n\n    \"Variable\": {\n      \"@id\": \"nomad:Variable\",\n      \"@context\": {\n        \"Namespace\": \"nomad:namespace\",\n        \"Path\": \"nomad:variablePath\",\n        \"Items\": \"nomad:variableItems\",\n        \"CreateTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\"\
  : \"xsd:long\"\n        },\n        \"ModifyTime\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:long\"\n        }\n      }\n    },\n\n    \"ACLPolicy\": {\n      \"@id\": \"nomad:ACLPolicy\",\n      \"@context\": {\n        \"Name\": \"schema:name\",\n        \"Description\": \"schema:description\",\n        \"Rules\": \"nomad:policyRules\"\n      }\n    },\n\n    \"ACLToken\": {\n      \"@id\": \"nomad:ACLToken\",\n      \"@context\": {\n        \"AccessorID\": \"nomad:accessorId\",\n        \"Name\": \"schema:name\",\n        \"Type\": \"nomad:tokenType\",\n        \"Policies\": {\n          \"@id\": \"nomad:policies\",\n          \"@container\": \"@set\"\n        },\n        \"Global\": \"nomad:global\",\n        \"CreateTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"ExpirationTime\": {\n          \"@id\": \"nomad:expirationTime\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n\
  \    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/nomad/refs/heads/main/json-ld/nomad-context.jsonld
tags:
- Workload Orchestration
- Container Orchestration
- Scheduling
- Infrastructure
- DevOps
- JSON-LD
- Linked Data
- Semantic Web
---
