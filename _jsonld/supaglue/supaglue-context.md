---
api_specs:
- filename: supaglue-management-api-openapi.yml
  format: yaml
  label: Supaglue Management API
  slug: management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/supaglue/refs/heads/main/openapi/supaglue-management-api-openapi.yml
- filename: supaglue-crm-api-openapi.yml
  format: yaml
  label: Supaglue Unified CRM API
  slug: crm-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/supaglue/refs/heads/main/openapi/supaglue-crm-api-openapi.yml
- filename: supaglue-engagement-api-openapi.yml
  format: yaml
  label: Supaglue Unified Engagement API
  slug: engagement-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/supaglue/refs/heads/main/openapi/supaglue-engagement-api-openapi.yml
- filename: supaglue-ticketing-api-openapi.yml
  format: yaml
  label: Supaglue Unified Ticketing API
  slug: ticketing-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/supaglue/refs/heads/main/openapi/supaglue-ticketing-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/supaglue-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/supaglue/refs/heads/main/json-ld/supaglue-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Supaglue from Supaglue.
layout: jsonld
name: Supaglue Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: owl
  uri: http://www.w3.org/2002/07/owl#
- prefix: rdfs
  uri: http://www.w3.org/2000/01/rdf-schema#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: Customer
  type: ''
- container: ''
  name: Connection
  type: ''
- container: ''
  name: Provider
  type: ''
- container: ''
  name: Contact
  type: ''
- container: ''
  name: Account
  type: ''
- container: ''
  name: Opportunity
  type: ''
- container: ''
  name: Lead
  type: ''
- container: ''
  name: Sync
  type: ''
- container: ''
  name: Destination
  type: ''
- container: ''
  name: customerId
  type: ''
- container: ''
  name: providerName
  type: ''
- container: ''
  name: remoteId
  type: ''
- container: ''
  name: firstName
  type: ''
- container: ''
  name: lastName
  type: ''
- container: ''
  name: emailAddresses
  type: ''
- container: ''
  name: phoneNumbers
  type: ''
- container: ''
  name: accountId
  type: reference
- container: ''
  name: ownerId
  type: reference
- container: ''
  name: remoteCreatedAt
  type: dateTime
- container: ''
  name: remoteUpdatedAt
  type: dateTime
- container: ''
  name: syncStatus
  type: ''
- container: ''
  name: magicLink
  type: reference
property_count: 22
provider_name: Supaglue
provider_slug: supaglue
slug: supaglue-context
source_filename: supaglue-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"owl\": \"http://www.w3.org/2002/07/owl#\",\n    \"rdfs\": \"http://www.w3.org/2000/01/rdf-schema#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Customer\": {\n      \"@id\": \"schema:Person\",\n      \"rdfs:comment\": \"An end-user customer whose third-party CRM/HRIS is connected via Supaglue\"\n    },\n    \"Connection\": {\n      \"@id\": \"schema:APIConnection\",\n      \"rdfs:comment\": \"A link between a Supaglue customer and a specific third-party provider\"\n    },\n    \"Provider\": {\n      \"@id\": \"schema:SoftwareApplication\",\n      \"rdfs:comment\": \"A third-party SaaS application integrated via Supaglue (e.g. Salesforce, HubSpot)\"\n    },\n    \"Contact\": {\n      \"@id\": \"schema:Person\",\n      \"rdfs:comment\": \"A CRM contact record accessed via the Supaglue Unified CRM API\"\n    },\n    \"Account\": {\n      \"@id\": \"schema:Organization\"\
  ,\n      \"rdfs:comment\": \"A CRM account (company) record accessed via the Supaglue Unified CRM API\"\n    },\n    \"Opportunity\": {\n      \"@id\": \"schema:Offer\",\n      \"rdfs:comment\": \"A CRM sales opportunity record\"\n    },\n    \"Lead\": {\n      \"@id\": \"schema:Person\",\n      \"rdfs:comment\": \"A CRM lead record representing a potential customer\"\n    },\n    \"Sync\": {\n      \"@id\": \"schema:Action\",\n      \"rdfs:comment\": \"A data synchronization job from a provider to a destination\"\n    },\n    \"Destination\": {\n      \"@id\": \"schema:DataCatalog\",\n      \"rdfs:comment\": \"A data warehouse destination (BigQuery, Snowflake, Redshift, Postgres)\"\n    },\n    \"customerId\": {\n      \"@id\": \"schema:identifier\"\n    },\n    \"providerName\": {\n      \"@id\": \"schema:name\"\n    },\n    \"remoteId\": {\n      \"@id\": \"schema:identifier\",\n      \"rdfs:comment\": \"The provider-native identifier for a record\"\n    },\n    \"firstName\": {\n \
  \     \"@id\": \"schema:givenName\"\n    },\n    \"lastName\": {\n      \"@id\": \"schema:familyName\"\n    },\n    \"emailAddresses\": {\n      \"@id\": \"schema:email\"\n    },\n    \"phoneNumbers\": {\n      \"@id\": \"schema:telephone\"\n    },\n    \"accountId\": {\n      \"@id\": \"schema:memberOf\",\n      \"@type\": \"@id\"\n    },\n    \"ownerId\": {\n      \"@id\": \"schema:accountablePerson\",\n      \"@type\": \"@id\"\n    },\n    \"remoteCreatedAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"remoteUpdatedAt\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"syncStatus\": {\n      \"@id\": \"schema:actionStatus\"\n    },\n    \"magicLink\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/supaglue/refs/heads/main/json-ld/supaglue-context.jsonld
tags:
- CRM
- HRIS
- Unified API
- Open Source
- Integrations
- Sales Engagement
- JSON-LD
- Linked Data
- Semantic Web
---
