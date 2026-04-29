---
api_specs:
- filename: spot-administration-api-openapi.yml
  format: yaml
  label: Spot Administration API
  slug: administration-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/spot/refs/heads/main/openapi/spot-administration-api-openapi.yml
- filename: spot-elastigroup-api-openapi.yml
  format: yaml
  label: Spot Elastigroup API
  slug: elastigroup-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/spot/refs/heads/main/openapi/spot-elastigroup-api-openapi.yml
- filename: spot-ocean-api-openapi.yml
  format: yaml
  label: Spot Ocean API
  slug: ocean-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/spot/refs/heads/main/openapi/spot-ocean-api-openapi.yml
- filename: spot-eco-api-openapi.yml
  format: yaml
  label: Spot Eco API
  slug: eco-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/spot/refs/heads/main/openapi/spot-eco-api-openapi.yml
- filename: spot-billing-engine-api-openapi.yml
  format: yaml
  label: Spot Billing Engine API
  slug: billing-engine-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/spot/refs/heads/main/openapi/spot-billing-engine-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/spot-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/spot/refs/heads/main/json-ld/spot-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Spot from Spot.
layout: jsonld
name: Spot Context
namespaces:
- prefix: spot
  uri: https://docs.spot.io/api/
properties:
- container: ''
  name: Organization
  type: ''
- container: ''
  name: Account
  type: ''
- container: ''
  name: User
  type: ''
- container: ''
  name: AccessPolicy
  type: ''
- container: ''
  name: Elastigroup
  type: ''
- container: ''
  name: OceanCluster
  type: ''
- container: ''
  name: VirtualNodeGroup
  type: ''
- container: ''
  name: Subscription
  type: ''
- container: ''
  name: CommitmentPlan
  type: ''
property_count: 9
provider_name: Spot
provider_slug: spot
slug: spot-context
source_filename: spot-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"spot\": \"https://docs.spot.io/api/\",\n    \"Organization\": {\n      \"@id\": \"spot:organization\",\n      \"@context\": {\n        \"id\": \"https://schema.org/identifier\",\n        \"name\": \"https://schema.org/name\"\n      }\n    },\n    \"Account\": {\n      \"@id\": \"spot:account\",\n      \"@context\": {\n        \"id\": \"https://schema.org/identifier\",\n        \"name\": \"https://schema.org/name\",\n        \"organizationId\": {\n          \"@id\": \"spot:organization\",\n          \"@type\": \"@id\"\n        },\n        \"cloudAccountId\": \"https://schema.org/identifier\"\n      }\n    },\n    \"User\": {\n      \"@id\": \"spot:user\",\n      \"@context\": {\n        \"userId\": \"https://schema.org/identifier\",\n        \"username\": \"https://schema.org/alternateName\",\n        \"email\": \"https://schema.org/email\",\n        \"firstName\": \"https://schema.org/givenName\",\n     \
  \   \"lastName\": \"https://schema.org/familyName\",\n        \"type\": \"https://schema.org/category\",\n        \"role\": \"https://schema.org/roleName\",\n        \"organizationId\": {\n          \"@id\": \"spot:organization\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n    \"AccessPolicy\": {\n      \"@id\": \"spot:access-policy\",\n      \"@context\": {\n        \"id\": \"https://schema.org/identifier\",\n        \"name\": \"https://schema.org/name\",\n        \"description\": \"https://schema.org/description\",\n        \"permissions\": \"https://schema.org/hasDigitalDocumentPermission\"\n      }\n    },\n    \"Elastigroup\": {\n      \"@id\": \"spot:elastigroup\",\n      \"@context\": {\n        \"id\": \"https://schema.org/identifier\",\n        \"name\": \"https://schema.org/name\",\n        \"description\": \"https://schema.org/description\",\n        \"region\": \"https://schema.org/locationCreated\",\n        \"capacity\": \"https://schema.org/value\",\n   \
  \     \"strategy\": \"https://schema.org/actionOption\",\n        \"compute\": \"https://schema.org/hasPart\",\n        \"createdAt\": \"https://schema.org/dateCreated\",\n        \"updatedAt\": \"https://schema.org/dateModified\"\n      }\n    },\n    \"OceanCluster\": {\n      \"@id\": \"spot:ocean-cluster\",\n      \"@context\": {\n        \"id\": \"https://schema.org/identifier\",\n        \"name\": \"https://schema.org/name\",\n        \"controllerClusterId\": \"https://schema.org/identifier\",\n        \"region\": \"https://schema.org/locationCreated\",\n        \"autoScaler\": \"https://schema.org/actionOption\",\n        \"capacity\": \"https://schema.org/value\",\n        \"strategy\": \"https://schema.org/actionOption\",\n        \"createdAt\": \"https://schema.org/dateCreated\",\n        \"updatedAt\": \"https://schema.org/dateModified\"\n      }\n    },\n    \"VirtualNodeGroup\": {\n      \"@id\": \"spot:virtual-node-group\",\n      \"@context\": {\n        \"id\": \"https://schema.org/identifier\"\
  ,\n        \"name\": \"https://schema.org/name\",\n        \"oceanId\": {\n          \"@id\": \"spot:ocean-cluster\",\n          \"@type\": \"@id\"\n        },\n        \"labels\": \"https://schema.org/keywords\",\n        \"taints\": \"https://schema.org/actionOption\"\n      }\n    },\n    \"Subscription\": {\n      \"@id\": \"spot:subscription\",\n      \"@context\": {\n        \"id\": \"https://schema.org/identifier\",\n        \"resourceId\": \"https://schema.org/identifier\",\n        \"protocol\": \"https://schema.org/encodingFormat\",\n        \"endpoint\": \"https://schema.org/url\",\n        \"eventType\": \"https://schema.org/category\"\n      }\n    },\n    \"CommitmentPlan\": {\n      \"@id\": \"spot:commitment-plan\",\n      \"@context\": {\n        \"id\": \"https://schema.org/identifier\",\n        \"type\": \"https://schema.org/category\",\n        \"provider\": \"https://schema.org/provider\",\n        \"status\": \"https://schema.org/status\",\n        \"startDate\"\
  : \"https://schema.org/startDate\",\n        \"endDate\": \"https://schema.org/endDate\",\n        \"monthlySavings\": \"https://schema.org/price\",\n        \"utilizationPercentage\": \"https://schema.org/value\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/spot/refs/heads/main/json-ld/spot-context.jsonld
tags:
- Autoscaling
- Cloud Infrastructure
- Containers
- Cost Optimization
- FinOps
- Kubernetes
- Spot Instances
- JSON-LD
- Linked Data
- Semantic Web
---
