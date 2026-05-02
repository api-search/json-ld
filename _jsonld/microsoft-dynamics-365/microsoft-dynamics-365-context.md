---
api_specs:
- filename: $metadata
  format: yaml
  label: Dynamics 365 Sales API
  slug: ''
  spec_type: OpenAPI
  url: https://[org].api.crm.dynamics.com/api/data/v9.2/$metadata
- filename: $metadata
  format: yaml
  label: Dynamics 365 Customer Service API
  slug: ''
  spec_type: OpenAPI
  url: https://[org].api.crm.dynamics.com/api/data/v9.2/$metadata
- filename: openapi
  format: yaml
  label: Dynamics 365 Business Central API
  slug: ''
  spec_type: OpenAPI
  url: https://docs.microsoft.com/dynamics365/business-central/dev-itpro/api-reference/v2.0/openapi
- filename: microsoft-dynamics-365-dataverse-web-api-openapi.yml
  format: yaml
  label: Microsoft Dataverse Web API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-dynamics-365/refs/heads/main/openapi/microsoft-dynamics-365-dataverse-web-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/microsoft-dynamics-365-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/microsoft-dynamics-365/refs/heads/main/json-ld/microsoft-dynamics-365-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Microsoft Dynamics 365 from Microsoft Dynamics 365.
layout: jsonld
name: Microsoft Dynamics 365 Context
namespaces:
- prefix: dynamics
  uri: https://learn.microsoft.com/en-us/power-apps/developer/data-platform/webapi/reference/
- prefix: odata
  uri: http://www.odata.org/vocabularies/
- prefix: crm
  uri: https://docs.microsoft.com/en-us/dynamics365/developer/reference/entities/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: Account
  type: ''
- container: ''
  name: Contact
  type: ''
- container: ''
  name: Opportunity
  type: ''
property_count: 3
provider_name: Microsoft Dynamics 365
provider_slug: microsoft-dynamics-365
slug: microsoft-dynamics-365-context
source_filename: microsoft-dynamics-365-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"dynamics\": \"https://learn.microsoft.com/en-us/power-apps/developer/data-platform/webapi/reference/\",\n    \"odata\": \"http://www.odata.org/vocabularies/\",\n    \"crm\": \"https://docs.microsoft.com/en-us/dynamics365/developer/reference/entities/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Account\": {\n      \"@id\": \"dynamics:account\",\n      \"@context\": {\n        \"accountid\": {\n          \"@id\": \"dynamics:account#accountid\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"accountnumber\": {\n          \"@id\": \"dynamics:account#accountnumber\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"emailaddress1\": {\n      \
  \    \"@id\": \"schema:email\",\n          \"@type\": \"xsd:string\"\n        },\n        \"telephone1\": {\n          \"@id\": \"schema:telephone\",\n          \"@type\": \"xsd:string\"\n        },\n        \"fax\": {\n          \"@id\": \"schema:faxNumber\",\n          \"@type\": \"xsd:string\"\n        },\n        \"websiteurl\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"revenue\": {\n          \"@id\": \"dynamics:account#revenue\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"numberofemployees\": {\n          \"@id\": \"schema:numberOfEmployees\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"industrycode\": {\n          \"@id\": \"dynamics:account#industrycode\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"ownershipcode\": {\n          \"@id\": \"dynamics:account#ownershipcode\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"sic\": {\n          \"@id\": \"dynamics:account#sic\"\
  ,\n          \"@type\": \"xsd:string\"\n        },\n        \"tickersymbol\": {\n          \"@id\": \"schema:tickerSymbol\",\n          \"@type\": \"xsd:string\"\n        },\n        \"stockexchange\": {\n          \"@id\": \"dynamics:account#stockexchange\",\n          \"@type\": \"xsd:string\"\n        },\n        \"creditlimit\": {\n          \"@id\": \"dynamics:account#creditlimit\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"creditonhold\": {\n          \"@id\": \"dynamics:account#creditonhold\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"marketcap\": {\n          \"@id\": \"dynamics:account#marketcap\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"statecode\": {\n          \"@id\": \"dynamics:account#statecode\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"statuscode\": {\n          \"@id\": \"dynamics:account#statuscode\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"address1_line1\": {\n      \
  \    \"@id\": \"schema:streetAddress\",\n          \"@type\": \"xsd:string\"\n        },\n        \"address1_city\": {\n          \"@id\": \"schema:addressLocality\",\n          \"@type\": \"xsd:string\"\n        },\n        \"address1_stateorprovince\": {\n          \"@id\": \"schema:addressRegion\",\n          \"@type\": \"xsd:string\"\n        },\n        \"address1_postalcode\": {\n          \"@id\": \"schema:postalCode\",\n          \"@type\": \"xsd:string\"\n        },\n        \"address1_country\": {\n          \"@id\": \"schema:addressCountry\",\n          \"@type\": \"xsd:string\"\n        },\n        \"address1_latitude\": {\n          \"@id\": \"schema:latitude\",\n          \"@type\": \"xsd:double\"\n        },\n        \"address1_longitude\": {\n          \"@id\": \"schema:longitude\",\n          \"@type\": \"xsd:double\"\n        },\n        \"createdon\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"modifiedon\"\
  : {\n          \"@id\": \"schema:dateModified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Contact\": {\n      \"@id\": \"dynamics:contact\",\n      \"@context\": {\n        \"contactid\": {\n          \"@id\": \"dynamics:contact#contactid\",\n          \"@type\": \"xsd:string\"\n        },\n        \"firstname\": {\n          \"@id\": \"schema:givenName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"middlename\": {\n          \"@id\": \"schema:additionalName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"lastname\": {\n          \"@id\": \"schema:familyName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"fullname\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"salutation\": {\n          \"@id\": \"schema:honorificPrefix\",\n          \"@type\": \"xsd:string\"\n        },\n        \"suffix\": {\n          \"@id\": \"schema:honorificSuffix\",\n         \
  \ \"@type\": \"xsd:string\"\n        },\n        \"jobtitle\": {\n          \"@id\": \"schema:jobTitle\",\n          \"@type\": \"xsd:string\"\n        },\n        \"department\": {\n          \"@id\": \"dynamics:contact#department\",\n          \"@type\": \"xsd:string\"\n        },\n        \"emailaddress1\": {\n          \"@id\": \"schema:email\",\n          \"@type\": \"xsd:string\"\n        },\n        \"telephone1\": {\n          \"@id\": \"schema:telephone\",\n          \"@type\": \"xsd:string\"\n        },\n        \"mobilephone\": {\n          \"@id\": \"dynamics:contact#mobilephone\",\n          \"@type\": \"xsd:string\"\n        },\n        \"fax\": {\n          \"@id\": \"schema:faxNumber\",\n          \"@type\": \"xsd:string\"\n        },\n        \"websiteurl\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"birthday\"\
  : {\n          \"@id\": \"schema:birthDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"gendercode\": {\n          \"@id\": \"schema:gender\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"annualincome\": {\n          \"@id\": \"dynamics:contact#annualincome\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"statecode\": {\n          \"@id\": \"dynamics:contact#statecode\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"statuscode\": {\n          \"@id\": \"dynamics:contact#statuscode\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"address1_line1\": {\n          \"@id\": \"schema:streetAddress\",\n          \"@type\": \"xsd:string\"\n        },\n        \"address1_city\": {\n          \"@id\": \"schema:addressLocality\",\n          \"@type\": \"xsd:string\"\n        },\n        \"address1_stateorprovince\": {\n          \"@id\": \"schema:addressRegion\",\n          \"@type\": \"xsd:string\"\n        },\n        \"\
  address1_postalcode\": {\n          \"@id\": \"schema:postalCode\",\n          \"@type\": \"xsd:string\"\n        },\n        \"address1_country\": {\n          \"@id\": \"schema:addressCountry\",\n          \"@type\": \"xsd:string\"\n        },\n        \"createdon\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"modifiedon\": {\n          \"@id\": \"schema:dateModified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Opportunity\": {\n      \"@id\": \"crm:opportunity\",\n      \"@context\": {\n        \"opportunityid\": {\n          \"@id\": \"crm:opportunity#opportunityid\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"estimatedvalue\": {\n          \"@id\"\
  : \"crm:opportunity#estimatedvalue\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"actualvalue\": {\n          \"@id\": \"crm:opportunity#actualvalue\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"closeprobability\": {\n          \"@id\": \"crm:opportunity#closeprobability\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"estimatedclosedate\": {\n          \"@id\": \"crm:opportunity#estimatedclosedate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"actualclosedate\": {\n          \"@id\": \"crm:opportunity#actualclosedate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"stepname\": {\n          \"@id\": \"crm:opportunity#stepname\",\n          \"@type\": \"xsd:string\"\n        },\n        \"salesstage\": {\n          \"@id\": \"crm:opportunity#salesstage\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"statecode\": {\n          \"@id\": \"crm:opportunity#statecode\",\n          \"@type\": \"xsd:integer\"\
  \n        },\n        \"statuscode\": {\n          \"@id\": \"crm:opportunity#statuscode\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"opportunityratingcode\": {\n          \"@id\": \"crm:opportunity#opportunityratingcode\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"budgetamount\": {\n          \"@id\": \"crm:opportunity#budgetamount\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"budgetstatus\": {\n          \"@id\": \"crm:opportunity#budgetstatus\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"purchaseprocess\": {\n          \"@id\": \"crm:opportunity#purchaseprocess\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"purchasetimeframe\": {\n          \"@id\": \"crm:opportunity#purchasetimeframe\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"discountamount\": {\n          \"@id\": \"crm:opportunity#discountamount\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"discountpercentage\"\
  : {\n          \"@id\": \"crm:opportunity#discountpercentage\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"totalamount\": {\n          \"@id\": \"crm:opportunity#totalamount\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"totaltax\": {\n          \"@id\": \"crm:opportunity#totaltax\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"freightamount\": {\n          \"@id\": \"crm:opportunity#freightamount\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"customerneed\": {\n          \"@id\": \"crm:opportunity#customerneed\",\n          \"@type\": \"xsd:string\"\n        },\n        \"customerpainpoints\": {\n          \"@id\": \"crm:opportunity#customerpainpoints\",\n          \"@type\": \"xsd:string\"\n        },\n        \"proposedsolution\": {\n          \"@id\": \"crm:opportunity#proposedsolution\",\n          \"@type\": \"xsd:string\"\n        },\n        \"decisionmaker\": {\n          \"@id\": \"crm:opportunity#decisionmaker\"\
  ,\n          \"@type\": \"xsd:boolean\"\n        },\n        \"createdon\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"modifiedon\": {\n          \"@id\": \"schema:dateModified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/microsoft-dynamics-365/refs/heads/main/json-ld/microsoft-dynamics-365-context.jsonld
tags:
- Business Applications
- Cloud
- CRM
- Enterprise
- ERP
- Microsoft
- JSON-LD
- Linked Data
- Semantic Web
---
