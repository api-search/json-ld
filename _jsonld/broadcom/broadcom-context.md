---
class_count: 3
classes:
- name
- description
- status
context_file: json-ld/broadcom-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/broadcom/refs/heads/main/json-ld/broadcom-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Broadcom from Broadcom.
layout: jsonld
name: Broadcom Context
namespaces:
- prefix: broadcom
  uri: https://developer.broadcom.com/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
properties:
- container: ''
  name: vm
  type: string
- container: ''
  name: power_state
  type: string
- container: ''
  name: cpu_count
  type: integer
- container: ''
  name: memory_size_MiB
  type: integer
- container: ''
  name: guest_OS
  type: string
- container: ''
  name: fqdn
  type: string
- container: ''
  name: connection_state
  type: string
- container: ''
  name: ha_enabled
  type: boolean
- container: ''
  name: drs_enabled
  type: boolean
- container: ''
  name: vsan_enabled
  type: boolean
- container: ''
  name: severity
  type: string
- container: ''
  name: condition
  type: string
- container: ''
  name: creatorId
  type: string
- container: ''
  name: workloadDomainType
  type: string
- container: ''
  name: isCancellable
  type: boolean
- container: ''
  name: isRetryable
  type: boolean
- container: ''
  name: creationTimestamp
  type: dateTime
- container: ''
  name: completionTimestamp
  type: dateTime
property_count: 18
provider_name: Broadcom
provider_slug: broadcom
slug: broadcom-context
tags:
- Cloud Infrastructure
- Gateways
- Management
- Networks
- Observability
- Virtualization
- JSON-LD
- Linked Data
- Semantic Web
---
