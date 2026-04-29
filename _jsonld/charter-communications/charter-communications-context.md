---
api_specs:
- filename: charter-communications-spectrum-enterprise-api-openapi.yml
  format: yaml
  label: Charter Communications Spectrum Enterprise API
  slug: spectrum-enterprise-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/charter-communications/refs/heads/main/openapi/charter-communications-spectrum-enterprise-api-openapi.yml
- filename: charter-communications-bryte-iq-api-openapi.yml
  format: yaml
  label: Charter Communications Bryte IQ API
  slug: bryte-iq-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/charter-communications/refs/heads/main/openapi/charter-communications-bryte-iq-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/charter-communications-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/charter-communications/refs/heads/main/json-ld/charter-communications-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Charter Communications from Charter Communications.
layout: jsonld
name: Charter Communications Context
namespaces:
- prefix: spectrum
  uri: https://enterprise.spectrum.com/schemas/
- prefix: bryteiq
  uri: https://api.charter.com/schemas/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Ticket
  type: ''
- container: ''
  name: Serviceability
  type: ''
- container: ''
  name: Device
  type: ''
- container: ''
  name: NetworkSession
  type: ''
property_count: 4
provider_name: Charter Communications
provider_slug: charter-communications
slug: charter-communications-context
source_filename: charter-communications-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"spectrum\": \"https://enterprise.spectrum.com/schemas/\",\n    \"bryteiq\": \"https://api.charter.com/schemas/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Ticket\": {\n      \"@id\": \"spectrum:Ticket\",\n      \"@context\": {\n        \"ticketId\": \"spectrum:ticketId\",\n        \"subject\": \"schema:about\",\n        \"description\": \"schema:description\",\n        \"status\": \"spectrum:status\",\n        \"priority\": \"spectrum:priority\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Serviceability\": {\n      \"@id\": \"spectrum:Serviceability\",\n      \"@context\": {\n        \"address\": \"\
  schema:address\",\n        \"isServiceable\": {\n          \"@id\": \"spectrum:isServiceable\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"availableProducts\": \"spectrum:availableProducts\"\n      }\n    },\n\n    \"Device\": {\n      \"@id\": \"bryteiq:Device\",\n      \"@context\": {\n        \"deviceId\": \"bryteiq:deviceId\",\n        \"deviceType\": \"bryteiq:deviceType\",\n        \"ipAddress\": \"bryteiq:ipAddress\",\n        \"lastSeen\": {\n          \"@id\": \"bryteiq:lastSeen\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"NetworkSession\": {\n      \"@id\": \"bryteiq:NetworkSession\",\n      \"@context\": {\n        \"sessionId\": \"bryteiq:sessionId\",\n        \"phoneNumber\": \"schema:telephone\",\n        \"startTime\": {\n          \"@id\": \"bryteiq:startTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"endTime\": {\n          \"@id\": \"bryteiq:endTime\",\n          \"@type\": \"xsd:dateTime\"\n  \
  \      }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/charter-communications/refs/heads/main/json-ld/charter-communications-context.jsonld
tags:
- Broadband
- Cable
- CAMARA
- Enterprise
- Network as a Service
- NaaS
- Spectrum
- Telecommunications
- Ticketing
- JSON-LD
- Linked Data
- Semantic Web
---
