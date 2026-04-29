---
class_count: 0
classes: []
context_file: json-ld/cert-manager-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/cert-manager/refs/heads/main/json-ld/cert-manager-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Cert Manager from Cert-Manager.
layout: jsonld
name: Cert Manager Context
namespaces:
- prefix: certmgr
  uri: https://cert-manager.io/vocab/
- prefix: k8s
  uri: https://kubernetes.io/vocab/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: sec
  uri: https://w3id.org/security#
properties:
- container: ''
  name: Certificate
  type: ''
- container: ''
  name: CertificateSpec
  type: ''
- container: ''
  name: CertificateStatus
  type: ''
- container: ''
  name: Issuer
  type: ''
- container: ''
  name: ClusterIssuer
  type: ''
- container: ''
  name: IssuerSpec
  type: ''
- container: ''
  name: ACMEIssuer
  type: ''
- container: ''
  name: CAIssuer
  type: ''
- container: ''
  name: CertificateRequest
  type: ''
- container: ''
  name: CertificateRequestPolicy
  type: ''
- container: ''
  name: ObjectReference
  type: ''
- container: ''
  name: Condition
  type: ''
property_count: 12
provider_name: Cert-Manager
provider_slug: cert-manager
slug: cert-manager-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"certmgr\": \"https://cert-manager.io/vocab/\",\n    \"k8s\": \"https://kubernetes.io/vocab/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"sec\": \"https://w3id.org/security#\",\n\n    \"Certificate\": {\n      \"@id\": \"certmgr:Certificate\",\n      \"@context\": {\n        \"apiVersion\": {\n          \"@id\": \"k8s:apiVersion\"\n        },\n        \"kind\": {\n          \"@id\": \"k8s:kind\"\n        },\n        \"metadata\": {\n          \"@id\": \"k8s:metadata\"\n        },\n        \"spec\": {\n          \"@id\": \"certmgr:certificateSpec\"\n        },\n        \"status\": {\n          \"@id\": \"certmgr:certificateStatus\"\n        }\n      }\n    },\n\n    \"CertificateSpec\": {\n      \"@id\": \"certmgr:CertificateSpec\",\n      \"@context\": {\n        \"secretName\": {\n          \"@id\": \"certmgr:secretName\"\
  \n        },\n        \"issuerRef\": {\n          \"@id\": \"certmgr:issuerRef\"\n        },\n        \"commonName\": {\n          \"@id\": \"schema:name\"\n        },\n        \"dnsNames\": {\n          \"@id\": \"certmgr:dnsNames\",\n          \"@container\": \"@set\"\n        },\n        \"uris\": {\n          \"@id\": \"certmgr:uris\",\n          \"@container\": \"@set\"\n        },\n        \"emailAddresses\": {\n          \"@id\": \"schema:email\",\n          \"@container\": \"@set\"\n        },\n        \"ipAddresses\": {\n          \"@id\": \"certmgr:ipAddresses\",\n          \"@container\": \"@set\"\n        },\n        \"duration\": {\n          \"@id\": \"certmgr:duration\"\n        },\n        \"renewBefore\": {\n          \"@id\": \"certmgr:renewBefore\"\n        },\n        \"isCA\": {\n          \"@id\": \"certmgr:isCA\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"usages\": {\n          \"@id\": \"certmgr:keyUsages\",\n          \"@container\": \"@set\"\
  \n        },\n        \"privateKey\": {\n          \"@id\": \"certmgr:privateKeyConfig\"\n        }\n      }\n    },\n\n    \"CertificateStatus\": {\n      \"@id\": \"certmgr:CertificateStatus\",\n      \"@context\": {\n        \"conditions\": {\n          \"@id\": \"k8s:conditions\",\n          \"@container\": \"@set\"\n        },\n        \"notBefore\": {\n          \"@id\": \"certmgr:notBefore\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"notAfter\": {\n          \"@id\": \"certmgr:notAfter\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"renewalTime\": {\n          \"@id\": \"certmgr:renewalTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"revision\": {\n          \"@id\": \"certmgr:revision\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"Issuer\": {\n      \"@id\": \"certmgr:Issuer\",\n      \"@context\": {\n        \"spec\": {\n          \"@id\": \"certmgr:issuerSpec\"\n        },\n        \"status\"\
  : {\n          \"@id\": \"certmgr:issuerStatus\"\n        }\n      }\n    },\n\n    \"ClusterIssuer\": {\n      \"@id\": \"certmgr:ClusterIssuer\",\n      \"@context\": {\n        \"spec\": {\n          \"@id\": \"certmgr:issuerSpec\"\n        },\n        \"status\": {\n          \"@id\": \"certmgr:issuerStatus\"\n        }\n      }\n    },\n\n    \"IssuerSpec\": {\n      \"@id\": \"certmgr:IssuerSpec\",\n      \"@context\": {\n        \"acme\": {\n          \"@id\": \"certmgr:acmeConfig\"\n        },\n        \"ca\": {\n          \"@id\": \"certmgr:caConfig\"\n        },\n        \"selfSigned\": {\n          \"@id\": \"certmgr:selfSignedConfig\"\n        },\n        \"vault\": {\n          \"@id\": \"certmgr:vaultConfig\"\n        },\n        \"venafi\": {\n          \"@id\": \"certmgr:venafiConfig\"\n        }\n      }\n    },\n\n    \"ACMEIssuer\": {\n      \"@id\": \"certmgr:ACMEIssuer\",\n      \"@context\": {\n        \"server\": {\n          \"@id\": \"certmgr:acmeServer\",\n  \
  \        \"@type\": \"@id\"\n        },\n        \"email\": {\n          \"@id\": \"schema:email\"\n        },\n        \"privateKeySecretRef\": {\n          \"@id\": \"certmgr:privateKeySecretRef\"\n        },\n        \"solvers\": {\n          \"@id\": \"certmgr:solvers\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"CAIssuer\": {\n      \"@id\": \"certmgr:CAIssuer\",\n      \"@context\": {\n        \"secretName\": {\n          \"@id\": \"certmgr:caSecretName\"\n        },\n        \"crlDistributionPoints\": {\n          \"@id\": \"sec:crlDistributionPoints\",\n          \"@container\": \"@set\"\n        },\n        \"ocspServers\": {\n          \"@id\": \"sec:ocspServers\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"CertificateRequest\": {\n      \"@id\": \"certmgr:CertificateRequest\",\n      \"@context\": {\n        \"spec\": {\n          \"@id\": \"certmgr:certificateRequestSpec\"\n        },\n        \"status\": {\n     \
  \     \"@id\": \"certmgr:certificateRequestStatus\"\n        }\n      }\n    },\n\n    \"CertificateRequestPolicy\": {\n      \"@id\": \"certmgr:CertificateRequestPolicy\",\n      \"@context\": {\n        \"spec\": {\n          \"@id\": \"certmgr:policySpec\"\n        },\n        \"status\": {\n          \"@id\": \"certmgr:policyStatus\"\n        }\n      }\n    },\n\n    \"ObjectReference\": {\n      \"@id\": \"k8s:ObjectReference\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\"\n        },\n        \"kind\": {\n          \"@id\": \"k8s:kind\"\n        },\n        \"group\": {\n          \"@id\": \"k8s:group\"\n        }\n      }\n    },\n\n    \"Condition\": {\n      \"@id\": \"k8s:Condition\",\n      \"@context\": {\n        \"type\": {\n          \"@id\": \"k8s:conditionType\"\n        },\n        \"status\": {\n          \"@id\": \"k8s:conditionStatus\"\n        },\n        \"reason\": {\n          \"@id\": \"k8s:conditionReason\"\n        },\n  \
  \      \"message\": {\n          \"@id\": \"schema:description\"\n        },\n        \"lastTransitionTime\": {\n          \"@id\": \"k8s:lastTransitionTime\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/cert-manager/refs/heads/main/json-ld/cert-manager-context.jsonld
tags:
- Certificates
- Cloud Native
- Graduated
- Kubernetes
- Security
- TLS
- JSON-LD
- Linked Data
- Semantic Web
---
