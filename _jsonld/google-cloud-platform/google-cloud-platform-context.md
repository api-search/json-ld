---
api_specs:
- filename: cloud-resource-manager-openapi.yml
  format: yaml
  label: Google Cloud Resource Manager API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-cloud-platform/refs/heads/main/openapi/cloud-resource-manager-openapi.yml
class_count: 0
classes: []
context_file: json-ld/google-cloud-platform-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-cloud-platform/refs/heads/main/json-ld/google-cloud-platform-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Google Cloud Platform from Google Cloud Platform.
layout: jsonld
name: Google Cloud Platform Context
namespaces:
- prefix: gcp
  uri: https://cloud.google.com/resource-manager/reference/rest/v3/
- prefix: gcpiam
  uri: https://cloud.google.com/iam/docs/reference/rest/v1/
- prefix: gcptags
  uri: https://cloud.google.com/resource-manager/reference/rest/v3/tagKeys/
- prefix: crm
  uri: https://cloudresourcemanager.googleapis.com/v3/
- prefix: iam
  uri: https://iam.googleapis.com/v1/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: foaf
  uri: http://xmlns.com/foaf/0.1/
- prefix: skos
  uri: http://www.w3.org/2004/02/skos/core#
- prefix: rdfs
  uri: http://www.w3.org/2000/01/rdf-schema#
properties:
- container: ''
  name: Project
  type: ''
- container: ''
  name: Folder
  type: ''
- container: ''
  name: Organization
  type: ''
- container: ''
  name: IamPolicy
  type: ''
- container: ''
  name: Binding
  type: ''
- container: ''
  name: Condition
  type: ''
- container: ''
  name: TagKey
  type: ''
- container: ''
  name: TagValue
  type: ''
- container: ''
  name: TagBinding
  type: ''
- container: ''
  name: ResourceHierarchy
  type: ''
- container: ''
  name: CloudService
  type: ''
- container: ''
  name: BillingAccount
  type: ''
- container: ''
  name: ServiceAccount
  type: ''
- container: ''
  name: projectId
  type: string
- container: ''
  name: displayName
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: createTime
  type: dateTime
- container: ''
  name: updateTime
  type: dateTime
- container: ''
  name: state
  type: string
- container: index
  name: labels
  type: ''
- container: ''
  name: parent
  type: reference
- container: ''
  name: etag
  type: string
property_count: 22
provider_name: Google Cloud Platform
provider_slug: google-cloud-platform
slug: google-cloud-platform-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"@vocab\": \"https://schema.org/\",\n    \"gcp\": \"https://cloud.google.com/resource-manager/reference/rest/v3/\",\n    \"gcpiam\": \"https://cloud.google.com/iam/docs/reference/rest/v1/\",\n    \"gcptags\": \"https://cloud.google.com/resource-manager/reference/rest/v3/tagKeys/\",\n    \"crm\": \"https://cloudresourcemanager.googleapis.com/v3/\",\n    \"iam\": \"https://iam.googleapis.com/v1/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"foaf\": \"http://xmlns.com/foaf/0.1/\",\n    \"skos\": \"http://www.w3.org/2004/02/skos/core#\",\n    \"rdfs\": \"http://www.w3.org/2000/01/rdf-schema#\",\n\n    \"Project\": {\n      \"@id\": \"gcp:projects\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"gcp:projects#name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"projectId\": {\n          \"\
  @id\": \"gcp:projects#projectId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"displayName\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"parent\": {\n          \"@id\": \"gcp:projects#parent\",\n          \"@type\": \"@id\"\n        },\n        \"state\": {\n          \"@id\": \"gcp:projects#state\",\n          \"@type\": \"xsd:string\"\n        },\n        \"createTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updateTime\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"deleteTime\": {\n          \"@id\": \"gcp:projects#deleteTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"etag\": {\n          \"@id\": \"gcp:projects#etag\",\n          \"@type\": \"xsd:string\"\n        },\n        \"labels\": {\n          \"@id\": \"gcp:projects#labels\",\n          \"@container\": \"\
  @index\"\n        }\n      }\n    },\n\n    \"Folder\": {\n      \"@id\": \"gcp:folders\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"gcp:folders#name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"displayName\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"parent\": {\n          \"@id\": \"gcp:folders#parent\",\n          \"@type\": \"@id\"\n        },\n        \"state\": {\n          \"@id\": \"gcp:folders#state\",\n          \"@type\": \"xsd:string\"\n        },\n        \"createTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updateTime\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"deleteTime\": {\n          \"@id\": \"gcp:folders#deleteTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"etag\": {\n          \"@id\": \"gcp:folders#etag\",\n       \
  \   \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"Organization\": {\n      \"@id\": \"gcp:organizations\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"gcp:organizations#name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"displayName\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"directoryCustomerId\": {\n          \"@id\": \"gcp:organizations#directoryCustomerId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"state\": {\n          \"@id\": \"gcp:organizations#state\",\n          \"@type\": \"xsd:string\"\n        },\n        \"createTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updateTime\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"deleteTime\": {\n          \"@id\": \"gcp:organizations#deleteTime\",\n          \"@type\": \"xsd:dateTime\"\
  \n        },\n        \"etag\": {\n          \"@id\": \"gcp:organizations#etag\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"IamPolicy\": {\n      \"@id\": \"gcpiam:Policy\",\n      \"@context\": {\n        \"version\": {\n          \"@id\": \"gcpiam:Policy#version\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"bindings\": {\n          \"@id\": \"gcpiam:Policy#bindings\",\n          \"@container\": \"@set\"\n        },\n        \"etag\": {\n          \"@id\": \"gcpiam:Policy#etag\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"Binding\": {\n      \"@id\": \"gcpiam:Binding\",\n      \"@context\": {\n        \"role\": {\n          \"@id\": \"gcpiam:Binding#role\",\n          \"@type\": \"xsd:string\"\n        },\n        \"members\": {\n          \"@id\": \"gcpiam:Binding#members\",\n          \"@container\": \"@set\"\n        },\n        \"condition\": {\n          \"@id\": \"gcpiam:Binding#condition\",\n     \
  \     \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Condition\": {\n      \"@id\": \"gcpiam:Expr\",\n      \"@context\": {\n        \"expression\": {\n          \"@id\": \"gcpiam:Expr#expression\",\n          \"@type\": \"xsd:string\"\n        },\n        \"title\": {\n          \"@id\": \"gcpiam:Expr#title\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"gcpiam:Expr#description\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"TagKey\": {\n      \"@id\": \"gcptags:TagKey\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"gcptags:TagKey#name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"parent\": {\n          \"@id\": \"gcptags:TagKey#parent\",\n          \"@type\": \"@id\"\n        },\n        \"shortName\": {\n          \"@id\": \"gcptags:TagKey#shortName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"namespacedName\": {\n          \"@id\": \"gcptags:TagKey#namespacedName\"\
  ,\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"dcterms:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"createTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updateTime\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"TagValue\": {\n      \"@id\": \"gcptags:TagValue\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"gcptags:TagValue#name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"parent\": {\n          \"@id\": \"gcptags:TagValue#parent\",\n          \"@type\": \"@id\"\n        },\n        \"shortName\": {\n          \"@id\": \"gcptags:TagValue#shortName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"namespacedName\": {\n          \"@id\": \"gcptags:TagValue#namespacedName\",\n          \"@type\": \"xsd:string\"\n   \
  \     },\n        \"description\": {\n          \"@id\": \"dcterms:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"createTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updateTime\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"TagBinding\": {\n      \"@id\": \"gcptags:TagBinding\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"gcptags:TagBinding#name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"parent\": {\n          \"@id\": \"gcptags:TagBinding#parent\",\n          \"@type\": \"@id\"\n        },\n        \"tagValue\": {\n          \"@id\": \"gcptags:TagBinding#tagValue\",\n          \"@type\": \"@id\"\n        },\n        \"tagValueNamespacedName\": {\n          \"@id\": \"gcptags:TagBinding#tagValueNamespacedName\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\
  \n    \"ResourceHierarchy\": {\n      \"@id\": \"gcp:ResourceHierarchy\",\n      \"@context\": {\n        \"organization\": {\n          \"@id\": \"gcp:ResourceHierarchy#organization\",\n          \"@type\": \"@id\"\n        },\n        \"folders\": {\n          \"@id\": \"gcp:ResourceHierarchy#folders\",\n          \"@container\": \"@set\"\n        },\n        \"projects\": {\n          \"@id\": \"gcp:ResourceHierarchy#projects\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"CloudService\": {\n      \"@id\": \"schema:WebAPI\",\n      \"@context\": {\n        \"serviceName\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"serviceEndpoint\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"documentation\": {\n          \"@id\": \"schema:documentation\",\n          \"@type\": \"@id\"\n        },\n        \"provider\": {\n          \"@id\": \"schema:provider\",\n     \
  \     \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"BillingAccount\": {\n      \"@id\": \"gcp:BillingAccount\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"gcp:BillingAccount#name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"displayName\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"open\": {\n          \"@id\": \"gcp:BillingAccount#open\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"masterBillingAccount\": {\n          \"@id\": \"gcp:BillingAccount#masterBillingAccount\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"ServiceAccount\": {\n      \"@id\": \"gcpiam:ServiceAccount\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"gcpiam:ServiceAccount#name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"email\": {\n          \"@id\": \"schema:email\",\n          \"@type\": \"xsd:string\"\n        },\n       \
  \ \"displayName\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"uniqueId\": {\n          \"@id\": \"gcpiam:ServiceAccount#uniqueId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"disabled\": {\n          \"@id\": \"gcpiam:ServiceAccount#disabled\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"description\": {\n          \"@id\": \"dcterms:description\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"projectId\": {\n      \"@id\": \"gcp:projects#projectId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"displayName\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"dcterms:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createTime\": {\n      \"@id\": \"dcterms:created\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updateTime\": {\n      \"@id\": \"dcterms:modified\",\n      \"@type\"\
  : \"xsd:dateTime\"\n    },\n    \"state\": {\n      \"@id\": \"gcp:state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"labels\": {\n      \"@id\": \"gcp:labels\",\n      \"@container\": \"@index\"\n    },\n    \"parent\": {\n      \"@id\": \"gcp:parent\",\n      \"@type\": \"@id\"\n    },\n    \"etag\": {\n      \"@id\": \"gcp:etag\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-cloud-platform/refs/heads/main/json-ld/google-cloud-platform-context.jsonld
tags:
- API Management
- Cloud Computing
- Infrastructure
- Platform as a Service
- JSON-LD
- Linked Data
- Semantic Web
---
