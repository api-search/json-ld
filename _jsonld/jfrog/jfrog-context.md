---
api_specs:
- filename: jfrog-artifactory-openapi.yml
  format: yaml
  label: JFrog Artifactory REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/jfrog/refs/heads/main/openapi/jfrog-artifactory-openapi.yml
- filename: jfrog-artifactory-openapi.yml
  format: yaml
  label: JFrog Artifactory REST API V2
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/jfrog/refs/heads/main/openapi/jfrog-artifactory-openapi.yml
- filename: jfrog-xray-openapi.yml
  format: yaml
  label: JFrog Xray REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/jfrog/refs/heads/main/openapi/jfrog-xray-openapi.yml
- filename: jfrog-distribution-openapi.yml
  format: yaml
  label: JFrog Distribution REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/jfrog/refs/heads/main/openapi/jfrog-distribution-openapi.yml
- filename: jfrog-pipelines-openapi.yml
  format: yaml
  label: JFrog Pipelines REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/jfrog/refs/heads/main/openapi/jfrog-pipelines-openapi.yml
- filename: jfrog-platform-openapi.yml
  format: yaml
  label: JFrog Platform REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/jfrog/refs/heads/main/openapi/jfrog-platform-openapi.yml
- filename: jfrog-access-openapi.yml
  format: yaml
  label: JFrog Access REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/jfrog/refs/heads/main/openapi/jfrog-access-openapi.yml
- filename: jfrog-curation-openapi.yml
  format: yaml
  label: JFrog Curation REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/jfrog/refs/heads/main/openapi/jfrog-curation-openapi.yml
- filename: jfrog-mission-control-openapi.yml
  format: yaml
  label: JFrog Mission Control REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/jfrog/refs/heads/main/openapi/jfrog-mission-control-openapi.yml
- filename: jfrog-release-lifecycle-openapi.yml
  format: yaml
  label: JFrog Release Lifecycle Management REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/jfrog/refs/heads/main/openapi/jfrog-release-lifecycle-openapi.yml
- filename: jfrog-workers-openapi.yml
  format: yaml
  label: JFrog Workers REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/jfrog/refs/heads/main/openapi/jfrog-workers-openapi.yml
- filename: jfrog-ml-openapi.yml
  format: yaml
  label: JFrog ML REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/jfrog/refs/heads/main/openapi/jfrog-ml-openapi.yml
- filename: jfrog-connect-openapi.yml
  format: yaml
  label: JFrog Connect REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/jfrog/refs/heads/main/openapi/jfrog-connect-openapi.yml
- filename: jfrog-catalog-openapi.yml
  format: yaml
  label: JFrog Catalog REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/jfrog/refs/heads/main/openapi/jfrog-catalog-openapi.yml
- filename: jfrog-evidence-openapi.yml
  format: yaml
  label: JFrog Evidence REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/jfrog/refs/heads/main/openapi/jfrog-evidence-openapi.yml
class_count: 9
classes:
- name
- description
- version
- url
- created
- modified
- identifier
- email
- license
context_file: json-ld/jfrog-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/jfrog/refs/heads/main/json-ld/jfrog-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Jfrog from JFrog.
layout: jsonld
name: Jfrog Context
namespaces:
- prefix: jfrog
  uri: https://jfrog.com/schemas/
- prefix: schema
  uri: https://schema.org/
- prefix: spdx
  uri: https://spdx.org/rdf/terms#
- prefix: ssvc
  uri: https://www.cisa.gov/ssvc#
- prefix: intoto
  uri: https://in-toto.io/attestation/
- prefix: slsa
  uri: https://slsa.dev/provenance/
- prefix: cvss
  uri: https://www.first.org/cvss/
properties:
- container: ''
  name: Artifact
  type: ''
- container: ''
  name: Repository
  type: ''
- container: ''
  name: BuildInfo
  type: ''
- container: ''
  name: ReleaseBundle
  type: ''
- container: ''
  name: Vulnerability
  type: ''
- container: ''
  name: User
  type: ''
- container: ''
  name: Permission
  type: ''
- container: ''
  name: Pipeline
  type: ''
- container: ''
  name: Worker
  type: ''
- container: ''
  name: CurationPolicy
  type: ''
- container: ''
  name: Evidence
  type: ''
- container: ''
  name: Project
  type: ''
- container: ''
  name: Package
  type: ''
property_count: 13
provider_name: JFrog
provider_slug: jfrog
slug: jfrog-context
source_filename: jfrog-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://jfrog.com/schemas/\",\n    \"jfrog\": \"https://jfrog.com/schemas/\",\n    \"schema\": \"https://schema.org/\",\n    \"spdx\": \"https://spdx.org/rdf/terms#\",\n    \"ssvc\": \"https://www.cisa.gov/ssvc#\",\n    \"intoto\": \"https://in-toto.io/attestation/\",\n    \"slsa\": \"https://slsa.dev/provenance/\",\n    \"cvss\": \"https://www.first.org/cvss/\",\n\n    \"Artifact\": {\n      \"@id\": \"jfrog:Artifact\",\n      \"@context\": {\n        \"repo\": \"jfrog:repo\",\n        \"path\": \"schema:contentUrl\",\n        \"name\": \"schema:name\",\n        \"type\": \"schema:additionalType\",\n        \"created\": \"schema:dateCreated\",\n        \"createdBy\": \"schema:creator\",\n        \"lastModified\": \"schema:dateModified\",\n        \"modifiedBy\": \"schema:editor\",\n        \"downloadUri\": \"schema:contentUrl\",\n        \"mimeType\": \"schema:encodingFormat\",\n        \"size\": \"schema:contentSize\",\n        \"checksums\"\
  : \"jfrog:checksums\",\n        \"uri\": \"schema:url\"\n      }\n    },\n\n    \"Repository\": {\n      \"@id\": \"jfrog:Repository\",\n      \"@context\": {\n        \"key\": \"schema:identifier\",\n        \"rclass\": \"jfrog:repositoryClass\",\n        \"packageType\": \"jfrog:packageType\",\n        \"description\": \"schema:description\",\n        \"url\": \"schema:url\",\n        \"environments\": \"jfrog:environments\",\n        \"projectKey\": \"jfrog:projectKey\"\n      }\n    },\n\n    \"BuildInfo\": {\n      \"@id\": \"jfrog:BuildInfo\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"number\": \"schema:version\",\n        \"type\": \"schema:additionalType\",\n        \"started\": \"schema:startDate\",\n        \"durationMillis\": \"schema:duration\",\n        \"buildAgent\": \"jfrog:buildAgent\",\n        \"principal\": \"schema:creator\",\n        \"vcsRevision\": \"jfrog:vcsRevision\",\n        \"vcsUrl\": \"schema:codeRepository\",\n        \"url\"\
  : \"schema:url\",\n        \"modules\": \"jfrog:modules\"\n      }\n    },\n\n    \"ReleaseBundle\": {\n      \"@id\": \"jfrog:ReleaseBundle\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"version\": \"schema:version\",\n        \"status\": \"jfrog:status\",\n        \"description\": \"schema:description\",\n        \"created\": \"schema:dateCreated\",\n        \"created_by\": \"schema:creator\",\n        \"artifacts\": \"jfrog:artifacts\",\n        \"current_environment\": \"jfrog:environment\",\n        \"promotion_history\": \"jfrog:promotionHistory\",\n        \"distribution_status\": \"jfrog:distributionStatus\",\n        \"evidence\": \"jfrog:evidence\"\n      }\n    },\n\n    \"Vulnerability\": {\n      \"@id\": \"jfrog:Vulnerability\",\n      \"@context\": {\n        \"issue_id\": \"schema:identifier\",\n        \"cve\": \"jfrog:cve\",\n        \"severity\": \"jfrog:severity\",\n        \"cvss_v3_score\": \"cvss:score\",\n        \"cvss_v3_vector\": \"\
  cvss:vectorString\",\n        \"summary\": \"schema:abstract\",\n        \"description\": \"schema:description\",\n        \"published\": \"schema:datePublished\",\n        \"updated\": \"schema:dateModified\",\n        \"references\": \"schema:citation\",\n        \"fixed_versions\": \"jfrog:fixedVersions\",\n        \"impacted_artifacts\": \"jfrog:impactedArtifacts\",\n        \"component\": \"jfrog:component\"\n      }\n    },\n\n    \"User\": {\n      \"@id\": \"jfrog:User\",\n      \"@context\": {\n        \"username\": \"schema:alternateName\",\n        \"email\": \"schema:email\",\n        \"admin\": \"jfrog:isAdmin\",\n        \"status\": \"jfrog:accountStatus\",\n        \"groups\": \"schema:memberOf\",\n        \"realm\": \"jfrog:authenticationRealm\",\n        \"last_logged_in\": \"jfrog:lastLoggedIn\",\n        \"created\": \"schema:dateCreated\"\n      }\n    },\n\n    \"Permission\": {\n      \"@id\": \"jfrog:Permission\",\n      \"@context\": {\n        \"name\": \"schema:name\"\
  ,\n        \"resources\": \"jfrog:resources\"\n      }\n    },\n\n    \"Pipeline\": {\n      \"@id\": \"jfrog:Pipeline\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"pipelineSourceId\": \"jfrog:pipelineSourceId\",\n        \"projectId\": \"jfrog:projectId\",\n        \"createdAt\": \"schema:dateCreated\",\n        \"updatedAt\": \"schema:dateModified\"\n      }\n    },\n\n    \"Worker\": {\n      \"@id\": \"jfrog:Worker\",\n      \"@context\": {\n        \"key\": \"schema:identifier\",\n        \"description\": \"schema:description\",\n        \"enabled\": \"jfrog:enabled\",\n        \"source_code\": \"schema:text\",\n        \"action\": \"jfrog:triggerAction\",\n        \"created\": \"schema:dateCreated\",\n        \"modified\": \"schema:dateModified\"\n      }\n    },\n\n    \"CurationPolicy\": {\n      \"@id\": \"jfrog:CurationPolicy\",\n      \"@context\": {\n        \"policy_name\": \"schema:name\",\n        \"description\"\
  : \"schema:description\",\n        \"enabled\": \"jfrog:enabled\",\n        \"policy_type\": \"jfrog:policyType\",\n        \"repositories\": \"jfrog:repositories\",\n        \"package_types\": \"jfrog:packageTypes\",\n        \"conditions\": \"jfrog:conditions\",\n        \"actions\": \"jfrog:actions\",\n        \"created\": \"schema:dateCreated\",\n        \"modified\": \"schema:dateModified\"\n      }\n    },\n\n    \"Evidence\": {\n      \"@id\": \"jfrog:Evidence\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"subject_type\": \"jfrog:subjectType\",\n        \"subject\": \"jfrog:subject\",\n        \"predicate_type\": \"intoto:predicateType\",\n        \"predicate\": \"intoto:predicate\",\n        \"dsse_envelope_path\": \"jfrog:dsseEnvelopePath\",\n        \"signature_algorithm\": \"jfrog:signatureAlgorithm\",\n        \"key_alias\": \"jfrog:keyAlias\",\n        \"verified\": \"jfrog:verified\",\n        \"created\": \"schema:dateCreated\",\n        \"\
  created_by\": \"schema:creator\"\n      }\n    },\n\n    \"Project\": {\n      \"@id\": \"jfrog:Project\",\n      \"@context\": {\n        \"project_key\": \"schema:identifier\",\n        \"display_name\": \"schema:name\",\n        \"description\": \"schema:description\"\n      }\n    },\n\n    \"Package\": {\n      \"@id\": \"jfrog:Package\",\n      \"@context\": {\n        \"package_type\": \"jfrog:packageType\",\n        \"package_name\": \"schema:name\",\n        \"latest_version\": \"schema:version\",\n        \"description\": \"schema:description\",\n        \"licenses\": \"spdx:licenseDeclared\",\n        \"repository_url\": \"schema:codeRepository\",\n        \"homepage\": \"schema:url\"\n      }\n    },\n\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"version\": \"schema:version\",\n    \"url\": \"schema:url\",\n    \"created\": \"schema:dateCreated\",\n    \"modified\": \"schema:dateModified\",\n    \"identifier\": \"schema:identifier\",\n\
  \    \"email\": \"schema:email\",\n    \"license\": \"spdx:licenseDeclared\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/jfrog/refs/heads/main/json-ld/jfrog-context.jsonld
tags:
- Artifactory
- CI/CD
- Container Registry
- DevOps
- MLOps
- Package Management
- Security
- Software Supply Chain
- JSON-LD
- Linked Data
- Semantic Web
---
