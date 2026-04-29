---
class_count: 12
classes:
- CIScan
- ComplianceIssue
- CompliancePolicy
- Container
- Defender
- DefenderSummary
- Host
- Image
- RegistryConfig
- RuntimePolicy
- Vulnerability
- VulnerabilityPolicy
context_file: json-ld/palo-alto-prisma-cloud-compute-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/json-ld/palo-alto-prisma-cloud-compute-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Palo Alto Prisma Cloud Compute Api from Palo Alto Networks.
layout: jsonld
name: Palo Alto Prisma Cloud Compute Api Context
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
  name: Id
  type: string
- container: ''
  name: accountId
  type: string
- container: ''
  name: appEmbedded
  type: integer
- container: set
  name: blacklist
  type: string
- container: ''
  name: block
  type: boolean
- container: ''
  name: byType
  type: reference
- container: ''
  name: cap
  type: integer
- container: ''
  name: category
  type: string
- container: ''
  name: cause
  type: string
- container: set
  name: checks
  type: reference
- container: ''
  name: cloudMetadata
  type: reference
- container: ''
  name: cluster
  type: string
- container: set
  name: clusters
  type: string
- container: set
  name: collections
  type: string
- container: set
  name: complianceIssues
  type: reference
- container: ''
  name: complianceIssuesCount
  type: integer
- container: ''
  name: condition
  type: reference
- container: ''
  name: connected
  type: boolean
- container: ''
  name: count
  type: integer
- container: ''
  name: created
  type: dateTime
- container: ''
  name: credentialID
  type: string
- container: ''
  name: cri
  type: integer
- container: ''
  name: critical
  type: integer
- container: ''
  name: cves
  type: reference
- container: ''
  name: cvss
  type: float
- container: ''
  name: description
  type: string
- container: ''
  name: disconnected
  type: integer
- container: ''
  name: docker
  type: integer
- container: ''
  name: dockerWindows
  type: integer
- container: ''
  name: effect
  type: string
- container: ''
  name: entityInfo
  type: reference
- container: ''
  name: fargate
  type: integer
- container: ''
  name: filesystem
  type: reference
- container: ''
  name: fixedVersion
  type: string
- container: ''
  name: high
  type: integer
- container: ''
  name: hostname
  type: string
- container: ''
  name: id
  type: integer
- container: set
  name: ids
  type: string
- container: ''
  name: imageId
  type: string
- container: ''
  name: imageName
  type: string
- container: ''
  name: instanceId
  type: string
- container: ''
  name: kernelVersion
  type: string
- container: ''
  name: lastModified
  type: dateTime
- container: ''
  name: link
  type: string
- container: ''
  name: low
  type: integer
- container: ''
  name: medium
  type: integer
- container: ''
  name: name
  type: string
- container: ''
  name: namespace
  type: string
- container: ''
  name: network
  type: reference
- container: ''
  name: os
  type: string
- container: ''
  name: osDistro
  type: string
- container: ''
  name: osDistroVersion
  type: string
- container: ''
  name: packageName
  type: string
- container: ''
  name: packageVersion
  type: string
- container: ''
  name: pass
  type: boolean
- container: ''
  name: processes
  type: reference
- container: ''
  name: provider
  type: string
- container: ''
  name: publishedDate
  type: dateTime
- container: ''
  name: region
  type: string
- container: ''
  name: registry
  type: string
- container: ''
  name: repo
  type: string
- container: set
  name: repoDigests
  type: string
- container: ''
  name: repoTag
  type: reference
- container: set
  name: rules
  type: reference
- container: ''
  name: scanTime
  type: dateTime
- container: ''
  name: scanners
  type: integer
- container: ''
  name: serverless
  type: integer
- container: set
  name: severities
  type: string
- container: ''
  name: severity
  type: string
- container: ''
  name: state
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: tag
  type: string
- container: ''
  name: title
  type: string
- container: ''
  name: total
  type: integer
- container: ''
  name: type
  type: string
- container: ''
  name: version
  type: string
- container: set
  name: versionDistribution
  type: reference
- container: set
  name: vulnerabilities
  type: reference
- container: ''
  name: vulnerabilitiesCount
  type: integer
- container: ''
  name: vulnerabilityDistribution
  type: reference
- container: set
  name: whitelist
  type: string
property_count: 81
provider_name: Palo Alto Networks
provider_slug: palo-alto-networks
slug: palo-alto-prisma-cloud-compute-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"pan\": \"https://pan.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"CIScan\": \"pan:CIScan\",\n    \"ComplianceIssue\": \"pan:ComplianceIssue\",\n    \"CompliancePolicy\": \"pan:CompliancePolicy\",\n    \"Container\": \"pan:Container\",\n    \"Defender\": \"pan:Defender\",\n    \"DefenderSummary\": \"pan:DefenderSummary\",\n    \"Host\": \"pan:Host\",\n    \"Image\": \"pan:Image\",\n    \"RegistryConfig\": \"pan:RegistryConfig\",\n    \"RuntimePolicy\": \"pan:RuntimePolicy\",\n    \"Vulnerability\": \"pan:Vulnerability\",\n    \"VulnerabilityPolicy\": \"pan:VulnerabilityPolicy\",\n    \"Id\": {\n      \"@id\": \"pan:_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accountId\": {\n      \"@id\": \"pan:accountId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"appEmbedded\": {\n      \"@id\": \"pan:appEmbedded\"\
  ,\n      \"@type\": \"xsd:integer\"\n    },\n    \"blacklist\": {\n      \"@id\": \"pan:blacklist\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"block\": {\n      \"@id\": \"pan:block\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"byType\": {\n      \"@id\": \"pan:by_type\",\n      \"@type\": \"@id\"\n    },\n    \"cap\": {\n      \"@id\": \"pan:cap\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"category\": {\n      \"@id\": \"pan:category\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cause\": {\n      \"@id\": \"pan:cause\",\n      \"@type\": \"xsd:string\"\n    },\n    \"checks\": {\n      \"@id\": \"pan:checks\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"cloudMetadata\": {\n      \"@id\": \"pan:cloudMetadata\",\n      \"@type\": \"@id\"\n    },\n    \"cluster\": {\n      \"@id\": \"pan:cluster\",\n      \"@type\": \"xsd:string\"\n    },\n    \"clusters\": {\n      \"@id\": \"pan:clusters\",\n      \"\
  @container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"collections\": {\n      \"@id\": \"pan:collections\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"complianceIssues\": {\n      \"@id\": \"pan:complianceIssues\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"complianceIssuesCount\": {\n      \"@id\": \"pan:complianceIssuesCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"condition\": {\n      \"@id\": \"pan:condition\",\n      \"@type\": \"@id\"\n    },\n    \"connected\": {\n      \"@id\": \"pan:connected\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"count\": {\n      \"@id\": \"pan:count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"created\": {\n      \"@id\": \"pan:created\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"credentialID\": {\n      \"@id\": \"pan:credentialID\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cri\": {\n      \"@id\": \"pan:cri\",\n      \"@type\"\
  : \"xsd:integer\"\n    },\n    \"critical\": {\n      \"@id\": \"pan:critical\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"cves\": {\n      \"@id\": \"pan:cves\",\n      \"@type\": \"@id\"\n    },\n    \"cvss\": {\n      \"@id\": \"pan:cvss\",\n      \"@type\": \"xsd:float\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"disconnected\": {\n      \"@id\": \"pan:disconnected\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"docker\": {\n      \"@id\": \"pan:docker\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"dockerWindows\": {\n      \"@id\": \"pan:dockerWindows\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"effect\": {\n      \"@id\": \"pan:effect\",\n      \"@type\": \"xsd:string\"\n    },\n    \"entityInfo\": {\n      \"@id\": \"pan:entityInfo\",\n      \"@type\": \"@id\"\n    },\n    \"fargate\": {\n      \"@id\": \"pan:fargate\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"filesystem\"\
  : {\n      \"@id\": \"pan:filesystem\",\n      \"@type\": \"@id\"\n    },\n    \"fixedVersion\": {\n      \"@id\": \"pan:fixedVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"high\": {\n      \"@id\": \"pan:high\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"hostname\": {\n      \"@id\": \"pan:hostname\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"pan:id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"ids\": {\n      \"@id\": \"pan:ids\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"imageId\": {\n      \"@id\": \"pan:imageId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"imageName\": {\n      \"@id\": \"pan:imageName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"instanceId\": {\n      \"@id\": \"pan:instanceId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"kernelVersion\": {\n      \"@id\": \"pan:kernelVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastModified\": {\n      \"\
  @id\": \"pan:lastModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"link\": {\n      \"@id\": \"pan:link\",\n      \"@type\": \"xsd:string\"\n    },\n    \"low\": {\n      \"@id\": \"pan:low\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"medium\": {\n      \"@id\": \"pan:medium\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"namespace\": {\n      \"@id\": \"pan:namespace\",\n      \"@type\": \"xsd:string\"\n    },\n    \"network\": {\n      \"@id\": \"pan:network\",\n      \"@type\": \"@id\"\n    },\n    \"os\": {\n      \"@id\": \"pan:os\",\n      \"@type\": \"xsd:string\"\n    },\n    \"osDistro\": {\n      \"@id\": \"pan:osDistro\",\n      \"@type\": \"xsd:string\"\n    },\n    \"osDistroVersion\": {\n      \"@id\": \"pan:osDistroVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"packageName\": {\n      \"@id\": \"pan:packageName\",\n      \"@type\": \"xsd:string\"\n\
  \    },\n    \"packageVersion\": {\n      \"@id\": \"pan:packageVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pass\": {\n      \"@id\": \"pan:pass\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"processes\": {\n      \"@id\": \"pan:processes\",\n      \"@type\": \"@id\"\n    },\n    \"provider\": {\n      \"@id\": \"pan:provider\",\n      \"@type\": \"xsd:string\"\n    },\n    \"publishedDate\": {\n      \"@id\": \"pan:publishedDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"region\": {\n      \"@id\": \"pan:region\",\n      \"@type\": \"xsd:string\"\n    },\n    \"registry\": {\n      \"@id\": \"pan:registry\",\n      \"@type\": \"xsd:string\"\n    },\n    \"repo\": {\n      \"@id\": \"pan:repo\",\n      \"@type\": \"xsd:string\"\n    },\n    \"repoDigests\": {\n      \"@id\": \"pan:repoDigests\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"repoTag\": {\n      \"@id\": \"pan:repoTag\",\n      \"@type\": \"@id\"\n    },\n\
  \    \"rules\": {\n      \"@id\": \"pan:rules\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"scanTime\": {\n      \"@id\": \"pan:scanTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"scanners\": {\n      \"@id\": \"pan:scanners\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"serverless\": {\n      \"@id\": \"pan:serverless\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"severities\": {\n      \"@id\": \"pan:severities\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"severity\": {\n      \"@id\": \"pan:severity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"state\": {\n      \"@id\": \"pan:state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"pan:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tag\": {\n      \"@id\": \"pan:tag\",\n      \"@type\": \"xsd:string\"\n    },\n    \"title\": {\n      \"@id\": \"pan:title\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"total\": {\n      \"@id\": \"pan:total\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"type\": {\n      \"@id\": \"pan:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"version\": {\n      \"@id\": \"schema:version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"versionDistribution\": {\n      \"@id\": \"pan:version_distribution\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"vulnerabilities\": {\n      \"@id\": \"pan:vulnerabilities\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"vulnerabilitiesCount\": {\n      \"@id\": \"pan:vulnerabilitiesCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"vulnerabilityDistribution\": {\n      \"@id\": \"pan:vulnerabilityDistribution\",\n      \"@type\": \"@id\"\n    },\n    \"whitelist\": {\n      \"@id\": \"pan:whitelist\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/json-ld/palo-alto-prisma-cloud-compute-api-context.jsonld
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
