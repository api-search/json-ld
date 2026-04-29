---
class_count: 20
classes:
- v1LabelSelector
- v1ListMeta
- v1ObjectMeta
- v1EventSource
- v1FieldsV1
- v1EventList
- v1LoadBalancerIngress
- v1Event
- v1EventSeries
- v1JSON
- v1NodeSystemInfo
- v1ManagedFieldsEntry
- v1PortStatus
- v1LabelSelectorRequirement
- v1NodeSwapStatus
- v1MicroTime
- v1OwnerReference
- v1ObjectReference
- v1GroupKind
- name
context_file: json-ld/argo-cd-v1-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/argo-cd/refs/heads/main/json-ld/argo-cd-v1-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Argo Cd V1 from Argo CD.
layout: jsonld
name: Argo Cd V1 Context
namespaces:
- prefix: argocd
  uri: https://argoproj.github.io/schema/argo-cd/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: set
  name: matchExpressions
  type: string
- container: ''
  name: matchLabels
  type: reference
- container: ''
  name: continue
  type: string
- container: ''
  name: remainingItemCount
  type: integer
- container: ''
  name: resourceVersion
  type: string
- container: ''
  name: selfLink
  type: string
- container: ''
  name: annotations
  type: reference
- container: ''
  name: creationTimestamp
  type: string
- container: ''
  name: deletionGracePeriodSeconds
  type: integer
- container: ''
  name: deletionTimestamp
  type: string
- container: set
  name: finalizers
  type: string
- container: ''
  name: generateName
  type: string
- container: ''
  name: generation
  type: integer
- container: ''
  name: labels
  type: reference
- container: set
  name: managedFields
  type: string
- container: ''
  name: namespace
  type: string
- container: set
  name: ownerReferences
  type: string
- container: ''
  name: uid
  type: string
- container: ''
  name: component
  type: string
- container: ''
  name: host
  type: string
- container: ''
  name: Raw
  type: string
- container: set
  name: items
  type: string
- container: ''
  name: metadata
  type: string
- container: ''
  name: hostname
  type: string
- container: ''
  name: ip
  type: string
- container: ''
  name: ipMode
  type: string
- container: set
  name: ports
  type: string
- container: ''
  name: action
  type: string
- container: ''
  name: count
  type: integer
- container: ''
  name: eventTime
  type: string
- container: ''
  name: firstTimestamp
  type: string
- container: ''
  name: involvedObject
  type: string
- container: ''
  name: lastTimestamp
  type: string
- container: ''
  name: message
  type: string
- container: ''
  name: reason
  type: string
- container: ''
  name: related
  type: string
- container: ''
  name: reportingComponent
  type: string
- container: ''
  name: reportingInstance
  type: string
- container: ''
  name: series
  type: string
- container: ''
  name: source
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: lastObservedTime
  type: string
- container: ''
  name: raw
  type: string
- container: ''
  name: architecture
  type: string
- container: ''
  name: bootID
  type: string
- container: ''
  name: containerRuntimeVersion
  type: string
- container: ''
  name: kernelVersion
  type: string
- container: ''
  name: kubeProxyVersion
  type: string
- container: ''
  name: kubeletVersion
  type: string
- container: ''
  name: machineID
  type: string
- container: ''
  name: operatingSystem
  type: string
- container: ''
  name: osImage
  type: string
- container: ''
  name: swap
  type: string
- container: ''
  name: systemUUID
  type: string
- container: ''
  name: apiVersion
  type: string
- container: ''
  name: fieldsType
  type: string
- container: ''
  name: fieldsV1
  type: string
- container: ''
  name: manager
  type: string
- container: ''
  name: operation
  type: string
- container: ''
  name: subresource
  type: string
- container: ''
  name: time
  type: string
- container: ''
  name: error
  type: string
- container: ''
  name: port
  type: integer
- container: ''
  name: protocol
  type: string
- container: ''
  name: key
  type: string
- container: ''
  name: operator
  type: string
- container: set
  name: values
  type: string
- container: ''
  name: capacity
  type: integer
- container: ''
  name: nanos
  type: integer
- container: ''
  name: seconds
  type: integer
- container: ''
  name: blockOwnerDeletion
  type: boolean
- container: ''
  name: controller
  type: boolean
- container: ''
  name: kind
  type: string
- container: ''
  name: fieldPath
  type: string
- container: ''
  name: group
  type: string
property_count: 75
provider_name: Argo CD
provider_slug: argo-cd
slug: argo-cd-v1-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"argocd\": \"https://argoproj.github.io/schema/argo-cd/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"v1LabelSelector\": \"argocd:v1LabelSelector\",\n    \"v1ListMeta\": \"argocd:v1ListMeta\",\n    \"v1ObjectMeta\": \"argocd:v1ObjectMeta\",\n    \"v1EventSource\": \"argocd:v1EventSource\",\n    \"v1FieldsV1\": \"argocd:v1FieldsV1\",\n    \"v1EventList\": \"argocd:v1EventList\",\n    \"v1LoadBalancerIngress\": \"argocd:v1LoadBalancerIngress\",\n    \"v1Event\": \"argocd:v1Event\",\n    \"v1EventSeries\": \"argocd:v1EventSeries\",\n    \"v1JSON\": \"argocd:v1JSON\",\n    \"v1NodeSystemInfo\": \"argocd:v1NodeSystemInfo\",\n    \"v1ManagedFieldsEntry\": \"argocd:v1ManagedFieldsEntry\",\n    \"v1PortStatus\": \"argocd:v1PortStatus\",\n    \"v1LabelSelectorRequirement\": \"argocd:v1LabelSelectorRequirement\",\n    \"v1NodeSwapStatus\"\
  : \"argocd:v1NodeSwapStatus\",\n    \"v1MicroTime\": \"argocd:v1MicroTime\",\n    \"v1OwnerReference\": \"argocd:v1OwnerReference\",\n    \"v1ObjectReference\": \"argocd:v1ObjectReference\",\n    \"v1GroupKind\": \"argocd:v1GroupKind\",\n    \"matchExpressions\": {\n      \"@id\": \"argocd:matchExpressions\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"matchLabels\": {\n      \"@id\": \"argocd:matchLabels\",\n      \"@type\": \"@id\"\n    },\n    \"continue\": {\n      \"@id\": \"argocd:continue\",\n      \"@type\": \"xsd:string\"\n    },\n    \"remainingItemCount\": {\n      \"@id\": \"argocd:remainingItemCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"resourceVersion\": {\n      \"@id\": \"argocd:resourceVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"selfLink\": {\n      \"@id\": \"argocd:selfLink\",\n      \"@type\": \"xsd:string\"\n    },\n    \"annotations\": {\n      \"@id\": \"argocd:annotations\",\n      \"@type\": \"@id\"\
  \n    },\n    \"creationTimestamp\": {\n      \"@id\": \"argocd:creationTimestamp\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deletionGracePeriodSeconds\": {\n      \"@id\": \"argocd:deletionGracePeriodSeconds\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"deletionTimestamp\": {\n      \"@id\": \"argocd:deletionTimestamp\",\n      \"@type\": \"xsd:string\"\n    },\n    \"finalizers\": {\n      \"@id\": \"argocd:finalizers\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"generateName\": {\n      \"@id\": \"argocd:generateName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"generation\": {\n      \"@id\": \"argocd:generation\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"labels\": {\n      \"@id\": \"argocd:labels\",\n      \"@type\": \"@id\"\n    },\n    \"managedFields\": {\n      \"@id\": \"argocd:managedFields\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"namespace\"\
  : {\n      \"@id\": \"argocd:namespace\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ownerReferences\": {\n      \"@id\": \"argocd:ownerReferences\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"uid\": {\n      \"@id\": \"argocd:uid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"component\": {\n      \"@id\": \"argocd:component\",\n      \"@type\": \"xsd:string\"\n    },\n    \"host\": {\n      \"@id\": \"argocd:host\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Raw\": {\n      \"@id\": \"argocd:Raw\",\n      \"@type\": \"xsd:string\"\n    },\n    \"items\": {\n      \"@id\": \"argocd:items\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"metadata\": {\n      \"@id\": \"argocd:metadata\",\n      \"@type\": \"xsd:string\"\n    },\n    \"hostname\": {\n      \"@id\": \"argocd:hostname\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ip\": {\n      \"@id\": \"argocd:ip\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"ipMode\": {\n      \"@id\": \"argocd:ipMode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ports\": {\n      \"@id\": \"argocd:ports\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"action\": {\n      \"@id\": \"argocd:action\",\n      \"@type\": \"xsd:string\"\n    },\n    \"count\": {\n      \"@id\": \"argocd:count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"eventTime\": {\n      \"@id\": \"argocd:eventTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"firstTimestamp\": {\n      \"@id\": \"argocd:firstTimestamp\",\n      \"@type\": \"xsd:string\"\n    },\n    \"involvedObject\": {\n      \"@id\": \"argocd:involvedObject\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastTimestamp\": {\n      \"@id\": \"argocd:lastTimestamp\",\n      \"@type\": \"xsd:string\"\n    },\n    \"message\": {\n      \"@id\": \"argocd:message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reason\": {\n      \"@id\": \"argocd:reason\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"related\": {\n      \"@id\": \"argocd:related\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reportingComponent\": {\n      \"@id\": \"argocd:reportingComponent\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reportingInstance\": {\n      \"@id\": \"argocd:reportingInstance\",\n      \"@type\": \"xsd:string\"\n    },\n    \"series\": {\n      \"@id\": \"argocd:series\",\n      \"@type\": \"xsd:string\"\n    },\n    \"source\": {\n      \"@id\": \"argocd:source\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"argocd:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastObservedTime\": {\n      \"@id\": \"argocd:lastObservedTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"raw\": {\n      \"@id\": \"argocd:raw\",\n      \"@type\": \"xsd:string\"\n    },\n    \"architecture\": {\n      \"@id\": \"argocd:architecture\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bootID\": {\n      \"@id\"\
  : \"argocd:bootID\",\n      \"@type\": \"xsd:string\"\n    },\n    \"containerRuntimeVersion\": {\n      \"@id\": \"argocd:containerRuntimeVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"kernelVersion\": {\n      \"@id\": \"argocd:kernelVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"kubeProxyVersion\": {\n      \"@id\": \"argocd:kubeProxyVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"kubeletVersion\": {\n      \"@id\": \"argocd:kubeletVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"machineID\": {\n      \"@id\": \"argocd:machineID\",\n      \"@type\": \"xsd:string\"\n    },\n    \"operatingSystem\": {\n      \"@id\": \"argocd:operatingSystem\",\n      \"@type\": \"xsd:string\"\n    },\n    \"osImage\": {\n      \"@id\": \"argocd:osImage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"swap\": {\n      \"@id\": \"argocd:swap\",\n      \"@type\": \"xsd:string\"\n    },\n    \"systemUUID\": {\n      \"@id\": \"argocd:systemUUID\",\n      \"\
  @type\": \"xsd:string\"\n    },\n    \"apiVersion\": {\n      \"@id\": \"argocd:apiVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fieldsType\": {\n      \"@id\": \"argocd:fieldsType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fieldsV1\": {\n      \"@id\": \"argocd:fieldsV1\",\n      \"@type\": \"xsd:string\"\n    },\n    \"manager\": {\n      \"@id\": \"argocd:manager\",\n      \"@type\": \"xsd:string\"\n    },\n    \"operation\": {\n      \"@id\": \"argocd:operation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subresource\": {\n      \"@id\": \"argocd:subresource\",\n      \"@type\": \"xsd:string\"\n    },\n    \"time\": {\n      \"@id\": \"argocd:time\",\n      \"@type\": \"xsd:string\"\n    },\n    \"error\": {\n      \"@id\": \"argocd:error\",\n      \"@type\": \"xsd:string\"\n    },\n    \"port\": {\n      \"@id\": \"argocd:port\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"protocol\": {\n      \"@id\": \"argocd:protocol\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"key\": {\n      \"@id\": \"argocd:key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"operator\": {\n      \"@id\": \"argocd:operator\",\n      \"@type\": \"xsd:string\"\n    },\n    \"values\": {\n      \"@id\": \"argocd:values\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"capacity\": {\n      \"@id\": \"argocd:capacity\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"nanos\": {\n      \"@id\": \"argocd:nanos\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"seconds\": {\n      \"@id\": \"argocd:seconds\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"blockOwnerDeletion\": {\n      \"@id\": \"argocd:blockOwnerDeletion\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"controller\": {\n      \"@id\": \"argocd:controller\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"kind\": {\n      \"@id\": \"argocd:kind\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fieldPath\": {\n      \"@id\": \"argocd:fieldPath\",\n      \"\
  @type\": \"xsd:string\"\n    },\n    \"group\": {\n      \"@id\": \"argocd:group\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/argo-cd/refs/heads/main/json-ld/argo-cd-v1-context.jsonld
tags:
- Continuous Delivery
- Containers
- Deployment
- GitOps
- Kubernetes
- CNCF
- Open Source
- JSON-LD
- Linked Data
- Semantic Web
---
