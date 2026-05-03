---
api_specs:
- filename: snowplow-console-api-openapi.yml
  format: yaml
  label: Snowplow Console API
  slug: snowplow-console-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/snowplow/refs/heads/main/openapi/snowplow-console-api-openapi.yml
class_count: 6
classes:
- name
- description
- url
- identifier
- Organization
- SoftwareApplication
context_file: json-ld/snowplow-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/snowplow/refs/heads/main/json-ld/snowplow-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Snowplow from Snowplow.
layout: jsonld
name: Snowplow Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
- prefix: snow
  uri: https://api-evangelist.github.io/snowplow/vocabulary/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: DataPipeline
  type: schema:SoftwareApplication
- container: ''
  name: BehavioralEvent
  type: schema:Event
- container: ''
  name: DataStructure
  type: schema:DefinedTerm
- container: ''
  name: DataProduct
  type: schema:Dataset
- container: ''
  name: EventSpecification
  type: schema:DefinedTerm
- container: ''
  name: Tracker
  type: schema:SoftwareApplication
- container: ''
  name: Collector
  type: schema:SoftwareApplication
- container: ''
  name: SchemaRegistry
  type: schema:DataCatalog
- container: ''
  name: eventId
  type: string
- container: ''
  name: eventType
  type: string
- container: ''
  name: appId
  type: string
- container: ''
  name: platform
  type: string
- container: ''
  name: collectorTimestamp
  type: dateTime
- container: ''
  name: deviceCreatedTimestamp
  type: dateTime
- container: ''
  name: derivedTimestamp
  type: dateTime
- container: ''
  name: userId
  type: string
- container: ''
  name: domainUserId
  type: string
- container: ''
  name: sessionId
  type: string
- container: ''
  name: pageUrl
  type: anyURI
- container: ''
  name: pageTitle
  type: string
- container: ''
  name: schemaVendor
  type: string
- container: ''
  name: schemaName
  type: string
- container: ''
  name: schemaVersion
  type: string
- container: ''
  name: deployedEnvironment
  type: string
- container: ''
  name: igluUri
  type: anyURI
- container: ''
  name: organizationId
  type: string
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: updatedAt
  type: dateTime
- container: ''
  name: geoCountry
  type: string
- container: ''
  name: geoCity
  type: string
property_count: 30
provider_name: Snowplow
provider_slug: snowplow
slug: snowplow-context
source_filename: snowplow-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"snow\": \"https://api-evangelist.github.io/snowplow/vocabulary/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"identifier\": \"schema:identifier\",\n    \"Organization\": \"schema:Organization\",\n    \"SoftwareApplication\": \"schema:SoftwareApplication\",\n    \"DataPipeline\": {\n      \"@id\": \"snow:DataPipeline\",\n      \"@type\": \"schema:SoftwareApplication\"\n    },\n    \"BehavioralEvent\": {\n      \"@id\": \"snow:BehavioralEvent\",\n      \"@type\": \"schema:Event\"\n    },\n    \"DataStructure\": {\n      \"@id\": \"snow:DataStructure\",\n      \"@type\": \"schema:DefinedTerm\"\n    },\n    \"DataProduct\": {\n      \"@id\": \"snow:DataProduct\",\n      \"@type\": \"schema:Dataset\"\n    },\n    \"\
  EventSpecification\": {\n      \"@id\": \"snow:EventSpecification\",\n      \"@type\": \"schema:DefinedTerm\"\n    },\n    \"Tracker\": {\n      \"@id\": \"snow:Tracker\",\n      \"@type\": \"schema:SoftwareApplication\"\n    },\n    \"Collector\": {\n      \"@id\": \"snow:Collector\",\n      \"@type\": \"schema:SoftwareApplication\"\n    },\n    \"SchemaRegistry\": {\n      \"@id\": \"snow:SchemaRegistry\",\n      \"@type\": \"schema:DataCatalog\"\n    },\n    \"eventId\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eventType\": {\n      \"@id\": \"snow:eventType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"appId\": {\n      \"@id\": \"snow:appId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"platform\": {\n      \"@id\": \"snow:platform\",\n      \"@type\": \"xsd:string\"\n    },\n    \"collectorTimestamp\": {\n      \"@id\": \"snow:collectorTimestamp\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"deviceCreatedTimestamp\":\
  \ {\n      \"@id\": \"snow:deviceCreatedTimestamp\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"derivedTimestamp\": {\n      \"@id\": \"snow:derivedTimestamp\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"userId\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"domainUserId\": {\n      \"@id\": \"snow:domainUserId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sessionId\": {\n      \"@id\": \"snow:sessionId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pageUrl\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"xsd:anyURI\"\n    },\n    \"pageTitle\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"schemaVendor\": {\n      \"@id\": \"snow:schemaVendor\",\n      \"@type\": \"xsd:string\"\n    },\n    \"schemaName\": {\n      \"@id\": \"snow:schemaName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"schemaVersion\": {\n      \"@id\": \"schema:version\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"deployedEnvironment\": {\n      \"@id\": \"snow:deployedEnvironment\",\n      \"@type\": \"xsd:string\"\n    },\n    \"igluUri\": {\n      \"@id\": \"snow:igluUri\",\n      \"@type\": \"xsd:anyURI\"\n    },\n    \"organizationId\": {\n      \"@id\": \"snow:organizationId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"geoCountry\": {\n      \"@id\": \"schema:addressCountry\",\n      \"@type\": \"xsd:string\"\n    },\n    \"geoCity\": {\n      \"@id\": \"schema:addressLocality\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/snowplow/refs/heads/main/json-ld/snowplow-context.jsonld
tags:
- Analytics Platform
- Behavioral Data
- Data Collection
- Data Engineering
- Data Pipeline
- Event Tracking
- Open Source
- JSON-LD
- Linked Data
- Semantic Web
---
