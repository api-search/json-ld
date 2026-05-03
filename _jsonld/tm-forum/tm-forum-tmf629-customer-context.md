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
class_count: 15
classes:
- Addressable
- BusinessPartner
- Consumer
- Customer
- Disability
- Entity
- Extensible
- JsonPatch
- LanguageAbility
- OtherNameIndividual
- Producer
- Quantity
- Skill
- Supplier
- TimePeriod
context_file: json-ld/tm-forum-tmf629-customer-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/tm-forum/refs/heads/main/json-ld/tm-forum-tmf629-customer-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Tm Forum Tmf629 Customer from TM Forum.
layout: jsonld
name: Tm Forum Tmf629 Customer Context
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
- container: ''
  name: amount
  type: decimal
- container: ''
  name: aristocraticTitle
  type: string
- container: ''
  name: attachment
  type: string
- container: ''
  name: attachmentType
  type: string
- container: ''
  name: birthDate
  type: dateTime
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
  name: country
  type: string
- container: ''
  name: countryOfBirth
  type: string
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
  name: emailAddress
  type: string
- container: ''
  name: endDateTime
  type: dateTime
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
  name: faxNumber
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
  name: geographicAddress
  type: string
- container: ''
  name: givenName
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
  name: legalName
  type: string
- container: ''
  name: listeningProficiency
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
  name: phoneNumber
  type: string
- container: ''
  name: placeOfBirth
  type: string
- container: ''
  name: postCode
  type: string
- container: ''
  name: preferred
  type: boolean
- container: ''
  name: preferredGivenName
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
- container: ''
  name: reason
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
  name: socialNetworkId
  type: string
- container: ''
  name: speakingProficiency
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
  name: statusReason
  type: string
- container: ''
  name: street1
  type: string
- container: ''
  name: street2
  type: string
- container: set
  name: taxDefinition
  type: string
- container: set
  name: taxExemptionCertificate
  type: string
- container: ''
  name: taxType
  type: string
- container: ''
  name: title
  type: string
- container: ''
  name: tradingName
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
  type: ''
- container: ''
  name: valueType
  type: string
- container: ''
  name: writingProficiency
  type: string
property_count: 119
provider_name: TM Forum
provider_slug: tm-forum
slug: tm-forum-tmf629-customer-context
source_filename: tm-forum-tmf629-customer-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"tmf\": \"https://tmforum.org/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Addressable\": \"tmf:Addressable\",\n    \"BusinessPartner\": \"tmf:BusinessPartner\",\n    \"Consumer\": \"tmf:Consumer\",\n    \"Customer\": \"tmf:Customer\",\n    \"Disability\": \"tmf:Disability\",\n    \"Entity\": \"tmf:Entity\",\n    \"Extensible\": \"tmf:Extensible\",\n    \"JsonPatch\": \"tmf:JsonPatch\",\n    \"LanguageAbility\": \"tmf:LanguageAbility\",\n    \"OtherNameIndividual\": \"tmf:OtherNameIndividual\",\n    \"Producer\": \"tmf:Producer\",\n    \"Quantity\": \"tmf:Quantity\",\n    \"Skill\": \"tmf:Skill\",\n    \"Supplier\": \"tmf:Supplier\",\n    \"TimePeriod\": \"tmf:TimePeriod\",\n    \"@baseType\": {\n      \"@id\": \"tmf:@baseType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"@schemaLocation\": {\n      \"@id\"\
  : \"tmf:@schemaLocation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"@type\": {\n      \"@id\": \"tmf:@type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"account\": {\n      \"@id\": \"tmf:account\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"agreement\": {\n      \"@id\": \"tmf:agreement\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"amount\": {\n      \"@id\": \"tmf:amount\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"aristocraticTitle\": {\n      \"@id\": \"tmf:aristocraticTitle\",\n      \"@type\": \"xsd:string\"\n    },\n    \"attachment\": {\n      \"@id\": \"tmf:attachment\",\n      \"@type\": \"xsd:string\"\n    },\n    \"attachmentType\": {\n      \"@id\": \"tmf:attachmentType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"birthDate\": {\n      \"@id\": \"tmf:birthDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"certificateNumber\": {\n      \"@id\": \"tmf:certificateNumber\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"characteristic\": {\n      \"@id\": \"tmf:characteristic\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"characteristicRelationship\": {\n      \"@id\": \"tmf:characteristicRelationship\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"city\": {\n      \"@id\": \"tmf:city\",\n      \"@type\": \"xsd:string\"\n    },\n    \"comment\": {\n      \"@id\": \"tmf:comment\",\n      \"@type\": \"xsd:string\"\n    },\n    \"contactMedium\": {\n      \"@id\": \"tmf:contactMedium\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"contactType\": {\n      \"@id\": \"tmf:contactType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"content\": {\n      \"@id\": \"tmf:content\",\n      \"@type\": \"xsd:string\"\n    },\n    \"country\": {\n      \"@id\": \"tmf:country\",\n      \"@type\": \"xsd:string\"\n    },\n    \"countryOfBirth\": {\n      \"@id\"\
  : \"tmf:countryOfBirth\",\n      \"@type\": \"xsd:string\"\n    },\n    \"creditAgencyName\": {\n      \"@id\": \"tmf:creditAgencyName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"creditAgencyType\": {\n      \"@id\": \"tmf:creditAgencyType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"creditProfile\": {\n      \"@id\": \"tmf:creditProfile\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"creditProfileDate\": {\n      \"@id\": \"tmf:creditProfileDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"creditRating\": {\n      \"@id\": \"tmf:creditRating\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"creditRiskRating\": {\n      \"@id\": \"tmf:creditRiskRating\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"creditScore\": {\n      \"@id\": \"tmf:creditScore\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"deathDate\": {\n      \"@id\": \"tmf:deathDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n\
  \    \"description\": {\n      \"@id\": \"schema:description\"\n    },\n    \"disability\": {\n      \"@id\": \"tmf:disability\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"disabilityCode\": {\n      \"@id\": \"tmf:disabilityCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"disabilityName\": {\n      \"@id\": \"tmf:disabilityName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"emailAddress\": {\n      \"@id\": \"tmf:emailAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"endDateTime\": {\n      \"@id\": \"tmf:endDateTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"engagedParty\": {\n      \"@id\": \"tmf:engagedParty\",\n      \"@type\": \"xsd:string\"\n    },\n    \"evaluatedLevel\": {\n      \"@id\": \"tmf:evaluatedLevel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"existsDuring\": {\n      \"@id\": \"tmf:existsDuring\",\n      \"@type\": \"xsd:string\"\n    },\n    \"externalIdentifierType\": {\n      \"@id\": \"tmf:externalIdentifierType\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"externalReference\": {\n      \"@id\": \"tmf:externalReference\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"familyName\": {\n      \"@id\": \"tmf:familyName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"familyNamePrefix\": {\n      \"@id\": \"tmf:familyNamePrefix\",\n      \"@type\": \"xsd:string\"\n    },\n    \"faxNumber\": {\n      \"@id\": \"tmf:faxNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"formattedName\": {\n      \"@id\": \"tmf:formattedName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"from\": {\n      \"@id\": \"tmf:from\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fullName\": {\n      \"@id\": \"tmf:fullName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"gender\": {\n      \"@id\": \"tmf:gender\",\n      \"@type\": \"xsd:string\"\n    },\n    \"generation\": {\n      \"@id\": \"tmf:generation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"geographicAddress\"\
  : {\n      \"@id\": \"tmf:geographicAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"givenName\": {\n      \"@id\": \"tmf:givenName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"href\": {\n      \"@id\": \"tmf:href\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"tmf:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"identificationId\": {\n      \"@id\": \"tmf:identificationId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"identificationType\": {\n      \"@id\": \"tmf:identificationType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"individualIdentification\": {\n      \"@id\": \"tmf:individualIdentification\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isFavouriteLanguage\": {\n      \"@id\": \"tmf:isFavouriteLanguage\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isHeadOffice\": {\n      \"@id\": \"tmf:isHeadOffice\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isLegalEntity\": {\n \
  \     \"@id\": \"tmf:isLegalEntity\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"issuingAuthority\": {\n      \"@id\": \"tmf:issuingAuthority\",\n      \"@type\": \"xsd:string\"\n    },\n    \"issuingDate\": {\n      \"@id\": \"tmf:issuingDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"issuingJurisdiction\": {\n      \"@id\": \"tmf:issuingJurisdiction\",\n      \"@type\": \"xsd:string\"\n    },\n    \"jurisdictionLevel\": {\n      \"@id\": \"tmf:jurisdictionLevel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"jurisdictionName\": {\n      \"@id\": \"tmf:jurisdictionName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"languageAbility\": {\n      \"@id\": \"tmf:languageAbility\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"languageCode\": {\n      \"@id\": \"tmf:languageCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"languageName\": {\n      \"@id\": \"tmf:languageName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"legalName\"\
  : {\n      \"@id\": \"tmf:legalName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"listeningProficiency\": {\n      \"@id\": \"tmf:listeningProficiency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"location\": {\n      \"@id\": \"tmf:location\",\n      \"@type\": \"xsd:string\"\n    },\n    \"maritalStatus\": {\n      \"@id\": \"tmf:maritalStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"middleName\": {\n      \"@id\": \"tmf:middleName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mimeType\": {\n      \"@id\": \"tmf:mimeType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\"\n    },\n    \"nameType\": {\n      \"@id\": \"tmf:nameType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nationality\": {\n      \"@id\": \"tmf:nationality\",\n      \"@type\": \"xsd:string\"\n    },\n    \"op\": {\n      \"@id\": \"tmf:op\",\n      \"@type\": \"xsd:string\"\n    },\n    \"organization\": {\n      \"@id\": \"tmf:organization\",\n\
  \      \"@type\": \"xsd:string\"\n    },\n    \"organizationChildRelationship\": {\n      \"@id\": \"tmf:organizationChildRelationship\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"organizationIdentification\": {\n      \"@id\": \"tmf:organizationIdentification\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"organizationParentRelationship\": {\n      \"@id\": \"tmf:organizationParentRelationship\",\n      \"@type\": \"xsd:string\"\n    },\n    \"organizationType\": {\n      \"@id\": \"tmf:organizationType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"otherName\": {\n      \"@id\": \"tmf:otherName\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"owner\": {\n      \"@id\": \"tmf:owner\",\n      \"@type\": \"xsd:string\"\n    },\n    \"partyCharacteristic\": {\n      \"@id\": \"tmf:partyCharacteristic\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"partyOrPartyRole\": {\n      \"@id\": \"tmf:partyOrPartyRole\",\n      \"@type\": \"xsd:string\"\n    },\n    \"partyRoleSpecification\": {\n      \"@id\": \"tmf:partyRoleSpecification\",\n      \"@type\": \"xsd:string\"\n    },\n    \"path\": {\n      \"@id\": \"tmf:path\",\n      \"@type\": \"xsd:string\"\n    },\n    \"paymentMethod\": {\n      \"@id\": \"tmf:paymentMethod\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"phoneNumber\": {\n      \"@id\": \"tmf:phoneNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"placeOfBirth\": {\n      \"@id\": \"tmf:placeOfBirth\",\n      \"@type\": \"xsd:string\"\n    },\n    \"postCode\": {\n      \"@id\": \"tmf:postCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"preferred\": {\n      \"@id\": \"tmf:preferred\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"preferredGivenName\": {\n      \"@id\": \"tmf:preferredGivenName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ratingReference\"\
  : {\n      \"@id\": \"tmf:ratingReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ratingScore\": {\n      \"@id\": \"tmf:ratingScore\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"readingProficiency\": {\n      \"@id\": \"tmf:readingProficiency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reason\": {\n      \"@id\": \"tmf:reason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"relatedParty\": {\n      \"@id\": \"tmf:relatedParty\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"relationshipType\": {\n      \"@id\": \"tmf:relationshipType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"role\": {\n      \"@id\": \"tmf:role\",\n      \"@type\": \"xsd:string\"\n    },\n    \"size\": {\n      \"@id\": \"tmf:size\",\n      \"@type\": \"xsd:string\"\n    },\n    \"skill\": {\n      \"@id\": \"tmf:skill\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"skillCode\": {\n      \"@id\": \"tmf:skillCode\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"skillName\": {\n      \"@id\": \"tmf:skillName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"socialNetworkId\": {\n      \"@id\": \"tmf:socialNetworkId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"speakingProficiency\": {\n      \"@id\": \"tmf:speakingProficiency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startDateTime\": {\n      \"@id\": \"tmf:startDateTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"stateOrProvince\": {\n      \"@id\": \"tmf:stateOrProvince\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"tmf:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"statusReason\": {\n      \"@id\": \"tmf:statusReason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"street1\": {\n      \"@id\": \"tmf:street1\",\n      \"@type\": \"xsd:string\"\n    },\n    \"street2\": {\n      \"@id\": \"tmf:street2\",\n      \"@type\": \"xsd:string\"\n    },\n    \"taxDefinition\": {\n \
  \     \"@id\": \"tmf:taxDefinition\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"taxExemptionCertificate\": {\n      \"@id\": \"tmf:taxExemptionCertificate\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"taxType\": {\n      \"@id\": \"tmf:taxType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"title\": {\n      \"@id\": \"tmf:title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tradingName\": {\n      \"@id\": \"tmf:tradingName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"units\": {\n      \"@id\": \"tmf:units\",\n      \"@type\": \"xsd:string\"\n    },\n    \"url\": {\n      \"@id\": \"schema:url\"\n    },\n    \"validFor\": {\n      \"@id\": \"tmf:validFor\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"tmf:value\"\n    },\n    \"valueType\": {\n      \"@id\": \"tmf:valueType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"writingProficiency\": {\n      \"@id\": \"\
  tmf:writingProficiency\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/tm-forum/refs/heads/main/json-ld/tm-forum-tmf629-customer-context.jsonld
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
