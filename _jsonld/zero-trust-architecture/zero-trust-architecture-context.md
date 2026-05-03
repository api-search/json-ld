---
class_count: 0
classes: []
context_file: json-ld/zero-trust-architecture-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/zero-trust-architecture/refs/heads/main/json-ld/zero-trust-architecture-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Zero Trust Architecture from Zero Trust Architecture.
layout: jsonld
name: Zero Trust Architecture Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: owl
  uri: http://www.w3.org/2002/07/owl#
- prefix: rdf
  uri: http://www.w3.org/1999/02/22-rdf-syntax-ns#
- prefix: rdfs
  uri: http://www.w3.org/2000/01/rdf-schema#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: security
  uri: https://w3id.org/security#
- prefix: zta
  uri: https://github.com/api-evangelist/zero-trust-architecture/blob/main/json-ld/zero-trust-architecture-context.jsonld#
properties:
- container: ''
  name: ZeroTrustPolicy
  type: reference
- container: ''
  name: ZeroTrustIdentity
  type: reference
- container: ''
  name: ZeroTrustResource
  type: reference
- container: ''
  name: PolicyDecisionPoint
  type: reference
- container: ''
  name: PolicyEnforcementPoint
  type: reference
- container: ''
  name: PolicyAdministrationPoint
  type: reference
- container: ''
  name: WorkloadIdentity
  type: reference
- container: ''
  name: policyId
  type: ''
- container: ''
  name: identityId
  type: ''
- container: ''
  name: resourceId
  type: ''
- container: ''
  name: name
  type: ''
- container: ''
  name: description
  type: ''
- container: ''
  name: version
  type: ''
- container: ''
  name: effect
  type: ''
- container: set
  name: subjects
  type: ''
- container: set
  name: resources
  type: ''
- container: ''
  name: conditions
  type: ''
- container: ''
  name: type
  type: reference
- container: ''
  name: principalName
  type: ''
- container: ''
  name: displayName
  type: ''
- container: ''
  name: spiffeId
  type: reference
- container: ''
  name: idProvider
  type: ''
- container: set
  name: authenticationMethods
  type: ''
- container: ''
  name: assuranceLevel
  type: ''
- container: ''
  name: authenticationAssuranceLevel
  type: ''
- container: ''
  name: device
  type: ''
- container: ''
  name: deviceId
  type: ''
- container: ''
  name: managed
  type: boolean
- container: ''
  name: compliant
  type: boolean
- container: ''
  name: trustScore
  type: integer
- container: ''
  name: riskScore
  type: integer
- container: ''
  name: sensitivity
  type: ''
- container: ''
  name: environment
  type: ''
- container: set
  name: protectionMechanisms
  type: ''
- container: ''
  name: policyEnforcementPoint
  type: ''
- container: set
  name: allowedActions
  type: ''
- container: set
  name: complianceFrameworks
  type: ''
- container: ''
  name: enforcementMode
  type: ''
- container: ''
  name: owner
  type: ''
- container: set
  name: groups
  type: ''
- container: ''
  name: lastAuthenticated
  type: dateTime
- container: ''
  name: sessionExpiry
  type: dateTime
- container: ''
  name: created
  type: date
- container: ''
  name: modified
  type: date
- container: ''
  name: url
  type: reference
property_count: 45
provider_name: Zero Trust Architecture
provider_slug: zero-trust-architecture
slug: zero-trust-architecture-context
source_filename: zero-trust-architecture-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"owl\": \"http://www.w3.org/2002/07/owl#\",\n    \"rdf\": \"http://www.w3.org/1999/02/22-rdf-syntax-ns#\",\n    \"rdfs\": \"http://www.w3.org/2000/01/rdf-schema#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"security\": \"https://w3id.org/security#\",\n    \"zta\": \"https://github.com/api-evangelist/zero-trust-architecture/blob/main/json-ld/zero-trust-architecture-context.jsonld#\",\n\n    \"ZeroTrustPolicy\": {\n      \"@id\": \"zta:ZeroTrustPolicy\",\n      \"@type\": \"@id\"\n    },\n    \"ZeroTrustIdentity\": {\n      \"@id\": \"zta:ZeroTrustIdentity\",\n      \"@type\": \"@id\"\n    },\n    \"ZeroTrustResource\": {\n      \"@id\": \"zta:ZeroTrustResource\",\n      \"@type\": \"@id\"\n    },\n    \"PolicyDecisionPoint\": {\n      \"@id\": \"zta:PolicyDecisionPoint\",\n      \"@type\": \"@id\"\n    },\n    \"PolicyEnforcementPoint\"\
  : {\n      \"@id\": \"zta:PolicyEnforcementPoint\",\n      \"@type\": \"@id\"\n    },\n    \"PolicyAdministrationPoint\": {\n      \"@id\": \"zta:PolicyAdministrationPoint\",\n      \"@type\": \"@id\"\n    },\n    \"WorkloadIdentity\": {\n      \"@id\": \"zta:WorkloadIdentity\",\n      \"@type\": \"@id\"\n    },\n\n    \"policyId\": {\n      \"@id\": \"schema:identifier\"\n    },\n    \"identityId\": {\n      \"@id\": \"schema:identifier\"\n    },\n    \"resourceId\": {\n      \"@id\": \"schema:identifier\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\"\n    },\n    \"version\": {\n      \"@id\": \"dcterms:hasVersion\"\n    },\n    \"effect\": {\n      \"@id\": \"zta:effect\"\n    },\n    \"subjects\": {\n      \"@id\": \"zta:subjects\",\n      \"@container\": \"@set\"\n    },\n    \"resources\": {\n      \"@id\": \"zta:resources\",\n      \"@container\": \"@set\"\n    },\n    \"conditions\": {\n      \"@id\"\
  : \"zta:conditions\"\n    },\n    \"type\": {\n      \"@id\": \"rdf:type\",\n      \"@type\": \"@id\"\n    },\n    \"principalName\": {\n      \"@id\": \"zta:principalName\"\n    },\n    \"displayName\": {\n      \"@id\": \"schema:name\"\n    },\n    \"spiffeId\": {\n      \"@id\": \"zta:spiffeId\",\n      \"@type\": \"@id\"\n    },\n    \"idProvider\": {\n      \"@id\": \"zta:identityProvider\"\n    },\n    \"authenticationMethods\": {\n      \"@id\": \"zta:authenticationMethods\",\n      \"@container\": \"@set\"\n    },\n    \"assuranceLevel\": {\n      \"@id\": \"zta:assuranceLevel\"\n    },\n    \"authenticationAssuranceLevel\": {\n      \"@id\": \"zta:authenticationAssuranceLevel\"\n    },\n    \"device\": {\n      \"@id\": \"zta:device\"\n    },\n    \"deviceId\": {\n      \"@id\": \"schema:identifier\"\n    },\n    \"managed\": {\n      \"@id\": \"zta:managed\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"compliant\": {\n      \"@id\": \"zta:compliant\",\n      \"@type\": \"\
  xsd:boolean\"\n    },\n    \"trustScore\": {\n      \"@id\": \"zta:trustScore\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"riskScore\": {\n      \"@id\": \"zta:riskScore\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"sensitivity\": {\n      \"@id\": \"zta:sensitivity\"\n    },\n    \"environment\": {\n      \"@id\": \"zta:environment\"\n    },\n    \"protectionMechanisms\": {\n      \"@id\": \"zta:protectionMechanisms\",\n      \"@container\": \"@set\"\n    },\n    \"policyEnforcementPoint\": {\n      \"@id\": \"zta:policyEnforcementPoint\"\n    },\n    \"allowedActions\": {\n      \"@id\": \"zta:allowedActions\",\n      \"@container\": \"@set\"\n    },\n    \"complianceFrameworks\": {\n      \"@id\": \"zta:complianceFrameworks\",\n      \"@container\": \"@set\"\n    },\n    \"enforcementMode\": {\n      \"@id\": \"zta:enforcementMode\"\n    },\n    \"owner\": {\n      \"@id\": \"schema:accountablePerson\"\n    },\n    \"groups\": {\n      \"@id\": \"zta:groups\",\n      \"\
  @container\": \"@set\"\n    },\n    \"lastAuthenticated\": {\n      \"@id\": \"zta:lastAuthenticated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"sessionExpiry\": {\n      \"@id\": \"zta:sessionExpiry\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"created\": {\n      \"@id\": \"dcterms:created\",\n      \"@type\": \"xsd:date\"\n    },\n    \"modified\": {\n      \"@id\": \"dcterms:modified\",\n      \"@type\": \"xsd:date\"\n    },\n    \"url\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/zero-trust-architecture/refs/heads/main/json-ld/zero-trust-architecture-context.jsonld
tags:
- Access Control
- Authentication
- Authorization
- Cybersecurity
- Identity Management
- Least Privilege
- Network Security
- NIST
- Security
- Zero Trust
- JSON-LD
- Linked Data
- Semantic Web
---
