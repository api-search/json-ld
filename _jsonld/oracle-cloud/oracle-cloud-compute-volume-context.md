---
class_count: 1
classes:
- VolumeAttachment
context_file: json-ld/oracle-cloud-compute-volume-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/oracle-cloud/refs/heads/main/json-ld/oracle-cloud-compute-volume-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Oracle Cloud Compute Volume from Oracle Cloud Infrastructure.
layout: jsonld
name: Oracle Cloud Compute Volume Context
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
  name: attachmentType
  type: string
- container: ''
  name: displayName
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: instanceId
  type: string
- container: ''
  name: lifecycleState
  type: string
- container: ''
  name: timeCreated
  type: dateTime
- container: ''
  name: volumeId
  type: string
property_count: 7
provider_name: Oracle Cloud Infrastructure
provider_slug: oracle-cloud
slug: oracle-cloud-compute-volume-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"oci\": \"https://docs.oracle.com/en-us/iaas/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"VolumeAttachment\": \"oci:VolumeAttachment\",\n    \"attachmentType\": {\n      \"@id\": \"oci:attachmentType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"displayName\": {\n      \"@id\": \"oci:displayName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"oci:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"instanceId\": {\n      \"@id\": \"oci:instanceId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lifecycleState\": {\n      \"@id\": \"oci:lifecycleState\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timeCreated\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"volumeId\": {\n      \"@id\": \"oci:volumeId\",\n      \"@type\": \"\
  xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/oracle-cloud/refs/heads/main/json-ld/oracle-cloud-compute-volume-context.jsonld
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
