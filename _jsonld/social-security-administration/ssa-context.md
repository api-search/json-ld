---
api_specs:
- filename: ssa-field-office-openapi.yml
  format: yaml
  label: SSA Field Office Address API
  slug: field-office-address-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/social-security-administration/refs/heads/main/openapi/ssa-field-office-openapi.yml
- filename: ssa-resident-station-openapi.yml
  format: yaml
  label: SSA Resident Station Address API
  slug: resident-station-address-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/social-security-administration/refs/heads/main/openapi/ssa-resident-station-openapi.yml
class_count: 20
classes:
- FieldOffice
- ResidentStation
- VideoServiceDelivery
- SSNVerification
- OASDIBenefit
- BeneficiaryData
- OFFICE_CODE
- OFFICE_NAME
- ADDRESS_LINE_1
- CITY
- STATE
- ZIP_CODE
- PHONE
- FAX
- LATITUDE_NUM
- LONGITUDE_NUM
- openTime
- dayOfWeek
- opens
- closes
context_file: json-ld/ssa-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/social-security-administration/refs/heads/main/json-ld/ssa-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Ssa from Social Security Administration.
layout: jsonld
name: Ssa Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: gov
  uri: https://www.ssa.gov/ontology/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: geo
  type: schema:GeoCoordinates
- container: ''
  name: GovernmentOffice
  type: reference
- container: ''
  name: SocialSecurityAdministration
  type: reference
- container: ''
  name: addressCountry
  type: reference
- container: ''
  name: postalAddress
  type: schema:PostalAddress
- container: ''
  name: location
  type: schema:Place
property_count: 6
provider_name: Social Security Administration
provider_slug: social-security-administration
slug: ssa-context
source_filename: ssa-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"gov\": \"https://www.ssa.gov/ontology/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"geo\": \"http://www.w3.org/2003/01/geo/wgs84_pos#\",\n\n    \"GovernmentOffice\": {\n      \"@id\": \"schema:GovernmentOffice\",\n      \"@type\": \"@id\"\n    },\n    \"FieldOffice\": \"gov:FieldOffice\",\n    \"ResidentStation\": \"gov:ResidentStation\",\n    \"VideoServiceDelivery\": \"gov:VideoServiceDelivery\",\n    \"SocialSecurityAdministration\": {\n      \"@id\": \"schema:GovernmentOrganization\",\n      \"@type\": \"@id\"\n    },\n    \"SSNVerification\": \"gov:SocialSecurityNumberVerification\",\n    \"OASDIBenefit\": \"gov:OASDIBenefit\",\n    \"BeneficiaryData\": \"gov:BeneficiaryData\",\n\n    \"OFFICE_CODE\": \"schema:identifier\",\n    \"OFFICE_NAME\": \"schema:name\",\n    \"ADDRESS_LINE_1\": \"schema:streetAddress\",\n    \"CITY\": \"schema:addressLocality\",\n  \
  \  \"STATE\": \"schema:addressRegion\",\n    \"ZIP_CODE\": \"schema:postalCode\",\n    \"PHONE\": \"schema:telephone\",\n    \"FAX\": \"schema:faxNumber\",\n    \"LATITUDE_NUM\": \"geo:lat\",\n    \"LONGITUDE_NUM\": \"geo:long\",\n\n    \"openTime\": \"schema:openingHoursSpecification\",\n    \"dayOfWeek\": \"schema:dayOfWeek\",\n    \"opens\": \"schema:opens\",\n    \"closes\": \"schema:closes\",\n    \"addressCountry\": {\n      \"@id\": \"schema:addressCountry\",\n      \"@type\": \"@id\",\n      \"@value\": \"US\"\n    },\n    \"postalAddress\": {\n      \"@id\": \"schema:postalAddress\",\n      \"@type\": \"schema:PostalAddress\"\n    },\n    \"location\": {\n      \"@id\": \"schema:location\",\n      \"@type\": \"schema:Place\"\n    },\n    \"geo\": {\n      \"@id\": \"schema:geo\",\n      \"@type\": \"schema:GeoCoordinates\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/social-security-administration/refs/heads/main/json-ld/ssa-context.jsonld
tags:
- Federal Government
- Social Security
- Government API
- Open Data
- OASDI
- Disability Benefits
- Retirement Benefits
- JSON-LD
- Linked Data
- Semantic Web
---
