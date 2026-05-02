---
api_specs:
- filename: llamaindex-llamacloud-api-openapi.yml
  format: yaml
  label: LlamaIndex LlamaCloud API
  slug: llamacloud-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/llamaindex/refs/heads/main/openapi/llamaindex-llamacloud-api-openapi.yml
- filename: llamaindex-llamaparse-api-openapi.yml
  format: yaml
  label: LlamaIndex LlamaParse API
  slug: llamaparse-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/llamaindex/refs/heads/main/openapi/llamaindex-llamaparse-api-openapi.yml
- filename: llamaindex-llamaextract-api-openapi.yml
  format: yaml
  label: LlamaIndex LlamaExtract API
  slug: llamaextract-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/llamaindex/refs/heads/main/openapi/llamaindex-llamaextract-api-openapi.yml
- filename: llamaindex-llamacloud-index-api-openapi.yml
  format: yaml
  label: LlamaIndex LlamaCloud Index API
  slug: llamacloud-index-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/llamaindex/refs/heads/main/openapi/llamaindex-llamacloud-index-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/llamaindex-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/llamaindex/refs/heads/main/json-ld/llamaindex-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Llamaindex from llamaindex.
layout: jsonld
name: Llamaindex Context
namespaces:
- prefix: llama
  uri: https://llamaindex.ai/ns/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Project
  type: ''
- container: ''
  name: Pipeline
  type: ''
- container: ''
  name: DataSource
  type: ''
- container: ''
  name: DataSink
  type: ''
- container: ''
  name: File
  type: ''
- container: ''
  name: ParseJob
  type: ''
- container: ''
  name: ExtractionAgent
  type: ''
- container: ''
  name: ExtractionJob
  type: ''
- container: ''
  name: RetrievalResult
  type: ''
property_count: 9
provider_name: llamaindex
provider_slug: llamaindex
slug: llamaindex-context
source_filename: llamaindex-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"llama\": \"https://llamaindex.ai/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Project\": {\n      \"@id\": \"llama:Project\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updated_at\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Pipeline\": {\n      \"@id\": \"llama:Pipeline\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"status\": \"llama:status\",\n        \"project\": {\n          \"@id\": \"llama:project\",\n          \"@type\": \"@id\"\n        },\n        \"embedding_model\"\
  : \"llama:embeddingModel\",\n        \"sync_interval\": \"llama:syncInterval\",\n        \"data_sources\": {\n          \"@id\": \"llama:dataSources\",\n          \"@container\": \"@set\"\n        },\n        \"data_sinks\": {\n          \"@id\": \"llama:dataSinks\",\n          \"@container\": \"@set\"\n        },\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updated_at\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"DataSource\": {\n      \"@id\": \"llama:DataSource\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"source_type\": \"llama:sourceType\",\n        \"config\": \"llama:configuration\",\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"DataSink\": {\n      \"@id\": \"llama:DataSink\",\n      \"@context\"\
  : {\n        \"name\": \"schema:name\",\n        \"sink_type\": \"llama:sinkType\",\n        \"config\": \"llama:configuration\"\n      }\n    },\n\n    \"File\": {\n      \"@id\": \"schema:DigitalDocument\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"file_size\": \"schema:contentSize\",\n        \"content_type\": \"schema:encodingFormat\",\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"ParseJob\": {\n      \"@id\": \"llama:ParseJob\",\n      \"@context\": {\n        \"status\": \"llama:status\",\n        \"tier\": \"llama:parsingTier\",\n        \"version\": \"schema:version\",\n        \"file_name\": \"schema:name\",\n        \"num_pages\": \"schema:numberOfPages\",\n        \"source_url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n      \
  \  },\n        \"result\": \"llama:parseResult\",\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"completed_at\": {\n          \"@id\": \"llama:completedAt\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"ExtractionAgent\": {\n      \"@id\": \"llama:ExtractionAgent\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"data_schema\": \"llama:dataSchema\",\n        \"prompt\": \"llama:prompt\",\n        \"project\": {\n          \"@id\": \"llama:project\",\n          \"@type\": \"@id\"\n        },\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updated_at\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"ExtractionJob\": {\n      \"@id\": \"llama:ExtractionJob\"\
  ,\n      \"@context\": {\n        \"status\": \"llama:status\",\n        \"extraction_agent\": {\n          \"@id\": \"llama:extractionAgent\",\n          \"@type\": \"@id\"\n        },\n        \"files\": {\n          \"@id\": \"llama:files\",\n          \"@container\": \"@set\"\n        },\n        \"results\": {\n          \"@id\": \"llama:results\",\n          \"@container\": \"@set\"\n        },\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"completed_at\": {\n          \"@id\": \"llama:completedAt\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"RetrievalResult\": {\n      \"@id\": \"llama:RetrievalResult\",\n      \"@context\": {\n        \"text\": \"schema:text\",\n        \"score\": \"llama:relevanceScore\",\n        \"metadata\": \"llama:metadata\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/llamaindex/refs/heads/main/json-ld/llamaindex-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
