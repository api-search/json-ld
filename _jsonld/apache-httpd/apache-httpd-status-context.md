---
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
