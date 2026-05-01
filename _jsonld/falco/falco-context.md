---
api_specs:
- filename: falco-openapi.yml
  format: yaml
  label: Falco HTTP API
  slug: falco-http-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/falco/refs/heads/main/openapi/falco-openapi.yml
class_count: 5
classes:
- Rule
- Macro
- List
- Alert
- DetectionEngine
context_file: json-ld/falco-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/falco/refs/heads/main/json-ld/falco-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Falco from Falco.
layout: jsonld
name: Falco Context
namespaces:
- prefix: falco
  uri: https://falco.org/vocab#
- prefix: schema
  uri: https://schema.org/
- prefix: sec
  uri: https://w3id.org/security#
- prefix: spdx
  uri: https://spdx.org/rdf/terms#
- prefix: stix
  uri: https://docs.oasis-open.org/cti/stix/v2.1/vocab#
- prefix: mitre
  uri: https://attack.mitre.org/techniques/
- prefix: cve
  uri: https://cve.mitre.org/cgi-bin/cvename.cgi?name=
- prefix: oci
  uri: https://opencontainers.org/schema#
- prefix: k8s
  uri: https://kubernetes.io/docs/reference/generated/kubernetes-api/v1.28/#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: rule
  type: string
- container: ''
  name: condition
  type: string
- container: ''
  name: output
  type: string
- container: ''
  name: priority
  type: string
- container: ''
  name: source
  type: string
- container: ''
  name: enabled
  type: boolean
- container: set
  name: tags
  type: ''
- container: ''
  name: hostname
  type: string
- container: ''
  name: time
  type: dateTime
- container: ''
  name: uuid
  type: string
- container: ''
  name: processName
  type: string
- container: ''
  name: processId
  type: integer
- container: ''
  name: parentProcessName
  type: string
- container: ''
  name: commandLine
  type: string
- container: ''
  name: userName
  type: string
- container: ''
  name: userId
  type: integer
- container: ''
  name: containerId
  type: string
- container: ''
  name: containerName
  type: string
- container: ''
  name: containerImage
  type: string
- container: ''
  name: containerImageTag
  type: string
- container: ''
  name: namespace
  type: string
- container: ''
  name: podName
  type: string
- container: ''
  name: threatCategory
  type: reference
- container: ''
  name: mitreAttackTechnique
  type: reference
- container: ''
  name: description
  type: string
- container: ''
  name: name
  type: string
- container: ''
  name: version
  type: string
- container: ''
  name: license
  type: string
property_count: 28
provider_name: Falco
provider_slug: falco
slug: falco-context
source_filename: falco-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"falco\": \"https://falco.org/vocab#\",\n    \"schema\": \"https://schema.org/\",\n    \"sec\": \"https://w3id.org/security#\",\n    \"spdx\": \"https://spdx.org/rdf/terms#\",\n    \"stix\": \"https://docs.oasis-open.org/cti/stix/v2.1/vocab#\",\n    \"mitre\": \"https://attack.mitre.org/techniques/\",\n    \"cve\": \"https://cve.mitre.org/cgi-bin/cvename.cgi?name=\",\n    \"oci\": \"https://opencontainers.org/schema#\",\n    \"k8s\": \"https://kubernetes.io/docs/reference/generated/kubernetes-api/v1.28/#\",\n\n    \"Rule\": \"falco:Rule\",\n    \"Macro\": \"falco:Macro\",\n    \"List\": \"falco:List\",\n    \"Alert\": \"falco:Alert\",\n    \"DetectionEngine\": \"falco:DetectionEngine\",\n\n    \"rule\": {\n      \"@id\": \"falco:ruleName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"condition\": {\n      \"@id\": \"falco:condition\",\n      \"@type\": \"xsd:string\"\n    },\n    \"output\": {\n      \"@id\": \"falco:output\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"priority\": {\n      \"@id\": \"falco:priority\",\n      \"@type\": \"xsd:string\"\n    },\n    \"source\": {\n      \"@id\": \"falco:dataSource\",\n      \"@type\": \"xsd:string\"\n    },\n    \"enabled\": {\n      \"@id\": \"falco:enabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"tags\": {\n      \"@id\": \"schema:keywords\",\n      \"@container\": \"@set\"\n    },\n\n    \"hostname\": {\n      \"@id\": \"schema:hostName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"time\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"uuid\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"processName\": {\n      \"@id\": \"falco:processName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"processId\": {\n      \"@id\": \"falco:processId\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"parentProcessName\": {\n      \"@id\": \"falco:parentProcessName\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"commandLine\": {\n      \"@id\": \"falco:commandLine\",\n      \"@type\": \"xsd:string\"\n    },\n    \"userName\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"userId\": {\n      \"@id\": \"falco:userId\",\n      \"@type\": \"xsd:integer\"\n    },\n\n    \"containerId\": {\n      \"@id\": \"oci:containerId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"containerName\": {\n      \"@id\": \"oci:containerName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"containerImage\": {\n      \"@id\": \"oci:imageRepository\",\n      \"@type\": \"xsd:string\"\n    },\n    \"containerImageTag\": {\n      \"@id\": \"oci:imageTag\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"namespace\": {\n      \"@id\": \"k8s:namespace\",\n      \"@type\": \"xsd:string\"\n    },\n    \"podName\": {\n      \"@id\": \"k8s:podName\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"threatCategory\": {\n      \"@id\":\
  \ \"stix:attack-pattern\",\n      \"@type\": \"@id\"\n    },\n    \"mitreAttackTechnique\": {\n      \"@id\": \"mitre:technique\",\n      \"@type\": \"@id\"\n    },\n\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"version\": {\n      \"@id\": \"schema:softwareVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"license\": {\n      \"@id\": \"spdx:licenseDeclared\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/falco/refs/heads/main/json-ld/falco-context.jsonld
tags:
- Cloud Native
- eBPF
- Runtime Security
- Security
- Threat Detection
- JSON-LD
- Linked Data
- Semantic Web
---
