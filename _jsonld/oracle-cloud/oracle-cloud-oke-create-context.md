---
class_count: 2
classes:
- CreateClusterDetails
- CreateNodePoolDetails
context_file: json-ld/oracle-cloud-oke-create-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/oracle-cloud/refs/heads/main/json-ld/oracle-cloud-oke-create-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Oracle Cloud Oke Create from Oracle Cloud Infrastructure.
layout: jsonld
name: Oracle Cloud Oke Create Context
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
  name: clusterId
  type: string
- container: ''
  name: compartmentId
  type: string
- container: ''
  name: kubernetesVersion
  type: string
- container: ''
  name: name
  type: string
- container: ''
  name: nodeShape
  type: string
- container: ''
  name: quantityPerSubnet
  type: integer
- container: ''
  name: vcnId
  type: string
property_count: 7
provider_name: Oracle Cloud Infrastructure
provider_slug: oracle-cloud
slug: oracle-cloud-oke-create-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"oci\": \"https://docs.oracle.com/en-us/iaas/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"CreateClusterDetails\": \"oci:CreateClusterDetails\",\n    \"CreateNodePoolDetails\": \"oci:CreateNodePoolDetails\",\n    \"clusterId\": {\n      \"@id\": \"oci:clusterId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"compartmentId\": {\n      \"@id\": \"oci:compartmentId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"kubernetesVersion\": {\n      \"@id\": \"oci:kubernetesVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nodeShape\": {\n      \"@id\": \"oci:nodeShape\",\n      \"@type\": \"xsd:string\"\n    },\n    \"quantityPerSubnet\": {\n      \"@id\": \"oci:quantityPerSubnet\",\n      \"@type\": \"xsd:integer\"\
  \n    },\n    \"vcnId\": {\n      \"@id\": \"oci:vcnId\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/oracle-cloud/refs/heads/main/json-ld/oracle-cloud-oke-create-context.jsonld
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
