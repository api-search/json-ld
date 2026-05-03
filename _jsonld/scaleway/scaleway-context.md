---
api_specs:
- filename: scaleway-instance-openapi.yml
  format: yaml
  label: Scaleway Instance API
  slug: scaleway-instance-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/scaleway/refs/heads/main/openapi/scaleway-instance-openapi.yml
- filename: scaleway-kubernetes-openapi.yml
  format: yaml
  label: Scaleway Kubernetes API
  slug: scaleway-kubernetes-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/scaleway/refs/heads/main/openapi/scaleway-kubernetes-openapi.yml
- filename: scaleway-iam-openapi.yml
  format: yaml
  label: Scaleway IAM API
  slug: scaleway-iam-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/scaleway/refs/heads/main/openapi/scaleway-iam-openapi.yml
- filename: scaleway-load-balancer-openapi.yml
  format: yaml
  label: Scaleway Load Balancer API
  slug: scaleway-load-balancer-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/scaleway/refs/heads/main/openapi/scaleway-load-balancer-openapi.yml
- filename: scaleway-database-openapi.yml
  format: yaml
  label: Scaleway Managed Database API
  slug: scaleway-database-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/scaleway/refs/heads/main/openapi/scaleway-database-openapi.yml
- filename: scaleway-vpc-openapi.yml
  format: yaml
  label: Scaleway VPC API
  slug: scaleway-vpc-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/scaleway/refs/heads/main/openapi/scaleway-vpc-openapi.yml
- filename: scaleway-serverless-containers-openapi.yml
  format: yaml
  label: Scaleway Serverless Containers API
  slug: scaleway-serverless-containers-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/scaleway/refs/heads/main/openapi/scaleway-serverless-containers-openapi.yml
- filename: scaleway-serverless-functions-openapi.yml
  format: yaml
  label: Scaleway Serverless Functions API
  slug: scaleway-serverless-functions-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/scaleway/refs/heads/main/openapi/scaleway-serverless-functions-openapi.yml
- filename: scaleway-secret-manager-openapi.yml
  format: yaml
  label: Scaleway Secret Manager API
  slug: scaleway-secret-manager-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/scaleway/refs/heads/main/openapi/scaleway-secret-manager-openapi.yml
- filename: scaleway-transactional-email-openapi.yml
  format: yaml
  label: Scaleway Transactional Email API
  slug: scaleway-transactional-email-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/scaleway/refs/heads/main/openapi/scaleway-transactional-email-openapi.yml
class_count: 1
classes:
- id
context_file: json-ld/scaleway-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/scaleway/refs/heads/main/json-ld/scaleway-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Scaleway from Scaleway.
layout: jsonld
name: Scaleway Context
namespaces:
- prefix: scw
  uri: https://www.scaleway.com/vocabulary/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: hydra
  uri: http://www.w3.org/ns/hydra/core#
properties:
- container: ''
  name: ScalewayInstance
  type: schema:SoftwareApplication
- container: ''
  name: ScalewayCluster
  type: schema:SoftwareApplication
- container: ''
  name: ScalewayProject
  type: schema:Project
- container: ''
  name: ScalewayOrganization
  type: schema:Organization
- container: ''
  name: ScalewaySecret
  type: schema:DigitalDocument
- container: ''
  name: ScalewayDatabase
  type: schema:Dataset
- container: ''
  name: name
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: state
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: zone
  type: string
- container: ''
  name: region
  type: string
- container: ''
  name: project_id
  type: reference
- container: ''
  name: organization_id
  type: reference
- container: ''
  name: commercial_type
  type: string
- container: ''
  name: version
  type: string
- container: list
  name: tags
  type: string
- container: ''
  name: created_at
  type: dateTime
- container: ''
  name: updated_at
  type: dateTime
- container: ''
  name: creation_date
  type: dateTime
- container: ''
  name: modification_date
  type: dateTime
- container: ''
  name: image
  type: schema:SoftwareApplication
- container: ''
  name: volumes
  type: schema:DataDownload
- container: ''
  name: public_ip
  type: schema:IPAddress
- container: ''
  name: private_ip
  type: string
- container: ''
  name: enable_ipv6
  type: boolean
- container: ''
  name: cni
  type: string
- container: ''
  name: cluster_url
  type: reference
- container: ''
  name: per_page
  type: integer
- container: ''
  name: page
  type: integer
- container: ''
  name: total_count
  type: integer
property_count: 31
provider_name: Scaleway
provider_slug: scaleway
slug: scaleway-context
source_filename: scaleway-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"scw\": \"https://www.scaleway.com/vocabulary/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"hydra\": \"http://www.w3.org/ns/hydra/core#\",\n\n    \"ScalewayInstance\": {\n      \"@id\": \"scw:Instance\",\n      \"@type\": \"schema:SoftwareApplication\"\n    },\n    \"ScalewayCluster\": {\n      \"@id\": \"scw:KubernetesCluster\",\n      \"@type\": \"schema:SoftwareApplication\"\n    },\n    \"ScalewayProject\": {\n      \"@id\": \"scw:Project\",\n      \"@type\": \"schema:Project\"\n    },\n    \"ScalewayOrganization\": {\n      \"@id\": \"scw:Organization\",\n      \"@type\": \"schema:Organization\"\n    },\n    \"ScalewaySecret\": {\n      \"@id\": \"scw:Secret\",\n      \"@type\": \"schema:DigitalDocument\"\n    },\n    \"ScalewayDatabase\": {\n      \"@id\": \"scw:Database\",\n      \"@type\": \"schema:Dataset\"\n    },\n\n    \"id\": \"@id\",\n    \"name\": {\n\
  \      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"state\": {\n      \"@id\": \"schema:actionStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"schema:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"zone\": {\n      \"@id\": \"scw:zone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"region\": {\n      \"@id\": \"scw:region\",\n      \"@type\": \"xsd:string\"\n    },\n    \"project_id\": {\n      \"@id\": \"scw:project\",\n      \"@type\": \"@id\"\n    },\n    \"organization_id\": {\n      \"@id\": \"scw:organization\",\n      \"@type\": \"@id\"\n    },\n    \"commercial_type\": {\n      \"@id\": \"scw:instanceType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"version\": {\n      \"@id\": \"schema:version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tags\": {\n      \"@id\": \"schema:keywords\"\
  ,\n      \"@type\": \"xsd:string\",\n      \"@container\": \"@list\"\n    },\n    \"created_at\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updated_at\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"creation_date\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"modification_date\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"image\": {\n      \"@id\": \"scw:osImage\",\n      \"@type\": \"schema:SoftwareApplication\"\n    },\n    \"volumes\": {\n      \"@id\": \"scw:storageVolume\",\n      \"@type\": \"schema:DataDownload\"\n    },\n    \"public_ip\": {\n      \"@id\": \"scw:publicIP\",\n      \"@type\": \"schema:IPAddress\"\n    },\n    \"private_ip\": {\n      \"@id\": \"scw:privateIP\",\n      \"@type\": \"xsd:string\"\n    },\n    \"enable_ipv6\": {\n      \"@id\": \"scw:ipv6Enabled\",\n     \
  \ \"@type\": \"xsd:boolean\"\n    },\n    \"cni\": {\n      \"@id\": \"scw:containerNetworkInterface\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cluster_url\": {\n      \"@id\": \"scw:apiEndpoint\",\n      \"@type\": \"@id\"\n    },\n    \"per_page\": {\n      \"@id\": \"hydra:limit\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"page\": {\n      \"@id\": \"hydra:pageIndex\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"total_count\": {\n      \"@id\": \"hydra:totalItems\",\n      \"@type\": \"xsd:integer\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/scaleway/refs/heads/main/json-ld/scaleway-context.jsonld
tags:
- AI
- Cloud Computing
- Containers
- Database
- European Cloud
- Infrastructure
- Kubernetes
- Serverless
- Storage
- JSON-LD
- Linked Data
- Semantic Web
---
