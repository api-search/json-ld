---
class_count: 9
classes:
- RefreshRequest
- ServiceEntry
- ServiceLink
- ServiceListResponse
- ServiceResponse
- TokenData
- TokenResponse
- description
- name
context_file: json-ld/apache-ofbiz-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apache-ofbiz/refs/heads/main/json-ld/apache-ofbiz-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apache Ofbiz from Apache OFBiz.
layout: jsonld
name: Apache Ofbiz Context
namespaces:
- prefix: ofbiz
  uri: https://ofbiz.apache.org/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: accessToken
  type: string
- container: set
  name: data
  type: string
- container: ''
  name: expiresIn
  type: string
- container: ''
  name: href
  type: reference
- container: ''
  name: link
  type: reference
- container: ''
  name: refreshToken
  type: string
- container: ''
  name: rel
  type: string
- container: ''
  name: statusCode
  type: integer
- container: ''
  name: statusDescription
  type: string
- container: ''
  name: successMessage
  type: string
- container: ''
  name: tokenType
  type: string
- container: ''
  name: type
  type: string
property_count: 12
provider_name: Apache OFBiz
provider_slug: apache-ofbiz
slug: apache-ofbiz-context
tags:
- ERP
- CRM
- E-Commerce
- Business Applications
- Apache
- Java
- Open Source
- Supply Chain
- JSON-LD
- Linked Data
- Semantic Web
---
