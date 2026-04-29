---
api_specs:
- filename: apache-http-client-openapi.yml
  format: yaml
  label: Apache HttpComponents Client API
  slug: apache-http-client-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/apache-http/refs/heads/main/openapi/apache-http-client-openapi.yml
class_count: 17
classes:
- method
- uri
- headers
- body
- contentType
- statusCode
- reasonPhrase
- connectTimeout
- socketTimeout
- maxConnections
- maxConnectionsPerRoute
- keepAliveTimeout
- host
- port
- scheme
- username
- password
context_file: json-ld/apache-http-client-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apache-http/refs/heads/main/json-ld/apache-http-client-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apache Http Client from Apache HttpComponents.
layout: jsonld
name: Apache Http Client Context
namespaces:
- prefix: httpclient
  uri: https://hc.apache.org/vocab#
properties: []
property_count: 0
provider_name: Apache HttpComponents
provider_slug: apache-http
slug: apache-http-client-context
source_filename: apache-http-client-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"httpclient\": \"https://hc.apache.org/vocab#\",\n    \"method\": \"httpclient:method\",\n    \"uri\": \"schema:url\",\n    \"headers\": \"httpclient:headers\",\n    \"body\": \"httpclient:body\",\n    \"contentType\": \"schema:encodingFormat\",\n    \"statusCode\": \"httpclient:statusCode\",\n    \"reasonPhrase\": \"httpclient:reasonPhrase\",\n    \"connectTimeout\": \"httpclient:connectTimeout\",\n    \"socketTimeout\": \"httpclient:socketTimeout\",\n    \"maxConnections\": \"httpclient:maxConnections\",\n    \"maxConnectionsPerRoute\": \"httpclient:maxConnectionsPerRoute\",\n    \"keepAliveTimeout\": \"httpclient:keepAliveTimeout\",\n    \"host\": \"schema:hostName\",\n    \"port\": \"schema:portNumber\",\n    \"scheme\": \"httpclient:scheme\",\n    \"username\": \"schema:accountId\",\n    \"password\": \"httpclient:password\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/apache-http/refs/heads/main/json-ld/apache-http-client-context.jsonld
tags:
- Apache
- HTTP Client
- Java
- Open Source
- SDK
- JSON-LD
- Linked Data
- Semantic Web
---
