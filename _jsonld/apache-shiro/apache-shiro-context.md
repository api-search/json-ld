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
