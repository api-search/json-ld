---
api_specs:
- filename: avalara-avatax-rest-openapi.yml
  format: yaml
  label: AvaTax APIs
  slug: avatax-apis
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/avalara/refs/heads/main/openapi/avalara-avatax-rest-openapi.yml
- filename: avalara-communications-openapi.yml
  format: yaml
  label: Communications Tax API
  slug: communications-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/avalara/refs/heads/main/openapi/avalara-communications-openapi.yml
- filename: avalara-excise-openapi.yml
  format: yaml
  label: Excise Platform API
  slug: excise-tax-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/avalara/refs/heads/main/openapi/avalara-excise-openapi.yml
- filename: avalara-item-classification-openapi.yml
  format: yaml
  label: Item Classification API
  slug: item-classification-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/avalara/refs/heads/main/openapi/avalara-item-classification-openapi.yml
- filename: avalara-avatax-brazil-openapi.yml
  format: yaml
  label: AvaTax Brazil API
  slug: avatax-brazil-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/avalara/refs/heads/main/openapi/avalara-avatax-brazil-openapi.yml
- filename: avalara-vat-reporting-openapi.yml
  format: yaml
  label: VAT Reporting API
  slug: vat-reporting-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/avalara/refs/heads/main/openapi/avalara-vat-reporting-openapi.yml
- filename: avalara-mylodgetax-openapi.yml
  format: yaml
  label: MyLodgeTax API
  slug: mylodgetax-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/avalara/refs/heads/main/openapi/avalara-mylodgetax-openapi.yml
- filename: avalara-certcapture-openapi.yml
  format: yaml
  label: CertCapture API
  slug: certcapture-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/avalara/refs/heads/main/openapi/avalara-certcapture-openapi.yml
- filename: avalara-e-invoicing-openapi.yml
  format: yaml
  label: E-Invoicing REST API
  slug: e-invoicing-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/avalara/refs/heads/main/openapi/avalara-e-invoicing-openapi.yml
- filename: avalara-activation-service-openapi.yml
  format: yaml
  label: Activation Service API
  slug: activation-service-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/avalara/refs/heads/main/openapi/avalara-activation-service-openapi.yml
- filename: avalara-business-openapi.yml
  format: yaml
  label: Avalara Business API
  slug: business-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/avalara/refs/heads/main/openapi/avalara-business-openapi.yml
- filename: avalara-portal-oauth-openapi.yml
  format: yaml
  label: Portal OAuth API
  slug: portal-oauth-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/avalara/refs/heads/main/openapi/avalara-portal-oauth-openapi.yml
- filename: avalara-shared-company-service-openapi.yml
  format: yaml
  label: Shared Company Service API
  slug: shared-company-service-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/avalara/refs/heads/main/openapi/avalara-shared-company-service-openapi.yml
- filename: avalara-hs-code-classification-openapi.yml
  format: yaml
  label: Automated Tariff Code Classification API
  slug: hs-code-classification-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/avalara/refs/heads/main/openapi/avalara-hs-code-classification-openapi.yml
- filename: avalara-1099-w9-openapi.yml
  format: yaml
  label: 1099 & W-9 API
  slug: 1099-w9-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/avalara/refs/heads/main/openapi/avalara-1099-w9-openapi.yml
class_count: 0
classes: []
context_file: json-ld/avalara-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/avalara/refs/heads/main/json-ld/avalara-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Avalara from Avalara.
layout: jsonld
name: Avalara Context
namespaces:
- prefix: avalara
  uri: https://developer.avalara.com/schemas/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Transaction
  type: ''
- container: ''
  name: Company
  type: ''
- container: ''
  name: Address
  type: ''
- container: ''
  name: LineItem
  type: ''
- container: ''
  name: Certificate
  type: ''
- container: ''
  name: Customer
  type: ''
- container: ''
  name: Nexus
  type: ''
- container: ''
  name: TaxCode
  type: ''
- container: ''
  name: EInvoice
  type: ''
- container: ''
  name: ExciseTransaction
  type: ''
- container: ''
  name: HSCode
  type: ''
property_count: 11
provider_name: Avalara
provider_slug: avalara
slug: avalara-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"avalara\": \"https://developer.avalara.com/schemas/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Transaction\": {\n      \"@id\": \"avalara:Transaction\",\n      \"@context\": {\n        \"code\": \"avalara:transactionCode\",\n        \"type\": \"avalara:documentType\",\n        \"status\": \"avalara:transactionStatus\",\n        \"date\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"xsd:date\"\n        },\n        \"companyCode\": \"avalara:companyCode\",\n        \"customerCode\": \"avalara:customerCode\",\n        \"currencyCode\": \"avalara:currencyCode\",\n        \"totalAmount\": {\n          \"@id\": \"schema:totalPrice\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"totalTax\": {\n          \"@id\": \"avalara:totalTax\",\n          \"@type\": \"xsd:decimal\"\n     \
  \   },\n        \"totalTaxable\": {\n          \"@id\": \"avalara:totalTaxable\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"totalExempt\": {\n          \"@id\": \"avalara:totalExempt\",\n          \"@type\": \"xsd:decimal\"\n        }\n      }\n    },\n\n    \"Company\": {\n      \"@id\": \"avalara:Company\",\n      \"@context\": {\n        \"companyCode\": \"avalara:companyCode\",\n        \"name\": \"schema:name\",\n        \"taxpayerIdNumber\": \"avalara:taxpayerIdNumber\",\n        \"defaultCountry\": \"avalara:defaultCountry\",\n        \"baseCurrencyCode\": \"avalara:baseCurrencyCode\",\n        \"isActive\": {\n          \"@id\": \"avalara:isActive\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"isDefault\": {\n          \"@id\": \"avalara:isDefault\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"createdDate\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"modifiedDate\"\
  : {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Address\": {\n      \"@id\": \"schema:PostalAddress\",\n      \"@context\": {\n        \"line1\": \"schema:streetAddress\",\n        \"city\": \"schema:addressLocality\",\n        \"region\": \"schema:addressRegion\",\n        \"postalCode\": \"schema:postalCode\",\n        \"country\": \"schema:addressCountry\",\n        \"latitude\": {\n          \"@id\": \"schema:latitude\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"longitude\": {\n          \"@id\": \"schema:longitude\",\n          \"@type\": \"xsd:decimal\"\n        }\n      }\n    },\n\n    \"LineItem\": {\n      \"@id\": \"avalara:LineItem\",\n      \"@context\": {\n        \"number\": \"avalara:lineNumber\",\n        \"itemCode\": \"schema:sku\",\n        \"description\": \"schema:description\",\n        \"quantity\": {\n          \"@id\": \"schema:amount\",\n          \"@type\": \"xsd:decimal\"\
  \n        },\n        \"amount\": {\n          \"@id\": \"schema:price\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"taxCode\": \"avalara:taxCode\",\n        \"tax\": {\n          \"@id\": \"avalara:lineTax\",\n          \"@type\": \"xsd:decimal\"\n        }\n      }\n    },\n\n    \"Certificate\": {\n      \"@id\": \"avalara:Certificate\",\n      \"@context\": {\n        \"exemptionNumber\": \"avalara:exemptionNumber\",\n        \"exemptionReason\": \"avalara:exemptionReason\",\n        \"signedDate\": {\n          \"@id\": \"avalara:signedDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"expirationDate\": {\n          \"@id\": \"schema:expires\",\n          \"@type\": \"xsd:date\"\n        },\n        \"status\": \"avalara:certificateStatus\",\n        \"exposureZone\": \"avalara:exposureZone\"\n      }\n    },\n\n    \"Customer\": {\n      \"@id\": \"avalara:Customer\",\n      \"@context\": {\n        \"customerCode\": \"avalara:customerCode\",\n  \
  \      \"name\": \"schema:name\",\n        \"emailAddress\": \"schema:email\",\n        \"phoneNumber\": \"schema:telephone\"\n      }\n    },\n\n    \"Nexus\": {\n      \"@id\": \"avalara:Nexus\",\n      \"@context\": {\n        \"country\": \"avalara:nexusCountry\",\n        \"region\": \"avalara:nexusRegion\",\n        \"jurisName\": \"avalara:jurisdictionName\",\n        \"nexusTypeId\": \"avalara:nexusType\",\n        \"effectiveDate\": {\n          \"@id\": \"avalara:effectiveDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"endDate\": {\n          \"@id\": \"avalara:endDate\",\n          \"@type\": \"xsd:date\"\n        }\n      }\n    },\n\n    \"TaxCode\": {\n      \"@id\": \"avalara:TaxCode\",\n      \"@context\": {\n        \"taxCode\": \"avalara:taxCodeValue\",\n        \"description\": \"schema:description\",\n        \"isPhysical\": {\n          \"@id\": \"avalara:isPhysical\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"isActive\": {\n  \
  \        \"@id\": \"avalara:isActive\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"EInvoice\": {\n      \"@id\": \"avalara:EInvoice\",\n      \"@context\": {\n        \"invoiceNumber\": \"avalara:invoiceNumber\",\n        \"dataFormat\": \"avalara:dataFormat\",\n        \"status\": \"avalara:documentStatus\",\n        \"senderName\": \"schema:name\",\n        \"countryCode\": \"avalara:countryCode\",\n        \"submissionDate\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"ExciseTransaction\": {\n      \"@id\": \"avalara:ExciseTransaction\",\n      \"@context\": {\n        \"productCode\": \"avalara:productCode\",\n        \"unitOfMeasure\": \"avalara:unitOfMeasure\",\n        \"quantity\": {\n          \"@id\": \"schema:amount\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"totalTax\": {\n          \"@id\": \"avalara:totalTax\",\n          \"@type\": \"xsd:decimal\"\
  \n        }\n      }\n    },\n\n    \"HSCode\": {\n      \"@id\": \"avalara:HSCode\",\n      \"@context\": {\n        \"hsCode\": \"avalara:hsCodeValue\",\n        \"description\": \"schema:description\",\n        \"confidence\": {\n          \"@id\": \"avalara:confidence\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"chapter\": \"avalara:chapter\",\n        \"section\": \"avalara:section\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/avalara/refs/heads/main/json-ld/avalara-context.jsonld
tags:
- Taxes
- JSON-LD
- Linked Data
- Semantic Web
---
