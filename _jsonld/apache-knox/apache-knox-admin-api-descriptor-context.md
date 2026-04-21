---
class_count: 3
classes:
- DescriptorList
- Descriptor
- name
context_file: json-ld/apache-knox-admin-api-descriptor-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apache-knox/refs/heads/main/json-ld/apache-knox-admin-api-descriptor-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apache Knox Admin Api Descriptor from Apache Knox.
layout: jsonld
name: Apache Knox Admin Api Descriptor Context
namespaces:
- prefix: knox
  uri: https://apache-knox.apache.org/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: set
  name: descriptors
  type: string
- container: ''
  name: discoveryType
  type: string
- container: ''
  name: discoveryAddress
  type: string
- container: ''
  name: cluster
  type: string
- container: ''
  name: providerConfig
  type: string
- container: set
  name: services
  type: reference
property_count: 6
provider_name: Apache Knox
provider_slug: apache-knox
slug: apache-knox-admin-api-descriptor-context
tags:
- API Gateway
- Authentication
- Hadoop
- Open Source
- Security
- SSO
- JSON-LD
- Linked Data
- Semantic Web
---
