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
