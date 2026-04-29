---
class_count: 2
classes:
- DomainDetail
- NetworkStats
context_file: json-ld/palo-alto-dns-security-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/json-ld/palo-alto-dns-security-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Palo Alto Dns Security Api from Palo Alto Networks.
layout: jsonld
name: Palo Alto Dns Security Api Context
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
  name: allowedQueries
  type: integer
- container: ''
  name: blockedQueries
  type: integer
- container: ''
  name: category
  type: string
- container: set
  name: categoryBreakdown
  type: reference
- container: ''
  name: count
  type: integer
- container: ''
  name: customerid
  type: string
- container: ''
  name: dnsSecurityCategory
  type: string
- container: ''
  name: domain
  type: string
- container: ''
  name: end
  type: string
- container: ''
  name: firstSeen
  type: dateTime
- container: set
  name: ipAddresses
  type: string
- container: ''
  name: lastSeen
  type: dateTime
- container: ''
  name: percentage
  type: float
- container: ''
  name: period
  type: reference
- container: ''
  name: queryCount
  type: integer
- container: ''
  name: registrar
  type: string
- container: ''
  name: registrationDate
  type: date
- container: ''
  name: riskLevel
  type: string
- container: ''
  name: riskScore
  type: float
- container: ''
  name: sinkholedQueries
  type: integer
- container: ''
  name: start
  type: string
- container: set
  name: topQueriedDomains
  type: reference
- container: ''
  name: totalQueries
  type: integer
property_count: 23
provider_name: Palo Alto Networks
provider_slug: palo-alto-networks
slug: palo-alto-dns-security-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"pan\": \"https://pan.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"DomainDetail\": \"pan:DomainDetail\",\n    \"NetworkStats\": \"pan:NetworkStats\",\n    \"allowedQueries\": {\n      \"@id\": \"pan:allowed_queries\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"blockedQueries\": {\n      \"@id\": \"pan:blocked_queries\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"category\": {\n      \"@id\": \"pan:category\",\n      \"@type\": \"xsd:string\"\n    },\n    \"categoryBreakdown\": {\n      \"@id\": \"pan:category_breakdown\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"count\": {\n      \"@id\": \"pan:count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"customerid\": {\n      \"@id\": \"pan:customerid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dnsSecurityCategory\"\
  : {\n      \"@id\": \"pan:dns_security_category\",\n      \"@type\": \"xsd:string\"\n    },\n    \"domain\": {\n      \"@id\": \"pan:domain\",\n      \"@type\": \"xsd:string\"\n    },\n    \"end\": {\n      \"@id\": \"pan:end\",\n      \"@type\": \"xsd:string\"\n    },\n    \"firstSeen\": {\n      \"@id\": \"pan:first_seen\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"ipAddresses\": {\n      \"@id\": \"pan:ip_addresses\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastSeen\": {\n      \"@id\": \"pan:last_seen\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"percentage\": {\n      \"@id\": \"pan:percentage\",\n      \"@type\": \"xsd:float\"\n    },\n    \"period\": {\n      \"@id\": \"pan:period\",\n      \"@type\": \"@id\"\n    },\n    \"queryCount\": {\n      \"@id\": \"pan:query_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"registrar\": {\n      \"@id\": \"pan:registrar\",\n      \"@type\": \"xsd:string\"\n    },\n    \"registrationDate\"\
  : {\n      \"@id\": \"pan:registration_date\",\n      \"@type\": \"xsd:date\"\n    },\n    \"riskLevel\": {\n      \"@id\": \"pan:risk_level\",\n      \"@type\": \"xsd:string\"\n    },\n    \"riskScore\": {\n      \"@id\": \"pan:risk_score\",\n      \"@type\": \"xsd:float\"\n    },\n    \"sinkholedQueries\": {\n      \"@id\": \"pan:sinkholed_queries\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"start\": {\n      \"@id\": \"pan:start\",\n      \"@type\": \"xsd:string\"\n    },\n    \"topQueriedDomains\": {\n      \"@id\": \"pan:top_queried_domains\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"totalQueries\": {\n      \"@id\": \"pan:total_queries\",\n      \"@type\": \"xsd:integer\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/json-ld/palo-alto-dns-security-api-context.jsonld
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
