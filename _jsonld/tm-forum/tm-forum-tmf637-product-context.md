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
class_count: 20
classes:
- Addressable
- BusinessPartner
- Consumer
- Disability
- Duration
- Entity
- EntityRelationship
- Extensible
- JsonPatch
- LanguageAbility
- Money
- OtherNameIndividual
- Place
- Producer
- ProductAttributeValueChangePayload
- Quantity
- Skill
- Supplier
- TargetProductSchema
- TimePeriod
context_file: json-ld/tm-forum-tmf637-product-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/tm-forum/refs/heads/main/json-ld/tm-forum-tmf637-product-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Tm Forum Tmf637 Product from TM Forum.
layout: jsonld
name: Tm Forum Tmf637 Product Context
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
- container: set
  name: account
  type: string
- container: set
  name: agreement
  type: string
- container: set
  name: agreementItem
  type: string
- container: ''
  name: amount
  type: decimal
- container: ''
  name: applicationDuration
  type: integer
- container: ''
  name: aristocraticTitle
  type: string
- container: ''
  name: associationSpec
  type: string
- container: set
  name: attachment
  type: string
- container: ''
  name: attachmentType
  type: string
- container: set
  name: bbox
  type: decimal
- container: ''
  name: billingAccount
  type: string
- container: ''
  name: birthDate
  type: dateTime
- container: ''
  name: buildingName
  type: string
- container: set
  name: calendar
  type: string
- container: ''
  name: certificateNumber
  type: string
- container: set
  name: characteristic
  type: string
- container: set
  name: characteristicRelationship
  type: string
- container: ''
  name: city
  type: string
- container: ''
  name: code
  type: string
- container: ''
  name: comment
  type: string
- container: set
  name: contactMedium
  type: string
- container: ''
  name: contactType
  type: string
- container: ''
  name: content
  type: string
- container: ''
  name: context
  type: string
- container: ''
  name: country
  type: string
- container: set
  name: countryCode
  type: string
- container: ''
  name: countryOfBirth
  type: string
- container: ''
  name: creationDate
  type: dateTime
- container: ''
  name: creditAgencyName
  type: string
- container: ''
  name: creditAgencyType
  type: string
- container: set
  name: creditProfile
  type: string
- container: ''
  name: creditProfileDate
  type: dateTime
- container: set
  name: creditRating
  type: string
- container: ''
  name: creditRiskRating
  type: integer
- container: ''
  name: creditScore
  type: integer
- container: ''
  name: day
  type: string
- container: ''
  name: deathDate
  type: dateTime
- container: ''
  name: description
  type: ''
- container: set
  name: disability
  type: string
- container: ''
  name: disabilityCode
  type: string
- container: ''
  name: disabilityName
  type: string
- container: ''
  name: duration
  type: string
- container: ''
  name: dutyFreeAmount
  type: string
- container: ''
  name: endDateTime
  type: dateTime
- container: ''
  name: endHour
  type: string
- container: ''
  name: engagedParty
  type: string
- container: ''
  name: evaluatedLevel
  type: string
- container: ''
  name: existsDuring
  type: string
- container: ''
  name: expression
  type: string
- container: ''
  name: expressionLanguage
  type: string
- container: ''
  name: expressionValue
  type: string
- container: set
  name: externalIdentifier
  type: string
- container: ''
  name: externalIdentifierType
  type: string
- container: set
  name: externalReference
  type: string
- container: ''
  name: familyName
  type: string
- container: ''
  name: familyNamePrefix
  type: string
- container: ''
  name: format
  type: string
- container: ''
  name: formattedName
  type: string
- container: ''
  name: from
  type: string
- container: ''
  name: fullName
  type: string
- container: ''
  name: gender
  type: string
- container: ''
  name: generation
  type: string
- container: ''
  name: geographicAddressType
  type: string
- container: ''
  name: geographicLocation
  type: string
- container: set
  name: geographicSubAddress
  type: string
- container: ''
  name: givenName
  type: string
- container: set
  name: hourPeriod
  type: string
- container: ''
  name: href
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: identificationId
  type: string
- container: ''
  name: identificationType
  type: string
- container: set
  name: individualIdentification
  type: string
- container: ''
  name: intent
  type: string
- container: set
  name: intentRelationship
  type: string
- container: ''
  name: intentSpecification
  type: string
- container: ''
  name: iri
  type: string
- container: ''
  name: isBundle
  type: boolean
- container: ''
  name: isCustomerVisible
  type: boolean
- container: ''
  name: isFavouriteLanguage
  type: boolean
- container: ''
  name: isHeadOffice
  type: boolean
- container: ''
  name: isLegalEntity
  type: boolean
- container: ''
  name: issuingAuthority
  type: string
- container: ''
  name: issuingDate
  type: dateTime
- container: ''
  name: issuingJurisdiction
  type: string
- container: ''
  name: jurisdictionLevel
  type: string
- container: ''
  name: jurisdictionName
  type: string
- container: set
  name: languageAbility
  type: string
- container: ''
  name: languageCode
  type: string
- container: ''
  name: languageName
  type: string
- container: ''
  name: lastUpdate
  type: dateTime
- container: ''
  name: legalName
  type: string
- container: ''
  name: levelNumber
  type: string
- container: ''
  name: levelType
  type: string
- container: ''
  name: lifecycleStatus
  type: string
- container: ''
  name: listeningProficiency
  type: string
- container: ''
  name: locality
  type: string
- container: ''
  name: location
  type: string
- container: ''
  name: maritalStatus
  type: string
- container: ''
  name: middleName
  type: string
- container: ''
  name: mimeType
  type: string
- container: ''
  name: name
  type: ''
- container: ''
  name: nameType
  type: string
- container: ''
  name: nationality
  type: string
- container: ''
  name: op
  type: string
- container: ''
  name: orderDate
  type: dateTime
- container: ''
  name: orderHref
  type: string
- container: ''
  name: orderId
  type: string
- container: ''
  name: orderItemAction
  type: string
- container: ''
  name: orderItemId
  type: string
- container: ''
  name: organization
  type: string
- container: set
  name: organizationChildRelationship
  type: string
- container: set
  name: organizationIdentification
  type: string
- container: ''
  name: organizationParentRelationship
  type: string
- container: ''
  name: organizationType
  type: string
- container: set
  name: otherName
  type: string
- container: ''
  name: owner
  type: string
- container: set
  name: partyCharacteristic
  type: string
- container: ''
  name: partyOrPartyRole
  type: string
- container: ''
  name: partyRoleSpecification
  type: string
- container: ''
  name: path
  type: string
- container: set
  name: paymentMethod
  type: string
- container: ''
  name: percentage
  type: decimal
- container: set
  name: place
  type: string
- container: ''
  name: placeOfBirth
  type: string
- container: ''
  name: postcode
  type: string
- container: ''
  name: preferred
  type: boolean
- container: ''
  name: preferredGivenName
  type: string
- container: ''
  name: price
  type: string
- container: set
  name: priceAlteration
  type: string
- container: ''
  name: priceType
  type: string
- container: ''
  name: priority
  type: string
- container: ''
  name: privateStreetName
  type: string
- container: ''
  name: privateStreetNumber
  type: string
- container: set
  name: product
  type: string
- container: set
  name: productCharacteristic
  type: string
- container: ''
  name: productOffering
  type: string
- container: ''
  name: productOfferingPrice
  type: string
- container: set
  name: productOrderItem
  type: string
- container: set
  name: productPrice
  type: string
- container: set
  name: productRelationship
  type: string
- container: ''
  name: productSerialNumber
  type: string
- container: ''
  name: productSpecification
  type: string
- container: set
  name: productTerm
  type: string
- container: ''
  name: ratingReference
  type: string
- container: ''
  name: ratingScore
  type: integer
- container: ''
  name: readingProficiency
  type: string
- container: set
  name: realizingResource
  type: string
- container: set
  name: realizingService
  type: string
- container: ''
  name: reason
  type: string
- container: ''
  name: recurringChargePeriod
  type: string
- container: set
  name: relatedParty
  type: string
- container: ''
  name: relationshipType
  type: string
- container: ''
  name: role
  type: string
- container: set
  name: siteRelationship
  type: string
- container: ''
  name: size
  type: string
- container: set
  name: skill
  type: string
- container: ''
  name: skillCode
  type: string
- container: ''
  name: skillName
  type: string
- container: ''
  name: speakingProficiency
  type: string
- container: ''
  name: startDate
  type: dateTime
- container: ''
  name: startDateTime
  type: dateTime
- container: ''
  name: startHour
  type: string
- container: ''
  name: stateOrProvince
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: statusChangeDate
  type: dateTime
- container: ''
  name: statusReason
  type: string
- container: ''
  name: streetName
  type: string
- container: ''
  name: streetNr
  type: string
- container: ''
  name: streetNrLast
  type: string
- container: ''
  name: streetNrLastSuffix
  type: string
- container: ''
  name: streetNrSuffix
  type: string
- container: ''
  name: streetSuffix
  type: string
- container: ''
  name: streetType
  type: string
- container: ''
  name: subAddressType
  type: string
- container: set
  name: subUnit
  type: string
- container: ''
  name: subUnitNumber
  type: string
- container: ''
  name: subUnitType
  type: string
- container: set
  name: taxDefinition
  type: string
- container: set
  name: taxExemptionCertificate
  type: string
- container: ''
  name: taxIncludedAmount
  type: string
- container: ''
  name: taxRate
  type: decimal
- container: ''
  name: taxType
  type: string
- container: ''
  name: terminationDate
  type: dateTime
- container: ''
  name: timeZone
  type: string
- container: ''
  name: title
  type: string
- container: ''
  name: tradingName
  type: string
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
  name: valueType
  type: string
- container: ''
  name: version
  type: ''
- container: ''
  name: writingProficiency
  type: string
property_count: 195
provider_name: TM Forum
provider_slug: tm-forum
slug: tm-forum-tmf637-product-context
source_filename: tm-forum-tmf637-product-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"tmf\": \"https://tmforum.org/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Addressable\": \"tmf:Addressable\",\n    \"BusinessPartner\": \"tmf:BusinessPartner\",\n    \"Consumer\": \"tmf:Consumer\",\n    \"Disability\": \"tmf:Disability\",\n    \"Duration\": \"tmf:Duration\",\n    \"Entity\": \"tmf:Entity\",\n    \"EntityRelationship\": \"tmf:EntityRelationship\",\n    \"Extensible\": \"tmf:Extensible\",\n    \"JsonPatch\": \"tmf:JsonPatch\",\n    \"LanguageAbility\": \"tmf:LanguageAbility\",\n    \"Money\": \"tmf:Money\",\n    \"OtherNameIndividual\": \"tmf:OtherNameIndividual\",\n    \"Place\": \"tmf:Place\",\n    \"Producer\": \"tmf:Producer\",\n    \"ProductAttributeValueChangePayload\": \"tmf:ProductAttributeValueChangePayload\",\n    \"Quantity\": \"tmf:Quantity\",\n    \"Skill\": \"tmf:Skill\",\n    \"\
  Supplier\": \"tmf:Supplier\",\n    \"TargetProductSchema\": \"tmf:TargetProductSchema\",\n    \"TimePeriod\": \"tmf:TimePeriod\",\n    \"@baseType\": {\n      \"@id\": \"tmf:@baseType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"@referredType\": {\n      \"@id\": \"tmf:@referredType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"@schemaLocation\": {\n      \"@id\": \"tmf:@schemaLocation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"@type\": {\n      \"@id\": \"tmf:@type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"account\": {\n      \"@id\": \"tmf:account\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"agreement\": {\n      \"@id\": \"tmf:agreement\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"agreementItem\": {\n      \"@id\": \"tmf:agreementItem\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"amount\": {\n      \"@id\": \"tmf:amount\",\n      \"@type\":\
  \ \"xsd:decimal\"\n    },\n    \"applicationDuration\": {\n      \"@id\": \"tmf:applicationDuration\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"aristocraticTitle\": {\n      \"@id\": \"tmf:aristocraticTitle\",\n      \"@type\": \"xsd:string\"\n    },\n    \"associationSpec\": {\n      \"@id\": \"tmf:associationSpec\",\n      \"@type\": \"xsd:string\"\n    },\n    \"attachment\": {\n      \"@id\": \"tmf:attachment\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"attachmentType\": {\n      \"@id\": \"tmf:attachmentType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bbox\": {\n      \"@id\": \"tmf:bbox\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"billingAccount\": {\n      \"@id\": \"tmf:billingAccount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"birthDate\": {\n      \"@id\": \"tmf:birthDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"buildingName\": {\n      \"@id\": \"tmf:buildingName\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"calendar\": {\n      \"@id\": \"tmf:calendar\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"certificateNumber\": {\n      \"@id\": \"tmf:certificateNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"characteristic\": {\n      \"@id\": \"tmf:characteristic\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"characteristicRelationship\": {\n      \"@id\": \"tmf:characteristicRelationship\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"city\": {\n      \"@id\": \"tmf:city\",\n      \"@type\": \"xsd:string\"\n    },\n    \"code\": {\n      \"@id\": \"tmf:code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"comment\": {\n      \"@id\": \"tmf:comment\",\n      \"@type\": \"xsd:string\"\n    },\n    \"contactMedium\": {\n      \"@id\": \"tmf:contactMedium\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"contactType\": {\n      \"@id\": \"tmf:contactType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"content\": {\n      \"@id\": \"tmf:content\",\n      \"@type\": \"xsd:string\"\n    },\n    \"context\": {\n      \"@id\": \"tmf:context\",\n      \"@type\": \"xsd:string\"\n    },\n    \"country\": {\n      \"@id\": \"tmf:country\",\n      \"@type\": \"xsd:string\"\n    },\n    \"countryCode\": {\n      \"@id\": \"tmf:countryCode\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"countryOfBirth\": {\n      \"@id\": \"tmf:countryOfBirth\",\n      \"@type\": \"xsd:string\"\n    },\n    \"creationDate\": {\n      \"@id\": \"tmf:creationDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"creditAgencyName\": {\n      \"@id\": \"tmf:creditAgencyName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"creditAgencyType\": {\n      \"@id\": \"tmf:creditAgencyType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"creditProfile\": {\n      \"@id\": \"\
  tmf:creditProfile\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"creditProfileDate\": {\n      \"@id\": \"tmf:creditProfileDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"creditRating\": {\n      \"@id\": \"tmf:creditRating\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"creditRiskRating\": {\n      \"@id\": \"tmf:creditRiskRating\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"creditScore\": {\n      \"@id\": \"tmf:creditScore\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"day\": {\n      \"@id\": \"tmf:day\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deathDate\": {\n      \"@id\": \"tmf:deathDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\"\n    },\n    \"disability\": {\n      \"@id\": \"tmf:disability\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"disabilityCode\": {\n      \"@id\": \"\
  tmf:disabilityCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"disabilityName\": {\n      \"@id\": \"tmf:disabilityName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"duration\": {\n      \"@id\": \"tmf:duration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dutyFreeAmount\": {\n      \"@id\": \"tmf:dutyFreeAmount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"endDateTime\": {\n      \"@id\": \"tmf:endDateTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"endHour\": {\n      \"@id\": \"tmf:endHour\",\n      \"@type\": \"xsd:string\"\n    },\n    \"engagedParty\": {\n      \"@id\": \"tmf:engagedParty\",\n      \"@type\": \"xsd:string\"\n    },\n    \"evaluatedLevel\": {\n      \"@id\": \"tmf:evaluatedLevel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"existsDuring\": {\n      \"@id\": \"tmf:existsDuring\",\n      \"@type\": \"xsd:string\"\n    },\n    \"expression\": {\n      \"@id\": \"tmf:expression\",\n      \"@type\": \"xsd:string\"\n    },\n    \"expressionLanguage\"\
  : {\n      \"@id\": \"tmf:expressionLanguage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"expressionValue\": {\n      \"@id\": \"tmf:expressionValue\",\n      \"@type\": \"xsd:string\"\n    },\n    \"externalIdentifier\": {\n      \"@id\": \"tmf:externalIdentifier\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"externalIdentifierType\": {\n      \"@id\": \"tmf:externalIdentifierType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"externalReference\": {\n      \"@id\": \"tmf:externalReference\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"familyName\": {\n      \"@id\": \"tmf:familyName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"familyNamePrefix\": {\n      \"@id\": \"tmf:familyNamePrefix\",\n      \"@type\": \"xsd:string\"\n    },\n    \"format\": {\n      \"@id\": \"tmf:format\",\n      \"@type\": \"xsd:string\"\n    },\n    \"formattedName\": {\n      \"@id\": \"tmf:formattedName\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"from\": {\n      \"@id\": \"tmf:from\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fullName\": {\n      \"@id\": \"tmf:fullName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"gender\": {\n      \"@id\": \"tmf:gender\",\n      \"@type\": \"xsd:string\"\n    },\n    \"generation\": {\n      \"@id\": \"tmf:generation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"geographicAddressType\": {\n      \"@id\": \"tmf:geographicAddressType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"geographicLocation\": {\n      \"@id\": \"tmf:geographicLocation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"geographicSubAddress\": {\n      \"@id\": \"tmf:geographicSubAddress\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"givenName\": {\n      \"@id\": \"tmf:givenName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"hourPeriod\": {\n      \"@id\": \"tmf:hourPeriod\",\n      \"@container\": \"@set\",\n      \"@type\":\
  \ \"xsd:string\"\n    },\n    \"href\": {\n      \"@id\": \"tmf:href\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"tmf:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"identificationId\": {\n      \"@id\": \"tmf:identificationId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"identificationType\": {\n      \"@id\": \"tmf:identificationType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"individualIdentification\": {\n      \"@id\": \"tmf:individualIdentification\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"intent\": {\n      \"@id\": \"tmf:intent\",\n      \"@type\": \"xsd:string\"\n    },\n    \"intentRelationship\": {\n      \"@id\": \"tmf:intentRelationship\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"intentSpecification\": {\n      \"@id\": \"tmf:intentSpecification\",\n      \"@type\": \"xsd:string\"\n    },\n    \"iri\": {\n      \"@id\": \"tmf:iri\",\n      \"\
  @type\": \"xsd:string\"\n    },\n    \"isBundle\": {\n      \"@id\": \"tmf:isBundle\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isCustomerVisible\": {\n      \"@id\": \"tmf:isCustomerVisible\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isFavouriteLanguage\": {\n      \"@id\": \"tmf:isFavouriteLanguage\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isHeadOffice\": {\n      \"@id\": \"tmf:isHeadOffice\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isLegalEntity\": {\n      \"@id\": \"tmf:isLegalEntity\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"issuingAuthority\": {\n      \"@id\": \"tmf:issuingAuthority\",\n      \"@type\": \"xsd:string\"\n    },\n    \"issuingDate\": {\n      \"@id\": \"tmf:issuingDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"issuingJurisdiction\": {\n      \"@id\": \"tmf:issuingJurisdiction\",\n      \"@type\": \"xsd:string\"\n    },\n    \"jurisdictionLevel\": {\n      \"@id\": \"tmf:jurisdictionLevel\",\n      \"@type\":\
  \ \"xsd:string\"\n    },\n    \"jurisdictionName\": {\n      \"@id\": \"tmf:jurisdictionName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"languageAbility\": {\n      \"@id\": \"tmf:languageAbility\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"languageCode\": {\n      \"@id\": \"tmf:languageCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"languageName\": {\n      \"@id\": \"tmf:languageName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastUpdate\": {\n      \"@id\": \"tmf:lastUpdate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"legalName\": {\n      \"@id\": \"tmf:legalName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"levelNumber\": {\n      \"@id\": \"tmf:levelNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"levelType\": {\n      \"@id\": \"tmf:levelType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lifecycleStatus\": {\n      \"@id\": \"tmf:lifecycleStatus\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"listeningProficiency\": {\n      \"@id\": \"tmf:listeningProficiency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"locality\": {\n      \"@id\": \"tmf:locality\",\n      \"@type\": \"xsd:string\"\n    },\n    \"location\": {\n      \"@id\": \"tmf:location\",\n      \"@type\": \"xsd:string\"\n    },\n    \"maritalStatus\": {\n      \"@id\": \"tmf:maritalStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"middleName\": {\n      \"@id\": \"tmf:middleName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mimeType\": {\n      \"@id\": \"tmf:mimeType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\"\n    },\n    \"nameType\": {\n      \"@id\": \"tmf:nameType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nationality\": {\n      \"@id\": \"tmf:nationality\",\n      \"@type\": \"xsd:string\"\n    },\n    \"op\": {\n      \"@id\": \"tmf:op\",\n      \"@type\": \"xsd:string\"\n    },\n    \"orderDate\": {\n      \"@id\": \"tmf:orderDate\"\
  ,\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"orderHref\": {\n      \"@id\": \"tmf:orderHref\",\n      \"@type\": \"xsd:string\"\n    },\n    \"orderId\": {\n      \"@id\": \"tmf:orderId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"orderItemAction\": {\n      \"@id\": \"tmf:orderItemAction\",\n      \"@type\": \"xsd:string\"\n    },\n    \"orderItemId\": {\n      \"@id\": \"tmf:orderItemId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"organization\": {\n      \"@id\": \"tmf:organization\",\n      \"@type\": \"xsd:string\"\n    },\n    \"organizationChildRelationship\": {\n      \"@id\": \"tmf:organizationChildRelationship\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"organizationIdentification\": {\n      \"@id\": \"tmf:organizationIdentification\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"organizationParentRelationship\": {\n      \"@id\": \"tmf:organizationParentRelationship\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"organizationType\": {\n      \"@id\": \"tmf:organizationType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"otherName\": {\n      \"@id\": \"tmf:otherName\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"owner\": {\n      \"@id\": \"tmf:owner\",\n      \"@type\": \"xsd:string\"\n    },\n    \"partyCharacteristic\": {\n      \"@id\": \"tmf:partyCharacteristic\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"partyOrPartyRole\": {\n      \"@id\": \"tmf:partyOrPartyRole\",\n      \"@type\": \"xsd:string\"\n    },\n    \"partyRoleSpecification\": {\n      \"@id\": \"tmf:partyRoleSpecification\",\n      \"@type\": \"xsd:string\"\n    },\n    \"path\": {\n      \"@id\": \"tmf:path\",\n      \"@type\": \"xsd:string\"\n    },\n    \"paymentMethod\": {\n      \"@id\": \"tmf:paymentMethod\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"percentage\": {\n   \
  \   \"@id\": \"tmf:percentage\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"place\": {\n      \"@id\": \"tmf:place\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"placeOfBirth\": {\n      \"@id\": \"tmf:placeOfBirth\",\n      \"@type\": \"xsd:string\"\n    },\n    \"postcode\": {\n      \"@id\": \"tmf:postcode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"preferred\": {\n      \"@id\": \"tmf:preferred\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"preferredGivenName\": {\n      \"@id\": \"tmf:preferredGivenName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"price\": {\n      \"@id\": \"tmf:price\",\n      \"@type\": \"xsd:string\"\n    },\n    \"priceAlteration\": {\n      \"@id\": \"tmf:priceAlteration\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"priceType\": {\n      \"@id\": \"tmf:priceType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"priority\": {\n      \"@id\": \"tmf:priority\",\n\
  \      \"@type\": \"xsd:string\"\n    },\n    \"privateStreetName\": {\n      \"@id\": \"tmf:privateStreetName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"privateStreetNumber\": {\n      \"@id\": \"tmf:privateStreetNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"product\": {\n      \"@id\": \"tmf:product\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"productCharacteristic\": {\n      \"@id\": \"tmf:productCharacteristic\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"productOffering\": {\n      \"@id\": \"tmf:productOffering\",\n      \"@type\": \"xsd:string\"\n    },\n    \"productOfferingPrice\": {\n      \"@id\": \"tmf:productOfferingPrice\",\n      \"@type\": \"xsd:string\"\n    },\n    \"productOrderItem\": {\n      \"@id\": \"tmf:productOrderItem\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"productPrice\": {\n      \"@id\": \"tmf:productPrice\",\n     \
  \ \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"productRelationship\": {\n      \"@id\": \"tmf:productRelationship\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"productSerialNumber\": {\n      \"@id\": \"tmf:productSerialNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"productSpecification\": {\n      \"@id\": \"tmf:productSpecification\",\n      \"@type\": \"xsd:string\"\n    },\n    \"productTerm\": {\n      \"@id\": \"tmf:productTerm\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ratingReference\": {\n      \"@id\": \"tmf:ratingReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ratingScore\": {\n      \"@id\": \"tmf:ratingScore\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"readingProficiency\": {\n      \"@id\": \"tmf:readingProficiency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"realizingResource\": {\n      \"@id\": \"tmf:realizingResource\",\n   \
  \   \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"realizingService\": {\n      \"@id\": \"tmf:realizingService\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reason\": {\n      \"@id\": \"tmf:reason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"recurringChargePeriod\": {\n      \"@id\": \"tmf:recurringChargePeriod\",\n      \"@type\": \"xsd:string\"\n    },\n    \"relatedParty\": {\n      \"@id\": \"tmf:relatedParty\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"relationshipType\": {\n      \"@id\": \"tmf:relationshipType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"role\": {\n      \"@id\": \"tmf:role\",\n      \"@type\": \"xsd:string\"\n    },\n    \"siteRelationship\": {\n      \"@id\": \"tmf:siteRelationship\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"size\": {\n      \"@id\": \"tmf:size\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"skill\": {\n      \"@id\": \"tmf:skill\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"skillCode\": {\n      \"@id\": \"tmf:skillCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"skillName\": {\n      \"@id\": \"tmf:skillName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"speakingProficiency\": {\n      \"@id\": \"tmf:speakingProficiency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startDate\": {\n      \"@id\": \"tmf:startDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"startDateTime\": {\n      \"@id\": \"tmf:startDateTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"startHour\": {\n      \"@id\": \"tmf:startHour\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stateOrProvince\": {\n      \"@id\": \"tmf:stateOrProvince\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"tmf:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"statusChangeDate\": {\n      \"@id\": \"tmf:statusChangeDate\"\
  ,\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"statusReason\": {\n      \"@id\": \"tmf:statusReason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"streetName\": {\n      \"@id\": \"tmf:streetName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"streetNr\": {\n      \"@id\": \"tmf:streetNr\",\n      \"@type\": \"xsd:string\"\n    },\n    \"streetNrLast\": {\n      \"@id\": \"tmf:streetNrLast\",\n      \"@type\": \"xsd:string\"\n    },\n    \"streetNrLastSuffix\": {\n      \"@id\": \"tmf:streetNrLastSuffix\",\n      \"@type\": \"xsd:string\"\n    },\n    \"streetNrSuffix\": {\n      \"@id\": \"tmf:streetNrSuffix\",\n      \"@type\": \"xsd:string\"\n    },\n    \"streetSuffix\": {\n      \"@id\": \"tmf:streetSuffix\",\n      \"@type\": \"xsd:string\"\n    },\n    \"streetType\": {\n      \"@id\": \"tmf:streetType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subAddressType\": {\n      \"@id\": \"tmf:subAddressType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subUnit\"\
  : {\n      \"@id\": \"tmf:subUnit\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subUnitNumber\": {\n      \"@id\": \"tmf:subUnitNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subUnitType\": {\n      \"@id\": \"tmf:subUnitType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"taxDefinition\": {\n      \"@id\": \"tmf:taxDefinition\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"taxExemptionCertificate\": {\n      \"@id\": \"tmf:taxExemptionCertificate\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"taxIncludedAmount\": {\n      \"@id\": \"tmf:taxIncludedAmount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"taxRate\": {\n      \"@id\": \"tmf:taxRate\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"taxType\": {\n      \"@id\": \"tmf:taxType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"terminationDate\": {\n      \"@id\": \"tmf:terminationDate\",\n      \"@type\"\
  : \"xsd:dateTime\"\n    },\n    \"timeZone\": {\n      \"@id\": \"tmf:timeZone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"title\": {\n      \"@id\": \"tmf:title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tradingName\": {\n      \"@id\": \"tmf:tradingName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"unit\": {\n      \"@id\": \"tmf:unit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"unitOfMeasure\": {\n      \"@id\": \"tmf:unitOfMeasure\",\n      \"@type\": \"xsd:string\"\n    },\n    \"units\": {\n      \"@id\": \"tmf:units\",\n      \"@type\": \"xsd:string\"\n    },\n    \"url\": {\n      \"@id\": \"schema:url\"\n    },\n    \"validFor\": {\n      \"@id\": \"tmf:validFor\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"tmf:value\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"valueType\": {\n      \"@id\": \"tmf:valueType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"version\": {\n      \"\
  @id\": \"schema:version\"\n    },\n    \"writingProficiency\": {\n      \"@id\": \"tmf:writingProficiency\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/tm-forum/refs/heads/main/json-ld/tm-forum-tmf637-product-context.jsonld
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
