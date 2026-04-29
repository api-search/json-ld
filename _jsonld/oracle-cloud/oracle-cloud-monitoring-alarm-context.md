---
class_count: 1
classes:
- AlarmSummary
context_file: json-ld/oracle-cloud-monitoring-alarm-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/oracle-cloud/refs/heads/main/json-ld/oracle-cloud-monitoring-alarm-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Oracle Cloud Monitoring Alarm from Oracle Cloud Infrastructure.
layout: jsonld
name: Oracle Cloud Monitoring Alarm Context
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
  name: displayName
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: isEnabled
  type: boolean
- container: ''
  name: lifecycleState
  type: string
- container: ''
  name: severity
  type: string
property_count: 5
provider_name: Oracle Cloud Infrastructure
provider_slug: oracle-cloud
slug: oracle-cloud-monitoring-alarm-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"oci\": \"https://docs.oracle.com/en-us/iaas/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AlarmSummary\": \"oci:AlarmSummary\",\n    \"displayName\": {\n      \"@id\": \"oci:displayName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"oci:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isEnabled\": {\n      \"@id\": \"oci:isEnabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"lifecycleState\": {\n      \"@id\": \"oci:lifecycleState\",\n      \"@type\": \"xsd:string\"\n    },\n    \"severity\": {\n      \"@id\": \"oci:severity\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/oracle-cloud/refs/heads/main/json-ld/oracle-cloud-monitoring-alarm-context.jsonld
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
