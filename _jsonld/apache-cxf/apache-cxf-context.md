---
class_count: 3
classes:
- JaxRsEndpoint
- JaxWsEndpoint
- WsSecurityConfig
context_file: json-ld/apache-cxf-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apache-cxf/refs/heads/main/json-ld/apache-cxf-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apache Cxf from Apache CXF.
layout: jsonld
name: Apache Cxf Context
namespaces:
- prefix: cxf
  uri: https://cxf.apache.org/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: action
  type: string
- container: ''
  name: address
  type: string
- container: ''
  name: encryptionPropFile
  type: string
- container: ''
  name: encryptionUser
  type: string
- container: ''
  name: endpointName
  type: string
- container: set
  name: features
  type: string
- container: ''
  name: implementor
  type: string
- container: set
  name: inInterceptors
  type: string
- container: set
  name: outInterceptors
  type: string
- container: ''
  name: passwordCallbackClass
  type: string
- container: ''
  name: passwordType
  type: string
- container: ''
  name: properties
  type: reference
- container: set
  name: providers
  type: string
- container: ''
  name: serviceClass
  type: string
- container: ''
  name: serviceName
  type: string
- container: ''
  name: signatureKeyIdentifier
  type: string
- container: ''
  name: signaturePropFile
  type: string
- container: ''
  name: user
  type: string
- container: ''
  name: wsdlLocation
  type: string
property_count: 19
provider_name: Apache CXF
provider_slug: apache-cxf
slug: apache-cxf-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"cxf\": \"https://cxf.apache.org/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"JaxRsEndpoint\": \"cxf:JaxRsEndpoint\",\n    \"JaxWsEndpoint\": \"cxf:JaxWsEndpoint\",\n    \"WsSecurityConfig\": \"cxf:WsSecurityConfig\",\n    \"action\": {\n      \"@id\": \"cxf:action\",\n      \"@type\": \"xsd:string\"\n    },\n    \"address\": {\n      \"@id\": \"cxf:address\",\n      \"@type\": \"xsd:string\"\n    },\n    \"encryptionPropFile\": {\n      \"@id\": \"cxf:encryptionPropFile\",\n      \"@type\": \"xsd:string\"\n    },\n    \"encryptionUser\": {\n      \"@id\": \"cxf:encryptionUser\",\n      \"@type\": \"xsd:string\"\n    },\n    \"endpointName\": {\n      \"@id\": \"cxf:endpointName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"features\": {\n      \"@id\": \"cxf:features\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"\
  implementor\": {\n      \"@id\": \"cxf:implementor\",\n      \"@type\": \"xsd:string\"\n    },\n    \"inInterceptors\": {\n      \"@id\": \"cxf:inInterceptors\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"outInterceptors\": {\n      \"@id\": \"cxf:outInterceptors\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"passwordCallbackClass\": {\n      \"@id\": \"cxf:passwordCallbackClass\",\n      \"@type\": \"xsd:string\"\n    },\n    \"passwordType\": {\n      \"@id\": \"cxf:passwordType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"properties\": {\n      \"@id\": \"cxf:properties\",\n      \"@type\": \"@id\"\n    },\n    \"providers\": {\n      \"@id\": \"cxf:providers\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"serviceClass\": {\n      \"@id\": \"cxf:serviceClass\",\n      \"@type\": \"xsd:string\"\n    },\n    \"serviceName\": {\n      \"@id\": \"cxf:serviceName\",\n    \
  \  \"@type\": \"xsd:string\"\n    },\n    \"signatureKeyIdentifier\": {\n      \"@id\": \"cxf:signatureKeyIdentifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"signaturePropFile\": {\n      \"@id\": \"cxf:signaturePropFile\",\n      \"@type\": \"xsd:string\"\n    },\n    \"user\": {\n      \"@id\": \"cxf:user\",\n      \"@type\": \"xsd:string\"\n    },\n    \"wsdlLocation\": {\n      \"@id\": \"cxf:wsdlLocation\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/apache-cxf/refs/heads/main/json-ld/apache-cxf-context.jsonld
tags:
- Apache
- JAX-RS
- JAX-WS
- Java
- Open Source
- REST
- SOAP
- WS-Security
- Web Services
- JSON-LD
- Linked Data
- Semantic Web
---
