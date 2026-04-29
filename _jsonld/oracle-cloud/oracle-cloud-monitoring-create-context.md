---
class_count: 1
classes:
- CreateAlarmDetails
context_file: json-ld/oracle-cloud-monitoring-create-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/oracle-cloud/refs/heads/main/json-ld/oracle-cloud-monitoring-create-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Oracle Cloud Monitoring Create from Oracle Cloud Infrastructure.
layout: jsonld
name: Oracle Cloud Monitoring Create Context
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
  name: compartmentId
  type: string
- container: set
  name: destinations
  type: string
- container: ''
  name: displayName
  type: string
- container: ''
  name: isEnabled
  type: boolean
- container: ''
  name: metricCompartmentId
  type: string
- container: ''
  name: namespace
  type: string
- container: ''
  name: query
  type: string
- container: ''
  name: severity
  type: string
property_count: 8
provider_name: Oracle Cloud Infrastructure
provider_slug: oracle-cloud
slug: oracle-cloud-monitoring-create-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"oci\": \"https://docs.oracle.com/en-us/iaas/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"CreateAlarmDetails\": \"oci:CreateAlarmDetails\",\n    \"compartmentId\": {\n      \"@id\": \"oci:compartmentId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"destinations\": {\n      \"@id\": \"oci:destinations\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"displayName\": {\n      \"@id\": \"oci:displayName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isEnabled\": {\n      \"@id\": \"oci:isEnabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"metricCompartmentId\": {\n      \"@id\": \"oci:metricCompartmentId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"namespace\": {\n      \"@id\": \"oci:namespace\",\n      \"@type\": \"xsd:string\"\n    },\n    \"query\": {\n\
  \      \"@id\": \"oci:query\",\n      \"@type\": \"xsd:string\"\n    },\n    \"severity\": {\n      \"@id\": \"oci:severity\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/oracle-cloud/refs/heads/main/json-ld/oracle-cloud-monitoring-create-context.jsonld
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
