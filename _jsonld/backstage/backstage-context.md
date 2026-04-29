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
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"backstage\": \"https://backstage.io/schema/\",\n    \"schema\": {\n      \"@id\": \"backstage:schema\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Action\": \"backstage:Action\",\n    \"AuthResponse\": \"backstage:AuthResponse\",\n    \"Backstage Catalog Entity\": \"backstage:Backstage Catalog Entity\",\n    \"ConditionalRequest\": \"backstage:ConditionalRequest\",\n    \"Entity\": \"backstage:Entity\",\n    \"EntityMetadata\": \"backstage:EntityMetadata\",\n    \"EntityRelation\": \"backstage:EntityRelation\",\n    \"JwksResponse\": \"backstage:JwksResponse\",\n    \"Location\": \"backstage:Location\",\n    \"PermissionDecision\": \"backstage:PermissionDecision\",\n    \"PermissionRequest\": \"backstage:PermissionRequest\",\n    \"SearchDocument\": \"backstage:SearchDocument\",\n    \"SearchResult\": \"backstage:SearchResult\"\
  ,\n    \"SearchResultSet\": \"backstage:SearchResultSet\",\n    \"Task\": \"backstage:Task\",\n    \"TechDocsMetadata\": \"backstage:TechDocsMetadata\",\n    \"annotations\": {\n      \"@id\": \"backstage:annotations\",\n      \"@type\": \"xsd:string\"\n    },\n    \"apiVersion\": {\n      \"@id\": \"backstage:apiVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"backstageIdentity\": {\n      \"@id\": \"backstage:backstageIdentity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"buildTimestamp\": {\n      \"@id\": \"backstage:build_timestamp\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"completedAt\": {\n      \"@id\": \"backstage:completedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"conditions\": {\n      \"@id\": \"backstage:conditions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdAt\": {\n      \"@id\": \"backstage:createdAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"createdBy\": {\n      \"@id\": \"backstage:createdBy\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\"\n    },\n    \"document\": {\n      \"@id\": \"backstage:document\",\n      \"@type\": \"xsd:string\"\n    },\n    \"etag\": {\n      \"@id\": \"backstage:etag\",\n      \"@type\": \"xsd:string\"\n    },\n    \"files\": {\n      \"@id\": \"backstage:files\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"highlight\": {\n      \"@id\": \"backstage:highlight\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"backstage:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"keys\": {\n      \"@id\": \"backstage:keys\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"kind\": {\n      \"@id\": \"backstage:kind\",\n      \"@type\": \"xsd:string\"\n    },\n    \"labels\": {\n      \"@id\": \"backstage:labels\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastHeartbeatAt\": {\n      \"@id\": \"backstage:lastHeartbeatAt\"\
  ,\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"links\": {\n      \"@id\": \"backstage:links\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"location\": {\n      \"@id\": \"backstage:location\",\n      \"@type\": \"xsd:string\"\n    },\n    \"metadata\": {\n      \"@id\": \"backstage:metadata\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\"\n    },\n    \"namespace\": {\n      \"@id\": \"backstage:namespace\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nextPageCursor\": {\n      \"@id\": \"backstage:nextPageCursor\",\n      \"@type\": \"xsd:string\"\n    },\n    \"numberOfResults\": {\n      \"@id\": \"backstage:numberOfResults\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"permission\": {\n      \"@id\": \"backstage:permission\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pluginId\": {\n      \"@id\": \"backstage:pluginId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"previousPageCursor\"\
  : {\n      \"@id\": \"backstage:previousPageCursor\",\n      \"@type\": \"xsd:string\"\n    },\n    \"profile\": {\n      \"@id\": \"backstage:profile\",\n      \"@type\": \"xsd:string\"\n    },\n    \"providerInfo\": {\n      \"@id\": \"backstage:providerInfo\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rank\": {\n      \"@id\": \"backstage:rank\",\n      \"@type\": \"xsd:string\"\n    },\n    \"relations\": {\n      \"@id\": \"backstage:relations\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resourceRef\": {\n      \"@id\": \"backstage:resourceRef\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resourceType\": {\n      \"@id\": \"backstage:resourceType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"result\": {\n      \"@id\": \"backstage:result\",\n      \"@type\": \"xsd:string\"\n    },\n    \"results\": {\n      \"@id\": \"backstage:results\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"siteDescription\"\
  : {\n      \"@id\": \"backstage:site_description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"siteName\": {\n      \"@id\": \"backstage:site_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"spec\": {\n      \"@id\": \"backstage:spec\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"backstage:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tags\": {\n      \"@id\": \"backstage:tags\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"target\": {\n      \"@id\": \"backstage:target\",\n      \"@type\": \"xsd:string\"\n    },\n    \"targetRef\": {\n      \"@id\": \"backstage:targetRef\",\n      \"@type\": \"xsd:string\"\n    },\n    \"text\": {\n      \"@id\": \"backstage:text\",\n      \"@type\": \"xsd:string\"\n    },\n    \"title\": {\n      \"@id\": \"backstage:title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"backstage:type\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"uid\": {\n      \"@id\": \"backstage:uid\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/backstage/refs/heads/main/json-ld/backstage-context.jsonld
tags:
- Developer Portal
- Internal Developer Platform
- Software Catalog
- Open Source
- JSON-LD
- Linked Data
- Semantic Web
---
