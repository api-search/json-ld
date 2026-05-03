---
class_count: 0
classes: []
context_file: json-ld/xslt-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/xslt/refs/heads/main/json-ld/xslt-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Xslt from XSLT.
layout: jsonld
name: Xslt Context
namespaces:
- prefix: xsl
  uri: http://www.w3.org/1999/XSL/Transform
- prefix: xs
  uri: http://www.w3.org/2001/XMLSchema
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: owl
  uri: http://www.w3.org/2002/07/owl#
- prefix: rdf
  uri: http://www.w3.org/1999/02/22-rdf-syntax-ns#
- prefix: rdfs
  uri: http://www.w3.org/2000/01/rdf-schema#
- prefix: xslt
  uri: https://github.com/api-evangelist/xslt/blob/main/json-ld/xslt-context.jsonld#
properties:
- container: ''
  name: Stylesheet
  type: reference
- container: ''
  name: Transformation
  type: reference
- container: ''
  name: Template
  type: reference
- container: ''
  name: Parameter
  type: reference
- container: ''
  name: version
  type: ''
- container: ''
  name: name
  type: ''
- container: ''
  name: description
  type: ''
- container: ''
  name: inputFormat
  type: ''
- container: ''
  name: outputFormat
  type: ''
- container: ''
  name: outputMethod
  type: ''
- container: ''
  name: encoding
  type: ''
- container: ''
  name: match
  type: ''
- container: ''
  name: select
  type: ''
- container: ''
  name: mode
  type: ''
- container: ''
  name: priority
  type: ''
- container: ''
  name: streaming
  type: boolean
- container: set
  name: parameters
  type: ''
- container: set
  name: templates
  type: ''
- container: set
  name: imports
  type: ''
- container: ''
  name: status
  type: ''
- container: ''
  name: source
  type: ''
- container: ''
  name: created
  type: date
- container: ''
  name: modified
  type: date
- container: ''
  name: uri
  type: reference
- container: ''
  name: href
  type: reference
- container: ''
  name: prefix
  type: ''
- container: ''
  name: error
  type: ''
- container: ''
  name: code
  type: ''
- container: ''
  name: message
  type: ''
property_count: 29
provider_name: XSLT
provider_slug: xslt
slug: xslt-context
source_filename: xslt-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsl\": \"http://www.w3.org/1999/XSL/Transform\",\n    \"xs\": \"http://www.w3.org/2001/XMLSchema\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"owl\": \"http://www.w3.org/2002/07/owl#\",\n    \"rdf\": \"http://www.w3.org/1999/02/22-rdf-syntax-ns#\",\n    \"rdfs\": \"http://www.w3.org/2000/01/rdf-schema#\",\n    \"xslt\": \"https://github.com/api-evangelist/xslt/blob/main/json-ld/xslt-context.jsonld#\",\n\n    \"Stylesheet\": {\n      \"@id\": \"xslt:Stylesheet\",\n      \"@type\": \"@id\"\n    },\n    \"Transformation\": {\n      \"@id\": \"xslt:Transformation\",\n      \"@type\": \"@id\"\n    },\n    \"Template\": {\n      \"@id\": \"xslt:Template\",\n      \"@type\": \"@id\"\n    },\n    \"Parameter\": {\n      \"@id\": \"xslt:Parameter\",\n      \"@type\": \"@id\"\n    },\n    \"version\": {\n      \"@id\": \"dcterms:hasVersion\"\n    },\n    \"name\": {\n      \"@id\"\
  : \"schema:name\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\"\n    },\n    \"inputFormat\": {\n      \"@id\": \"xslt:inputFormat\"\n    },\n    \"outputFormat\": {\n      \"@id\": \"xslt:outputFormat\"\n    },\n    \"outputMethod\": {\n      \"@id\": \"xslt:outputMethod\"\n    },\n    \"encoding\": {\n      \"@id\": \"xslt:encoding\"\n    },\n    \"match\": {\n      \"@id\": \"xslt:match\"\n    },\n    \"select\": {\n      \"@id\": \"xslt:select\"\n    },\n    \"mode\": {\n      \"@id\": \"xslt:mode\"\n    },\n    \"priority\": {\n      \"@id\": \"xslt:priority\"\n    },\n    \"streaming\": {\n      \"@id\": \"xslt:streaming\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"parameters\": {\n      \"@id\": \"xslt:parameters\",\n      \"@container\": \"@set\"\n    },\n    \"templates\": {\n      \"@id\": \"xslt:templates\",\n      \"@container\": \"@set\"\n    },\n    \"imports\": {\n      \"@id\": \"xslt:imports\",\n      \"@container\": \"@set\"\n    },\n \
  \   \"status\": {\n      \"@id\": \"xslt:status\"\n    },\n    \"source\": {\n      \"@id\": \"xslt:source\"\n    },\n    \"created\": {\n      \"@id\": \"dcterms:created\",\n      \"@type\": \"xsd:date\"\n    },\n    \"modified\": {\n      \"@id\": \"dcterms:modified\",\n      \"@type\": \"xsd:date\"\n    },\n    \"uri\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    },\n    \"href\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    },\n    \"prefix\": {\n      \"@id\": \"xslt:namespacePrefix\"\n    },\n    \"error\": {\n      \"@id\": \"schema:error\"\n    },\n    \"code\": {\n      \"@id\": \"schema:identifier\"\n    },\n    \"message\": {\n      \"@id\": \"schema:description\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/xslt/refs/heads/main/json-ld/xslt-context.jsonld
tags:
- Data Transformation
- Standard
- W3C
- XML
- XSLT
- XPath
- JSON-LD
- Linked Data
- Semantic Web
---
