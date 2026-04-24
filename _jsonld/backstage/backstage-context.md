---
class_count: 16
classes:
- Action
- AuthResponse
- Backstage Catalog Entity
- ConditionalRequest
- Entity
- EntityMetadata
- EntityRelation
- JwksResponse
- Location
- PermissionDecision
- PermissionRequest
- SearchDocument
- SearchResult
- SearchResultSet
- Task
- TechDocsMetadata
context_file: json-ld/backstage-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/backstage/refs/heads/main/json-ld/backstage-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Backstage from Backstage.
layout: jsonld
name: Backstage Context
namespaces:
- prefix: backstage
  uri: https://backstage.io/schema/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: schema
  type: string
- container: ''
  name: annotations
  type: string
- container: ''
  name: apiVersion
  type: string
- container: ''
  name: backstageIdentity
  type: string
- container: ''
  name: buildTimestamp
  type: dateTime
- container: ''
  name: completedAt
  type: dateTime
- container: ''
  name: conditions
  type: string
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: createdBy
  type: string
- container: ''
  name: description
  type: ''
- container: ''
  name: document
  type: string
- container: ''
  name: etag
  type: string
- container: set
  name: files
  type: string
- container: ''
  name: highlight
  type: string
- container: ''
  name: id
  type: string
- container: set
  name: keys
  type: string
- container: ''
  name: kind
  type: string
- container: ''
  name: labels
  type: string
- container: ''
  name: lastHeartbeatAt
  type: dateTime
- container: set
  name: links
  type: string
- container: ''
  name: location
  type: string
- container: ''
  name: metadata
  type: string
- container: ''
  name: name
  type: ''
- container: ''
  name: namespace
  type: string
- container: ''
  name: nextPageCursor
  type: string
- container: ''
  name: numberOfResults
  type: integer
- container: ''
  name: permission
  type: string
- container: ''
  name: pluginId
  type: string
- container: ''
  name: previousPageCursor
  type: string
- container: ''
  name: profile
  type: string
- container: ''
  name: providerInfo
  type: string
- container: ''
  name: rank
  type: string
- container: set
  name: relations
  type: string
- container: ''
  name: resourceRef
  type: string
- container: ''
  name: resourceType
  type: string
- container: ''
  name: result
  type: string
- container: set
  name: results
  type: string
- container: ''
  name: siteDescription
  type: string
- container: ''
  name: siteName
  type: string
- container: ''
  name: spec
  type: string
- container: ''
  name: status
  type: string
- container: set
  name: tags
  type: string
- container: ''
  name: target
  type: string
- container: ''
  name: targetRef
  type: string
- container: ''
  name: text
  type: string
- container: ''
  name: title
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: uid
  type: string
property_count: 48
provider_name: Backstage
provider_slug: backstage
slug: backstage-context
tags:
- Developer Portal
- Internal Developer Platform
- Software Catalog
- Open Source
- JSON-LD
- Linked Data
- Semantic Web
---
