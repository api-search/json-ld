---
class_count: 28
classes:
- ServiceInterface
- ServiceContract
- ServiceRegistry
- ServiceProvider
- ServiceConsumer
- EnterpriseServiceBus
- ServiceOrchestration
- ServiceChoreography
- SoapMessage
- WsdlDefinition
- ServiceOperation
- ServicePolicy
- ServiceSLA
- name
- description
- version
- status
- endpoint
- team
- domain
- email
- availability
- responseTime
- registeredAt
- updatedAt
- interfaceType
- inputSchema
- outputSchema
context_file: json-ld/soa-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/soa/refs/heads/main/json-ld/soa-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Soa from SOA.
layout: jsonld
name: Soa Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: soa
  uri: https://www.oasis-open.org/committees/soa-rm/
- prefix: wsdl
  uri: https://www.w3.org/TR/wsdl20#
- prefix: soap
  uri: https://www.w3.org/TR/soap12/
- prefix: owl
  uri: http://www.w3.org/2002/07/owl#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: Service
  type: reference
- container: ''
  name: wsdlUrl
  type: reference
- container: ''
  name: owner
  type: reference
- container: list
  name: dependencies
  type: reference
- container: list
  name: tags
  type: ''
- container: list
  name: operations
  type: ''
property_count: 6
provider_name: SOA
provider_slug: soa
slug: soa-context
source_filename: soa-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"soa\": \"https://www.oasis-open.org/committees/soa-rm/\",\n    \"wsdl\": \"https://www.w3.org/TR/wsdl20#\",\n    \"soap\": \"https://www.w3.org/TR/soap12/\",\n    \"owl\": \"http://www.w3.org/2002/07/owl#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Service\": {\n      \"@id\": \"schema:Service\",\n      \"@type\": \"@id\"\n    },\n    \"ServiceInterface\": \"soa:ServiceInterface\",\n    \"ServiceContract\": \"soa:ServiceContract\",\n    \"ServiceRegistry\": \"soa:ServiceRegistry\",\n    \"ServiceProvider\": \"soa:ServiceProvider\",\n    \"ServiceConsumer\": \"soa:ServiceConsumer\",\n    \"EnterpriseServiceBus\": \"soa:EnterpriseServiceBus\",\n    \"ServiceOrchestration\": \"soa:ServiceOrchestration\",\n    \"ServiceChoreography\": \"soa:ServiceChoreography\",\n    \"SoapMessage\": \"soap:Envelope\",\n    \"WsdlDefinition\": \"wsdl:Description\",\n    \"ServiceOperation\"\
  : \"soa:Operation\",\n    \"ServicePolicy\": \"soa:Policy\",\n    \"ServiceSLA\": \"soa:ServiceLevelAgreement\",\n\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"version\": \"schema:version\",\n    \"status\": \"schema:status\",\n    \"endpoint\": \"schema:url\",\n    \"wsdlUrl\": {\n      \"@id\": \"wsdl:interface\",\n      \"@type\": \"@id\"\n    },\n    \"owner\": {\n      \"@id\": \"schema:provider\",\n      \"@type\": \"@id\"\n    },\n    \"team\": \"schema:department\",\n    \"domain\": \"schema:category\",\n    \"email\": \"schema:email\",\n    \"availability\": \"schema:availableAtOrFrom\",\n    \"responseTime\": \"schema:processingTime\",\n    \"dependencies\": {\n      \"@id\": \"soa:dependsOn\",\n      \"@type\": \"@id\",\n      \"@container\": \"@list\"\n    },\n    \"registeredAt\": \"schema:dateCreated\",\n    \"updatedAt\": \"schema:dateModified\",\n    \"tags\": {\n      \"@id\": \"schema:keywords\",\n      \"@container\": \"@list\"\
  \n    },\n    \"interfaceType\": \"soa:interfaceType\",\n    \"operations\": {\n      \"@id\": \"soa:hasOperation\",\n      \"@container\": \"@list\"\n    },\n    \"inputSchema\": \"soa:inputSchema\",\n    \"outputSchema\": \"soa:outputSchema\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/soa/refs/heads/main/json-ld/soa-context.jsonld
tags:
- SOA
- Service-Oriented Architecture
- Enterprise Integration
- Web Services
- SOAP
- ESB
- Microservices
- API Design
- JSON-LD
- Linked Data
- Semantic Web
---
