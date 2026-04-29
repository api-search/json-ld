---
class_count: 1
classes:
- UpdateInstanceDetails
context_file: json-ld/oracle-cloud-compute-update-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/oracle-cloud/refs/heads/main/json-ld/oracle-cloud-compute-update-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Oracle Cloud Compute Update from Oracle Cloud Infrastructure.
layout: jsonld
name: Oracle Cloud Compute Update Context
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
  name: freeformTags
  type: ''
- container: ''
  name: shape
  type: string
- container: ''
  name: shapeConfig
  type: ''
property_count: 4
provider_name: Oracle Cloud Infrastructure
provider_slug: oracle-cloud
slug: oracle-cloud-compute-update-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"oci\": \"https://docs.oracle.com/en-us/iaas/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"UpdateInstanceDetails\": \"oci:UpdateInstanceDetails\",\n    \"displayName\": {\n      \"@id\": \"oci:displayName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"freeformTags\": {\n      \"@id\": \"oci:freeformTags\"\n    },\n    \"shape\": {\n      \"@id\": \"oci:shape\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shapeConfig\": {\n      \"@id\": \"oci:shapeConfig\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/oracle-cloud/refs/heads/main/json-ld/oracle-cloud-compute-update-context.jsonld
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
