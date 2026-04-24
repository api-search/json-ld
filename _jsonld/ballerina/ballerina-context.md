---
class_count: 10
classes:
- Connector
- ConnectorSearchResponse
- ConnectorSummary
- Module
- Organization
- Package
- PackageDocs
- PackageSearchResponse
- PackageSummary
- PackageVersion
context_file: json-ld/ballerina-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/ballerina/refs/heads/main/json-ld/ballerina-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Ballerina from Ballerina.
layout: jsonld
name: Ballerina Context
namespaces:
- prefix: ballerina
  uri: https://central.ballerina.io/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: set
  name: authors
  type: string
- container: ''
  name: ballerinaVersion
  type: string
- container: ''
  name: category
  type: string
- container: set
  name: connectors
  type: string
- container: ''
  name: count
  type: integer
- container: ''
  name: createdDate
  type: dateTime
- container: set
  name: dependencies
  type: string
- container: ''
  name: description
  type: ''
- container: set
  name: functions
  type: string
- container: set
  name: keywords
  type: string
- container: ''
  name: license
  type: string
- container: ''
  name: limit
  type: integer
- container: ''
  name: moduleName
  type: string
- container: set
  name: modules
  type: string
- container: ''
  name: name
  type: ''
- container: ''
  name: offset
  type: integer
- container: ''
  name: organization
  type: string
- container: ''
  name: packageCount
  type: integer
- container: ''
  name: packageName
  type: string
- container: set
  name: packages
  type: string
- container: ''
  name: platform
  type: string
- container: ''
  name: pullCount
  type: integer
- container: ''
  name: readme
  type: string
- container: ''
  name: repositoryURL
  type: reference
- container: ''
  name: version
  type: ''
- container: set
  name: versions
  type: string
- container: ''
  name: website
  type: reference
property_count: 27
provider_name: Ballerina
provider_slug: ballerina
slug: ballerina-context
tags:
- Integrations
- Orchestrations
- Open Source
- Programming Language
- JSON-LD
- Linked Data
- Semantic Web
---
