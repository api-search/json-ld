---
class_count: 18
classes:
- TokensRequest
- ModelList
- SentenceDetectionResult
- ChunkingResult
- NamedEntity
- NERResult
- POSTokensRequest
- Span
- LemmatizationResult
- LanguageDetectionResult
- Chunk
- CategorizationResult
- TokenizationResult
- ModelInfo
- POSTaggingResult
- LanguageProbability
- ParseResult
- TextRequest
context_file: json-ld/apache-opennlp-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apache-opennlp/refs/heads/main/json-ld/apache-opennlp-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apache Opennlp from Apache OpenNLP.
layout: jsonld
name: Apache Opennlp Context
namespaces:
- prefix: nlp
  uri: https://opennlp.apache.org/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: set
  name: tokens
  type: ''
- container: ''
  name: language
  type: string
- container: set
  name: models
  type: ''
- container: set
  name: sentences
  type: ''
- container: set
  name: spans
  type: ''
- container: set
  name: chunks
  type: ''
- container: ''
  name: text
  type: schema:description
- container: ''
  name: type
  type: string
- container: ''
  name: start
  type: integer
- container: ''
  name: end
  type: integer
- container: ''
  name: probability
  type: decimal
- container: set
  name: entities
  type: ''
- container: set
  name: posTags
  type: ''
- container: set
  name: lemmas
  type: ''
- container: ''
  name: bestLanguage
  type: string
- container: ''
  name: confidence
  type: decimal
- container: set
  name: languages
  type: ''
- container: ''
  name: bestCategory
  type: string
- container: ''
  name: probabilities
  type: string
- container: ''
  name: modelId
  type: string
- container: ''
  name: version
  type: string
- container: ''
  name: loaded
  type: boolean
- container: set
  name: tags
  type: ''
- container: ''
  name: parseTree
  type: string
property_count: 24
provider_name: Apache OpenNLP
provider_slug: apache-opennlp
slug: apache-opennlp-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"nlp\": \"https://opennlp.apache.org/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"TokensRequest\": \"nlp:TokensRequest\",\n    \"ModelList\": \"nlp:ModelList\",\n    \"SentenceDetectionResult\": \"nlp:SentenceDetectionResult\",\n    \"ChunkingResult\": \"nlp:ChunkingResult\",\n    \"NamedEntity\": \"nlp:NamedEntity\",\n    \"NERResult\": \"nlp:NERResult\",\n    \"POSTokensRequest\": \"nlp:POSTokensRequest\",\n    \"Span\": \"nlp:Span\",\n    \"LemmatizationResult\": \"nlp:LemmatizationResult\",\n    \"LanguageDetectionResult\": \"nlp:LanguageDetectionResult\",\n    \"Chunk\": \"nlp:Chunk\",\n    \"CategorizationResult\": \"nlp:CategorizationResult\",\n    \"TokenizationResult\": \"nlp:TokenizationResult\",\n    \"ModelInfo\": \"nlp:ModelInfo\",\n    \"POSTaggingResult\": \"nlp:POSTaggingResult\",\n    \"LanguageProbability\": \"nlp:LanguageProbability\",\n\
  \    \"ParseResult\": \"nlp:ParseResult\",\n    \"TextRequest\": \"nlp:TextRequest\",\n    \"tokens\": {\n      \"@id\": \"nlp:tokens\",\n      \"@container\": \"@set\"\n    },\n    \"language\": {\n      \"@id\": \"nlp:language\",\n      \"@type\": \"xsd:string\"\n    },\n    \"models\": {\n      \"@id\": \"nlp:models\",\n      \"@container\": \"@set\"\n    },\n    \"sentences\": {\n      \"@id\": \"nlp:sentences\",\n      \"@container\": \"@set\"\n    },\n    \"spans\": {\n      \"@id\": \"nlp:spans\",\n      \"@container\": \"@set\"\n    },\n    \"chunks\": {\n      \"@id\": \"nlp:chunks\",\n      \"@container\": \"@set\"\n    },\n    \"text\": {\n      \"@id\": \"nlp:text\",\n      \"@type\": \"schema:description\"\n    },\n    \"type\": {\n      \"@id\": \"nlp:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"start\": {\n      \"@id\": \"nlp:start\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"end\": {\n      \"@id\": \"nlp:end\",\n      \"@type\": \"xsd:integer\"\n   \
  \ },\n    \"probability\": {\n      \"@id\": \"nlp:probability\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"entities\": {\n      \"@id\": \"nlp:entities\",\n      \"@container\": \"@set\"\n    },\n    \"posTags\": {\n      \"@id\": \"nlp:posTags\",\n      \"@container\": \"@set\"\n    },\n    \"lemmas\": {\n      \"@id\": \"nlp:lemmas\",\n      \"@container\": \"@set\"\n    },\n    \"bestLanguage\": {\n      \"@id\": \"nlp:bestLanguage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"confidence\": {\n      \"@id\": \"nlp:confidence\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"languages\": {\n      \"@id\": \"nlp:languages\",\n      \"@container\": \"@set\"\n    },\n    \"bestCategory\": {\n      \"@id\": \"nlp:bestCategory\",\n      \"@type\": \"xsd:string\"\n    },\n    \"probabilities\": {\n      \"@id\": \"nlp:probabilities\",\n      \"@type\": \"xsd:string\"\n    },\n    \"modelId\": {\n      \"@id\": \"nlp:modelId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"\
  version\": {\n      \"@id\": \"nlp:version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"loaded\": {\n      \"@id\": \"nlp:loaded\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"tags\": {\n      \"@id\": \"nlp:tags\",\n      \"@container\": \"@set\"\n    },\n    \"parseTree\": {\n      \"@id\": \"nlp:parseTree\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/apache-opennlp/refs/heads/main/json-ld/apache-opennlp-context.jsonld
tags:
- Machine Learning
- Natural Language Processing
- NLP
- Text Processing
- Apache
- Open Source
- Java
- JSON-LD
- Linked Data
- Semantic Web
---
