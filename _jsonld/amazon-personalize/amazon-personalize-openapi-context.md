---
class_count: 4
classes:
- Campaign
- CreateDatasetGroupRequest
- DatasetGroup
- Solution
context_file: json-ld/amazon-personalize-openapi-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-personalize/refs/heads/main/json-ld/amazon-personalize-openapi-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Personalize Openapi from Amazon Personalize.
layout: jsonld
name: Amazon Personalize Openapi Context
namespaces:
- prefix: personalize
  uri: https://personalize.amazonaws.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: campaignArn
  type: string
- container: ''
  name: creationDateTime
  type: dateTime
- container: ''
  name: datasetGroupArn
  type: string
- container: ''
  name: domain
  type: string
- container: ''
  name: minProvisionedTPS
  type: integer
- container: ''
  name: name
  type: ''
- container: ''
  name: recipeArn
  type: string
- container: ''
  name: solutionArn
  type: string
- container: ''
  name: solutionVersionArn
  type: string
- container: ''
  name: status
  type: string
property_count: 10
provider_name: Amazon Personalize
provider_slug: amazon-personalize
slug: amazon-personalize-openapi-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"personalize\": \"https://personalize.amazonaws.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Campaign\": \"personalize:Campaign\",\n    \"CreateDatasetGroupRequest\": \"personalize:CreateDatasetGroupRequest\",\n    \"DatasetGroup\": \"personalize:DatasetGroup\",\n    \"Solution\": \"personalize:Solution\",\n    \"campaignArn\": {\n      \"@id\": \"personalize:campaignArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"creationDateTime\": {\n      \"@id\": \"personalize:creationDateTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"datasetGroupArn\": {\n      \"@id\": \"personalize:datasetGroupArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"domain\": {\n      \"@id\": \"personalize:domain\",\n      \"@type\": \"xsd:string\"\n    },\n    \"minProvisionedTPS\": {\n      \"@id\": \"personalize:minProvisionedTPS\"\
  ,\n      \"@type\": \"xsd:integer\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\"\n    },\n    \"recipeArn\": {\n      \"@id\": \"personalize:recipeArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"solutionArn\": {\n      \"@id\": \"personalize:solutionArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"solutionVersionArn\": {\n      \"@id\": \"personalize:solutionVersionArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"personalize:status\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-personalize/refs/heads/main/json-ld/amazon-personalize-openapi-context.jsonld
tags:
- AI
- AWS
- Customer Experience
- Machine Learning
- ML
- Personalization
- Recommendations
- JSON-LD
- Linked Data
- Semantic Web
---
