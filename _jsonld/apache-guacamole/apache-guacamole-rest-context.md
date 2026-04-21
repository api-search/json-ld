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
