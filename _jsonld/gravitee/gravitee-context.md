---
api_specs:
- filename: gravitee-management-api-openapi.yml
  format: yaml
  label: Gravitee Management API
  slug: gravitee-management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/gravitee/refs/heads/main/openapi/gravitee-management-api-openapi.yml
- filename: gravitee-access-management-api-openapi.yml
  format: yaml
  label: Gravitee Access Management API
  slug: gravitee-access-management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/gravitee/refs/heads/main/openapi/gravitee-access-management-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/gravitee-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/gravitee/refs/heads/main/json-ld/gravitee-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Gravitee from Gravitee.
layout: jsonld
name: Gravitee Context
namespaces:
- prefix: gravitee
  uri: https://gravitee.io/ns/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Api
  type: ''
- container: ''
  name: Plan
  type: ''
- container: ''
  name: Subscription
  type: ''
- container: ''
  name: Application
  type: ''
- container: ''
  name: Domain
  type: ''
- container: ''
  name: User
  type: ''
- container: ''
  name: Role
  type: ''
- container: ''
  name: IdentityProvider
  type: ''
- container: ''
  name: Flow
  type: ''
- container: ''
  name: AuditEvent
  type: ''
property_count: 10
provider_name: Gravitee
provider_slug: gravitee
slug: gravitee-context
source_filename: gravitee-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"gravitee\": \"https://gravitee.io/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Api\": {\n      \"@id\": \"gravitee:Api\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"version\": \"schema:version\",\n        \"definitionVersion\": \"gravitee:definitionVersion\",\n        \"type\": \"gravitee:apiType\",\n        \"state\": \"gravitee:lifecycleState\",\n        \"visibility\": \"gravitee:visibility\",\n        \"lifecycleState\": \"gravitee:publicationState\",\n        \"tags\": {\n          \"@id\": \"schema:keywords\",\n          \"@container\": \"@set\"\n        },\n        \"labels\": {\n          \"@id\": \"gravitee:labels\",\n          \"@container\": \"@set\"\n        },\n        \"entrypoints\": {\n          \"@id\": \"gravitee:entrypoints\"\
  ,\n          \"@container\": \"@set\"\n        },\n        \"endpoints\": {\n          \"@id\": \"gravitee:endpoints\",\n          \"@container\": \"@set\"\n        },\n        \"deployedAt\": {\n          \"@id\": \"gravitee:deployedAt\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Plan\": {\n      \"@id\": \"gravitee:Plan\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"security\": \"gravitee:securityType\",\n        \"status\": \"gravitee:planStatus\",\n        \"validation\": \"gravitee:validationMode\"\n      }\n    },\n\n    \"Subscription\": {\n      \"@id\": \"gravitee:Subscription\",\n      \"@context\": {\n        \"plan\": \"gravitee:plan\"\
  ,\n        \"application\": \"gravitee:application\",\n        \"status\": \"gravitee:subscriptionStatus\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Application\": {\n      \"@id\": \"gravitee:Application\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"type\": \"gravitee:applicationType\",\n        \"status\": \"gravitee:applicationStatus\",\n        \"settings\": \"gravitee:applicationSettings\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Domain\": {\n      \"@id\": \"gravitee:Domain\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"enabled\": \"gravitee:enabled\",\n        \"path\": \"gravitee:contextPath\",\n        \"oidc\": \"gravitee:oidcConfig\"\
  ,\n        \"scim\": \"gravitee:scimConfig\",\n        \"loginSettings\": \"gravitee:loginSettings\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"User\": {\n      \"@id\": \"gravitee:User\",\n      \"@context\": {\n        \"username\": \"schema:name\",\n        \"email\": \"schema:email\",\n        \"firstName\": \"schema:givenName\",\n        \"lastName\": \"schema:familyName\",\n        \"enabled\": \"gravitee:enabled\",\n        \"roles\": {\n          \"@id\": \"gravitee:roles\",\n          \"@container\": \"@set\"\n        },\n        \"source\": \"gravitee:identitySource\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n      \
  \    \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Role\": {\n      \"@id\": \"gravitee:Role\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"scope\": \"gravitee:roleScope\",\n        \"permissions\": {\n          \"@id\": \"gravitee:permissions\",\n          \"@container\": \"@set\"\n        },\n        \"system\": \"gravitee:systemRole\"\n      }\n    },\n\n    \"IdentityProvider\": {\n      \"@id\": \"gravitee:IdentityProvider\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"type\": \"gravitee:providerType\",\n        \"enabled\": \"gravitee:enabled\",\n        \"configuration\": \"gravitee:providerConfiguration\"\n      }\n    },\n\n    \"Flow\": {\n      \"@id\": \"gravitee:Flow\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"type\": \"gravitee:flowType\",\n        \"enabled\": \"gravitee:enabled\",\n        \"pre\": {\n          \"@id\": \"\
  gravitee:preSteps\",\n          \"@container\": \"@list\"\n        },\n        \"post\": {\n          \"@id\": \"gravitee:postSteps\",\n          \"@container\": \"@list\"\n        }\n      }\n    },\n\n    \"AuditEvent\": {\n      \"@id\": \"gravitee:AuditEvent\",\n      \"@context\": {\n        \"event\": \"gravitee:eventType\",\n        \"referenceType\": \"gravitee:referenceType\",\n        \"referenceId\": \"gravitee:referenceId\",\n        \"user\": \"gravitee:actor\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/gravitee/refs/heads/main/json-ld/gravitee-context.jsonld
tags:
- API Gateway
- API Management
- GraphQL
- Open Source
- JSON-LD
- Linked Data
- Semantic Web
---
