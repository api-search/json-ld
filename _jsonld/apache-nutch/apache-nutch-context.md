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
