---
class_count: 1
classes:
- scim
context_file: json-ld/cisco-directory-connector-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/cisco-directory-connector/refs/heads/main/json-ld/cisco-directory-connector-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Cisco Directory Connector from Cisco Directory Connector.
layout: jsonld
name: Cisco Directory Connector Context
namespaces:
- prefix: webex
  uri: https://webexapis.com/v1/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: DirectorySyncJob
  type: ''
- container: ''
  name: User
  type: ''
- container: ''
  name: Group
  type: ''
- container: ''
  name: AttributeMapping
  type: ''
property_count: 4
provider_name: Cisco Directory Connector
provider_slug: cisco-directory-connector
slug: cisco-directory-connector-context
source_filename: cisco-directory-connector-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"webex\": \"https://webexapis.com/v1/\",\n    \"scim\": \"urn:ietf:params:scim:schemas:core:2.0:\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"DirectorySyncJob\": {\n      \"@id\": \"webex:DirectorySyncJob\",\n      \"@context\": {\n        \"id\": \"webex:id\",\n        \"orgId\": \"webex:org_id\",\n        \"status\": \"webex:status\",\n        \"syncType\": \"webex:sync_type\",\n        \"started\": {\n          \"@id\": \"schema:startTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"completed\": {\n          \"@id\": \"schema:endTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"usersAdded\": \"webex:users_added\",\n        \"usersUpdated\": \"webex:users_updated\",\n        \"usersDeleted\": \"webex:users_deleted\",\n        \"errors\": \"webex:errors\"\n      }\n    },\n\n\
  \    \"User\": {\n      \"@id\": \"scim:User\",\n      \"@context\": {\n        \"id\": \"scim:id\",\n        \"userName\": \"scim:userName\",\n        \"displayName\": \"schema:name\",\n        \"name\": \"scim:name\",\n        \"emails\": \"schema:email\",\n        \"active\": \"scim:active\",\n        \"groups\": \"scim:groups\",\n        \"phoneNumbers\": \"schema:telephone\",\n        \"title\": \"schema:jobTitle\",\n        \"externalId\": \"scim:externalId\",\n        \"meta\": \"scim:meta\"\n      }\n    },\n\n    \"Group\": {\n      \"@id\": \"scim:Group\",\n      \"@context\": {\n        \"id\": \"scim:id\",\n        \"displayName\": \"schema:name\",\n        \"members\": \"scim:members\",\n        \"externalId\": \"scim:externalId\",\n        \"meta\": \"scim:meta\"\n      }\n    },\n\n    \"AttributeMapping\": {\n      \"@id\": \"webex:AttributeMapping\",\n      \"@context\": {\n        \"directoryAttribute\": \"webex:directory_attribute\",\n        \"webexAttribute\": \"webex:webex_attribute\"\
  ,\n        \"transform\": \"webex:transform\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/cisco-directory-connector/refs/heads/main/json-ld/cisco-directory-connector-context.jsonld
tags:
- Active Directory
- Directory
- Enterprise
- Identity Management
- LDAP
- Provisioning
- SCIM
- Synchronization
- JSON-LD
- Linked Data
- Semantic Web
---
