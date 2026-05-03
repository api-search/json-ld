---
class_count: 28
classes:
- SchemaStitching
- Subschema
- TypeMerging
- SchemaGateway
- StitchingDirective
- SchemaDelegation
- SchemaTransform
- GraphQLSchema
- GraphQLType
- GraphQLQuery
- GraphQLMutation
- GraphQLSubscription
- GraphQLResolver
- name
- description
- url
- version
- codeRepository
- documentation
- license
- programmingLanguage
- selectionSet
- mergeKey
- batchEnabled
- SoftwareApplication
- SoftwareSourceCode
- APIReference
- TechArticle
context_file: json-ld/schema-stitching-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/schema-stitching/refs/heads/main/json-ld/schema-stitching-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Schema Stitching from Schema Stitching.
layout: jsonld
name: Schema Stitching Context
namespaces:
- prefix: stitching
  uri: https://the-guild.dev/graphql/stitching/vocab#
- prefix: graphql
  uri: https://graphql.org/vocab#
properties:
- container: ''
  name: hasSubschema
  type: reference
- container: ''
  name: mergesType
  type: reference
- container: ''
  name: delegatesTo
  type: reference
- container: ''
  name: transformApplied
  type: reference
property_count: 4
provider_name: Schema Stitching
provider_slug: schema-stitching
slug: schema-stitching-context
source_filename: schema-stitching-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"stitching\": \"https://the-guild.dev/graphql/stitching/vocab#\",\n    \"graphql\": \"https://graphql.org/vocab#\",\n\n    \"SchemaStitching\": \"stitching:SchemaStitching\",\n    \"Subschema\": \"stitching:Subschema\",\n    \"TypeMerging\": \"stitching:TypeMerging\",\n    \"SchemaGateway\": \"stitching:SchemaGateway\",\n    \"StitchingDirective\": \"stitching:StitchingDirective\",\n    \"SchemaDelegation\": \"stitching:SchemaDelegation\",\n    \"SchemaTransform\": \"stitching:SchemaTransform\",\n\n    \"GraphQLSchema\": \"graphql:Schema\",\n    \"GraphQLType\": \"graphql:Type\",\n    \"GraphQLQuery\": \"graphql:Query\",\n    \"GraphQLMutation\": \"graphql:Mutation\",\n    \"GraphQLSubscription\": \"graphql:Subscription\",\n    \"GraphQLResolver\": \"graphql:Resolver\",\n\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"version\": \"schema:version\"\
  ,\n    \"codeRepository\": \"schema:codeRepository\",\n    \"documentation\": \"schema:documentation\",\n    \"license\": \"schema:license\",\n    \"programmingLanguage\": \"schema:programmingLanguage\",\n\n    \"hasSubschema\": {\n      \"@id\": \"stitching:hasSubschema\",\n      \"@type\": \"@id\"\n    },\n    \"mergesType\": {\n      \"@id\": \"stitching:mergesType\",\n      \"@type\": \"@id\"\n    },\n    \"delegatesTo\": {\n      \"@id\": \"stitching:delegatesTo\",\n      \"@type\": \"@id\"\n    },\n    \"selectionSet\": \"stitching:selectionSet\",\n    \"mergeKey\": \"stitching:mergeKey\",\n    \"batchEnabled\": \"stitching:batchEnabled\",\n    \"transformApplied\": {\n      \"@id\": \"stitching:transformApplied\",\n      \"@type\": \"@id\"\n    },\n\n    \"SoftwareApplication\": \"schema:SoftwareApplication\",\n    \"SoftwareSourceCode\": \"schema:SoftwareSourceCode\",\n    \"APIReference\": \"schema:APIReference\",\n    \"TechArticle\": \"schema:TechArticle\"\n  },\n  \"@graph\"\
  : [\n    {\n      \"@id\": \"https://the-guild.dev/graphql/stitching\",\n      \"@type\": [\"SoftwareApplication\", \"SchemaGateway\"],\n      \"name\": \"Schema Stitching\",\n      \"description\": \"A GraphQL technique for combining multiple GraphQL schemas into a single unified API gateway using type merging and schema delegation.\",\n      \"url\": \"https://the-guild.dev/graphql/stitching\",\n      \"documentation\": \"https://the-guild.dev/graphql/stitching/docs\",\n      \"codeRepository\": \"https://github.com/ardatan/graphql-tools\",\n      \"programmingLanguage\": \"TypeScript\"\n    }\n  ]\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/schema-stitching/refs/heads/main/json-ld/schema-stitching-context.jsonld
tags:
- API Composition
- API Gateway
- Federation
- GraphQL
- Microservices
- Schema Stitching
- Type Merging
- JSON-LD
- Linked Data
- Semantic Web
---
