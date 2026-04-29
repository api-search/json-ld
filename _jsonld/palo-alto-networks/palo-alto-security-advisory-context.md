---
class_count: 6
classes:
- Palo Alto Networks Security Advisory
- cna
- containers
- cveMetadata
- cvssV31
- cvssV40
context_file: json-ld/palo-alto-security-advisory-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/json-ld/palo-alto-security-advisory-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Palo Alto Security Advisory from Palo Alto Networks.
layout: jsonld
name: Palo Alto Security Advisory Context
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
- container: set
  name: adp
  type: ''
- container: set
  name: affected
  type: ''
- container: ''
  name: assignerOrgId
  type: string
- container: ''
  name: baseScore
  type: decimal
- container: ''
  name: baseSeverity
  type: string
- container: set
  name: configurations
  type: ''
- container: ''
  name: cveId
  type: string
- container: ''
  name: dataType
  type: string
- container: ''
  name: datePublished
  type: dateTime
- container: ''
  name: dateUpdated
  type: dateTime
- container: set
  name: descriptions
  type: ''
- container: ''
  name: lang
  type: string
- container: ''
  name: lessThan
  type: string
- container: ''
  name: lessThanOrEqual
  type: string
- container: set
  name: metrics
  type: ''
- container: ''
  name: name
  type: string
- container: ''
  name: orgId
  type: string
- container: ''
  name: product
  type: string
- container: set
  name: references
  type: ''
- container: set
  name: solutions
  type: ''
- container: ''
  name: state
  type: string
- container: ''
  name: status
  type: string
- container: set
  name: tags
  type: string
- container: ''
  name: title
  type: string
- container: ''
  name: url
  type: reference
- container: ''
  name: value
  type: string
- container: ''
  name: vectorString
  type: string
- container: ''
  name: vendor
  type: string
- container: ''
  name: version
  type: string
- container: ''
  name: versionType
  type: string
- container: set
  name: versions
  type: ''
- container: set
  name: workarounds
  type: ''
property_count: 32
provider_name: Palo Alto Networks
provider_slug: palo-alto-networks
slug: palo-alto-security-advisory-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"pan\": \"https://pan.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Palo Alto Networks Security Advisory\": \"pan:Palo Alto Networks Security Advisory\",\n    \"adp\": {\n      \"@id\": \"pan:adp\",\n      \"@container\": \"@set\"\n    },\n    \"affected\": {\n      \"@id\": \"pan:affected\",\n      \"@container\": \"@set\"\n    },\n    \"assignerOrgId\": {\n      \"@id\": \"pan:assignerOrgId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"baseScore\": {\n      \"@id\": \"pan:baseScore\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"baseSeverity\": {\n      \"@id\": \"pan:baseSeverity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cna\": \"pan:cna\",\n    \"configurations\": {\n      \"@id\": \"pan:configurations\",\n      \"@container\": \"@set\"\n    },\n    \"containers\": \"pan:containers\"\
  ,\n    \"cveId\": {\n      \"@id\": \"pan:cveId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cveMetadata\": \"pan:cveMetadata\",\n    \"cvssV31\": \"pan:cvssV3_1\",\n    \"cvssV40\": \"pan:cvssV4_0\",\n    \"dataType\": {\n      \"@id\": \"pan:dataType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"datePublished\": {\n      \"@id\": \"pan:datePublished\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"dateUpdated\": {\n      \"@id\": \"pan:dateUpdated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"descriptions\": {\n      \"@id\": \"pan:descriptions\",\n      \"@container\": \"@set\"\n    },\n    \"lang\": {\n      \"@id\": \"pan:lang\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lessThan\": {\n      \"@id\": \"pan:lessThan\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lessThanOrEqual\": {\n      \"@id\": \"pan:lessThanOrEqual\",\n      \"@type\": \"xsd:string\"\n    },\n    \"metrics\": {\n      \"@id\": \"pan:metrics\",\n      \"@container\": \"@set\"\n \
  \   },\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"orgId\": {\n      \"@id\": \"pan:orgId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"product\": {\n      \"@id\": \"pan:product\",\n      \"@type\": \"xsd:string\"\n    },\n    \"references\": {\n      \"@id\": \"pan:references\",\n      \"@container\": \"@set\"\n    },\n    \"solutions\": {\n      \"@id\": \"pan:solutions\",\n      \"@container\": \"@set\"\n    },\n    \"state\": {\n      \"@id\": \"pan:state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"pan:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tags\": {\n      \"@id\": \"pan:tags\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"title\": {\n      \"@id\": \"pan:title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"url\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    },\n    \"value\": {\n      \"@id\": \"pan:value\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"vectorString\": {\n      \"@id\": \"pan:vectorString\",\n      \"@type\": \"xsd:string\"\n    },\n    \"vendor\": {\n      \"@id\": \"pan:vendor\",\n      \"@type\": \"xsd:string\"\n    },\n    \"version\": {\n      \"@id\": \"schema:version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"versionType\": {\n      \"@id\": \"pan:versionType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"versions\": {\n      \"@id\": \"pan:versions\",\n      \"@container\": \"@set\"\n    },\n    \"workarounds\": {\n      \"@id\": \"pan:workarounds\",\n      \"@container\": \"@set\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/json-ld/palo-alto-security-advisory-context.jsonld
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
