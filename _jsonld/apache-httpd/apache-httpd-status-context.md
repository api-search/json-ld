---
api_specs:
- filename: apache-httpd-status-openapi.yml
  format: yaml
  label: Apache HTTP Server Status API
  slug: apache-httpd-status-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/apache-httpd/refs/heads/main/openapi/apache-httpd-status-openapi.yml
class_count: 26
classes:
- ServerVersion
- ServerMPM
- ServerUptimeSeconds
- Load1
- Load5
- Load15
- ReqPerSec
- BytesPerSec
- BusyWorkers
- IdleWorkers
- Scoreboard
- serverName
- serverAliases
- documentRoot
- port
- sslEnabled
- errorLog
- accessLog
- url
- scheme
- hostname
- loadFactor
- lbStatus
- lbMethod
- nonce
- members
context_file: json-ld/apache-httpd-status-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apache-httpd/refs/heads/main/json-ld/apache-httpd-status-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apache Httpd Status from Apache HTTP Server.
layout: jsonld
name: Apache Httpd Status Context
namespaces:
- prefix: httpd
  uri: https://httpd.apache.org/vocab#
properties: []
property_count: 0
provider_name: Apache HTTP Server
provider_slug: apache-httpd
slug: apache-httpd-status-context
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"httpd\": \"https://httpd.apache.org/vocab#\",\n    \"ServerVersion\": \"httpd:ServerVersion\",\n    \"ServerMPM\": \"httpd:ServerMPM\",\n    \"ServerUptimeSeconds\": \"httpd:ServerUptimeSeconds\",\n    \"Load1\": \"httpd:Load1\",\n    \"Load5\": \"httpd:Load5\",\n    \"Load15\": \"httpd:Load15\",\n    \"ReqPerSec\": \"httpd:ReqPerSec\",\n    \"BytesPerSec\": \"httpd:BytesPerSec\",\n    \"BusyWorkers\": \"httpd:BusyWorkers\",\n    \"IdleWorkers\": \"httpd:IdleWorkers\",\n    \"Scoreboard\": \"httpd:Scoreboard\",\n    \"serverName\": \"schema:name\",\n    \"serverAliases\": \"httpd:serverAliases\",\n    \"documentRoot\": \"httpd:documentRoot\",\n    \"port\": \"schema:portNumber\",\n    \"sslEnabled\": \"httpd:sslEnabled\",\n    \"errorLog\": \"httpd:errorLog\",\n    \"accessLog\": \"httpd:accessLog\",\n    \"url\": \"schema:url\",\n    \"scheme\": \"httpd:scheme\",\n    \"hostname\": \"schema:hostName\",\n\
  \    \"loadFactor\": \"httpd:loadFactor\",\n    \"lbStatus\": \"httpd:lbStatus\",\n    \"lbMethod\": \"httpd:lbMethod\",\n    \"nonce\": \"httpd:nonce\",\n    \"members\": \"httpd:members\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/apache-httpd/refs/heads/main/json-ld/apache-httpd-status-context.jsonld
tags:
- Apache
- Load Balancer
- Open Source
- Proxy
- Reverse Proxy
- Web Server
- JSON-LD
- Linked Data
- Semantic Web
---
