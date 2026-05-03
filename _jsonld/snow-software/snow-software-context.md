---
api_specs:
- filename: snow-software-licenses-openapi.yml
  format: yaml
  label: Snow Atlas SAM Licenses API
  slug: snow-atlas-licenses-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/snow-software/refs/heads/main/openapi/snow-software-licenses-openapi.yml
- filename: snow-software-saas-applications-openapi.yml
  format: yaml
  label: Snow Atlas SaaS Applications API
  slug: snow-atlas-saas-applications-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/snow-software/refs/heads/main/openapi/snow-software-saas-applications-openapi.yml
- filename: snow-software-saas-subscriptions-openapi.yml
  format: yaml
  label: Snow Atlas SaaS Subscriptions API
  slug: snow-atlas-saas-subscriptions-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/snow-software/refs/heads/main/openapi/snow-software-saas-subscriptions-openapi.yml
- filename: snow-software-computers-openapi.json
  format: json
  label: Snow Atlas SAM Computers API
  slug: snow-atlas-computers-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/snow-software/refs/heads/main/openapi/snow-software-computers-openapi.json
class_count: 6
classes:
- name
- description
- url
- Organization
- SoftwareApplication
- Product
context_file: json-ld/snow-software-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/snow-software/refs/heads/main/json-ld/snow-software-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Snow Software from Snow Software.
layout: jsonld
name: Snow Software Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
- prefix: snow
  uri: https://api-evangelist.github.io/snow-software/vocabulary/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: ITAssetManagementPlatform
  type: schema:SoftwareApplication
- container: ''
  name: SoftwareLicense
  type: schema:Permit
- container: ''
  name: SaaSApplication
  type: schema:SoftwareApplication
- container: ''
  name: SaaSSubscription
  type: schema:Order
- container: ''
  name: Computer
  type: schema:ComputerSystem
- container: ''
  name: LicensePolicy
  type: schema:CreativeWork
- container: ''
  name: Agreement
  type: schema:Contract
- container: ''
  name: licenseType
  type: string
- container: ''
  name: quantity
  type: integer
- container: ''
  name: usedQuantity
  type: integer
- container: ''
  name: availableQuantity
  type: integer
- container: ''
  name: expirationDate
  type: date
- container: ''
  name: maintenanceExpirationDate
  type: date
- container: ''
  name: utilizationRate
  type: decimal
- container: ''
  name: costPerUser
  type: decimal
- container: ''
  name: annualSpend
  type: decimal
- container: ''
  name: potentialSavings
  type: decimal
- container: ''
  name: activeUsers
  type: integer
- container: ''
  name: totalUsers
  type: integer
- container: ''
  name: discoverySource
  type: string
- container: ''
  name: dataRegion
  type: string
- container: ''
  name: hostname
  type: string
- container: ''
  name: operatingSystem
  type: string
- container: ''
  name: vendor
  type: string
- container: ''
  name: renewalDate
  type: date
- container: ''
  name: contractEndDate
  type: date
- container: ''
  name: licenseCount
  type: integer
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: updatedAt
  type: dateTime
property_count: 29
provider_name: Snow Software
provider_slug: snow-software
slug: snow-software-context
source_filename: snow-software-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"snow\": \"https://api-evangelist.github.io/snow-software/vocabulary/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"Organization\": \"schema:Organization\",\n    \"SoftwareApplication\": \"schema:SoftwareApplication\",\n    \"Product\": \"schema:Product\",\n    \"ITAssetManagementPlatform\": {\n      \"@id\": \"snow:ITAssetManagementPlatform\",\n      \"@type\": \"schema:SoftwareApplication\"\n    },\n    \"SoftwareLicense\": {\n      \"@id\": \"snow:SoftwareLicense\",\n      \"@type\": \"schema:Permit\"\n    },\n    \"SaaSApplication\": {\n      \"@id\": \"snow:SaaSApplication\",\n      \"@type\": \"schema:SoftwareApplication\"\n    },\n    \"SaaSSubscription\": {\n      \"@id\": \"snow:SaaSSubscription\",\n  \
  \    \"@type\": \"schema:Order\"\n    },\n    \"Computer\": {\n      \"@id\": \"snow:Computer\",\n      \"@type\": \"schema:ComputerSystem\"\n    },\n    \"LicensePolicy\": {\n      \"@id\": \"snow:LicensePolicy\",\n      \"@type\": \"schema:CreativeWork\"\n    },\n    \"Agreement\": {\n      \"@id\": \"snow:Agreement\",\n      \"@type\": \"schema:Contract\"\n    },\n    \"licenseType\": {\n      \"@id\": \"snow:licenseType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"quantity\": {\n      \"@id\": \"snow:quantity\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"usedQuantity\": {\n      \"@id\": \"snow:usedQuantity\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"availableQuantity\": {\n      \"@id\": \"snow:availableQuantity\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"expirationDate\": {\n      \"@id\": \"snow:expirationDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"maintenanceExpirationDate\": {\n      \"@id\": \"snow:maintenanceExpirationDate\",\n      \"@type\"\
  : \"xsd:date\"\n    },\n    \"utilizationRate\": {\n      \"@id\": \"snow:utilizationRate\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"costPerUser\": {\n      \"@id\": \"snow:costPerUser\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"annualSpend\": {\n      \"@id\": \"snow:annualSpend\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"potentialSavings\": {\n      \"@id\": \"snow:potentialSavings\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"activeUsers\": {\n      \"@id\": \"snow:activeUsers\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"totalUsers\": {\n      \"@id\": \"snow:totalUsers\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"discoverySource\": {\n      \"@id\": \"snow:discoverySource\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dataRegion\": {\n      \"@id\": \"snow:dataRegion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"hostname\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"operatingSystem\": {\n\
  \      \"@id\": \"schema:operatingSystem\",\n      \"@type\": \"xsd:string\"\n    },\n    \"vendor\": {\n      \"@id\": \"schema:manufacturer\",\n      \"@type\": \"xsd:string\"\n    },\n    \"renewalDate\": {\n      \"@id\": \"snow:renewalDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"contractEndDate\": {\n      \"@id\": \"snow:contractEndDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"licenseCount\": {\n      \"@id\": \"snow:licenseCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/snow-software/refs/heads/main/json-ld/snow-software-context.jsonld
tags:
- Cloud License Management
- FinOps
- IT Asset Management
- SaaS Management
- Software Asset Management
- JSON-LD
- Linked Data
- Semantic Web
---
