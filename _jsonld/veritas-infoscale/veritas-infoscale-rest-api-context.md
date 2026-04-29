---
api_specs:
- filename: veritas-infoscale-rest-api.yaml
  format: yaml
  label: Veritas InfoScale REST API
  slug: rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/veritas-infoscale/refs/heads/main/openapi/veritas-infoscale-rest-api.yaml
class_count: 10
classes:
- Cluster
- ServiceGroup
- Resource
- System
- DiskGroup
- Volume
- Disk
- Snapshot
- Alert
- Job
context_file: json-ld/veritas-infoscale-rest-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/veritas-infoscale/refs/heads/main/json-ld/veritas-infoscale-rest-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Veritas Infoscale Rest Api from Veritas InfoScale.
layout: jsonld
name: Veritas Infoscale Rest Api Context
namespaces:
- prefix: veritas
  uri: https://www.veritas.com/support/en_US/doc/infoscale/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: clusterId
  type: string
- container: ''
  name: clusterName
  type: string
- container: ''
  name: name
  type: string
- container: ''
  name: state
  type: string
- container: ''
  name: nodeCount
  type: integer
- container: ''
  name: clusterVersion
  type: string
- container: ''
  name: fencingMode
  type: string
- container: ''
  name: uptime
  type: string
- container: ''
  name: lastModified
  type: dateTime
- container: list
  name: systemList
  type: ''
- container: ''
  name: currentSystem
  type: string
- container: ''
  name: autoStart
  type: boolean
- container: ''
  name: parallel
  type: boolean
- container: ''
  name: resourceCount
  type: integer
- container: ''
  name: groupType
  type: string
- container: ''
  name: critical
  type: boolean
- container: ''
  name: totalSize
  type: string
- container: ''
  name: freeSize
  type: string
- container: ''
  name: diskCount
  type: integer
- container: ''
  name: volumeCount
  type: integer
- container: ''
  name: layout
  type: string
- container: ''
  name: size
  type: string
- container: ''
  name: plexCount
  type: integer
- container: ''
  name: readPolicy
  type: string
- container: ''
  name: usageType
  type: string
- container: ''
  name: diskGroup
  type: string
- container: ''
  name: frozen
  type: boolean
- container: ''
  name: cpuUsage
  type: double
- container: ''
  name: memoryUsage
  type: double
- container: ''
  name: platform
  type: string
- container: ''
  name: architecture
  type: string
- container: ''
  name: severity
  type: string
- container: ''
  name: message
  type: string
- container: ''
  name: source
  type: string
- container: ''
  name: timestamp
  type: dateTime
- container: ''
  name: acknowledged
  type: boolean
- container: ''
  name: devicePath
  type: string
- container: ''
  name: mediaType
  type: string
property_count: 38
provider_name: Veritas InfoScale
provider_slug: veritas-infoscale
slug: veritas-infoscale-rest-api-context
source_filename: veritas-infoscale-rest-api-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"veritas\": \"https://www.veritas.com/support/en_US/doc/infoscale/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Cluster\": \"veritas:Cluster\",\n    \"ServiceGroup\": \"veritas:ServiceGroup\",\n    \"Resource\": \"veritas:Resource\",\n    \"System\": \"veritas:System\",\n    \"DiskGroup\": \"veritas:DiskGroup\",\n    \"Volume\": \"veritas:Volume\",\n    \"Disk\": \"veritas:Disk\",\n    \"Snapshot\": \"veritas:Snapshot\",\n    \"Alert\": \"veritas:Alert\",\n    \"Job\": \"veritas:Job\",\n\n    \"clusterId\": {\n      \"@id\": \"dcterms:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"clusterName\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"state\": {\n      \"@id\":\
  \ \"veritas:state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nodeCount\": {\n      \"@id\": \"veritas:nodeCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"clusterVersion\": {\n      \"@id\": \"schema:softwareVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fencingMode\": {\n      \"@id\": \"veritas:fencingMode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"uptime\": {\n      \"@id\": \"veritas:uptime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastModified\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"systemList\": {\n      \"@id\": \"veritas:systemList\",\n      \"@container\": \"@list\"\n    },\n    \"currentSystem\": {\n      \"@id\": \"veritas:currentSystem\",\n      \"@type\": \"xsd:string\"\n    },\n    \"autoStart\": {\n      \"@id\": \"veritas:autoStart\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"parallel\": {\n      \"@id\": \"veritas:parallel\",\n      \"@type\": \"xsd:boolean\"\n\
  \    },\n    \"resourceCount\": {\n      \"@id\": \"veritas:resourceCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"groupType\": {\n      \"@id\": \"veritas:groupType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"critical\": {\n      \"@id\": \"veritas:critical\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"totalSize\": {\n      \"@id\": \"veritas:totalSize\",\n      \"@type\": \"xsd:string\"\n    },\n    \"freeSize\": {\n      \"@id\": \"veritas:freeSize\",\n      \"@type\": \"xsd:string\"\n    },\n    \"diskCount\": {\n      \"@id\": \"veritas:diskCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"volumeCount\": {\n      \"@id\": \"veritas:volumeCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"layout\": {\n      \"@id\": \"veritas:layout\",\n      \"@type\": \"xsd:string\"\n    },\n    \"size\": {\n      \"@id\": \"veritas:size\",\n      \"@type\": \"xsd:string\"\n    },\n    \"plexCount\": {\n      \"@id\": \"veritas:plexCount\",\n      \"@type\"\
  : \"xsd:integer\"\n    },\n    \"readPolicy\": {\n      \"@id\": \"veritas:readPolicy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"usageType\": {\n      \"@id\": \"veritas:usageType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"diskGroup\": {\n      \"@id\": \"veritas:diskGroup\",\n      \"@type\": \"xsd:string\"\n    },\n    \"frozen\": {\n      \"@id\": \"veritas:frozen\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"cpuUsage\": {\n      \"@id\": \"veritas:cpuUsage\",\n      \"@type\": \"xsd:double\"\n    },\n    \"memoryUsage\": {\n      \"@id\": \"veritas:memoryUsage\",\n      \"@type\": \"xsd:double\"\n    },\n    \"platform\": {\n      \"@id\": \"schema:operatingSystem\",\n      \"@type\": \"xsd:string\"\n    },\n    \"architecture\": {\n      \"@id\": \"veritas:architecture\",\n      \"@type\": \"xsd:string\"\n    },\n    \"severity\": {\n      \"@id\": \"veritas:severity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"message\": {\n      \"@id\": \"schema:description\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"source\": {\n      \"@id\": \"veritas:source\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timestamp\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"acknowledged\": {\n      \"@id\": \"veritas:acknowledged\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"devicePath\": {\n      \"@id\": \"veritas:devicePath\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mediaType\": {\n      \"@id\": \"veritas:mediaType\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/veritas-infoscale/refs/heads/main/json-ld/veritas-infoscale-rest-api-context.jsonld
tags:
- Clustering
- Data Management
- Disaster Recovery
- High Availability
- Storage Management
- Virtualization
- JSON-LD
- Linked Data
- Semantic Web
---
