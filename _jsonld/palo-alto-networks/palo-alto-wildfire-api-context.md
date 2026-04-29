---
class_count: 6
classes:
- AnalysisReport
- BulkVerdictResponse
- SandboxReport
- SubmitResponse
- VerdictResponse
- report
context_file: json-ld/palo-alto-wildfire-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/json-ld/palo-alto-wildfire-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Palo Alto Wildfire Api from Palo Alto Networks.
layout: jsonld
name: Palo Alto Wildfire Api Context
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
  name: createTime
  type: dateTime
- container: set
  name: dns
  type: reference
- container: set
  name: entry
  type: reference
- container: ''
  name: fileInfo
  type: reference
- container: ''
  name: fileStype
  type: string
- container: ''
  name: filename
  type: string
- container: ''
  name: filetype
  type: string
- container: ''
  name: fileurl
  type: string
- container: ''
  name: get-verdict-info
  type: reference
- container: ''
  name: get-verdicts-info
  type: reference
- container: set
  name: http
  type: reference
- container: ''
  name: md5
  type: string
- container: ''
  name: network
  type: reference
- container: ''
  name: platform
  type: string
- container: set
  name: process
  type: reference
- container: ''
  name: processList
  type: reference
- container: ''
  name: sha256
  type: string
- container: ''
  name: size
  type: integer
- container: ''
  name: software
  type: string
- container: ''
  name: summary
  type: reference
- container: ''
  name: taskInfo
  type: reference
- container: set
  name: tcp
  type: reference
- container: ''
  name: upload-file-info
  type: reference
- container: ''
  name: url
  type: string
- container: ''
  name: verdict
  type: integer
- container: ''
  name: version
  type: string
- container: ''
  name: wildfire
  type: reference
property_count: 27
provider_name: Palo Alto Networks
provider_slug: palo-alto-networks
slug: palo-alto-wildfire-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"pan\": \"https://pan.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AnalysisReport\": \"pan:AnalysisReport\",\n    \"BulkVerdictResponse\": \"pan:BulkVerdictResponse\",\n    \"SandboxReport\": \"pan:SandboxReport\",\n    \"SubmitResponse\": \"pan:SubmitResponse\",\n    \"VerdictResponse\": \"pan:VerdictResponse\",\n    \"@country\": {\n      \"@id\": \"pan:@country\",\n      \"@type\": \"xsd:string\"\n    },\n    \"@ip\": {\n      \"@id\": \"pan:@ip\",\n      \"@type\": \"xsd:string\"\n    },\n    \"@name\": {\n      \"@id\": \"pan:@name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"@pid\": {\n      \"@id\": \"pan:@pid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"@port\": {\n      \"@id\": \"pan:@port\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"@query\": {\n      \"@id\": \"pan:@query\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"@request\": {\n      \"@id\": \"pan:@request\",\n      \"@type\": \"xsd:string\"\n    },\n    \"@response\": {\n      \"@id\": \"pan:@response\",\n      \"@type\": \"xsd:string\"\n    },\n    \"@text\": {\n      \"@id\": \"pan:@text\",\n      \"@type\": \"xsd:string\"\n    },\n    \"@verdict\": {\n      \"@id\": \"pan:@verdict\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createTime\": {\n      \"@id\": \"pan:create_time\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"dns\": {\n      \"@id\": \"pan:dns\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"entry\": {\n      \"@id\": \"pan:entry\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"fileInfo\": {\n      \"@id\": \"pan:file_info\",\n      \"@type\": \"@id\"\n    },\n    \"fileStype\": {\n      \"@id\": \"pan:file_stype\",\n      \"@type\": \"xsd:string\"\n    },\n    \"filename\": {\n      \"@id\": \"pan:filename\",\n\
  \      \"@type\": \"xsd:string\"\n    },\n    \"filetype\": {\n      \"@id\": \"pan:filetype\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fileurl\": {\n      \"@id\": \"pan:fileurl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"get-verdict-info\": {\n      \"@id\": \"pan:get-verdict-info\",\n      \"@type\": \"@id\"\n    },\n    \"get-verdicts-info\": {\n      \"@id\": \"pan:get-verdicts-info\",\n      \"@type\": \"@id\"\n    },\n    \"http\": {\n      \"@id\": \"pan:http\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"md5\": {\n      \"@id\": \"pan:md5\",\n      \"@type\": \"xsd:string\"\n    },\n    \"network\": {\n      \"@id\": \"pan:network\",\n      \"@type\": \"@id\"\n    },\n    \"platform\": {\n      \"@id\": \"pan:platform\",\n      \"@type\": \"xsd:string\"\n    },\n    \"process\": {\n      \"@id\": \"pan:process\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"processList\": {\n      \"@id\": \"pan:process_list\"\
  ,\n      \"@type\": \"@id\"\n    },\n    \"report\": \"pan:report\",\n    \"sha256\": {\n      \"@id\": \"pan:sha256\",\n      \"@type\": \"xsd:string\"\n    },\n    \"size\": {\n      \"@id\": \"pan:size\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"software\": {\n      \"@id\": \"pan:software\",\n      \"@type\": \"xsd:string\"\n    },\n    \"summary\": {\n      \"@id\": \"pan:summary\",\n      \"@type\": \"@id\"\n    },\n    \"taskInfo\": {\n      \"@id\": \"pan:task_info\",\n      \"@type\": \"@id\"\n    },\n    \"tcp\": {\n      \"@id\": \"pan:tcp\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"upload-file-info\": {\n      \"@id\": \"pan:upload-file-info\",\n      \"@type\": \"@id\"\n    },\n    \"url\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"xsd:string\"\n    },\n    \"verdict\": {\n      \"@id\": \"pan:verdict\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"version\": {\n      \"@id\": \"schema:version\",\n      \"@type\": \"\
  xsd:string\"\n    },\n    \"wildfire\": {\n      \"@id\": \"pan:wildfire\",\n      \"@type\": \"@id\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/json-ld/palo-alto-wildfire-api-context.jsonld
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
