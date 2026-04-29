---
class_count: 9
classes:
- AuthToken
- username
- Connection
- name
- ConnectionGroup
- User
- UserGroup
- ActiveConnection
- ConnectionHistoryEntry
context_file: json-ld/apache-guacamole-rest-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apache-guacamole/refs/heads/main/json-ld/apache-guacamole-rest-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apache Guacamole Rest from Apache Guacamole.
layout: jsonld
name: Apache Guacamole Rest Context
namespaces:
- prefix: guacamole
  uri: https://guacamole.apache.org/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: authToken
  type: string
- container: ''
  name: dataSource
  type: string
- container: ''
  name: availableDataSources
  type: '@set'
- container: ''
  name: identifier
  type: string
- container: ''
  name: protocol
  type: string
- container: ''
  name: parentIdentifier
  type: string
- container: ''
  name: activeConnections
  type: integer
- container: ''
  name: parameters
  type: reference
- container: ''
  name: type
  type: string
- container: ''
  name: password
  type: string
- container: ''
  name: attributes
  type: reference
- container: ''
  name: lastActive
  type: integer
- container: ''
  name: connectionIdentifier
  type: string
- container: ''
  name: startDate
  type: integer
- container: ''
  name: remoteHost
  type: string
- container: ''
  name: connectionName
  type: string
- container: ''
  name: endDate
  type: integer
property_count: 17
provider_name: Apache Guacamole
provider_slug: apache-guacamole
slug: apache-guacamole-rest-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"guacamole\": \"https://guacamole.apache.org/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AuthToken\": \"guacamole:AuthToken\",\n    \"authToken\": {\n      \"@id\": \"guacamole:authToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"username\": \"schema:name\",\n    \"dataSource\": {\n      \"@id\": \"guacamole:dataSource\",\n      \"@type\": \"xsd:string\"\n    },\n    \"availableDataSources\": {\n      \"@id\": \"guacamole:availableDataSources\",\n      \"@type\": \"@set\"\n    },\n    \"Connection\": \"guacamole:Connection\",\n    \"identifier\": {\n      \"@id\": \"guacamole:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"protocol\": {\n      \"@id\": \"guacamole:protocol\",\n      \"@type\": \"xsd:string\"\n    },\n    \"parentIdentifier\": {\n      \"@id\": \"guacamole:parentIdentifier\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"activeConnections\": {\n      \"@id\": \"guacamole:activeConnections\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"parameters\": {\n      \"@id\": \"guacamole:parameters\",\n      \"@type\": \"@id\"\n    },\n    \"ConnectionGroup\": \"guacamole:ConnectionGroup\",\n    \"type\": {\n      \"@id\": \"guacamole:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"User\": \"guacamole:User\",\n    \"password\": {\n      \"@id\": \"guacamole:password\",\n      \"@type\": \"xsd:string\"\n    },\n    \"attributes\": {\n      \"@id\": \"guacamole:attributes\",\n      \"@type\": \"@id\"\n    },\n    \"lastActive\": {\n      \"@id\": \"guacamole:lastActive\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"UserGroup\": \"guacamole:UserGroup\",\n    \"ActiveConnection\": \"guacamole:ActiveConnection\",\n    \"connectionIdentifier\": {\n      \"@id\": \"guacamole:connectionIdentifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startDate\": {\n      \"\
  @id\": \"guacamole:startDate\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"remoteHost\": {\n      \"@id\": \"guacamole:remoteHost\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ConnectionHistoryEntry\": \"guacamole:ConnectionHistoryEntry\",\n    \"connectionName\": {\n      \"@id\": \"guacamole:connectionName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"endDate\": {\n      \"@id\": \"guacamole:endDate\",\n      \"@type\": \"xsd:integer\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/apache-guacamole/refs/heads/main/json-ld/apache-guacamole-rest-context.jsonld
tags:
- Apache
- Open Source
- RDP
- Remote Access
- Remote Desktop
- SSH
- VNC
- Web Gateway
- JSON-LD
- Linked Data
- Semantic Web
---
