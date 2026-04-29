---
class_count: 1
classes:
- id
context_file: json-ld/hubspot-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/hubspot/refs/heads/main/json-ld/hubspot-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Hubspot from HubSpot.
layout: jsonld
name: Hubspot Context
namespaces:
- prefix: hubspot
  uri: https://developers.hubspot.com/docs/api/schemas/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: rdfs
  uri: http://www.w3.org/2000/01/rdf-schema#
properties:
- container: ''
  name: Contact
  type: rdfs:Class
- container: ''
  name: Company
  type: rdfs:Class
- container: ''
  name: Deal
  type: rdfs:Class
- container: ''
  name: Ticket
  type: rdfs:Class
- container: ''
  name: Engagement
  type: rdfs:Class
- container: ''
  name: WebhookEvent
  type: rdfs:Class
- container: ''
  name: email
  type: string
- container: ''
  name: firstName
  type: string
- container: ''
  name: lastname
  type: string
- container: ''
  name: phone
  type: string
- container: ''
  name: mobilephone
  type: string
- container: ''
  name: company
  type: string
- container: ''
  name: website
  type: anyURI
- container: ''
  name: jobtitle
  type: string
- container: ''
  name: address
  type: string
- container: ''
  name: city
  type: string
- container: ''
  name: state
  type: string
- container: ''
  name: country
  type: string
- container: ''
  name: zip
  type: string
- container: ''
  name: name
  type: string
- container: ''
  name: domain
  type: anyURI
- container: ''
  name: description
  type: string
- container: ''
  name: numberofemployees
  type: integer
- container: ''
  name: annualrevenue
  type: decimal
- container: ''
  name: dealname
  type: string
- container: ''
  name: amount
  type: decimal
- container: ''
  name: dealstage
  type: string
- container: ''
  name: closedate
  type: date
- container: ''
  name: pipeline
  type: string
- container: ''
  name: subject
  type: string
- container: ''
  name: content
  type: string
- container: ''
  name: hs_ticket_priority
  type: string
- container: ''
  name: hs_pipeline_stage
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: associations
  type: ''
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: updatedAt
  type: dateTime
- container: ''
  name: archived
  type: boolean
- container: ''
  name: eventId
  type: ''
- container: ''
  name: objectId
  type: integer
- container: ''
  name: portalId
  type: integer
- container: ''
  name: occurredAt
  type: long
- container: ''
  name: subscriptionType
  type: string
- container: ''
  name: changeSource
  type: string
- container: ''
  name: changeFlag
  type: string
- container: ''
  name: propertyName
  type: string
- container: ''
  name: propertyValue
  type: string
- container: ''
  name: subscriptionId
  type: integer
- container: ''
  name: appId
  type: integer
property_count: 49
provider_name: HubSpot
provider_slug: hubspot
slug: hubspot-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"hubspot\": \"https://developers.hubspot.com/docs/api/schemas/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"rdfs\": \"http://www.w3.org/2000/01/rdf-schema#\",\n\n    \"Contact\": {\n      \"@id\": \"hubspot:Contact\",\n      \"@type\": \"rdfs:Class\",\n      \"rdfs:subClassOf\": { \"@id\": \"schema:Person\" },\n      \"rdfs:label\": \"HubSpot Contact\",\n      \"rdfs:comment\": \"A contact record in HubSpot CRM representing an individual person.\"\n    },\n    \"Company\": {\n      \"@id\": \"hubspot:Company\",\n      \"@type\": \"rdfs:Class\",\n      \"rdfs:subClassOf\": { \"@id\": \"schema:Organization\" },\n      \"rdfs:label\": \"HubSpot Company\",\n      \"rdfs:comment\": \"A company record in HubSpot CRM representing a business or organization.\"\n    },\n    \"Deal\": {\n      \"@id\": \"hubspot:Deal\",\n    \
  \  \"@type\": \"rdfs:Class\",\n      \"rdfs:label\": \"HubSpot Deal\",\n      \"rdfs:comment\": \"A deal record in HubSpot CRM representing a sales opportunity.\"\n    },\n    \"Ticket\": {\n      \"@id\": \"hubspot:Ticket\",\n      \"@type\": \"rdfs:Class\",\n      \"rdfs:label\": \"HubSpot Ticket\",\n      \"rdfs:comment\": \"A ticket record in HubSpot CRM representing a customer support request.\"\n    },\n    \"Engagement\": {\n      \"@id\": \"hubspot:Engagement\",\n      \"@type\": \"rdfs:Class\",\n      \"rdfs:label\": \"HubSpot Engagement\",\n      \"rdfs:comment\": \"An engagement record in HubSpot CRM representing an activity such as a call, meeting, email, note, or task.\"\n    },\n    \"WebhookEvent\": {\n      \"@id\": \"hubspot:WebhookEvent\",\n      \"@type\": \"rdfs:Class\",\n      \"rdfs:label\": \"HubSpot Webhook Event\",\n      \"rdfs:comment\": \"An event notification delivered via HubSpot webhooks when a CRM object or conversation changes.\"\n    },\n\n    \"id\":\
  \ \"@id\",\n\n    \"email\": {\n      \"@id\": \"schema:email\",\n      \"@type\": \"xsd:string\"\n    },\n    \"firstName\": {\n      \"@id\": \"schema:givenName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastname\": {\n      \"@id\": \"schema:familyName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"phone\": {\n      \"@id\": \"schema:telephone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mobilephone\": {\n      \"@id\": \"schema:telephone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"company\": {\n      \"@id\": \"schema:worksFor\",\n      \"@type\": \"xsd:string\"\n    },\n    \"website\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"xsd:anyURI\"\n    },\n    \"jobtitle\": {\n      \"@id\": \"schema:jobTitle\",\n      \"@type\": \"xsd:string\"\n    },\n    \"address\": {\n      \"@id\": \"schema:streetAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"city\": {\n      \"@id\": \"schema:addressLocality\",\n      \"@type\": \"xsd:string\"\n   \
  \ },\n    \"state\": {\n      \"@id\": \"schema:addressRegion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"country\": {\n      \"@id\": \"schema:addressCountry\",\n      \"@type\": \"xsd:string\"\n    },\n    \"zip\": {\n      \"@id\": \"schema:postalCode\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"domain\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"xsd:anyURI\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"numberofemployees\": {\n      \"@id\": \"schema:numberOfEmployees\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"annualrevenue\": {\n      \"@id\": \"schema:revenue\",\n      \"@type\": \"xsd:decimal\"\n    },\n\n    \"dealname\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"amount\": {\n      \"@id\": \"hubspot:amount\",\n      \"@type\": \"xsd:decimal\"\
  \n    },\n    \"dealstage\": {\n      \"@id\": \"hubspot:dealStage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"closedate\": {\n      \"@id\": \"hubspot:closeDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"pipeline\": {\n      \"@id\": \"hubspot:pipeline\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"subject\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"content\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"hs_ticket_priority\": {\n      \"@id\": \"hubspot:ticketPriority\",\n      \"@type\": \"xsd:string\"\n    },\n    \"hs_pipeline_stage\": {\n      \"@id\": \"hubspot:pipelineStage\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"type\": {\n      \"@id\": \"hubspot:engagementType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"associations\": {\n      \"@id\": \"hubspot:associations\"\n    },\n\n    \"createdAt\": {\n      \"@id\": \"dcterms:created\",\n      \"@type\": \"xsd:dateTime\"\
  \n    },\n    \"updatedAt\": {\n      \"@id\": \"dcterms:modified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"archived\": {\n      \"@id\": \"hubspot:archived\",\n      \"@type\": \"xsd:boolean\"\n    },\n\n    \"eventId\": {\n      \"@id\": \"@id\"\n    },\n    \"objectId\": {\n      \"@id\": \"hubspot:objectId\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"portalId\": {\n      \"@id\": \"hubspot:portalId\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"occurredAt\": {\n      \"@id\": \"dcterms:date\",\n      \"@type\": \"xsd:long\"\n    },\n    \"subscriptionType\": {\n      \"@id\": \"hubspot:subscriptionType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"changeSource\": {\n      \"@id\": \"hubspot:changeSource\",\n      \"@type\": \"xsd:string\"\n    },\n    \"changeFlag\": {\n      \"@id\": \"hubspot:changeFlag\",\n      \"@type\": \"xsd:string\"\n    },\n    \"propertyName\": {\n      \"@id\": \"hubspot:propertyName\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"propertyValue\": {\n      \"@id\": \"hubspot:propertyValue\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subscriptionId\": {\n      \"@id\": \"hubspot:subscriptionId\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"appId\": {\n      \"@id\": \"hubspot:appId\",\n      \"@type\": \"xsd:integer\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/hubspot/refs/heads/main/json-ld/hubspot-context.jsonld
tags:
- Analytics
- Commerce
- Content
- CRM
- Customer Service
- Email Marketing
- Marketing
- Marketing Automation
- Operations
- Sales
- JSON-LD
- Linked Data
- Semantic Web
---
