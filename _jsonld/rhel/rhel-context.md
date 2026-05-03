---
api_specs:
- filename: openapi.json
  format: json
  label: Red Hat Subscription Management API
  slug: subscription-management-api
  spec_type: OpenAPI
  url: https://api.access.redhat.com/management/v1/openapi.json
- filename: openapi.json
  format: json
  label: Red Hat Insights API
  slug: insights-api
  spec_type: OpenAPI
  url: https://cloud.redhat.com/api/insights/v1/openapi.json
- filename: rhel-security-data-openapi.yml
  format: yaml
  label: Red Hat Security Data API
  slug: security-data-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/rhel/refs/heads/main/openapi/rhel-security-data-openapi.yml
- filename: openapi.json
  format: json
  label: Red Hat Insights Compliance API
  slug: compliance-api
  spec_type: OpenAPI
  url: https://console.redhat.com/api/compliance/v2/openapi.json
- filename: openapi.json
  format: json
  label: Red Hat Insights Vulnerability API
  slug: vulnerability-api
  spec_type: OpenAPI
  url: https://console.redhat.com/api/vulnerability/v1/openapi.json
- filename: openapi.json
  format: json
  label: Red Hat Insights Patch API
  slug: patch-api
  spec_type: OpenAPI
  url: https://console.redhat.com/api/patch/v3/openapi.json
- filename: openapi.json
  format: json
  label: Red Hat Insights Host Inventory API
  slug: inventory-api
  spec_type: OpenAPI
  url: https://console.redhat.com/api/inventory/v1/openapi.json
- filename: openapi.json
  format: json
  label: Red Hat Insights Remediations API
  slug: remediations-api
  spec_type: OpenAPI
  url: https://console.redhat.com/api/remediations/v1/openapi.json
class_count: 33
classes:
- CVE
- System
- Subscription
- Advisory
- Entitlement
- cveId
- threatSeverity
- cvssScore
- cvss3Score
- publicDate
- affectedRelease
- packageState
- fixState
- cpe
- systemUUID
- entitlementStatus
- entitlementCount
- serviceLevel
- systemType
- subscriptionNumber
- sku
- startDate
- endDate
- subscriptionStatus
- advisoryId
- advisoryType
- name
- description
- url
- identifier
- version
- dateCreated
- dateModified
context_file: json-ld/rhel-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/rhel/refs/heads/main/json-ld/rhel-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Rhel from Red Hat Enterprise Linux.
layout: jsonld
name: Rhel Context
namespaces:
- prefix: rhel
  uri: https://redhat.com/vocab/rhel#
- prefix: security
  uri: https://redhat.com/vocab/security#
properties: []
property_count: 0
provider_name: Red Hat Enterprise Linux
provider_slug: rhel
slug: rhel-context
source_filename: rhel-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"rhel\": \"https://redhat.com/vocab/rhel#\",\n    \"security\": \"https://redhat.com/vocab/security#\",\n\n    \"CVE\": \"rhel:CVE\",\n    \"System\": \"rhel:System\",\n    \"Subscription\": \"rhel:Subscription\",\n    \"Advisory\": \"rhel:Advisory\",\n    \"Entitlement\": \"rhel:Entitlement\",\n\n    \"cveId\": \"rhel:cveId\",\n    \"threatSeverity\": \"rhel:threatSeverity\",\n    \"cvssScore\": \"rhel:cvssScore\",\n    \"cvss3Score\": \"rhel:cvss3Score\",\n    \"publicDate\": \"schema:datePublished\",\n    \"affectedRelease\": \"rhel:affectedRelease\",\n    \"packageState\": \"rhel:packageState\",\n    \"fixState\": \"rhel:fixState\",\n    \"cpe\": \"rhel:cpe\",\n\n    \"systemUUID\": \"rhel:systemUUID\",\n    \"entitlementStatus\": \"rhel:entitlementStatus\",\n    \"entitlementCount\": \"rhel:entitlementCount\",\n    \"serviceLevel\": \"rhel:serviceLevel\",\n    \"systemType\": \"rhel:systemType\",\n\n\
  \    \"subscriptionNumber\": \"rhel:subscriptionNumber\",\n    \"sku\": \"rhel:sku\",\n    \"startDate\": \"schema:startDate\",\n    \"endDate\": \"schema:endDate\",\n    \"subscriptionStatus\": \"rhel:subscriptionStatus\",\n\n    \"advisoryId\": \"rhel:advisoryId\",\n    \"advisoryType\": \"rhel:advisoryType\",\n\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"identifier\": \"schema:identifier\",\n    \"version\": \"schema:version\",\n    \"dateCreated\": \"schema:dateCreated\",\n    \"dateModified\": \"schema:dateModified\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/rhel/refs/heads/main/json-ld/rhel-context.jsonld
tags:
- Automation
- Compliance
- Enterprise
- Linux
- Operating System
- Red Hat
- RHEL
- Security
- Subscription Management
- Vulnerability Management
- JSON-LD
- Linked Data
- Semantic Web
---
