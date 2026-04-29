---
class_count: 0
classes: []
context_file: json-ld/atlassian-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/atlassian/refs/heads/main/json-ld/atlassian-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Atlassian from Atlassian.
layout: jsonld
name: Atlassian Context
namespaces:
- prefix: atlassian
  uri: https://developer.atlassian.com/cloud/admin/vocabulary#
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: Organization
  type: ''
- container: ''
  name: User
  type: ''
- container: ''
  name: ProductAccess
  type: ''
- container: ''
  name: Domain
  type: ''
- container: ''
  name: Policy
  type: ''
- container: ''
  name: Event
  type: ''
- container: ''
  name: EventActor
  type: ''
- container: ''
  name: EventLocation
  type: ''
- container: ''
  name: Group
  type: ''
- container: ''
  name: RoleAssignment
  type: ''
property_count: 10
provider_name: Atlassian
provider_slug: atlassian
slug: atlassian-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"@vocab\": \"https://schema.org/\",\n    \"atlassian\": \"https://developer.atlassian.com/cloud/admin/vocabulary#\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Organization\": {\n      \"@id\": \"atlassian:Organization\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"atlassian:organizationId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"type\": {\n          \"@id\": \"atlassian:resourceType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"attributes\": {\n          \"@id\": \"atlassian:organizationAttributes\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"User\": {\n      \"@id\": \"atlassian:User\",\n      \"@context\": {\n        \"account_id\": {\n          \"@id\": \"atlassian:accountId\"\
  ,\n          \"@type\": \"xsd:string\"\n        },\n        \"account_type\": {\n          \"@id\": \"atlassian:accountType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"account_status\": {\n          \"@id\": \"atlassian:accountStatus\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"email\": {\n          \"@id\": \"schema:email\",\n          \"@type\": \"xsd:string\"\n        },\n        \"picture\": {\n          \"@id\": \"schema:image\",\n          \"@type\": \"@id\"\n        },\n        \"nickname\": {\n          \"@id\": \"schema:alternateName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"last_active\": {\n          \"@id\": \"atlassian:lastActive\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"created\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"\
  product_access\": {\n          \"@id\": \"atlassian:productAccess\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"ProductAccess\": {\n      \"@id\": \"atlassian:ProductAccess\",\n      \"@context\": {\n        \"key\": {\n          \"@id\": \"atlassian:productKey\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"last_active\": {\n          \"@id\": \"atlassian:lastActive\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Domain\": {\n      \"@id\": \"atlassian:Domain\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"atlassian:domainId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"type\": {\n          \"@id\": \"atlassian:resourceType\",\n          \"@type\"\
  : \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"claim\": {\n          \"@id\": \"atlassian:domainClaim\",\n          \"@type\": \"@id\"\n        },\n        \"claimType\": {\n          \"@id\": \"atlassian:claimType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"claimStatus\": {\n          \"@id\": \"atlassian:claimStatus\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"Policy\": {\n      \"@id\": \"atlassian:Policy\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"atlassian:policyId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"type\": {\n          \"@id\": \"atlassian:policyType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"status\": {\n          \"@id\": \"atlassian:policyStatus\",\n   \
  \       \"@type\": \"xsd:string\"\n        },\n        \"attributes\": {\n          \"@id\": \"atlassian:policyAttributes\",\n          \"@type\": \"@id\"\n        },\n        \"resources\": {\n          \"@id\": \"atlassian:policyResources\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        },\n        \"created\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updated\": {\n          \"@id\": \"schema:dateModified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Event\": {\n      \"@id\": \"atlassian:Event\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"atlassian:eventId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"type\": {\n          \"@id\": \"atlassian:resourceType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"time\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"xsd:dateTime\"\n       \
  \ },\n        \"action\": {\n          \"@id\": \"atlassian:eventAction\",\n          \"@type\": \"xsd:string\"\n        },\n        \"actor\": {\n          \"@id\": \"atlassian:eventActor\",\n          \"@type\": \"@id\"\n        },\n        \"context\": {\n          \"@id\": \"atlassian:eventContext\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        },\n        \"container\": {\n          \"@id\": \"atlassian:eventContainer\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        },\n        \"location\": {\n          \"@id\": \"atlassian:eventLocation\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"EventActor\": {\n      \"@id\": \"atlassian:EventActor\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"atlassian:actorId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"type\": {\n\
  \          \"@id\": \"atlassian:actorType\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"EventLocation\": {\n      \"@id\": \"atlassian:EventLocation\",\n      \"@context\": {\n        \"ip\": {\n          \"@id\": \"atlassian:ipAddress\",\n          \"@type\": \"xsd:string\"\n        },\n        \"geo\": {\n          \"@id\": \"atlassian:geoLocation\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"Group\": {\n      \"@id\": \"atlassian:Group\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"atlassian:groupId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"type\": {\n          \"@id\": \"atlassian:resourceType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"\
  member_count\": {\n          \"@id\": \"atlassian:memberCount\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"RoleAssignment\": {\n      \"@id\": \"atlassian:RoleAssignment\",\n      \"@context\": {\n        \"role\": {\n          \"@id\": \"atlassian:roleName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"resource\": {\n          \"@id\": \"atlassian:roleResource\",\n          \"@type\": \"@id\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/atlassian/refs/heads/main/json-ld/atlassian-context.jsonld
tags:
- Code
- Collaboration
- Platform
- Productivity
- Software Development
- JSON-LD
- Linked Data
- Semantic Web
---
