---
class_count: 26
classes:
- ServerInfo
- ClusterSetupResponse
- ChangeRow
- Document
- AllDocsResponse
- ErrorResponse
- ViewResponse
- CreateIndexRequest
- DocumentInput
- KeysRequest
- SessionInfo
- FindResponse
- IndexesResponse
- FindRequest
- WriteResponse
- ChangesResponse
- BulkDocsRequest
- ReplicationResponse
- DocRow
- DatabaseInfo
- ReplicationRequest
- OkResponse
- CreateIndexResponse
- SessionRequest
- name
- version
context_file: json-ld/apache-couchdb-http-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apache-couchdb/refs/heads/main/json-ld/apache-couchdb-http-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apache Couchdb Http Api from Apache CouchDB.
layout: jsonld
name: Apache Couchdb Http Api Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: couchdb
  type: string
- container: ''
  name: Deleted
  type: boolean
- container: ''
  name: Id
  type: string
- container: ''
  name: Rev
  type: string
- container: ''
  name: active
  type: integer
- container: set
  name: authenticationHandlers
  type: string
- container: ''
  name: bookmark
  type: string
- container: set
  name: changes
  type: reference
- container: ''
  name: continuous
  type: boolean
- container: ''
  name: createTarget
  type: boolean
- container: ''
  name: dbName
  type: string
- container: ''
  name: ddoc
  type: string
- container: ''
  name: deleted
  type: boolean
- container: ''
  name: doc
  type: reference
- container: ''
  name: docCount
  type: integer
- container: ''
  name: docDelCount
  type: integer
- container: set
  name: docIds
  type: string
- container: set
  name: docs
  type: reference
- container: ''
  name: error
  type: string
- container: ''
  name: external
  type: integer
- container: set
  name: fields
  type: string
- container: ''
  name: file
  type: integer
- container: ''
  name: filter
  type: string
- container: ''
  name: gitSha
  type: string
- container: set
  name: history
  type: reference
- container: ''
  name: id
  type: string
- container: ''
  name: index
  type: reference
- container: set
  name: indexes
  type: reference
- container: ''
  name: info
  type: reference
- container: ''
  name: key
  type: string
- container: set
  name: keys
  type: string
- container: ''
  name: lastSeq
  type: string
- container: ''
  name: limit
  type: integer
- container: ''
  name: newEdits
  type: boolean
- container: ''
  name: offset
  type: integer
- container: ''
  name: ok
  type: boolean
- container: ''
  name: password
  type: string
- container: ''
  name: pending
  type: integer
- container: ''
  name: reason
  type: string
- container: ''
  name: result
  type: string
- container: set
  name: results
  type: reference
- container: ''
  name: rev
  type: string
- container: set
  name: roles
  type: string
- container: set
  name: rows
  type: reference
- container: ''
  name: selector
  type: reference
- container: ''
  name: seq
  type: string
- container: ''
  name: sessionId
  type: string
- container: ''
  name: sizes
  type: reference
- container: ''
  name: skip
  type: integer
- container: set
  name: sort
  type: reference
- container: ''
  name: source
  type: string
- container: ''
  name: sourceLastSeq
  type: string
- container: ''
  name: state
  type: string
- container: ''
  name: target
  type: string
- container: ''
  name: totalRows
  type: integer
- container: ''
  name: type
  type: string
- container: ''
  name: updateSeq
  type: string
- container: ''
  name: userCtx
  type: reference
- container: ''
  name: uuid
  type: string
- container: ''
  name: value
  type: reference
- container: ''
  name: vendor
  type: reference
- container: ''
  name: warning
  type: string
property_count: 62
provider_name: Apache CouchDB
provider_slug: apache-couchdb
slug: apache-couchdb-http-api-context
tags:
- Apache
- Database
- Document Store
- JSON
- NoSQL
- Open Source
- Replication
- REST
- JSON-LD
- Linked Data
- Semantic Web
---
