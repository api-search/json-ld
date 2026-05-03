---
api_specs:
- filename: toornament-openapi.yml
  format: yaml
  label: Toornament Organizer API
  slug: organizer-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/toornament/refs/heads/main/openapi/toornament-openapi.yml
class_count: 0
classes: []
context_file: json-ld/toornament-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/toornament/refs/heads/main/json-ld/toornament-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Toornament from Toornament.
layout: jsonld
name: Toornament Context
namespaces:
- prefix: toornament
  uri: https://api.toornament.com/ns/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Tournament
  type: ''
- container: ''
  name: Participant
  type: ''
- container: ''
  name: Stage
  type: ''
- container: ''
  name: Match
  type: ''
- container: ''
  name: RankingItem
  type: ''
- container: ''
  name: Discipline
  type: ''
- container: ''
  name: Webhook
  type: ''
property_count: 7
provider_name: Toornament
provider_slug: toornament
slug: toornament-context
source_filename: toornament-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"toornament\": \"https://api.toornament.com/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Tournament\": {\n      \"@id\": \"toornament:Tournament\",\n      \"@context\": {\n        \"id\": \"toornament:tournamentId\",\n        \"name\": \"schema:name\",\n        \"full_name\": \"schema:alternateName\",\n        \"description\": \"schema:description\",\n        \"status\": \"toornament:tournamentStatus\",\n        \"discipline\": \"toornament:discipline\",\n        \"participant_type\": \"toornament:participantType\",\n        \"size\": \"toornament:maxParticipants\",\n        \"online\": \"toornament:isOnline\",\n        \"country\": \"schema:addressCountry\",\n        \"timezone\": \"schema:temporalCoverage\",\n        \"scheduled_date_start\": {\n          \"@id\": \"schema:startDate\",\n          \"@type\": \"\
  xsd:date\"\n        },\n        \"scheduled_date_end\": {\n          \"@id\": \"schema:endDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"registration_enabled\": \"toornament:registrationEnabled\",\n        \"platforms\": {\n          \"@id\": \"toornament:platforms\",\n          \"@container\": \"@set\"\n        },\n        \"website\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"public\": \"toornament:isPublic\",\n        \"prize\": \"toornament:prizePool\",\n        \"contact\": \"schema:email\",\n        \"rules\": \"toornament:tournamentRules\",\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Participant\": {\n      \"@id\": \"toornament:Participant\",\n      \"@context\": {\n        \"id\": \"toornament:participantId\",\n        \"name\": \"schema:name\",\n        \"email\": \"schema:email\",\n        \"type\": \"toornament:participantType\"\
  ,\n        \"checked_in\": \"toornament:checkedIn\",\n        \"lineup\": {\n          \"@id\": \"toornament:lineup\",\n          \"@container\": \"@list\"\n        },\n        \"custom_fields\": \"toornament:customFields\",\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Stage\": {\n      \"@id\": \"toornament:Stage\",\n      \"@context\": {\n        \"id\": \"toornament:stageId\",\n        \"name\": \"schema:name\",\n        \"number\": \"toornament:stageNumber\",\n        \"type\": \"toornament:stageType\",\n        \"size\": \"toornament:stageSize\",\n        \"status\": \"toornament:stageStatus\"\n      }\n    },\n\n    \"Match\": {\n      \"@id\": \"toornament:Match\",\n      \"@context\": {\n        \"id\": \"toornament:matchId\",\n        \"number\": \"toornament:matchNumber\",\n        \"status\": \"toornament:matchStatus\",\n        \"scheduled_datetime\": {\n          \"@id\": \"\
  schema:startDate\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"played_at\": {\n          \"@id\": \"toornament:playedAt\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"opponents\": {\n          \"@id\": \"toornament:opponents\",\n          \"@container\": \"@list\"\n        }\n      }\n    },\n\n    \"RankingItem\": {\n      \"@id\": \"toornament:RankingItem\",\n      \"@context\": {\n        \"id\": \"toornament:rankingItemId\",\n        \"position\": \"toornament:rankingPosition\",\n        \"participant\": \"toornament:rankedParticipant\",\n        \"properties\": \"toornament:rankingStats\"\n      }\n    },\n\n    \"Discipline\": {\n      \"@id\": \"toornament:Discipline\",\n      \"@context\": {\n        \"id\": \"toornament:disciplineId\",\n        \"name\": \"schema:name\",\n        \"full_name\": \"schema:alternateName\",\n        \"platforms\": {\n          \"@id\": \"toornament:platforms\",\n          \"@container\": \"@set\"\n        }\n \
  \     }\n    },\n\n    \"Webhook\": {\n      \"@id\": \"toornament:Webhook\",\n      \"@context\": {\n        \"id\": \"toornament:webhookId\",\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"events\": {\n          \"@id\": \"toornament:subscribedEvents\",\n          \"@container\": \"@set\"\n        },\n        \"is_active\": \"toornament:isActive\",\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/toornament/refs/heads/main/json-ld/toornament-context.jsonld
tags:
- Esports
- Gaming
- Tournaments
- Brackets
- Competition
- JSON-LD
- Linked Data
- Semantic Web
---
