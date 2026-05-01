---
api_specs:
- filename: flagsmith-flags-api-openapi.yml
  format: yaml
  label: Flagsmith Flags API
  slug: flags-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/flagsmith/refs/heads/main/openapi/flagsmith-flags-api-openapi.yml
- filename: flagsmith-admin-api-openapi.yml
  format: yaml
  label: Flagsmith Admin API
  slug: admin-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/flagsmith/refs/heads/main/openapi/flagsmith-admin-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/flagsmith-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/flagsmith/refs/heads/main/json-ld/flagsmith-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Flagsmith from flagsmith.
layout: jsonld
name: Flagsmith Context
namespaces:
- prefix: flagsmith
  uri: https://flagsmith.com/ns/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Organisation
  type: ''
- container: ''
  name: Project
  type: ''
- container: ''
  name: Environment
  type: ''
- container: ''
  name: Feature
  type: ''
- container: ''
  name: FeatureState
  type: ''
- container: ''
  name: Segment
  type: ''
- container: ''
  name: Identity
  type: ''
- container: ''
  name: Trait
  type: ''
- container: ''
  name: Webhook
  type: ''
property_count: 9
provider_name: flagsmith
provider_slug: flagsmith
slug: flagsmith-context
source_filename: flagsmith-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"flagsmith\": \"https://flagsmith.com/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Organisation\": {\n      \"@id\": \"flagsmith:Organisation\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"createdDate\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"webhookNotificationEmail\": {\n          \"@id\": \"flagsmith:webhookNotificationEmail\",\n          \"@type\": \"xsd:string\"\n        },\n        \"numSeats\": {\n          \"@id\": \"flagsmith:numSeats\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"persistTraitData\": {\n          \"@id\": \"flagsmith:persistTraitData\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"Project\": {\n      \"@id\": \"flagsmith:Project\",\n      \"@context\"\
  : {\n        \"name\": \"schema:name\",\n        \"createdDate\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"organisation\": {\n          \"@id\": \"flagsmith:organisation\",\n          \"@type\": \"@id\"\n        },\n        \"hideDisabledFlags\": {\n          \"@id\": \"flagsmith:hideDisabledFlags\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"enableRealtimeUpdates\": {\n          \"@id\": \"flagsmith:enableRealtimeUpdates\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"Environment\": {\n      \"@id\": \"flagsmith:Environment\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"apiKey\": {\n          \"@id\": \"flagsmith:apiKey\",\n          \"@type\": \"xsd:string\"\n        },\n        \"project\": {\n          \"@id\": \"flagsmith:project\",\n          \"@type\": \"@id\"\n        },\n        \"allowClientTraits\"\
  : {\n          \"@id\": \"flagsmith:allowClientTraits\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"minimumChangeRequestApprovals\": {\n          \"@id\": \"flagsmith:minimumChangeRequestApprovals\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"Feature\": {\n      \"@id\": \"flagsmith:Feature\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"createdDate\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"featureType\": {\n          \"@id\": \"flagsmith:featureType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"defaultEnabled\": {\n          \"@id\": \"flagsmith:defaultEnabled\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"initialValue\": {\n          \"@id\": \"flagsmith:initialValue\",\n          \"@type\": \"xsd:string\"\n        },\n        \"isArchived\": {\n          \"@id\"\
  : \"flagsmith:isArchived\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"project\": {\n          \"@id\": \"flagsmith:project\",\n          \"@type\": \"@id\"\n        },\n        \"owners\": {\n          \"@id\": \"flagsmith:owners\",\n          \"@container\": \"@set\"\n        },\n        \"tags\": {\n          \"@id\": \"flagsmith:tags\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"FeatureState\": {\n      \"@id\": \"flagsmith:FeatureState\",\n      \"@context\": {\n        \"enabled\": {\n          \"@id\": \"flagsmith:enabled\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"featureStateValue\": {\n          \"@id\": \"flagsmith:featureStateValue\"\n        },\n        \"feature\": {\n          \"@id\": \"flagsmith:feature\",\n          \"@type\": \"@id\"\n        },\n        \"environment\": {\n          \"@id\": \"flagsmith:environment\",\n          \"@type\": \"@id\"\n        },\n        \"identity\": {\n          \"@id\"\
  : \"flagsmith:identity\",\n          \"@type\": \"@id\"\n        },\n        \"featureSegment\": {\n          \"@id\": \"flagsmith:featureSegment\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Segment\": {\n      \"@id\": \"flagsmith:Segment\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"project\": {\n          \"@id\": \"flagsmith:project\",\n          \"@type\": \"@id\"\n        },\n        \"rules\": {\n          \"@id\": \"flagsmith:rules\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Identity\": {\n      \"@id\": \"flagsmith:Identity\",\n      \"@context\": {\n        \"identifier\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"environment\": {\n          \"@id\": \"flagsmith:environment\",\n          \"@type\": \"@id\"\n        },\n        \"traits\": {\n          \"@id\": \"flagsmith:traits\",\n\
  \          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Trait\": {\n      \"@id\": \"flagsmith:Trait\",\n      \"@context\": {\n        \"traitKey\": {\n          \"@id\": \"flagsmith:traitKey\",\n          \"@type\": \"xsd:string\"\n        },\n        \"traitValue\": {\n          \"@id\": \"flagsmith:traitValue\"\n        },\n        \"transient\": {\n          \"@id\": \"flagsmith:transient\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"Webhook\": {\n      \"@id\": \"flagsmith:Webhook\",\n      \"@context\": {\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"enabled\": {\n          \"@id\": \"flagsmith:enabled\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\
  \n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/flagsmith/refs/heads/main/json-ld/flagsmith-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
