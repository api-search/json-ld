---
api_specs:
- filename: squid-cache-manager-openapi.yml
  format: yaml
  label: Squid Cache Manager API
  slug: squid-cache-manager
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/squid/refs/heads/main/openapi/squid-cache-manager-openapi.yml
class_count: 28
classes:
- CacheProxy
- CacheStatistics
- CacheObject
- Connection
- AccessControlList
- squid_version
- uptime_seconds
- cache_hits
- total
- memory
- disk
- request_counts
- byte_counts
- bytes_from_clients
- bytes_to_clients
- bytes_from_servers
- bytes_to_servers
- memory_usage
- total_accounted
- max_resident
- current_resident
- store_directory
- current_objects
- client_addr
- method
- url
- elapsed_seconds
- cache_status
context_file: json-ld/squid-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/squid/refs/heads/main/json-ld/squid-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Squid from Squid.
layout: jsonld
name: Squid Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: squid
  uri: http://www.squid-cache.org/vocab/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: nwk
  uri: https://www.w3.org/ns/network-vocab#
properties:
- container: ''
  name: start_time
  type: dateTime
- container: ''
  name: current_time
  type: dateTime
- container: ''
  name: hit_ratio
  type: decimal
- container: ''
  name: current_capacity
  type: decimal
property_count: 4
provider_name: Squid
provider_slug: squid
slug: squid-context
source_filename: squid-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"squid\": \"http://www.squid-cache.org/vocab/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"nwk\": \"https://www.w3.org/ns/network-vocab#\",\n\n    \"CacheProxy\": \"schema:SoftwareApplication\",\n    \"CacheStatistics\": \"squid:CacheStatistics\",\n    \"CacheObject\": \"squid:CacheObject\",\n    \"Connection\": \"nwk:Connection\",\n    \"AccessControlList\": \"squid:ACL\",\n\n    \"squid_version\": \"schema:softwareVersion\",\n    \"start_time\": {\n      \"@id\": \"schema:startDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"current_time\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"uptime_seconds\": \"squid:uptimeSeconds\",\n\n    \"cache_hits\": \"squid:cacheHits\",\n    \"hit_ratio\": {\n      \"@id\": \"squid:hitRatio\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"total\": \"schema:totalItems\",\n\
  \    \"memory\": \"squid:memoryHits\",\n    \"disk\": \"squid:diskHits\",\n\n    \"request_counts\": \"squid:requestCounts\",\n    \"byte_counts\": \"squid:byteCounts\",\n    \"bytes_from_clients\": \"squid:bytesFromClients\",\n    \"bytes_to_clients\": \"squid:bytesToClients\",\n    \"bytes_from_servers\": \"squid:bytesFromServers\",\n    \"bytes_to_servers\": \"squid:bytesToServers\",\n\n    \"memory_usage\": \"squid:memoryUsage\",\n    \"total_accounted\": \"squid:totalAccountedBytes\",\n    \"max_resident\": \"squid:maxResidentSetSize\",\n    \"current_resident\": \"squid:currentResidentSetSize\",\n\n    \"store_directory\": \"squid:storeDirectory\",\n    \"current_objects\": \"schema:numberOfItems\",\n    \"current_capacity\": {\n      \"@id\": \"squid:capacityUsed\",\n      \"@type\": \"xsd:decimal\"\n    },\n\n    \"client_addr\": \"schema:sender\",\n    \"method\": \"schema:httpMethod\",\n    \"url\": \"schema:url\",\n    \"elapsed_seconds\": \"squid:elapsedSeconds\",\n    \"cache_status\"\
  : \"squid:cacheStatus\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/squid/refs/heads/main/json-ld/squid-context.jsonld
tags:
- Caching Proxy
- Proxy
- HTTP Proxy
- Web Cache
- Access Control
- Content Filtering
- JSON-LD
- Linked Data
- Semantic Web
---
