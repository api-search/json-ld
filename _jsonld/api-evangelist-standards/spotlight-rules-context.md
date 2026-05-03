---
class_count: 24
classes:
- SpectralRule
- VacuumRule
- Ruleset
- LintingFunction
- description
- message
- severity
- given
- then
- formats
- id
- howToFix
- category
- recommended
- tags
- extends
- aliases
- overrides
- rules
- function
- field
- functionOptions
- match
- notMatch
context_file: json-ld/spotlight-rules-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/api-evangelist-standards/refs/heads/main/json-ld/spotlight-rules-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Spotlight Rules from Spotlight Rules.
layout: jsonld
name: Spotlight Rules Context
namespaces:
- prefix: spotlight
  uri: https://spotlight-rules.com/vocab#
- prefix: spectral
  uri: https://stoplight.io/spectral/vocab#
- prefix: vacuum
  uri: https://quobix.com/vacuum/vocab#
properties:
- container: ''
  name: Spectral
  type: reference
- container: ''
  name: Vacuum
  type: reference
- container: ''
  name: OpenAPI
  type: reference
- container: ''
  name: AsyncAPI
  type: reference
- container: ''
  name: Arazzo
  type: reference
property_count: 5
provider_name: Spotlight Rules
provider_slug: api-evangelist-standards
slug: spotlight-rules-context
source_filename: spotlight-rules-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"spotlight\": \"https://spotlight-rules.com/vocab#\",\n    \"spectral\": \"https://stoplight.io/spectral/vocab#\",\n    \"vacuum\": \"https://quobix.com/vacuum/vocab#\",\n    \"SpectralRule\": \"spotlight:SpectralRule\",\n    \"VacuumRule\": \"spotlight:VacuumRule\",\n    \"Ruleset\": \"spotlight:Ruleset\",\n    \"LintingFunction\": \"spotlight:LintingFunction\",\n    \"description\": \"description\",\n    \"message\": \"spotlight:ruleMessage\",\n    \"severity\": \"spotlight:severity\",\n    \"given\": \"spotlight:jsonPathSelector\",\n    \"then\": \"spotlight:assertion\",\n    \"formats\": \"spotlight:applicableFormats\",\n    \"id\": \"identifier\",\n    \"howToFix\": \"spotlight:remediationGuidance\",\n    \"category\": \"category\",\n    \"recommended\": \"spotlight:isRecommended\",\n    \"tags\": \"keywords\",\n    \"extends\": \"spotlight:extendsRuleset\",\n    \"aliases\": \"spotlight:jsonPathAliases\"\
  ,\n    \"overrides\": \"spotlight:fileOverrides\",\n    \"rules\": \"spotlight:containsRules\",\n    \"function\": \"spotlight:validationFunction\",\n    \"field\": \"spotlight:targetField\",\n    \"functionOptions\": \"spotlight:functionOptions\",\n    \"match\": \"spotlight:matchPattern\",\n    \"notMatch\": \"spotlight:negativeMatchPattern\",\n    \"Spectral\": {\n      \"@id\": \"spotlight:Spectral\",\n      \"@type\": \"@id\"\n    },\n    \"Vacuum\": {\n      \"@id\": \"spotlight:Vacuum\",\n      \"@type\": \"@id\"\n    },\n    \"OpenAPI\": {\n      \"@id\": \"https://spec.openapis.org/oas/v3.1.0\",\n      \"@type\": \"@id\"\n    },\n    \"AsyncAPI\": {\n      \"@id\": \"https://www.asyncapi.com/docs/reference\",\n      \"@type\": \"@id\"\n    },\n    \"Arazzo\": {\n      \"@id\": \"https://spec.openapis.org/arazzo/v1.0.0\",\n      \"@type\": \"@id\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/api-evangelist-standards/refs/heads/main/json-ld/spotlight-rules-context.jsonld
tags:
- API Governance
- Linting
- Spectral
- Vacuum
- OpenAPI
- Standards
- JSON-LD
- Linked Data
- Semantic Web
---
