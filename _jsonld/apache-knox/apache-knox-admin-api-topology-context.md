---
class_count: 3
classes:
- Topology
- TopologyList
- name
context_file: json-ld/apache-knox-admin-api-topology-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apache-knox/refs/heads/main/json-ld/apache-knox-admin-api-topology-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apache Knox Admin Api Topology from Apache Knox.
layout: jsonld
name: Apache Knox Admin Api Topology Context
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
- container: ''
  name: uri
  type: string
- container: ''
  name: timestamp
  type: integer
- container: ''
  name: topologies
  type: reference
- container: set
  name: topology
  type: string
property_count: 4
provider_name: Apache Knox
provider_slug: apache-knox
slug: apache-knox-admin-api-topology-context
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
