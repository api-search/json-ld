---
api_specs:
- filename: google-cloud-dataflow-api-openapi.yml
  format: yaml
  label: Google Cloud Dataflow API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-cloud-dataflow/refs/heads/main/openapi/google-cloud-dataflow-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/google-cloud-dataflow-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-cloud-dataflow/refs/heads/main/json-ld/google-cloud-dataflow-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Google Cloud Dataflow from Google Cloud Dataflow.
layout: jsonld
name: Google Cloud Dataflow Context
namespaces:
- prefix: gcd
  uri: https://cloud.google.com/dataflow/docs/reference/rest/v1b3/
- prefix: gcp
  uri: https://cloud.google.com/apis/design/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: rdfs
  uri: http://www.w3.org/2000/01/rdf-schema#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: Job
  type: ''
- container: ''
  name: Environment
  type: ''
- container: ''
  name: WorkerPool
  type: ''
- container: ''
  name: Snapshot
  type: ''
- container: ''
  name: PipelineDescription
  type: ''
- container: ''
  name: TransformSummary
  type: ''
- container: ''
  name: TemplateMetadata
  type: ''
- container: ''
  name: ParameterMetadata
  type: ''
- container: ''
  name: JobMetrics
  type: ''
- container: ''
  name: MetricUpdate
  type: ''
- container: ''
  name: JobMessage
  type: ''
- container: ''
  name: AutoscalingEvent
  type: ''
property_count: 12
provider_name: Google Cloud Dataflow
provider_slug: google-cloud-dataflow
slug: google-cloud-dataflow-context
source_filename: google-cloud-dataflow-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"gcd\": \"https://cloud.google.com/dataflow/docs/reference/rest/v1b3/\",\n    \"gcp\": \"https://cloud.google.com/apis/design/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"rdfs\": \"http://www.w3.org/2000/01/rdf-schema#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Job\": {\n      \"@id\": \"gcd:projects.locations.jobs\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"projectId\": {\n          \"@id\": \"gcp:projectId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"type\": {\n          \"@id\": \"schema:additionalType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"currentState\": {\n          \"@id\"\
  : \"gcd:JobState\",\n          \"@type\": \"xsd:string\"\n        },\n        \"requestedState\": {\n          \"@id\": \"gcd:JobState\",\n          \"@type\": \"xsd:string\"\n        },\n        \"createTime\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"startTime\": {\n          \"@id\": \"schema:startDate\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"currentStateTime\": {\n          \"@id\": \"schema:dateModified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"location\": {\n          \"@id\": \"schema:locationCreated\",\n          \"@type\": \"xsd:string\"\n        },\n        \"labels\": {\n          \"@id\": \"schema:keywords\",\n          \"@type\": \"xsd:string\"\n        },\n        \"environment\": {\n          \"@id\": \"gcd:Environment\",\n          \"@type\": \"@id\"\n        },\n        \"pipelineDescription\": {\n          \"@id\": \"gcd:PipelineDescription\",\n          \"\
  @type\": \"@id\"\n        },\n        \"jobMetadata\": {\n          \"@id\": \"gcd:JobMetadata\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Environment\": {\n      \"@id\": \"gcd:Environment\",\n      \"@context\": {\n        \"tempStoragePrefix\": {\n          \"@id\": \"gcd:tempStoragePrefix\",\n          \"@type\": \"xsd:string\"\n        },\n        \"serviceAccountEmail\": {\n          \"@id\": \"schema:email\",\n          \"@type\": \"xsd:string\"\n        },\n        \"workerRegion\": {\n          \"@id\": \"schema:addressRegion\",\n          \"@type\": \"xsd:string\"\n        },\n        \"workerZone\": {\n          \"@id\": \"gcd:workerZone\",\n          \"@type\": \"xsd:string\"\n        },\n        \"serviceKmsKeyName\": {\n          \"@id\": \"gcd:serviceKmsKeyName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"streamingMode\": {\n          \"@id\": \"gcd:streamingMode\",\n          \"@type\": \"xsd:string\"\n        },\n        \"workerPools\"\
  : {\n          \"@id\": \"gcd:WorkerPool\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"WorkerPool\": {\n      \"@id\": \"gcd:WorkerPool\",\n      \"@context\": {\n        \"kind\": {\n          \"@id\": \"schema:additionalType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"numWorkers\": {\n          \"@id\": \"gcd:numWorkers\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"machineType\": {\n          \"@id\": \"gcd:machineType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"diskSizeGb\": {\n          \"@id\": \"gcd:diskSizeGb\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"diskType\": {\n          \"@id\": \"gcd:diskType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"zone\": {\n          \"@id\": \"gcd:zone\",\n          \"@type\": \"xsd:string\"\n        },\n        \"network\": {\n          \"@id\": \"gcd:network\",\n          \"@type\": \"xsd:string\"\
  \n        },\n        \"subnetwork\": {\n          \"@id\": \"gcd:subnetwork\",\n          \"@type\": \"xsd:string\"\n        },\n        \"ipConfiguration\": {\n          \"@id\": \"gcd:ipConfiguration\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"Snapshot\": {\n      \"@id\": \"gcd:projects.locations.snapshots\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"projectId\": {\n          \"@id\": \"gcp:projectId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"sourceJobId\": {\n          \"@id\": \"gcd:sourceJobId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"creationTime\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"ttl\": {\n          \"@id\": \"gcd:ttl\",\n          \"@type\": \"xsd:duration\"\n        },\n        \"state\": {\n          \"@id\": \"gcd:SnapshotState\"\
  ,\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"diskSizeBytes\": {\n          \"@id\": \"schema:contentSize\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"region\": {\n          \"@id\": \"schema:addressRegion\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"PipelineDescription\": {\n      \"@id\": \"gcd:PipelineDescription\",\n      \"@context\": {\n        \"originalPipelineTransform\": {\n          \"@id\": \"gcd:TransformSummary\",\n          \"@type\": \"@id\",\n          \"@container\": \"@list\"\n        },\n        \"executionPipelineStage\": {\n          \"@id\": \"gcd:ExecutionStageSummary\",\n          \"@type\": \"@id\",\n          \"@container\": \"@list\"\n        }\n      }\n    },\n\n    \"TransformSummary\": {\n      \"@id\": \"gcd:TransformSummary\",\n      \"@context\": {\n        \"kind\"\
  : {\n          \"@id\": \"schema:additionalType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"id\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"TemplateMetadata\": {\n      \"@id\": \"gcd:TemplateMetadata\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"streaming\": {\n          \"@id\": \"gcd:streaming\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"parameters\": {\n          \"@id\": \"gcd:ParameterMetadata\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"ParameterMetadata\": {\n      \"@id\": \"gcd:ParameterMetadata\"\
  ,\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"label\": {\n          \"@id\": \"rdfs:label\",\n          \"@type\": \"xsd:string\"\n        },\n        \"helpText\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"isOptional\": {\n          \"@id\": \"gcd:isOptional\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"paramType\": {\n          \"@id\": \"gcd:paramType\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"JobMetrics\": {\n      \"@id\": \"gcd:JobMetrics\",\n      \"@context\": {\n        \"metricTime\": {\n          \"@id\": \"schema:dateModified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"metrics\": {\n          \"@id\": \"gcd:MetricUpdate\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"MetricUpdate\": {\n\
  \      \"@id\": \"gcd:MetricUpdate\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"gcd:MetricStructuredName\",\n          \"@type\": \"@id\"\n        },\n        \"kind\": {\n          \"@id\": \"schema:additionalType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"cumulative\": {\n          \"@id\": \"gcd:cumulative\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"updateTime\": {\n          \"@id\": \"schema:dateModified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"JobMessage\": {\n      \"@id\": \"gcd:JobMessage\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"time\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"messageText\": {\n          \"@id\": \"schema:text\",\n          \"@type\": \"xsd:string\"\n        },\n        \"messageImportance\"\
  : {\n          \"@id\": \"gcd:JobMessageImportance\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"AutoscalingEvent\": {\n      \"@id\": \"gcd:AutoscalingEvent\",\n      \"@context\": {\n        \"currentNumWorkers\": {\n          \"@id\": \"gcd:currentNumWorkers\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"targetNumWorkers\": {\n          \"@id\": \"gcd:targetNumWorkers\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"eventType\": {\n          \"@id\": \"schema:additionalType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"time\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"workerPool\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-cloud-dataflow/refs/heads/main/json-ld/google-cloud-dataflow-context.jsonld
tags:
- Apache Beam
- Batch Processing
- Big Data
- Data Processing
- ETL
- Stream Processing
- JSON-LD
- Linked Data
- Semantic Web
---
