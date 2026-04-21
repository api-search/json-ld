---
class_count: 6
classes:
- VirtualMachine
- Network
- Volume
- Zone
- AsyncJobResponse
- AsyncJobResult
context_file: json-ld/apache-cloudstack-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apache-cloudstack/refs/heads/main/json-ld/apache-cloudstack-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apache Cloudstack from Apache CloudStack.
layout: jsonld
name: Apache Cloudstack Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: cloudstack
  uri: https://cloudstack.apache.org/vocab#
properties:
- container: ''
  name: id
  type: string
- container: ''
  name: name
  type: string
- container: ''
  name: state
  type: string
- container: ''
  name: zoneid
  type: string
- container: ''
  name: zonename
  type: string
- container: ''
  name: serviceofferingid
  type: string
- container: ''
  name: templateid
  type: string
- container: ''
  name: cpunumber
  type: integer
- container: ''
  name: memory
  type: integer
- container: ''
  name: ipaddress
  type: string
- container: ''
  name: cidr
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: size
  type: long
- container: ''
  name: virtualmachineid
  type: string
- container: ''
  name: networktype
  type: string
- container: ''
  name: allocationstate
  type: string
- container: ''
  name: securitygroupsenabled
  type: boolean
- container: ''
  name: jobid
  type: string
- container: ''
  name: jobstatus
  type: integer
- container: ''
  name: jobresultcode
  type: integer
- container: ''
  name: jobresult
  type: ''
property_count: 21
provider_name: Apache CloudStack
provider_slug: apache-cloudstack
slug: apache-cloudstack-context
tags:
- Apache
- Cloud
- IaaS
- Infrastructure
- Open Source
- Virtualization
- JSON-LD
- Linked Data
- Semantic Web
---
