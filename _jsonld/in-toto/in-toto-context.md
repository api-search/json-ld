---
class_count: 9
classes:
- Layout
- Step
- Inspection
- Link
- Statement
- Subject
- DigestSet
- ArtifactRule
- Functionary
context_file: json-ld/in-toto-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/in-toto/refs/heads/main/json-ld/in-toto-context.jsonld
description: JSON-LD context defining the semantic vocabulary for In Toto from In-Toto.
layout: jsonld
name: In Toto Context
namespaces:
- prefix: intoto
  uri: https://in-toto.io/vocab#
- prefix: slsa
  uri: https://slsa.dev/vocab#
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: sec
  uri: https://w3id.org/security#
- prefix: spdx
  uri: https://spdx.org/rdf/terms#
properties:
- container: ''
  name: name
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: version
  type: string
- container: ''
  name: expires
  type: dateTime
- container: ''
  name: created
  type: dateTime
- container: set
  name: steps
  type: ''
- container: set
  name: inspect
  type: ''
- container: set
  name: keys
  type: ''
- container: set
  name: pubkeys
  type: ''
- container: ''
  name: threshold
  type: integer
- container: list
  name: expected_command
  type: ''
- container: list
  name: expected_materials
  type: ''
- container: list
  name: expected_products
  type: ''
- container: list
  name: command
  type: ''
- container: ''
  name: materials
  type: reference
- container: ''
  name: products
  type: reference
- container: ''
  name: byproducts
  type: ''
- container: ''
  name: environment
  type: ''
- container: list
  name: run
  type: ''
- container: set
  name: subject
  type: ''
- container: ''
  name: predicateType
  type: reference
- container: ''
  name: predicate
  type: ''
- container: ''
  name: digest
  type: ''
- container: ''
  name: sha256
  type: string
- container: ''
  name: sha512
  type: string
- container: ''
  name: gitCommit
  type: string
- container: ''
  name: buildType
  type: reference
- container: ''
  name: externalParameters
  type: ''
- container: ''
  name: internalParameters
  type: ''
- container: set
  name: resolvedDependencies
  type: ''
- container: ''
  name: builder
  type: ''
- container: ''
  name: buildDefinition
  type: ''
- container: ''
  name: runDetails
  type: ''
- container: ''
  name: invocationId
  type: string
- container: ''
  name: startedOn
  type: dateTime
- container: ''
  name: finishedOn
  type: dateTime
- container: ''
  name: keytype
  type: string
- container: ''
  name: scheme
  type: string
- container: ''
  name: keyval
  type: ''
- container: set
  name: tags
  type: ''
- container: ''
  name: url
  type: reference
property_count: 41
provider_name: In-Toto
provider_slug: in-toto
slug: in-toto-context
source_filename: in-toto-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"intoto\": \"https://in-toto.io/vocab#\",\n    \"slsa\": \"https://slsa.dev/vocab#\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"sec\": \"https://w3id.org/security#\",\n    \"spdx\": \"https://spdx.org/rdf/terms#\",\n\n    \"Layout\": \"intoto:Layout\",\n    \"Step\": \"intoto:Step\",\n    \"Inspection\": \"intoto:Inspection\",\n    \"Link\": \"intoto:Link\",\n    \"Statement\": \"intoto:Statement\",\n    \"Subject\": \"intoto:Subject\",\n    \"DigestSet\": \"intoto:DigestSet\",\n    \"ArtifactRule\": \"intoto:ArtifactRule\",\n    \"Functionary\": \"intoto:Functionary\",\n\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"version\": {\n      \"@id\": \"schema:softwareVersion\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"expires\": {\n      \"@id\": \"dcterms:valid\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"created\": {\n      \"@id\": \"dcterms:created\",\n      \"@type\": \"xsd:dateTime\"\n    },\n\n    \"steps\": {\n      \"@id\": \"intoto:steps\",\n      \"@container\": \"@set\"\n    },\n    \"inspect\": {\n      \"@id\": \"intoto:inspections\",\n      \"@container\": \"@set\"\n    },\n    \"keys\": {\n      \"@id\": \"sec:verificationMethod\",\n      \"@container\": \"@set\"\n    },\n    \"pubkeys\": {\n      \"@id\": \"intoto:authorizedKeys\",\n      \"@container\": \"@set\"\n    },\n    \"threshold\": {\n      \"@id\": \"intoto:threshold\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"expected_command\": {\n      \"@id\": \"intoto:expectedCommand\",\n      \"@container\": \"@list\"\n    },\n    \"expected_materials\": {\n      \"@id\": \"intoto:expectedMaterials\",\n      \"@container\": \"@list\"\n    },\n    \"expected_products\"\
  : {\n      \"@id\": \"intoto:expectedProducts\",\n      \"@container\": \"@list\"\n    },\n\n    \"command\": {\n      \"@id\": \"intoto:command\",\n      \"@container\": \"@list\"\n    },\n    \"materials\": {\n      \"@id\": \"intoto:materials\",\n      \"@type\": \"@id\"\n    },\n    \"products\": {\n      \"@id\": \"intoto:products\",\n      \"@type\": \"@id\"\n    },\n    \"byproducts\": {\n      \"@id\": \"intoto:byproducts\"\n    },\n    \"environment\": {\n      \"@id\": \"intoto:environment\"\n    },\n    \"run\": {\n      \"@id\": \"intoto:runCommand\",\n      \"@container\": \"@list\"\n    },\n\n    \"subject\": {\n      \"@id\": \"intoto:subject\",\n      \"@container\": \"@set\"\n    },\n    \"predicateType\": {\n      \"@id\": \"intoto:predicateType\",\n      \"@type\": \"@id\"\n    },\n    \"predicate\": {\n      \"@id\": \"intoto:predicate\"\n    },\n    \"digest\": {\n      \"@id\": \"intoto:digest\"\n    },\n    \"sha256\": {\n      \"@id\": \"intoto:sha256\",\n     \
  \ \"@type\": \"xsd:string\"\n    },\n    \"sha512\": {\n      \"@id\": \"intoto:sha512\",\n      \"@type\": \"xsd:string\"\n    },\n    \"gitCommit\": {\n      \"@id\": \"intoto:gitCommit\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"buildType\": {\n      \"@id\": \"slsa:buildType\",\n      \"@type\": \"@id\"\n    },\n    \"externalParameters\": {\n      \"@id\": \"slsa:externalParameters\"\n    },\n    \"internalParameters\": {\n      \"@id\": \"slsa:internalParameters\"\n    },\n    \"resolvedDependencies\": {\n      \"@id\": \"slsa:resolvedDependencies\",\n      \"@container\": \"@set\"\n    },\n    \"builder\": {\n      \"@id\": \"slsa:builder\"\n    },\n    \"buildDefinition\": {\n      \"@id\": \"slsa:buildDefinition\"\n    },\n    \"runDetails\": {\n      \"@id\": \"slsa:runDetails\"\n    },\n    \"invocationId\": {\n      \"@id\": \"slsa:invocationId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startedOn\": {\n      \"@id\": \"slsa:startedOn\",\n      \"@type\": \"\
  xsd:dateTime\"\n    },\n    \"finishedOn\": {\n      \"@id\": \"slsa:finishedOn\",\n      \"@type\": \"xsd:dateTime\"\n    },\n\n    \"keytype\": {\n      \"@id\": \"sec:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"scheme\": {\n      \"@id\": \"sec:algorithm\",\n      \"@type\": \"xsd:string\"\n    },\n    \"keyval\": {\n      \"@id\": \"sec:publicKeyJwk\"\n    },\n\n    \"tags\": {\n      \"@id\": \"schema:keywords\",\n      \"@container\": \"@set\"\n    },\n    \"url\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/in-toto/refs/heads/main/json-ld/in-toto-context.jsonld
tags:
- Cloud Native
- Graduated
- Security
- Software Integrity
- Supply Chain Security
- Verification
- JSON-LD
- Linked Data
- Semantic Web
---
