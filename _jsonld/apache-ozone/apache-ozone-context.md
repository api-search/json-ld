---
class_count: 5
classes:
- ListAllMyBucketsResult
- Owner
- Bucket
- ListObjectsResult
- Object
context_file: json-ld/apache-ozone-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apache-ozone/refs/heads/main/json-ld/apache-ozone-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apache Ozone from Apache Ozone.
layout: jsonld
name: Apache Ozone Context
namespaces:
- prefix: ozon
  uri: https://ozone.apache.org/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: owner
  type: string
- container: set
  name: buckets
  type: ''
- container: ''
  name: id
  type: string
- container: ''
  name: displayName
  type: string
- container: ''
  name: name
  type: schema:name
- container: ''
  name: creationDate
  type: string
- container: ''
  name: storageClass
  type: string
- container: ''
  name: prefix
  type: string
- container: ''
  name: maxKeys
  type: integer
- container: ''
  name: isTruncated
  type: boolean
- container: ''
  name: nextContinuationToken
  type: string
- container: set
  name: contents
  type: ''
- container: ''
  name: key
  type: string
- container: ''
  name: lastModified
  type: string
- container: ''
  name: etag
  type: string
- container: ''
  name: size
  type: integer
property_count: 16
provider_name: Apache Ozone
provider_slug: apache-ozone
slug: apache-ozone-context
tags:
- Distributed Storage
- Hadoop
- Object Storage
- S3-Compatible
- Apache
- Open Source
- JSON-LD
- Linked Data
- Semantic Web
---
