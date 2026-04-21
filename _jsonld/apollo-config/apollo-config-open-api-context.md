---
class_count: 6
classes:
- App
- Namespace
- Item
- Cluster
- Release
- name
context_file: json-ld/apollo-config-open-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apollo-config/refs/heads/main/json-ld/apollo-config-open-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apollo Config Open Api from Apollo Config.
layout: jsonld
name: Apollo Config Open Api Context
namespaces:
- prefix: apollo
  uri: https://apolloconfig.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: appId
  type: string
- container: ''
  name: orgId
  type: string
- container: ''
  name: orgName
  type: string
- container: ''
  name: ownerName
  type: string
- container: ''
  name: ownerEmail
  type: string
- container: ''
  name: dataChangeCreatedBy
  type: string
- container: ''
  name: dataChangeLastModifiedBy
  type: string
- container: ''
  name: dataChangeCreatedTime
  type: dateTime
- container: ''
  name: dataChangeLastModifiedTime
  type: dateTime
- container: ''
  name: clusterName
  type: string
- container: ''
  name: namespaceName
  type: string
- container: ''
  name: comment
  type: string
- container: ''
  name: format
  type: string
- container: ''
  name: isPublic
  type: boolean
- container: set
  name: items
  type: string
- container: ''
  name: id
  type: integer
- container: ''
  name: namespaceId
  type: integer
- container: ''
  name: key
  type: string
- container: ''
  name: value
  type: string
- container: ''
  name: lineNum
  type: integer
- container: ''
  name: isAbandoned
  type: boolean
- container: ''
  name: configurations
  type: reference
property_count: 22
provider_name: Apollo Config
provider_slug: apollo-config
slug: apollo-config-open-api-context
tags:
- Apache 2.0
- Configuration Management
- Ctrip
- Distributed Systems
- Java
- Microservices
- Open Source
- Real-Time Configuration
- JSON-LD
- Linked Data
- Semantic Web
---
