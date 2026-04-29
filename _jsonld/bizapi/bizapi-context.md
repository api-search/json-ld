---
api_specs:
- filename: bizapi-business-intelligence-api-openapi.yml
  format: yaml
  label: BizAPI Business Intelligence API
  slug: bizapi
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/bizapi/refs/heads/main/openapi/bizapi-business-intelligence-api-openapi.yml
class_count: 34
classes:
- company_name
- dba
- street
- city
- state
- zip
- country
- latitude
- longitude
- phone
- fax
- email
- url
- stock_ticker
- top_contact_name
- top_contact_title
- sales_volume
- total_employees
- employees_on_site
- year_started
- location_type
- subsidiary_indicator
- duns_number
- sic_code_4
- sic_code_8
- naics_code_6
- parent_duns
- parent_name
- domestic_ultimate_duns
- domestic_ultimate_name
- global_ultimate_duns
- global_ultimate_name
- hierarchy_code
- family_member_count
context_file: json-ld/bizapi-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/bizapi/refs/heads/main/json-ld/bizapi-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Bizapi from BizAPI.
layout: jsonld
name: Bizapi Context
namespaces:
- prefix: bizapi
  uri: https://www.naics.com/ns/bizapi#
properties: []
property_count: 0
provider_name: BizAPI
provider_slug: bizapi
slug: bizapi-context
source_filename: bizapi-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"bizapi\": \"https://www.naics.com/ns/bizapi#\",\n    \"company_name\": \"schema:legalName\",\n    \"dba\": \"schema:alternateName\",\n    \"street\": \"schema:streetAddress\",\n    \"city\": \"schema:addressLocality\",\n    \"state\": \"schema:addressRegion\",\n    \"zip\": \"schema:postalCode\",\n    \"country\": \"schema:addressCountry\",\n    \"latitude\": \"schema:latitude\",\n    \"longitude\": \"schema:longitude\",\n    \"phone\": \"schema:telephone\",\n    \"fax\": \"schema:faxNumber\",\n    \"email\": \"schema:email\",\n    \"url\": \"schema:url\",\n    \"stock_ticker\": \"schema:tickerSymbol\",\n    \"top_contact_name\": \"schema:name\",\n    \"top_contact_title\": \"schema:jobTitle\",\n    \"sales_volume\": \"schema:revenue\",\n    \"total_employees\": \"schema:numberOfEmployees\",\n    \"employees_on_site\": \"bizapi:employeesOnSite\",\n    \"year_started\": \"schema:foundingDate\",\n    \"location_type\"\
  : \"bizapi:locationType\",\n    \"subsidiary_indicator\": \"bizapi:subsidiaryIndicator\",\n    \"duns_number\": \"schema:duns\",\n    \"sic_code_4\": \"bizapi:sicCode4\",\n    \"sic_code_8\": \"bizapi:sicCode8\",\n    \"naics_code_6\": \"schema:naics\",\n    \"parent_duns\": \"bizapi:parentDuns\",\n    \"parent_name\": \"schema:parentOrganization\",\n    \"domestic_ultimate_duns\": \"bizapi:domesticUltimateDuns\",\n    \"domestic_ultimate_name\": \"bizapi:domesticUltimateName\",\n    \"global_ultimate_duns\": \"bizapi:globalUltimateDuns\",\n    \"global_ultimate_name\": \"bizapi:globalUltimateName\",\n    \"hierarchy_code\": \"bizapi:hierarchyCode\",\n    \"family_member_count\": \"bizapi:familyMemberCount\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/bizapi/refs/heads/main/json-ld/bizapi-context.jsonld
tags:
- Business Intelligence
- Company Data
- CRM
- Firmographic Data
- NAICS
- SIC
- JSON-LD
- Linked Data
- Semantic Web
---
