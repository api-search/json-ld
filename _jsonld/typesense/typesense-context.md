---
api_specs:
- filename: typesense-search-api-openapi.yml
  format: yaml
  label: Typesense Search API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/typesense/refs/heads/main/openapi/typesense-search-api-openapi.yml
- filename: typesense-vector-search-api-openapi.yml
  format: yaml
  label: Typesense Vector Search API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/typesense/refs/heads/main/openapi/typesense-vector-search-api-openapi.yml
- filename: typesense-conversational-search-api-openapi.yml
  format: yaml
  label: Typesense Conversational Search API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/typesense/refs/heads/main/openapi/typesense-conversational-search-api-openapi.yml
- filename: typesense-analytics-api-openapi.yml
  format: yaml
  label: Typesense Analytics API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/typesense/refs/heads/main/openapi/typesense-analytics-api-openapi.yml
- filename: typesense-cloud-management-api-openapi.yml
  format: yaml
  label: Typesense Cloud Management API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/typesense/refs/heads/main/openapi/typesense-cloud-management-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/typesense-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/typesense/refs/heads/main/json-ld/typesense-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Typesense from Typesense.
layout: jsonld
name: Typesense Context
namespaces:
- prefix: typesense
  uri: https://typesense.org/ns/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Collection
  type: ''
- container: ''
  name: Field
  type: ''
- container: ''
  name: Document
  type: ''
- container: ''
  name: SearchResult
  type: ''
- container: ''
  name: SearchHit
  type: ''
- container: ''
  name: SynonymSet
  type: ''
- container: ''
  name: CurationSet
  type: ''
- container: ''
  name: ApiKey
  type: ''
- container: ''
  name: CollectionAlias
  type: ''
- container: ''
  name: AnalyticsEvent
  type: ''
- container: ''
  name: ConversationModel
  type: ''
- container: ''
  name: Cluster
  type: ''
property_count: 12
provider_name: Typesense
provider_slug: typesense
slug: typesense-context
source_filename: typesense-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"typesense\": \"https://typesense.org/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Collection\": {\n      \"@id\": \"typesense:Collection\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"fields\": \"typesense:fields\",\n        \"default_sorting_field\": \"typesense:defaultSortingField\",\n        \"token_separators\": \"typesense:tokenSeparators\",\n        \"symbols_to_index\": \"typesense:symbolsToIndex\",\n        \"enable_nested_fields\": \"typesense:enableNestedFields\",\n        \"num_documents\": \"typesense:numDocuments\",\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"synonym_sets\": {\n          \"@id\": \"typesense:synonymSets\",\n          \"@container\"\
  : \"@set\"\n        }\n      }\n    },\n\n    \"Field\": {\n      \"@id\": \"typesense:Field\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"type\": \"typesense:fieldType\",\n        \"optional\": \"typesense:optional\",\n        \"facet\": \"typesense:facet\",\n        \"index\": \"typesense:index\",\n        \"sort\": \"typesense:sortable\",\n        \"locale\": \"typesense:locale\",\n        \"num_dim\": \"typesense:numDimensions\",\n        \"vec_dist\": \"typesense:vectorDistance\",\n        \"reference\": \"typesense:reference\",\n        \"embed\": \"typesense:embedConfig\"\n      }\n    },\n\n    \"Document\": {\n      \"@id\": \"typesense:Document\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"collection\": \"typesense:collection\"\n      }\n    },\n\n    \"SearchResult\": {\n      \"@id\": \"typesense:SearchResult\",\n      \"@context\": {\n        \"found\": \"typesense:found\",\n        \"search_time_ms\": \"typesense:searchTimeMs\"\
  ,\n        \"out_of\": \"typesense:outOf\",\n        \"page\": \"typesense:page\",\n        \"hits\": {\n          \"@id\": \"typesense:hits\",\n          \"@container\": \"@list\"\n        },\n        \"facet_counts\": {\n          \"@id\": \"typesense:facetCounts\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"SearchHit\": {\n      \"@id\": \"typesense:SearchHit\",\n      \"@context\": {\n        \"document\": \"typesense:document\",\n        \"text_match\": \"typesense:textMatch\",\n        \"vector_distance\": \"typesense:vectorDistance\",\n        \"highlights\": {\n          \"@id\": \"typesense:highlights\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"SynonymSet\": {\n      \"@id\": \"typesense:SynonymSet\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"synonyms\": {\n          \"@id\": \"typesense:synonymItems\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"CurationSet\"\
  : {\n      \"@id\": \"typesense:CurationSet\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"rule\": \"typesense:curationRule\",\n        \"includes\": {\n          \"@id\": \"typesense:pinnedDocuments\",\n          \"@container\": \"@list\"\n        },\n        \"excludes\": {\n          \"@id\": \"typesense:hiddenDocuments\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"ApiKey\": {\n      \"@id\": \"typesense:ApiKey\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"description\": \"schema:description\",\n        \"actions\": {\n          \"@id\": \"typesense:allowedActions\",\n          \"@container\": \"@set\"\n        },\n        \"collections\": {\n          \"@id\": \"typesense:allowedCollections\",\n          \"@container\": \"@set\"\n        },\n        \"expires_at\": {\n          \"@id\": \"typesense:expiresAt\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"CollectionAlias\"\
  : {\n      \"@id\": \"typesense:CollectionAlias\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"collection_name\": \"typesense:targetCollection\"\n      }\n    },\n\n    \"AnalyticsEvent\": {\n      \"@id\": \"typesense:AnalyticsEvent\",\n      \"@context\": {\n        \"type\": \"typesense:eventType\",\n        \"name\": \"schema:name\",\n        \"data\": \"typesense:eventData\",\n        \"timestamp\": {\n          \"@id\": \"dcterms:date\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"ConversationModel\": {\n      \"@id\": \"typesense:ConversationModel\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"model_name\": \"typesense:modelName\",\n        \"system_prompt\": \"typesense:systemPrompt\",\n        \"max_bytes\": \"typesense:maxBytes\",\n        \"history_collection\": \"typesense:historyCollection\"\n      }\n    },\n\n    \"Cluster\": {\n      \"@id\": \"typesense:CloudCluster\",\n      \"@context\"\
  : {\n        \"id\": \"schema:identifier\",\n        \"cluster_name\": \"schema:name\",\n        \"status\": \"typesense:clusterStatus\",\n        \"memory\": \"typesense:memory\",\n        \"vcpu\": \"typesense:vcpu\",\n        \"typesense_server_version\": \"schema:softwareVersion\",\n        \"regions\": {\n          \"@id\": \"typesense:regions\",\n          \"@container\": \"@set\"\n        },\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"hostnames\": \"typesense:hostnames\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/typesense/refs/heads/main/json-ld/typesense-context.jsonld
tags:
- Full-Text Search
- Open Source
- Search Engine
- Typo Tolerance
- Vector Search
- JSON-LD
- Linked Data
- Semantic Web
---
