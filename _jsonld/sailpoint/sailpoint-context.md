---
api_specs:
- filename: openapi.yaml
  format: yaml
  label: SailPoint Identity Security Cloud V3 API
  slug: identity-security-cloud-v3-api
  spec_type: OpenAPI
  url: https://developer.sailpoint.com/docs/api/v3/identity-security-cloud-v-3-api/
- filename: openapi.yaml
  format: yaml
  label: SailPoint Identity Security Cloud V2024 API
  slug: identity-security-cloud-v2024-api
  spec_type: OpenAPI
  url: https://developer.sailpoint.com/docs/api/v2024/identity-security-cloud-v-2024-api/
- filename: openapi.yaml
  format: yaml
  label: SailPoint Identity Security Cloud V2025 API
  slug: identity-security-cloud-v2025-api
  spec_type: OpenAPI
  url: https://developer.sailpoint.com/docs/api/v2025/identity-security-cloud-v-2025-api/
- filename: openapi.yaml
  format: yaml
  label: SailPoint Identity Security Cloud Beta API
  slug: identity-security-cloud-beta-api
  spec_type: OpenAPI
  url: https://developer.sailpoint.com/docs/api/beta/identity-security-cloud-beta-api/
- filename: openapi.yaml
  format: yaml
  label: SailPoint IdentityIQ SCIM API
  slug: identityiq-scim-api
  spec_type: OpenAPI
  url: https://developer.sailpoint.com/docs/api/iiq/identityiq-scim-rest-api/
- filename: openapi.yaml
  format: yaml
  label: SailPoint Identity Security Cloud V2026 API
  slug: identity-security-cloud-v2026-api
  spec_type: OpenAPI
  url: https://developer.sailpoint.com/docs/api/v2026/identity-security-cloud-v-2026-api/
class_count: 0
classes: []
context_file: json-ld/sailpoint-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/sailpoint/refs/heads/main/json-ld/sailpoint-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Sailpoint from SailPoint.
layout: jsonld
name: Sailpoint Context
namespaces:
- prefix: sailpoint
  uri: https://developer.sailpoint.com/docs/api/v3/
- prefix: schema
  uri: https://schema.org/
- prefix: iam
  uri: https://www.w3.org/ns/iam#
- prefix: sec
  uri: https://w3id.org/security#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: foaf
  uri: http://xmlns.com/foaf/0.1/
- prefix: org
  uri: http://www.w3.org/ns/org#
- prefix: vcard
  uri: http://www.w3.org/2006/vcard/ns#
properties:
- container: ''
  name: PublicIdentity
  type: ''
- container: ''
  name: IdentityReference
  type: ''
- container: ''
  name: IdentityAttribute
  type: ''
- container: ''
  name: IdentityProfile
  type: ''
- container: ''
  name: OwnerReference
  type: ''
- container: ''
  name: SourceReference
  type: ''
- container: ''
  name: AccessProfile
  type: ''
- container: ''
  name: EntitlementRef
  type: ''
- container: ''
  name: Entitlement
  type: ''
- container: ''
  name: AccessProfileRef
  type: ''
- container: ''
  name: Role
  type: ''
- container: ''
  name: RoleMembershipSelector
  type: ''
- container: ''
  name: IdentityCertification
  type: ''
- container: ''
  name: CampaignReference
  type: ''
- container: ''
  name: Reviewer
  type: ''
- container: ''
  name: CertificationDecision
  type: ''
- container: ''
  name: AccessReviewItem
  type: ''
- container: ''
  name: Requestability
  type: ''
- container: ''
  name: ApprovalScheme
  type: ''
property_count: 19
provider_name: SailPoint
provider_slug: sailpoint
slug: sailpoint-context
source_filename: sailpoint-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"@vocab\": \"https://developer.sailpoint.com/docs/api/v3/\",\n    \"sailpoint\": \"https://developer.sailpoint.com/docs/api/v3/\",\n    \"schema\": \"https://schema.org/\",\n    \"iam\": \"https://www.w3.org/ns/iam#\",\n    \"sec\": \"https://w3id.org/security#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"foaf\": \"http://xmlns.com/foaf/0.1/\",\n    \"org\": \"http://www.w3.org/ns/org#\",\n    \"vcard\": \"http://www.w3.org/2006/vcard/ns#\",\n\n    \"PublicIdentity\": {\n      \"@id\": \"sailpoint:PublicIdentity\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"sailpoint:identityId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"alias\": {\n          \"@id\": \"sailpoint:alias\",\n          \"@type\": \"xsd:string\"\n   \
  \     },\n        \"email\": {\n          \"@id\": \"schema:email\",\n          \"@type\": \"xsd:string\"\n        },\n        \"status\": {\n          \"@id\": \"sailpoint:lifecycleStatus\",\n          \"@type\": \"xsd:string\"\n        },\n        \"identityState\": {\n          \"@id\": \"sailpoint:identityState\",\n          \"@type\": \"xsd:string\"\n        },\n        \"manager\": {\n          \"@id\": \"sailpoint:manager\",\n          \"@type\": \"@id\"\n        },\n        \"attributes\": {\n          \"@id\": \"sailpoint:identityAttributes\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"IdentityReference\": {\n      \"@id\": \"sailpoint:IdentityReference\",\n      \"@context\": {\n        \"type\": {\n          \"@id\": \"sailpoint:referenceType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"id\": {\n          \"@id\": \"sailpoint:identityId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\"\
  : \"schema:name\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"IdentityAttribute\": {\n      \"@id\": \"sailpoint:IdentityAttribute\",\n      \"@context\": {\n        \"key\": {\n          \"@id\": \"sailpoint:attributeKey\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"value\": {\n          \"@id\": \"sailpoint:attributeValue\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"IdentityProfile\": {\n      \"@id\": \"sailpoint:IdentityProfile\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"sailpoint:profileId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"\
  owner\": {\n          \"@id\": \"sailpoint:owner\",\n          \"@type\": \"@id\"\n        },\n        \"priority\": {\n          \"@id\": \"sailpoint:priority\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"authoritativeSource\": {\n          \"@id\": \"sailpoint:authoritativeSource\",\n          \"@type\": \"@id\"\n        },\n        \"identityRefreshRequired\": {\n          \"@id\": \"sailpoint:identityRefreshRequired\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"identityCount\": {\n          \"@id\": \"sailpoint:identityCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"hasTimeBasedAttr\": {\n          \"@id\": \"sailpoint:hasTimeBasedAttr\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"modified\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n\
  \    },\n\n    \"OwnerReference\": {\n      \"@id\": \"sailpoint:OwnerReference\",\n      \"@context\": {\n        \"type\": {\n          \"@id\": \"sailpoint:referenceType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"id\": {\n          \"@id\": \"sailpoint:ownerId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"SourceReference\": {\n      \"@id\": \"sailpoint:SourceReference\",\n      \"@context\": {\n        \"type\": {\n          \"@id\": \"sailpoint:referenceType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"id\": {\n          \"@id\": \"sailpoint:sourceId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"AccessProfile\": {\n      \"@id\": \"sailpoint:AccessProfile\",\n      \"@context\"\
  : {\n        \"id\": {\n          \"@id\": \"sailpoint:accessProfileId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"modified\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"enabled\": {\n          \"@id\": \"sailpoint:enabled\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"owner\": {\n          \"@id\": \"sailpoint:owner\",\n          \"@type\": \"@id\"\n        },\n        \"source\": {\n          \"@id\": \"sailpoint:source\",\n          \"@type\": \"@id\"\n        },\n        \"entitlements\": {\n          \"@id\": \"sailpoint:entitlements\",\n       \
  \   \"@container\": \"@set\"\n        },\n        \"requestable\": {\n          \"@id\": \"sailpoint:requestable\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"accessRequestConfig\": {\n          \"@id\": \"sailpoint:accessRequestConfig\",\n          \"@type\": \"@id\"\n        },\n        \"revocationRequestConfig\": {\n          \"@id\": \"sailpoint:revocationRequestConfig\",\n          \"@type\": \"@id\"\n        },\n        \"segments\": {\n          \"@id\": \"sailpoint:segments\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"EntitlementRef\": {\n      \"@id\": \"sailpoint:EntitlementRef\",\n      \"@context\": {\n        \"type\": {\n          \"@id\": \"sailpoint:referenceType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"id\": {\n          \"@id\": \"sailpoint:entitlementId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\
  \n        }\n      }\n    },\n\n    \"Entitlement\": {\n      \"@id\": \"sailpoint:Entitlement\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"sailpoint:entitlementId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"attribute\": {\n          \"@id\": \"sailpoint:entitlementAttribute\",\n          \"@type\": \"xsd:string\"\n        },\n        \"value\": {\n          \"@id\": \"sailpoint:entitlementValue\",\n          \"@type\": \"xsd:string\"\n        },\n        \"sourceSchemaObjectType\": {\n          \"@id\": \"sailpoint:sourceSchemaObjectType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"privileged\": {\n          \"@id\": \"sailpoint:privileged\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"\
  cloudGoverned\": {\n          \"@id\": \"sailpoint:cloudGoverned\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"modified\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"source\": {\n          \"@id\": \"sailpoint:source\",\n          \"@type\": \"@id\"\n        },\n        \"owner\": {\n          \"@id\": \"sailpoint:owner\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"AccessProfileRef\": {\n      \"@id\": \"sailpoint:AccessProfileRef\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"sailpoint:accessProfileId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"type\": {\n          \"@id\": \"sailpoint:referenceType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\":\
  \ \"xsd:string\"\n        }\n      }\n    },\n\n    \"Role\": {\n      \"@id\": \"sailpoint:Role\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"sailpoint:roleId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"modified\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"owner\": {\n          \"@id\": \"sailpoint:owner\",\n          \"@type\": \"@id\"\n        },\n        \"accessProfiles\": {\n          \"@id\": \"sailpoint:accessProfiles\",\n          \"@container\": \"@set\"\n        },\n        \"entitlements\": {\n          \"@id\": \"sailpoint:entitlements\"\
  ,\n          \"@container\": \"@set\"\n        },\n        \"membership\": {\n          \"@id\": \"sailpoint:membership\",\n          \"@type\": \"@id\"\n        },\n        \"enabled\": {\n          \"@id\": \"sailpoint:enabled\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"requestable\": {\n          \"@id\": \"sailpoint:requestable\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"accessRequestConfig\": {\n          \"@id\": \"sailpoint:accessRequestConfig\",\n          \"@type\": \"@id\"\n        },\n        \"revocationRequestConfig\": {\n          \"@id\": \"sailpoint:revocationRequestConfig\",\n          \"@type\": \"@id\"\n        },\n        \"segments\": {\n          \"@id\": \"sailpoint:segments\",\n          \"@container\": \"@set\"\n        },\n        \"dimensional\": {\n          \"@id\": \"sailpoint:dimensional\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"RoleMembershipSelector\": {\n      \"@id\": \"sailpoint:RoleMembershipSelector\"\
  ,\n      \"@context\": {\n        \"type\": {\n          \"@id\": \"sailpoint:selectorType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"criteria\": {\n          \"@id\": \"sailpoint:criteria\",\n          \"@type\": \"@id\"\n        },\n        \"identities\": {\n          \"@id\": \"sailpoint:memberIdentities\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"IdentityCertification\": {\n      \"@id\": \"sailpoint:IdentityCertification\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"sailpoint:certificationId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"campaign\": {\n          \"@id\": \"sailpoint:campaign\",\n          \"@type\": \"@id\"\n        },\n        \"completed\": {\n          \"@id\": \"sailpoint:completed\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"identitiesCompleted\"\
  : {\n          \"@id\": \"sailpoint:identitiesCompleted\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"identitiesTotal\": {\n          \"@id\": \"sailpoint:identitiesTotal\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"modified\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"decisionsMade\": {\n          \"@id\": \"sailpoint:decisionsMade\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"decisionsTotal\": {\n          \"@id\": \"sailpoint:decisionsTotal\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"due\": {\n          \"@id\": \"sailpoint:dueDate\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"signed\": {\n          \"@id\": \"sailpoint:signedDate\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"reviewer\": {\n   \
  \       \"@id\": \"sailpoint:reviewer\",\n          \"@type\": \"@id\"\n        },\n        \"reassignment\": {\n          \"@id\": \"sailpoint:reassignment\",\n          \"@type\": \"@id\"\n        },\n        \"hasErrors\": {\n          \"@id\": \"sailpoint:hasErrors\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"errorMessage\": {\n          \"@id\": \"sailpoint:errorMessage\",\n          \"@type\": \"xsd:string\"\n        },\n        \"phase\": {\n          \"@id\": \"sailpoint:certificationPhase\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"CampaignReference\": {\n      \"@id\": \"sailpoint:CampaignReference\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"sailpoint:campaignId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"type\": {\n          \"@id\": \"sailpoint:referenceType\",\n          \"@type\"\
  : \"xsd:string\"\n        },\n        \"campaignType\": {\n          \"@id\": \"sailpoint:campaignType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"correlatedStatus\": {\n          \"@id\": \"sailpoint:correlatedStatus\",\n          \"@type\": \"xsd:string\"\n        },\n        \"mandatoryCommentRequirement\": {\n          \"@id\": \"sailpoint:mandatoryCommentRequirement\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"Reviewer\": {\n      \"@id\": \"sailpoint:Reviewer\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"sailpoint:reviewerId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"email\": {\n          \"@id\": \"schema:email\",\n          \"@type\": \"xsd:string\"\n        },\n\
  \        \"type\": {\n          \"@id\": \"sailpoint:referenceType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"modified\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"CertificationDecision\": {\n      \"@id\": \"sailpoint:CertificationDecision\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"sailpoint:reviewItemId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"decision\": {\n          \"@id\": \"sailpoint:decision\",\n          \"@type\": \"xsd:string\"\n        },\n        \"bulk\": {\n          \"@id\": \"sailpoint:bulkDecision\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"comments\": {\n          \"@id\": \"sailpoint:decisionComments\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"AccessReviewItem\"\
  : {\n      \"@id\": \"sailpoint:AccessReviewItem\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"sailpoint:reviewItemId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"accessSummary\": {\n          \"@id\": \"sailpoint:accessSummary\",\n          \"@type\": \"@id\"\n        },\n        \"identitySummary\": {\n          \"@id\": \"sailpoint:identitySummary\",\n          \"@type\": \"@id\"\n        },\n        \"decision\": {\n          \"@id\": \"sailpoint:decision\",\n          \"@type\": \"xsd:string\"\n        },\n        \"recommendation\": {\n          \"@id\": \"sailpoint:recommendation\",\n          \"@type\": \"@id\"\n        },\n        \"comments\": {\n          \"@id\": \"sailpoint:reviewComments\",\n          \"@type\": \"xsd:string\"\n        },\n        \"completed\": {\n          \"@id\": \"sailpoint:completed\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"Requestability\": {\n      \"@id\": \"sailpoint:Requestability\"\
  ,\n      \"@context\": {\n        \"commentsRequired\": {\n          \"@id\": \"sailpoint:commentsRequired\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"denialCommentsRequired\": {\n          \"@id\": \"sailpoint:denialCommentsRequired\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"approvalSchemes\": {\n          \"@id\": \"sailpoint:approvalSchemes\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"ApprovalScheme\": {\n      \"@id\": \"sailpoint:ApprovalScheme\",\n      \"@context\": {\n        \"approverType\": {\n          \"@id\": \"sailpoint:approverType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"approverId\": {\n          \"@id\": \"sailpoint:approverId\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/sailpoint/refs/heads/main/json-ld/sailpoint-context.jsonld
tags:
- Access Governance
- Compliance
- IAM
- Identity Management
- Identity Security
- Security
- JSON-LD
- Linked Data
- Semantic Web
---
