---
class_count: 6
classes:
- LegalEntityAssociation
- LegalEntityCapability
- LegalEntityInfoRequiredType
- LegalEntityInfo
- LegalEntity
- name
context_file: json-ld/adyen-legal-entity-legal-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-legal-entity-legal-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Legal Entity Legal from Adyen.
layout: jsonld
name: Adyen Legal Entity Legal Context
namespaces:
- prefix: adyen
  uri: https://docs.adyen.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: associatorId
  type: string
- container: ''
  name: entityType
  type: string
- container: ''
  name: jobTitle
  type: string
- container: ''
  name: legalEntityId
  type: string
- container: set
  name: settlorExemptionReason
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: allowed
  type: boolean
- container: ''
  name: allowedLevel
  type: string
- container: ''
  name: allowedSettings
  type: string
- container: ''
  name: requested
  type: boolean
- container: ''
  name: requestedLevel
  type: string
- container: ''
  name: requestedSettings
  type: string
- container: set
  name: transferInstruments
  type: string
- container: ''
  name: verificationStatus
  type: string
- container: ''
  name: capabilities
  type: reference
- container: set
  name: entityAssociations
  type: string
- container: ''
  name: individual
  type: string
- container: ''
  name: organization
  type: string
- container: ''
  name: reference
  type: string
- container: ''
  name: soleProprietorship
  type: string
- container: ''
  name: trust
  type: string
- container: ''
  name: unincorporatedPartnership
  type: string
- container: ''
  name: verificationPlan
  type: string
- container: set
  name: documentDetails
  type: string
- container: set
  name: documents
  type: string
- container: ''
  name: id
  type: string
- container: set
  name: problems
  type: string
- container: set
  name: verificationDeadlines
  type: string
property_count: 28
provider_name: Adyen
provider_slug: adyen
slug: adyen-legal-entity-legal-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"LegalEntityAssociation\": \"adyen:LegalEntityAssociation\",\n    \"LegalEntityCapability\": \"adyen:LegalEntityCapability\",\n    \"LegalEntityInfoRequiredType\": \"adyen:LegalEntityInfoRequiredType\",\n    \"LegalEntityInfo\": \"adyen:LegalEntityInfo\",\n    \"LegalEntity\": \"adyen:LegalEntity\",\n    \"associatorId\": {\n      \"@id\": \"adyen:associatorId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"entityType\": {\n      \"@id\": \"adyen:entityType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"jobTitle\": {\n      \"@id\": \"adyen:jobTitle\",\n      \"@type\": \"xsd:string\"\n    },\n    \"legalEntityId\": {\n      \"@id\": \"adyen:legalEntityId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\"\
  ,\n    \"settlorExemptionReason\": {\n      \"@id\": \"adyen:settlorExemptionReason\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"adyen:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"allowed\": {\n      \"@id\": \"adyen:allowed\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"allowedLevel\": {\n      \"@id\": \"adyen:allowedLevel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"allowedSettings\": {\n      \"@id\": \"adyen:allowedSettings\",\n      \"@type\": \"xsd:string\"\n    },\n    \"requested\": {\n      \"@id\": \"adyen:requested\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"requestedLevel\": {\n      \"@id\": \"adyen:requestedLevel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"requestedSettings\": {\n      \"@id\": \"adyen:requestedSettings\",\n      \"@type\": \"xsd:string\"\n    },\n    \"transferInstruments\": {\n      \"@id\": \"adyen:transferInstruments\",\n      \"@container\": \"@set\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"verificationStatus\": {\n      \"@id\": \"adyen:verificationStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"capabilities\": {\n      \"@id\": \"adyen:capabilities\",\n      \"@type\": \"@id\"\n    },\n    \"entityAssociations\": {\n      \"@id\": \"adyen:entityAssociations\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"individual\": {\n      \"@id\": \"adyen:individual\",\n      \"@type\": \"xsd:string\"\n    },\n    \"organization\": {\n      \"@id\": \"adyen:organization\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reference\": {\n      \"@id\": \"adyen:reference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"soleProprietorship\": {\n      \"@id\": \"adyen:soleProprietorship\",\n      \"@type\": \"xsd:string\"\n    },\n    \"trust\": {\n      \"@id\": \"adyen:trust\",\n      \"@type\": \"xsd:string\"\n    },\n    \"unincorporatedPartnership\": {\n      \"@id\": \"adyen:unincorporatedPartnership\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"verificationPlan\": {\n      \"@id\": \"adyen:verificationPlan\",\n      \"@type\": \"xsd:string\"\n    },\n    \"documentDetails\": {\n      \"@id\": \"adyen:documentDetails\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"documents\": {\n      \"@id\": \"adyen:documents\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"adyen:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"problems\": {\n      \"@id\": \"adyen:problems\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"verificationDeadlines\": {\n      \"@id\": \"adyen:verificationDeadlines\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-legal-entity-legal-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
