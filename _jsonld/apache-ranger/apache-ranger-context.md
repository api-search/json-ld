---
api_specs:
- filename: apache-ranger-rest-api.yaml
  format: yaml
  label: Apache Ranger REST API
  slug: apache-ranger-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/apache-ranger/refs/heads/main/openapi/apache-ranger-rest-api.yaml
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
source_filename: apache-ranger-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"rang\": \"https://ranger.apache.org/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"PolicyList\": \"rang:PolicyList\",\n    \"Policy\": \"rang:Policy\",\n    \"PolicyResource\": \"rang:PolicyResource\",\n    \"PolicyItem\": \"rang:PolicyItem\",\n    \"AccessType\": \"rang:AccessType\",\n    \"ServiceList\": \"rang:ServiceList\",\n    \"RangerService\": \"rang:RangerService\",\n    \"UserList\": \"rang:UserList\",\n    \"RangerUser\": \"rang:RangerUser\",\n    \"GroupList\": \"rang:GroupList\",\n    \"RangerGroup\": \"rang:RangerGroup\",\n    \"AuditList\": \"rang:AuditList\",\n    \"AuditEntry\": \"rang:AuditEntry\",\n    \"totalCount\": {\n      \"@id\": \"rang:totalCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"pageSize\": {\n      \"@id\": \"rang:pageSize\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"resultSize\": {\n      \"@id\": \"rang:resultSize\"\
  ,\n      \"@type\": \"xsd:integer\"\n    },\n    \"policies\": {\n      \"@id\": \"rang:policies\",\n      \"@container\": \"@set\"\n    },\n    \"id\": {\n      \"@id\": \"rang:id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"name\": {\n      \"@id\": \"rang:name\",\n      \"@type\": \"schema:name\"\n    },\n    \"serviceType\": {\n      \"@id\": \"rang:serviceType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"serviceName\": {\n      \"@id\": \"rang:serviceName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"rang:description\",\n      \"@type\": \"schema:description\"\n    },\n    \"isEnabled\": {\n      \"@id\": \"rang:isEnabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isAuditEnabled\": {\n      \"@id\": \"rang:isAuditEnabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"resources\": {\n      \"@id\": \"rang:resources\",\n      \"@type\": \"xsd:string\"\n    },\n    \"policyItems\": {\n      \"@id\": \"rang:policyItems\"\
  ,\n      \"@container\": \"@set\"\n    },\n    \"values\": {\n      \"@id\": \"rang:values\",\n      \"@container\": \"@set\"\n    },\n    \"isRecursive\": {\n      \"@id\": \"rang:isRecursive\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isExcludes\": {\n      \"@id\": \"rang:isExcludes\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"users\": {\n      \"@id\": \"rang:users\",\n      \"@container\": \"@set\"\n    },\n    \"groups\": {\n      \"@id\": \"rang:groups\",\n      \"@container\": \"@set\"\n    },\n    \"accesses\": {\n      \"@id\": \"rang:accesses\",\n      \"@container\": \"@set\"\n    },\n    \"conditions\": {\n      \"@id\": \"rang:conditions\",\n      \"@container\": \"@set\"\n    },\n    \"type\": {\n      \"@id\": \"rang:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isAllowed\": {\n      \"@id\": \"rang:isAllowed\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"services\": {\n      \"@id\": \"rang:services\",\n      \"@container\": \"@set\"\n   \
  \ },\n    \"configs\": {\n      \"@id\": \"rang:configs\",\n      \"@type\": \"xsd:string\"\n    },\n    \"firstName\": {\n      \"@id\": \"rang:firstName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastName\": {\n      \"@id\": \"rang:lastName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"emailAddress\": {\n      \"@id\": \"rang:emailAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"userSource\": {\n      \"@id\": \"rang:userSource\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"status\": {\n      \"@id\": \"rang:status\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"groupSource\": {\n      \"@id\": \"rang:groupSource\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"auditList\": {\n      \"@id\": \"rang:auditList\",\n      \"@container\": \"@set\"\n    },\n    \"user\": {\n      \"@id\": \"rang:user\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resourceType\": {\n      \"@id\": \"rang:resourceType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"\
  resourcePath\": {\n      \"@id\": \"rang:resourcePath\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accessType\": {\n      \"@id\": \"rang:accessType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"result\": {\n      \"@id\": \"rang:result\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"aclEnforcer\": {\n      \"@id\": \"rang:aclEnforcer\",\n      \"@type\": \"xsd:string\"\n    },\n    \"agentId\": {\n      \"@id\": \"rang:agentId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"repoName\": {\n      \"@id\": \"rang:repoName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sessionId\": {\n      \"@id\": \"rang:sessionId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"clientIP\": {\n      \"@id\": \"rang:clientIP\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eventTime\": {\n      \"@id\": \"rang:eventTime\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/apache-ranger/refs/heads/main/json-ld/apache-ranger-context.jsonld
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
