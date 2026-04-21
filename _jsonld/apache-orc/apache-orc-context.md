---
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
