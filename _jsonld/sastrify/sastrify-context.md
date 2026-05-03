---
class_count: 5
classes:
- Organization
- name
- description
- url
- SoftwareApplication
context_file: json-ld/sastrify-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/sastrify/refs/heads/main/json-ld/sastrify-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Sastrify from Sastrify.
layout: jsonld
name: Sastrify Context
namespaces:
- prefix: sastrify
  uri: https://www.sastrify.com/ontology#
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: SaaSApplication
  type: reference
- container: ''
  name: SaaSSubscription
  type: reference
- container: ''
  name: LicenseInventory
  type: reference
- container: ''
  name: SpendBenchmark
  type: reference
- container: ''
  name: VendorNegotiation
  type: reference
- container: ''
  name: RenewalAlert
  type: reference
- container: ''
  name: UsageAnalytics
  type: reference
- container: ''
  name: SoftwareStack
  type: reference
- container: ''
  name: ProcurementWorkflow
  type: reference
- container: ''
  name: applicationName
  type: string
- container: ''
  name: vendorName
  type: string
- container: ''
  name: annualCost
  type: decimal
- container: ''
  name: currency
  type: string
- container: ''
  name: licenseCount
  type: integer
- container: ''
  name: activeUsers
  type: integer
- container: ''
  name: renewalDate
  type: date
- container: ''
  name: contractStartDate
  type: date
- container: ''
  name: paymentTerms
  type: string
- container: ''
  name: category
  type: string
- container: ''
  name: benchmarkSavingsPercent
  type: decimal
- container: ''
  name: utilizationRate
  type: decimal
property_count: 21
provider_name: Sastrify
provider_slug: sastrify
slug: sastrify-context
source_filename: sastrify-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"sastrify\": \"https://www.sastrify.com/ontology#\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"SaaSApplication\": {\n      \"@id\": \"sastrify:SaaSApplication\",\n      \"@type\": \"@id\",\n      \"comment\": \"A software-as-a-service application managed in the Sastrify platform\"\n    },\n    \"SaaSSubscription\": {\n      \"@id\": \"sastrify:SaaSSubscription\",\n      \"@type\": \"@id\",\n      \"comment\": \"A subscription contract for a SaaS application including license counts and renewal dates\"\n    },\n    \"LicenseInventory\": {\n      \"@id\": \"sastrify:LicenseInventory\",\n      \"@type\": \"@id\",\n      \"comment\": \"The set of licenses owned by an organization for a SaaS tool\"\n    },\n    \"SpendBenchmark\": {\n      \"@id\": \"sastrify:SpendBenchmark\",\n      \"@type\": \"@id\",\n      \"comment\": \"Market pricing benchmark data for a SaaS tool\
  \ category\"\n    },\n    \"VendorNegotiation\": {\n      \"@id\": \"sastrify:VendorNegotiation\",\n      \"@type\": \"@id\",\n      \"comment\": \"A procurement negotiation process managed through Sastrify\"\n    },\n    \"RenewalAlert\": {\n      \"@id\": \"sastrify:RenewalAlert\",\n      \"@type\": \"@id\",\n      \"comment\": \"A notification triggered ahead of a SaaS contract renewal date\"\n    },\n    \"UsageAnalytics\": {\n      \"@id\": \"sastrify:UsageAnalytics\",\n      \"@type\": \"@id\",\n      \"comment\": \"Usage data and activity metrics for a SaaS application\"\n    },\n    \"SoftwareStack\": {\n      \"@id\": \"sastrify:SoftwareStack\",\n      \"@type\": \"@id\",\n      \"comment\": \"The complete inventory of SaaS tools in use within an organization\"\n    },\n    \"ProcurementWorkflow\": {\n      \"@id\": \"sastrify:ProcurementWorkflow\",\n      \"@type\": \"@id\",\n      \"comment\": \"A structured process for evaluating, approving, and purchasing SaaS tools\"\n  \
  \  },\n\n    \"applicationName\": {\n      \"@id\": \"sastrify:applicationName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"vendorName\": {\n      \"@id\": \"sastrify:vendorName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"annualCost\": {\n      \"@id\": \"sastrify:annualCost\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"currency\": {\n      \"@id\": \"sastrify:currency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"licenseCount\": {\n      \"@id\": \"sastrify:licenseCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"activeUsers\": {\n      \"@id\": \"sastrify:activeUsers\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"renewalDate\": {\n      \"@id\": \"sastrify:renewalDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"contractStartDate\": {\n      \"@id\": \"sastrify:contractStartDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"paymentTerms\": {\n      \"@id\": \"sastrify:paymentTerms\",\n      \"@type\": \"xsd:string\"\n    },\n    \"category\"\
  : {\n      \"@id\": \"sastrify:category\",\n      \"@type\": \"xsd:string\"\n    },\n    \"benchmarkSavingsPercent\": {\n      \"@id\": \"sastrify:benchmarkSavingsPercent\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"utilizationRate\": {\n      \"@id\": \"sastrify:utilizationRate\",\n      \"@type\": \"xsd:decimal\"\n    },\n\n    \"Organization\": \"schema:Organization\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"SoftwareApplication\": \"schema:SoftwareApplication\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/sastrify/refs/heads/main/json-ld/sastrify-context.jsonld
tags:
- Cost Optimization
- License Management
- Procurement
- SaaS Management
- Software Spend
- Vendor Management
- JSON-LD
- Linked Data
- Semantic Web
---
