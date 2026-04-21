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
