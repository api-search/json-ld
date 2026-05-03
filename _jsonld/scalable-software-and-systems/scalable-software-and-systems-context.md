---
api_specs:
- filename: openapi.yml
  format: yaml
  label: Temporal API
  slug: temporal
  spec_type: OpenAPI
  url: https://github.com/temporalio/api/blob/master/openapi/openapi.yml
class_count: 35
classes:
- DistributedSystem
- SoftwareArchitecture
- ArchitecturePattern
- DomainModel
- BoundedContext
- EventSourcingAggregate
- WorkflowOrchestration
- BuildingBlock
- name
- description
- url
- documentation
- version
- license
- provider
- dateCreated
- dateModified
- SoftwareApplication
- SoftwareSourceCode
- WebAPI
- baseUrl
- apiType
- authType
- tags
- pattern
- consistencyModel
- messageFormat
- brokerType
- workflowEngine
- activityRetry
- compensatingTransaction
- observabilityPillars
- deploymentModel
- gitopsEnabled
- infrastructureAsCode
context_file: json-ld/scalable-software-and-systems-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/scalable-software-and-systems/refs/heads/main/json-ld/scalable-software-and-systems-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Scalable Software And Systems from Scalable Software and Systems.
layout: jsonld
name: Scalable Software And Systems Context
namespaces:
- prefix: api
  uri: https://api-evangelist.com/vocabulary/
- prefix: sas
  uri: https://api-evangelist.com/vocabulary/scalable-software-and-systems/
properties: []
property_count: 0
provider_name: Scalable Software and Systems
provider_slug: scalable-software-and-systems
slug: scalable-software-and-systems-context
source_filename: scalable-software-and-systems-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"@vocab\": \"https://schema.org/\",\n    \"api\": \"https://api-evangelist.com/vocabulary/\",\n    \"sas\": \"https://api-evangelist.com/vocabulary/scalable-software-and-systems/\",\n\n    \"DistributedSystem\": \"sas:DistributedSystem\",\n    \"SoftwareArchitecture\": \"sas:SoftwareArchitecture\",\n    \"ArchitecturePattern\": \"sas:ArchitecturePattern\",\n    \"DomainModel\": \"sas:DomainModel\",\n    \"BoundedContext\": \"sas:BoundedContext\",\n    \"EventSourcingAggregate\": \"sas:EventSourcingAggregate\",\n    \"WorkflowOrchestration\": \"sas:WorkflowOrchestration\",\n    \"BuildingBlock\": \"sas:BuildingBlock\",\n\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"documentation\": \"schema:documentation\",\n    \"version\": \"schema:version\",\n    \"license\": \"schema:license\",\n    \"provider\": \"schema:provider\",\n    \"dateCreated\": \"schema:dateCreated\"\
  ,\n    \"dateModified\": \"schema:dateModified\",\n\n    \"SoftwareApplication\": \"schema:SoftwareApplication\",\n    \"SoftwareSourceCode\": \"schema:SoftwareSourceCode\",\n    \"WebAPI\": \"schema:WebAPI\",\n\n    \"baseUrl\": \"api:baseUrl\",\n    \"apiType\": \"api:apiType\",\n    \"authType\": \"api:authType\",\n    \"tags\": \"api:tags\",\n\n    \"pattern\": \"sas:pattern\",\n    \"consistencyModel\": \"sas:consistencyModel\",\n    \"messageFormat\": \"sas:messageFormat\",\n    \"brokerType\": \"sas:brokerType\",\n    \"workflowEngine\": \"sas:workflowEngine\",\n    \"activityRetry\": \"sas:activityRetry\",\n    \"compensatingTransaction\": \"sas:compensatingTransaction\",\n    \"observabilityPillars\": \"sas:observabilityPillars\",\n    \"deploymentModel\": \"sas:deploymentModel\",\n    \"gitopsEnabled\": \"sas:gitopsEnabled\",\n    \"infrastructureAsCode\": \"sas:infrastructureAsCode\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/scalable-software-and-systems/refs/heads/main/json-ld/scalable-software-and-systems-context.jsonld
tags:
- API First
- Architecture Patterns
- CQRS
- Distributed Systems
- Enterprise
- Event Driven
- Microservices
- Scalable Architecture
- Software Engineering
- Systems Design
- JSON-LD
- Linked Data
- Semantic Web
---
