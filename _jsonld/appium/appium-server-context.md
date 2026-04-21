---
class_count: 7
classes:
- FindElementRequest
- ErrorResponse
- ActionSequence
- SessionInfo
- AppIdRequest
- Cookie
- name
context_file: json-ld/appium-server-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/appium/refs/heads/main/json-ld/appium-server-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Appium Server from Appium.
layout: jsonld
name: Appium Server Context
namespaces:
- prefix: appium
  uri: https://appium.io/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: using
  type: string
- container: ''
  name: value
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: parameters
  type: reference
- container: set
  name: actions
  type: string
- container: ''
  name: capabilities
  type: reference
- container: ''
  name: appId
  type: string
- container: ''
  name: bundleId
  type: string
- container: ''
  name: options
  type: reference
- container: ''
  name: domain
  type: string
- container: ''
  name: path
  type: string
- container: ''
  name: httpOnly
  type: boolean
- container: ''
  name: secure
  type: boolean
- container: ''
  name: expiry
  type: integer
property_count: 15
provider_name: Appium
provider_slug: appium
slug: appium-server-context
tags:
- Android
- Cross-Platform
- iOS
- Mobile Testing
- Open Source
- OpenJS Foundation
- Test Automation
- WebDriver
- JSON-LD
- Linked Data
- Semantic Web
---
