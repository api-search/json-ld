---
class_count: 1
classes:
- UpdateAlarmDetails
context_file: json-ld/oracle-cloud-monitoring-update-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/oracle-cloud/refs/heads/main/json-ld/oracle-cloud-monitoring-update-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Oracle Cloud Monitoring Update from Oracle Cloud Infrastructure.
layout: jsonld
name: Oracle Cloud Monitoring Update Context
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
  name: isEnabled
  type: boolean
- container: ''
  name: query
  type: string
- container: ''
  name: severity
  type: string
property_count: 4
provider_name: Oracle Cloud Infrastructure
provider_slug: oracle-cloud
slug: oracle-cloud-monitoring-update-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"oci\": \"https://docs.oracle.com/en-us/iaas/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"UpdateAlarmDetails\": \"oci:UpdateAlarmDetails\",\n    \"displayName\": {\n      \"@id\": \"oci:displayName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isEnabled\": {\n      \"@id\": \"oci:isEnabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"query\": {\n      \"@id\": \"oci:query\",\n      \"@type\": \"xsd:string\"\n    },\n    \"severity\": {\n      \"@id\": \"oci:severity\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/oracle-cloud/refs/heads/main/json-ld/oracle-cloud-monitoring-update-context.jsonld
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
