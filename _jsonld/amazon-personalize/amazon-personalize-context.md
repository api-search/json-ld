---
class_count: 0
classes: []
context_file: json-ld/amazon-personalize-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-personalize/refs/heads/main/json-ld/amazon-personalize-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Personalize from Amazon Personalize.
layout: jsonld
name: Amazon Personalize Context
namespaces:
- prefix: personalize
  uri: https://docs.aws.amazon.com/personalize/latest/dg/
- prefix: aws
  uri: https://aws.amazon.com/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: DatasetGroup
  type: ''
- container: ''
  name: Dataset
  type: ''
- container: ''
  name: Solution
  type: ''
- container: ''
  name: Campaign
  type: ''
- container: ''
  name: Recommender
  type: ''
property_count: 5
provider_name: Amazon Personalize
provider_slug: amazon-personalize
slug: amazon-personalize-context
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"personalize\": \"https://docs.aws.amazon.com/personalize/latest/dg/\",\n    \"aws\": \"https://aws.amazon.com/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"DatasetGroup\": {\n      \"@id\": \"personalize:API_DescribeDatasetGroup\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"datasetGroupArn\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"status\": {\n          \"@id\": \"personalize:status\",\n          \"@type\": \"xsd:string\"\n        },\n        \"domain\": {\n          \"@id\": \"personalize:domain\",\n          \"@type\": \"xsd:string\"\n        },\n        \"kmsKeyArn\": {\n          \"@id\": \"personalize:kmsKeyArn\",\n          \"@type\"\
  : \"xsd:string\"\n        },\n        \"roleArn\": {\n          \"@id\": \"personalize:roleArn\",\n          \"@type\": \"xsd:string\"\n        },\n        \"creationDateTime\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"lastUpdatedDateTime\": {\n          \"@id\": \"schema:dateModified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Dataset\": {\n      \"@id\": \"personalize:API_DescribeDataset\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"datasetArn\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"datasetType\": {\n          \"@id\": \"personalize:datasetType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"schemaArn\": {\n          \"@id\": \"personalize:schemaArn\",\n          \"@type\": \"xsd:string\"\n        },\n   \
  \     \"status\": {\n          \"@id\": \"personalize:status\",\n          \"@type\": \"xsd:string\"\n        },\n        \"creationDateTime\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Solution\": {\n      \"@id\": \"personalize:API_DescribeSolution\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"solutionArn\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"recipeArn\": {\n          \"@id\": \"personalize:recipeArn\",\n          \"@type\": \"xsd:string\"\n        },\n        \"datasetGroupArn\": {\n          \"@id\": \"personalize:datasetGroupArn\",\n          \"@type\": \"xsd:string\"\n        },\n        \"performAutoML\": {\n          \"@id\": \"personalize:performAutoML\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"performHPO\": {\n\
  \          \"@id\": \"personalize:performHPO\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"status\": {\n          \"@id\": \"personalize:status\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"Campaign\": {\n      \"@id\": \"personalize:API_DescribeCampaign\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"campaignArn\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"solutionVersionArn\": {\n          \"@id\": \"personalize:solutionVersionArn\",\n          \"@type\": \"xsd:string\"\n        },\n        \"minProvisionedTPS\": {\n          \"@id\": \"personalize:minProvisionedTPS\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"status\": {\n          \"@id\": \"personalize:status\",\n          \"@type\": \"xsd:string\"\n        },\n        \"creationDateTime\": {\n          \"@id\"\
  : \"schema:dateCreated\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Recommender\": {\n      \"@id\": \"personalize:API_DescribeRecommender\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"recommenderArn\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"datasetGroupArn\": {\n          \"@id\": \"personalize:datasetGroupArn\",\n          \"@type\": \"xsd:string\"\n        },\n        \"recipeArn\": {\n          \"@id\": \"personalize:recipeArn\",\n          \"@type\": \"xsd:string\"\n        },\n        \"status\": {\n          \"@id\": \"personalize:status\",\n          \"@type\": \"xsd:string\"\n        },\n        \"creationDateTime\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-personalize/refs/heads/main/json-ld/amazon-personalize-context.jsonld
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
