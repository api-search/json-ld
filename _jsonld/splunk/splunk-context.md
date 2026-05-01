---
api_specs:
- filename: splunk-enterprise-rest-api.yml
  format: yaml
  label: Splunk Enterprise REST API
  slug: splunk-enterprise-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/splunk/refs/heads/main/openapi/splunk-enterprise-rest-api.yml
- filename: openapi.json
  format: json
  label: Splunk Cloud ACS OpenAPI Specification
  slug: splunk-cloud-admin-config-service-openapi
  spec_type: OpenAPI
  url: https://admin.splunk.com/service/info/specs/v2/openapi.json
class_count: 0
classes: []
context_file: json-ld/splunk-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/splunk/refs/heads/main/json-ld/splunk-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Splunk from Splunk.
layout: jsonld
name: Splunk Context
namespaces:
- prefix: splunk
  uri: https://dev.splunk.com/enterprise/reference#
- prefix: splunkrest
  uri: https://docs.splunk.com/Documentation/Splunk/latest/RESTREF/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: hydra
  uri: http://www.w3.org/ns/hydra/core#
- prefix: spdx
  uri: http://spdx.org/rdf/terms#
- prefix: ssn
  uri: http://www.w3.org/ns/ssn/
- prefix: sosa
  uri: http://www.w3.org/ns/sosa/
properties:
- container: ''
  name: SearchJob
  type: ''
- container: ''
  name: Event
  type: ''
- container: ''
  name: Index
  type: ''
- container: ''
  name: DataInput
  type: ''
- container: ''
  name: MonitorInput
  type: ''
- container: ''
  name: HecToken
  type: ''
- container: ''
  name: SearchResults
  type: ''
- container: ''
  name: owner
  type: string
- container: ''
  name: app
  type: string
- container: ''
  name: sharing
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: name
  type: string
- container: ''
  name: id
  type: reference
- container: ''
  name: created
  type: dateTime
- container: ''
  name: modified
  type: dateTime
property_count: 15
provider_name: Splunk
provider_slug: splunk
slug: splunk-context
source_filename: splunk-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"@vocab\": \"https://schema.org/\",\n    \"splunk\": \"https://dev.splunk.com/enterprise/reference#\",\n    \"splunkrest\": \"https://docs.splunk.com/Documentation/Splunk/latest/RESTREF/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"hydra\": \"http://www.w3.org/ns/hydra/core#\",\n    \"spdx\": \"http://spdx.org/rdf/terms#\",\n    \"ssn\": \"http://www.w3.org/ns/ssn/\",\n    \"sosa\": \"http://www.w3.org/ns/sosa/\",\n\n    \"SearchJob\": {\n      \"@id\": \"splunk:SearchJob\",\n      \"@context\": {\n        \"sid\": {\n          \"@id\": \"splunk:searchId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"search\": {\n          \"@id\": \"splunk:searchQuery\",\n          \"@type\": \"xsd:string\"\n        },\n        \"dispatchState\": {\n          \"@id\": \"splunk:dispatchState\",\n          \"@type\": \"xsd:string\"\n        },\n        \"doneProgress\"\
  : {\n          \"@id\": \"splunk:doneProgress\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"scanCount\": {\n          \"@id\": \"splunk:scanCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"eventCount\": {\n          \"@id\": \"splunk:eventCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"resultCount\": {\n          \"@id\": \"splunk:resultCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"runDuration\": {\n          \"@id\": \"splunk:runDuration\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"earliestTime\": {\n          \"@id\": \"splunk:earliestTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"latestTime\": {\n          \"@id\": \"splunk:latestTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"cursorTime\": {\n          \"@id\": \"splunk:cursorTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"isDone\": {\n          \"@id\": \"splunk:isDone\"\
  ,\n          \"@type\": \"xsd:boolean\"\n        },\n        \"isFailed\": {\n          \"@id\": \"splunk:isFailed\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"isPaused\": {\n          \"@id\": \"splunk:isPaused\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"isFinalized\": {\n          \"@id\": \"splunk:isFinalized\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"isSaved\": {\n          \"@id\": \"splunk:isSaved\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"isRealTimeSearch\": {\n          \"@id\": \"splunk:isRealTimeSearch\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"ttl\": {\n          \"@id\": \"splunk:timeToLive\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"priority\": {\n          \"@id\": \"splunk:priority\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"author\": {\n          \"@id\": \"dcterms:creator\",\n          \"@type\": \"xsd:string\"\n        },\n    \
  \    \"published\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updated\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Event\": {\n      \"@id\": \"splunk:Event\",\n      \"@context\": {\n        \"time\": {\n          \"@id\": \"splunk:eventTime\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"_time\": {\n          \"@id\": \"splunk:indexedTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"_raw\": {\n          \"@id\": \"splunk:rawEvent\",\n          \"@type\": \"xsd:string\"\n        },\n        \"event\": {\n          \"@id\": \"splunk:eventPayload\"\n        },\n        \"host\": {\n          \"@id\": \"splunk:host\",\n          \"@type\": \"xsd:string\"\n        },\n        \"source\": {\n          \"@id\": \"splunk:source\",\n          \"@type\": \"xsd:string\"\n        },\n        \"sourcetype\": {\n          \"\
  @id\": \"splunk:sourcetype\",\n          \"@type\": \"xsd:string\"\n        },\n        \"index\": {\n          \"@id\": \"splunk:index\",\n          \"@type\": \"xsd:string\"\n        },\n        \"_indextime\": {\n          \"@id\": \"splunk:indexTime\",\n          \"@type\": \"xsd:string\"\n        },\n        \"linecount\": {\n          \"@id\": \"splunk:lineCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"splunk_server\": {\n          \"@id\": \"splunk:splunkServer\",\n          \"@type\": \"xsd:string\"\n        },\n        \"eventtype\": {\n          \"@id\": \"splunk:eventType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"tag\": {\n          \"@id\": \"splunk:tag\",\n          \"@container\": \"@set\"\n        },\n        \"fields\": {\n          \"@id\": \"splunk:metadataFields\"\n        }\n      }\n    },\n\n    \"Index\": {\n      \"@id\": \"splunk:Index\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"dcterms:title\"\
  ,\n          \"@type\": \"xsd:string\"\n        },\n        \"datatype\": {\n          \"@id\": \"splunk:datatype\",\n          \"@type\": \"xsd:string\"\n        },\n        \"totalEventCount\": {\n          \"@id\": \"splunk:totalEventCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"currentDBSizeMB\": {\n          \"@id\": \"splunk:currentDBSizeMB\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"maxTotalDataSizeMB\": {\n          \"@id\": \"splunk:maxTotalDataSizeMB\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"frozenTimePeriodInSecs\": {\n          \"@id\": \"splunk:frozenTimePeriodInSecs\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"homePath\": {\n          \"@id\": \"splunk:homePath\",\n          \"@type\": \"xsd:string\"\n        },\n        \"coldPath\": {\n          \"@id\": \"splunk:coldPath\",\n          \"@type\": \"xsd:string\"\n        },\n        \"thawedPath\": {\n          \"@id\": \"splunk:thawedPath\"\
  ,\n          \"@type\": \"xsd:string\"\n        },\n        \"disabled\": {\n          \"@id\": \"splunk:disabled\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"isInternal\": {\n          \"@id\": \"splunk:isInternal\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"minTime\": {\n          \"@id\": \"splunk:minTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"maxTime\": {\n          \"@id\": \"splunk:maxTime\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"DataInput\": {\n      \"@id\": \"splunk:DataInput\",\n      \"@context\": {\n        \"inputType\": {\n          \"@id\": \"splunk:inputType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"disabled\": {\n          \"@id\": \"splunk:disabled\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"index\": {\n          \"@id\": \"splunk:index\",\n          \"@type\": \"xsd:string\"\n        },\n        \"sourcetype\": {\n          \"\
  @id\": \"splunk:sourcetype\",\n          \"@type\": \"xsd:string\"\n        },\n        \"host\": {\n          \"@id\": \"splunk:host\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"MonitorInput\": {\n      \"@id\": \"splunk:MonitorInput\",\n      \"@context\": {\n        \"path\": {\n          \"@id\": \"splunk:monitorPath\",\n          \"@type\": \"xsd:string\"\n        },\n        \"recursive\": {\n          \"@id\": \"splunk:recursive\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"followTail\": {\n          \"@id\": \"splunk:followTail\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"whitelist\": {\n          \"@id\": \"splunk:whitelist\",\n          \"@type\": \"xsd:string\"\n        },\n        \"blacklist\": {\n          \"@id\": \"splunk:blacklist\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"HecToken\": {\n      \"@id\": \"splunk:HecToken\",\n      \"@context\": {\n        \"token\": {\n\
  \          \"@id\": \"splunk:tokenValue\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"dcterms:title\",\n          \"@type\": \"xsd:string\"\n        },\n        \"useACK\": {\n          \"@id\": \"splunk:useACK\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"indexes\": {\n          \"@id\": \"splunk:allowedIndexes\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"SearchResults\": {\n      \"@id\": \"splunk:SearchResults\",\n      \"@context\": {\n        \"init_offset\": {\n          \"@id\": \"splunk:initOffset\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"results\": {\n          \"@id\": \"splunk:resultEntries\",\n          \"@container\": \"@list\"\n        },\n        \"preview\": {\n          \"@id\": \"splunk:isPreview\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"owner\": {\n      \"@id\": \"dcterms:creator\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"app\": {\n      \"@id\": \"splunk:appContext\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sharing\": {\n      \"@id\": \"splunk:sharingLevel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"dcterms:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"dcterms:title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"@id\",\n      \"@type\": \"@id\"\n    },\n    \"created\": {\n      \"@id\": \"dcterms:created\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"modified\": {\n      \"@id\": \"dcterms:modified\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/splunk/refs/heads/main/json-ld/splunk-context.jsonld
tags:
- Analytics
- Data Analysis
- Logging
- Machine Data
- Monitoring
- Observability
- Platform
- Security
- SIEM
- JSON-LD
- Linked Data
- Semantic Web
---
