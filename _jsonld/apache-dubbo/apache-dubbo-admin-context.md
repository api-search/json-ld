---
class_count: 35
classes:
- model.Mock
- version
- model.Consumer
- model.ParamMatch
- model.StringMatch
- version.Version
- model.ConditionRouteDto
- model.ServiceDetailDTO
- model.Retry
- model.ListStringMatch
- model.Accesslog
- model.ClusterMetricsRes
- model.Weight
- model.TagRouteDto
- model.Metadata
- model.Region
- model.RegistrySource
- model.AddressMatch
- time.Duration
- model.Argument
- model.DynamicConfig
- model.ListServiceByPage
- model.OverrideConfig
- model.MockRule
- model.Gray
- model.Tag
- name
- model.ConditionMatch
- model.Timeout
- model.FlowMetricsRes
- model.ServiceDTO
- model.Provider
- url
- model.ListMockRulesByPage
- model.HTTPError
context_file: json-ld/apache-dubbo-admin-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apache-dubbo/refs/heads/main/json-ld/apache-dubbo-admin-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apache Dubbo Admin from Apache Dubbo.
layout: jsonld
name: Apache Dubbo Admin Context
namespaces:
- prefix: dubbo
  uri: https://dubbo.apache.org/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: group
  type: string
- container: ''
  name: mock
  type: string
- container: ''
  name: service
  type: string
- container: ''
  name: address
  type: string
- container: ''
  name: alived
  type: integer
- container: ''
  name: application
  type: string
- container: ''
  name: collected
  type: string
- container: ''
  name: created
  type: string
- container: ''
  name: expired
  type: string
- container: ''
  name: hash
  type: string
- container: ''
  name: id
  type: integer
- container: set
  name: ids
  type: integer
- container: ''
  name: miss
  type: boolean
- container: ''
  name: modified
  type: string
- container: ''
  name: now
  type: string
- container: ''
  name: operator
  type: string
- container: ''
  name: operatorAddress
  type: string
- container: ''
  name: parameters
  type: string
- container: ''
  name: registry
  type: string
- container: ''
  name: result
  type: string
- container: ''
  name: statistics
  type: string
- container: ''
  name: username
  type: string
- container: ''
  name: key
  type: string
- container: ''
  name: value
  type: string
- container: ''
  name: empty
  type: string
- container: ''
  name: exact
  type: string
- container: ''
  name: noempty
  type: string
- container: ''
  name: prefix
  type: string
- container: ''
  name: regex
  type: string
- container: ''
  name: wildcard
  type: string
- container: ''
  name: buildDate
  type: string
- container: ''
  name: compiler
  type: string
- container: ''
  name: gitCommit
  type: string
- container: ''
  name: gitTreeState
  type: string
- container: ''
  name: gitVersion
  type: string
- container: ''
  name: goVersion
  type: string
- container: ''
  name: platform
  type: string
- container: set
  name: conditions
  type: string
- container: ''
  name: configVersion
  type: string
- container: ''
  name: enabled
  type: boolean
- container: ''
  name: force
  type: boolean
- container: ''
  name: priority
  type: integer
- container: ''
  name: runtime
  type: boolean
- container: ''
  name: serviceGroup
  type: string
- container: ''
  name: serviceVersion
  type: string
- container: set
  name: consumers
  type: string
- container: ''
  name: metadata
  type: string
- container: set
  name: providers
  type: string
- container: ''
  name: retry
  type: integer
- container: set
  name: oneof
  type: string
- container: ''
  name: accesslog
  type: string
- container: ''
  name: data
  type: reference
- container: ''
  name: match
  type: string
- container: ''
  name: weight
  type: integer
- container: set
  name: tags
  type: string
- container: ''
  name: configCenter
  type: string
- container: ''
  name: metadataCenter
  type: string
- container: set
  name: protocols
  type: string
- container: set
  name: rules
  type: string
- container: set
  name: versions
  type: string
- container: ''
  name: rule
  type: string
- container: ''
  name: cird
  type: string
- container: set
  name: configs
  type: string
- container: set
  name: content
  type: string
- container: ''
  name: first
  type: boolean
- container: ''
  name: last
  type: boolean
- container: ''
  name: offset
  type: integer
- container: ''
  name: pageNumber
  type: string
- container: ''
  name: size
  type: string
- container: ''
  name: totalElements
  type: integer
- container: ''
  name: totalPages
  type: integer
- container: set
  name: addresses
  type: string
- container: set
  name: applications
  type: string
- container: set
  name: providerAddresses
  type: string
- container: set
  name: services
  type: string
- container: ''
  name: side
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: enable
  type: boolean
- container: ''
  name: methodName
  type: string
- container: ''
  name: serviceName
  type: string
- container: set
  name: param
  type: string
- container: ''
  name: timeout
  type: integer
- container: ''
  name: appName
  type: string
- container: ''
  name: registrySource
  type: string
- container: ''
  name: dynamic
  type: boolean
- container: ''
  name: serialization
  type: string
- container: ''
  name: total
  type: integer
- container: ''
  name: error
  type: string
property_count: 88
provider_name: Apache Dubbo
provider_slug: apache-dubbo
slug: apache-dubbo-admin-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"dubbo\": \"https://dubbo.apache.org/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"model.Mock\": \"dubbo:model.Mock\",\n    \"group\": {\n      \"@id\": \"dubbo:group\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mock\": {\n      \"@id\": \"dubbo:mock\",\n      \"@type\": \"xsd:string\"\n    },\n    \"service\": {\n      \"@id\": \"dubbo:service\",\n      \"@type\": \"xsd:string\"\n    },\n    \"version\": \"schema:version\",\n    \"model.Consumer\": \"dubbo:model.Consumer\",\n    \"address\": {\n      \"@id\": \"dubbo:address\",\n      \"@type\": \"xsd:string\"\n    },\n    \"alived\": {\n      \"@id\": \"dubbo:alived\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"application\": {\n      \"@id\": \"dubbo:application\",\n      \"@type\": \"xsd:string\"\n    },\n    \"collected\": {\n      \"@id\": \"\
  dubbo:collected\",\n      \"@type\": \"xsd:string\"\n    },\n    \"created\": {\n      \"@id\": \"dubbo:created\",\n      \"@type\": \"xsd:string\"\n    },\n    \"expired\": {\n      \"@id\": \"dubbo:expired\",\n      \"@type\": \"xsd:string\"\n    },\n    \"hash\": {\n      \"@id\": \"dubbo:hash\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"dubbo:id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"ids\": {\n      \"@id\": \"dubbo:ids\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"miss\": {\n      \"@id\": \"dubbo:miss\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"modified\": {\n      \"@id\": \"dubbo:modified\",\n      \"@type\": \"xsd:string\"\n    },\n    \"now\": {\n      \"@id\": \"dubbo:now\",\n      \"@type\": \"xsd:string\"\n    },\n    \"operator\": {\n      \"@id\": \"dubbo:operator\",\n      \"@type\": \"xsd:string\"\n    },\n    \"operatorAddress\": {\n      \"@id\": \"dubbo:operatorAddress\",\n \
  \     \"@type\": \"xsd:string\"\n    },\n    \"parameters\": {\n      \"@id\": \"dubbo:parameters\",\n      \"@type\": \"xsd:string\"\n    },\n    \"registry\": {\n      \"@id\": \"dubbo:registry\",\n      \"@type\": \"xsd:string\"\n    },\n    \"result\": {\n      \"@id\": \"dubbo:result\",\n      \"@type\": \"xsd:string\"\n    },\n    \"statistics\": {\n      \"@id\": \"dubbo:statistics\",\n      \"@type\": \"xsd:string\"\n    },\n    \"username\": {\n      \"@id\": \"dubbo:username\",\n      \"@type\": \"xsd:string\"\n    },\n    \"model.ParamMatch\": \"dubbo:model.ParamMatch\",\n    \"key\": {\n      \"@id\": \"dubbo:key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"dubbo:value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"model.StringMatch\": \"dubbo:model.StringMatch\",\n    \"empty\": {\n      \"@id\": \"dubbo:empty\",\n      \"@type\": \"xsd:string\"\n    },\n    \"exact\": {\n      \"@id\": \"dubbo:exact\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"noempty\": {\n      \"@id\": \"dubbo:noempty\",\n      \"@type\": \"xsd:string\"\n    },\n    \"prefix\": {\n      \"@id\": \"dubbo:prefix\",\n      \"@type\": \"xsd:string\"\n    },\n    \"regex\": {\n      \"@id\": \"dubbo:regex\",\n      \"@type\": \"xsd:string\"\n    },\n    \"wildcard\": {\n      \"@id\": \"dubbo:wildcard\",\n      \"@type\": \"xsd:string\"\n    },\n    \"version.Version\": \"dubbo:version.Version\",\n    \"buildDate\": {\n      \"@id\": \"dubbo:buildDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"compiler\": {\n      \"@id\": \"dubbo:compiler\",\n      \"@type\": \"xsd:string\"\n    },\n    \"gitCommit\": {\n      \"@id\": \"dubbo:gitCommit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"gitTreeState\": {\n      \"@id\": \"dubbo:gitTreeState\",\n      \"@type\": \"xsd:string\"\n    },\n    \"gitVersion\": {\n      \"@id\": \"dubbo:gitVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"goVersion\": {\n      \"@id\": \"dubbo:goVersion\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"platform\": {\n      \"@id\": \"dubbo:platform\",\n      \"@type\": \"xsd:string\"\n    },\n    \"model.ConditionRouteDto\": \"dubbo:model.ConditionRouteDto\",\n    \"conditions\": {\n      \"@id\": \"dubbo:conditions\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"configVersion\": {\n      \"@id\": \"dubbo:configVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"enabled\": {\n      \"@id\": \"dubbo:enabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"force\": {\n      \"@id\": \"dubbo:force\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"priority\": {\n      \"@id\": \"dubbo:priority\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"runtime\": {\n      \"@id\": \"dubbo:runtime\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"serviceGroup\": {\n      \"@id\": \"dubbo:serviceGroup\",\n      \"@type\": \"xsd:string\"\n    },\n    \"serviceVersion\": {\n      \"@id\": \"dubbo:serviceVersion\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"model.ServiceDetailDTO\": \"dubbo:model.ServiceDetailDTO\",\n    \"consumers\": {\n      \"@id\": \"dubbo:consumers\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"metadata\": {\n      \"@id\": \"dubbo:metadata\",\n      \"@type\": \"xsd:string\"\n    },\n    \"providers\": {\n      \"@id\": \"dubbo:providers\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"model.Retry\": \"dubbo:model.Retry\",\n    \"retry\": {\n      \"@id\": \"dubbo:retry\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"model.ListStringMatch\": \"dubbo:model.ListStringMatch\",\n    \"oneof\": {\n      \"@id\": \"dubbo:oneof\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"model.Accesslog\": \"dubbo:model.Accesslog\",\n    \"accesslog\": {\n      \"@id\": \"dubbo:accesslog\",\n      \"@type\": \"xsd:string\"\n    },\n    \"model.ClusterMetricsRes\": \"dubbo:model.ClusterMetricsRes\"\
  ,\n    \"data\": {\n      \"@id\": \"dubbo:data\",\n      \"@type\": \"@id\"\n    },\n    \"model.Weight\": \"dubbo:model.Weight\",\n    \"match\": {\n      \"@id\": \"dubbo:match\",\n      \"@type\": \"xsd:string\"\n    },\n    \"weight\": {\n      \"@id\": \"dubbo:weight\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"model.TagRouteDto\": \"dubbo:model.TagRouteDto\",\n    \"tags\": {\n      \"@id\": \"dubbo:tags\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"model.Metadata\": \"dubbo:model.Metadata\",\n    \"configCenter\": {\n      \"@id\": \"dubbo:configCenter\",\n      \"@type\": \"xsd:string\"\n    },\n    \"metadataCenter\": {\n      \"@id\": \"dubbo:metadataCenter\",\n      \"@type\": \"xsd:string\"\n    },\n    \"protocols\": {\n      \"@id\": \"dubbo:protocols\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rules\": {\n      \"@id\": \"dubbo:rules\",\n      \"@container\": \"@set\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"versions\": {\n      \"@id\": \"dubbo:versions\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"model.Region\": \"dubbo:model.Region\",\n    \"rule\": {\n      \"@id\": \"dubbo:rule\",\n      \"@type\": \"xsd:string\"\n    },\n    \"model.RegistrySource\": \"dubbo:model.RegistrySource\",\n    \"model.AddressMatch\": \"dubbo:model.AddressMatch\",\n    \"cird\": {\n      \"@id\": \"dubbo:cird\",\n      \"@type\": \"xsd:string\"\n    },\n    \"time.Duration\": \"dubbo:time.Duration\",\n    \"model.Argument\": \"dubbo:model.Argument\",\n    \"model.DynamicConfig\": \"dubbo:model.DynamicConfig\",\n    \"configs\": {\n      \"@id\": \"dubbo:configs\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"model.ListServiceByPage\": \"dubbo:model.ListServiceByPage\",\n    \"content\": {\n      \"@id\": \"dubbo:content\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"\
  first\": {\n      \"@id\": \"dubbo:first\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"last\": {\n      \"@id\": \"dubbo:last\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"offset\": {\n      \"@id\": \"dubbo:offset\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"pageNumber\": {\n      \"@id\": \"dubbo:pageNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"size\": {\n      \"@id\": \"dubbo:size\",\n      \"@type\": \"xsd:string\"\n    },\n    \"totalElements\": {\n      \"@id\": \"dubbo:totalElements\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"totalPages\": {\n      \"@id\": \"dubbo:totalPages\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"model.OverrideConfig\": \"dubbo:model.OverrideConfig\",\n    \"addresses\": {\n      \"@id\": \"dubbo:addresses\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"applications\": {\n      \"@id\": \"dubbo:applications\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"providerAddresses\": {\n      \"@id\": \"dubbo:providerAddresses\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"services\": {\n      \"@id\": \"dubbo:services\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"side\": {\n      \"@id\": \"dubbo:side\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"dubbo:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"model.MockRule\": \"dubbo:model.MockRule\",\n    \"enable\": {\n      \"@id\": \"dubbo:enable\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"methodName\": {\n      \"@id\": \"dubbo:methodName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"serviceName\": {\n      \"@id\": \"dubbo:serviceName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"model.Gray\": \"dubbo:model.Gray\",\n    \"model.Tag\": \"dubbo:model.Tag\",\n    \"name\": \"schema:name\",\n    \"model.ConditionMatch\": \"dubbo:model.ConditionMatch\",\n\
  \    \"param\": {\n      \"@id\": \"dubbo:param\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"model.Timeout\": \"dubbo:model.Timeout\",\n    \"timeout\": {\n      \"@id\": \"dubbo:timeout\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"model.FlowMetricsRes\": \"dubbo:model.FlowMetricsRes\",\n    \"model.ServiceDTO\": \"dubbo:model.ServiceDTO\",\n    \"appName\": {\n      \"@id\": \"dubbo:appName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"registrySource\": {\n      \"@id\": \"dubbo:registrySource\",\n      \"@type\": \"xsd:string\"\n    },\n    \"model.Provider\": \"dubbo:model.Provider\",\n    \"dynamic\": {\n      \"@id\": \"dubbo:dynamic\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"serialization\": {\n      \"@id\": \"dubbo:serialization\",\n      \"@type\": \"xsd:string\"\n    },\n    \"url\": \"schema:url\",\n    \"model.ListMockRulesByPage\": \"dubbo:model.ListMockRulesByPage\",\n    \"total\": {\n      \"@id\": \"dubbo:total\"\
  ,\n      \"@type\": \"xsd:integer\"\n    },\n    \"model.HTTPError\": \"dubbo:model.HTTPError\",\n    \"error\": {\n      \"@id\": \"dubbo:error\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/apache-dubbo/refs/heads/main/json-ld/apache-dubbo-admin-context.jsonld
tags:
- Apache
- Go
- Java
- Microservices
- Open Source
- RPC
- Service Discovery
- Service Mesh
- JSON-LD
- Linked Data
- Semantic Web
---
