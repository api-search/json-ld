---
class_count: 23
classes:
- name
- description
- version
- created
- modified
- HTML
- XML
- TEXT
- JAVASCRIPT
- CSS
- RAW
- StandardDialect
- SpringStandardDialect
- SpringSecurityDialect
- LayoutDialect
- Java8TimeDialect
- mavenCoordinates
- programmingLanguage
- license
- codeRepository
- softwareVersion
- documentation
- downloadUrl
context_file: json-ld/thymeleaf-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/thymeleaf/refs/heads/main/json-ld/thymeleaf-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Thymeleaf from Thymeleaf.
layout: jsonld
name: Thymeleaf Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: rdfs
  uri: http://www.w3.org/2000/01/rdf-schema#
- prefix: th
  uri: https://www.thymeleaf.org/vocab#
properties:
- container: ''
  name: ThymeleafTemplate
  type: ''
- container: ''
  name: ThymeleafDialect
  type: ''
- container: ''
  name: ThymeleafFragment
  type: ''
- container: ''
  name: ThymeleafExpression
  type: ''
- container: ''
  name: TemplateMode
  type: ''
- container: ''
  name: templateMode
  type: ''
- container: ''
  name: prefix
  type: ''
- container: list
  name: processors
  type: ''
- container: list
  name: fragments
  type: ''
- container: ''
  name: fragmentName
  type: ''
- container: ''
  name: expressionType
  type: ''
- container: ''
  name: dialect
  type: reference
- container: ''
  name: templateResolver
  type: reference
- container: ''
  name: variableExpression
  type: ''
- container: ''
  name: selectionExpression
  type: ''
- container: ''
  name: messageExpression
  type: ''
- container: ''
  name: urlExpression
  type: ''
- container: ''
  name: fragmentExpression
  type: ''
property_count: 18
provider_name: Thymeleaf
provider_slug: thymeleaf
slug: thymeleaf-context
source_filename: thymeleaf-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://www.thymeleaf.org/vocab#\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"rdfs\": \"http://www.w3.org/2000/01/rdf-schema#\",\n    \"th\": \"https://www.thymeleaf.org/vocab#\",\n\n    \"ThymeleafTemplate\": {\n      \"@id\": \"th:ThymeleafTemplate\",\n      \"rdfs:comment\": \"A Thymeleaf template file\"\n    },\n    \"ThymeleafDialect\": {\n      \"@id\": \"th:ThymeleafDialect\",\n      \"rdfs:comment\": \"A Thymeleaf dialect extending the template engine with processors\"\n    },\n    \"ThymeleafFragment\": {\n      \"@id\": \"th:ThymeleafFragment\",\n      \"rdfs:comment\": \"A reusable named fragment within a Thymeleaf template\"\n    },\n    \"ThymeleafExpression\": {\n      \"@id\": \"th:ThymeleafExpression\",\n      \"rdfs:comment\": \"A Thymeleaf expression for data binding or URL generation\"\n    },\n    \"TemplateMode\": {\n      \"@id\": \"th:TemplateMode\",\n\
  \      \"rdfs:comment\": \"The processing mode for a Thymeleaf template: HTML, XML, TEXT, JAVASCRIPT, CSS, or RAW\"\n    },\n\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"version\": \"schema:version\",\n    \"created\": \"schema:dateCreated\",\n    \"modified\": \"schema:dateModified\",\n\n    \"templateMode\": {\n      \"@id\": \"th:templateMode\",\n      \"rdfs:comment\": \"The template mode (HTML, XML, TEXT, JAVASCRIPT, CSS, RAW)\"\n    },\n    \"prefix\": {\n      \"@id\": \"th:dialectPrefix\",\n      \"rdfs:comment\": \"The attribute namespace prefix for a dialect (e.g., 'th' for Standard Dialect)\"\n    },\n    \"processors\": {\n      \"@id\": \"th:hasProcessors\",\n      \"@container\": \"@list\"\n    },\n    \"fragments\": {\n      \"@id\": \"th:hasFragments\",\n      \"@container\": \"@list\"\n    },\n    \"fragmentName\": {\n      \"@id\": \"th:fragmentName\",\n      \"rdfs:comment\": \"The name of a th:fragment definition\"\n    },\n\
  \    \"expressionType\": {\n      \"@id\": \"th:expressionType\",\n      \"rdfs:comment\": \"The type of Thymeleaf expression: variable, selection, message, url, or fragment\"\n    },\n    \"dialect\": {\n      \"@id\": \"th:usesDialect\",\n      \"@type\": \"@id\"\n    },\n    \"templateResolver\": {\n      \"@id\": \"th:usesTemplateResolver\",\n      \"@type\": \"@id\"\n    },\n\n    \"HTML\": \"th:TemplateModeHTML\",\n    \"XML\": \"th:TemplateModeXML\",\n    \"TEXT\": \"th:TemplateModeTEXT\",\n    \"JAVASCRIPT\": \"th:TemplateModeJAVASCRIPT\",\n    \"CSS\": \"th:TemplateModeCSS\",\n    \"RAW\": \"th:TemplateModeRAW\",\n\n    \"StandardDialect\": \"th:DialectStandard\",\n    \"SpringStandardDialect\": \"th:DialectSpringStandard\",\n    \"SpringSecurityDialect\": \"th:DialectSpringSecurity\",\n    \"LayoutDialect\": \"th:DialectLayout\",\n    \"Java8TimeDialect\": \"th:DialectJava8Time\",\n\n    \"variableExpression\": {\n      \"@id\": \"th:variableExpression\",\n      \"rdfs:comment\"\
  : \"${...} — evaluates OGNL or Spring EL against the model\"\n    },\n    \"selectionExpression\": {\n      \"@id\": \"th:selectionExpression\",\n      \"rdfs:comment\": \"*{...} — evaluates against the selected object (th:object)\"\n    },\n    \"messageExpression\": {\n      \"@id\": \"th:messageExpression\",\n      \"rdfs:comment\": \"#{...} — resolves internationalized messages\"\n    },\n    \"urlExpression\": {\n      \"@id\": \"th:urlExpression\",\n      \"rdfs:comment\": \"@{...} — builds context-relative URLs\"\n    },\n    \"fragmentExpression\": {\n      \"@id\": \"th:fragmentExpression\",\n      \"rdfs:comment\": \"~{...} — references template fragments\"\n    },\n\n    \"mavenCoordinates\": \"schema:identifier\",\n    \"programmingLanguage\": \"schema:programmingLanguage\",\n    \"license\": \"schema:license\",\n    \"codeRepository\": \"schema:codeRepository\",\n    \"softwareVersion\": \"schema:softwareVersion\",\n    \"documentation\": \"schema:documentation\",\n    \"\
  downloadUrl\": \"schema:downloadUrl\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/thymeleaf/refs/heads/main/json-ld/thymeleaf-context.jsonld
tags:
- HTML
- Java
- Open Source
- Server Side Rendering
- Spring
- Spring Boot
- Template Engine
- Thymeleaf
- Web Development
- JSON-LD
- Linked Data
- Semantic Web
---
