---
class_count: 1
classes:
- SummarizeMetricsDataDetails
context_file: json-ld/oracle-cloud-monitoring-summarize-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/oracle-cloud/refs/heads/main/json-ld/oracle-cloud-monitoring-summarize-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Oracle Cloud Monitoring Summarize from Oracle Cloud Infrastructure.
layout: jsonld
name: Oracle Cloud Monitoring Summarize Context
namespaces:
- prefix: oci
  uri: https://docs.oracle.com/en-us/iaas/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: endTime
  type: dateTime
- container: ''
  name: namespace
  type: string
- container: ''
  name: query
  type: string
- container: ''
  name: resolution
  type: string
- container: ''
  name: startTime
  type: dateTime
property_count: 5
provider_name: Oracle Cloud Infrastructure
provider_slug: oracle-cloud
slug: oracle-cloud-monitoring-summarize-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"oci\": \"https://docs.oracle.com/en-us/iaas/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"SummarizeMetricsDataDetails\": \"oci:SummarizeMetricsDataDetails\",\n    \"endTime\": {\n      \"@id\": \"oci:endTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"namespace\": {\n      \"@id\": \"oci:namespace\",\n      \"@type\": \"xsd:string\"\n    },\n    \"query\": {\n      \"@id\": \"oci:query\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resolution\": {\n      \"@id\": \"oci:resolution\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startTime\": {\n      \"@id\": \"oci:startTime\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/oracle-cloud/refs/heads/main/json-ld/oracle-cloud-monitoring-summarize-context.jsonld
tags:
- Cloud Computing
- Enterprise Cloud
- Infrastructure as a Service
- Oracle
- Platform as a Service
- JSON-LD
- Linked Data
- Semantic Web
---
