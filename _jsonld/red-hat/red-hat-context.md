---
class_count: 1
classes:
- id
context_file: json-ld/red-hat-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/red-hat/refs/heads/main/json-ld/red-hat-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Red Hat from Red Hat.
layout: jsonld
name: Red Hat Context
namespaces:
- prefix: redhat
  uri: https://developers.redhat.com/schemas/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: rdfs
  uri: http://www.w3.org/2000/01/rdf-schema#
properties:
- container: ''
  name: Cluster
  type: rdfs:Class
- container: ''
  name: Host
  type: rdfs:Class
- container: ''
  name: Advisory
  type: rdfs:Class
- container: ''
  name: JobTemplate
  type: rdfs:Class
- container: ''
  name: Job
  type: rdfs:Class
- container: ''
  name: Inventory
  type: rdfs:Class
- container: ''
  name: Repository
  type: rdfs:Class
- container: ''
  name: ContainerImage
  type: rdfs:Class
- container: ''
  name: Realm
  type: rdfs:Class
- container: ''
  name: ContentView
  type: rdfs:Class
- container: ''
  name: InsightsRule
  type: rdfs:Class
- container: ''
  name: NotificationEvent
  type: rdfs:Class
- container: ''
  name: name
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: displayName
  type: string
- container: ''
  name: url
  type: reference
- container: ''
  name: email
  type: string
- container: ''
  name: version
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: state
  type: string
- container: ''
  name: enabled
  type: boolean
- container: ''
  name: cloudProvider
  type: string
- container: ''
  name: region
  type: string
- container: ''
  name: openshiftVersion
  type: string
- container: ''
  name: multiAz
  type: boolean
- container: ''
  name: nodeCount
  type: integer
- container: ''
  name: hostname
  type: string
- container: ''
  name: ipAddress
  type: string
- container: ''
  name: operatingSystem
  type: string
- container: ''
  name: rhelVersion
  type: string
- container: ''
  name: severity
  type: string
- container: ''
  name: cveId
  type: string
- container: ''
  name: advisoryId
  type: string
- container: ''
  name: advisoryType
  type: string
- container: ''
  name: rebootRequired
  type: boolean
- container: ''
  name: playbook
  type: string
- container: ''
  name: inventory
  type: ''
- container: ''
  name: jobTemplate
  type: ''
- container: ''
  name: elapsed
  type: decimal
- container: ''
  name: namespace
  type: string
- container: ''
  name: manifestDigest
  type: string
- container: ''
  name: isPublic
  type: boolean
- container: ''
  name: tagCount
  type: integer
- container: ''
  name: realm
  type: string
- container: ''
  name: clientId
  type: string
- container: ''
  name: protocol
  type: string
- container: ''
  name: organizationId
  type: string
- container: ''
  name: eventType
  type: string
- container: ''
  name: bundle
  type: string
- container: ''
  name: application
  type: string
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: updatedAt
  type: dateTime
- container: ''
  name: publishedAt
  type: dateTime
- container: ''
  name: lastSeen
  type: dateTime
- container: ''
  name: timestamp
  type: dateTime
property_count: 55
provider_name: Red Hat
provider_slug: red-hat
slug: red-hat-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"redhat\": \"https://developers.redhat.com/schemas/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"rdfs\": \"http://www.w3.org/2000/01/rdf-schema#\",\n\n    \"Cluster\": {\n      \"@id\": \"redhat:Cluster\",\n      \"@type\": \"rdfs:Class\",\n      \"rdfs:subClassOf\": { \"@id\": \"schema:SoftwareApplication\" },\n      \"rdfs:label\": \"Red Hat OpenShift Cluster\",\n      \"rdfs:comment\": \"An OpenShift Kubernetes cluster managed through the Red Hat Cluster Manager.\"\n    },\n    \"Host\": {\n      \"@id\": \"redhat:Host\",\n      \"@type\": \"rdfs:Class\",\n      \"rdfs:subClassOf\": { \"@id\": \"schema:DigitalDocument\" },\n      \"rdfs:label\": \"Red Hat Managed Host\",\n      \"rdfs:comment\": \"A RHEL system registered with Red Hat Satellite or Insights for management and monitoring.\"\n    },\n    \"Advisory\"\
  : {\n      \"@id\": \"redhat:Advisory\",\n      \"@type\": \"rdfs:Class\",\n      \"rdfs:label\": \"Red Hat Advisory\",\n      \"rdfs:comment\": \"An erratum advisory published by Red Hat containing security fixes, bug fixes, or enhancements.\"\n    },\n    \"JobTemplate\": {\n      \"@id\": \"redhat:JobTemplate\",\n      \"@type\": \"rdfs:Class\",\n      \"rdfs:label\": \"Ansible Job Template\",\n      \"rdfs:comment\": \"A parameterized template for running Ansible playbooks against inventories of managed hosts.\"\n    },\n    \"Job\": {\n      \"@id\": \"redhat:Job\",\n      \"@type\": \"rdfs:Class\",\n      \"rdfs:subClassOf\": { \"@id\": \"schema:Action\" },\n      \"rdfs:label\": \"Ansible Job\",\n      \"rdfs:comment\": \"A single execution of an Ansible job template against an inventory of managed hosts.\"\n    },\n    \"Inventory\": {\n      \"@id\": \"redhat:Inventory\",\n      \"@type\": \"rdfs:Class\",\n      \"rdfs:label\": \"Ansible Inventory\",\n      \"rdfs:comment\": \"\
  A collection of hosts and groups that automation jobs target for execution.\"\n    },\n    \"Repository\": {\n      \"@id\": \"redhat:Repository\",\n      \"@type\": \"rdfs:Class\",\n      \"rdfs:label\": \"Quay Repository\",\n      \"rdfs:comment\": \"A container image repository in the Red Hat Quay registry.\"\n    },\n    \"ContainerImage\": {\n      \"@id\": \"redhat:ContainerImage\",\n      \"@type\": \"rdfs:Class\",\n      \"rdfs:subClassOf\": { \"@id\": \"schema:SoftwareApplication\" },\n      \"rdfs:label\": \"Container Image\",\n      \"rdfs:comment\": \"A container image stored in a Quay registry repository.\"\n    },\n    \"Realm\": {\n      \"@id\": \"redhat:Realm\",\n      \"@type\": \"rdfs:Class\",\n      \"rdfs:label\": \"Keycloak Realm\",\n      \"rdfs:comment\": \"A Keycloak realm providing isolated identity and access management configuration.\"\n    },\n    \"ContentView\": {\n      \"@id\": \"redhat:ContentView\",\n      \"@type\": \"rdfs:Class\",\n      \"rdfs:label\"\
  : \"Satellite Content View\",\n      \"rdfs:comment\": \"A curated snapshot of software repositories for controlled content delivery in Red Hat Satellite.\"\n    },\n    \"InsightsRule\": {\n      \"@id\": \"redhat:InsightsRule\",\n      \"@type\": \"rdfs:Class\",\n      \"rdfs:label\": \"Insights Advisor Rule\",\n      \"rdfs:comment\": \"A detection rule in Red Hat Insights that identifies configuration risks, security issues, or performance problems.\"\n    },\n    \"NotificationEvent\": {\n      \"@id\": \"redhat:NotificationEvent\",\n      \"@type\": \"rdfs:Class\",\n      \"rdfs:subClassOf\": { \"@id\": \"schema:Event\" },\n      \"rdfs:label\": \"Hybrid Cloud Console Notification Event\",\n      \"rdfs:comment\": \"An event notification from the Red Hat Hybrid Cloud Console notifications service.\"\n    },\n\n    \"id\": \"@id\",\n\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"displayName\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"url\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    },\n    \"email\": {\n      \"@id\": \"schema:email\",\n      \"@type\": \"xsd:string\"\n    },\n    \"version\": {\n      \"@id\": \"schema:softwareVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"redhat:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"state\": {\n      \"@id\": \"redhat:state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"enabled\": {\n      \"@id\": \"redhat:enabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n\n    \"cloudProvider\": {\n      \"@id\": \"redhat:cloudProvider\",\n      \"@type\": \"xsd:string\"\n    },\n    \"region\": {\n      \"@id\": \"redhat:region\",\n      \"@type\": \"xsd:string\"\n    },\n    \"openshiftVersion\": {\n      \"@id\": \"schema:softwareVersion\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"multiAz\": {\n      \"@id\": \"redhat:multiAz\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"nodeCount\": {\n      \"@id\": \"redhat:nodeCount\",\n      \"@type\": \"xsd:integer\"\n    },\n\n    \"hostname\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ipAddress\": {\n      \"@id\": \"redhat:ipAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"operatingSystem\": {\n      \"@id\": \"schema:operatingSystem\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rhelVersion\": {\n      \"@id\": \"redhat:rhelVersion\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"severity\": {\n      \"@id\": \"redhat:severity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cveId\": {\n      \"@id\": \"redhat:cveId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"advisoryId\": {\n      \"@id\": \"redhat:advisoryId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"advisoryType\": {\n      \"@id\": \"redhat:advisoryType\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"rebootRequired\": {\n      \"@id\": \"redhat:rebootRequired\",\n      \"@type\": \"xsd:boolean\"\n    },\n\n    \"playbook\": {\n      \"@id\": \"redhat:playbook\",\n      \"@type\": \"xsd:string\"\n    },\n    \"inventory\": {\n      \"@id\": \"redhat:inventory\"\n    },\n    \"jobTemplate\": {\n      \"@id\": \"redhat:jobTemplate\"\n    },\n    \"elapsed\": {\n      \"@id\": \"redhat:elapsed\",\n      \"@type\": \"xsd:decimal\"\n    },\n\n    \"namespace\": {\n      \"@id\": \"redhat:namespace\",\n      \"@type\": \"xsd:string\"\n    },\n    \"manifestDigest\": {\n      \"@id\": \"redhat:manifestDigest\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isPublic\": {\n      \"@id\": \"redhat:isPublic\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"tagCount\": {\n      \"@id\": \"redhat:tagCount\",\n      \"@type\": \"xsd:integer\"\n    },\n\n    \"realm\": {\n      \"@id\": \"redhat:realm\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"clientId\": {\n      \"@id\": \"redhat:clientId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"protocol\": {\n      \"@id\": \"redhat:protocol\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"organizationId\": {\n      \"@id\": \"redhat:organizationId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eventType\": {\n      \"@id\": \"redhat:eventType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bundle\": {\n      \"@id\": \"redhat:bundle\",\n      \"@type\": \"xsd:string\"\n    },\n    \"application\": {\n      \"@id\": \"redhat:application\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"createdAt\": {\n      \"@id\": \"dcterms:created\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"dcterms:modified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"publishedAt\": {\n      \"@id\": \"dcterms:issued\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"lastSeen\": {\n      \"@id\": \"redhat:lastSeen\",\n      \"@type\": \"\
  xsd:dateTime\"\n    },\n    \"timestamp\": {\n      \"@id\": \"dcterms:date\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/red-hat/refs/heads/main/json-ld/red-hat-context.jsonld
tags:
- Cloud
- Containers
- Enterprise
- Hybrid Cloud
- Kubernetes
- Linux
- Open Source
- JSON-LD
- Linked Data
- Semantic Web
---
