---
class_count: 2
classes:
- AwsCloudMapInstanceAttribute
- AwsCloudMapServiceDiscovery
context_file: json-ld/aws-app-mesh-aws-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/aws-app-mesh/refs/heads/main/json-ld/aws-app-mesh-aws-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Aws App Mesh Aws from AWS App Mesh.
layout: jsonld
name: Aws App Mesh Aws Context
namespaces:
- prefix: aws
  uri: https://aws.amazon.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: attributes
  type: string
- container: ''
  name: ipPreference
  type: string
- container: ''
  name: namespaceName
  type: string
- container: ''
  name: serviceName
  type: string
- container: ''
  name: key
  type: string
- container: ''
  name: value
  type: string
property_count: 6
provider_name: AWS App Mesh
provider_slug: aws-app-mesh
slug: aws-app-mesh-aws-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aws\": \"https://aws.amazon.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AwsCloudMapInstanceAttribute\": \"aws:AwsCloudMapInstanceAttribute\",\n    \"AwsCloudMapServiceDiscovery\": \"aws:AwsCloudMapServiceDiscovery\",\n    \"attributes\": {\n      \"@id\": \"aws:attributes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ipPreference\": {\n      \"@id\": \"aws:ipPreference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"namespaceName\": {\n      \"@id\": \"aws:namespaceName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"serviceName\": {\n      \"@id\": \"aws:serviceName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"key\": {\n      \"@id\": \"aws:key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"aws:value\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/aws-app-mesh/refs/heads/main/json-ld/aws-app-mesh-aws-context.jsonld
tags:
- AWS
- Deprecated
- Envoy
- Microservices
- Networking
- Service Mesh
- JSON-LD
- Linked Data
- Semantic Web
---
