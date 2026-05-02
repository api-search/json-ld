---
api_specs:
- filename: swagger.json
  format: json
  label: Harbor API
  slug: harbor
  spec_type: OpenAPI
  url: https://api.harbor.gg/docs/v1/swagger.json
class_count: 0
classes: []
context_file: json-ld/harbor-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/harbor/refs/heads/main/json-ld/harbor-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Harbor from Harbor.
layout: jsonld
name: Harbor Context
namespaces:
- prefix: harbor
  uri: https://api.harbor.gg/vocab/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: loyalty
  uri: https://w3id.org/loyalty#
properties:
- container: ''
  name: Community
  type: ''
- container: ''
  name: Member
  type: ''
- container: ''
  name: Tier
  type: ''
- container: ''
  name: Challenge
  type: ''
- container: ''
  name: Reward
  type: ''
- container: ''
  name: Redemption
  type: ''
- container: ''
  name: LeaderboardEntry
  type: ''
- container: ''
  name: PointTransaction
  type: ''
property_count: 8
provider_name: Harbor
provider_slug: harbor
slug: harbor-context
source_filename: harbor-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"harbor\": \"https://api.harbor.gg/vocab/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"loyalty\": \"https://w3id.org/loyalty#\",\n\n    \"Community\": {\n      \"@id\": \"schema:Organization\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"slug\": \"schema:alternateName\",\n        \"description\": \"schema:description\",\n        \"logoUrl\": {\n          \"@id\": \"schema:logo\",\n          \"@type\": \"@id\"\n        },\n        \"primaryColor\": \"schema:color\",\n        \"memberCount\": \"schema:numberOfEmployees\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"tiers\": {\n          \"@id\": \"harbor:tiers\",\n          \"@container\": \"@set\"\n        }\n      }\n\
  \    },\n\n    \"Member\": {\n      \"@id\": \"schema:Person\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"externalId\": {\n          \"@id\": \"schema:sameAs\",\n          \"@type\": \"xsd:string\"\n        },\n        \"displayName\": \"schema:name\",\n        \"email\": \"schema:email\",\n        \"pointsBalance\": {\n          \"@id\": \"loyalty:pointBalance\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"totalPointsEarned\": {\n          \"@id\": \"loyalty:totalPointsEarned\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"referralCode\": {\n          \"@id\": \"harbor:referralCode\",\n          \"@type\": \"xsd:string\"\n        },\n        \"status\": \"schema:additionalType\",\n        \"joinedAt\": {\n          \"@id\": \"schema:startDate\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"lastActiveAt\": {\n          \"@id\": \"schema:dateModified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n\
  \        \"tier\": \"harbor:tier\",\n        \"metadata\": \"schema:additionalProperty\"\n      }\n    },\n\n    \"Tier\": {\n      \"@id\": \"loyalty:Tier\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"pointsRequired\": {\n          \"@id\": \"loyalty:pointsRequired\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"benefits\": {\n          \"@id\": \"schema:featureList\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Challenge\": {\n      \"@id\": \"schema:Action\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"title\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"points\": {\n          \"@id\": \"loyalty:pointValue\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"actionType\": \"schema:additionalType\",\n        \"repeatable\": {\n          \"@id\": \"harbor:repeatable\",\n          \"@type\": \"xsd:boolean\"\
  \n        },\n        \"status\": \"schema:actionStatus\",\n        \"startsAt\": {\n          \"@id\": \"schema:startDate\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"endsAt\": {\n          \"@id\": \"schema:endDate\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Reward\": {\n      \"@id\": \"schema:Offer\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"title\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"pointCost\": {\n          \"@id\": \"loyalty:pointCost\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"type\": \"schema:category\",\n        \"status\": \"schema:availability\",\n        \"quantity\": {\n          \"@id\": \"schema:inventoryLevel\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"imageUrl\": {\n          \"@id\": \"schema:image\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Redemption\": {\n      \"@id\"\
  : \"schema:Order\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"memberId\": {\n          \"@id\": \"schema:customer\",\n          \"@type\": \"xsd:string\"\n        },\n        \"rewardId\": {\n          \"@id\": \"schema:orderedItem\",\n          \"@type\": \"xsd:string\"\n        },\n        \"pointsSpent\": {\n          \"@id\": \"loyalty:pointsRedeemed\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"status\": \"schema:orderStatus\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"LeaderboardEntry\": {\n      \"@id\": \"schema:ListItem\",\n      \"@context\": {\n        \"rank\": {\n          \"@id\": \"schema:position\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"memberId\": \"schema:identifier\",\n        \"\
  displayName\": \"schema:name\",\n        \"points\": {\n          \"@id\": \"loyalty:pointBalance\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"PointTransaction\": {\n      \"@id\": \"schema:MonetaryTransaction\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"memberId\": {\n          \"@id\": \"schema:participant\",\n          \"@type\": \"xsd:string\"\n        },\n        \"type\": \"schema:additionalType\",\n        \"points\": {\n          \"@id\": \"loyalty:pointAmount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"description\": \"schema:description\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/harbor/refs/heads/main/json-ld/harbor-context.jsonld
tags:
- Community
- Engagement
- Loyalty
- Superfans
- JSON-LD
- Linked Data
- Semantic Web
---
