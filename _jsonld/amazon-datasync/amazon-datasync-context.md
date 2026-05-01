---
api_specs:
- filename: amazon-datasync-api-openapi.yml
  format: yaml
  label: Amazon DataSync REST API
  slug: amazon-datasync-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-datasync/refs/heads/main/openapi/amazon-datasync-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/amazon-datasync-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-datasync/refs/heads/main/json-ld/amazon-datasync-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Datasync from Amazon DataSync.
layout: jsonld
name: Amazon Datasync Context
namespaces:
- prefix: datasync
  uri: https://docs.aws.amazon.com/datasync/latest/userguide/
- prefix: aws
  uri: https://aws.amazon.com/
- prefix: iam
  uri: https://docs.aws.amazon.com/IAM/latest/UserGuide/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: schema
  uri: https://schema.org/
properties:
- container: ''
  name: Task
  type: ''
- container: ''
  name: Location
  type: ''
- container: ''
  name: Agent
  type: ''
property_count: 3
provider_name: Amazon DataSync
provider_slug: amazon-datasync
slug: amazon-datasync-context
source_filename: amazon-datasync-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"@vocab\": \"https://schema.org/\",\n    \"datasync\": \"https://docs.aws.amazon.com/datasync/latest/userguide/\",\n    \"aws\": \"https://aws.amazon.com/\",\n    \"iam\": \"https://docs.aws.amazon.com/IAM/latest/UserGuide/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"schema\": \"https://schema.org/\",\n\n    \"Task\": {\n      \"@id\": \"datasync:API_DescribeTask.html\",\n      \"@context\": {\n        \"TaskArn\": {\n          \"@id\": \"aws:arn\",\n          \"@type\": \"@id\"\n        },\n        \"Name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"Status\": {\n          \"@id\": \"datasync:TaskStatus\",\n          \"@type\": \"xsd:string\"\n        },\n        \"SourceLocationArn\": {\n          \"@id\": \"datasync:SourceLocation\",\n          \"@type\": \"@id\"\n        },\n        \"DestinationLocationArn\"\
  : {\n          \"@id\": \"datasync:DestinationLocation\",\n          \"@type\": \"@id\"\n        },\n        \"CreationTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Location\": {\n      \"@id\": \"datasync:API_DescribeLocationS3.html\",\n      \"@context\": {\n        \"LocationArn\": {\n          \"@id\": \"aws:arn\",\n          \"@type\": \"@id\"\n        },\n        \"LocationUri\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"CreationTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Agent\": {\n      \"@id\": \"datasync:API_DescribeAgent.html\",\n      \"@context\": {\n        \"AgentArn\": {\n          \"@id\": \"aws:arn\",\n          \"@type\": \"@id\"\n        },\n        \"Name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"\
  Status\": {\n          \"@id\": \"datasync:AgentStatus\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-datasync/refs/heads/main/json-ld/amazon-datasync-context.jsonld
tags:
- Data Transfer
- Migration
- Storage
- Automation
- Hybrid Cloud
- JSON-LD
- Linked Data
- Semantic Web
---
