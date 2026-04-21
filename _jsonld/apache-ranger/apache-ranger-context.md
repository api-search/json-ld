---
class_count: 13
classes:
- PolicyList
- Policy
- PolicyResource
- PolicyItem
- AccessType
- ServiceList
- RangerService
- UserList
- RangerUser
- GroupList
- RangerGroup
- AuditList
- AuditEntry
context_file: json-ld/apache-ranger-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apache-ranger/refs/heads/main/json-ld/apache-ranger-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apache Ranger from Apache Ranger.
layout: jsonld
name: Apache Ranger Context
namespaces:
- prefix: rang
  uri: https://ranger.apache.org/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: totalCount
  type: integer
- container: ''
  name: pageSize
  type: integer
- container: ''
  name: resultSize
  type: integer
- container: set
  name: policies
  type: ''
- container: ''
  name: id
  type: integer
- container: ''
  name: name
  type: schema:name
- container: ''
  name: serviceType
  type: string
- container: ''
  name: serviceName
  type: string
- container: ''
  name: description
  type: schema:description
- container: ''
  name: isEnabled
  type: boolean
- container: ''
  name: isAuditEnabled
  type: boolean
- container: ''
  name: resources
  type: string
- container: set
  name: policyItems
  type: ''
- container: set
  name: values
  type: ''
- container: ''
  name: isRecursive
  type: boolean
- container: ''
  name: isExcludes
  type: boolean
- container: set
  name: users
  type: ''
- container: set
  name: groups
  type: ''
- container: set
  name: accesses
  type: ''
- container: set
  name: conditions
  type: ''
- container: ''
  name: type
  type: string
- container: ''
  name: isAllowed
  type: boolean
- container: set
  name: services
  type: ''
- container: ''
  name: configs
  type: string
- container: ''
  name: firstName
  type: string
- container: ''
  name: lastName
  type: string
- container: ''
  name: emailAddress
  type: string
- container: ''
  name: userSource
  type: integer
- container: ''
  name: status
  type: integer
- container: ''
  name: groupSource
  type: integer
- container: set
  name: auditList
  type: ''
- container: ''
  name: user
  type: string
- container: ''
  name: resourceType
  type: string
- container: ''
  name: resourcePath
  type: string
- container: ''
  name: accessType
  type: string
- container: ''
  name: result
  type: integer
- container: ''
  name: aclEnforcer
  type: string
- container: ''
  name: agentId
  type: string
- container: ''
  name: repoName
  type: string
- container: ''
  name: sessionId
  type: string
- container: ''
  name: clientIP
  type: string
- container: ''
  name: eventTime
  type: string
property_count: 42
provider_name: Apache Ranger
provider_slug: apache-ranger
slug: apache-ranger-context
tags:
- Access Control
- Authorization
- Hadoop
- Policy Management
- Security
- Apache
- Open Source
- JSON-LD
- Linked Data
- Semantic Web
---
