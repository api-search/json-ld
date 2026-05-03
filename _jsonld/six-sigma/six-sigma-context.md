---
class_count: 33
classes:
- SixSigmaProject
- DefectMeasurement
- ControlChart
- FishboneDiagram
- DMAIC
- DMADV
- id
- name
- description
- methodology
- phase
- champion
- blackBelt
- greenBelt
- processOwner
- businessCase
- problemStatement
- goalStatement
- baselineSigmaLevel
- targetSigmaLevel
- baselineDPMO
- targetDPMO
- capabilityIndex
- estimatedAnnualSavings
- DPMO
- sigmaLevel
- defectsObserved
- opportunities
- processStep
- chartType
- centerLine
- upperControlLimit
- lowerControlLimit
context_file: json-ld/six-sigma-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/six-sigma/refs/heads/main/json-ld/six-sigma-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Six Sigma from Six Sigma.
layout: jsonld
name: Six Sigma Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: sixsigma
  uri: https://www.asq.org/quality-resources/six-sigma/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: qudt
  uri: http://qudt.org/schema/qudt/
properties:
- container: ''
  name: startDate
  type: date
- container: ''
  name: targetCompletionDate
  type: date
property_count: 2
provider_name: Six Sigma
provider_slug: six-sigma
slug: six-sigma-context
source_filename: six-sigma-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"sixsigma\": \"https://www.asq.org/quality-resources/six-sigma/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"qudt\": \"http://qudt.org/schema/qudt/\",\n\n    \"SixSigmaProject\": \"sixsigma:Project\",\n    \"DefectMeasurement\": \"sixsigma:DefectMeasurement\",\n    \"ControlChart\": \"sixsigma:ControlChart\",\n    \"FishboneDiagram\": \"sixsigma:FishboneDiagram\",\n    \"DMAIC\": \"sixsigma:DMAIC\",\n    \"DMADV\": \"sixsigma:DMADV\",\n\n    \"id\": \"@id\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"methodology\": \"sixsigma:methodology\",\n    \"phase\": \"sixsigma:phase\",\n    \"champion\": \"sixsigma:champion\",\n    \"blackBelt\": \"sixsigma:blackBelt\",\n    \"greenBelt\": \"sixsigma:greenBelt\",\n    \"processOwner\": \"sixsigma:processOwner\",\n    \"startDate\": {\n      \"@id\": \"schema:startDate\",\n      \"@type\"\
  : \"xsd:date\"\n    },\n    \"targetCompletionDate\": {\n      \"@id\": \"schema:endDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"businessCase\": \"sixsigma:businessCase\",\n    \"problemStatement\": \"schema:description\",\n    \"goalStatement\": \"sixsigma:goalStatement\",\n\n    \"baselineSigmaLevel\": \"sixsigma:baselineSigmaLevel\",\n    \"targetSigmaLevel\": \"sixsigma:targetSigmaLevel\",\n    \"baselineDPMO\": \"sixsigma:baselineDPMO\",\n    \"targetDPMO\": \"sixsigma:targetDPMO\",\n    \"capabilityIndex\": \"sixsigma:capabilityIndex\",\n    \"estimatedAnnualSavings\": \"schema:value\",\n\n    \"DPMO\": \"sixsigma:defectsPerMillionOpportunities\",\n    \"sigmaLevel\": \"sixsigma:sigmaLevel\",\n    \"defectsObserved\": \"sixsigma:defectsObserved\",\n    \"opportunities\": \"sixsigma:opportunities\",\n\n    \"processStep\": \"schema:step\",\n    \"chartType\": \"sixsigma:controlChartType\",\n    \"centerLine\": \"sixsigma:centerLine\",\n    \"upperControlLimit\": \"sixsigma:upperControlLimit\"\
  ,\n    \"lowerControlLimit\": \"sixsigma:lowerControlLimit\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/six-sigma/refs/heads/main/json-ld/six-sigma-context.jsonld
tags:
- Quality Management
- Process Improvement
- Lean Manufacturing
- Business Excellence
- Statistical Analysis
- DMAIC
- Operational Excellence
- JSON-LD
- Linked Data
- Semantic Web
---
