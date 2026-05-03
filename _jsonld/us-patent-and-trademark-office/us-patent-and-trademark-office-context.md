---
api_specs:
- filename: swagger.yaml
  format: yaml
  label: USPTO Open Data Portal API
  slug: open-data-portal-api
  spec_type: OpenAPI
  url: https://data.uspto.gov/swagger/swagger.yaml
- filename: uspto-tsdr-openapi.yml
  format: yaml
  label: USPTO Trademark Status and Document Retrieval API
  slug: tsdr-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/us-patent-and-trademark-office/refs/heads/main/openapi/uspto-tsdr-openapi.yml
class_count: 3
classes:
- PatentApplication
- TrademarkRegistration
- PtabProceeding
context_file: json-ld/us-patent-and-trademark-office-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/us-patent-and-trademark-office/refs/heads/main/json-ld/us-patent-and-trademark-office-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Us Patent And Trademark Office from US Patent and Trademark Office.
layout: jsonld
name: Us Patent And Trademark Office Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: patent
  uri: https://data.uspto.gov/vocab/patent/
- prefix: trademark
  uri: https://data.uspto.gov/vocab/trademark/
- prefix: ptab
  uri: https://data.uspto.gov/vocab/ptab/
properties:
- container: ''
  name: applicationNumberText
  type: string
- container: ''
  name: applicationTypeLabelName
  type: string
- container: ''
  name: applicationFilingDate
  type: date
- container: ''
  name: grantDate
  type: date
- container: ''
  name: patentNumber
  type: string
- container: ''
  name: inventionTitle
  type: string
- container: set
  name: inventors
  type: ''
- container: ''
  name: inventorNameText
  type: string
- container: set
  name: applicants
  type: ''
- container: ''
  name: applicantNameText
  type: string
- container: ''
  name: serialNumber
  type: string
- container: ''
  name: registrationNumber
  type: string
- container: ''
  name: markLiteralElements
  type: string
- container: ''
  name: registrationDate
  type: date
- container: ''
  name: ownerName
  type: string
- container: ''
  name: goodsAndServices
  type: string
- container: set
  name: internationalClassCodes
  type: ''
- container: ''
  name: trialNumber
  type: string
- container: ''
  name: proceedingTypeCode
  type: string
- container: ''
  name: petitionerPartyName
  type: string
- container: ''
  name: respondentPartyName
  type: string
property_count: 21
provider_name: US Patent and Trademark Office
provider_slug: us-patent-and-trademark-office
slug: us-patent-and-trademark-office-context
source_filename: us-patent-and-trademark-office-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"patent\": \"https://data.uspto.gov/vocab/patent/\",\n    \"trademark\": \"https://data.uspto.gov/vocab/trademark/\",\n    \"ptab\": \"https://data.uspto.gov/vocab/ptab/\",\n\n    \"PatentApplication\": \"schema:CreativeWork\",\n    \"TrademarkRegistration\": \"schema:Intangible\",\n    \"PtabProceeding\": \"schema:LegalService\",\n\n    \"applicationNumberText\": {\n      \"@id\": \"patent:applicationNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"applicationTypeLabelName\": {\n      \"@id\": \"patent:applicationType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"applicationFilingDate\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:date\"\n    },\n    \"grantDate\": {\n      \"@id\": \"patent:grantDate\",\n      \"@type\": \"xsd:date\"\n    },\n \
  \   \"patentNumber\": {\n      \"@id\": \"patent:patentNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"inventionTitle\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"inventors\": {\n      \"@id\": \"schema:author\",\n      \"@container\": \"@set\"\n    },\n    \"inventorNameText\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"applicants\": {\n      \"@id\": \"schema:maintainer\",\n      \"@container\": \"@set\"\n    },\n    \"applicantNameText\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"serialNumber\": {\n      \"@id\": \"trademark:serialNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"registrationNumber\": {\n      \"@id\": \"trademark:registrationNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"markLiteralElements\": {\n      \"@id\": \"trademark:markText\",\n      \"@type\": \"xsd:string\"\n    },\n    \"registrationDate\": {\n      \"@id\"\
  : \"schema:datePublished\",\n      \"@type\": \"xsd:date\"\n    },\n    \"ownerName\": {\n      \"@id\": \"schema:copyrightHolder\",\n      \"@type\": \"xsd:string\"\n    },\n    \"goodsAndServices\": {\n      \"@id\": \"trademark:goodsAndServices\",\n      \"@type\": \"xsd:string\"\n    },\n    \"internationalClassCodes\": {\n      \"@id\": \"trademark:internationalClass\",\n      \"@container\": \"@set\"\n    },\n\n    \"trialNumber\": {\n      \"@id\": \"ptab:trialNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"proceedingTypeCode\": {\n      \"@id\": \"ptab:proceedingType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"petitionerPartyName\": {\n      \"@id\": \"schema:participant\",\n      \"@type\": \"xsd:string\"\n    },\n    \"respondentPartyName\": {\n      \"@id\": \"schema:participant\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/us-patent-and-trademark-office/refs/heads/main/json-ld/us-patent-and-trademark-office-context.jsonld
tags:
- Federal Government
- Patents
- Trademarks
- Intellectual Property
- Open Data
- JSON-LD
- Linked Data
- Semantic Web
---
