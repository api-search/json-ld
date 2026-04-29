---
class_count: 12
classes:
- LoginRequest
- LoginResponse
- TokenResponse
- Session
- PermissionCheckRequest
- PermissionCheckResult
- RoleList
- UserList
- User
- UserRequest
- HashRequest
- HashResult
context_file: json-ld/apache-shiro-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apache-shiro/refs/heads/main/json-ld/apache-shiro-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apache Shiro from Apache Shiro.
layout: jsonld
name: Apache Shiro Context
namespaces:
- prefix: shir
  uri: https://shiro.apache.org/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: username
  type: string
- container: ''
  name: password
  type: string
- container: ''
  name: rememberMe
  type: boolean
- container: ''
  name: sessionId
  type: string
- container: ''
  name: principal
  type: string
- container: set
  name: roles
  type: ''
- container: set
  name: permissions
  type: ''
- container: ''
  name: token
  type: string
- container: ''
  name: tokenType
  type: string
- container: ''
  name: expiresIn
  type: integer
- container: ''
  name: id
  type: string
- container: ''
  name: startTimestamp
  type: string
- container: ''
  name: lastAccessTime
  type: string
- container: ''
  name: timeout
  type: integer
- container: ''
  name: host
  type: string
- container: ''
  name: expired
  type: boolean
- container: ''
  name: permission
  type: string
- container: ''
  name: permitted
  type: boolean
- container: set
  name: users
  type: ''
- container: ''
  name: total
  type: integer
- container: ''
  name: email
  type: string
- container: ''
  name: locked
  type: boolean
- container: ''
  name: algorithm
  type: string
- container: ''
  name: iterations
  type: integer
- container: ''
  name: hash
  type: string
- container: ''
  name: salt
  type: string
property_count: 26
provider_name: Apache Shiro
provider_slug: apache-shiro
slug: apache-shiro-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"shir\": \"https://shiro.apache.org/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"LoginRequest\": \"shir:LoginRequest\",\n    \"LoginResponse\": \"shir:LoginResponse\",\n    \"TokenResponse\": \"shir:TokenResponse\",\n    \"Session\": \"shir:Session\",\n    \"PermissionCheckRequest\": \"shir:PermissionCheckRequest\",\n    \"PermissionCheckResult\": \"shir:PermissionCheckResult\",\n    \"RoleList\": \"shir:RoleList\",\n    \"UserList\": \"shir:UserList\",\n    \"User\": \"shir:User\",\n    \"UserRequest\": \"shir:UserRequest\",\n    \"HashRequest\": \"shir:HashRequest\",\n    \"HashResult\": \"shir:HashResult\",\n    \"username\": {\n      \"@id\": \"shir:username\",\n      \"@type\": \"xsd:string\"\n    },\n    \"password\": {\n      \"@id\": \"shir:password\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rememberMe\": {\n      \"@id\": \"shir:rememberMe\"\
  ,\n      \"@type\": \"xsd:boolean\"\n    },\n    \"sessionId\": {\n      \"@id\": \"shir:sessionId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"principal\": {\n      \"@id\": \"shir:principal\",\n      \"@type\": \"xsd:string\"\n    },\n    \"roles\": {\n      \"@id\": \"shir:roles\",\n      \"@container\": \"@set\"\n    },\n    \"permissions\": {\n      \"@id\": \"shir:permissions\",\n      \"@container\": \"@set\"\n    },\n    \"token\": {\n      \"@id\": \"shir:token\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tokenType\": {\n      \"@id\": \"shir:tokenType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"expiresIn\": {\n      \"@id\": \"shir:expiresIn\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"id\": {\n      \"@id\": \"shir:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startTimestamp\": {\n      \"@id\": \"shir:startTimestamp\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastAccessTime\": {\n      \"@id\": \"shir:lastAccessTime\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"timeout\": {\n      \"@id\": \"shir:timeout\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"host\": {\n      \"@id\": \"shir:host\",\n      \"@type\": \"xsd:string\"\n    },\n    \"expired\": {\n      \"@id\": \"shir:expired\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"permission\": {\n      \"@id\": \"shir:permission\",\n      \"@type\": \"xsd:string\"\n    },\n    \"permitted\": {\n      \"@id\": \"shir:permitted\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"users\": {\n      \"@id\": \"shir:users\",\n      \"@container\": \"@set\"\n    },\n    \"total\": {\n      \"@id\": \"shir:total\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"email\": {\n      \"@id\": \"shir:email\",\n      \"@type\": \"xsd:string\"\n    },\n    \"locked\": {\n      \"@id\": \"shir:locked\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"algorithm\": {\n      \"@id\": \"shir:algorithm\",\n      \"@type\": \"xsd:string\"\n    },\n    \"iterations\": {\n  \
  \    \"@id\": \"shir:iterations\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"hash\": {\n      \"@id\": \"shir:hash\",\n      \"@type\": \"xsd:string\"\n    },\n    \"salt\": {\n      \"@id\": \"shir:salt\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/apache-shiro/refs/heads/main/json-ld/apache-shiro-context.jsonld
tags:
- Authentication
- Authorization
- Cryptography
- Java
- Security
- Apache
- Open Source
- JSON-LD
- Linked Data
- Semantic Web
---
