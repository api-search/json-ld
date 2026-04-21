---
class_count: 4
classes:
- name
- description
- created
- modified
context_file: json-ld/argo-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/argo/refs/heads/main/json-ld/argo-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Argo from Argo.
layout: jsonld
name: Argo Context
namespaces:
- prefix: argo
  uri: https://argoproj.github.io/argo-workflows/schema#
- prefix: argocd
  uri: https://argoproj.github.io/argo-cd/schema#
- prefix: k8s
  uri: https://kubernetes.io/docs/reference/generated/kubernetes-api/v1.28/#
- prefix: devops
  uri: https://w3id.org/devops#
- prefix: prov
  uri: http://www.w3.org/ns/prov#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: rdfs
  uri: http://www.w3.org/2000/01/rdf-schema#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: bpmn
  uri: http://www.omg.org/spec/BPMN/20100524/MODEL#
- prefix: ssn
  uri: http://www.w3.org/ns/ssn/
- prefix: wot
  uri: https://www.w3.org/2019/wot/td#
properties:
- container: ''
  name: Workflow
  type: reference
- container: ''
  name: WorkflowTemplate
  type: reference
- container: ''
  name: CronWorkflow
  type: reference
- container: ''
  name: Application
  type: reference
- container: ''
  name: ApplicationSet
  type: reference
- container: ''
  name: AppProject
  type: reference
- container: ''
  name: template
  type: reference
- container: ''
  name: entrypoint
  type: string
- container: ''
  name: steps
  type: reference
- container: ''
  name: dag
  type: reference
- container: ''
  name: dagTask
  type: reference
- container: ''
  name: dependencies
  type: reference
- container: ''
  name: container
  type: reference
- container: ''
  name: script
  type: reference
- container: ''
  name: resource
  type: reference
- container: ''
  name: artifact
  type: reference
- container: ''
  name: parameter
  type: reference
- container: ''
  name: retryStrategy
  type: reference
- container: ''
  name: source
  type: reference
- container: ''
  name: destination
  type: reference
- container: ''
  name: syncPolicy
  type: reference
- container: ''
  name: syncStatus
  type: string
- container: ''
  name: healthStatus
  type: string
- container: ''
  name: automatedSync
  type: reference
- container: ''
  name: selfHeal
  type: boolean
- container: ''
  name: prune
  type: boolean
- container: ''
  name: revision
  type: string
- container: ''
  name: namespace
  type: string
- container: ''
  name: cluster
  type: reference
- container: ''
  name: serviceAccountName
  type: string
- container: ''
  name: schedule
  type: string
- container: ''
  name: phase
  type: string
- container: ''
  name: startedAt
  type: dateTime
- container: ''
  name: finishedAt
  type: dateTime
- container: ''
  name: image
  type: string
- container: ''
  name: repoURL
  type: reference
- container: ''
  name: project
  type: string
property_count: 37
provider_name: Argo
provider_slug: argo
slug: argo-context
tags:
- CNCF
- CI/CD
- GitOps
- Kubernetes
- Open Source
- Progressive Delivery
- Workflow Engine
- JSON-LD
- Linked Data
- Semantic Web
---
