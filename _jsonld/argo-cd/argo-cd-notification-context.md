---
class_count: 7
classes:
- notificationTrigger
- notificationServiceList
- notificationTemplateList
- notificationService
- notificationTemplate
- notificationTriggerList
- name
context_file: json-ld/argo-cd-notification-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/argo-cd/refs/heads/main/json-ld/argo-cd-notification-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Argo Cd Notification from Argo CD.
layout: jsonld
name: Argo Cd Notification Context
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
  name: items
  type: string
property_count: 1
provider_name: Argo CD
provider_slug: argo-cd
slug: argo-cd-notification-context
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
