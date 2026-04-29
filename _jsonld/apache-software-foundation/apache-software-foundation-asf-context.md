---
class_count: 5
classes:
- Apache Software Foundation Project
- Apache Software Foundation Committee
- Apache Software Foundation Podling
- name
- description
context_file: json-ld/apache-software-foundation-asf-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apache-software-foundation/refs/heads/main/json-ld/apache-software-foundation-asf-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apache Software Foundation Asf from Apache Software Foundation.
layout: jsonld
name: Apache Software Foundation Asf Context
namespaces:
- prefix: asf
  uri: https://www.apache.org/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: category
  type: string
- container: ''
  name: pmc
  type: string
- container: ''
  name: homepage
  type: reference
- container: ''
  name: programming-language
  type: string
- container: ''
  name: bug-database
  type: reference
- container: ''
  name: download-page
  type: reference
- container: ''
  name: mailing-list
  type: reference
- container: set
  name: repository
  type: string
- container: ''
  name: license
  type: string
- container: ''
  name: shortdesc
  type: string
- container: ''
  name: chair
  type: string
- container: ''
  name: established
  type: string
- container: set
  name: report
  type: string
- container: ''
  name: roster
  type: reference
- container: ''
  name: rosterCount
  type: integer
- container: ''
  name: status
  type: string
- container: ''
  name: startdate
  type: string
- container: ''
  name: enddate
  type: string
- container: ''
  name: sponsor
  type: string
- container: ''
  name: champion
  type: string
- container: set
  name: mentors
  type: string
- container: ''
  name: resolution
  type: string
property_count: 22
provider_name: Apache Software Foundation
provider_slug: apache-software-foundation
slug: apache-software-foundation-asf-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"asf\": \"https://www.apache.org/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Apache Software Foundation Project\": \"asf:Apache Software Foundation Project\",\n    \"Apache Software Foundation Committee\": \"asf:Apache Software Foundation Committee\",\n    \"Apache Software Foundation Podling\": \"asf:Apache Software Foundation Podling\",\n    \"name\": \"schema:name\",\n    \"category\": {\n      \"@id\": \"asf:category\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pmc\": {\n      \"@id\": \"asf:pmc\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\",\n    \"homepage\": {\n      \"@id\": \"asf:homepage\",\n      \"@type\": \"@id\"\n    },\n    \"programming-language\": {\n      \"@id\": \"asf:programming-language\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bug-database\"\
  : {\n      \"@id\": \"asf:bug-database\",\n      \"@type\": \"@id\"\n    },\n    \"download-page\": {\n      \"@id\": \"asf:download-page\",\n      \"@type\": \"@id\"\n    },\n    \"mailing-list\": {\n      \"@id\": \"asf:mailing-list\",\n      \"@type\": \"@id\"\n    },\n    \"repository\": {\n      \"@id\": \"asf:repository\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"license\": {\n      \"@id\": \"asf:license\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shortdesc\": {\n      \"@id\": \"asf:shortdesc\",\n      \"@type\": \"xsd:string\"\n    },\n    \"chair\": {\n      \"@id\": \"asf:chair\",\n      \"@type\": \"xsd:string\"\n    },\n    \"established\": {\n      \"@id\": \"asf:established\",\n      \"@type\": \"xsd:string\"\n    },\n    \"report\": {\n      \"@id\": \"asf:report\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"roster\": {\n      \"@id\": \"asf:roster\",\n      \"@type\": \"@id\"\n    },\n\
  \    \"rosterCount\": {\n      \"@id\": \"asf:roster_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"status\": {\n      \"@id\": \"asf:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startdate\": {\n      \"@id\": \"asf:startdate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"enddate\": {\n      \"@id\": \"asf:enddate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sponsor\": {\n      \"@id\": \"asf:sponsor\",\n      \"@type\": \"xsd:string\"\n    },\n    \"champion\": {\n      \"@id\": \"asf:champion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mentors\": {\n      \"@id\": \"asf:mentors\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resolution\": {\n      \"@id\": \"asf:resolution\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/apache-software-foundation/refs/heads/main/json-ld/apache-software-foundation-asf-context.jsonld
tags:
- ASF
- Open Source
- Governance
- Projects
- Apache
- JSON-LD
- Linked Data
- Semantic Web
---
