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
class_count: 9
classes:
- ObjectSummary
- BucketSummary
- UpdateBucketDetails
- PreauthenticatedRequestSummary
- PreauthenticatedRequest
- Bucket
- ListObjects
- CreateBucketDetails
- CreatePreauthenticatedRequestDetails
context_file: json-ld/oracle-cloud-object-storage-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/oracle-cloud/refs/heads/main/json-ld/oracle-cloud-object-storage-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Oracle Cloud Object Storage from Oracle Cloud Infrastructure.
layout: jsonld
name: Oracle Cloud Object Storage Context
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
  name: accessType
  type: string
- container: ''
  name: accessUri
  type: string
- container: ''
  name: approximateCount
  type: integer
- container: ''
  name: approximateSize
  type: integer
- container: ''
  name: compartmentId
  type: string
- container: ''
  name: createdBy
  type: string
- container: ''
  name: definedTags
  type: ''
- container: ''
  name: etag
  type: string
- container: ''
  name: freeformTags
  type: ''
- container: ''
  name: id
  type: string
- container: ''
  name: md5
  type: string
- container: ''
  name: name
  type: string
- container: ''
  name: namespace
  type: string
- container: ''
  name: nextStartWith
  type: string
- container: ''
  name: objectEventsEnabled
  type: boolean
- container: ''
  name: objectLifecyclePolicyEtag
  type: string
- container: ''
  name: objectName
  type: string
- container: set
  name: objects
  type: reference
- container: set
  name: prefixes
  type: string
- container: ''
  name: publicAccessType
  type: string
- container: ''
  name: size
  type: integer
- container: ''
  name: storageTier
  type: string
- container: ''
  name: timeCreated
  type: dateTime
- container: ''
  name: timeExpires
  type: dateTime
- container: ''
  name: timeModified
  type: dateTime
- container: ''
  name: versioning
  type: string
property_count: 26
provider_name: Oracle Cloud Infrastructure
provider_slug: oracle-cloud
slug: oracle-cloud-object-storage-context
source_filename: oracle-cloud-object-storage-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"oci\": \"https://docs.oracle.com/en-us/iaas/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ObjectSummary\": \"oci:ObjectSummary\",\n    \"BucketSummary\": \"oci:BucketSummary\",\n    \"UpdateBucketDetails\": \"oci:UpdateBucketDetails\",\n    \"PreauthenticatedRequestSummary\": \"oci:PreauthenticatedRequestSummary\",\n    \"PreauthenticatedRequest\": \"oci:PreauthenticatedRequest\",\n    \"Bucket\": \"oci:Bucket\",\n    \"ListObjects\": \"oci:ListObjects\",\n    \"CreateBucketDetails\": \"oci:CreateBucketDetails\",\n    \"CreatePreauthenticatedRequestDetails\": \"oci:CreatePreauthenticatedRequestDetails\",\n    \"accessType\": {\n      \"@id\": \"oci:accessType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accessUri\": {\n      \"@id\": \"oci:accessUri\",\n      \"@type\": \"xsd:string\"\n    },\n    \"approximateCount\"\
  : {\n      \"@id\": \"oci:approximateCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"approximateSize\": {\n      \"@id\": \"oci:approximateSize\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"compartmentId\": {\n      \"@id\": \"oci:compartmentId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdBy\": {\n      \"@id\": \"oci:createdBy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"definedTags\": {\n      \"@id\": \"oci:definedTags\"\n    },\n    \"etag\": {\n      \"@id\": \"oci:etag\",\n      \"@type\": \"xsd:string\"\n    },\n    \"freeformTags\": {\n      \"@id\": \"oci:freeformTags\"\n    },\n    \"id\": {\n      \"@id\": \"oci:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"md5\": {\n      \"@id\": \"oci:md5\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"namespace\": {\n      \"@id\": \"oci:namespace\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nextStartWith\"\
  : {\n      \"@id\": \"oci:nextStartWith\",\n      \"@type\": \"xsd:string\"\n    },\n    \"objectEventsEnabled\": {\n      \"@id\": \"oci:objectEventsEnabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"objectLifecyclePolicyEtag\": {\n      \"@id\": \"oci:objectLifecyclePolicyEtag\",\n      \"@type\": \"xsd:string\"\n    },\n    \"objectName\": {\n      \"@id\": \"oci:objectName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"objects\": {\n      \"@id\": \"oci:objects\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"prefixes\": {\n      \"@id\": \"oci:prefixes\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"publicAccessType\": {\n      \"@id\": \"oci:publicAccessType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"size\": {\n      \"@id\": \"oci:size\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"storageTier\": {\n      \"@id\": \"oci:storageTier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timeCreated\"\
  : {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"timeExpires\": {\n      \"@id\": \"oci:timeExpires\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"timeModified\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"versioning\": {\n      \"@id\": \"oci:versioning\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/oracle-cloud/refs/heads/main/json-ld/oracle-cloud-object-storage-context.jsonld
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
