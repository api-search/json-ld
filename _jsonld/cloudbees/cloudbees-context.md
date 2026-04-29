---
class_count: 0
classes: []
context_file: json-ld/cloudbees-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/cloudbees/refs/heads/main/json-ld/cloudbees-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Cloudbees from CloudBees.
layout: jsonld
name: Cloudbees Context
namespaces:
- prefix: cloudbees
  uri: https://api.cloudbees.com/ns/
- prefix: rollout
  uri: https://x-api.rollout.io/public-api/
- prefix: jenkins
  uri: https://www.jenkins.io/doc/book/using/remote-access-api/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Application
  type: ''
- container: ''
  name: Environment
  type: ''
- container: ''
  name: FeatureFlag
  type: ''
- container: ''
  name: TargetGroup
  type: ''
- container: ''
  name: Experiment
  type: ''
- container: ''
  name: AuditEvent
  type: ''
- container: ''
  name: Pipeline
  type: ''
- container: ''
  name: Release
  type: ''
- container: ''
  name: Deployment
  type: ''
- container: ''
  name: Build
  type: ''
- container: ''
  name: Job
  type: ''
property_count: 11
provider_name: CloudBees
provider_slug: cloudbees
slug: cloudbees-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"cloudbees\": \"https://api.cloudbees.com/ns/\",\n    \"rollout\": \"https://x-api.rollout.io/public-api/\",\n    \"jenkins\": \"https://www.jenkins.io/doc/book/using/remote-access-api/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Application\": {\n      \"@id\": \"rollout:Application\",\n      \"@context\": {\n        \"id\": \"rollout:id\",\n        \"name\": \"schema:name\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Environment\": {\n      \"@id\": \"rollout:Environment\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"key\": \"rollout:environment_key\",\n        \"description\": \"schema:description\"\n      }\n    },\n\n    \"FeatureFlag\": {\n      \"@id\": \"rollout:FeatureFlag\",\n   \
  \   \"@context\": {\n        \"id\": \"rollout:id\",\n        \"name\": \"schema:name\",\n        \"type\": \"rollout:flag_type\",\n        \"defaultValue\": \"rollout:default_value\",\n        \"isPermanent\": \"rollout:is_permanent\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"TargetGroup\": {\n      \"@id\": \"rollout:TargetGroup\",\n      \"@context\": {\n        \"id\": \"rollout:id\",\n        \"name\": \"schema:name\",\n        \"conditions\": {\n          \"@id\": \"rollout:conditions\",\n          \"@container\": \"@list\"\n        }\n      }\n    },\n\n    \"Experiment\": {\n      \"@id\": \"rollout:Experiment\",\n      \"@context\": {\n        \"id\": \"rollout:id\",\n        \"name\": \"schema:name\",\n        \"flagId\": \"rollout:flag_id\",\n        \"audience\": \"rollout:audience\",\n        \"variants\": {\n          \"@id\": \"rollout:variants\",\n          \"@container\"\
  : \"@list\"\n        }\n      }\n    },\n\n    \"AuditEvent\": {\n      \"@id\": \"rollout:AuditEvent\",\n      \"@context\": {\n        \"id\": \"rollout:id\",\n        \"actor\": \"schema:agent\",\n        \"action\": \"schema:action\",\n        \"subject\": \"rollout:subject\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Pipeline\": {\n      \"@id\": \"cloudbees:Pipeline\",\n      \"@context\": {\n        \"id\": \"cloudbees:id\",\n        \"name\": \"schema:name\",\n        \"projectName\": \"cloudbees:project_name\",\n        \"stages\": {\n          \"@id\": \"cloudbees:stages\",\n          \"@container\": \"@list\"\n        }\n      }\n    },\n\n    \"Release\": {\n      \"@id\": \"cloudbees:Release\",\n      \"@context\": {\n        \"id\": \"cloudbees:id\",\n        \"name\": \"schema:name\",\n        \"projectName\": \"cloudbees:project_name\",\n        \"status\": \"cloudbees:status\"\
  ,\n        \"plannedStartDate\": {\n          \"@id\": \"schema:scheduledTime\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Deployment\": {\n      \"@id\": \"cloudbees:Deployment\",\n      \"@context\": {\n        \"id\": \"cloudbees:id\",\n        \"applicationName\": \"cloudbees:application_name\",\n        \"environmentName\": \"cloudbees:environment_name\",\n        \"status\": \"cloudbees:status\",\n        \"startedAt\": {\n          \"@id\": \"schema:startTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"endedAt\": {\n          \"@id\": \"schema:endTime\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Build\": {\n      \"@id\": \"jenkins:Build\",\n      \"@context\": {\n        \"number\": \"jenkins:number\",\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"result\": \"jenkins:result\",\n        \"duration\": \"jenkins:duration\",\n     \
  \   \"timestamp\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"actions\": {\n          \"@id\": \"jenkins:actions\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Job\": {\n      \"@id\": \"jenkins:Job\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"color\": \"jenkins:color\",\n        \"lastBuild\": \"jenkins:last_build\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/cloudbees/refs/heads/main/json-ld/cloudbees-context.jsonld
tags:
- CI/CD
- Continuous Delivery
- Continuous Integration
- DevOps
- Feature Flags
- Feature Management
- Jenkins
- Release Orchestration
- Software Delivery
- JSON-LD
- Linked Data
- Semantic Web
---
