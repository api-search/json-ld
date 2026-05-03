---
api_specs:
- filename: tm-forum-tmf620-product-catalog-openapi.yaml
  format: yaml
  label: TMF620 Product Catalog Management
  slug: tmf620-product-catalog
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tm-forum/refs/heads/main/openapi/tm-forum-tmf620-product-catalog-openapi.yaml
- filename: tm-forum-tmf621-trouble-ticket-openapi.yaml
  format: yaml
  label: TMF621 Trouble Ticket Management
  slug: tmf621-trouble-ticket
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tm-forum/refs/heads/main/openapi/tm-forum-tmf621-trouble-ticket-openapi.yaml
- filename: tm-forum-tmf622-product-ordering-openapi.yaml
  format: yaml
  label: TMF622 Product Order Management
  slug: tmf622-product-ordering
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tm-forum/refs/heads/main/openapi/tm-forum-tmf622-product-ordering-openapi.yaml
- filename: tm-forum-tmf629-customer-management-openapi.yaml
  format: yaml
  label: TMF629 Customer Management
  slug: tmf629-customer-management
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tm-forum/refs/heads/main/openapi/tm-forum-tmf629-customer-management-openapi.yaml
- filename: tm-forum-tmf632-party-management-openapi.yaml
  format: yaml
  label: TMF632 Party Management
  slug: tmf632-party-management
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tm-forum/refs/heads/main/openapi/tm-forum-tmf632-party-management-openapi.yaml
- filename: tm-forum-tmf633-service-catalog-openapi.json
  format: json
  label: TMF633 Service Catalog Management
  slug: tmf633-service-catalog
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tm-forum/refs/heads/main/openapi/tm-forum-tmf633-service-catalog-openapi.json
- filename: tm-forum-tmf634-resource-catalog-openapi.json
  format: json
  label: TMF634 Resource Catalog Management
  slug: tmf634-resource-catalog
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tm-forum/refs/heads/main/openapi/tm-forum-tmf634-resource-catalog-openapi.json
- filename: tm-forum-tmf637-product-inventory-openapi.yaml
  format: yaml
  label: TMF637 Product Inventory Management
  slug: tmf637-product-inventory
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tm-forum/refs/heads/main/openapi/tm-forum-tmf637-product-inventory-openapi.yaml
- filename: tm-forum-tmf641-service-ordering-openapi.json
  format: json
  label: TMF641 Service Order Management
  slug: tmf641-service-ordering
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tm-forum/refs/heads/main/openapi/tm-forum-tmf641-service-ordering-openapi.json
- filename: tm-forum-tmf648-quote-management-openapi.json
  format: json
  label: TMF648 Quote Management
  slug: tmf648-quote-management
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tm-forum/refs/heads/main/openapi/tm-forum-tmf648-quote-management-openapi.json
- filename: tm-forum-tmf651-agreement-management-openapi.json
  format: json
  label: TMF651 Agreement Management
  slug: tmf651-agreement-management
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tm-forum/refs/heads/main/openapi/tm-forum-tmf651-agreement-management-openapi.json
- filename: tm-forum-tmf666-account-management-openapi.json
  format: json
  label: TMF666 Account Management
  slug: tmf666-account-management
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tm-forum/refs/heads/main/openapi/tm-forum-tmf666-account-management-openapi.json
class_count: 8
classes:
- Addressable
- Entity
- Extensible
- JsonPatch
- Quantity
- TimePeriod
- TroubleTicketSpecification_RES
- TroubleTicket_RES
context_file: json-ld/tm-forum-tmf621-trouble-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/tm-forum/refs/heads/main/json-ld/tm-forum-tmf621-trouble-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Tm Forum Tmf621 Trouble from TM Forum.
layout: jsonld
name: Tm Forum Tmf621 Trouble Context
namespaces:
- prefix: tmf
  uri: https://tmforum.org/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: amount
  type: decimal
- container: set
  name: attachment
  type: string
- container: ''
  name: attachmentType
  type: string
- container: ''
  name: author
  type: string
- container: ''
  name: channel
  type: string
- container: set
  name: charSpecRelationship
  type: string
- container: set
  name: characteristicRelationship
  type: string
- container: ''
  name: characteristicSpecificationId
  type: string
- container: set
  name: characteristicValueSpecification
  type: string
- container: ''
  name: city
  type: string
- container: ''
  name: configurable
  type: boolean
- container: ''
  name: contactType
  type: string
- container: ''
  name: content
  type: string
- container: ''
  name: country
  type: string
- container: ''
  name: creationDate
  type: dateTime
- container: ''
  name: date
  type: dateTime
- container: ''
  name: description
  type: ''
- container: ''
  name: emailAddress
  type: string
- container: ''
  name: endDateTime
  type: dateTime
- container: ''
  name: entity
  type: string
- container: ''
  name: expectedResolutionDate
  type: dateTime
- container: ''
  name: extensible
  type: boolean
- container: set
  name: externalIdentifier
  type: string
- container: ''
  name: externalIdentifierType
  type: string
- container: ''
  name: faxNumber
  type: string
- container: ''
  name: from
  type: string
- container: ''
  name: geographicAddress
  type: string
- container: ''
  name: href
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: isDefault
  type: boolean
- container: ''
  name: isUnique
  type: boolean
- container: ''
  name: lastUpdate
  type: dateTime
- container: ''
  name: lifecycleStatus
  type: string
- container: ''
  name: maxCardinality
  type: integer
- container: ''
  name: mimeType
  type: string
- container: ''
  name: minCardinality
  type: integer
- container: ''
  name: name
  type: ''
- container: set
  name: note
  type: string
- container: ''
  name: op
  type: string
- container: ''
  name: owner
  type: string
- container: ''
  name: parentSpecificationHref
  type: reference
- container: ''
  name: parentSpecificationId
  type: string
- container: ''
  name: path
  type: string
- container: ''
  name: phoneNumber
  type: string
- container: ''
  name: postCode
  type: string
- container: ''
  name: preferred
  type: boolean
- container: ''
  name: priority
  type: string
- container: ''
  name: rangeInterval
  type: string
- container: ''
  name: regex
  type: string
- container: set
  name: relatedEntity
  type: string
- container: set
  name: relatedParty
  type: string
- container: ''
  name: relationshipType
  type: string
- container: ''
  name: requestedResolutionDate
  type: dateTime
- container: ''
  name: resolutionDate
  type: dateTime
- container: ''
  name: role
  type: string
- container: ''
  name: severity
  type: string
- container: ''
  name: size
  type: string
- container: set
  name: specCharacteristic
  type: string
- container: ''
  name: startDateTime
  type: dateTime
- container: ''
  name: stateOrProvince
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: statusChangeDate
  type: dateTime
- container: set
  name: statusChangeHistory
  type: string
- container: ''
  name: statusChangeReason
  type: string
- container: ''
  name: street1
  type: string
- container: ''
  name: street2
  type: string
- container: ''
  name: text
  type: string
- container: ''
  name: ticketType
  type: string
- container: set
  name: troubleTicketCharacteristic
  type: string
- container: set
  name: troubleTicketRelationship
  type: string
- container: ''
  name: troubleTicketSpecification
  type: string
- container: ''
  name: unitOfMeasure
  type: string
- container: ''
  name: units
  type: string
- container: ''
  name: url
  type: ''
- container: ''
  name: validFor
  type: string
- container: ''
  name: value
  type: integer
- container: ''
  name: valueFrom
  type: integer
- container: ''
  name: valueTo
  type: integer
- container: ''
  name: valueType
  type: string
- container: ''
  name: version
  type: ''
property_count: 80
provider_name: TM Forum
provider_slug: tm-forum
slug: tm-forum-tmf621-trouble-context
source_filename: tm-forum-tmf621-trouble-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"tmf\": \"https://tmforum.org/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Addressable\": \"tmf:Addressable\",\n    \"Entity\": \"tmf:Entity\",\n    \"Extensible\": \"tmf:Extensible\",\n    \"JsonPatch\": \"tmf:JsonPatch\",\n    \"Quantity\": \"tmf:Quantity\",\n    \"TimePeriod\": \"tmf:TimePeriod\",\n    \"TroubleTicketSpecification_RES\": \"tmf:TroubleTicketSpecification_RES\",\n    \"TroubleTicket_RES\": \"tmf:TroubleTicket_RES\",\n    \"@baseType\": {\n      \"@id\": \"tmf:@baseType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"@schemaLocation\": {\n      \"@id\": \"tmf:@schemaLocation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"@type\": {\n      \"@id\": \"tmf:@type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"@valueSchemaLocation\": {\n      \"@id\": \"tmf:@valueSchemaLocation\",\n   \
  \   \"@type\": \"xsd:string\"\n    },\n    \"amount\": {\n      \"@id\": \"tmf:amount\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"attachment\": {\n      \"@id\": \"tmf:attachment\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"attachmentType\": {\n      \"@id\": \"tmf:attachmentType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"author\": {\n      \"@id\": \"tmf:author\",\n      \"@type\": \"xsd:string\"\n    },\n    \"channel\": {\n      \"@id\": \"tmf:channel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"charSpecRelationship\": {\n      \"@id\": \"tmf:charSpecRelationship\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"characteristicRelationship\": {\n      \"@id\": \"tmf:characteristicRelationship\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"characteristicSpecificationId\": {\n      \"@id\": \"tmf:characteristicSpecificationId\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"characteristicValueSpecification\": {\n      \"@id\": \"tmf:characteristicValueSpecification\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"city\": {\n      \"@id\": \"tmf:city\",\n      \"@type\": \"xsd:string\"\n    },\n    \"configurable\": {\n      \"@id\": \"tmf:configurable\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"contactType\": {\n      \"@id\": \"tmf:contactType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"content\": {\n      \"@id\": \"tmf:content\",\n      \"@type\": \"xsd:string\"\n    },\n    \"country\": {\n      \"@id\": \"tmf:country\",\n      \"@type\": \"xsd:string\"\n    },\n    \"creationDate\": {\n      \"@id\": \"tmf:creationDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"date\": {\n      \"@id\": \"tmf:date\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\"\n    },\n    \"emailAddress\": {\n      \"@id\": \"tmf:emailAddress\",\n\
  \      \"@type\": \"xsd:string\"\n    },\n    \"endDateTime\": {\n      \"@id\": \"tmf:endDateTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"entity\": {\n      \"@id\": \"tmf:entity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"expectedResolutionDate\": {\n      \"@id\": \"tmf:expectedResolutionDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"extensible\": {\n      \"@id\": \"tmf:extensible\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"externalIdentifier\": {\n      \"@id\": \"tmf:externalIdentifier\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"externalIdentifierType\": {\n      \"@id\": \"tmf:externalIdentifierType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"faxNumber\": {\n      \"@id\": \"tmf:faxNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"from\": {\n      \"@id\": \"tmf:from\",\n      \"@type\": \"xsd:string\"\n    },\n    \"geographicAddress\": {\n      \"@id\": \"tmf:geographicAddress\",\n  \
  \    \"@type\": \"xsd:string\"\n    },\n    \"href\": {\n      \"@id\": \"tmf:href\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"tmf:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isDefault\": {\n      \"@id\": \"tmf:isDefault\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isUnique\": {\n      \"@id\": \"tmf:isUnique\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"lastUpdate\": {\n      \"@id\": \"tmf:lastUpdate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"lifecycleStatus\": {\n      \"@id\": \"tmf:lifecycleStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"maxCardinality\": {\n      \"@id\": \"tmf:maxCardinality\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"mimeType\": {\n      \"@id\": \"tmf:mimeType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"minCardinality\": {\n      \"@id\": \"tmf:minCardinality\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\"\n    },\n    \"note\"\
  : {\n      \"@id\": \"tmf:note\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"op\": {\n      \"@id\": \"tmf:op\",\n      \"@type\": \"xsd:string\"\n    },\n    \"owner\": {\n      \"@id\": \"tmf:owner\",\n      \"@type\": \"xsd:string\"\n    },\n    \"parentSpecificationHref\": {\n      \"@id\": \"tmf:parentSpecificationHref\",\n      \"@type\": \"@id\"\n    },\n    \"parentSpecificationId\": {\n      \"@id\": \"tmf:parentSpecificationId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"path\": {\n      \"@id\": \"tmf:path\",\n      \"@type\": \"xsd:string\"\n    },\n    \"phoneNumber\": {\n      \"@id\": \"tmf:phoneNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"postCode\": {\n      \"@id\": \"tmf:postCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"preferred\": {\n      \"@id\": \"tmf:preferred\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"priority\": {\n      \"@id\": \"tmf:priority\",\n      \"@type\": \"xsd:string\"\n  \
  \  },\n    \"rangeInterval\": {\n      \"@id\": \"tmf:rangeInterval\",\n      \"@type\": \"xsd:string\"\n    },\n    \"regex\": {\n      \"@id\": \"tmf:regex\",\n      \"@type\": \"xsd:string\"\n    },\n    \"relatedEntity\": {\n      \"@id\": \"tmf:relatedEntity\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"relatedParty\": {\n      \"@id\": \"tmf:relatedParty\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"relationshipType\": {\n      \"@id\": \"tmf:relationshipType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"requestedResolutionDate\": {\n      \"@id\": \"tmf:requestedResolutionDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"resolutionDate\": {\n      \"@id\": \"tmf:resolutionDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"role\": {\n      \"@id\": \"tmf:role\",\n      \"@type\": \"xsd:string\"\n    },\n    \"severity\": {\n      \"@id\": \"tmf:severity\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"size\": {\n      \"@id\": \"tmf:size\",\n      \"@type\": \"xsd:string\"\n    },\n    \"specCharacteristic\": {\n      \"@id\": \"tmf:specCharacteristic\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startDateTime\": {\n      \"@id\": \"tmf:startDateTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"stateOrProvince\": {\n      \"@id\": \"tmf:stateOrProvince\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"tmf:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"statusChangeDate\": {\n      \"@id\": \"tmf:statusChangeDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"statusChangeHistory\": {\n      \"@id\": \"tmf:statusChangeHistory\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"statusChangeReason\": {\n      \"@id\": \"tmf:statusChangeReason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"street1\": {\n      \"@id\": \"tmf:street1\",\n      \"\
  @type\": \"xsd:string\"\n    },\n    \"street2\": {\n      \"@id\": \"tmf:street2\",\n      \"@type\": \"xsd:string\"\n    },\n    \"text\": {\n      \"@id\": \"tmf:text\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ticketType\": {\n      \"@id\": \"tmf:ticketType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"troubleTicketCharacteristic\": {\n      \"@id\": \"tmf:troubleTicketCharacteristic\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"troubleTicketRelationship\": {\n      \"@id\": \"tmf:troubleTicketRelationship\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"troubleTicketSpecification\": {\n      \"@id\": \"tmf:troubleTicketSpecification\",\n      \"@type\": \"xsd:string\"\n    },\n    \"unitOfMeasure\": {\n      \"@id\": \"tmf:unitOfMeasure\",\n      \"@type\": \"xsd:string\"\n    },\n    \"units\": {\n      \"@id\": \"tmf:units\",\n      \"@type\": \"xsd:string\"\n    },\n    \"url\": {\n      \"@id\"\
  : \"schema:url\"\n    },\n    \"validFor\": {\n      \"@id\": \"tmf:validFor\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"tmf:value\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"valueFrom\": {\n      \"@id\": \"tmf:valueFrom\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"valueTo\": {\n      \"@id\": \"tmf:valueTo\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"valueType\": {\n      \"@id\": \"tmf:valueType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"version\": {\n      \"@id\": \"schema:version\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/tm-forum/refs/heads/main/json-ld/tm-forum-tmf621-trouble-context.jsonld
tags:
- Telco
- Telecommunications
- BSS
- OSS
- Open APIs
- Standards
- JSON-LD
- Linked Data
- Semantic Web
---
