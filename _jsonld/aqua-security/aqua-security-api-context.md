---
class_count: 20
classes:
- LoginRequest
- LoginResponse
- ErrorResponse
- VulnerabilityCounts
- Image
- ImageList
- ImageRequest
- Container
- ContainerList
- Policy
- PolicyList
- PolicyRequest
- Registry
- RegistryList
- User
- UserList
- description
- email
- name
- url
context_file: json-ld/aqua-security-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/aqua-security/refs/heads/main/json-ld/aqua-security-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Aqua Security Api from Aqua Security.
layout: jsonld
name: Aqua Security Api Context
namespaces:
- prefix: aqua
  uri: https://aquasec.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: blockFailed
  type: boolean
- container: ''
  name: code
  type: integer
- container: ''
  name: containerId
  type: string
- container: ''
  name: count
  type: integer
- container: ''
  name: critical
  type: integer
- container: ''
  name: digest
  type: string
- container: ''
  name: disallowed
  type: boolean
- container: ''
  name: high
  type: integer
- container: ''
  name: host
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: image
  type: string
- container: ''
  name: low
  type: integer
- container: ''
  name: maximumScore
  type: decimal
- container: ''
  name: medium
  type: integer
- container: ''
  name: message
  type: string
- container: ''
  name: negligible
  type: integer
- container: ''
  name: password
  type: string
- container: ''
  name: policy
  type: string
- container: ''
  name: registry
  type: string
- container: set
  name: result
  type: string
- container: ''
  name: role
  type: string
- container: ''
  name: scanStatus
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: tag
  type: string
- container: ''
  name: token
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: username
  type: string
- container: ''
  name: vulnerabilities
  type: string
property_count: 28
provider_name: Aqua Security
provider_slug: aqua-security
slug: aqua-security-api-context
tags:
- Cloud Native
- Containers
- Kubernetes
- Runtime Protection
- Security
- Vulnerability Scanning
- JSON-LD
- Linked Data
- Semantic Web
---
