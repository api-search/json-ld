---
class_count: 9
classes:
- activity_id
- name
- category
- sector
- source
- region
- data_version
- co2e_calculation_method
- constituent_gases
context_file: json-ld/climatiq-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/climatiq/refs/heads/main/json-ld/climatiq-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Climatiq from Climatiq.
layout: jsonld
name: Climatiq Context
namespaces:
- prefix: climatiq
  uri: https://www.climatiq.io/schemas/
- prefix: schema
  uri: https://schema.org/
- prefix: qudt
  uri: http://qudt.org/schema/qudt/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: EmissionFactor
  type: ''
- container: ''
  name: EmissionEstimate
  type: schema:QuantitativeValue
- container: ''
  name: Activity
  type: schema:Action
- container: ''
  name: year
  type: gYear
- container: ''
  name: co2e
  type: decimal
- container: ''
  name: co2e_unit
  type: ''
property_count: 6
provider_name: Climatiq
provider_slug: climatiq
slug: climatiq-context
tags:
- Carbon Accounting
- Carbon Emissions
- Climate
- Energy
- Environment
- GHG Protocol
- Sustainability
- JSON-LD
- Linked Data
- Semantic Web
---
