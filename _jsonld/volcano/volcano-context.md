---
api_specs:
- filename: volcano-job-openapi.yml
  format: yaml
  label: Volcano Batch Scheduling API
  slug: volcano-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/volcano/refs/heads/main/openapi/volcano-job-openapi.yml
- filename: volcano-queue-openapi.yml
  format: yaml
  label: Volcano Queue API
  slug: volcano-queue-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/volcano/refs/heads/main/openapi/volcano-queue-openapi.yml
- filename: volcano-podgroup-openapi.yml
  format: yaml
  label: Volcano PodGroup API
  slug: volcano-podgroup-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/volcano/refs/heads/main/openapi/volcano-podgroup-openapi.yml
class_count: 0
classes: []
context_file: json-ld/volcano-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/volcano/refs/heads/main/json-ld/volcano-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Volcano from Volcano.
layout: jsonld
name: Volcano Context
namespaces:
- prefix: volcano
  uri: https://volcano.sh/vocabulary#
- prefix: k8s
  uri: https://kubernetes.io/vocabulary#
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: prov
  uri: http://www.w3.org/ns/prov#
properties:
- container: ''
  name: Job
  type: ''
- container: ''
  name: TaskSpec
  type: ''
- container: ''
  name: Queue
  type: ''
- container: ''
  name: QueueStatus
  type: ''
- container: ''
  name: PodGroup
  type: ''
- container: ''
  name: LifecyclePolicy
  type: ''
- container: ''
  name: JobStatus
  type: ''
property_count: 7
provider_name: Volcano
provider_slug: volcano
slug: volcano-context
source_filename: volcano-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"volcano\": \"https://volcano.sh/vocabulary#\",\n    \"k8s\": \"https://kubernetes.io/vocabulary#\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"prov\": \"http://www.w3.org/ns/prov#\",\n\n    \"Job\": {\n      \"@id\": \"volcano:Job\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"namespace\": \"k8s:namespace\",\n        \"queue\": {\n          \"@id\": \"volcano:queue\",\n          \"@type\": \"@id\"\n        },\n        \"minAvailable\": \"volcano:minAvailable\",\n        \"tasks\": {\n          \"@id\": \"volcano:tasks\",\n          \"@container\": \"@set\"\n        },\n        \"policies\": {\n          \"@id\": \"volcano:lifecyclePolicies\",\n          \"@container\": \"@set\"\n        },\n        \"plugins\": \"volcano:plugins\",\n        \"maxRetry\": \"volcano:maxRetry\",\n        \"schedulerName\"\
  : \"volcano:schedulerName\",\n        \"creationTimestamp\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"TaskSpec\": {\n      \"@id\": \"volcano:Task\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"replicas\": \"volcano:replicaCount\",\n        \"policies\": {\n          \"@id\": \"volcano:lifecyclePolicies\",\n          \"@container\": \"@set\"\n        },\n        \"topologyPolicy\": \"volcano:topologyPolicy\",\n        \"maxRetry\": \"volcano:maxRetry\",\n        \"dependsOn\": \"volcano:taskDependencies\"\n      }\n    },\n\n    \"Queue\": {\n      \"@id\": \"volcano:Queue\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"weight\": \"volcano:schedulingWeight\",\n        \"capability\": \"volcano:resourceCapacity\",\n        \"reclaimable\": \"volcano:isReclaimable\",\n        \"state\": \"volcano:queueState\",\n        \"guarantee\": \"volcano:guaranteedResources\"\
  ,\n        \"parent\": {\n          \"@id\": \"volcano:parentQueue\",\n          \"@type\": \"@id\"\n        },\n        \"creationTimestamp\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"QueueStatus\": {\n      \"@id\": \"volcano:QueueStatus\",\n      \"@context\": {\n        \"state\": \"volcano:queueState\",\n        \"pending\": \"volcano:pendingCount\",\n        \"running\": \"volcano:runningCount\",\n        \"inqueue\": \"volcano:inqueuedCount\",\n        \"allocated\": \"volcano:allocatedResources\",\n        \"guaranteed\": \"volcano:guaranteedResources\"\n      }\n    },\n\n    \"PodGroup\": {\n      \"@id\": \"volcano:PodGroup\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"namespace\": \"k8s:namespace\",\n        \"minMember\": \"volcano:minMember\",\n        \"minResources\": \"volcano:minimumResources\",\n        \"queue\": {\n          \"@id\": \"volcano:queue\",\n       \
  \   \"@type\": \"@id\"\n        },\n        \"priorityClassName\": \"k8s:priorityClass\",\n        \"phase\": \"volcano:podGroupPhase\",\n        \"occupiedBy\": {\n          \"@id\": \"volcano:ownerJob\",\n          \"@type\": \"@id\"\n        },\n        \"creationTimestamp\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"LifecyclePolicy\": {\n      \"@id\": \"volcano:LifecyclePolicy\",\n      \"@context\": {\n        \"action\": \"volcano:policyAction\",\n        \"event\": \"volcano:triggerEvent\",\n        \"events\": {\n          \"@id\": \"volcano:triggerEvents\",\n          \"@container\": \"@set\"\n        },\n        \"exitCode\": \"volcano:triggerExitCode\",\n        \"timeout\": \"volcano:policyTimeout\"\n      }\n    },\n\n    \"JobStatus\": {\n      \"@id\": \"volcano:JobStatus\",\n      \"@context\": {\n        \"phase\": \"volcano:jobPhase\",\n        \"retryCount\": \"volcano:retryCount\",\n     \
  \   \"runningDuration\": {\n          \"@id\": \"schema:duration\",\n          \"@type\": \"xsd:string\"\n        },\n        \"minAvailable\": \"volcano:minAvailable\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/volcano/refs/heads/main/json-ld/volcano-context.jsonld
tags:
- Batch Processing
- Cloud Native
- HPC
- Incubating
- Kubernetes
- Scheduling
- JSON-LD
- Linked Data
- Semantic Web
---
