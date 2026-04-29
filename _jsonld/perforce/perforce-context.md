---
api_specs:
- filename: perforce-helix-swarm-openapi.yml
  format: yaml
  label: Perforce Helix Swarm API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/perforce/refs/heads/main/openapi/perforce-helix-swarm-openapi.yml
class_count: 0
classes: []
context_file: json-ld/perforce-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/perforce/refs/heads/main/json-ld/perforce-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Perforce from Perforce.
layout: jsonld
name: Perforce Context
namespaces:
- prefix: swarm
  uri: https://help.perforce.com/helix-core/helix-swarm/ns/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Review
  type: ''
- container: ''
  name: Comment
  type: ''
- container: ''
  name: Activity
  type: ''
- container: ''
  name: Project
  type: ''
- container: ''
  name: Change
  type: ''
- container: ''
  name: Participant
  type: ''
- container: ''
  name: ReviewerGroup
  type: ''
- container: ''
  name: ReviewVersion
  type: ''
- container: ''
  name: CommentContext
  type: ''
property_count: 9
provider_name: Perforce
provider_slug: perforce
slug: perforce-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"swarm\": \"https://help.perforce.com/helix-core/helix-swarm/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Review\": {\n      \"@id\": \"swarm:Review\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"author\": {\n          \"@id\": \"schema:author\",\n          \"@type\": \"@id\"\n        },\n        \"description\": \"schema:description\",\n        \"state\": \"swarm:state\",\n        \"stateLabel\": \"swarm:stateLabel\",\n        \"type\": \"swarm:reviewType\",\n        \"changes\": {\n          \"@id\": \"swarm:changes\",\n          \"@container\": \"@set\"\n        },\n        \"commits\": {\n          \"@id\": \"swarm:commits\",\n          \"@container\": \"@set\"\n        },\n        \"participants\": {\n          \"@id\": \"swarm:participants\",\n          \"@type\": \"@id\"\n \
  \       },\n        \"groups\": {\n          \"@id\": \"swarm:reviewerGroups\",\n          \"@container\": \"@set\"\n        },\n        \"projects\": {\n          \"@id\": \"swarm:associatedProjects\",\n          \"@type\": \"@id\"\n        },\n        \"pending\": \"swarm:isPending\",\n        \"testStatus\": \"swarm:testStatus\",\n        \"deployStatus\": \"swarm:deployStatus\",\n        \"versions\": {\n          \"@id\": \"swarm:versions\",\n          \"@container\": \"@list\"\n        },\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"updated\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"updateDate\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Comment\": {\n      \"@id\": \"swarm:Comment\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"body\"\
  : \"schema:text\",\n        \"user\": {\n          \"@id\": \"schema:author\",\n          \"@type\": \"@id\"\n        },\n        \"topic\": \"swarm:topic\",\n        \"taskState\": \"swarm:taskState\",\n        \"context\": \"swarm:inlineContext\",\n        \"flags\": {\n          \"@id\": \"swarm:flags\",\n          \"@container\": \"@set\"\n        },\n        \"likes\": {\n          \"@id\": \"swarm:likes\",\n          \"@container\": \"@set\"\n        },\n        \"attachments\": {\n          \"@id\": \"swarm:attachments\",\n          \"@container\": \"@set\"\n        },\n        \"time\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"updated\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"edited\": {\n          \"@id\": \"swarm:editedAt\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"Activity\": {\n      \"@id\": \"swarm:Activity\",\n\
  \      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"action\": \"swarm:action\",\n        \"user\": {\n          \"@id\": \"schema:agent\",\n          \"@type\": \"@id\"\n        },\n        \"target\": \"swarm:target\",\n        \"type\": \"swarm:activityType\",\n        \"description\": \"schema:description\",\n        \"topic\": \"swarm:topic\",\n        \"change\": \"swarm:changelistId\",\n        \"link\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"streams\": {\n          \"@id\": \"swarm:streams\",\n          \"@container\": \"@set\"\n        },\n        \"date\": {\n          \"@id\": \"dcterms:date\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Project\": {\n      \"@id\": \"swarm:Project\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"members\": {\n          \"@id\"\
  : \"schema:member\",\n          \"@container\": \"@set\"\n        },\n        \"owners\": {\n          \"@id\": \"swarm:owners\",\n          \"@container\": \"@set\"\n        },\n        \"subgroups\": {\n          \"@id\": \"swarm:subgroups\",\n          \"@container\": \"@set\"\n        },\n        \"branches\": {\n          \"@id\": \"swarm:branches\",\n          \"@container\": \"@set\"\n        },\n        \"private\": \"swarm:isPrivate\",\n        \"deleted\": \"swarm:isDeleted\",\n        \"workflow\": \"swarm:workflow\",\n        \"jobview\": \"swarm:jobview\",\n        \"minimumUpVotes\": \"swarm:minimumUpVotes\",\n        \"retainDefaultReviewers\": \"swarm:retainDefaultReviewers\",\n        \"readme\": \"swarm:readme\"\n      }\n    },\n\n    \"Change\": {\n      \"@id\": \"swarm:Change\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"projects\": {\n          \"@id\": \"swarm:affectedProjects\",\n          \"@type\": \"@id\"\n        },\n        \"\
  defaultReviewers\": {\n          \"@id\": \"swarm:defaultReviewers\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Participant\": {\n      \"@id\": \"swarm:Participant\",\n      \"@context\": {\n        \"vote\": \"swarm:vote\",\n        \"required\": \"swarm:isRequired\"\n      }\n    },\n\n    \"ReviewerGroup\": {\n      \"@id\": \"swarm:ReviewerGroup\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"required\": \"swarm:isRequired\",\n        \"quorum\": \"swarm:quorum\"\n      }\n    },\n\n    \"ReviewVersion\": {\n      \"@id\": \"swarm:ReviewVersion\",\n      \"@context\": {\n        \"change\": \"swarm:changelistId\",\n        \"user\": {\n          \"@id\": \"schema:author\",\n          \"@type\": \"@id\"\n        },\n        \"time\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"pending\": \"swarm:isPending\",\n        \"stream\": \"swarm:stream\",\n        \"difference\": \"\
  swarm:difference\",\n        \"archiveChange\": \"swarm:archiveChangelistId\"\n      }\n    },\n\n    \"CommentContext\": {\n      \"@id\": \"swarm:CommentContext\",\n      \"@context\": {\n        \"file\": \"swarm:depotFile\",\n        \"leftLine\": \"swarm:leftLineNumber\",\n        \"rightLine\": \"swarm:rightLineNumber\",\n        \"content\": \"swarm:contextContent\",\n        \"version\": \"swarm:reviewVersion\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/perforce/refs/heads/main/json-ld/perforce-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
