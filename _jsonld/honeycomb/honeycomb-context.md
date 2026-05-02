---
api_specs:
- filename: honeycomb-api-openapi.yml
  format: yaml
  label: Honeycomb API
  slug: api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/honeycomb/refs/heads/main/openapi/honeycomb-api-openapi.yml
- filename: honeycomb-events-api-openapi.yml
  format: yaml
  label: Honeycomb Events API
  slug: events-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/honeycomb/refs/heads/main/openapi/honeycomb-events-api-openapi.yml
- filename: honeycomb-queries-api-openapi.yml
  format: yaml
  label: Honeycomb Queries API
  slug: queries-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/honeycomb/refs/heads/main/openapi/honeycomb-queries-api-openapi.yml
- filename: honeycomb-slos-api-openapi.yml
  format: yaml
  label: Honeycomb SLOs API
  slug: slos-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/honeycomb/refs/heads/main/openapi/honeycomb-slos-api-openapi.yml
- filename: honeycomb-datasets-api-openapi.yml
  format: yaml
  label: Honeycomb Datasets API
  slug: datasets-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/honeycomb/refs/heads/main/openapi/honeycomb-datasets-api-openapi.yml
- filename: honeycomb-boards-api-openapi.yml
  format: yaml
  label: Honeycomb Boards API
  slug: boards-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/honeycomb/refs/heads/main/openapi/honeycomb-boards-api-openapi.yml
- filename: honeycomb-markers-api-openapi.yml
  format: yaml
  label: Honeycomb Markers API
  slug: markers-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/honeycomb/refs/heads/main/openapi/honeycomb-markers-api-openapi.yml
- filename: honeycomb-triggers-api-openapi.yml
  format: yaml
  label: Honeycomb Triggers API
  slug: triggers-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/honeycomb/refs/heads/main/openapi/honeycomb-triggers-api-openapi.yml
- filename: honeycomb-environments-api-openapi.yml
  format: yaml
  label: Honeycomb Environments API
  slug: environments-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/honeycomb/refs/heads/main/openapi/honeycomb-environments-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/honeycomb-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/honeycomb/refs/heads/main/json-ld/honeycomb-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Honeycomb from honeycomb.
layout: jsonld
name: Honeycomb Context
namespaces:
- prefix: honeycomb
  uri: https://api.honeycomb.io/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Dataset
  type: ''
- container: ''
  name: Column
  type: ''
- container: ''
  name: Event
  type: ''
- container: ''
  name: Query
  type: ''
- container: ''
  name: Board
  type: ''
- container: ''
  name: Marker
  type: ''
- container: ''
  name: Trigger
  type: ''
- container: ''
  name: SLO
  type: ''
- container: ''
  name: Recipient
  type: ''
- container: ''
  name: Environment
  type: ''
- container: ''
  name: ApiKey
  type: ''
property_count: 11
provider_name: honeycomb
provider_slug: honeycomb
slug: honeycomb-context
source_filename: honeycomb-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"honeycomb\": \"https://api.honeycomb.io/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Dataset\": {\n      \"@id\": \"honeycomb:Dataset\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"slug\": \"honeycomb:slug\",\n        \"description\": \"schema:description\",\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"last_written_at\": {\n          \"@id\": \"honeycomb:lastWrittenAt\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"regular_columns_count\": {\n          \"@id\": \"honeycomb:regularColumnsCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"columns\": {\n          \"@id\": \"honeycomb:columns\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n   \
  \ \"Column\": {\n      \"@id\": \"honeycomb:Column\",\n      \"@context\": {\n        \"key_name\": \"schema:name\",\n        \"type\": \"honeycomb:columnType\",\n        \"description\": \"schema:description\",\n        \"hidden\": \"honeycomb:hidden\",\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updated_at\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"last_written\": {\n          \"@id\": \"honeycomb:lastWritten\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Event\": {\n      \"@id\": \"honeycomb:Event\",\n      \"@context\": {\n        \"time\": {\n          \"@id\": \"dcterms:date\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"samplerate\": {\n          \"@id\": \"honeycomb:sampleRate\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"data\": \"honeycomb:eventData\"\n     \
  \ }\n    },\n\n    \"Query\": {\n      \"@id\": \"honeycomb:Query\",\n      \"@context\": {\n        \"calculations\": {\n          \"@id\": \"honeycomb:calculations\",\n          \"@container\": \"@set\"\n        },\n        \"filters\": {\n          \"@id\": \"honeycomb:filters\",\n          \"@container\": \"@set\"\n        },\n        \"breakdowns\": {\n          \"@id\": \"honeycomb:breakdowns\",\n          \"@container\": \"@set\"\n        },\n        \"time_range\": {\n          \"@id\": \"honeycomb:timeRange\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"granularity\": {\n          \"@id\": \"honeycomb:granularity\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"Board\": {\n      \"@id\": \"honeycomb:Board\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"style\": \"honeycomb:boardStyle\",\n        \"column_layout\": \"honeycomb:columnLayout\",\n        \"queries\"\
  : {\n          \"@id\": \"honeycomb:boardQueries\",\n          \"@container\": \"@set\"\n        },\n        \"board_url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updated_at\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Marker\": {\n      \"@id\": \"honeycomb:Marker\",\n      \"@context\": {\n        \"start_time\": {\n          \"@id\": \"honeycomb:startTime\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"end_time\": {\n          \"@id\": \"honeycomb:endTime\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"message\": \"schema:description\",\n        \"type\": \"honeycomb:markerType\",\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"created_at\": {\n \
  \         \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updated_at\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Trigger\": {\n      \"@id\": \"honeycomb:Trigger\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"disabled\": \"honeycomb:disabled\",\n        \"frequency\": {\n          \"@id\": \"honeycomb:frequency\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"recipients\": {\n          \"@id\": \"honeycomb:recipients\",\n          \"@container\": \"@set\"\n        },\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updated_at\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"SLO\": {\n      \"@id\": \"honeycomb:SLO\",\n    \
  \  \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"target_percentage\": {\n          \"@id\": \"honeycomb:targetPercentage\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"time_period_days\": {\n          \"@id\": \"honeycomb:timePeriodDays\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updated_at\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Recipient\": {\n      \"@id\": \"honeycomb:Recipient\",\n      \"@context\": {\n        \"type\": \"honeycomb:recipientType\",\n        \"target\": \"honeycomb:recipientTarget\",\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updated_at\": {\n          \"@id\": \"dcterms:modified\"\
  ,\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Environment\": {\n      \"@id\": \"honeycomb:Environment\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"slug\": \"honeycomb:slug\",\n        \"description\": \"schema:description\",\n        \"color\": \"honeycomb:color\",\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updated_at\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"ApiKey\": {\n      \"@id\": \"honeycomb:ApiKey\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"type\": \"honeycomb:keyType\",\n        \"disabled\": \"honeycomb:disabled\",\n        \"environment_id\": \"honeycomb:environmentId\",\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/honeycomb/refs/heads/main/json-ld/honeycomb-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
