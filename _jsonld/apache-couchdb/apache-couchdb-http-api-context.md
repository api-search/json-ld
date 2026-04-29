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
source_filename: apache-couchdb-http-api-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"couchdb\": {\n      \"@id\": \"couchdb:couchdb\",\n      \"@type\": \"xsd:string\"\n    },\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ServerInfo\": \"couchdb:ServerInfo\",\n    \"ClusterSetupResponse\": \"couchdb:ClusterSetupResponse\",\n    \"ChangeRow\": \"couchdb:ChangeRow\",\n    \"Document\": \"couchdb:Document\",\n    \"AllDocsResponse\": \"couchdb:AllDocsResponse\",\n    \"ErrorResponse\": \"couchdb:ErrorResponse\",\n    \"ViewResponse\": \"couchdb:ViewResponse\",\n    \"CreateIndexRequest\": \"couchdb:CreateIndexRequest\",\n    \"DocumentInput\": \"couchdb:DocumentInput\",\n    \"KeysRequest\": \"couchdb:KeysRequest\",\n    \"SessionInfo\": \"couchdb:SessionInfo\",\n    \"FindResponse\": \"couchdb:FindResponse\",\n    \"IndexesResponse\": \"couchdb:IndexesResponse\",\n    \"FindRequest\": \"couchdb:FindRequest\"\
  ,\n    \"WriteResponse\": \"couchdb:WriteResponse\",\n    \"ChangesResponse\": \"couchdb:ChangesResponse\",\n    \"BulkDocsRequest\": \"couchdb:BulkDocsRequest\",\n    \"ReplicationResponse\": \"couchdb:ReplicationResponse\",\n    \"DocRow\": \"couchdb:DocRow\",\n    \"DatabaseInfo\": \"couchdb:DatabaseInfo\",\n    \"ReplicationRequest\": \"couchdb:ReplicationRequest\",\n    \"OkResponse\": \"couchdb:OkResponse\",\n    \"CreateIndexResponse\": \"couchdb:CreateIndexResponse\",\n    \"SessionRequest\": \"couchdb:SessionRequest\",\n    \"Deleted\": {\n      \"@id\": \"couchdb:_deleted\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"Id\": {\n      \"@id\": \"couchdb:_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Rev\": {\n      \"@id\": \"couchdb:_rev\",\n      \"@type\": \"xsd:string\"\n    },\n    \"active\": {\n      \"@id\": \"couchdb:active\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"authenticationHandlers\": {\n      \"@id\": \"couchdb:authentication_handlers\",\n\
  \      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bookmark\": {\n      \"@id\": \"couchdb:bookmark\",\n      \"@type\": \"xsd:string\"\n    },\n    \"changes\": {\n      \"@id\": \"couchdb:changes\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"continuous\": {\n      \"@id\": \"couchdb:continuous\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"createTarget\": {\n      \"@id\": \"couchdb:create_target\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"dbName\": {\n      \"@id\": \"couchdb:db_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ddoc\": {\n      \"@id\": \"couchdb:ddoc\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deleted\": {\n      \"@id\": \"couchdb:deleted\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"doc\": {\n      \"@id\": \"couchdb:doc\",\n      \"@type\": \"@id\"\n    },\n    \"docCount\": {\n      \"@id\": \"couchdb:doc_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"docDelCount\"\
  : {\n      \"@id\": \"couchdb:doc_del_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"docIds\": {\n      \"@id\": \"couchdb:doc_ids\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"docs\": {\n      \"@id\": \"couchdb:docs\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"error\": {\n      \"@id\": \"couchdb:error\",\n      \"@type\": \"xsd:string\"\n    },\n    \"external\": {\n      \"@id\": \"couchdb:external\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"fields\": {\n      \"@id\": \"couchdb:fields\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"file\": {\n      \"@id\": \"couchdb:file\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"filter\": {\n      \"@id\": \"couchdb:filter\",\n      \"@type\": \"xsd:string\"\n    },\n    \"gitSha\": {\n      \"@id\": \"couchdb:git_sha\",\n      \"@type\": \"xsd:string\"\n    },\n    \"history\": {\n      \"@id\": \"couchdb:history\"\
  ,\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"id\": {\n      \"@id\": \"couchdb:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"index\": {\n      \"@id\": \"couchdb:index\",\n      \"@type\": \"@id\"\n    },\n    \"indexes\": {\n      \"@id\": \"couchdb:indexes\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"info\": {\n      \"@id\": \"couchdb:info\",\n      \"@type\": \"@id\"\n    },\n    \"key\": {\n      \"@id\": \"couchdb:key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"keys\": {\n      \"@id\": \"couchdb:keys\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastSeq\": {\n      \"@id\": \"couchdb:last_seq\",\n      \"@type\": \"xsd:string\"\n    },\n    \"limit\": {\n      \"@id\": \"couchdb:limit\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"name\": \"schema:name\",\n    \"newEdits\": {\n      \"@id\": \"couchdb:new_edits\",\n      \"@type\": \"xsd:boolean\"\n    },\n  \
  \  \"offset\": {\n      \"@id\": \"couchdb:offset\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"ok\": {\n      \"@id\": \"couchdb:ok\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"password\": {\n      \"@id\": \"couchdb:password\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pending\": {\n      \"@id\": \"couchdb:pending\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"reason\": {\n      \"@id\": \"couchdb:reason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"result\": {\n      \"@id\": \"couchdb:result\",\n      \"@type\": \"xsd:string\"\n    },\n    \"results\": {\n      \"@id\": \"couchdb:results\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"rev\": {\n      \"@id\": \"couchdb:rev\",\n      \"@type\": \"xsd:string\"\n    },\n    \"roles\": {\n      \"@id\": \"couchdb:roles\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rows\": {\n      \"@id\": \"couchdb:rows\",\n      \"@container\": \"@set\",\n\
  \      \"@type\": \"@id\"\n    },\n    \"selector\": {\n      \"@id\": \"couchdb:selector\",\n      \"@type\": \"@id\"\n    },\n    \"seq\": {\n      \"@id\": \"couchdb:seq\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sessionId\": {\n      \"@id\": \"couchdb:session_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sizes\": {\n      \"@id\": \"couchdb:sizes\",\n      \"@type\": \"@id\"\n    },\n    \"skip\": {\n      \"@id\": \"couchdb:skip\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"sort\": {\n      \"@id\": \"couchdb:sort\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"source\": {\n      \"@id\": \"couchdb:source\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sourceLastSeq\": {\n      \"@id\": \"couchdb:source_last_seq\",\n      \"@type\": \"xsd:string\"\n    },\n    \"state\": {\n      \"@id\": \"couchdb:state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"target\": {\n      \"@id\": \"couchdb:target\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"totalRows\": {\n      \"@id\": \"couchdb:total_rows\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"type\": {\n      \"@id\": \"couchdb:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"updateSeq\": {\n      \"@id\": \"couchdb:update_seq\",\n      \"@type\": \"xsd:string\"\n    },\n    \"userCtx\": {\n      \"@id\": \"couchdb:userCtx\",\n      \"@type\": \"@id\"\n    },\n    \"uuid\": {\n      \"@id\": \"couchdb:uuid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"couchdb:value\",\n      \"@type\": \"@id\"\n    },\n    \"vendor\": {\n      \"@id\": \"couchdb:vendor\",\n      \"@type\": \"@id\"\n    },\n    \"version\": \"schema:version\",\n    \"warning\": {\n      \"@id\": \"couchdb:warning\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/apache-couchdb/refs/heads/main/json-ld/apache-couchdb-http-api-context.jsonld
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
