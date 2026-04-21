---
class_count: 4
classes:
- TestResults
- TestStatus
- TestRunRequest
- TestRunResponse
context_file: json-ld/apache-jmeter-rest-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apache-jmeter/refs/heads/main/json-ld/apache-jmeter-rest-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apache Jmeter Rest Api from Apache JMeter.
layout: jsonld
name: Apache Jmeter Rest Api Context
namespaces:
- prefix: jmeter
  uri: https://apache-jmeter.apache.org/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: testId
  type: string
- container: ''
  name: totalRequests
  type: integer
- container: ''
  name: errorCount
  type: integer
- container: ''
  name: averageResponseTime
  type: decimal
- container: ''
  name: minResponseTime
  type: decimal
- container: ''
  name: maxResponseTime
  type: decimal
- container: ''
  name: percentile90
  type: decimal
- container: ''
  name: throughput
  type: decimal
- container: ''
  name: status
  type: string
- container: ''
  name: activeThreads
  type: integer
- container: ''
  name: elapsedTime
  type: integer
- container: ''
  name: errorRate
  type: decimal
- container: ''
  name: testPlan
  type: string
- container: ''
  name: properties
  type: reference
- container: ''
  name: startTime
  type: integer
property_count: 15
provider_name: Apache JMeter
provider_slug: apache-jmeter
slug: apache-jmeter-rest-api-context
tags:
- API Testing
- Java
- Load Testing
- Open Source
- Performance Testing
- Stress Testing
- JSON-LD
- Linked Data
- Semantic Web
---
