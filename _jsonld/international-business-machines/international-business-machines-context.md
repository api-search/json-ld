---
api_specs:
- filename: ibm-watsonx-ai-openapi.yml
  format: yaml
  label: IBM Watsonx.ai API
  slug: watsonx-ai
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/international-business-machines/refs/heads/main/openapi/ibm-watsonx-ai-openapi.yml
- filename: ibm-watsonx-assistant-openapi.yml
  format: yaml
  label: IBM Watsonx Assistant V2 API
  slug: watsonx-assistant
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/international-business-machines/refs/heads/main/openapi/ibm-watsonx-assistant-openapi.yml
- filename: ibm-natural-language-understanding-openapi.yml
  format: yaml
  label: IBM Natural Language Understanding API
  slug: natural-language-understanding
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/international-business-machines/refs/heads/main/openapi/ibm-natural-language-understanding-openapi.yml
- filename: ibm-speech-to-text-openapi.yml
  format: yaml
  label: IBM Speech to Text API
  slug: speech-to-text
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/international-business-machines/refs/heads/main/openapi/ibm-speech-to-text-openapi.yml
- filename: ibm-text-to-speech-openapi.yml
  format: yaml
  label: IBM Text to Speech API
  slug: text-to-speech
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/international-business-machines/refs/heads/main/openapi/ibm-text-to-speech-openapi.yml
- filename: ibm-cloud-object-storage-openapi.yml
  format: yaml
  label: IBM Cloud Object Storage API
  slug: cloud-object-storage
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/international-business-machines/refs/heads/main/openapi/ibm-cloud-object-storage-openapi.yml
- filename: ibm-kubernetes-service-openapi.yml
  format: yaml
  label: IBM Cloud Kubernetes Service API
  slug: kubernetes-service
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/international-business-machines/refs/heads/main/openapi/ibm-kubernetes-service-openapi.yml
- filename: ibm-vpc-openapi.yml
  format: yaml
  label: IBM Cloud VPC API
  slug: vpc
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/international-business-machines/refs/heads/main/openapi/ibm-vpc-openapi.yml
class_count: 32
classes:
- FoundationModel
- TextGenerationRequest
- TextGenerationResponse
- Embedding
- AssistantSession
- AssistantMessage
- Intent
- Entity
- AnalysisResult
- Sentiment
- Emotion
- Keyword
- Concept
- SpeechRecognitionResult
- SpeechModel
- Voice
- Bucket
- StorageObject
- VPC
- Instance
- Subnet
- SecurityGroup
- Cluster
- WorkerNode
- WorkerPool
- model_id
- project_id
- assistant_id
- session_id
- transcript
- confidence
- crn
context_file: json-ld/international-business-machines-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/international-business-machines/refs/heads/main/json-ld/international-business-machines-context.jsonld
description: JSON-LD context defining the semantic vocabulary for International Business Machines from International Business Machines.
layout: jsonld
name: International Business Machines Context
namespaces:
- prefix: ibm
  uri: https://cloud.ibm.com/apidocs/
- prefix: watsonx
  uri: https://cloud.ibm.com/apidocs/watsonx-ai#
- prefix: assistant
  uri: https://cloud.ibm.com/apidocs/assistant-v2#
- prefix: nlu
  uri: https://cloud.ibm.com/apidocs/natural-language-understanding#
- prefix: stt
  uri: https://cloud.ibm.com/apidocs/speech-to-text#
- prefix: tts
  uri: https://cloud.ibm.com/apidocs/text-to-speech#
- prefix: cos
  uri: https://cloud.ibm.com/docs/cloud-object-storage#
- prefix: vpc
  uri: https://cloud.ibm.com/apidocs/vpc/latest#
- prefix: iks
  uri: https://cloud.ibm.com/apidocs/kubernetes/containers-v1-v2#
properties: []
property_count: 0
provider_name: International Business Machines
provider_slug: international-business-machines
slug: international-business-machines-context
source_filename: international-business-machines-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"ibm\": \"https://cloud.ibm.com/apidocs/\",\n    \"watsonx\": \"https://cloud.ibm.com/apidocs/watsonx-ai#\",\n    \"assistant\": \"https://cloud.ibm.com/apidocs/assistant-v2#\",\n    \"nlu\": \"https://cloud.ibm.com/apidocs/natural-language-understanding#\",\n    \"stt\": \"https://cloud.ibm.com/apidocs/speech-to-text#\",\n    \"tts\": \"https://cloud.ibm.com/apidocs/text-to-speech#\",\n    \"cos\": \"https://cloud.ibm.com/docs/cloud-object-storage#\",\n    \"vpc\": \"https://cloud.ibm.com/apidocs/vpc/latest#\",\n    \"iks\": \"https://cloud.ibm.com/apidocs/kubernetes/containers-v1-v2#\",\n    \"FoundationModel\": \"watsonx:FoundationModel\",\n    \"TextGenerationRequest\": \"watsonx:TextGenerationRequest\",\n    \"TextGenerationResponse\": \"watsonx:TextGenerationResponse\",\n    \"Embedding\": \"watsonx:Embedding\",\n    \"AssistantSession\": \"assistant:Session\",\n    \"AssistantMessage\": \"assistant:Message\"\
  ,\n    \"Intent\": \"assistant:Intent\",\n    \"Entity\": \"assistant:Entity\",\n    \"AnalysisResult\": \"nlu:AnalysisResult\",\n    \"Sentiment\": \"nlu:Sentiment\",\n    \"Emotion\": \"nlu:Emotion\",\n    \"Keyword\": \"nlu:Keyword\",\n    \"Concept\": \"nlu:Concept\",\n    \"SpeechRecognitionResult\": \"stt:RecognitionResult\",\n    \"SpeechModel\": \"stt:SpeechModel\",\n    \"Voice\": \"tts:Voice\",\n    \"Bucket\": \"cos:Bucket\",\n    \"StorageObject\": \"cos:Object\",\n    \"VPC\": \"vpc:VPC\",\n    \"Instance\": \"vpc:Instance\",\n    \"Subnet\": \"vpc:Subnet\",\n    \"SecurityGroup\": \"vpc:SecurityGroup\",\n    \"Cluster\": \"iks:Cluster\",\n    \"WorkerNode\": \"iks:Worker\",\n    \"WorkerPool\": \"iks:WorkerPool\",\n    \"model_id\": \"watsonx:model_id\",\n    \"project_id\": \"watsonx:project_id\",\n    \"assistant_id\": \"assistant:assistant_id\",\n    \"session_id\": \"assistant:session_id\",\n    \"transcript\": \"stt:transcript\",\n    \"confidence\": \"stt:confidence\"\
  ,\n    \"crn\": \"ibm:crn\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/international-business-machines/refs/heads/main/json-ld/international-business-machines-context.jsonld
tags:
- Artificial Intelligence
- Cloud
- Enterprise
- IBM
- JSON-LD
- Linked Data
- Semantic Web
---
