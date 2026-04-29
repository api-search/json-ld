---
class_count: 16
classes:
- ChildNode
- DbQuery
- FetchNodeDbInfo
- JobConfig
- JobInfo
- LinkSchema
- NodeSchema
- NutchConfig
- NutchServerInfo
- ReaderConfig
- SeedList
- SeedUrl
- ServiceConfig
- ServiceInfo
- name
- url
context_file: json-ld/apache-nutch-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apache-nutch/refs/heads/main/json-ld/apache-nutch-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apache Nutch from Apache Nutch.
layout: jsonld
name: Apache Nutch Context
namespaces:
- prefix: nutch
  uri: https://nutch.apache.org/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: anchor
  type: string
- container: ''
  name: anchorText
  type: string
- container: ''
  name: args
  type: reference
- container: ''
  name: childUrl
  type: string
- container: set
  name: children
  type: string
- container: ''
  name: confId
  type: string
- container: ''
  name: configId
  type: string
- container: set
  name: configuration
  type: string
- container: ''
  name: crawlId
  type: string
- container: set
  name: dumpPaths
  type: string
- container: ''
  name: force
  type: boolean
- container: ''
  name: id
  type: string
- container: ''
  name: inlinkScore
  type: string
- container: ''
  name: jobClassName
  type: string
- container: set
  name: jobs
  type: string
- container: ''
  name: keyUrl
  type: string
- container: ''
  name: linktype
  type: string
- container: ''
  name: metadata
  type: string
- container: ''
  name: msg
  type: string
- container: ''
  name: numOfOutlinks
  type: integer
- container: ''
  name: numInlinks
  type: string
- container: ''
  name: numOutlinks
  type: string
- container: ''
  name: outlinkScore
  type: string
- container: ''
  name: params
  type: reference
- container: ''
  name: path
  type: string
- container: ''
  name: result
  type: reference
- container: set
  name: runningJobs
  type: string
- container: ''
  name: score
  type: string
- container: ''
  name: seedFilePath
  type: string
- container: set
  name: seedUrls
  type: string
- container: ''
  name: startDate
  type: dateTime
- container: ''
  name: state
  type: string
- container: ''
  name: status
  type: integer
- container: ''
  name: timestamp
  type: string
- container: ''
  name: type
  type: string
property_count: 35
provider_name: Apache Nutch
provider_slug: apache-nutch
slug: apache-nutch-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"nutch\": \"https://nutch.apache.org/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ChildNode\": \"nutch:ChildNode\",\n    \"DbQuery\": \"nutch:DbQuery\",\n    \"FetchNodeDbInfo\": \"nutch:FetchNodeDbInfo\",\n    \"JobConfig\": \"nutch:JobConfig\",\n    \"JobInfo\": \"nutch:JobInfo\",\n    \"LinkSchema\": \"nutch:LinkSchema\",\n    \"NodeSchema\": \"nutch:NodeSchema\",\n    \"NutchConfig\": \"nutch:NutchConfig\",\n    \"NutchServerInfo\": \"nutch:NutchServerInfo\",\n    \"ReaderConfig\": \"nutch:ReaderConfig\",\n    \"SeedList\": \"nutch:SeedList\",\n    \"SeedUrl\": \"nutch:SeedUrl\",\n    \"ServiceConfig\": \"nutch:ServiceConfig\",\n    \"ServiceInfo\": \"nutch:ServiceInfo\",\n    \"anchor\": {\n      \"@id\": \"nutch:anchor\",\n      \"@type\": \"xsd:string\"\n    },\n    \"anchorText\": {\n      \"@id\": \"\
  nutch:anchorText\",\n      \"@type\": \"xsd:string\"\n    },\n    \"args\": {\n      \"@id\": \"nutch:args\",\n      \"@type\": \"@id\"\n    },\n    \"childUrl\": {\n      \"@id\": \"nutch:childUrl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"children\": {\n      \"@id\": \"nutch:children\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"confId\": {\n      \"@id\": \"nutch:confId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"configId\": {\n      \"@id\": \"nutch:configId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"configuration\": {\n      \"@id\": \"nutch:configuration\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"crawlId\": {\n      \"@id\": \"nutch:crawlId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dumpPaths\": {\n      \"@id\": \"nutch:dumpPaths\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"force\": {\n      \"@id\": \"nutch:force\",\n      \"@type\"\
  : \"xsd:boolean\"\n    },\n    \"id\": {\n      \"@id\": \"nutch:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"inlinkScore\": {\n      \"@id\": \"nutch:inlink_score\",\n      \"@type\": \"xsd:string\"\n    },\n    \"jobClassName\": {\n      \"@id\": \"nutch:jobClassName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"jobs\": {\n      \"@id\": \"nutch:jobs\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"keyUrl\": {\n      \"@id\": \"nutch:key_url\",\n      \"@type\": \"xsd:string\"\n    },\n    \"linktype\": {\n      \"@id\": \"nutch:linktype\",\n      \"@type\": \"xsd:string\"\n    },\n    \"metadata\": {\n      \"@id\": \"nutch:metadata\",\n      \"@type\": \"xsd:string\"\n    },\n    \"msg\": {\n      \"@id\": \"nutch:msg\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"numOfOutlinks\": {\n      \"@id\": \"nutch:numOfOutlinks\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"numInlinks\": {\n      \"@id\"\
  : \"nutch:num_inlinks\",\n      \"@type\": \"xsd:string\"\n    },\n    \"numOutlinks\": {\n      \"@id\": \"nutch:num_outlinks\",\n      \"@type\": \"xsd:string\"\n    },\n    \"outlinkScore\": {\n      \"@id\": \"nutch:outlink_score\",\n      \"@type\": \"xsd:string\"\n    },\n    \"params\": {\n      \"@id\": \"nutch:params\",\n      \"@type\": \"@id\"\n    },\n    \"path\": {\n      \"@id\": \"nutch:path\",\n      \"@type\": \"xsd:string\"\n    },\n    \"result\": {\n      \"@id\": \"nutch:result\",\n      \"@type\": \"@id\"\n    },\n    \"runningJobs\": {\n      \"@id\": \"nutch:runningJobs\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"score\": {\n      \"@id\": \"nutch:score\",\n      \"@type\": \"xsd:string\"\n    },\n    \"seedFilePath\": {\n      \"@id\": \"nutch:seedFilePath\",\n      \"@type\": \"xsd:string\"\n    },\n    \"seedUrls\": {\n      \"@id\": \"nutch:seedUrls\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n\
  \    },\n    \"startDate\": {\n      \"@id\": \"nutch:startDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"state\": {\n      \"@id\": \"nutch:state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"nutch:status\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"timestamp\": {\n      \"@id\": \"nutch:timestamp\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"nutch:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"url\": \"schema:url\"\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/apache-nutch/refs/heads/main/json-ld/apache-nutch-context.jsonld
tags:
- Web Crawler
- Indexing
- Search
- Apache
- Java
- Hadoop
- Open Source
- JSON-LD
- Linked Data
- Semantic Web
---
