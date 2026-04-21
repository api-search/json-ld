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
