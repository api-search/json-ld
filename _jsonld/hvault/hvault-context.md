---
api_specs:
- filename: hvault-system-backend-openapi.yml
  format: yaml
  label: Vault System Backend API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/hvault/refs/heads/main/openapi/hvault-system-backend-openapi.yml
- filename: hvault-secrets-engines-openapi.yml
  format: yaml
  label: Vault Secrets Engines API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/hvault/refs/heads/main/openapi/hvault-secrets-engines-openapi.yml
- filename: hvault-auth-methods-openapi.yml
  format: yaml
  label: Vault Auth Methods API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/hvault/refs/heads/main/openapi/hvault-auth-methods-openapi.yml
- filename: hvault-identity-openapi.yml
  format: yaml
  label: Vault Identity API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/hvault/refs/heads/main/openapi/hvault-identity-openapi.yml
class_count: 0
classes: []
context_file: json-ld/hvault-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/hvault/refs/heads/main/json-ld/hvault-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Hvault from HashiCorp Vault.
layout: jsonld
name: Hvault Context
namespaces:
- prefix: vault
  uri: https://developer.hashicorp.com/schemas/vault/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Secret
  type: ''
- container: ''
  name: Entity
  type: ''
- container: ''
  name: EntityAlias
  type: ''
- container: ''
  name: Group
  type: ''
- container: ''
  name: Token
  type: ''
- container: ''
  name: Policy
  type: ''
- container: ''
  name: AuthMount
  type: ''
- container: ''
  name: SecretsMount
  type: ''
- container: ''
  name: AuditDevice
  type: ''
- container: ''
  name: Lease
  type: ''
property_count: 10
provider_name: HashiCorp Vault
provider_slug: hvault
slug: hvault-context
source_filename: hvault-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"vault\": \"https://developer.hashicorp.com/schemas/vault/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Secret\": {\n      \"@id\": \"vault:Secret\",\n      \"@context\": {\n        \"data\": \"vault:secretData\",\n        \"version\": {\n          \"@id\": \"vault:version\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"created_time\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"deletion_time\": {\n          \"@id\": \"vault:deletionTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"destroyed\": {\n          \"@id\": \"vault:destroyed\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"Entity\": {\n      \"@id\": \"vault:Entity\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n    \
  \    \"disabled\": {\n          \"@id\": \"vault:disabled\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"policies\": \"vault:policies\",\n        \"creation_time\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"last_update_time\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"EntityAlias\": {\n      \"@id\": \"vault:EntityAlias\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"canonical_id\": \"vault:canonicalId\",\n        \"mount_accessor\": \"vault:mountAccessor\",\n        \"mount_path\": \"vault:mountPath\",\n        \"mount_type\": \"vault:mountType\",\n        \"creation_time\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"last_update_time\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\
  \n    \"Group\": {\n      \"@id\": \"vault:Group\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"type\": \"vault:groupType\",\n        \"policies\": \"vault:policies\",\n        \"member_entity_ids\": \"vault:memberEntityIds\",\n        \"member_group_ids\": \"vault:memberGroupIds\",\n        \"parent_group_ids\": \"vault:parentGroupIds\",\n        \"creation_time\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"last_update_time\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Token\": {\n      \"@id\": \"vault:Token\",\n      \"@context\": {\n        \"accessor\": \"vault:accessor\",\n        \"display_name\": \"schema:name\",\n        \"entity_id\": \"vault:entityId\",\n        \"policies\": \"vault:policies\",\n        \"orphan\": {\n          \"@id\": \"vault:orphan\",\n          \"@type\": \"xsd:boolean\"\n        },\n      \
  \  \"renewable\": {\n          \"@id\": \"vault:renewable\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"ttl\": {\n          \"@id\": \"vault:ttl\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"type\": \"vault:tokenType\",\n        \"creation_time\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"expire_time\": {\n          \"@id\": \"vault:expireTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"issue_time\": {\n          \"@id\": \"dcterms:issued\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Policy\": {\n      \"@id\": \"vault:Policy\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"policy\": \"vault:policyDocument\"\n      }\n    },\n\n    \"AuthMount\": {\n      \"@id\": \"vault:AuthMount\",\n      \"@context\": {\n        \"type\": \"vault:authType\",\n        \"description\": \"schema:description\",\n        \"accessor\"\
  : \"vault:accessor\",\n        \"local\": {\n          \"@id\": \"vault:local\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"seal_wrap\": {\n          \"@id\": \"vault:sealWrap\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"SecretsMount\": {\n      \"@id\": \"vault:SecretsMount\",\n      \"@context\": {\n        \"type\": \"vault:engineType\",\n        \"description\": \"schema:description\",\n        \"accessor\": \"vault:accessor\",\n        \"local\": {\n          \"@id\": \"vault:local\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"seal_wrap\": {\n          \"@id\": \"vault:sealWrap\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"AuditDevice\": {\n      \"@id\": \"vault:AuditDevice\",\n      \"@context\": {\n        \"type\": \"vault:auditType\",\n        \"description\": \"schema:description\",\n        \"path\": \"vault:auditPath\",\n        \"local\": {\n          \"@id\": \"vault:local\"\
  ,\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"Lease\": {\n      \"@id\": \"vault:Lease\",\n      \"@context\": {\n        \"lease_id\": \"vault:leaseId\",\n        \"lease_duration\": {\n          \"@id\": \"vault:leaseDuration\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"renewable\": {\n          \"@id\": \"vault:renewable\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/hvault/refs/heads/main/json-ld/hvault-context.jsonld
tags:
- Encryption
- Identity
- Infrastructure
- Secrets Management
- Security
- JSON-LD
- Linked Data
- Semantic Web
---
