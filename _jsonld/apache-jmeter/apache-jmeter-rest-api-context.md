---
api_specs:
- filename: apache-jmeter-rest-api.yaml
  format: yaml
  label: Apache JMeter REST API
  slug: rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/apache-jmeter/refs/heads/main/openapi/apache-jmeter-rest-api.yaml
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
source_filename: apache-jmeter-rest-api-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"jmeter\": \"https://apache-jmeter.apache.org/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"TestResults\": \"jmeter:TestResults\",\n    \"TestStatus\": \"jmeter:TestStatus\",\n    \"TestRunRequest\": \"jmeter:TestRunRequest\",\n    \"TestRunResponse\": \"jmeter:TestRunResponse\",\n    \"testId\": {\n      \"@id\": \"jmeter:testId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"totalRequests\": {\n      \"@id\": \"jmeter:totalRequests\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"errorCount\": {\n      \"@id\": \"jmeter:errorCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"averageResponseTime\": {\n      \"@id\": \"jmeter:averageResponseTime\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"minResponseTime\": {\n      \"@id\": \"jmeter:minResponseTime\",\n      \"@type\": \"xsd:decimal\"\n \
  \   },\n    \"maxResponseTime\": {\n      \"@id\": \"jmeter:maxResponseTime\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"percentile90\": {\n      \"@id\": \"jmeter:percentile90\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"throughput\": {\n      \"@id\": \"jmeter:throughput\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"status\": {\n      \"@id\": \"jmeter:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"activeThreads\": {\n      \"@id\": \"jmeter:activeThreads\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"elapsedTime\": {\n      \"@id\": \"jmeter:elapsedTime\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"errorRate\": {\n      \"@id\": \"jmeter:errorRate\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"testPlan\": {\n      \"@id\": \"jmeter:testPlan\",\n      \"@type\": \"xsd:string\"\n    },\n    \"properties\": {\n      \"@id\": \"jmeter:properties\",\n      \"@type\": \"@id\"\n    },\n    \"startTime\": {\n      \"@id\": \"jmeter:startTime\"\
  ,\n      \"@type\": \"xsd:integer\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/apache-jmeter/refs/heads/main/json-ld/apache-jmeter-rest-api-context.jsonld
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
