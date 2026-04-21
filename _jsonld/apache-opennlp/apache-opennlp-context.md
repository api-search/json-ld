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
