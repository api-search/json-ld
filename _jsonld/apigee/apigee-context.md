---
class_count: 0
classes: []
context_file: json-ld/apigee-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apigee/refs/heads/main/json-ld/apigee-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apigee from Apigee.
layout: jsonld
name: Apigee Context
namespaces:
- prefix: apigee
  uri: https://cloud.google.com/apigee/docs/reference/apis/apigee/rest/v1/
- prefix: apihub
  uri: https://cloud.google.com/apigee/docs/reference/apis/apihub/rest/v1/
- prefix: gcp
  uri: https://cloud.google.com/apis/design/
- prefix: iana
  uri: https://www.iana.org/assignments/link-relations/
- prefix: hydra
  uri: http://www.w3.org/ns/hydra/core#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: foaf
  uri: http://xmlns.com/foaf/0.1/
- prefix: vcard
  uri: http://www.w3.org/2006/vcard/ns#
properties:
- container: ''
  name: Organization
  type: ''
- container: ''
  name: ApiProxy
  type: ''
- container: ''
  name: ApiProduct
  type: ''
- container: ''
  name: Developer
  type: ''
- container: ''
  name: DeveloperApp
  type: ''
- container: ''
  name: Environment
  type: ''
- container: ''
  name: Deployment
  type: ''
- container: ''
  name: SharedFlow
  type: ''
- container: ''
  name: TargetServer
  type: ''
- container: ''
  name: KeyValueMap
  type: ''
- container: ''
  name: Integration
  type: ''
- container: ''
  name: ApiObservation
  type: ''
- container: ''
  name: Artifact
  type: ''
- container: ''
  name: Instance
  type: ''
property_count: 14
provider_name: Apigee
provider_slug: apigee
slug: apigee-context
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"apigee\": \"https://cloud.google.com/apigee/docs/reference/apis/apigee/rest/v1/\",\n    \"apihub\": \"https://cloud.google.com/apigee/docs/reference/apis/apihub/rest/v1/\",\n    \"gcp\": \"https://cloud.google.com/apis/design/\",\n    \"iana\": \"https://www.iana.org/assignments/link-relations/\",\n    \"hydra\": \"http://www.w3.org/ns/hydra/core#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"foaf\": \"http://xmlns.com/foaf/0.1/\",\n    \"vcard\": \"http://www.w3.org/2006/vcard/ns#\",\n\n    \"Organization\": {\n      \"@id\": \"schema:Organization\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"displayName\": \"schema:alternateName\",\n        \"description\": \"schema:description\",\n        \"projectId\": \"schema:identifier\",\n        \"createdAt\": \"schema:dateCreated\",\n        \"lastModifiedAt\": \"schema:dateModified\",\n        \"state\": \"schema:status\"\
  ,\n        \"analyticsRegion\": \"schema:areaServed\",\n        \"environments\": \"schema:hasPart\",\n        \"billingType\": \"schema:paymentAccepted\"\n      }\n    },\n\n    \"ApiProxy\": {\n      \"@id\": \"schema:WebAPI\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"revision\": \"schema:version\",\n        \"latestRevisionId\": \"schema:softwareVersion\",\n        \"labels\": \"schema:keywords\",\n        \"apiProxyType\": \"schema:applicationCategory\",\n        \"createdAt\": \"schema:dateCreated\",\n        \"lastModifiedAt\": \"schema:dateModified\"\n      }\n    },\n\n    \"ApiProduct\": {\n      \"@id\": \"schema:Product\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"displayName\": \"schema:alternateName\",\n        \"description\": \"schema:description\",\n        \"approvalType\": \"schema:availability\",\n        \"environments\": \"schema:areaServed\",\n        \"proxies\"\
  : \"schema:hasPart\",\n        \"scopes\": \"schema:permissionType\",\n        \"quota\": \"schema:inventoryLevel\",\n        \"quotaInterval\": \"schema:repeatFrequency\",\n        \"quotaTimeUnit\": \"schema:duration\",\n        \"createdAt\": \"schema:dateCreated\",\n        \"lastModifiedAt\": \"schema:dateModified\"\n      }\n    },\n\n    \"Developer\": {\n      \"@id\": \"foaf:Person\",\n      \"@context\": {\n        \"email\": \"schema:email\",\n        \"firstName\": \"schema:givenName\",\n        \"lastName\": \"schema:familyName\",\n        \"userName\": \"foaf:accountName\",\n        \"developerId\": \"schema:identifier\",\n        \"organizationName\": \"schema:memberOf\",\n        \"status\": \"schema:status\",\n        \"apps\": \"schema:owns\",\n        \"companies\": \"schema:worksFor\",\n        \"createdAt\": \"schema:dateCreated\",\n        \"lastModifiedAt\": \"schema:dateModified\"\n      }\n    },\n\n    \"DeveloperApp\": {\n      \"@id\": \"schema:SoftwareApplication\"\
  ,\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"appId\": \"schema:identifier\",\n        \"developerId\": \"schema:author\",\n        \"apiProducts\": \"schema:isPartOf\",\n        \"callbackUrl\": \"schema:url\",\n        \"status\": \"schema:creativeWorkStatus\",\n        \"scopes\": \"schema:permissionType\",\n        \"createdAt\": \"schema:dateCreated\",\n        \"lastModifiedAt\": \"schema:dateModified\"\n      }\n    },\n\n    \"Environment\": {\n      \"@id\": \"schema:Place\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"displayName\": \"schema:alternateName\",\n        \"description\": \"schema:description\",\n        \"state\": \"schema:status\",\n        \"deploymentType\": \"schema:additionalType\",\n        \"createdAt\": \"schema:dateCreated\",\n        \"lastModifiedAt\": \"schema:dateModified\"\n      }\n    },\n\n    \"Deployment\": {\n      \"@id\": \"schema:DeployAction\",\n      \"@context\": {\n        \"environment\"\
  : \"schema:location\",\n        \"apiProxy\": \"schema:object\",\n        \"revision\": \"schema:version\",\n        \"deployStartTime\": \"schema:startTime\",\n        \"state\": \"schema:actionStatus\"\n      }\n    },\n\n    \"SharedFlow\": {\n      \"@id\": \"schema:SoftwareSourceCode\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"revision\": \"schema:version\",\n        \"latestRevisionId\": \"schema:softwareVersion\",\n        \"createdAt\": \"schema:dateCreated\",\n        \"lastModifiedAt\": \"schema:dateModified\"\n      }\n    },\n\n    \"TargetServer\": {\n      \"@id\": \"schema:WebAPI\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"host\": \"schema:url\",\n        \"port\": \"schema:identifier\",\n        \"isEnabled\": \"schema:status\",\n        \"protocol\": \"schema:applicationCategory\",\n        \"description\": \"schema:description\"\n      }\n    },\n\n    \"KeyValueMap\": {\n      \"@id\": \"schema:DataCatalog\",\n\
  \      \"@context\": {\n        \"name\": \"schema:name\",\n        \"encrypted\": \"schema:accessMode\"\n      }\n    },\n\n    \"Integration\": {\n      \"@id\": \"schema:SoftwareApplication\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"state\": \"schema:creativeWorkStatus\",\n        \"createTime\": \"schema:dateCreated\",\n        \"lastModifierEmail\": \"schema:editor\"\n      }\n    },\n\n    \"ApiObservation\": {\n      \"@id\": \"schema:Observation\",\n      \"@context\": {\n        \"hostname\": \"schema:url\",\n        \"serverIps\": \"schema:identifier\",\n        \"requestCount\": \"schema:interactionCount\",\n        \"lastEventDetectedTime\": \"schema:dateModified\",\n        \"firstEventDetectedTime\": \"schema:dateCreated\",\n        \"style\": \"schema:additionalType\",\n        \"tags\": \"schema:keywords\"\n      }\n    },\n\n    \"Artifact\": {\n      \"@id\": \"schema:DigitalDocument\",\n\
  \      \"@context\": {\n        \"name\": \"schema:name\",\n        \"mimeType\": \"schema:encodingFormat\",\n        \"sizeBytes\": \"schema:contentSize\",\n        \"hash\": \"schema:sha256\",\n        \"createTime\": \"schema:dateCreated\",\n        \"updateTime\": \"schema:dateModified\"\n      }\n    },\n\n    \"Instance\": {\n      \"@id\": \"schema:SoftwareApplication\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"location\": \"schema:contentLocation\",\n        \"host\": \"schema:url\",\n        \"state\": \"schema:status\",\n        \"description\": \"schema:description\",\n        \"displayName\": \"schema:alternateName\",\n        \"createdAt\": \"schema:dateCreated\",\n        \"lastModifiedAt\": \"schema:dateModified\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/apigee/refs/heads/main/json-ld/apigee-context.jsonld
tags:
- Analytics
- API Gateway
- API Governance
- API Hub
- API Management
- Developer Portal
- Enterprise
- Hybrid
- Integrations
- Microservices
- Monetization
- JSON-LD
- Linked Data
- Semantic Web
---
