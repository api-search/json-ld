---
api_specs:
- filename: oracle-cloud-compute-openapi.yaml
  format: yaml
  label: Compute API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/oracle-cloud/refs/heads/main/openapi/oracle-cloud-compute-openapi.yaml
- filename: oracle-cloud-object-storage-openapi.yaml
  format: yaml
  label: Object Storage API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/oracle-cloud/refs/heads/main/openapi/oracle-cloud-object-storage-openapi.yaml
- filename: oracle-cloud-networking-openapi.yaml
  format: yaml
  label: Networking API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/oracle-cloud/refs/heads/main/openapi/oracle-cloud-networking-openapi.yaml
- filename: oracle-cloud-database-openapi.yaml
  format: yaml
  label: Database API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/oracle-cloud/refs/heads/main/openapi/oracle-cloud-database-openapi.yaml
- filename: oracle-cloud-iam-openapi.yaml
  format: yaml
  label: Identity and Access Management API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/oracle-cloud/refs/heads/main/openapi/oracle-cloud-iam-openapi.yaml
- filename: oracle-cloud-oke-openapi.yaml
  format: yaml
  label: Container Engine for Kubernetes API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/oracle-cloud/refs/heads/main/openapi/oracle-cloud-oke-openapi.yaml
- filename: oracle-cloud-functions-openapi.yaml
  format: yaml
  label: Functions API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/oracle-cloud/refs/heads/main/openapi/oracle-cloud-functions-openapi.yaml
- filename: oracle-cloud-monitoring-openapi.yaml
  format: yaml
  label: Monitoring API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/oracle-cloud/refs/heads/main/openapi/oracle-cloud-monitoring-openapi.yaml
class_count: 3
classes:
- CreatePolicyDetails
- CreateUserDetails
- CreateGroupDetails
context_file: json-ld/oracle-cloud-iam-create-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/oracle-cloud/refs/heads/main/json-ld/oracle-cloud-iam-create-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Oracle Cloud Iam Create from Oracle Cloud Infrastructure.
layout: jsonld
name: Oracle Cloud Iam Create Context
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
- container: ''
  name: description
  type: string
- container: ''
  name: email
  type: string
- container: ''
  name: name
  type: string
- container: set
  name: statements
  type: string
property_count: 5
provider_name: Oracle Cloud Infrastructure
provider_slug: oracle-cloud
slug: oracle-cloud-iam-create-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"oci\": \"https://docs.oracle.com/en-us/iaas/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"CreatePolicyDetails\": \"oci:CreatePolicyDetails\",\n    \"CreateUserDetails\": \"oci:CreateUserDetails\",\n    \"CreateGroupDetails\": \"oci:CreateGroupDetails\",\n    \"compartmentId\": {\n      \"@id\": \"oci:compartmentId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"email\": {\n      \"@id\": \"schema:email\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"statements\": {\n      \"@id\": \"oci:statements\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/oracle-cloud/refs/heads/main/json-ld/oracle-cloud-iam-create-context.jsonld
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
