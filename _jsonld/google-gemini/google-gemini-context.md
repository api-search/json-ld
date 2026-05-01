---
api_specs:
- filename: google-gemini-api-openapi.yml
  format: yaml
  label: Gemini API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-gemini/refs/heads/main/openapi/google-gemini-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/google-gemini-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-gemini/refs/heads/main/json-ld/google-gemini-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Google Gemini from Google Gemini.
layout: jsonld
name: Google Gemini Context
namespaces:
- prefix: gemini
  uri: https://ai.google.dev/api/
- prefix: gapi
  uri: https://generativelanguage.googleapis.com/v1beta/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: skos
  uri: http://www.w3.org/2004/02/skos/core#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: GenerateContentRequest
  type: ''
- container: ''
  name: GenerateContentResponse
  type: ''
- container: ''
  name: Content
  type: ''
- container: ''
  name: Part
  type: ''
- container: ''
  name: Blob
  type: ''
- container: ''
  name: FileData
  type: ''
- container: ''
  name: FunctionCall
  type: ''
- container: ''
  name: FunctionResponse
  type: ''
- container: ''
  name: Tool
  type: ''
- container: ''
  name: FunctionDeclaration
  type: ''
- container: ''
  name: ToolConfig
  type: ''
- container: ''
  name: FunctionCallingConfig
  type: ''
- container: ''
  name: SafetySetting
  type: ''
- container: ''
  name: GenerationConfig
  type: ''
- container: ''
  name: Candidate
  type: ''
- container: ''
  name: SafetyRating
  type: ''
- container: ''
  name: CitationMetadata
  type: ''
- container: ''
  name: CitationSource
  type: ''
- container: ''
  name: PromptFeedback
  type: ''
- container: ''
  name: UsageMetadata
  type: ''
- container: ''
  name: EmbedContentRequest
  type: ''
- container: ''
  name: EmbedContentResponse
  type: ''
- container: ''
  name: ContentEmbedding
  type: ''
property_count: 23
provider_name: Google Gemini
provider_slug: google-gemini
slug: google-gemini-context
source_filename: google-gemini-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"@vocab\": \"https://schema.org/\",\n    \"gemini\": \"https://ai.google.dev/api/\",\n    \"gapi\": \"https://generativelanguage.googleapis.com/v1beta/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"skos\": \"http://www.w3.org/2004/02/skos/core#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"GenerateContentRequest\": {\n      \"@id\": \"gemini:GenerateContentRequest\",\n      \"@context\": {\n        \"contents\": {\n          \"@id\": \"gemini:contents\",\n          \"@type\": \"@id\",\n          \"@container\": \"@list\"\n        },\n        \"tools\": {\n          \"@id\": \"gemini:tools\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        },\n        \"toolConfig\": {\n          \"@id\": \"gemini:toolConfig\",\n          \"@type\": \"@id\"\n        },\n        \"safetySettings\": {\n          \"@id\": \"gemini:safetySettings\",\n          \"@type\": \"@id\",\n    \
  \      \"@container\": \"@set\"\n        },\n        \"systemInstruction\": {\n          \"@id\": \"gemini:systemInstruction\",\n          \"@type\": \"@id\"\n        },\n        \"generationConfig\": {\n          \"@id\": \"gemini:generationConfig\",\n          \"@type\": \"@id\"\n        },\n        \"cachedContent\": {\n          \"@id\": \"gemini:cachedContent\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"GenerateContentResponse\": {\n      \"@id\": \"gemini:GenerateContentResponse\",\n      \"@context\": {\n        \"candidates\": {\n          \"@id\": \"gemini:candidates\",\n          \"@type\": \"@id\",\n          \"@container\": \"@list\"\n        },\n        \"promptFeedback\": {\n          \"@id\": \"gemini:promptFeedback\",\n          \"@type\": \"@id\"\n        },\n        \"usageMetadata\": {\n          \"@id\": \"gemini:usageMetadata\",\n          \"@type\": \"@id\"\n        },\n        \"modelVersion\": {\n          \"@id\": \"gemini:modelVersion\"\
  ,\n          \"@type\": \"xsd:string\"\n        },\n        \"responseId\": {\n          \"@id\": \"gemini:responseId\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"Content\": {\n      \"@id\": \"gemini:Content\",\n      \"@context\": {\n        \"parts\": {\n          \"@id\": \"gemini:parts\",\n          \"@type\": \"@id\",\n          \"@container\": \"@list\"\n        },\n        \"role\": {\n          \"@id\": \"gemini:role\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"Part\": {\n      \"@id\": \"gemini:Part\",\n      \"@context\": {\n        \"text\": {\n          \"@id\": \"gemini:text\",\n          \"@type\": \"xsd:string\"\n        },\n        \"inlineData\": {\n          \"@id\": \"gemini:inlineData\",\n          \"@type\": \"@id\"\n        },\n        \"fileData\": {\n          \"@id\": \"gemini:fileData\",\n          \"@type\": \"@id\"\n        },\n        \"functionCall\": {\n          \"@id\": \"gemini:functionCall\"\
  ,\n          \"@type\": \"@id\"\n        },\n        \"functionResponse\": {\n          \"@id\": \"gemini:functionResponse\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Blob\": {\n      \"@id\": \"gemini:Blob\",\n      \"@context\": {\n        \"mimeType\": {\n          \"@id\": \"gemini:mimeType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"data\": {\n          \"@id\": \"gemini:data\",\n          \"@type\": \"xsd:base64Binary\"\n        }\n      }\n    },\n\n    \"FileData\": {\n      \"@id\": \"gemini:FileData\",\n      \"@context\": {\n        \"mimeType\": {\n          \"@id\": \"gemini:mimeType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"fileUri\": {\n          \"@id\": \"gemini:fileUri\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"FunctionCall\": {\n      \"@id\": \"gemini:FunctionCall\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"gemini:functionName\",\n          \"@type\"\
  : \"xsd:string\"\n        },\n        \"args\": {\n          \"@id\": \"gemini:functionArgs\",\n          \"@type\": \"@json\"\n        }\n      }\n    },\n\n    \"FunctionResponse\": {\n      \"@id\": \"gemini:FunctionResponse\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"gemini:functionName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"response\": {\n          \"@id\": \"gemini:functionResponseData\",\n          \"@type\": \"@json\"\n        }\n      }\n    },\n\n    \"Tool\": {\n      \"@id\": \"gemini:Tool\",\n      \"@context\": {\n        \"functionDeclarations\": {\n          \"@id\": \"gemini:functionDeclarations\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        },\n        \"codeExecution\": {\n          \"@id\": \"gemini:codeExecution\",\n          \"@type\": \"@json\"\n        }\n      }\n    },\n\n    \"FunctionDeclaration\": {\n      \"@id\": \"gemini:FunctionDeclaration\",\n      \"@context\": {\n      \
  \  \"name\": {\n          \"@id\": \"gemini:functionName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"dcterms:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"parameters\": {\n          \"@id\": \"gemini:parameters\",\n          \"@type\": \"@json\"\n        }\n      }\n    },\n\n    \"ToolConfig\": {\n      \"@id\": \"gemini:ToolConfig\",\n      \"@context\": {\n        \"functionCallingConfig\": {\n          \"@id\": \"gemini:functionCallingConfig\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"FunctionCallingConfig\": {\n      \"@id\": \"gemini:FunctionCallingConfig\",\n      \"@context\": {\n        \"mode\": {\n          \"@id\": \"gemini:functionCallingMode\",\n          \"@type\": \"xsd:string\"\n        },\n        \"allowedFunctionNames\": {\n          \"@id\": \"gemini:allowedFunctionNames\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"SafetySetting\"\
  : {\n      \"@id\": \"gemini:SafetySetting\",\n      \"@context\": {\n        \"category\": {\n          \"@id\": \"gemini:harmCategory\",\n          \"@type\": \"xsd:string\"\n        },\n        \"threshold\": {\n          \"@id\": \"gemini:blockThreshold\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"GenerationConfig\": {\n      \"@id\": \"gemini:GenerationConfig\",\n      \"@context\": {\n        \"candidateCount\": {\n          \"@id\": \"gemini:candidateCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"stopSequences\": {\n          \"@id\": \"gemini:stopSequences\",\n          \"@container\": \"@list\"\n        },\n        \"maxOutputTokens\": {\n          \"@id\": \"gemini:maxOutputTokens\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"temperature\": {\n          \"@id\": \"gemini:temperature\",\n          \"@type\": \"xsd:float\"\n        },\n        \"topP\": {\n          \"@id\": \"gemini:topP\",\n          \"\
  @type\": \"xsd:float\"\n        },\n        \"topK\": {\n          \"@id\": \"gemini:topK\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"responseMimeType\": {\n          \"@id\": \"gemini:responseMimeType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"responseSchema\": {\n          \"@id\": \"gemini:responseSchema\",\n          \"@type\": \"@json\"\n        },\n        \"presencePenalty\": {\n          \"@id\": \"gemini:presencePenalty\",\n          \"@type\": \"xsd:float\"\n        },\n        \"frequencyPenalty\": {\n          \"@id\": \"gemini:frequencyPenalty\",\n          \"@type\": \"xsd:float\"\n        },\n        \"seed\": {\n          \"@id\": \"gemini:seed\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"Candidate\": {\n      \"@id\": \"gemini:Candidate\",\n      \"@context\": {\n        \"content\": {\n          \"@id\": \"gemini:candidateContent\",\n          \"@type\": \"@id\"\n        },\n        \"finishReason\"\
  : {\n          \"@id\": \"gemini:finishReason\",\n          \"@type\": \"xsd:string\"\n        },\n        \"safetyRatings\": {\n          \"@id\": \"gemini:safetyRatings\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        },\n        \"citationMetadata\": {\n          \"@id\": \"gemini:citationMetadata\",\n          \"@type\": \"@id\"\n        },\n        \"tokenCount\": {\n          \"@id\": \"gemini:tokenCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"index\": {\n          \"@id\": \"gemini:candidateIndex\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"SafetyRating\": {\n      \"@id\": \"gemini:SafetyRating\",\n      \"@context\": {\n        \"category\": {\n          \"@id\": \"gemini:harmCategory\",\n          \"@type\": \"xsd:string\"\n        },\n        \"probability\": {\n          \"@id\": \"gemini:harmProbability\",\n          \"@type\": \"xsd:string\"\n        },\n        \"blocked\": {\n       \
  \   \"@id\": \"gemini:blocked\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"CitationMetadata\": {\n      \"@id\": \"gemini:CitationMetadata\",\n      \"@context\": {\n        \"citationSources\": {\n          \"@id\": \"gemini:citationSources\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"CitationSource\": {\n      \"@id\": \"gemini:CitationSource\",\n      \"@context\": {\n        \"startIndex\": {\n          \"@id\": \"gemini:startIndex\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"endIndex\": {\n          \"@id\": \"gemini:endIndex\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"uri\": {\n          \"@id\": \"gemini:sourceUri\",\n          \"@type\": \"@id\"\n        },\n        \"license\": {\n          \"@id\": \"gemini:license\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"PromptFeedback\": {\n      \"@id\": \"gemini:PromptFeedback\"\
  ,\n      \"@context\": {\n        \"blockReason\": {\n          \"@id\": \"gemini:blockReason\",\n          \"@type\": \"xsd:string\"\n        },\n        \"safetyRatings\": {\n          \"@id\": \"gemini:safetyRatings\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"UsageMetadata\": {\n      \"@id\": \"gemini:UsageMetadata\",\n      \"@context\": {\n        \"promptTokenCount\": {\n          \"@id\": \"gemini:promptTokenCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"candidatesTokenCount\": {\n          \"@id\": \"gemini:candidatesTokenCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"totalTokenCount\": {\n          \"@id\": \"gemini:totalTokenCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"cachedContentTokenCount\": {\n          \"@id\": \"gemini:cachedContentTokenCount\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"EmbedContentRequest\"\
  : {\n      \"@id\": \"gemini:EmbedContentRequest\",\n      \"@context\": {\n        \"content\": {\n          \"@id\": \"gemini:embeddingContent\",\n          \"@type\": \"@id\"\n        },\n        \"taskType\": {\n          \"@id\": \"gemini:taskType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"title\": {\n          \"@id\": \"dcterms:title\",\n          \"@type\": \"xsd:string\"\n        },\n        \"outputDimensionality\": {\n          \"@id\": \"gemini:outputDimensionality\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"EmbedContentResponse\": {\n      \"@id\": \"gemini:EmbedContentResponse\",\n      \"@context\": {\n        \"embedding\": {\n          \"@id\": \"gemini:embedding\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"ContentEmbedding\": {\n      \"@id\": \"gemini:ContentEmbedding\",\n      \"@context\": {\n        \"values\": {\n          \"@id\": \"gemini:embeddingValues\",\n          \"@container\"\
  : \"@list\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-gemini/refs/heads/main/json-ld/google-gemini-context.jsonld
tags:
- Agentic AI
- Artificial Intelligence
- Code Generation
- Embeddings
- Generative AI
- Image Generation
- LLM
- Machine Learning
- Multimodal
- JSON-LD
- Linked Data
- Semantic Web
---
