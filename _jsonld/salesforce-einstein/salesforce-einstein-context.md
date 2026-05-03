---
api_specs:
- filename: openapi.json
  format: json
  label: Einstein Vision API
  slug: ''
  spec_type: OpenAPI
  url: https://api.einstein.ai/v2/vision/openapi.json
- filename: openapi.json
  format: json
  label: Einstein Language API
  slug: ''
  spec_type: OpenAPI
  url: https://api.einstein.ai/v2/language/openapi.json
- filename: salesforce-einstein-prediction-builder-openapi.yml
  format: yaml
  label: Einstein Prediction Builder API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/salesforce-einstein/refs/heads/main/openapi/salesforce-einstein-prediction-builder-openapi.yml
- filename: salesforce-einstein-discovery-openapi.yml
  format: yaml
  label: Einstein Discovery API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/salesforce-einstein/refs/heads/main/openapi/salesforce-einstein-discovery-openapi.yml
- filename: salesforce-einstein-bots-openapi.yml
  format: yaml
  label: Einstein Bots API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/salesforce-einstein/refs/heads/main/openapi/salesforce-einstein-bots-openapi.yml
- filename: salesforce-einstein-gpt-openapi.yml
  format: yaml
  label: Einstein GPT API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/salesforce-einstein/refs/heads/main/openapi/salesforce-einstein-gpt-openapi.yml
class_count: 4
classes:
- name
- description
- url
- identifier
context_file: json-ld/salesforce-einstein-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/salesforce-einstein/refs/heads/main/json-ld/salesforce-einstein-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Salesforce Einstein from Salesforce Einstein.
layout: jsonld
name: Salesforce Einstein Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: einstein
  uri: https://developer.salesforce.com/docs/einstein/
- prefix: sf
  uri: https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: mlSchema
  uri: http://www.w3.org/ns/mls#
properties:
- container: ''
  name: EinsteinVisionAPI
  type: ''
- container: ''
  name: EinsteinLanguageAPI
  type: ''
- container: ''
  name: Dataset
  type: ''
- container: ''
  name: Model
  type: ''
- container: ''
  name: Prediction
  type: ''
- container: ''
  name: PredictionFactor
  type: ''
- container: ''
  name: BotSession
  type: ''
- container: ''
  name: BotMessage
  type: ''
- container: ''
  name: Generation
  type: ''
- container: ''
  name: PromptTemplate
  type: ''
- container: ''
  name: Story
  type: ''
- container: ''
  name: PredictionDefinition
  type: ''
- container: ''
  name: dateCreated
  type: dateTime
- container: ''
  name: dateModified
  type: dateTime
- container: ''
  name: provider
  type: reference
- container: ''
  name: Salesforce
  type: schema:Organization
property_count: 16
provider_name: Salesforce Einstein
provider_slug: salesforce-einstein
slug: salesforce-einstein-context
source_filename: salesforce-einstein-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"einstein\": \"https://developer.salesforce.com/docs/einstein/\",\n    \"sf\": \"https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"mlSchema\": \"http://www.w3.org/ns/mls#\",\n\n    \"EinsteinVisionAPI\": {\n      \"@id\": \"schema:WebAPI\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"url\": \"schema:url\",\n        \"provider\": \"schema:provider\",\n        \"documentation\": \"schema:documentation\"\n      }\n    },\n\n    \"EinsteinLanguageAPI\": {\n      \"@id\": \"schema:WebAPI\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"url\": \"schema:url\",\n        \"provider\": \"schema:provider\",\n        \"documentation\": \"schema:documentation\"\n\
  \      }\n    },\n\n    \"Dataset\": {\n      \"@id\": \"schema:Dataset\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"dateCreated\": \"schema:dateCreated\",\n        \"dateModified\": \"schema:dateModified\",\n        \"datasetType\": \"einstein:datasetType\",\n        \"totalExamples\": \"einstein:totalExamples\",\n        \"totalLabels\": \"einstein:totalLabels\",\n        \"available\": \"einstein:available\",\n        \"labelSummary\": \"einstein:labelSummary\"\n      }\n    },\n\n    \"Model\": {\n      \"@id\": \"mlSchema:Model\",\n      \"@context\": {\n        \"modelId\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"status\": \"einstein:modelStatus\",\n        \"modelType\": \"einstein:modelType\",\n        \"progress\": \"einstein:trainingProgress\",\n        \"epochs\": \"mlSchema:epochs\",\n        \"learningRate\": \"mlSchema:learningRate\",\n        \"dateCreated\": \"schema:dateCreated\"\
  ,\n        \"dateModified\": \"schema:dateModified\",\n        \"trainStats\": \"einstein:trainStats\"\n      }\n    },\n\n    \"Prediction\": {\n      \"@id\": \"einstein:Prediction\",\n      \"@context\": {\n        \"score\": \"einstein:predictionScore\",\n        \"label\": \"einstein:predictionLabel\",\n        \"predictionType\": \"einstein:predictionType\",\n        \"factors\": \"einstein:predictionFactors\",\n        \"prescriptions\": \"einstein:prescriptions\",\n        \"recordId\": \"sf:recordId\",\n        \"dateCreated\": \"schema:dateCreated\"\n      }\n    },\n\n    \"PredictionFactor\": {\n      \"@id\": \"einstein:PredictionFactor\",\n      \"@context\": {\n        \"featureName\": \"einstein:featureName\",\n        \"featureValue\": \"einstein:featureValue\",\n        \"importance\": \"einstein:importance\",\n        \"direction\": \"einstein:direction\"\n      }\n    },\n\n    \"BotSession\": {\n      \"@id\": \"einstein:BotSession\",\n      \"@context\": {\n     \
  \   \"sessionId\": \"schema:identifier\",\n        \"botId\": \"einstein:botId\",\n        \"status\": \"einstein:sessionStatus\",\n        \"messages\": \"einstein:messages\",\n        \"dateCreated\": \"schema:dateCreated\"\n      }\n    },\n\n    \"BotMessage\": {\n      \"@id\": \"schema:Message\",\n      \"@context\": {\n        \"text\": \"schema:text\",\n        \"messageType\": \"einstein:messageType\",\n        \"sender\": \"schema:sender\",\n        \"choices\": \"einstein:choices\",\n        \"sequenceId\": \"einstein:sequenceId\",\n        \"dateSent\": \"schema:dateSent\"\n      }\n    },\n\n    \"Generation\": {\n      \"@id\": \"einstein:Generation\",\n      \"@context\": {\n        \"generationId\": \"schema:identifier\",\n        \"prompt\": \"einstein:prompt\",\n        \"generatedText\": \"schema:text\",\n        \"modelId\": \"einstein:modelId\",\n        \"contentQuality\": \"einstein:contentQuality\",\n        \"tokenUsage\": \"einstein:tokenUsage\",\n        \"dateCreated\"\
  : \"schema:dateCreated\"\n      }\n    },\n\n    \"PromptTemplate\": {\n      \"@id\": \"einstein:PromptTemplate\",\n      \"@context\": {\n        \"developerName\": \"schema:identifier\",\n        \"masterLabel\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"promptText\": \"einstein:promptText\",\n        \"templateType\": \"einstein:templateType\",\n        \"relatedEntity\": \"einstein:relatedEntity\",\n        \"status\": \"einstein:status\"\n      }\n    },\n\n    \"Story\": {\n      \"@id\": \"einstein:DiscoveryStory\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"label\": \"schema:alternateName\",\n        \"status\": \"einstein:storyStatus\",\n        \"outcomeVariable\": \"einstein:outcomeVariable\",\n        \"outcomeGoal\": \"einstein:outcomeGoal\",\n        \"dateCreated\": \"schema:dateCreated\",\n        \"dateModified\": \"schema:dateModified\"\n      }\n    },\n\n    \"PredictionDefinition\": {\n      \"@id\": \"\
  einstein:PredictionDefinition\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"label\": \"schema:alternateName\",\n        \"status\": \"einstein:definitionStatus\",\n        \"predictionType\": \"einstein:predictionType\",\n        \"sobjectType\": \"sf:sobjectType\",\n        \"outcome\": \"einstein:outcome\"\n      }\n    },\n\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"identifier\": \"schema:identifier\",\n    \"dateCreated\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"dateModified\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"provider\": {\n      \"@id\": \"schema:provider\",\n      \"@type\": \"@id\"\n    },\n    \"Salesforce\": {\n      \"@id\": \"https://www.salesforce.com/\",\n      \"@type\": \"schema:Organization\",\n      \"name\": \"Salesforce\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/salesforce-einstein/refs/heads/main/json-ld/salesforce-einstein-context.jsonld
tags:
- Artificial Intelligence
- Computer Vision
- CRM
- Machine Learning
- Natural Language Processing
- Predictive Analytics
- Salesforce
- JSON-LD
- Linked Data
- Semantic Web
---
