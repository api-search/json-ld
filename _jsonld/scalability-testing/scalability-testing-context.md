---
api_specs:
- filename: loadtestservice.json
  format: json
  label: Azure Load Testing API
  slug: azure-load-testing
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/loadtestservice/resource-manager/Microsoft.LoadTestService/stable/2022-12-01/loadtestservice.json
class_count: 5
classes:
- name
- description
- url
- startTime
- endTime
context_file: json-ld/scalability-testing-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/scalability-testing/refs/heads/main/json-ld/scalability-testing-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Scalability Testing from Scalability Testing.
layout: jsonld
name: Scalability Testing Context
namespaces:
- prefix: perf
  uri: https://schema.performance-testing.org/ontology#
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: LoadTest
  type: reference
- container: ''
  name: StressTest
  type: reference
- container: ''
  name: SpikeTest
  type: reference
- container: ''
  name: SoakTest
  type: reference
- container: ''
  name: VirtualUser
  type: reference
- container: ''
  name: TestScenario
  type: reference
- container: ''
  name: TestResult
  type: reference
- container: ''
  name: Metric
  type: reference
- container: ''
  name: Percentile
  type: reference
- container: ''
  name: Bottleneck
  type: reference
- container: ''
  name: virtualUsers
  type: integer
- container: ''
  name: duration
  type: duration
- container: ''
  name: rampUpTime
  type: duration
- container: ''
  name: requestsPerSecond
  type: decimal
- container: ''
  name: responseTimeMs
  type: decimal
- container: ''
  name: p50
  type: decimal
- container: ''
  name: p90
  type: decimal
- container: ''
  name: p95
  type: decimal
- container: ''
  name: p99
  type: decimal
- container: ''
  name: errorRate
  type: decimal
- container: ''
  name: throughput
  type: decimal
- container: ''
  name: apdex
  type: decimal
property_count: 22
provider_name: Scalability Testing
provider_slug: scalability-testing
slug: scalability-testing-context
source_filename: scalability-testing-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"perf\": \"https://schema.performance-testing.org/ontology#\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"LoadTest\": {\n      \"@id\": \"perf:LoadTest\",\n      \"@type\": \"@id\",\n      \"comment\": \"A test that simulates user load on a system to evaluate performance\"\n    },\n    \"StressTest\": {\n      \"@id\": \"perf:StressTest\",\n      \"@type\": \"@id\",\n      \"comment\": \"A test that pushes a system beyond normal operating capacity to find breaking points\"\n    },\n    \"SpikeTest\": {\n      \"@id\": \"perf:SpikeTest\",\n      \"@type\": \"@id\",\n      \"comment\": \"A test simulating sudden sharp increases in user load\"\n    },\n    \"SoakTest\": {\n      \"@id\": \"perf:SoakTest\",\n      \"@type\": \"@id\",\n      \"comment\": \"A long-duration test to identify memory leaks and degradation over time\"\n    },\n    \"VirtualUser\": {\n      \"\
  @id\": \"perf:VirtualUser\",\n      \"@type\": \"@id\",\n      \"comment\": \"A simulated user thread executing a test scenario\"\n    },\n    \"TestScenario\": {\n      \"@id\": \"perf:TestScenario\",\n      \"@type\": \"@id\",\n      \"comment\": \"A defined sequence of actions simulated by virtual users\"\n    },\n    \"TestResult\": {\n      \"@id\": \"perf:TestResult\",\n      \"@type\": \"@id\",\n      \"comment\": \"Aggregated performance metrics from a completed load test\"\n    },\n    \"Metric\": {\n      \"@id\": \"perf:Metric\",\n      \"@type\": \"@id\",\n      \"comment\": \"A measured performance indicator from a load test\"\n    },\n    \"Percentile\": {\n      \"@id\": \"perf:Percentile\",\n      \"@type\": \"@id\",\n      \"comment\": \"A statistical measure showing the value below which a given percentage of observations fall\"\n    },\n    \"Bottleneck\": {\n      \"@id\": \"perf:Bottleneck\",\n      \"@type\": \"@id\",\n      \"comment\": \"A system constraint that\
  \ limits overall throughput or scalability\"\n    },\n\n    \"virtualUsers\": {\n      \"@id\": \"perf:virtualUsers\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"duration\": {\n      \"@id\": \"perf:duration\",\n      \"@type\": \"xsd:duration\"\n    },\n    \"rampUpTime\": {\n      \"@id\": \"perf:rampUpTime\",\n      \"@type\": \"xsd:duration\"\n    },\n    \"requestsPerSecond\": {\n      \"@id\": \"perf:requestsPerSecond\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"responseTimeMs\": {\n      \"@id\": \"perf:responseTimeMs\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"p50\": {\n      \"@id\": \"perf:p50\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"p90\": {\n      \"@id\": \"perf:p90\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"p95\": {\n      \"@id\": \"perf:p95\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"p99\": {\n      \"@id\": \"perf:p99\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"errorRate\": {\n      \"@id\": \"perf:errorRate\",\n\
  \      \"@type\": \"xsd:decimal\"\n    },\n    \"throughput\": {\n      \"@id\": \"perf:throughput\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"apdex\": {\n      \"@id\": \"perf:apdex\",\n      \"@type\": \"xsd:decimal\"\n    },\n\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"startTime\": \"schema:startTime\",\n    \"endTime\": \"schema:endTime\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/scalability-testing/refs/heads/main/json-ld/scalability-testing-context.jsonld
tags:
- API Testing
- Load Testing
- Performance Testing
- Scalability
- Stress Testing
- JSON-LD
- Linked Data
- Semantic Web
---
