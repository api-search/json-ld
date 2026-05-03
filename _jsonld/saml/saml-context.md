---
api_specs:
- filename: saml-sso-bindings.yml
  format: yaml
  label: SAML 2.0 SSO HTTP Bindings API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/saml/refs/heads/main/openapi/saml-sso-bindings.yml
class_count: 7
classes:
- saml
- samlp
- samlmd
- name
- description
- url
- identifier
context_file: json-ld/saml-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/saml/refs/heads/main/json-ld/saml-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Saml from SAML.
layout: jsonld
name: Saml Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: sec
  uri: https://w3id.org/security#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: foaf
  uri: http://xmlns.com/foaf/0.1/
properties:
- container: ''
  name: IdentityProvider
  type: reference
- container: ''
  name: ServiceProvider
  type: reference
- container: ''
  name: EntityDescriptor
  type: reference
- container: ''
  name: Assertion
  type: reference
- container: ''
  name: AuthnRequest
  type: reference
- container: ''
  name: AuthnStatement
  type: reference
- container: ''
  name: AttributeStatement
  type: reference
- container: ''
  name: Subject
  type: reference
- container: ''
  name: NameID
  type: reference
- container: ''
  name: Conditions
  type: reference
- container: ''
  name: entityID
  type: reference
- container: ''
  name: issuer
  type: string
- container: ''
  name: issueInstant
  type: dateTime
- container: ''
  name: destination
  type: reference
- container: ''
  name: assertionConsumerServiceURL
  type: reference
- container: ''
  name: singleSignOnService
  type: reference
- container: ''
  name: singleLogoutService
  type: reference
- container: ''
  name: assertionConsumerService
  type: reference
- container: ''
  name: binding
  type: reference
- container: ''
  name: location
  type: reference
- container: ''
  name: nameIDFormat
  type: reference
- container: ''
  name: protocolSupportEnumeration
  type: reference
- container: ''
  name: authnContextClassRef
  type: reference
- container: ''
  name: sessionIndex
  type: string
- container: ''
  name: relayState
  type: string
- container: ''
  name: forceAuthn
  type: boolean
- container: ''
  name: isPassive
  type: boolean
- container: ''
  name: wantAuthnRequestsSigned
  type: boolean
- container: ''
  name: authnRequestsSigned
  type: boolean
- container: ''
  name: wantAssertionsSigned
  type: boolean
- container: ''
  name: notBefore
  type: dateTime
- container: ''
  name: notOnOrAfter
  type: dateTime
- container: ''
  name: audience
  type: reference
- container: ''
  name: signingCertificate
  type: string
- container: ''
  name: issued
  type: date
property_count: 35
provider_name: SAML
provider_slug: saml
slug: saml-context
source_filename: saml-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"saml\": \"urn:oasis:names:tc:SAML:2.0:\",\n    \"samlp\": \"urn:oasis:names:tc:SAML:2.0:protocol#\",\n    \"samlmd\": \"urn:oasis:names:tc:SAML:2.0:metadata#\",\n    \"schema\": \"https://schema.org/\",\n    \"sec\": \"https://w3id.org/security#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"foaf\": \"http://xmlns.com/foaf/0.1/\",\n    \"IdentityProvider\": {\n      \"@id\": \"samlmd:IDPSSODescriptor\",\n      \"@type\": \"@id\"\n    },\n    \"ServiceProvider\": {\n      \"@id\": \"samlmd:SPSSODescriptor\",\n      \"@type\": \"@id\"\n    },\n    \"EntityDescriptor\": {\n      \"@id\": \"samlmd:EntityDescriptor\",\n      \"@type\": \"@id\"\n    },\n    \"Assertion\": {\n      \"@id\": \"saml:assertion#Assertion\",\n      \"@type\": \"@id\"\n    },\n    \"AuthnRequest\": {\n      \"@id\": \"samlp:AuthnRequest\",\n      \"@type\": \"@id\"\n    },\n    \"AuthnStatement\"\
  : {\n      \"@id\": \"saml:assertion#AuthnStatement\",\n      \"@type\": \"@id\"\n    },\n    \"AttributeStatement\": {\n      \"@id\": \"saml:assertion#AttributeStatement\",\n      \"@type\": \"@id\"\n    },\n    \"Subject\": {\n      \"@id\": \"saml:assertion#Subject\",\n      \"@type\": \"@id\"\n    },\n    \"NameID\": {\n      \"@id\": \"saml:assertion#NameID\",\n      \"@type\": \"@id\"\n    },\n    \"Conditions\": {\n      \"@id\": \"saml:assertion#Conditions\",\n      \"@type\": \"@id\"\n    },\n    \"entityID\": {\n      \"@id\": \"samlmd:entityID\",\n      \"@type\": \"@id\"\n    },\n    \"issuer\": {\n      \"@id\": \"saml:assertion#Issuer\",\n      \"@type\": \"xsd:string\"\n    },\n    \"issueInstant\": {\n      \"@id\": \"saml:assertion#IssueInstant\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"destination\": {\n      \"@id\": \"samlp:Destination\",\n      \"@type\": \"@id\"\n    },\n    \"assertionConsumerServiceURL\": {\n      \"@id\": \"samlp:AssertionConsumerServiceURL\"\
  ,\n      \"@type\": \"@id\"\n    },\n    \"singleSignOnService\": {\n      \"@id\": \"samlmd:SingleSignOnService\",\n      \"@type\": \"@id\"\n    },\n    \"singleLogoutService\": {\n      \"@id\": \"samlmd:SingleLogoutService\",\n      \"@type\": \"@id\"\n    },\n    \"assertionConsumerService\": {\n      \"@id\": \"samlmd:AssertionConsumerService\",\n      \"@type\": \"@id\"\n    },\n    \"binding\": {\n      \"@id\": \"samlmd:Binding\",\n      \"@type\": \"@id\"\n    },\n    \"location\": {\n      \"@id\": \"samlmd:Location\",\n      \"@type\": \"@id\"\n    },\n    \"nameIDFormat\": {\n      \"@id\": \"samlmd:NameIDFormat\",\n      \"@type\": \"@id\"\n    },\n    \"protocolSupportEnumeration\": {\n      \"@id\": \"samlmd:protocolSupportEnumeration\",\n      \"@type\": \"@id\"\n    },\n    \"authnContextClassRef\": {\n      \"@id\": \"saml:assertion#AuthnContextClassRef\",\n      \"@type\": \"@id\"\n    },\n    \"sessionIndex\": {\n      \"@id\": \"samlp:SessionIndex\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"relayState\": {\n      \"@id\": \"samlp:RelayState\",\n      \"@type\": \"xsd:string\"\n    },\n    \"forceAuthn\": {\n      \"@id\": \"samlp:ForceAuthn\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isPassive\": {\n      \"@id\": \"samlp:IsPassive\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"wantAuthnRequestsSigned\": {\n      \"@id\": \"samlmd:WantAuthnRequestsSigned\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"authnRequestsSigned\": {\n      \"@id\": \"samlmd:AuthnRequestsSigned\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"wantAssertionsSigned\": {\n      \"@id\": \"samlmd:WantAssertionsSigned\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"notBefore\": {\n      \"@id\": \"saml:assertion#NotBefore\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"notOnOrAfter\": {\n      \"@id\": \"saml:assertion#NotOnOrAfter\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"audience\": {\n      \"@id\": \"saml:assertion#Audience\"\
  ,\n      \"@type\": \"@id\"\n    },\n    \"signingCertificate\": {\n      \"@id\": \"sec:publicKey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"identifier\": \"dcterms:identifier\",\n    \"issued\": {\n      \"@id\": \"dcterms:issued\",\n      \"@type\": \"xsd:date\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/saml/refs/heads/main/json-ld/saml-context.jsonld
tags:
- Authentication
- Authorization
- Federation
- Identity Management
- Open Standard
- Security
- Single Sign-On
- SSO
- XML
- JSON-LD
- Linked Data
- Semantic Web
---
