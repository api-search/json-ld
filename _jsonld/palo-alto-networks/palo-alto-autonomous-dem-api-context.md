---
class_count: 6
classes:
- AgentScore
- ApplicationScore
- MonitoredAgent
- MonitoredApplication
- PerformanceMetric
- TestResult
context_file: json-ld/palo-alto-autonomous-dem-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/json-ld/palo-alto-autonomous-dem-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Palo Alto Autonomous Dem Api from Palo Alto Networks.
layout: jsonld
name: Palo Alto Autonomous Dem Api Context
namespaces:
- prefix: pan
  uri: https://pan.dev/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: agentId
  type: string
- container: ''
  name: agentVersion
  type: string
- container: ''
  name: appId
  type: string
- container: ''
  name: application
  type: string
- container: ''
  name: applicationScore
  type: integer
- container: ''
  name: category
  type: string
- container: ''
  name: cpuUsagePct
  type: decimal
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: deviceName
  type: string
- container: ''
  name: dnsTimeMs
  type: decimal
- container: ''
  name: endpointScore
  type: integer
- container: ''
  name: errorMessage
  type: string
- container: ''
  name: httpStatusCode
  type: integer
- container: ''
  name: jitterMs
  type: decimal
- container: ''
  name: lastSeen
  type: dateTime
- container: ''
  name: latencyMs
  type: decimal
- container: ''
  name: memoryUsagePct
  type: decimal
- container: ''
  name: metricType
  type: string
- container: ''
  name: monitoredUsers
  type: integer
- container: ''
  name: name
  type: string
- container: ''
  name: networkScore
  type: integer
- container: ''
  name: os
  type: string
- container: ''
  name: osVersion
  type: string
- container: ''
  name: overallScore
  type: integer
- container: ''
  name: packetLossPct
  type: decimal
- container: ''
  name: sampleCount
  type: integer
- container: ''
  name: segment
  type: string
- container: ''
  name: siteName
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: tcpConnectMs
  type: decimal
- container: ''
  name: testCount
  type: integer
- container: ''
  name: testId
  type: string
- container: ''
  name: timestamp
  type: dateTime
- container: ''
  name: ttfbMs
  type: decimal
- container: ''
  name: type
  type: string
- container: ''
  name: unit
  type: string
- container: ''
  name: url
  type: string
- container: ''
  name: userId
  type: string
- container: ''
  name: value
  type: decimal
property_count: 39
provider_name: Palo Alto Networks
provider_slug: palo-alto-networks
slug: palo-alto-autonomous-dem-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"pan\": \"https://pan.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AgentScore\": \"pan:AgentScore\",\n    \"ApplicationScore\": \"pan:ApplicationScore\",\n    \"MonitoredAgent\": \"pan:MonitoredAgent\",\n    \"MonitoredApplication\": \"pan:MonitoredApplication\",\n    \"PerformanceMetric\": \"pan:PerformanceMetric\",\n    \"TestResult\": \"pan:TestResult\",\n    \"agentId\": {\n      \"@id\": \"pan:agent_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"agentVersion\": {\n      \"@id\": \"pan:agent_version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"appId\": {\n      \"@id\": \"pan:app_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"application\": {\n      \"@id\": \"pan:application\",\n      \"@type\": \"xsd:string\"\n    },\n    \"applicationScore\": {\n      \"@id\": \"pan:application_score\"\
  ,\n      \"@type\": \"xsd:integer\"\n    },\n    \"category\": {\n      \"@id\": \"pan:category\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cpuUsagePct\": {\n      \"@id\": \"pan:cpu_usage_pct\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"deviceName\": {\n      \"@id\": \"pan:device_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dnsTimeMs\": {\n      \"@id\": \"pan:dns_time_ms\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"endpointScore\": {\n      \"@id\": \"pan:endpoint_score\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"errorMessage\": {\n      \"@id\": \"pan:error_message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"httpStatusCode\": {\n      \"@id\": \"pan:http_status_code\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"jitterMs\": {\n      \"@id\": \"pan:jitter_ms\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"lastSeen\": {\n   \
  \   \"@id\": \"pan:last_seen\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"latencyMs\": {\n      \"@id\": \"pan:latency_ms\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"memoryUsagePct\": {\n      \"@id\": \"pan:memory_usage_pct\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"metricType\": {\n      \"@id\": \"pan:metric_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"monitoredUsers\": {\n      \"@id\": \"pan:monitored_users\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"networkScore\": {\n      \"@id\": \"pan:network_score\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"os\": {\n      \"@id\": \"pan:os\",\n      \"@type\": \"xsd:string\"\n    },\n    \"osVersion\": {\n      \"@id\": \"pan:os_version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"overallScore\": {\n      \"@id\": \"pan:overall_score\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"packetLossPct\"\
  : {\n      \"@id\": \"pan:packet_loss_pct\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"sampleCount\": {\n      \"@id\": \"pan:sample_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"segment\": {\n      \"@id\": \"pan:segment\",\n      \"@type\": \"xsd:string\"\n    },\n    \"siteName\": {\n      \"@id\": \"pan:site_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"pan:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tcpConnectMs\": {\n      \"@id\": \"pan:tcp_connect_ms\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"testCount\": {\n      \"@id\": \"pan:test_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"testId\": {\n      \"@id\": \"pan:test_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timestamp\": {\n      \"@id\": \"pan:timestamp\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"ttfbMs\": {\n      \"@id\": \"pan:ttfb_ms\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"type\": {\n      \"@id\"\
  : \"pan:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"unit\": {\n      \"@id\": \"pan:unit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"url\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"xsd:string\"\n    },\n    \"userId\": {\n      \"@id\": \"pan:user_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"pan:value\",\n      \"@type\": \"xsd:decimal\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/json-ld/palo-alto-autonomous-dem-api-context.jsonld
tags:
- Cloud Security
- Cybersecurity
- Firewall
- Network Security
- SASE
- SOAR
- Threat Intelligence
- XDR
- JSON-LD
- Linked Data
- Semantic Web
---
