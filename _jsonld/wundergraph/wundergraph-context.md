---
api_specs:
- filename: wundergraph-cosmo-platform-openapi.yml
  format: yaml
  label: WunderGraph Cosmo Platform API
  slug: cosmo-platform
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/wundergraph/refs/heads/main/openapi/wundergraph-cosmo-platform-openapi.yml
class_count: 0
classes: []
context_file: json-ld/wundergraph-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/wundergraph/refs/heads/main/json-ld/wundergraph-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Wundergraph from WunderGraph.
layout: jsonld
name: Wundergraph Context
namespaces:
- prefix: cosmo
  uri: https://cosmo-docs.wundergraph.com/
properties:
- container: ''
  name: Namespace
  type: ''
- container: ''
  name: FederatedGraph
  type: ''
- container: ''
  name: Subgraph
  type: ''
- container: ''
  name: Monograph
  type: ''
- container: ''
  name: SchemaContract
  type: ''
- container: ''
  name: FeatureFlag
  type: ''
- container: ''
  name: RouterToken
  type: ''
- container: ''
  name: APIKey
  type: ''
- container: ''
  name: ChangelogEntry
  type: ''
- container: ''
  name: OperationResponse
  type: ''
property_count: 10
provider_name: WunderGraph
provider_slug: wundergraph
slug: wundergraph-context
source_filename: wundergraph-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"cosmo\": \"https://cosmo-docs.wundergraph.com/\",\n    \"Namespace\": {\n      \"@id\": \"cosmo:cli/namespace\",\n      \"@context\": {\n        \"id\": \"https://schema.org/identifier\",\n        \"name\": \"https://schema.org/name\",\n        \"createdAt\": \"https://schema.org/dateCreated\"\n      }\n    },\n    \"FederatedGraph\": {\n      \"@id\": \"cosmo:cli/federated-graph\",\n      \"@context\": {\n        \"id\": \"https://schema.org/identifier\",\n        \"name\": \"https://schema.org/name\",\n        \"namespace\": {\n          \"@id\": \"cosmo:cli/namespace\",\n          \"@type\": \"@id\"\n        },\n        \"routingUrl\": \"https://schema.org/url\",\n        \"labelMatchers\": \"https://schema.org/keywords\",\n        \"compositionStatus\": \"https://schema.org/status\",\n        \"lastComposedAt\": \"https://schema.org/dateModified\",\n        \"subgraphsCount\": \"https://schema.org/numberOfItems\"\
  ,\n        \"readme\": \"https://schema.org/description\",\n        \"createdAt\": \"https://schema.org/dateCreated\",\n        \"updatedAt\": \"https://schema.org/dateModified\"\n      }\n    },\n    \"Subgraph\": {\n      \"@id\": \"cosmo:cli/subgraph\",\n      \"@context\": {\n        \"id\": \"https://schema.org/identifier\",\n        \"name\": \"https://schema.org/name\",\n        \"namespace\": {\n          \"@id\": \"cosmo:cli/namespace\",\n          \"@type\": \"@id\"\n        },\n        \"routingUrl\": \"https://schema.org/url\",\n        \"labels\": \"https://schema.org/keywords\",\n        \"subscriptionUrl\": \"https://schema.org/url\",\n        \"subscriptionProtocol\": \"https://schema.org/encodingFormat\",\n        \"lastPublishedAt\": \"https://schema.org/datePublished\",\n        \"readme\": \"https://schema.org/description\",\n        \"createdAt\": \"https://schema.org/dateCreated\",\n        \"updatedAt\": \"https://schema.org/dateModified\"\n      }\n    },\n    \"\
  Monograph\": {\n      \"@id\": \"cosmo:cli/monograph\",\n      \"@context\": {\n        \"id\": \"https://schema.org/identifier\",\n        \"name\": \"https://schema.org/name\",\n        \"namespace\": {\n          \"@id\": \"cosmo:cli/namespace\",\n          \"@type\": \"@id\"\n        },\n        \"routingUrl\": \"https://schema.org/url\",\n        \"graphUrl\": \"https://schema.org/url\",\n        \"compositionStatus\": \"https://schema.org/status\",\n        \"readme\": \"https://schema.org/description\",\n        \"createdAt\": \"https://schema.org/dateCreated\",\n        \"updatedAt\": \"https://schema.org/dateModified\"\n      }\n    },\n    \"SchemaContract\": {\n      \"@id\": \"cosmo:cli/contract\",\n      \"@context\": {\n        \"id\": \"https://schema.org/identifier\",\n        \"name\": \"https://schema.org/name\",\n        \"namespace\": {\n          \"@id\": \"cosmo:cli/namespace\",\n          \"@type\": \"@id\"\n        },\n        \"sourceGraphName\": {\n          \"\
  @id\": \"cosmo:cli/federated-graph\",\n          \"@type\": \"@id\"\n        },\n        \"routingUrl\": \"https://schema.org/url\",\n        \"excludeTags\": \"https://schema.org/keywords\",\n        \"compositionStatus\": \"https://schema.org/status\",\n        \"createdAt\": \"https://schema.org/dateCreated\",\n        \"updatedAt\": \"https://schema.org/dateModified\"\n      }\n    },\n    \"FeatureFlag\": {\n      \"@id\": \"cosmo:cli/feature-flag\",\n      \"@context\": {\n        \"id\": \"https://schema.org/identifier\",\n        \"name\": \"https://schema.org/name\",\n        \"namespace\": {\n          \"@id\": \"cosmo:cli/namespace\",\n          \"@type\": \"@id\"\n        },\n        \"isEnabled\": \"https://schema.org/status\",\n        \"featureSubgraphNames\": \"https://schema.org/hasPart\",\n        \"labels\": \"https://schema.org/keywords\",\n        \"createdAt\": \"https://schema.org/dateCreated\",\n        \"updatedAt\": \"https://schema.org/dateModified\"\n      }\n\
  \    },\n    \"RouterToken\": {\n      \"@id\": \"cosmo:cli/router/token\",\n      \"@context\": {\n        \"id\": \"https://schema.org/identifier\",\n        \"name\": \"https://schema.org/name\",\n        \"createdAt\": \"https://schema.org/dateCreated\",\n        \"lastUsedAt\": \"https://schema.org/dateModified\"\n      }\n    },\n    \"APIKey\": {\n      \"@id\": \"cosmo:cli/auth\",\n      \"@context\": {\n        \"name\": \"https://schema.org/name\",\n        \"createdAt\": \"https://schema.org/dateCreated\",\n        \"expiresAt\": \"https://schema.org/expires\",\n        \"lastUsedAt\": \"https://schema.org/dateModified\",\n        \"createdBy\": \"https://schema.org/creator\"\n      }\n    },\n    \"ChangelogEntry\": {\n      \"@id\": \"cosmo:cli/federated-graph/changelog\",\n      \"@context\": {\n        \"id\": \"https://schema.org/identifier\",\n        \"schemaVersionId\": \"https://schema.org/version\",\n        \"createdAt\": \"https://schema.org/dateCreated\",\n    \
  \    \"changeType\": \"https://schema.org/category\",\n        \"path\": \"https://schema.org/urlTemplate\",\n        \"changeMessage\": \"https://schema.org/description\"\n      }\n    },\n    \"OperationResponse\": {\n      \"@id\": \"https://schema.org/ActionStatusType\",\n      \"@context\": {\n        \"success\": \"https://schema.org/actionStatus\",\n        \"message\": \"https://schema.org/description\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/wundergraph/refs/heads/main/json-ld/wundergraph-context.jsonld
tags:
- Federation
- GraphQL
- Management
- Schema Registry
- JSON-LD
- Linked Data
- Semantic Web
---
