---
api_specs:
- filename: cloud-dataproc-openapi.yml
  format: yaml
  label: Cloud Dataproc API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-cloud-dataproc/refs/heads/main/openapi/cloud-dataproc-openapi.yml
class_count: 21
classes:
- Cluster
- Job
- WorkflowTemplate
- Operation
- clusterName
- description
- state
- projectId
- labels
- createTime
- updateTime
- region
- machineTypeUri
- numInstances
- imageVersion
- clusterUuid
- jobId
- sparkJob
- hadoopJob
- pysparkJob
- hiveJob
context_file: json-ld/google-cloud-dataproc-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-cloud-dataproc/refs/heads/main/json-ld/google-cloud-dataproc-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Google Cloud Dataproc from Google Cloud Dataproc.
layout: jsonld
name: Google Cloud Dataproc Context
namespaces:
- prefix: dataproc
  uri: https://cloud.google.com/dataproc/docs/reference/rest/v1/
- prefix: gcloud
  uri: https://cloud.google.com/apis/
properties: []
property_count: 0
provider_name: Google Cloud Dataproc
provider_slug: google-cloud-dataproc
slug: google-cloud-dataproc-context
source_filename: google-cloud-dataproc-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"dataproc\": \"https://cloud.google.com/dataproc/docs/reference/rest/v1/\",\n    \"gcloud\": \"https://cloud.google.com/apis/\",\n    \"Cluster\": \"dataproc:projects.regions.clusters\",\n    \"Job\": \"dataproc:projects.regions.jobs\",\n    \"WorkflowTemplate\": \"dataproc:projects.regions.workflowTemplates\",\n    \"Operation\": \"dataproc:projects.regions.operations\",\n    \"clusterName\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"state\": \"dataproc:state\",\n    \"projectId\": \"gcloud:project\",\n    \"labels\": \"schema:keywords\",\n    \"createTime\": \"schema:dateCreated\",\n    \"updateTime\": \"schema:dateModified\",\n    \"region\": \"schema:location\",\n    \"machineTypeUri\": \"dataproc:machineType\",\n    \"numInstances\": \"dataproc:numInstances\",\n    \"imageVersion\": \"schema:softwareVersion\",\n    \"clusterUuid\": \"schema:identifier\",\n    \"jobId\": \"\
  schema:identifier\",\n    \"sparkJob\": \"dataproc:sparkJob\",\n    \"hadoopJob\": \"dataproc:hadoopJob\",\n    \"pysparkJob\": \"dataproc:pysparkJob\",\n    \"hiveJob\": \"dataproc:hiveJob\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-cloud-dataproc/refs/heads/main/json-ld/google-cloud-dataproc-context.jsonld
tags:
- Big Data
- Data Processing
- Google Cloud
- Hadoop
- Spark
- JSON-LD
- Linked Data
- Semantic Web
---
