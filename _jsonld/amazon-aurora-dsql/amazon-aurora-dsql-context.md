---
api_specs:
- filename: amazon-aurora-dsql-openapi.yml
  format: yaml
  label: Amazon Aurora DSQL API
  slug: amazon-aurora-dsql-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-aurora-dsql/refs/heads/main/openapi/amazon-aurora-dsql-openapi.yml
class_count: 4
classes:
- Cluster
- ClusterIdentifier
- ClusterArn
- ClusterStatus
context_file: json-ld/amazon-aurora-dsql-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-aurora-dsql/refs/heads/main/json-ld/amazon-aurora-dsql-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Aurora Dsql from Amazon Aurora DSQL.
layout: jsonld
name: Amazon Aurora Dsql Context
namespaces:
- prefix: dsql
  uri: https://aws.amazon.com/rds/aurora/dsql/
properties: []
property_count: 0
provider_name: Amazon Aurora DSQL
provider_slug: amazon-aurora-dsql
slug: amazon-aurora-dsql-context
source_filename: amazon-aurora-dsql-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"dsql\": \"https://aws.amazon.com/rds/aurora/dsql/\",\n    \"Cluster\": \"dsql:Cluster\",\n    \"ClusterIdentifier\": \"dsql:clusterIdentifier\",\n    \"ClusterArn\": \"dsql:clusterArn\",\n    \"ClusterStatus\": \"dsql:ClusterStatus\"\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-aurora-dsql/refs/heads/main/json-ld/amazon-aurora-dsql-context.jsonld
tags:
- Amazon Aurora DSQL
- Distributed SQL
- PostgreSQL
- Serverless
- JSON-LD
- Linked Data
- Semantic Web
---
