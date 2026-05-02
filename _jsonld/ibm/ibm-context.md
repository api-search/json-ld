---
api_specs:
- filename: assistant-v2.json
  format: json
  label: IBM Watson Assistant
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/watson-developer-cloud/api-spec/master/assistant/assistant-v2.json
- filename: natural-language-understanding.json
  format: json
  label: IBM Watson Natural Language Understanding
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/watson-developer-cloud/api-spec/master/natural-language-understanding/natural-language-understanding.json
- filename: language-translator.json
  format: json
  label: IBM Watson Language Translator
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/watson-developer-cloud/api-spec/master/language-translator/language-translator.json
- filename: speech-to-text.json
  format: json
  label: IBM Watson Speech to Text
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/watson-developer-cloud/api-spec/master/speech-to-text/speech-to-text.json
- filename: text-to-speech.json
  format: json
  label: IBM Watson Text to Speech
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/watson-developer-cloud/api-spec/master/text-to-speech/text-to-speech.json
- filename: ibm-cloud-iam.yml
  format: yaml
  label: IBM Cloud IAM Identity Services
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/ibm/refs/heads/main/openapi/ibm-cloud-iam.yml
- filename: ibm-cloud-iam.yml
  format: yaml
  label: IBM IAM Policy Management
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/ibm/refs/heads/main/openapi/ibm-cloud-iam.yml
- filename: ibm-cloud-iam.yml
  format: yaml
  label: IBM IAM Access Groups
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/ibm/refs/heads/main/openapi/ibm-cloud-iam.yml
class_count: 4
classes:
- id
- type
- name
- description
context_file: json-ld/ibm-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/ibm/refs/heads/main/json-ld/ibm-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Ibm from IBM.
layout: jsonld
name: Ibm Context
namespaces:
- prefix: ibm
  uri: https://cloud.ibm.com/schema/
- prefix: iam
  uri: https://cloud.ibm.com/schema/iam/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: skos
  uri: http://www.w3.org/2004/02/skos/core#
properties:
- container: ''
  name: CloudResource
  type: ''
- container: ''
  name: ResourceInstance
  type: ''
- container: ''
  name: ResourceGroup
  type: ''
- container: ''
  name: Account
  type: ''
- container: ''
  name: ServiceId
  type: ''
- container: ''
  name: ApiKey
  type: ''
- container: ''
  name: TrustedProfile
  type: ''
- container: ''
  name: ClaimRule
  type: ''
- container: ''
  name: AccessPolicy
  type: ''
- container: ''
  name: PolicySubject
  type: ''
- container: ''
  name: PolicyRole
  type: ''
- container: ''
  name: PolicyResource
  type: ''
- container: ''
  name: Role
  type: ''
- container: ''
  name: AccessGroup
  type: ''
- container: ''
  name: AccessToken
  type: ''
- container: ''
  name: Tag
  type: ''
- container: ''
  name: url
  type: reference
- container: ''
  name: crn
  type: string
- container: ''
  name: accountId
  type: string
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: modifiedAt
  type: dateTime
property_count: 21
provider_name: IBM
provider_slug: ibm
slug: ibm-context
source_filename: ibm-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"ibm\": \"https://cloud.ibm.com/schema/\",\n    \"iam\": \"https://cloud.ibm.com/schema/iam/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"skos\": \"http://www.w3.org/2004/02/skos/core#\",\n\n    \"id\": \"@id\",\n    \"type\": \"@type\",\n\n    \"CloudResource\": {\n      \"@id\": \"ibm:CloudResource\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"crn\": {\n          \"@id\": \"ibm:crn\",\n          \"@type\": \"xsd:string\"\n        },\n        \"accountId\": {\n          \"@id\": \"ibm:accountId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"resourceGroupId\": {\n          \"@id\": \"ibm:resourceGroupId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"region\": {\n          \"@id\": \"ibm:region\",\n          \"\
  @type\": \"xsd:string\"\n        },\n        \"state\": {\n          \"@id\": \"ibm:state\",\n          \"@type\": \"xsd:string\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"createdBy\": {\n          \"@id\": \"ibm:createdBy\",\n          \"@type\": \"@id\"\n        },\n        \"tags\": {\n          \"@id\": \"ibm:tags\",\n          \"@container\": \"@set\"\n        },\n        \"locked\": {\n          \"@id\": \"ibm:locked\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"ResourceInstance\": {\n      \"@id\": \"ibm:ResourceInstance\",\n      \"@context\": {\n        \"guid\": {\n          \"@id\": \"ibm:guid\",\n          \"@type\": \"xsd:string\"\n        },\n        \"resourcePlanId\": {\n          \"@id\": \"ibm:resourcePlanId\",\n         \
  \ \"@type\": \"xsd:string\"\n        },\n        \"targetCrn\": {\n          \"@id\": \"ibm:targetCrn\",\n          \"@type\": \"xsd:string\"\n        },\n        \"dashboardUrl\": {\n          \"@id\": \"ibm:dashboardUrl\",\n          \"@type\": \"xsd:anyURI\"\n        },\n        \"allowCleanup\": {\n          \"@id\": \"ibm:allowCleanup\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"ResourceGroup\": {\n      \"@id\": \"ibm:ResourceGroup\",\n      \"@context\": {\n        \"isDefault\": {\n          \"@id\": \"ibm:isDefault\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"quotaId\": {\n          \"@id\": \"ibm:quotaId\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"Account\": {\n      \"@id\": \"ibm:Account\",\n      \"@context\": {\n        \"ownerIamId\": {\n          \"@id\": \"ibm:ownerIamId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"accountType\": {\n          \"@id\": \"ibm:accountType\"\
  ,\n          \"@type\": \"xsd:string\"\n        },\n        \"enterpriseId\": {\n          \"@id\": \"ibm:enterpriseId\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"ServiceId\": {\n      \"@id\": \"iam:ServiceId\",\n      \"@context\": {\n        \"entityTag\": {\n          \"@id\": \"iam:entityTag\",\n          \"@type\": \"xsd:string\"\n        },\n        \"uniqueInstanceCrns\": {\n          \"@id\": \"iam:uniqueInstanceCrns\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"ApiKey\": {\n      \"@id\": \"iam:ApiKey\",\n      \"@context\": {\n        \"iamId\": {\n          \"@id\": \"iam:iamId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"disabled\": {\n          \"@id\": \"iam:disabled\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"supportSessions\": {\n          \"@id\": \"iam:supportSessions\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"actionWhenLeaked\": {\n          \"@id\"\
  : \"iam:actionWhenLeaked\",\n          \"@type\": \"xsd:string\"\n        },\n        \"expiresAt\": {\n          \"@id\": \"iam:expiresAt\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"TrustedProfile\": {\n      \"@id\": \"iam:TrustedProfile\",\n      \"@context\": {\n        \"iamId\": {\n          \"@id\": \"iam:iamId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"templateId\": {\n          \"@id\": \"iam:templateId\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"ClaimRule\": {\n      \"@id\": \"iam:ClaimRule\",\n      \"@context\": {\n        \"ruleType\": {\n          \"@id\": \"iam:ruleType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"conditions\": {\n          \"@id\": \"iam:conditions\",\n          \"@container\": \"@set\"\n        },\n        \"realmName\": {\n          \"@id\": \"iam:realmName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"crType\": {\n          \"@id\"\
  : \"iam:crType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"expiration\": {\n          \"@id\": \"iam:expiration\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"AccessPolicy\": {\n      \"@id\": \"iam:AccessPolicy\",\n      \"@context\": {\n        \"policyType\": {\n          \"@id\": \"iam:policyType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"subjects\": {\n          \"@id\": \"iam:subjects\",\n          \"@container\": \"@set\"\n        },\n        \"roles\": {\n          \"@id\": \"iam:roles\",\n          \"@container\": \"@set\"\n        },\n        \"resources\": {\n          \"@id\": \"iam:resources\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"PolicySubject\": {\n      \"@id\": \"iam:PolicySubject\",\n      \"@context\": {\n        \"attributes\": {\n          \"@id\": \"iam:subjectAttributes\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"PolicyRole\":\
  \ {\n      \"@id\": \"iam:PolicyRole\",\n      \"@context\": {\n        \"roleId\": {\n          \"@id\": \"iam:roleId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"displayName\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"PolicyResource\": {\n      \"@id\": \"iam:PolicyResource\",\n      \"@context\": {\n        \"attributes\": {\n          \"@id\": \"iam:resourceAttributes\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Role\": {\n      \"@id\": \"iam:Role\",\n      \"@context\": {\n        \"displayName\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"actions\": {\n          \"@id\": \"iam:actions\",\n          \"@container\": \"@set\"\n        },\n        \"serviceName\": {\n          \"@id\": \"iam:serviceName\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"AccessGroup\": {\n      \"@id\"\
  : \"iam:AccessGroup\",\n      \"@context\": {\n        \"isFederated\": {\n          \"@id\": \"iam:isFederated\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"membershipType\": {\n          \"@id\": \"iam:membershipType\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"AccessToken\": {\n      \"@id\": \"iam:AccessToken\",\n      \"@context\": {\n        \"accessToken\": {\n          \"@id\": \"iam:accessToken\",\n          \"@type\": \"xsd:string\"\n        },\n        \"refreshToken\": {\n          \"@id\": \"iam:refreshToken\",\n          \"@type\": \"xsd:string\"\n        },\n        \"tokenType\": {\n          \"@id\": \"iam:tokenType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"expiresIn\": {\n          \"@id\": \"iam:expiresIn\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"expiration\": {\n          \"@id\": \"iam:expiration\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"scope\": {\n \
  \         \"@id\": \"iam:scope\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"Tag\": {\n      \"@id\": \"ibm:Tag\",\n      \"@context\": {\n        \"tagName\": {\n          \"@id\": \"ibm:tagName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"tagType\": {\n          \"@id\": \"ibm:tagType\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    },\n    \"crn\": {\n      \"@id\": \"ibm:crn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accountId\": {\n      \"@id\": \"ibm:accountId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdAt\": {\n      \"@id\": \"dcterms:created\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"modifiedAt\": {\n      \"@id\": \"dcterms:modified\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/ibm/refs/heads/main/json-ld/ibm-context.jsonld
tags:
- API Management
- Artificial Intelligence
- Billing
- Cloud Computing
- Containers
- Data Governance
- Databases
- DevOps
- Enterprise
- Generative AI
- Hybrid Cloud
- Infrastructure
- Machine Learning
- Networking
- Observability
- Security
- Serverless
- Storage
- Watson
- Watsonx
- JSON-LD
- Linked Data
- Semantic Web
---
