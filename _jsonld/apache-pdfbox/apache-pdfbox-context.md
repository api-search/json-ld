---
class_count: 11
classes:
- CreateDocumentRequest
- DocumentInfo
- TextExtractionResult
- PageList
- PageInfo
- DocumentMetadata
- MergeRequest
- SplitRequest
- SignRequest
- FormFields
- FormField
context_file: json-ld/apache-pdfbox-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apache-pdfbox/refs/heads/main/json-ld/apache-pdfbox-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apache Pdfbox from Apache PDFBox.
layout: jsonld
name: Apache Pdfbox Context
namespaces:
- prefix: pdfb
  uri: https://pdfbox.apache.org/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: title
  type: string
- container: ''
  name: author
  type: string
- container: ''
  name: pageSize
  type: string
- container: ''
  name: documentId
  type: string
- container: ''
  name: pageCount
  type: integer
- container: ''
  name: fileSize
  type: integer
- container: ''
  name: version
  type: string
- container: ''
  name: text
  type: string
- container: ''
  name: wordCount
  type: integer
- container: ''
  name: totalPages
  type: integer
- container: set
  name: pages
  type: ''
- container: ''
  name: pageNumber
  type: integer
- container: ''
  name: width
  type: decimal
- container: ''
  name: height
  type: decimal
- container: ''
  name: rotation
  type: integer
- container: ''
  name: subject
  type: string
- container: ''
  name: creator
  type: string
- container: ''
  name: producer
  type: string
- container: ''
  name: creationDate
  type: string
- container: ''
  name: modificationDate
  type: string
- container: set
  name: sourceDocumentIds
  type: ''
- container: ''
  name: outputTitle
  type: string
- container: set
  name: splitAtPages
  type: ''
- container: ''
  name: keystorePath
  type: string
- container: ''
  name: password
  type: string
- container: ''
  name: reason
  type: string
- container: ''
  name: location
  type: string
- container: set
  name: fields
  type: ''
- container: ''
  name: name
  type: schema:name
- container: ''
  name: type
  type: string
- container: ''
  name: value
  type: string
- container: ''
  name: required
  type: boolean
property_count: 32
provider_name: Apache PDFBox
provider_slug: apache-pdfbox
slug: apache-pdfbox-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"pdfb\": \"https://pdfbox.apache.org/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"CreateDocumentRequest\": \"pdfb:CreateDocumentRequest\",\n    \"DocumentInfo\": \"pdfb:DocumentInfo\",\n    \"TextExtractionResult\": \"pdfb:TextExtractionResult\",\n    \"PageList\": \"pdfb:PageList\",\n    \"PageInfo\": \"pdfb:PageInfo\",\n    \"DocumentMetadata\": \"pdfb:DocumentMetadata\",\n    \"MergeRequest\": \"pdfb:MergeRequest\",\n    \"SplitRequest\": \"pdfb:SplitRequest\",\n    \"SignRequest\": \"pdfb:SignRequest\",\n    \"FormFields\": \"pdfb:FormFields\",\n    \"FormField\": \"pdfb:FormField\",\n    \"title\": {\n      \"@id\": \"pdfb:title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"author\": {\n      \"@id\": \"pdfb:author\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pageSize\": {\n      \"@id\": \"pdfb:pageSize\",\n      \"@type\": \"xsd:string\"\n\
  \    },\n    \"documentId\": {\n      \"@id\": \"pdfb:documentId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pageCount\": {\n      \"@id\": \"pdfb:pageCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"fileSize\": {\n      \"@id\": \"pdfb:fileSize\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"version\": {\n      \"@id\": \"pdfb:version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"text\": {\n      \"@id\": \"pdfb:text\",\n      \"@type\": \"xsd:string\"\n    },\n    \"wordCount\": {\n      \"@id\": \"pdfb:wordCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"totalPages\": {\n      \"@id\": \"pdfb:totalPages\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"pages\": {\n      \"@id\": \"pdfb:pages\",\n      \"@container\": \"@set\"\n    },\n    \"pageNumber\": {\n      \"@id\": \"pdfb:pageNumber\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"width\": {\n      \"@id\": \"pdfb:width\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"height\": {\n  \
  \    \"@id\": \"pdfb:height\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"rotation\": {\n      \"@id\": \"pdfb:rotation\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"subject\": {\n      \"@id\": \"pdfb:subject\",\n      \"@type\": \"xsd:string\"\n    },\n    \"creator\": {\n      \"@id\": \"pdfb:creator\",\n      \"@type\": \"xsd:string\"\n    },\n    \"producer\": {\n      \"@id\": \"pdfb:producer\",\n      \"@type\": \"xsd:string\"\n    },\n    \"creationDate\": {\n      \"@id\": \"pdfb:creationDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"modificationDate\": {\n      \"@id\": \"pdfb:modificationDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sourceDocumentIds\": {\n      \"@id\": \"pdfb:sourceDocumentIds\",\n      \"@container\": \"@set\"\n    },\n    \"outputTitle\": {\n      \"@id\": \"pdfb:outputTitle\",\n      \"@type\": \"xsd:string\"\n    },\n    \"splitAtPages\": {\n      \"@id\": \"pdfb:splitAtPages\",\n      \"@container\": \"@set\"\n    },\n \
  \   \"keystorePath\": {\n      \"@id\": \"pdfb:keystorePath\",\n      \"@type\": \"xsd:string\"\n    },\n    \"password\": {\n      \"@id\": \"pdfb:password\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reason\": {\n      \"@id\": \"pdfb:reason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"location\": {\n      \"@id\": \"pdfb:location\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fields\": {\n      \"@id\": \"pdfb:fields\",\n      \"@container\": \"@set\"\n    },\n    \"name\": {\n      \"@id\": \"pdfb:name\",\n      \"@type\": \"schema:name\"\n    },\n    \"type\": {\n      \"@id\": \"pdfb:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"pdfb:value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"required\": {\n      \"@id\": \"pdfb:required\",\n      \"@type\": \"xsd:boolean\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/apache-pdfbox/refs/heads/main/json-ld/apache-pdfbox-context.jsonld
tags:
- Document Processing
- Java
- PDF
- Text Extraction
- Apache
- Open Source
- JSON-LD
- Linked Data
- Semantic Web
---
