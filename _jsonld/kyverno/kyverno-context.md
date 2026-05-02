---
api_specs:
- filename: kyverno-policy-reporter-openapi.yml
  format: yaml
  label: Kyverno Policy Reporter API
  slug: kyverno-policy-reporter-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/kyverno/refs/heads/main/openapi/kyverno-policy-reporter-openapi.yml
class_count: 11
classes:
- Policy
- ClusterPolicy
- PolicyRule
- ValidationRule
- MutationRule
- GenerationRule
- ImageVerificationRule
- PolicyReport
- ClusterPolicyReport
- PolicyResult
- PolicyViolation
context_file: json-ld/kyverno-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/kyverno/refs/heads/main/json-ld/kyverno-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Kyverno from Kyverno.
layout: jsonld
name: Kyverno Context
namespaces:
- prefix: kyverno
  uri: https://kyverno.io/vocab#
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: k8s
  uri: https://kubernetes.io/docs/reference/generated/kubernetes-api/v1.28/#
- prefix: oci
  uri: https://opencontainers.org/schema#
- prefix: sec
  uri: https://w3id.org/security#
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
  name: policy
  type: string
- container: ''
  name: rule
  type: string
- container: ''
  name: message
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: severity
  type: string
- container: ''
  name: category
  type: string
- container: ''
  name: source
  type: string
- container: ''
  name: background
  type: boolean
- container: ''
  name: validationFailureAction
  type: string
- container: ''
  name: failurePolicy
  type: string
- container: ''
  name: ready
  type: boolean
- container: set
  name: rules
  type: ''
- container: ''
  name: match
  type: reference
- container: ''
  name: exclude
  type: reference
- container: ''
  name: validate
  type: reference
- container: ''
  name: mutate
  type: reference
- container: ''
  name: generate
  type: reference
- container: set
  name: verifyImages
  type: ''
- container: set
  name: context
  type: ''
- container: ''
  name: namespace
  type: string
- container: set
  name: namespaces
  type: ''
- container: ''
  name: kind
  type: string
- container: set
  name: kinds
  type: ''
- container: ''
  name: apiVersion
  type: string
- container: ''
  name: uid
  type: string
- container: set
  name: imageReferences
  type: ''
- container: ''
  name: mutateDigest
  type: boolean
- container: ''
  name: verifyDigest
  type: boolean
- container: set
  name: attestors
  type: ''
- container: ''
  name: publicKeys
  type: string
- container: ''
  name: issuer
  type: reference
- container: ''
  name: subject
  type: string
- container: ''
  name: pass
  type: integer
- container: ''
  name: fail
  type: integer
- container: ''
  name: warn
  type: integer
- container: ''
  name: error
  type: integer
- container: ''
  name: skip
  type: integer
- container: ''
  name: summary
  type: reference
- container: set
  name: results
  type: ''
- container: ''
  name: synchronize
  type: boolean
- container: set
  name: tags
  type: ''
- container: ''
  name: creationTimestamp
  type: dateTime
- container: ''
  name: timestamp
  type: dateTime
- container: ''
  name: lastTransitionTime
  type: dateTime
property_count: 47
provider_name: Kyverno
provider_slug: kyverno
slug: kyverno-context
source_filename: kyverno-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"kyverno\": \"https://kyverno.io/vocab#\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"k8s\": \"https://kubernetes.io/docs/reference/generated/kubernetes-api/v1.28/#\",\n    \"oci\": \"https://opencontainers.org/schema#\",\n    \"sec\": \"https://w3id.org/security#\",\n\n    \"Policy\": \"kyverno:Policy\",\n    \"ClusterPolicy\": \"kyverno:ClusterPolicy\",\n    \"PolicyRule\": \"kyverno:PolicyRule\",\n    \"ValidationRule\": \"kyverno:ValidationRule\",\n    \"MutationRule\": \"kyverno:MutationRule\",\n    \"GenerationRule\": \"kyverno:GenerationRule\",\n    \"ImageVerificationRule\": \"kyverno:ImageVerificationRule\",\n    \"PolicyReport\": \"kyverno:PolicyReport\",\n    \"ClusterPolicyReport\": \"kyverno:ClusterPolicyReport\",\n    \"PolicyResult\": \"kyverno:PolicyResult\",\n    \"PolicyViolation\": \"kyverno:PolicyViolation\"\
  ,\n\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"version\": {\n      \"@id\": \"schema:softwareVersion\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"policy\": {\n      \"@id\": \"kyverno:policyName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rule\": {\n      \"@id\": \"kyverno:ruleName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"message\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"kyverno:resultStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"severity\": {\n      \"@id\": \"kyverno:severity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"category\": {\n      \"@id\": \"dcterms:subject\",\n      \"@type\": \"xsd:string\"\n    },\n    \"source\": {\n      \"@id\": \"dcterms:source\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"background\": {\n      \"@id\": \"kyverno:backgroundScanning\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"validationFailureAction\": {\n      \"@id\": \"kyverno:validationFailureAction\",\n      \"@type\": \"xsd:string\"\n    },\n    \"failurePolicy\": {\n      \"@id\": \"kyverno:failurePolicy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ready\": {\n      \"@id\": \"schema:Boolean\",\n      \"@type\": \"xsd:boolean\"\n    },\n\n    \"rules\": {\n      \"@id\": \"kyverno:hasRule\",\n      \"@container\": \"@set\"\n    },\n    \"match\": {\n      \"@id\": \"kyverno:matchCriteria\",\n      \"@type\": \"@id\"\n    },\n    \"exclude\": {\n      \"@id\": \"kyverno:excludeCriteria\",\n      \"@type\": \"@id\"\n    },\n    \"validate\": {\n      \"@id\": \"kyverno:validationSpec\",\n      \"@type\": \"@id\"\n    },\n    \"mutate\": {\n      \"@id\": \"kyverno:mutationSpec\",\n      \"@type\": \"@id\"\n    },\n    \"generate\": {\n      \"@id\": \"kyverno:generationSpec\",\n\
  \      \"@type\": \"@id\"\n    },\n    \"verifyImages\": {\n      \"@id\": \"kyverno:imageVerificationSpec\",\n      \"@container\": \"@set\"\n    },\n    \"context\": {\n      \"@id\": \"kyverno:ruleContext\",\n      \"@container\": \"@set\"\n    },\n\n    \"namespace\": {\n      \"@id\": \"k8s:namespace\",\n      \"@type\": \"xsd:string\"\n    },\n    \"namespaces\": {\n      \"@id\": \"k8s:namespace\",\n      \"@container\": \"@set\"\n    },\n    \"kind\": {\n      \"@id\": \"k8s:kind\",\n      \"@type\": \"xsd:string\"\n    },\n    \"kinds\": {\n      \"@id\": \"k8s:kind\",\n      \"@container\": \"@set\"\n    },\n    \"apiVersion\": {\n      \"@id\": \"k8s:apiVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"uid\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"imageReferences\": {\n      \"@id\": \"oci:imageReference\",\n      \"@container\": \"@set\"\n    },\n    \"mutateDigest\": {\n      \"@id\": \"kyverno:mutateDigest\",\n\
  \      \"@type\": \"xsd:boolean\"\n    },\n    \"verifyDigest\": {\n      \"@id\": \"kyverno:verifyDigest\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"attestors\": {\n      \"@id\": \"sec:verifier\",\n      \"@container\": \"@set\"\n    },\n    \"publicKeys\": {\n      \"@id\": \"sec:publicKey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"issuer\": {\n      \"@id\": \"sec:issuer\",\n      \"@type\": \"@id\"\n    },\n    \"subject\": {\n      \"@id\": \"sec:credentialSubject\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"pass\": {\n      \"@id\": \"kyverno:passCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"fail\": {\n      \"@id\": \"kyverno:failCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"warn\": {\n      \"@id\": \"kyverno:warnCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"error\": {\n      \"@id\": \"kyverno:errorCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"skip\": {\n      \"@id\": \"kyverno:skipCount\",\n      \"@type\"\
  : \"xsd:integer\"\n    },\n    \"summary\": {\n      \"@id\": \"kyverno:resultSummary\",\n      \"@type\": \"@id\"\n    },\n    \"results\": {\n      \"@id\": \"kyverno:policyResult\",\n      \"@container\": \"@set\"\n    },\n\n    \"synchronize\": {\n      \"@id\": \"kyverno:synchronize\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"tags\": {\n      \"@id\": \"schema:keywords\",\n      \"@container\": \"@set\"\n    },\n\n    \"creationTimestamp\": {\n      \"@id\": \"dcterms:created\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"timestamp\": {\n      \"@id\": \"dcterms:date\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"lastTransitionTime\": {\n      \"@id\": \"kyverno:lastTransitionTime\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/kyverno/refs/heads/main/json-ld/kyverno-context.jsonld
tags:
- Cloud Native
- Governance
- Kubernetes
- Policy Management
- Security
- JSON-LD
- Linked Data
- Semantic Web
---
