---
api_specs:
- filename: dns-openapi.yml
  format: yaml
  label: Google Cloud DNS API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-cloud-dns/refs/heads/main/openapi/dns-openapi.yml
class_count: 11
classes:
- ManagedZone
- ResourceRecordSet
- Change
- Policy
- name
- description
- id
- dnsName
- visibility
- nameServers
- rrdatas
context_file: json-ld/dns-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-cloud-dns/refs/heads/main/json-ld/dns-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Dns from Google Cloud DNS.
layout: jsonld
name: Dns Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: gcp
  uri: https://cloud.google.com/schema#
properties:
- container: ''
  name: ttl
  type: integer
- container: ''
  name: creationTime
  type: dateTime
- container: ''
  name: startTime
  type: dateTime
property_count: 3
provider_name: Google Cloud DNS
provider_slug: google-cloud-dns
slug: dns-context
source_filename: dns-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://cloud.google.com/dns/schema#\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"gcp\": \"https://cloud.google.com/schema#\",\n    \"ManagedZone\": \"gcp:DNSManagedZone\",\n    \"ResourceRecordSet\": \"gcp:DNSResourceRecordSet\",\n    \"Change\": \"gcp:DNSChange\",\n    \"Policy\": \"gcp:DNSPolicy\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"id\": \"schema:identifier\",\n    \"dnsName\": \"gcp:dnsName\",\n    \"visibility\": \"gcp:visibility\",\n    \"nameServers\": \"gcp:nameServers\",\n    \"ttl\": {\n      \"@id\": \"gcp:ttl\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"rrdatas\": \"gcp:rrdatas\",\n    \"creationTime\": {\n      \"@id\": \"dcterms:created\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"startTime\": {\n      \"@id\": \"gcp:startTime\",\n      \"@type\": \"\
  xsd:dateTime\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-cloud-dns/refs/heads/main/json-ld/dns-context.jsonld
tags:
- DNS
- Domain Names
- Google Cloud
- Name Resolution
- Networking
- JSON-LD
- Linked Data
- Semantic Web
---
