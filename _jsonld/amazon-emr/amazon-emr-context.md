---
class_count: 0
classes: []
context_file: json-ld/amazon-emr-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-emr/refs/heads/main/json-ld/amazon-emr-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Emr from Amazon EMR.
layout: jsonld
name: Amazon Emr Context
namespaces:
- prefix: emr
  uri: https://docs.aws.amazon.com/emr/latest/APIReference/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Cluster
  type: ''
- container: ''
  name: Step
  type: ''
property_count: 2
provider_name: Amazon EMR
provider_slug: amazon-emr
slug: amazon-emr-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"emr\": \"https://docs.aws.amazon.com/emr/latest/APIReference/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Cluster\": {\n      \"@id\": \"emr:Cluster\",\n      \"@context\": {\n        \"id\": \"emr:clusterId\",\n        \"name\": \"schema:name\",\n        \"status\": \"emr:clusterStatus\",\n        \"releaseLabel\": \"emr:releaseLabel\",\n        \"applications\": {\n          \"@id\": \"emr:applications\",\n          \"@container\": \"@set\"\n        },\n        \"instanceCollectionType\": \"emr:instanceCollectionType\",\n        \"logUri\": \"emr:logUri\",\n        \"autoTerminate\": \"emr:autoTerminate\",\n        \"creationDateTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"tags\": {\n          \"@id\": \"emr:tags\",\n          \"@container\": \"\
  @set\"\n        }\n      }\n    },\n\n    \"Step\": {\n      \"@id\": \"emr:Step\",\n      \"@context\": {\n        \"id\": \"emr:stepId\",\n        \"name\": \"schema:name\",\n        \"status\": \"emr:stepStatus\",\n        \"actionOnFailure\": \"emr:actionOnFailure\",\n        \"hadoopJarStep\": \"emr:hadoopJarStep\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-emr/refs/heads/main/json-ld/amazon-emr-context.jsonld
tags:
- Amazon Web Services
- Analytics
- Apache Spark
- AWS
- Big Data
- Data Processing
- Hadoop
- JSON-LD
- Linked Data
- Semantic Web
---
