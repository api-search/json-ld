---
api_specs:
- filename: apache-orc-tools-api.yaml
  format: yaml
  label: Apache ORC
  slug: apache-orc
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/apache-orc/refs/heads/main/openapi/apache-orc-tools-api.yaml
class_count: 12
classes:
- FileList
- FileInfo
- OrcSchema
- ColumnType
- FileMetadata
- StripeInfo
- ColumnStatisticsResponse
- ColumnStatistics
- ConversionRequest
- ConversionResult
- MergeRequest
- OperationResult
context_file: json-ld/apache-orc-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apache-orc/refs/heads/main/json-ld/apache-orc-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apache Orc from Apache ORC.
layout: jsonld
name: Apache Orc Context
namespaces:
- prefix: apa
  uri: https://apache-orc.apache.org/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: set
  name: files
  type: ''
- container: ''
  name: path
  type: string
- container: ''
  name: size
  type: integer
- container: ''
  name: rowCount
  type: integer
- container: ''
  name: stripes
  type: integer
- container: ''
  name: typeName
  type: string
- container: set
  name: columns
  type: ''
- container: ''
  name: name
  type: schema:name
- container: ''
  name: type
  type: string
- container: ''
  name: nullable
  type: boolean
- container: set
  name: children
  type: ''
- container: ''
  name: filePath
  type: string
- container: ''
  name: fileVersion
  type: string
- container: ''
  name: writerVersion
  type: string
- container: ''
  name: compression
  type: string
- container: ''
  name: compressionBlockSize
  type: integer
- container: ''
  name: rawDataSize
  type: integer
- container: ''
  name: numberOfStripes
  type: integer
- container: ''
  name: stripeIndex
  type: integer
- container: ''
  name: offset
  type: integer
- container: ''
  name: length
  type: integer
- container: set
  name: statistics
  type: ''
- container: ''
  name: columnIndex
  type: integer
- container: ''
  name: columnName
  type: string
- container: ''
  name: valueCount
  type: integer
- container: ''
  name: nullCount
  type: integer
- container: ''
  name: hasMinimum
  type: boolean
- container: ''
  name: minimum
  type: string
- container: ''
  name: maximum
  type: string
- container: ''
  name: sourcePath
  type: string
- container: ''
  name: outputPath
  type: string
- container: ''
  name: sourceFormat
  type: string
- container: ''
  name: rowBatchSize
  type: integer
- container: ''
  name: status
  type: string
- container: ''
  name: rowsWritten
  type: integer
- container: ''
  name: duration
  type: integer
- container: set
  name: inputPaths
  type: ''
property_count: 37
provider_name: Apache ORC
provider_slug: apache-orc
slug: apache-orc-context
source_filename: apache-orc-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"apa\": \"https://apache-orc.apache.org/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"FileList\": \"xsd:FileList\",\n    \"FileInfo\": \"xsd:FileInfo\",\n    \"OrcSchema\": \"xsd:OrcSchema\",\n    \"ColumnType\": \"xsd:ColumnType\",\n    \"FileMetadata\": \"xsd:FileMetadata\",\n    \"StripeInfo\": \"xsd:StripeInfo\",\n    \"ColumnStatisticsResponse\": \"xsd:ColumnStatisticsResponse\",\n    \"ColumnStatistics\": \"xsd:ColumnStatistics\",\n    \"ConversionRequest\": \"xsd:ConversionRequest\",\n    \"ConversionResult\": \"xsd:ConversionResult\",\n    \"MergeRequest\": \"xsd:MergeRequest\",\n    \"OperationResult\": \"xsd:OperationResult\",\n    \"files\": {\n      \"@id\": \"xsd:files\",\n      \"@container\": \"@set\"\n    },\n    \"path\": {\n      \"@id\": \"xsd:path\",\n      \"@type\": \"xsd:string\"\n    },\n    \"size\": {\n      \"@id\": \"xsd:size\",\n\
  \      \"@type\": \"xsd:integer\"\n    },\n    \"rowCount\": {\n      \"@id\": \"xsd:rowCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"stripes\": {\n      \"@id\": \"xsd:stripes\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"typeName\": {\n      \"@id\": \"xsd:typeName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"columns\": {\n      \"@id\": \"xsd:columns\",\n      \"@container\": \"@set\"\n    },\n    \"name\": {\n      \"@id\": \"xsd:name\",\n      \"@type\": \"schema:name\"\n    },\n    \"type\": {\n      \"@id\": \"xsd:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nullable\": {\n      \"@id\": \"xsd:nullable\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"children\": {\n      \"@id\": \"xsd:children\",\n      \"@container\": \"@set\"\n    },\n    \"filePath\": {\n      \"@id\": \"xsd:filePath\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fileVersion\": {\n      \"@id\": \"xsd:fileVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"writerVersion\"\
  : {\n      \"@id\": \"xsd:writerVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"compression\": {\n      \"@id\": \"xsd:compression\",\n      \"@type\": \"xsd:string\"\n    },\n    \"compressionBlockSize\": {\n      \"@id\": \"xsd:compressionBlockSize\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"rawDataSize\": {\n      \"@id\": \"xsd:rawDataSize\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"numberOfStripes\": {\n      \"@id\": \"xsd:numberOfStripes\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"stripeIndex\": {\n      \"@id\": \"xsd:stripeIndex\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"offset\": {\n      \"@id\": \"xsd:offset\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"length\": {\n      \"@id\": \"xsd:length\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"statistics\": {\n      \"@id\": \"xsd:statistics\",\n      \"@container\": \"@set\"\n    },\n    \"columnIndex\": {\n      \"@id\": \"xsd:columnIndex\",\n      \"@type\": \"xsd:integer\"\
  \n    },\n    \"columnName\": {\n      \"@id\": \"xsd:columnName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"valueCount\": {\n      \"@id\": \"xsd:valueCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"nullCount\": {\n      \"@id\": \"xsd:nullCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"hasMinimum\": {\n      \"@id\": \"xsd:hasMinimum\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"minimum\": {\n      \"@id\": \"xsd:minimum\",\n      \"@type\": \"xsd:string\"\n    },\n    \"maximum\": {\n      \"@id\": \"xsd:maximum\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sourcePath\": {\n      \"@id\": \"xsd:sourcePath\",\n      \"@type\": \"xsd:string\"\n    },\n    \"outputPath\": {\n      \"@id\": \"xsd:outputPath\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sourceFormat\": {\n      \"@id\": \"xsd:sourceFormat\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rowBatchSize\": {\n      \"@id\": \"xsd:rowBatchSize\",\n      \"@type\": \"xsd:integer\"\n\
  \    },\n    \"status\": {\n      \"@id\": \"xsd:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rowsWritten\": {\n      \"@id\": \"xsd:rowsWritten\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"duration\": {\n      \"@id\": \"xsd:duration\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"inputPaths\": {\n      \"@id\": \"xsd:inputPaths\",\n      \"@container\": \"@set\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/apache-orc/refs/heads/main/json-ld/apache-orc-context.jsonld
tags:
- Big Data
- Columnar Storage
- Compression
- File Format
- Hadoop
- Apache
- Open Source
- JSON-LD
- Linked Data
- Semantic Web
---
