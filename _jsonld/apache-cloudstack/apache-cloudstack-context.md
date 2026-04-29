---
class_count: 6
classes:
- VirtualMachine
- Network
- Volume
- Zone
- AsyncJobResponse
- AsyncJobResult
context_file: json-ld/apache-cloudstack-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apache-cloudstack/refs/heads/main/json-ld/apache-cloudstack-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apache Cloudstack from Apache CloudStack.
layout: jsonld
name: Apache Cloudstack Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: cloudstack
  uri: https://cloudstack.apache.org/vocab#
properties:
- container: ''
  name: id
  type: string
- container: ''
  name: name
  type: string
- container: ''
  name: state
  type: string
- container: ''
  name: zoneid
  type: string
- container: ''
  name: zonename
  type: string
- container: ''
  name: serviceofferingid
  type: string
- container: ''
  name: templateid
  type: string
- container: ''
  name: cpunumber
  type: integer
- container: ''
  name: memory
  type: integer
- container: ''
  name: ipaddress
  type: string
- container: ''
  name: cidr
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: size
  type: long
- container: ''
  name: virtualmachineid
  type: string
- container: ''
  name: networktype
  type: string
- container: ''
  name: allocationstate
  type: string
- container: ''
  name: securitygroupsenabled
  type: boolean
- container: ''
  name: jobid
  type: string
- container: ''
  name: jobstatus
  type: integer
- container: ''
  name: jobresultcode
  type: integer
- container: ''
  name: jobresult
  type: ''
property_count: 21
provider_name: Apache CloudStack
provider_slug: apache-cloudstack
slug: apache-cloudstack-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"cloudstack\": \"https://cloudstack.apache.org/vocab#\",\n    \"VirtualMachine\": \"cloudstack:VirtualMachine\",\n    \"Network\": \"cloudstack:Network\",\n    \"Volume\": \"cloudstack:Volume\",\n    \"Zone\": \"cloudstack:Zone\",\n    \"AsyncJobResponse\": \"cloudstack:AsyncJobResponse\",\n    \"AsyncJobResult\": \"cloudstack:AsyncJobResult\",\n    \"id\": { \"@id\": \"cloudstack:id\", \"@type\": \"xsd:string\" },\n    \"name\": { \"@id\": \"cloudstack:name\", \"@type\": \"xsd:string\" },\n    \"state\": { \"@id\": \"cloudstack:state\", \"@type\": \"xsd:string\" },\n    \"zoneid\": { \"@id\": \"cloudstack:zoneid\", \"@type\": \"xsd:string\" },\n    \"zonename\": { \"@id\": \"cloudstack:zonename\", \"@type\": \"xsd:string\" },\n    \"serviceofferingid\": { \"@id\": \"cloudstack:serviceofferingid\"\
  , \"@type\": \"xsd:string\" },\n    \"templateid\": { \"@id\": \"cloudstack:templateid\", \"@type\": \"xsd:string\" },\n    \"cpunumber\": { \"@id\": \"cloudstack:cpunumber\", \"@type\": \"xsd:integer\" },\n    \"memory\": { \"@id\": \"cloudstack:memory\", \"@type\": \"xsd:integer\" },\n    \"ipaddress\": { \"@id\": \"cloudstack:ipaddress\", \"@type\": \"xsd:string\" },\n    \"cidr\": { \"@id\": \"cloudstack:cidr\", \"@type\": \"xsd:string\" },\n    \"type\": { \"@id\": \"cloudstack:type\", \"@type\": \"xsd:string\" },\n    \"size\": { \"@id\": \"cloudstack:size\", \"@type\": \"xsd:long\" },\n    \"virtualmachineid\": { \"@id\": \"cloudstack:virtualmachineid\", \"@type\": \"xsd:string\" },\n    \"networktype\": { \"@id\": \"cloudstack:networktype\", \"@type\": \"xsd:string\" },\n    \"allocationstate\": { \"@id\": \"cloudstack:allocationstate\", \"@type\": \"xsd:string\" },\n    \"securitygroupsenabled\": { \"@id\": \"cloudstack:securitygroupsenabled\", \"@type\": \"xsd:boolean\" },\n\
  \    \"jobid\": { \"@id\": \"cloudstack:jobid\", \"@type\": \"xsd:string\" },\n    \"jobstatus\": { \"@id\": \"cloudstack:jobstatus\", \"@type\": \"xsd:integer\" },\n    \"jobresultcode\": { \"@id\": \"cloudstack:jobresultcode\", \"@type\": \"xsd:integer\" },\n    \"jobresult\": { \"@id\": \"cloudstack:jobresult\" }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/apache-cloudstack/refs/heads/main/json-ld/apache-cloudstack-context.jsonld
tags:
- Apache
- Cloud
- IaaS
- Infrastructure
- Open Source
- Virtualization
- JSON-LD
- Linked Data
- Semantic Web
---
