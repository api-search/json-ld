---
api_specs:
- filename: walgreens-store-locator-openapi.yml
  format: yaml
  label: Walgreens Store Locator API
  slug: walgreens-store-locator
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/walgreens/refs/heads/main/openapi/walgreens-store-locator-openapi.yml
- filename: walgreens-prescription-refill-openapi.yml
  format: yaml
  label: Walgreens Prescription Refill API
  slug: walgreens-prescription-refill
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/walgreens/refs/heads/main/openapi/walgreens-prescription-refill-openapi.yml
- filename: walgreens-vaccine-scheduling-openapi.yml
  format: yaml
  label: Walgreens Vaccine Scheduling API
  slug: walgreens-vaccine-scheduling
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/walgreens/refs/heads/main/openapi/walgreens-vaccine-scheduling-openapi.yml
class_count: 40
classes:
- Store
- storeNumber
- brand
- name
- description
- latitude
- longitude
- distance
- timeZone
- street
- city
- state
- zip
- county
- areaCode
- faxNumber
- storeOpenTime
- storeCloseTime
- pharmacyOpenTime
- pharmacyCloseTime
- serviceIndicators
- npiCode
- Appointment
- engagementId
- engagementType
- Vaccine
- vaccineCode
- vaccineName
- vaccineType
- multiDose
- eligible
- Patient
- firstName
- lastName
- middleName
- gender
- smsConsent
- Prescription
- rxNo
- pharmacyNbr
context_file: json-ld/walgreens-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/walgreens/refs/heads/main/json-ld/walgreens-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Walgreens from Walgreens.
layout: jsonld
name: Walgreens Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: wag
  uri: https://developer.walgreens.com/vocab/
properties:
- container: ''
  name: address
  type: schema:PostalAddress
- container: ''
  name: phone
  type: schema:ContactPoint
- container: ''
  name: appointmentDate
  type: dateTime
- container: ''
  name: dob
  type: date
property_count: 4
provider_name: Walgreens
provider_slug: walgreens
slug: walgreens-context
source_filename: walgreens-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"wag\": \"https://developer.walgreens.com/vocab/\",\n\n    \"Store\": \"schema:Pharmacy\",\n    \"storeNumber\": \"wag:storeNumber\",\n    \"brand\": \"schema:brand\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"latitude\": \"schema:latitude\",\n    \"longitude\": \"schema:longitude\",\n    \"distance\": \"schema:distance\",\n    \"timeZone\": \"schema:TimeZone\",\n\n    \"address\": {\n      \"@id\": \"schema:address\",\n      \"@type\": \"schema:PostalAddress\"\n    },\n    \"street\": \"schema:streetAddress\",\n    \"city\": \"schema:addressLocality\",\n    \"state\": \"schema:addressRegion\",\n    \"zip\": \"schema:postalCode\",\n    \"county\": \"schema:addressCountry\",\n\n    \"phone\": {\n      \"@id\": \"schema:telephone\",\n      \"@type\": \"schema:ContactPoint\"\n    },\n    \"\
  areaCode\": \"wag:areaCode\",\n    \"faxNumber\": \"schema:faxNumber\",\n\n    \"storeOpenTime\": \"schema:openingHours\",\n    \"storeCloseTime\": \"schema:openingHours\",\n    \"pharmacyOpenTime\": \"wag:pharmacyOpenTime\",\n    \"pharmacyCloseTime\": \"wag:pharmacyCloseTime\",\n    \"serviceIndicators\": \"schema:availableService\",\n    \"npiCode\": \"wag:npiCode\",\n\n    \"Appointment\": \"schema:MedicalProcedure\",\n    \"engagementId\": \"wag:engagementId\",\n    \"appointmentDate\": {\n      \"@id\": \"schema:scheduledTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"engagementType\": \"wag:engagementType\",\n\n    \"Vaccine\": \"schema:Drug\",\n    \"vaccineCode\": \"wag:vaccineCode\",\n    \"vaccineName\": \"schema:name\",\n    \"vaccineType\": \"schema:additionalType\",\n    \"multiDose\": \"wag:multiDose\",\n    \"eligible\": \"wag:eligible\",\n\n    \"Patient\": \"schema:Patient\",\n    \"firstName\": \"schema:givenName\",\n    \"lastName\": \"schema:familyName\"\
  ,\n    \"middleName\": \"schema:additionalName\",\n    \"dob\": {\n      \"@id\": \"schema:birthDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"gender\": \"schema:gender\",\n    \"smsConsent\": \"wag:smsConsent\",\n\n    \"Prescription\": \"schema:Drug\",\n    \"rxNo\": \"wag:prescriptionNumber\",\n    \"pharmacyNbr\": \"wag:pharmacyNumber\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/walgreens/refs/heads/main/json-ld/walgreens-context.jsonld
tags:
- Pharmacy
- Healthcare
- Retail
- Prescriptions
- Vaccines
- JSON-LD
- Linked Data
- Semantic Web
---
