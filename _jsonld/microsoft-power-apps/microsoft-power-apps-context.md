---
api_specs:
- filename: microsoft-power-apps-dataverse-web-api-openapi.yml
  format: yaml
  label: Dataverse API (Common Data Service)
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-power-apps/refs/heads/main/openapi/microsoft-power-apps-dataverse-web-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/microsoft-power-apps-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/microsoft-power-apps/refs/heads/main/json-ld/microsoft-power-apps-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Microsoft Power Apps from Microsoft Power Apps.
layout: jsonld
name: Microsoft Power Apps Context
namespaces:
- prefix: dataverse
  uri: https://learn.microsoft.com/en-us/power-apps/developer/data-platform/webapi/reference/
- prefix: schema
  uri: https://schema.org/
- prefix: odata
  uri: http://docs.oasis-open.org/odata/ns/
- prefix: crm
  uri: https://learn.microsoft.com/en-us/power-apps/developer/data-platform/webapi/reference/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: vcard
  uri: http://www.w3.org/2006/vcard/ns#
properties:
- container: ''
  name: Account
  type: ''
- container: ''
  name: Contact
  type: ''
- container: ''
  name: Entity
  type: ''
- container: ''
  name: DataverseAddress
  type: ''
- container: ''
  name: ODataCollection
  type: ''
property_count: 5
provider_name: Microsoft Power Apps
provider_slug: microsoft-power-apps
slug: microsoft-power-apps-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n\n    \"dataverse\": \"https://learn.microsoft.com/en-us/power-apps/developer/data-platform/webapi/reference/\",\n    \"schema\": \"https://schema.org/\",\n    \"odata\": \"http://docs.oasis-open.org/odata/ns/\",\n    \"crm\": \"https://learn.microsoft.com/en-us/power-apps/developer/data-platform/webapi/reference/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"vcard\": \"http://www.w3.org/2006/vcard/ns#\",\n\n    \"Account\": {\n      \"@id\": \"dataverse:account\",\n      \"@context\": {\n        \"accountid\": {\n          \"@id\": \"dataverse:account#accountid\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"schema:legalName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"accountnumber\": {\n          \"@id\": \"dataverse:account#accountnumber\",\n          \"@type\": \"xsd:string\"\n        },\n     \
  \   \"description\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"emailaddress1\": {\n          \"@id\": \"schema:email\",\n          \"@type\": \"xsd:string\"\n        },\n        \"emailaddress2\": {\n          \"@id\": \"dataverse:account#emailaddress2\",\n          \"@type\": \"xsd:string\"\n        },\n        \"emailaddress3\": {\n          \"@id\": \"dataverse:account#emailaddress3\",\n          \"@type\": \"xsd:string\"\n        },\n        \"telephone1\": {\n          \"@id\": \"schema:telephone\",\n          \"@type\": \"xsd:string\"\n        },\n        \"telephone2\": {\n          \"@id\": \"dataverse:account#telephone2\",\n          \"@type\": \"xsd:string\"\n        },\n        \"telephone3\": {\n          \"@id\": \"dataverse:account#telephone3\",\n          \"@type\": \"xsd:string\"\n        },\n        \"fax\": {\n          \"@id\": \"schema:faxNumber\",\n          \"@type\": \"xsd:string\"\n        },\n    \
  \    \"websiteurl\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"industrycode\": {\n          \"@id\": \"dataverse:account#industrycode\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"numberofemployees\": {\n          \"@id\": \"schema:numberOfEmployees\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"revenue\": {\n          \"@id\": \"dataverse:account#revenue\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"ownershipcode\": {\n          \"@id\": \"dataverse:account#ownershipcode\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"customertypecode\": {\n          \"@id\": \"dataverse:account#customertypecode\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"sic\": {\n          \"@id\": \"dataverse:account#sic\",\n          \"@type\": \"xsd:string\"\n        },\n        \"tickersymbol\": {\n          \"@id\": \"schema:tickerSymbol\",\n          \"@type\": \"xsd:string\"\
  \n        },\n        \"stockexchange\": {\n          \"@id\": \"dataverse:account#stockexchange\",\n          \"@type\": \"xsd:string\"\n        },\n        \"creditlimit\": {\n          \"@id\": \"dataverse:account#creditlimit\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"creditonhold\": {\n          \"@id\": \"dataverse:account#creditonhold\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"address1_line1\": {\n          \"@id\": \"schema:streetAddress\",\n          \"@type\": \"xsd:string\"\n        },\n        \"address1_city\": {\n          \"@id\": \"schema:addressLocality\",\n          \"@type\": \"xsd:string\"\n        },\n        \"address1_stateorprovince\": {\n          \"@id\": \"schema:addressRegion\",\n          \"@type\": \"xsd:string\"\n        },\n        \"address1_postalcode\": {\n          \"@id\": \"schema:postalCode\",\n          \"@type\": \"xsd:string\"\n        },\n        \"address1_country\": {\n          \"@id\": \"schema:addressCountry\"\
  ,\n          \"@type\": \"xsd:string\"\n        },\n        \"address1_latitude\": {\n          \"@id\": \"schema:latitude\",\n          \"@type\": \"xsd:double\"\n        },\n        \"address1_longitude\": {\n          \"@id\": \"schema:longitude\",\n          \"@type\": \"xsd:double\"\n        },\n        \"statecode\": {\n          \"@id\": \"dataverse:account#statecode\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"statuscode\": {\n          \"@id\": \"dataverse:account#statuscode\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"createdon\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"modifiedon\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"primarycontactid\": {\n          \"@id\": \"dataverse:account#primarycontactid\",\n          \"@type\": \"@id\"\n        },\n        \"parentaccountid\": {\n          \"@id\": \"dataverse:account#parentaccountid\"\
  ,\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Contact\": {\n      \"@id\": \"dataverse:contact\",\n      \"@context\": {\n        \"contactid\": {\n          \"@id\": \"dataverse:contact#contactid\",\n          \"@type\": \"xsd:string\"\n        },\n        \"firstname\": {\n          \"@id\": \"schema:givenName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"lastname\": {\n          \"@id\": \"schema:familyName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"fullname\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"middlename\": {\n          \"@id\": \"schema:additionalName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"nickname\": {\n          \"@id\": \"dataverse:contact#nickname\",\n          \"@type\": \"xsd:string\"\n        },\n        \"salutation\": {\n          \"@id\": \"schema:honorificPrefix\",\n          \"@type\": \"xsd:string\"\n        },\n        \"\
  suffix\": {\n          \"@id\": \"schema:honorificSuffix\",\n          \"@type\": \"xsd:string\"\n        },\n        \"jobtitle\": {\n          \"@id\": \"schema:jobTitle\",\n          \"@type\": \"xsd:string\"\n        },\n        \"department\": {\n          \"@id\": \"dataverse:contact#department\",\n          \"@type\": \"xsd:string\"\n        },\n        \"emailaddress1\": {\n          \"@id\": \"schema:email\",\n          \"@type\": \"xsd:string\"\n        },\n        \"emailaddress2\": {\n          \"@id\": \"dataverse:contact#emailaddress2\",\n          \"@type\": \"xsd:string\"\n        },\n        \"emailaddress3\": {\n          \"@id\": \"dataverse:contact#emailaddress3\",\n          \"@type\": \"xsd:string\"\n        },\n        \"telephone1\": {\n          \"@id\": \"schema:telephone\",\n          \"@type\": \"xsd:string\"\n        },\n        \"telephone2\": {\n          \"@id\": \"dataverse:contact#telephone2\",\n          \"@type\": \"xsd:string\"\n        },\n       \
  \ \"telephone3\": {\n          \"@id\": \"dataverse:contact#telephone3\",\n          \"@type\": \"xsd:string\"\n        },\n        \"mobilephone\": {\n          \"@id\": \"dataverse:contact#mobilephone\",\n          \"@type\": \"xsd:string\"\n        },\n        \"fax\": {\n          \"@id\": \"schema:faxNumber\",\n          \"@type\": \"xsd:string\"\n        },\n        \"websiteurl\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"gendercode\": {\n          \"@id\": \"schema:gender\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"birthdate\": {\n          \"@id\": \"schema:birthDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"anniversary\": {\n          \"@id\": \"dataverse:contact#anniversary\",\n          \"@type\": \"xsd:date\"\n        },\n        \"spousesname\": {\n          \"@id\"\
  : \"schema:spouse\",\n          \"@type\": \"xsd:string\"\n        },\n        \"numberofchildren\": {\n          \"@id\": \"dataverse:contact#numberofchildren\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"address1_line1\": {\n          \"@id\": \"schema:streetAddress\",\n          \"@type\": \"xsd:string\"\n        },\n        \"address1_city\": {\n          \"@id\": \"schema:addressLocality\",\n          \"@type\": \"xsd:string\"\n        },\n        \"address1_stateorprovince\": {\n          \"@id\": \"schema:addressRegion\",\n          \"@type\": \"xsd:string\"\n        },\n        \"address1_postalcode\": {\n          \"@id\": \"schema:postalCode\",\n          \"@type\": \"xsd:string\"\n        },\n        \"address1_country\": {\n          \"@id\": \"schema:addressCountry\",\n          \"@type\": \"xsd:string\"\n        },\n        \"address1_latitude\": {\n          \"@id\": \"schema:latitude\",\n          \"@type\": \"xsd:double\"\n        },\n        \"address1_longitude\"\
  : {\n          \"@id\": \"schema:longitude\",\n          \"@type\": \"xsd:double\"\n        },\n        \"statecode\": {\n          \"@id\": \"dataverse:contact#statecode\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"statuscode\": {\n          \"@id\": \"dataverse:contact#statuscode\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"createdon\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"modifiedon\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"parentcustomerid\": {\n          \"@id\": \"dataverse:contact#parentcustomerid\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Entity\": {\n      \"@id\": \"dataverse:entity\",\n      \"@context\": {\n        \"entityid\": {\n          \"@id\": \"dataverse:entity#entityid\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\"\
  ,\n          \"@type\": \"xsd:string\"\n        },\n        \"logicalname\": {\n          \"@id\": \"dataverse:entity#logicalname\",\n          \"@type\": \"xsd:string\"\n        },\n        \"logicalcollectionname\": {\n          \"@id\": \"dataverse:entity#logicalcollectionname\",\n          \"@type\": \"xsd:string\"\n        },\n        \"collectionname\": {\n          \"@id\": \"dataverse:entity#collectionname\",\n          \"@type\": \"xsd:string\"\n        },\n        \"entitysetname\": {\n          \"@id\": \"dataverse:entity#entitysetname\",\n          \"@type\": \"xsd:string\"\n        },\n        \"physicalname\": {\n          \"@id\": \"dataverse:entity#physicalname\",\n          \"@type\": \"xsd:string\"\n        },\n        \"basetablename\": {\n          \"@id\": \"dataverse:entity#basetablename\",\n          \"@type\": \"xsd:string\"\n        },\n        \"externalname\": {\n          \"@id\": \"dataverse:entity#externalname\",\n          \"@type\": \"xsd:string\"\n    \
  \    },\n        \"isactivity\": {\n          \"@id\": \"dataverse:entity#isactivity\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"objecttypecode\": {\n          \"@id\": \"dataverse:entity#objecttypecode\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"componentstate\": {\n          \"@id\": \"dataverse:entity#componentstate\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"DataverseAddress\": {\n      \"@id\": \"schema:PostalAddress\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"line1\": {\n          \"@id\": \"schema:streetAddress\",\n          \"@type\": \"xsd:string\"\n        },\n        \"city\": {\n          \"@id\": \"schema:addressLocality\",\n          \"@type\": \"xsd:string\"\n        },\n        \"stateorprovince\": {\n          \"@id\": \"schema:addressRegion\",\n          \"@type\": \"xsd:string\"\n        },\n   \
  \     \"postalcode\": {\n          \"@id\": \"schema:postalCode\",\n          \"@type\": \"xsd:string\"\n        },\n        \"country\": {\n          \"@id\": \"schema:addressCountry\",\n          \"@type\": \"xsd:string\"\n        },\n        \"county\": {\n          \"@id\": \"dataverse:customeraddress#county\",\n          \"@type\": \"xsd:string\"\n        },\n        \"telephone1\": {\n          \"@id\": \"schema:telephone\",\n          \"@type\": \"xsd:string\"\n        },\n        \"fax\": {\n          \"@id\": \"schema:faxNumber\",\n          \"@type\": \"xsd:string\"\n        },\n        \"latitude\": {\n          \"@id\": \"schema:latitude\",\n          \"@type\": \"xsd:double\"\n        },\n        \"longitude\": {\n          \"@id\": \"schema:longitude\",\n          \"@type\": \"xsd:double\"\n        }\n      }\n    },\n\n    \"ODataCollection\": {\n      \"@id\": \"odata:Collection\",\n      \"@context\": {\n        \"value\": {\n          \"@id\": \"odata:value\",\n     \
  \     \"@container\": \"@list\"\n        },\n        \"count\": {\n          \"@id\": \"odata:count\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"nextLink\": {\n          \"@id\": \"odata:nextLink\",\n          \"@type\": \"@id\"\n        },\n        \"context\": {\n          \"@id\": \"odata:context\",\n          \"@type\": \"@id\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/microsoft-power-apps/refs/heads/main/json-ld/microsoft-power-apps-context.jsonld
tags:
- Business Applications
- Cloud
- Enterprise
- Low-Code
- Microsoft
- No-Code
- Power Platform
- SaaS
- JSON-LD
- Linked Data
- Semantic Web
---
