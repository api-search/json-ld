---
class_count: 23
classes:
- ProxyConfiguration
- AccessControlRule
- UpstreamProxy
- FilterRule
- SoftwareApplication
- user
- group
- logFile
- logLevel
- pidFile
- maxClients
- allow
- deny
- upstream
- noUpstream
- filter
- filterURLs
- connectPort
- statHost
- reverseOnly
- reverseBaseURL
- disableViaHeader
- xTinyproxyHeader
context_file: json-ld/tinyproxy-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/tinyproxy/refs/heads/main/json-ld/tinyproxy-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Tinyproxy from Tinyproxy.
layout: jsonld
name: Tinyproxy Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: tinyproxy
  uri: https://tinyproxy.github.io/vocab/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: port
  type: integer
- container: ''
  name: timeout
  type: integer
property_count: 2
provider_name: Tinyproxy
provider_slug: tinyproxy
slug: tinyproxy-context
source_filename: tinyproxy-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"tinyproxy\": \"https://tinyproxy.github.io/vocab/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"ProxyConfiguration\": \"tinyproxy:ProxyConfiguration\",\n    \"AccessControlRule\": \"tinyproxy:AccessControlRule\",\n    \"UpstreamProxy\": \"tinyproxy:UpstreamProxy\",\n    \"FilterRule\": \"tinyproxy:FilterRule\",\n    \"SoftwareApplication\": \"schema:SoftwareApplication\",\n\n    \"port\": {\n      \"@id\": \"schema:serverPort\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"user\": \"schema:accountId\",\n    \"group\": \"tinyproxy:processGroup\",\n    \"logFile\": \"tinyproxy:logFilePath\",\n    \"logLevel\": \"tinyproxy:logLevel\",\n    \"pidFile\": \"tinyproxy:pidFilePath\",\n    \"maxClients\": \"tinyproxy:maxConnections\",\n    \"timeout\": {\n      \"@id\": \"tinyproxy:connectionTimeout\",\n      \"@type\": \"xsd:integer\"\n    },\n\n    \"allow\": \"tinyproxy:allowRule\"\
  ,\n    \"deny\": \"tinyproxy:denyRule\",\n    \"upstream\": \"tinyproxy:upstreamProxy\",\n    \"noUpstream\": \"tinyproxy:bypassUpstream\",\n    \"filter\": \"tinyproxy:filterFile\",\n    \"filterURLs\": \"tinyproxy:filterByUrl\",\n    \"connectPort\": \"tinyproxy:allowedConnectPort\",\n    \"statHost\": \"tinyproxy:statisticsHost\",\n\n    \"reverseOnly\": \"tinyproxy:reverseProxyMode\",\n    \"reverseBaseURL\": \"tinyproxy:reverseBaseUrl\",\n\n    \"disableViaHeader\": \"tinyproxy:disableVia\",\n    \"xTinyproxyHeader\": \"tinyproxy:addClientIpHeader\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/tinyproxy/refs/heads/main/json-ld/tinyproxy-context.jsonld
tags:
- Forward Proxy
- Proxy
- HTTP
- Networking
- Open Source
- JSON-LD
- Linked Data
- Semantic Web
---
