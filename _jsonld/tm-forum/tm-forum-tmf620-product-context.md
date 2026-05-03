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
class_count: 9
classes:
- Addressable
- Duration
- Entity
- Extensible
- JsonPatch
- Money
- Quantity
- TargetProductSchema
- TimePeriod
context_file: json-ld/tm-forum-tmf620-product-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/tm-forum/refs/heads/main/json-ld/tm-forum-tmf620-product-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Tm Forum Tmf620 Product from TM Forum.
layout: jsonld
name: Tm Forum Tmf620 Product Context
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
  name: action
  type: string
- container: set
  name: agreement
  type: string
- container: set
  name: allowedAction
  type: string
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
  name: brand
  type: string
- container: set
  name: bundledGroupProductOffering
  type: string
- container: ''
  name: bundledGroupProductOfferingOption
  type: string
- container: set
  name: bundledPopRelationship
  type: string
- container: set
  name: bundledProductOffering
  type: string
- container: ''
  name: bundledProductOfferingOption
  type: string
- container: set
  name: bundledProductSpecification
  type: string
- container: ''
  name: catalogType
  type: string
- container: set
  name: category
  type: string
- container: set
  name: channel
  type: string
- container: set
  name: charSpecRelationship
  type: string
- container: set
  name: characteristic
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
  name: completionDate
  type: dateTime
- container: ''
  name: configurable
  type: boolean
- container: ''
  name: content
  type: string
- container: ''
  name: contentType
  type: string
- container: ''
  name: creationDate
  type: dateTime
- container: ''
  name: description
  type: ''
- container: ''
  name: duration
  type: string
- container: ''
  name: endDateTime
  type: dateTime
- container: ''
  name: errorLog
  type: string
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
  name: from
  type: string
- container: ''
  name: href
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: intentSpecification
  type: string
- container: ''
  name: isBundle
  type: boolean
- container: ''
  name: isDefault
  type: boolean
- container: ''
  name: isRoot
  type: boolean
- container: ''
  name: isSellable
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
- container: set
  name: marketSegment
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
- container: ''
  name: numberRelOfferDefault
  type: integer
- container: ''
  name: numberRelOfferLowerLimit
  type: integer
- container: ''
  name: numberRelOfferUpperLimit
  type: integer
- container: ''
  name: op
  type: string
- container: ''
  name: owner
  type: string
- container: ''
  name: parent
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
  name: percentage
  type: decimal
- container: ''
  name: plaSpecId
  type: string
- container: set
  name: place
  type: string
- container: set
  name: policy
  type: string
- container: set
  name: popRelationship
  type: string
- container: ''
  name: price
  type: string
- container: ''
  name: priceType
  type: string
- container: set
  name: pricingLogicAlgorithm
  type: string
- container: set
  name: prodSpecCharValueUse
  type: string
- container: ''
  name: productNumber
  type: string
- container: set
  name: productOffering
  type: string
- container: set
  name: productOfferingCharacteristic
  type: string
- container: set
  name: productOfferingPrice
  type: string
- container: set
  name: productOfferingRelationship
  type: string
- container: set
  name: productOfferingTerm
  type: string
- container: set
  name: productSpecCharacteristic
  type: string
- container: set
  name: productSpecCharacteristicValue
  type: string
- container: ''
  name: productSpecification
  type: string
- container: set
  name: productSpecificationRelationship
  type: string
- container: ''
  name: query
  type: string
- container: ''
  name: rangeInterval
  type: string
- container: ''
  name: recurringChargePeriodLength
  type: integer
- container: ''
  name: recurringChargePeriodType
  type: string
- container: ''
  name: regex
  type: string
- container: set
  name: relatedParty
  type: string
- container: ''
  name: relationshipType
  type: string
- container: ''
  name: resourceCandidate
  type: string
- container: set
  name: resourceSpecification
  type: string
- container: ''
  name: role
  type: string
- container: ''
  name: serviceCandidate
  type: string
- container: ''
  name: serviceLevelAgreement
  type: string
- container: set
  name: serviceSpecification
  type: string
- container: ''
  name: size
  type: string
- container: ''
  name: startDateTime
  type: dateTime
- container: ''
  name: status
  type: string
- container: ''
  name: statusReason
  type: string
- container: set
  name: subCategory
  type: string
- container: ''
  name: targetProductSchema
  type: string
- container: set
  name: tax
  type: string
- container: ''
  name: taxAmount
  type: string
- container: ''
  name: taxCategory
  type: string
- container: ''
  name: taxRate
  type: decimal
- container: ''
  name: unit
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
- container: set
  name: value
  type: decimal
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
property_count: 110
provider_name: TM Forum
provider_slug: tm-forum
slug: tm-forum-tmf620-product-context
source_filename: tm-forum-tmf620-product-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"tmf\": \"https://tmforum.org/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Addressable\": \"tmf:Addressable\",\n    \"Duration\": \"tmf:Duration\",\n    \"Entity\": \"tmf:Entity\",\n    \"Extensible\": \"tmf:Extensible\",\n    \"JsonPatch\": \"tmf:JsonPatch\",\n    \"Money\": \"tmf:Money\",\n    \"Quantity\": \"tmf:Quantity\",\n    \"TargetProductSchema\": \"tmf:TargetProductSchema\",\n    \"TimePeriod\": \"tmf:TimePeriod\",\n    \"@baseType\": {\n      \"@id\": \"tmf:@baseType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"@schemaLocation\": {\n      \"@id\": \"tmf:@schemaLocation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"@type\": {\n      \"@id\": \"tmf:@type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"@valueSchemaLocation\": {\n      \"@id\": \"tmf:@valueSchemaLocation\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"action\": {\n      \"@id\": \"tmf:action\",\n      \"@type\": \"xsd:string\"\n    },\n    \"agreement\": {\n      \"@id\": \"tmf:agreement\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"allowedAction\": {\n      \"@id\": \"tmf:allowedAction\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"amount\": {\n      \"@id\": \"tmf:amount\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"attachment\": {\n      \"@id\": \"tmf:attachment\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"attachmentType\": {\n      \"@id\": \"tmf:attachmentType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"brand\": {\n      \"@id\": \"tmf:brand\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bundledGroupProductOffering\": {\n      \"@id\": \"tmf:bundledGroupProductOffering\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bundledGroupProductOfferingOption\"\
  : {\n      \"@id\": \"tmf:bundledGroupProductOfferingOption\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bundledPopRelationship\": {\n      \"@id\": \"tmf:bundledPopRelationship\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bundledProductOffering\": {\n      \"@id\": \"tmf:bundledProductOffering\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bundledProductOfferingOption\": {\n      \"@id\": \"tmf:bundledProductOfferingOption\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bundledProductSpecification\": {\n      \"@id\": \"tmf:bundledProductSpecification\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"catalogType\": {\n      \"@id\": \"tmf:catalogType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"category\": {\n      \"@id\": \"tmf:category\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"channel\": {\n      \"@id\": \"tmf:channel\"\
  ,\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"charSpecRelationship\": {\n      \"@id\": \"tmf:charSpecRelationship\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"characteristic\": {\n      \"@id\": \"tmf:characteristic\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"characteristicRelationship\": {\n      \"@id\": \"tmf:characteristicRelationship\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"characteristicSpecificationId\": {\n      \"@id\": \"tmf:characteristicSpecificationId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"characteristicValueSpecification\": {\n      \"@id\": \"tmf:characteristicValueSpecification\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"completionDate\": {\n      \"@id\": \"tmf:completionDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"configurable\": {\n      \"@id\"\
  : \"tmf:configurable\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"content\": {\n      \"@id\": \"tmf:content\",\n      \"@type\": \"xsd:string\"\n    },\n    \"contentType\": {\n      \"@id\": \"tmf:contentType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"creationDate\": {\n      \"@id\": \"tmf:creationDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\"\n    },\n    \"duration\": {\n      \"@id\": \"tmf:duration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"endDateTime\": {\n      \"@id\": \"tmf:endDateTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"errorLog\": {\n      \"@id\": \"tmf:errorLog\",\n      \"@type\": \"xsd:string\"\n    },\n    \"extensible\": {\n      \"@id\": \"tmf:extensible\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"externalIdentifier\": {\n      \"@id\": \"tmf:externalIdentifier\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"externalIdentifierType\"\
  : {\n      \"@id\": \"tmf:externalIdentifierType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"from\": {\n      \"@id\": \"tmf:from\",\n      \"@type\": \"xsd:string\"\n    },\n    \"href\": {\n      \"@id\": \"tmf:href\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"tmf:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"intentSpecification\": {\n      \"@id\": \"tmf:intentSpecification\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isBundle\": {\n      \"@id\": \"tmf:isBundle\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isDefault\": {\n      \"@id\": \"tmf:isDefault\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isRoot\": {\n      \"@id\": \"tmf:isRoot\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isSellable\": {\n      \"@id\": \"tmf:isSellable\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isUnique\": {\n      \"@id\": \"tmf:isUnique\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"lastUpdate\": {\n      \"@id\": \"\
  tmf:lastUpdate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"lifecycleStatus\": {\n      \"@id\": \"tmf:lifecycleStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"marketSegment\": {\n      \"@id\": \"tmf:marketSegment\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"maxCardinality\": {\n      \"@id\": \"tmf:maxCardinality\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"mimeType\": {\n      \"@id\": \"tmf:mimeType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"minCardinality\": {\n      \"@id\": \"tmf:minCardinality\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\"\n    },\n    \"numberRelOfferDefault\": {\n      \"@id\": \"tmf:numberRelOfferDefault\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"numberRelOfferLowerLimit\": {\n      \"@id\": \"tmf:numberRelOfferLowerLimit\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"numberRelOfferUpperLimit\": {\n      \"@id\": \"tmf:numberRelOfferUpperLimit\"\
  ,\n      \"@type\": \"xsd:integer\"\n    },\n    \"op\": {\n      \"@id\": \"tmf:op\",\n      \"@type\": \"xsd:string\"\n    },\n    \"owner\": {\n      \"@id\": \"tmf:owner\",\n      \"@type\": \"xsd:string\"\n    },\n    \"parent\": {\n      \"@id\": \"tmf:parent\",\n      \"@type\": \"xsd:string\"\n    },\n    \"parentSpecificationHref\": {\n      \"@id\": \"tmf:parentSpecificationHref\",\n      \"@type\": \"@id\"\n    },\n    \"parentSpecificationId\": {\n      \"@id\": \"tmf:parentSpecificationId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"path\": {\n      \"@id\": \"tmf:path\",\n      \"@type\": \"xsd:string\"\n    },\n    \"percentage\": {\n      \"@id\": \"tmf:percentage\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"plaSpecId\": {\n      \"@id\": \"tmf:plaSpecId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"place\": {\n      \"@id\": \"tmf:place\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"policy\": {\n      \"@id\": \"tmf:policy\"\
  ,\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"popRelationship\": {\n      \"@id\": \"tmf:popRelationship\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"price\": {\n      \"@id\": \"tmf:price\",\n      \"@type\": \"xsd:string\"\n    },\n    \"priceType\": {\n      \"@id\": \"tmf:priceType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pricingLogicAlgorithm\": {\n      \"@id\": \"tmf:pricingLogicAlgorithm\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"prodSpecCharValueUse\": {\n      \"@id\": \"tmf:prodSpecCharValueUse\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"productNumber\": {\n      \"@id\": \"tmf:productNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"productOffering\": {\n      \"@id\": \"tmf:productOffering\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"productOfferingCharacteristic\"\
  : {\n      \"@id\": \"tmf:productOfferingCharacteristic\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"productOfferingPrice\": {\n      \"@id\": \"tmf:productOfferingPrice\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"productOfferingRelationship\": {\n      \"@id\": \"tmf:productOfferingRelationship\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"productOfferingTerm\": {\n      \"@id\": \"tmf:productOfferingTerm\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"productSpecCharacteristic\": {\n      \"@id\": \"tmf:productSpecCharacteristic\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"productSpecCharacteristicValue\": {\n      \"@id\": \"tmf:productSpecCharacteristicValue\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"productSpecification\": {\n      \"@id\": \"tmf:productSpecification\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"productSpecificationRelationship\": {\n      \"@id\": \"tmf:productSpecificationRelationship\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"query\": {\n      \"@id\": \"tmf:query\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rangeInterval\": {\n      \"@id\": \"tmf:rangeInterval\",\n      \"@type\": \"xsd:string\"\n    },\n    \"recurringChargePeriodLength\": {\n      \"@id\": \"tmf:recurringChargePeriodLength\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"recurringChargePeriodType\": {\n      \"@id\": \"tmf:recurringChargePeriodType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"regex\": {\n      \"@id\": \"tmf:regex\",\n      \"@type\": \"xsd:string\"\n    },\n    \"relatedParty\": {\n      \"@id\": \"tmf:relatedParty\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"relationshipType\": {\n      \"@id\": \"tmf:relationshipType\",\n      \"@type\": \"\
  xsd:string\"\n    },\n    \"resourceCandidate\": {\n      \"@id\": \"tmf:resourceCandidate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resourceSpecification\": {\n      \"@id\": \"tmf:resourceSpecification\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"role\": {\n      \"@id\": \"tmf:role\",\n      \"@type\": \"xsd:string\"\n    },\n    \"serviceCandidate\": {\n      \"@id\": \"tmf:serviceCandidate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"serviceLevelAgreement\": {\n      \"@id\": \"tmf:serviceLevelAgreement\",\n      \"@type\": \"xsd:string\"\n    },\n    \"serviceSpecification\": {\n      \"@id\": \"tmf:serviceSpecification\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"size\": {\n      \"@id\": \"tmf:size\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startDateTime\": {\n      \"@id\": \"tmf:startDateTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"status\": {\n      \"@id\": \"tmf:status\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"statusReason\": {\n      \"@id\": \"tmf:statusReason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subCategory\": {\n      \"@id\": \"tmf:subCategory\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"targetProductSchema\": {\n      \"@id\": \"tmf:targetProductSchema\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tax\": {\n      \"@id\": \"tmf:tax\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"taxAmount\": {\n      \"@id\": \"tmf:taxAmount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"taxCategory\": {\n      \"@id\": \"tmf:taxCategory\",\n      \"@type\": \"xsd:string\"\n    },\n    \"taxRate\": {\n      \"@id\": \"tmf:taxRate\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"unit\": {\n      \"@id\": \"tmf:unit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"unitOfMeasure\": {\n      \"@id\": \"tmf:unitOfMeasure\",\n      \"@type\": \"xsd:string\"\n\
  \    },\n    \"units\": {\n      \"@id\": \"tmf:units\",\n      \"@type\": \"xsd:string\"\n    },\n    \"url\": {\n      \"@id\": \"schema:url\"\n    },\n    \"validFor\": {\n      \"@id\": \"tmf:validFor\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"tmf:value\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"valueFrom\": {\n      \"@id\": \"tmf:valueFrom\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"valueTo\": {\n      \"@id\": \"tmf:valueTo\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"valueType\": {\n      \"@id\": \"tmf:valueType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"version\": {\n      \"@id\": \"schema:version\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/tm-forum/refs/heads/main/json-ld/tm-forum-tmf620-product-context.jsonld
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
