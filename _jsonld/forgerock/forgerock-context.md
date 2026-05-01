---
api_specs:
- filename: forgerock-identity-cloud-openapi.yml
  format: yaml
  label: ForgeRock Identity Cloud REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/forgerock/refs/heads/main/openapi/forgerock-identity-cloud-openapi.yml
- filename: forgerock-access-management-openapi.yml
  format: yaml
  label: ForgeRock Access Management API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/forgerock/refs/heads/main/openapi/forgerock-access-management-openapi.yml
- filename: forgerock-identity-management-openapi.yml
  format: yaml
  label: ForgeRock Identity Management API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/forgerock/refs/heads/main/openapi/forgerock-identity-management-openapi.yml
- filename: forgerock-identity-gateway-openapi.yml
  format: yaml
  label: ForgeRock Identity Gateway API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/forgerock/refs/heads/main/openapi/forgerock-identity-gateway-openapi.yml
- filename: forgerock-directory-services-openapi.yml
  format: yaml
  label: ForgeRock Directory Services API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/forgerock/refs/heads/main/openapi/forgerock-directory-services-openapi.yml
- filename: forgerock-identity-governance-openapi.yml
  format: yaml
  label: ForgeRock Identity Governance API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/forgerock/refs/heads/main/openapi/forgerock-identity-governance-openapi.yml
- filename: forgerock-autonomous-identity-openapi.yml
  format: yaml
  label: ForgeRock Autonomous Identity API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/forgerock/refs/heads/main/openapi/forgerock-autonomous-identity-openapi.yml
class_count: 0
classes: []
context_file: json-ld/forgerock-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/forgerock/refs/heads/main/json-ld/forgerock-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Forgerock from ForgeRock.
layout: jsonld
name: Forgerock Context
namespaces:
- prefix: forgerock
  uri: https://schema.forgerock.com/
- prefix: schema
  uri: https://schema.org/
- prefix: iam
  uri: https://www.w3.org/ns/iam#
- prefix: sec
  uri: https://w3id.org/security#
- prefix: vcard
  uri: http://www.w3.org/2006/vcard/ns#
- prefix: foaf
  uri: http://xmlns.com/foaf/0.1/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: ldap
  uri: https://www.w3.org/ns/ldap#
- prefix: oauth
  uri: https://www.w3.org/ns/oauth#
properties:
- container: ''
  name: ManagedUser
  type: ''
- container: ''
  name: ManagedRole
  type: ''
- container: ''
  name: Session
  type: ''
- container: ''
  name: Policy
  type: ''
- container: ''
  name: OAuth2Token
  type: ''
- container: ''
  name: DirectoryEntry
  type: ''
- container: ''
  name: DirectoryGroup
  type: ''
- container: ''
  name: Entitlement
  type: ''
- container: ''
  name: Certification
  type: ''
- container: ''
  name: Route
  type: ''
- container: ''
  name: ConfidenceScore
  type: ''
property_count: 11
provider_name: ForgeRock
provider_slug: forgerock
slug: forgerock-context
source_filename: forgerock-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n\n    \"forgerock\": \"https://schema.forgerock.com/\",\n    \"schema\": \"https://schema.org/\",\n    \"iam\": \"https://www.w3.org/ns/iam#\",\n    \"sec\": \"https://w3id.org/security#\",\n    \"vcard\": \"http://www.w3.org/2006/vcard/ns#\",\n    \"foaf\": \"http://xmlns.com/foaf/0.1/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ldap\": \"https://www.w3.org/ns/ldap#\",\n    \"oauth\": \"https://www.w3.org/ns/oauth#\",\n\n    \"ManagedUser\": {\n      \"@id\": \"forgerock:ManagedUser\",\n      \"@context\": {\n        \"_id\": \"dcterms:identifier\",\n        \"userName\": \"foaf:accountName\",\n        \"givenName\": \"schema:givenName\",\n        \"sn\": \"schema:familyName\",\n        \"mail\": \"schema:email\",\n        \"telephoneNumber\": \"schema:telephone\",\n        \"accountStatus\": \"forgerock:accountStatus\",\n        \"city\": \"schema:addressLocality\"\
  ,\n        \"stateProvince\": \"schema:addressRegion\",\n        \"postalCode\": \"schema:postalCode\",\n        \"country\": \"schema:addressCountry\",\n        \"postalAddress\": \"schema:streetAddress\",\n        \"description\": \"schema:description\",\n        \"effectiveRoles\": {\n          \"@id\": \"forgerock:effectiveRoles\",\n          \"@type\": \"@id\"\n        },\n        \"effectiveAssignments\": {\n          \"@id\": \"forgerock:effectiveAssignments\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"ManagedRole\": {\n      \"@id\": \"forgerock:ManagedRole\",\n      \"@context\": {\n        \"_id\": \"dcterms:identifier\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"condition\": \"forgerock:roleCondition\",\n        \"temporalConstraints\": \"forgerock:temporalConstraints\",\n        \"members\": {\n          \"@id\": \"schema:member\",\n          \"@type\": \"@id\"\n        },\n        \"assignments\"\
  : {\n          \"@id\": \"forgerock:roleAssignments\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Session\": {\n      \"@id\": \"forgerock:Session\",\n      \"@context\": {\n        \"tokenId\": \"forgerock:tokenId\",\n        \"username\": \"foaf:accountName\",\n        \"universalId\": \"dcterms:identifier\",\n        \"realm\": \"forgerock:realm\",\n        \"latestAccessTime\": {\n          \"@id\": \"forgerock:latestAccessTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"maxIdleExpirationTime\": {\n          \"@id\": \"forgerock:maxIdleExpirationTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"maxSessionExpirationTime\": {\n          \"@id\": \"forgerock:maxSessionExpirationTime\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Policy\": {\n      \"@id\": \"forgerock:AuthorizationPolicy\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\"\
  ,\n        \"active\": \"forgerock:isActive\",\n        \"applicationName\": \"forgerock:policySet\",\n        \"resources\": \"forgerock:policyResources\",\n        \"actionValues\": \"forgerock:actionValues\",\n        \"subject\": \"forgerock:subjectCondition\",\n        \"condition\": \"forgerock:environmentCondition\",\n        \"resourceTypeUuid\": {\n          \"@id\": \"forgerock:resourceType\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"OAuth2Token\": {\n      \"@id\": \"oauth:AccessToken\",\n      \"@context\": {\n        \"access_token\": \"oauth:accessToken\",\n        \"token_type\": \"oauth:tokenType\",\n        \"expires_in\": \"oauth:expiresIn\",\n        \"refresh_token\": \"oauth:refreshToken\",\n        \"scope\": \"oauth:scope\",\n        \"id_token\": \"oauth:idToken\"\n      }\n    },\n\n    \"DirectoryEntry\": {\n      \"@id\": \"forgerock:DirectoryEntry\",\n      \"@context\": {\n        \"_id\": \"dcterms:identifier\",\n        \"cn\": \"\
  foaf:name\",\n        \"givenName\": \"schema:givenName\",\n        \"sn\": \"schema:familyName\",\n        \"mail\": \"schema:email\",\n        \"telephoneNumber\": \"schema:telephone\",\n        \"description\": \"schema:description\",\n        \"memberOf\": {\n          \"@id\": \"schema:memberOf\",\n          \"@type\": \"@id\"\n        },\n        \"userName\": \"foaf:accountName\"\n      }\n    },\n\n    \"DirectoryGroup\": {\n      \"@id\": \"forgerock:DirectoryGroup\",\n      \"@context\": {\n        \"_id\": \"dcterms:identifier\",\n        \"cn\": \"foaf:name\",\n        \"description\": \"schema:description\",\n        \"members\": {\n          \"@id\": \"schema:member\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Entitlement\": {\n      \"@id\": \"forgerock:Entitlement\",\n      \"@context\": {\n        \"_id\": \"dcterms:identifier\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"applicationName\":\
  \ \"forgerock:applicationName\",\n        \"type\": \"forgerock:entitlementType\",\n        \"owner\": {\n          \"@id\": \"schema:owner\",\n          \"@type\": \"@id\"\n        },\n        \"riskLevel\": \"forgerock:riskLevel\"\n      }\n    },\n\n    \"Certification\": {\n      \"@id\": \"forgerock:AccessCertification\",\n      \"@context\": {\n        \"_id\": \"dcterms:identifier\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"type\": \"forgerock:certificationType\",\n        \"status\": \"forgerock:certificationStatus\",\n        \"createdDate\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Route\": {\n      \"@id\": \"forgerock:GatewayRoute\",\n      \"@context\": {\n        \"_id\": \"dcterms:identifier\",\n        \"name\": \"schema:name\",\n        \"condition\": \"forgerock:routeCondition\",\n        \"handler\": \"forgerock:routeHandler\",\n     \
  \   \"baseURI\": {\n          \"@id\": \"forgerock:baseURI\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"ConfidenceScore\": {\n      \"@id\": \"forgerock:ConfidenceScore\",\n      \"@context\": {\n        \"entitlementId\": {\n          \"@id\": \"forgerock:entitlement\",\n          \"@type\": \"@id\"\n        },\n        \"userId\": {\n          \"@id\": \"forgerock:user\",\n          \"@type\": \"@id\"\n        },\n        \"confidenceScore\": {\n          \"@id\": \"forgerock:confidenceValue\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"drivingAttributes\": \"forgerock:drivingAttributes\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/forgerock/refs/heads/main/json-ld/forgerock-context.jsonld
tags:
- Access Management
- Authentication
- Authorization
- Identity Governance
- Identity Management
- OAuth
- OpenID Connect
- JSON-LD
- Linked Data
- Semantic Web
---
