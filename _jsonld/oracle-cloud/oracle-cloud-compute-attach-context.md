---
class_count: 1
classes:
- AttachVolumeDetails
context_file: json-ld/oracle-cloud-compute-attach-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/oracle-cloud/refs/heads/main/json-ld/oracle-cloud-compute-attach-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Oracle Cloud Compute Attach from Oracle Cloud Infrastructure.
layout: jsonld
name: Oracle Cloud Compute Attach Context
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
  name: instanceId
  type: string
- container: ''
  name: isReadOnly
  type: boolean
- container: ''
  name: type
  type: string
- container: ''
  name: volumeId
  type: string
property_count: 5
provider_name: Oracle Cloud Infrastructure
provider_slug: oracle-cloud
slug: oracle-cloud-compute-attach-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"oci\": \"https://docs.oracle.com/en-us/iaas/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AttachVolumeDetails\": \"oci:AttachVolumeDetails\",\n    \"displayName\": {\n      \"@id\": \"oci:displayName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"instanceId\": {\n      \"@id\": \"oci:instanceId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isReadOnly\": {\n      \"@id\": \"oci:isReadOnly\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"type\": {\n      \"@id\": \"oci:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"volumeId\": {\n      \"@id\": \"oci:volumeId\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/oracle-cloud/refs/heads/main/json-ld/oracle-cloud-compute-attach-context.jsonld
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
