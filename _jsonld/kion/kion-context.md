---
api_specs:
- filename: kion-cloud-operations-api-openapi.yml
  format: yaml
  label: Kion Cloud Operations API
  slug: kion-cloud-operations-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/kion/refs/heads/main/openapi/kion-cloud-operations-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/kion-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/kion/refs/heads/main/json-ld/kion-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Kion from Kion.
layout: jsonld
name: Kion Context
namespaces:
- prefix: kion
  uri: https://support.kion.io/hc/en-us/sections/4412439670797-Public-API#
properties:
- container: ''
  name: Account
  type: ''
- container: ''
  name: Project
  type: ''
- container: ''
  name: OU
  type: ''
- container: ''
  name: CloudRule
  type: ''
- container: ''
  name: ComplianceCheck
  type: ''
- container: ''
  name: ComplianceStandard
  type: ''
- container: ''
  name: FundingSource
  type: ''
- container: ''
  name: Label
  type: ''
- container: ''
  name: User
  type: ''
- container: ''
  name: UserGroup
  type: ''
- container: ''
  name: CloudAccessRole
  type: ''
- container: ''
  name: AwsIamPolicy
  type: ''
- container: ''
  name: ServiceControlPolicy
  type: ''
- container: ''
  name: CloudFormationTemplate
  type: ''
- container: ''
  name: Webhook
  type: ''
- container: ''
  name: CustomVariable
  type: ''
property_count: 16
provider_name: Kion
provider_slug: kion
slug: kion-context
source_filename: kion-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"kion\": \"https://support.kion.io/hc/en-us/sections/4412439670797-Public-API#\",\n    \"Account\": {\n      \"@id\": \"kion:account\",\n      \"@context\": {\n        \"name\": \"https://schema.org/name\",\n        \"account_number\": \"https://schema.org/identifier\",\n        \"account_type_id\": \"https://schema.org/category\",\n        \"payer_id\": \"https://schema.org/fundedItem\",\n        \"project_id\": {\n          \"@id\": \"kion:project\",\n          \"@type\": \"@id\"\n        },\n        \"email\": \"https://schema.org/email\",\n        \"linked_account_number\": \"https://schema.org/identifier\",\n        \"linked_role\": \"https://schema.org/roleName\",\n        \"start_datecode\": \"https://schema.org/startDate\",\n        \"skip_access_checking\": \"https://schema.org/actionOption\",\n        \"labels\": \"https://schema.org/keywords\",\n        \"created_at\": \"https://schema.org/dateCreated\"\
  \n      }\n    },\n    \"Project\": {\n      \"@id\": \"kion:project\",\n      \"@context\": {\n        \"name\": \"https://schema.org/name\",\n        \"description\": \"https://schema.org/description\",\n        \"ou_id\": {\n          \"@id\": \"kion:ou\",\n          \"@type\": \"@id\"\n        },\n        \"default_aws_region\": \"https://schema.org/areaServed\",\n        \"permission_scheme_id\": \"https://schema.org/accessMode\",\n        \"project_funding\": \"https://schema.org/funding\",\n        \"budget\": \"https://schema.org/totalPrice\",\n        \"labels\": \"https://schema.org/keywords\",\n        \"archived\": \"https://schema.org/status\",\n        \"auto_pay\": \"https://schema.org/actionOption\",\n        \"created_at\": \"https://schema.org/dateCreated\"\n      }\n    },\n    \"OU\": {\n      \"@id\": \"kion:ou\",\n      \"@context\": {\n        \"name\": \"https://schema.org/name\",\n        \"description\": \"https://schema.org/description\",\n        \"parent_ou_id\"\
  : {\n          \"@id\": \"kion:ou\",\n          \"@type\": \"@id\"\n        },\n        \"permission_scheme_id\": \"https://schema.org/accessMode\",\n        \"labels\": \"https://schema.org/keywords\",\n        \"created_at\": \"https://schema.org/dateCreated\"\n      }\n    },\n    \"CloudRule\": {\n      \"@id\": \"kion:cloud-rule\",\n      \"@context\": {\n        \"name\": \"https://schema.org/name\",\n        \"description\": \"https://schema.org/description\",\n        \"pre_webhook_id\": {\n          \"@id\": \"kion:webhook\",\n          \"@type\": \"@id\"\n        },\n        \"post_webhook_id\": {\n          \"@id\": \"kion:webhook\",\n          \"@type\": \"@id\"\n        },\n        \"built_in\": \"https://schema.org/isAccessibleForFree\",\n        \"owner_users\": \"https://schema.org/author\",\n        \"owner_user_groups\": \"https://schema.org/author\",\n        \"aws_iam_policies\": \"https://schema.org/hasPart\",\n        \"compliance_standards\": \"https://schema.org/hasPart\"\
  ,\n        \"labels\": \"https://schema.org/keywords\",\n        \"created_at\": \"https://schema.org/dateCreated\"\n      }\n    },\n    \"ComplianceCheck\": {\n      \"@id\": \"kion:compliance-check\",\n      \"@context\": {\n        \"name\": \"https://schema.org/name\",\n        \"description\": \"https://schema.org/description\",\n        \"cloud_provider_id\": \"https://schema.org/provider\",\n        \"severity_type_id\": \"https://schema.org/significance\",\n        \"body\": \"https://schema.org/text\",\n        \"frequency_minutes\": \"https://schema.org/repeatFrequency\",\n        \"is_all_regions\": \"https://schema.org/areaServed\",\n        \"regions\": \"https://schema.org/areaServed\",\n        \"labels\": \"https://schema.org/keywords\",\n        \"created_at\": \"https://schema.org/dateCreated\"\n      }\n    },\n    \"ComplianceStandard\": {\n      \"@id\": \"kion:compliance-standard\",\n      \"@context\": {\n        \"name\": \"https://schema.org/name\",\n        \"\
  description\": \"https://schema.org/description\",\n        \"compliance_checks\": {\n          \"@id\": \"kion:compliance-check\",\n          \"@type\": \"@id\"\n        },\n        \"labels\": \"https://schema.org/keywords\",\n        \"created_at\": \"https://schema.org/dateCreated\"\n      }\n    },\n    \"FundingSource\": {\n      \"@id\": \"kion:funding-source\",\n      \"@context\": {\n        \"name\": \"https://schema.org/name\",\n        \"description\": \"https://schema.org/description\",\n        \"amount\": \"https://schema.org/price\",\n        \"start_datecode\": \"https://schema.org/startDate\",\n        \"end_datecode\": \"https://schema.org/endDate\",\n        \"ou_id\": {\n          \"@id\": \"kion:ou\",\n          \"@type\": \"@id\"\n        },\n        \"labels\": \"https://schema.org/keywords\",\n        \"created_at\": \"https://schema.org/dateCreated\"\n      }\n    },\n    \"Label\": {\n      \"@id\": \"kion:label\",\n      \"@context\": {\n        \"key\": \"\
  https://schema.org/propertyID\",\n        \"value\": \"https://schema.org/value\",\n        \"color\": \"https://schema.org/color\",\n        \"created_at\": \"https://schema.org/dateCreated\"\n      }\n    },\n    \"User\": {\n      \"@id\": \"kion:user\",\n      \"@context\": {\n        \"username\": \"https://schema.org/identifier\",\n        \"first_name\": \"https://schema.org/givenName\",\n        \"last_name\": \"https://schema.org/familyName\",\n        \"email\": \"https://schema.org/email\",\n        \"idms_id\": \"https://schema.org/memberOf\",\n        \"enabled\": \"https://schema.org/status\",\n        \"created_at\": \"https://schema.org/dateCreated\"\n      }\n    },\n    \"UserGroup\": {\n      \"@id\": \"kion:user-group\",\n      \"@context\": {\n        \"name\": \"https://schema.org/name\",\n        \"description\": \"https://schema.org/description\",\n        \"idms_id\": \"https://schema.org/memberOf\",\n        \"users\": {\n          \"@id\": \"kion:user\",\n  \
  \        \"@type\": \"@id\"\n        },\n        \"enabled\": \"https://schema.org/status\",\n        \"created_at\": \"https://schema.org/dateCreated\"\n      }\n    },\n    \"CloudAccessRole\": {\n      \"@id\": \"kion:cloud-access-role\",\n      \"@context\": {\n        \"name\": \"https://schema.org/name\",\n        \"aws_iam_role_name\": \"https://schema.org/roleName\",\n        \"web_access\": \"https://schema.org/actionOption\",\n        \"short_term_access_keys\": \"https://schema.org/actionOption\",\n        \"long_term_access_keys\": \"https://schema.org/actionOption\",\n        \"aws_iam_policies\": \"https://schema.org/hasPart\",\n        \"users\": {\n          \"@id\": \"kion:user\",\n          \"@type\": \"@id\"\n        },\n        \"user_groups\": {\n          \"@id\": \"kion:user-group\",\n          \"@type\": \"@id\"\n        },\n        \"labels\": \"https://schema.org/keywords\",\n        \"created_at\": \"https://schema.org/dateCreated\"\n      }\n    },\n    \"AwsIamPolicy\"\
  : {\n      \"@id\": \"kion:aws-iam-policy\",\n      \"@context\": {\n        \"name\": \"https://schema.org/name\",\n        \"description\": \"https://schema.org/description\",\n        \"aws_iam_path\": \"https://schema.org/identifier\",\n        \"policy\": \"https://schema.org/text\",\n        \"aws_managed_policy\": \"https://schema.org/isAccessibleForFree\",\n        \"labels\": \"https://schema.org/keywords\",\n        \"created_at\": \"https://schema.org/dateCreated\"\n      }\n    },\n    \"ServiceControlPolicy\": {\n      \"@id\": \"kion:service-control-policy\",\n      \"@context\": {\n        \"name\": \"https://schema.org/name\",\n        \"description\": \"https://schema.org/description\",\n        \"policy\": \"https://schema.org/text\",\n        \"labels\": \"https://schema.org/keywords\",\n        \"created_at\": \"https://schema.org/dateCreated\"\n      }\n    },\n    \"CloudFormationTemplate\": {\n      \"@id\": \"kion:cloudformation-template\",\n      \"@context\":\
  \ {\n        \"name\": \"https://schema.org/name\",\n        \"description\": \"https://schema.org/description\",\n        \"template_url\": \"https://schema.org/url\",\n        \"template_body\": \"https://schema.org/text\",\n        \"region\": \"https://schema.org/areaServed\",\n        \"terminate_protected\": \"https://schema.org/actionOption\",\n        \"labels\": \"https://schema.org/keywords\",\n        \"created_at\": \"https://schema.org/dateCreated\"\n      }\n    },\n    \"Webhook\": {\n      \"@id\": \"kion:webhook\",\n      \"@context\": {\n        \"name\": \"https://schema.org/name\",\n        \"description\": \"https://schema.org/description\",\n        \"url\": \"https://schema.org/url\",\n        \"auth_type\": \"https://schema.org/authenticator\",\n        \"labels\": \"https://schema.org/keywords\",\n        \"created_at\": \"https://schema.org/dateCreated\"\n      }\n    },\n    \"CustomVariable\": {\n      \"@id\": \"kion:custom-variable\",\n      \"@context\":\
  \ {\n        \"key\": \"https://schema.org/propertyID\",\n        \"value\": \"https://schema.org/value\",\n        \"description\": \"https://schema.org/description\",\n        \"labels\": \"https://schema.org/keywords\",\n        \"created_at\": \"https://schema.org/dateCreated\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/kion/refs/heads/main/json-ld/kion-context.jsonld
tags:
- Cloud Operations
- Compliance
- Costs
- FinOps
- Governance
- Spend
- JSON-LD
- Linked Data
- Semantic Web
---
