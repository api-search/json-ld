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
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"argo\": \"https://argoproj.github.io/argo-workflows/schema#\",\n    \"argocd\": \"https://argoproj.github.io/argo-cd/schema#\",\n    \"k8s\": \"https://kubernetes.io/docs/reference/generated/kubernetes-api/v1.28/#\",\n    \"devops\": \"https://w3id.org/devops#\",\n    \"prov\": \"http://www.w3.org/ns/prov#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"rdfs\": \"http://www.w3.org/2000/01/rdf-schema#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"bpmn\": \"http://www.omg.org/spec/BPMN/20100524/MODEL#\",\n    \"ssn\": \"http://www.w3.org/ns/ssn/\",\n    \"wot\": \"https://www.w3.org/2019/wot/td#\",\n\n    \"Workflow\": {\n      \"@id\": \"argo:Workflow\",\n      \"@type\": \"@id\",\n      \"rdfs:subClassOf\": \"bpmn:Process\",\n      \"rdfs:comment\": \"A Kubernetes-native workflow definition that orchestrates container execution as a sequence of steps or a directed acyclic graph\"\
  \n    },\n    \"WorkflowTemplate\": {\n      \"@id\": \"argo:WorkflowTemplate\",\n      \"@type\": \"@id\",\n      \"rdfs:subClassOf\": \"CreativeWork\",\n      \"rdfs:comment\": \"A reusable workflow definition that can be referenced by Workflows\"\n    },\n    \"CronWorkflow\": {\n      \"@id\": \"argo:CronWorkflow\",\n      \"@type\": \"@id\",\n      \"rdfs:subClassOf\": \"ScheduleAction\",\n      \"rdfs:comment\": \"A workflow scheduled to run on a cron-based time schedule\"\n    },\n    \"Application\": {\n      \"@id\": \"argocd:Application\",\n      \"@type\": \"@id\",\n      \"rdfs:subClassOf\": \"SoftwareApplication\",\n      \"rdfs:comment\": \"An Argo CD Application representing a deployed set of Kubernetes resources managed through GitOps\"\n    },\n    \"ApplicationSet\": {\n      \"@id\": \"argocd:ApplicationSet\",\n      \"@type\": \"@id\",\n      \"rdfs:subClassOf\": \"ItemList\",\n      \"rdfs:comment\": \"A template for generating multiple Argo CD Applications from a\
  \ single definition\"\n    },\n    \"AppProject\": {\n      \"@id\": \"argocd:AppProject\",\n      \"@type\": \"@id\",\n      \"rdfs:subClassOf\": \"Project\",\n      \"rdfs:comment\": \"An Argo CD project that provides logical grouping and access control for applications\"\n    },\n\n    \"template\": {\n      \"@id\": \"argo:template\",\n      \"@type\": \"@id\",\n      \"rdfs:comment\": \"A template defining a unit of execution within a workflow\"\n    },\n    \"entrypoint\": {\n      \"@id\": \"argo:entrypoint\",\n      \"@type\": \"xsd:string\",\n      \"rdfs:comment\": \"The name of the template used as the starting point of a workflow\"\n    },\n    \"steps\": {\n      \"@id\": \"argo:steps\",\n      \"@type\": \"@id\",\n      \"rdfs:subClassOf\": \"bpmn:SequenceFlow\",\n      \"rdfs:comment\": \"Sequential groups of parallel steps in a workflow\"\n    },\n    \"dag\": {\n      \"@id\": \"argo:dag\",\n      \"@type\": \"@id\",\n      \"rdfs:comment\": \"A directed acyclic graph\
  \ of tasks defining execution dependencies\"\n    },\n    \"dagTask\": {\n      \"@id\": \"argo:dagTask\",\n      \"@type\": \"@id\",\n      \"rdfs:subClassOf\": \"bpmn:Task\",\n      \"rdfs:comment\": \"A single task within a DAG template\"\n    },\n    \"dependencies\": {\n      \"@id\": \"argo:dependencies\",\n      \"@type\": \"@id\",\n      \"owl:sameAs\": \"prov:wasDerivedFrom\",\n      \"rdfs:comment\": \"Tasks that must complete before this task can execute\"\n    },\n    \"container\": {\n      \"@id\": \"argo:container\",\n      \"@type\": \"@id\",\n      \"rdfs:subClassOf\": \"k8s:Container\",\n      \"rdfs:comment\": \"Container specification for executing a workflow step\"\n    },\n    \"script\": {\n      \"@id\": \"argo:script\",\n      \"@type\": \"@id\",\n      \"rdfs:comment\": \"Inline script to execute in a container\"\n    },\n    \"resource\": {\n      \"@id\": \"argo:resource\",\n      \"@type\": \"@id\",\n      \"rdfs:comment\": \"Kubernetes resource to create,\
  \ patch, or delete\"\n    },\n    \"artifact\": {\n      \"@id\": \"argo:artifact\",\n      \"@type\": \"@id\",\n      \"owl:sameAs\": \"prov:Entity\",\n      \"rdfs:comment\": \"A data artifact passed between workflow steps\"\n    },\n    \"parameter\": {\n      \"@id\": \"argo:parameter\",\n      \"@type\": \"@id\",\n      \"rdfs:subClassOf\": \"PropertyValue\",\n      \"rdfs:comment\": \"A named parameter for passing values between workflow steps\"\n    },\n    \"retryStrategy\": {\n      \"@id\": \"argo:retryStrategy\",\n      \"@type\": \"@id\",\n      \"rdfs:comment\": \"Strategy defining how failed steps should be retried\"\n    },\n\n    \"source\": {\n      \"@id\": \"argocd:source\",\n      \"@type\": \"@id\",\n      \"rdfs:subClassOf\": \"codeRepository\",\n      \"rdfs:comment\": \"Git repository or Helm chart source for application manifests\"\n    },\n    \"destination\": {\n      \"@id\": \"argocd:destination\",\n      \"@type\": \"@id\",\n      \"rdfs:comment\": \"Target\
  \ Kubernetes cluster and namespace for deployment\"\n    },\n    \"syncPolicy\": {\n      \"@id\": \"argocd:syncPolicy\",\n      \"@type\": \"@id\",\n      \"rdfs:comment\": \"Policy controlling how and when application state is synced\"\n    },\n    \"syncStatus\": {\n      \"@id\": \"argocd:syncStatus\",\n      \"@type\": \"xsd:string\",\n      \"rdfs:comment\": \"Current sync status of the application (Synced, OutOfSync, Unknown)\"\n    },\n    \"healthStatus\": {\n      \"@id\": \"argocd:healthStatus\",\n      \"@type\": \"xsd:string\",\n      \"rdfs:comment\": \"Current health status of the application (Healthy, Degraded, Progressing, Missing)\"\n    },\n    \"automatedSync\": {\n      \"@id\": \"argocd:automatedSync\",\n      \"@type\": \"@id\",\n      \"rdfs:comment\": \"Configuration for automatic synchronization of application state\"\n    },\n    \"selfHeal\": {\n      \"@id\": \"argocd:selfHeal\",\n      \"@type\": \"xsd:boolean\",\n      \"rdfs:comment\": \"Whether Argo CD\
  \ automatically corrects drift from desired state\"\n    },\n    \"prune\": {\n      \"@id\": \"argocd:prune\",\n      \"@type\": \"xsd:boolean\",\n      \"rdfs:comment\": \"Whether to delete resources no longer defined in the source\"\n    },\n    \"revision\": {\n      \"@id\": \"argocd:revision\",\n      \"@type\": \"xsd:string\",\n      \"owl:sameAs\": \"dcterms:hasVersion\",\n      \"rdfs:comment\": \"Git commit SHA, branch, or tag being deployed\"\n    },\n\n    \"namespace\": {\n      \"@id\": \"k8s:namespace\",\n      \"@type\": \"xsd:string\",\n      \"rdfs:comment\": \"Kubernetes namespace for the resource\"\n    },\n    \"cluster\": {\n      \"@id\": \"k8s:cluster\",\n      \"@type\": \"@id\",\n      \"rdfs:comment\": \"Target Kubernetes cluster for deployment\"\n    },\n    \"serviceAccountName\": {\n      \"@id\": \"k8s:serviceAccountName\",\n      \"@type\": \"xsd:string\",\n      \"rdfs:comment\": \"Kubernetes service account for running pods\"\n    },\n\n    \"schedule\"\
  : {\n      \"@id\": \"argo:schedule\",\n      \"@type\": \"xsd:string\",\n      \"rdfs:comment\": \"Cron expression defining when a CronWorkflow runs\"\n    },\n    \"phase\": {\n      \"@id\": \"argo:phase\",\n      \"@type\": \"xsd:string\",\n      \"rdfs:comment\": \"Current execution phase (Pending, Running, Succeeded, Failed, Error)\"\n    },\n    \"startedAt\": {\n      \"@id\": \"argo:startedAt\",\n      \"@type\": \"xsd:dateTime\",\n      \"owl:sameAs\": \"prov:startedAtTime\",\n      \"rdfs:comment\": \"Timestamp when the workflow or step started execution\"\n    },\n    \"finishedAt\": {\n      \"@id\": \"argo:finishedAt\",\n      \"@type\": \"xsd:dateTime\",\n      \"owl:sameAs\": \"prov:endedAtTime\",\n      \"rdfs:comment\": \"Timestamp when the workflow or step finished execution\"\n    },\n    \"image\": {\n      \"@id\": \"argo:image\",\n      \"@type\": \"xsd:string\",\n      \"owl:sameAs\": \"SoftwareApplication\",\n      \"rdfs:comment\": \"Container image reference\
  \ for executing a step\"\n    },\n\n    \"name\": \"rdfs:label\",\n    \"description\": \"rdfs:comment\",\n    \"created\": \"dcterms:created\",\n    \"modified\": \"dcterms:modified\",\n    \"repoURL\": {\n      \"@id\": \"codeRepository\",\n      \"@type\": \"@id\"\n    },\n    \"project\": {\n      \"@id\": \"argocd:project\",\n      \"@type\": \"xsd:string\",\n      \"rdfs:comment\": \"Argo CD project providing governance and access control\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/argo/refs/heads/main/json-ld/argo-context.jsonld
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
