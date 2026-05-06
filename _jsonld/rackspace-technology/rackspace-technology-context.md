---
api_specs:
- filename: rackspace-cloud-dns.yaml
  format: yaml
  label: Rackspace Cloud DNS API
  slug: cloud-dns-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/rackspace-technology/refs/heads/main/openapi/rackspace-cloud-dns.yaml
- filename: rackspace-customer-service.yaml
  format: yaml
  label: Rackspace Customer Service API
  slug: customer-service-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/rackspace-technology/refs/heads/main/openapi/rackspace-customer-service.yaml
- filename: rackspace-cloud-identity.yaml
  format: yaml
  label: Rackspace Customer Identity API
  slug: customer-identity-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/rackspace-technology/refs/heads/main/openapi/rackspace-cloud-identity.yaml
- filename: rackspace-offer.yaml
  format: yaml
  label: Rackspace Offer API
  slug: offer-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/rackspace-technology/refs/heads/main/openapi/rackspace-offer.yaml
class_count: 42
classes:
- Rackspace
- name
- description
- url
- tenant
- tenantId
- accountId
- rcn
- Domain
- DomainList
- Record
- RecordList
- ttl
- type
- data
- priority
- User
- username
- Token
- Role
- Tenant
- Endpoint
- region
- ServiceCatalogEntry
- CustomerAccount
- Contact
- Metadata
- Offering
- Product
- offeringCode
- offeringVersion
- lineOfBusiness
- status
- currency
- listPrice
- Limit
- AsyncJob
- jobId
- Fault
- code
- message
- details
context_file: json-ld/rackspace-technology-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/rackspace-technology/refs/heads/main/json-ld/rackspace-technology-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Rackspace Technology from Rackspace Technology.
layout: jsonld
name: Rackspace Technology Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: rax
  uri: https://docs.rackspace.com/vocab/
- prefix: openapi
  uri: https://spec.openapis.org/oas/3.0.3/
- prefix: jsonschema
  uri: https://json-schema.org/draft/2020-12/schema
properties:
- container: ''
  name: email
  type: schema:Email
- container: ''
  name: id
  type: schema:Text
- container: ''
  name: created
  type: schema:DateTime
- container: ''
  name: updated
  type: schema:DateTime
- container: ''
  name: expires
  type: schema:DateTime
- container: ''
  name: domain
  type: reference
- container: ''
  name: publicURL
  type: reference
- container: ''
  name: internalURL
  type: reference
- container: ''
  name: callbackUrl
  type: reference
property_count: 9
provider_name: Rackspace Technology
provider_slug: rackspace-technology
slug: rackspace-technology-context
source_filename: rackspace-technology-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"rax\": \"https://docs.rackspace.com/vocab/\",\n    \"openapi\": \"https://spec.openapis.org/oas/3.0.3/\",\n    \"jsonschema\": \"https://json-schema.org/draft/2020-12/schema\",\n    \"Rackspace\": \"schema:Organization\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"email\": { \"@id\": \"schema:email\", \"@type\": \"schema:Email\" },\n    \"id\": { \"@id\": \"schema:identifier\", \"@type\": \"schema:Text\" },\n    \"created\": { \"@id\": \"schema:dateCreated\", \"@type\": \"schema:DateTime\" },\n    \"updated\": { \"@id\": \"schema:dateModified\", \"@type\": \"schema:DateTime\" },\n    \"expires\": { \"@id\": \"schema:expires\", \"@type\": \"schema:DateTime\" },\n    \"tenant\": \"rax:tenant\",\n    \"tenantId\": \"rax:tenantId\",\n    \"accountId\": \"rax:accountId\",\n    \"rcn\": \"rax:rackspaceCustomerNumber\"\
  ,\n    \"domain\": { \"@id\": \"rax:Domain\", \"@type\": \"@id\" },\n    \"Domain\": \"rax:Domain\",\n    \"DomainList\": \"rax:DomainList\",\n    \"Record\": \"rax:Record\",\n    \"RecordList\": \"rax:RecordList\",\n    \"ttl\": \"rax:ttl\",\n    \"type\": \"schema:additionalType\",\n    \"data\": \"rax:recordData\",\n    \"priority\": \"rax:priority\",\n    \"User\": \"schema:Person\",\n    \"username\": \"schema:alternateName\",\n    \"Token\": \"rax:Token\",\n    \"Role\": \"rax:Role\",\n    \"Tenant\": \"rax:Tenant\",\n    \"Endpoint\": \"rax:ServiceCatalogEndpoint\",\n    \"publicURL\": { \"@id\": \"rax:publicURL\", \"@type\": \"@id\" },\n    \"internalURL\": { \"@id\": \"rax:internalURL\", \"@type\": \"@id\" },\n    \"region\": \"rax:region\",\n    \"ServiceCatalogEntry\": \"rax:ServiceCatalogEntry\",\n    \"CustomerAccount\": \"schema:Account\",\n    \"Contact\": \"schema:Person\",\n    \"Metadata\": \"rax:Metadata\",\n    \"Offering\": \"schema:Offer\",\n    \"Product\": \"schema:Product\"\
  ,\n    \"offeringCode\": \"rax:offeringCode\",\n    \"offeringVersion\": \"rax:offeringVersion\",\n    \"lineOfBusiness\": \"rax:lineOfBusiness\",\n    \"status\": \"schema:itemStatus\",\n    \"currency\": \"schema:priceCurrency\",\n    \"listPrice\": \"schema:price\",\n    \"Limit\": \"rax:Limit\",\n    \"AsyncJob\": \"rax:AsyncJob\",\n    \"callbackUrl\": { \"@id\": \"rax:callbackUrl\", \"@type\": \"@id\" },\n    \"jobId\": \"rax:jobId\",\n    \"Fault\": \"schema:Error\",\n    \"code\": \"schema:errorCode\",\n    \"message\": \"schema:description\",\n    \"details\": \"rax:errorDetails\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/rackspace-technology/refs/heads/main/json-ld/rackspace-technology-context.jsonld
tags:
- Cloud
- Managed Services
- Multicloud
- Infrastructure
- DevOps
- JSON-LD
- Linked Data
- Semantic Web
---
