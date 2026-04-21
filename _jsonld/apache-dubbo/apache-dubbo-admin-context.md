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
