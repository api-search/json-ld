---
class_count: 14
classes:
- SupplyChain
- Supplier
- DisruptionEvent
- RiskAssessment
- MitigationPlan
- tier
- risk_score
- status
- parts
- sites
- event_type
- severity
- affected_suppliers
- affected_parts
context_file: json-ld/resilinc-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/resilinc/refs/heads/main/json-ld/resilinc-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Resilinc from Resilinc.
layout: jsonld
name: Resilinc Context
namespaces:
- prefix: resilinc
  uri: https://resilinc.ai/vocab/
- prefix: Organization
  uri: https://schema.org/Organization
- prefix: id
  uri: https://schema.org/identifier
- prefix: name
  uri: https://schema.org/name
- prefix: description
  uri: https://schema.org/description
- prefix: country
  uri: https://schema.org/addressCountry
- prefix: region
  uri: https://schema.org/addressRegion
- prefix: city
  uri: https://schema.org/addressLocality
- prefix: industry
  uri: https://schema.org/industry
- prefix: location
  uri: https://schema.org/Place
- prefix: published_at
  uri: https://schema.org/datePublished
- prefix: started_at
  uri: https://schema.org/startDate
- prefix: resolved_at
  uri: https://schema.org/endDate
- prefix: source_urls
  uri: https://schema.org/url
- prefix: created_at
  uri: https://schema.org/dateCreated
- prefix: updated_at
  uri: https://schema.org/dateModified
properties: []
property_count: 0
provider_name: Resilinc
provider_slug: resilinc
slug: resilinc-context
source_filename: resilinc-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"resilinc\": \"https://resilinc.ai/vocab/\",\n    \"Organization\": \"https://schema.org/Organization\",\n    \"SupplyChain\": \"resilinc:SupplyChain\",\n    \"Supplier\": \"resilinc:Supplier\",\n    \"DisruptionEvent\": \"resilinc:DisruptionEvent\",\n    \"RiskAssessment\": \"resilinc:RiskAssessment\",\n    \"MitigationPlan\": \"resilinc:MitigationPlan\",\n    \"id\": \"https://schema.org/identifier\",\n    \"name\": \"https://schema.org/name\",\n    \"description\": \"https://schema.org/description\",\n    \"country\": \"https://schema.org/addressCountry\",\n    \"region\": \"https://schema.org/addressRegion\",\n    \"city\": \"https://schema.org/addressLocality\",\n    \"industry\": \"https://schema.org/industry\",\n    \"tier\": \"resilinc:supplierTier\",\n    \"risk_score\": \"resilinc:riskScore\",\n    \"status\": \"resilinc:status\",\n    \"parts\": \"resilinc:parts\",\n    \"sites\": \"resilinc:sites\"\
  ,\n    \"event_type\": \"resilinc:eventType\",\n    \"severity\": \"resilinc:severity\",\n    \"location\": \"https://schema.org/Place\",\n    \"affected_suppliers\": \"resilinc:affectedSuppliers\",\n    \"affected_parts\": \"resilinc:affectedParts\",\n    \"published_at\": \"https://schema.org/datePublished\",\n    \"started_at\": \"https://schema.org/startDate\",\n    \"resolved_at\": \"https://schema.org/endDate\",\n    \"source_urls\": \"https://schema.org/url\",\n    \"created_at\": \"https://schema.org/dateCreated\",\n    \"updated_at\": \"https://schema.org/dateModified\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/resilinc/refs/heads/main/json-ld/resilinc-context.jsonld
tags:
- Supply Chain
- Risk Management
- Supplier Intelligence
- Disruption Monitoring
- AI
- JSON-LD
- Linked Data
- Semantic Web
---
