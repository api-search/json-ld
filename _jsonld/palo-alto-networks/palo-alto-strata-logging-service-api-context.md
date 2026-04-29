---
class_count: 9
classes:
- EmailDestination
- EmailDestinationRequest
- ForwardingStatus
- HTTPSDestination
- HTTPSDestinationRequest
- LogForwardingProfile
- LogForwardingProfileRequest
- SyslogDestination
- SyslogDestinationRequest
context_file: json-ld/palo-alto-strata-logging-service-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/json-ld/palo-alto-strata-logging-service-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Palo Alto Strata Logging Service Api from Palo Alto Networks.
layout: jsonld
name: Palo Alto Strata Logging Service Api Context
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
  name: andAlsoTo
  type: string
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: description
  type: string
- container: ''
  name: destinationCount
  type: integer
- container: ''
  name: destinationId
  type: string
- container: ''
  name: destinationType
  type: string
- container: set
  name: destinations
  type: reference
- container: ''
  name: enabled
  type: boolean
- container: ''
  name: errorCount24h
  type: integer
- container: ''
  name: facility
  type: string
- container: ''
  name: format
  type: string
- container: ''
  name: from
  type: string
- container: ''
  name: gateway
  type: string
- container: ''
  name: headers
  type: reference
- container: ''
  name: httpMethod
  type: string
- container: ''
  name: lastError
  type: string
- container: ''
  name: lastSuccessfulDelivery
  type: dateTime
- container: set
  name: logTypes
  type: string
- container: ''
  name: name
  type: string
- container: ''
  name: overallStatus
  type: string
- container: ''
  name: port
  type: integer
- container: ''
  name: profileId
  type: string
- container: ''
  name: protocol
  type: string
- container: ''
  name: server
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: tlsVerify
  type: boolean
- container: ''
  name: to
  type: string
- container: ''
  name: updatedAt
  type: dateTime
- container: ''
  name: uri
  type: reference
property_count: 29
provider_name: Palo Alto Networks
provider_slug: palo-alto-networks
slug: palo-alto-strata-logging-service-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"pan\": \"https://pan.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"EmailDestination\": \"pan:EmailDestination\",\n    \"EmailDestinationRequest\": \"pan:EmailDestinationRequest\",\n    \"ForwardingStatus\": \"pan:ForwardingStatus\",\n    \"HTTPSDestination\": \"pan:HTTPSDestination\",\n    \"HTTPSDestinationRequest\": \"pan:HTTPSDestinationRequest\",\n    \"LogForwardingProfile\": \"pan:LogForwardingProfile\",\n    \"LogForwardingProfileRequest\": \"pan:LogForwardingProfileRequest\",\n    \"SyslogDestination\": \"pan:SyslogDestination\",\n    \"SyslogDestinationRequest\": \"pan:SyslogDestinationRequest\",\n    \"andAlsoTo\": {\n      \"@id\": \"pan:and_also_to\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n\
  \    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"destinationCount\": {\n      \"@id\": \"pan:destination_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"destinationId\": {\n      \"@id\": \"pan:destination_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"destinationType\": {\n      \"@id\": \"pan:destination_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"destinations\": {\n      \"@id\": \"pan:destinations\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"enabled\": {\n      \"@id\": \"pan:enabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"errorCount24h\": {\n      \"@id\": \"pan:error_count_24h\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"facility\": {\n      \"@id\": \"pan:facility\",\n      \"@type\": \"xsd:string\"\n    },\n    \"format\": {\n      \"@id\": \"pan:format\",\n      \"@type\": \"xsd:string\"\n    },\n    \"from\": {\n      \"@id\": \"pan:from\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"gateway\": {\n      \"@id\": \"pan:gateway\",\n      \"@type\": \"xsd:string\"\n    },\n    \"headers\": {\n      \"@id\": \"pan:headers\",\n      \"@type\": \"@id\"\n    },\n    \"httpMethod\": {\n      \"@id\": \"pan:http_method\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastError\": {\n      \"@id\": \"pan:last_error\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastSuccessfulDelivery\": {\n      \"@id\": \"pan:last_successful_delivery\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"logTypes\": {\n      \"@id\": \"pan:log_types\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"overallStatus\": {\n      \"@id\": \"pan:overall_status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"port\": {\n      \"@id\": \"pan:port\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"profileId\": {\n      \"\
  @id\": \"pan:profile_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"protocol\": {\n      \"@id\": \"pan:protocol\",\n      \"@type\": \"xsd:string\"\n    },\n    \"server\": {\n      \"@id\": \"pan:server\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"pan:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tlsVerify\": {\n      \"@id\": \"pan:tls_verify\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"to\": {\n      \"@id\": \"pan:to\",\n      \"@type\": \"xsd:string\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"uri\": {\n      \"@id\": \"pan:uri\",\n      \"@type\": \"@id\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/json-ld/palo-alto-strata-logging-service-api-context.jsonld
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
