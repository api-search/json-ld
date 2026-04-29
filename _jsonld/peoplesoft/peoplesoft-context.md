---
api_specs:
- filename: rest-api.yml
  format: yaml
  label: PeopleSoft REST API
  slug: rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/peoplesoft/refs/heads/main/openapi/rest-api.yml
- filename: application-services-framework.yml
  format: yaml
  label: PeopleSoft Application Services Framework API
  slug: application-services-framework-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/peoplesoft/refs/heads/main/openapi/application-services-framework.yml
- filename: integration-broker.yml
  format: yaml
  label: PeopleSoft Integration Broker
  slug: integration-broker
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/peoplesoft/refs/heads/main/openapi/integration-broker.yml
- filename: query.yml
  format: yaml
  label: PeopleSoft Query API
  slug: query-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/peoplesoft/refs/heads/main/openapi/query.yml
- filename: component-interface.yml
  format: yaml
  label: PeopleSoft Component Interface API
  slug: component-interface-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/peoplesoft/refs/heads/main/openapi/component-interface.yml
- filename: search-framework.yml
  format: yaml
  label: PeopleSoft Search Framework API
  slug: search-framework-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/peoplesoft/refs/heads/main/openapi/search-framework.yml
- filename: notification-framework.yml
  format: yaml
  label: PeopleSoft Notification Framework API
  slug: notification-framework-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/peoplesoft/refs/heads/main/openapi/notification-framework.yml
- filename: chatbot-integration.yml
  format: yaml
  label: PeopleSoft Chatbot Integration Framework API
  slug: chatbot-integration-framework-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/peoplesoft/refs/heads/main/openapi/chatbot-integration.yml
- filename: approval-workflow-engine.yml
  format: yaml
  label: PeopleSoft Approval Workflow Engine API
  slug: approval-workflow-engine-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/peoplesoft/refs/heads/main/openapi/approval-workflow-engine.yml
- filename: process-scheduler.yml
  format: yaml
  label: PeopleSoft Process Scheduler API
  slug: process-scheduler-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/peoplesoft/refs/heads/main/openapi/process-scheduler.yml
- filename: cloud-manager.yml
  format: yaml
  label: PeopleSoft Cloud Manager API
  slug: cloud-manager-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/peoplesoft/refs/heads/main/openapi/cloud-manager.yml
- filename: update-manager.yml
  format: yaml
  label: PeopleSoft Update Manager API
  slug: update-manager-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/peoplesoft/refs/heads/main/openapi/update-manager.yml
- filename: pivot-grid.yml
  format: yaml
  label: PeopleSoft Pivot Grid API
  slug: pivot-grid-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/peoplesoft/refs/heads/main/openapi/pivot-grid.yml
- filename: hcm.yml
  format: yaml
  label: PeopleSoft HCM API
  slug: hcm-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/peoplesoft/refs/heads/main/openapi/hcm.yml
- filename: recruiting-talent-management.yml
  format: yaml
  label: PeopleSoft Recruiting and Talent Management API
  slug: recruiting-and-talent-management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/peoplesoft/refs/heads/main/openapi/recruiting-talent-management.yml
- filename: financials.yml
  format: yaml
  label: PeopleSoft Financials API
  slug: financials-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/peoplesoft/refs/heads/main/openapi/financials.yml
- filename: supply-chain-management.yml
  format: yaml
  label: PeopleSoft Supply Chain Management API
  slug: supply-chain-management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/peoplesoft/refs/heads/main/openapi/supply-chain-management.yml
- filename: crm.yml
  format: yaml
  label: PeopleSoft CRM API
  slug: crm-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/peoplesoft/refs/heads/main/openapi/crm.yml
- filename: campus-solutions.yml
  format: yaml
  label: PeopleSoft Campus Solutions API
  slug: campus-solutions-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/peoplesoft/refs/heads/main/openapi/campus-solutions.yml
- filename: enterprise-performance-management.yml
  format: yaml
  label: PeopleSoft Enterprise Performance Management API
  slug: enterprise-performance-management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/peoplesoft/refs/heads/main/openapi/enterprise-performance-management.yml
- filename: interaction-hub.yml
  format: yaml
  label: PeopleSoft Interaction Hub API
  slug: interaction-hub-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/peoplesoft/refs/heads/main/openapi/interaction-hub.yml
class_count: 8
classes:
- Case
- ClassEnrollment
- Employee
- JournalEntry
- Position
- PurchaseOrder
- Student
- Voucher
context_file: json-ld/peoplesoft-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/peoplesoft/refs/heads/main/json-ld/peoplesoft-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Peoplesoft from PeopleSoft.
layout: jsonld
name: Peoplesoft Context
namespaces:
- prefix: ps
  uri: https://docs.oracle.com/en/applications/peoplesoft/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: ACAD_CAREER
  type: string
- container: ''
  name: ACAD_LEVEL_BOT
  type: string
- container: ''
  name: ACAD_PLAN
  type: string
- container: ''
  name: ACAD_PROG
  type: string
- container: ''
  name: ACAD_STANDING
  type: string
- container: ''
  name: ACCOUNTING_PERIOD
  type: integer
- container: ''
  name: ADDRESS1
  type: string
- container: ''
  name: ADMIT_TERM
  type: string
- container: ''
  name: ANNUAL_RT
  type: decimal
- container: ''
  name: ASSIGNED_TO
  type: string
- container: ''
  name: BUSINESS_UNIT
  type: string
- container: ''
  name: BUYER_ID
  type: string
- container: ''
  name: CAMPUS
  type: string
- container: ''
  name: CASE_ID
  type: string
- container: ''
  name: CATALOG_NBR
  type: string
- container: ''
  name: CATEGORY
  type: string
- container: ''
  name: CITY
  type: string
- container: ''
  name: CLASS_NBR
  type: integer
- container: ''
  name: COMPANY
  type: string
- container: ''
  name: COUNTRY
  type: string
- container: ''
  name: CREATED_DTTM
  type: dateTime
- container: ''
  name: CRSE_ID
  type: string
- container: ''
  name: CUM_GPA
  type: decimal
- container: ''
  name: CURRENCY_CD
  type: string
- container: ''
  name: CUST_ID
  type: string
- container: ''
  name: DEPTID
  type: string
- container: ''
  name: DESCR
  type: string
- container: ''
  name: DUE_DT
  type: date
- container: ''
  name: EFFDT
  type: date
- container: ''
  name: EMAIL_ADDR
  type: string
- container: ''
  name: EMPLID
  type: string
- container: ''
  name: EMPL_STATUS
  type: string
- container: ''
  name: ENRL_STATUS_REASON
  type: string
- container: ''
  name: FIRST_NAME
  type: string
- container: ''
  name: FISCAL_YEAR
  type: integer
- container: ''
  name: FULL_PART_TIME
  type: string
- container: ''
  name: GRADE_INPUT
  type: string
- container: ''
  name: GROSS_AMT
  type: decimal
- container: ''
  name: HIRE_DT
  type: date
- container: ''
  name: HR_STATUS
  type: string
- container: ''
  name: INSTITUTION
  type: string
- container: ''
  name: INVOICE_DT
  type: date
- container: ''
  name: INVOICE_ID
  type: string
- container: ''
  name: JOBCODE
  type: string
- container: ''
  name: JOURNAL_DATE
  type: date
- container: ''
  name: JOURNAL_ID
  type: string
- container: ''
  name: JRNL_HDR_STATUS
  type: string
- container: ''
  name: LAST_NAME
  type: string
- container: ''
  name: LEDGER
  type: string
- container: set
  name: LINES
  type: string
- container: ''
  name: LOCATION
  type: string
- container: ''
  name: MAX_HEAD_COUNT
  type: integer
- container: ''
  name: NAME
  type: string
- container: ''
  name: PHONE
  type: string
- container: ''
  name: POSITION_NBR
  type: string
- container: ''
  name: POSN_STATUS
  type: string
- container: ''
  name: POSTAL
  type: string
- container: ''
  name: PO_DT
  type: date
- container: ''
  name: PO_ID
  type: string
- container: ''
  name: PO_STATUS
  type: string
- container: ''
  name: PRIORITY
  type: string
- container: ''
  name: REG_TEMP
  type: string
- container: ''
  name: REPORTS_TO
  type: string
- container: ''
  name: RESOLVED_DTTM
  type: dateTime
- container: ''
  name: SHIP_TO_LOCATION
  type: string
- container: ''
  name: STATE
  type: string
- container: ''
  name: STATUS
  type: string
- container: ''
  name: STDNT_CAR_NBR
  type: integer
- container: ''
  name: STRM
  type: string
- container: ''
  name: SUBJECT
  type: string
- container: ''
  name: SUPERVISOR_ID
  type: string
- container: ''
  name: TERMINATION_DT
  type: date
- container: ''
  name: TOT_TAKEN_GPA
  type: decimal
- container: ''
  name: UNT_TAKEN
  type: decimal
- container: ''
  name: VCHR_HDR_STATUS
  type: string
- container: ''
  name: VENDOR_ID
  type: string
- container: ''
  name: VOUCHER_ID
  type: string
property_count: 77
provider_name: PeopleSoft
provider_slug: peoplesoft
slug: peoplesoft-context
source_filename: peoplesoft-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"ps\": \"https://docs.oracle.com/en/applications/peoplesoft/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Case\": \"ps:Case\",\n    \"ClassEnrollment\": \"ps:ClassEnrollment\",\n    \"Employee\": \"ps:Employee\",\n    \"JournalEntry\": \"ps:JournalEntry\",\n    \"Position\": \"ps:Position\",\n    \"PurchaseOrder\": \"ps:PurchaseOrder\",\n    \"Student\": \"ps:Student\",\n    \"Voucher\": \"ps:Voucher\",\n    \"ACAD_CAREER\": {\n      \"@id\": \"ps:ACAD_CAREER\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ACAD_LEVEL_BOT\": {\n      \"@id\": \"ps:ACAD_LEVEL_BOT\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ACAD_PLAN\": {\n      \"@id\": \"ps:ACAD_PLAN\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ACAD_PROG\": {\n      \"@id\": \"ps:ACAD_PROG\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ACAD_STANDING\": {\n      \"@id\": \"ps:ACAD_STANDING\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"ACCOUNTING_PERIOD\": {\n      \"@id\": \"ps:ACCOUNTING_PERIOD\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"ADDRESS1\": {\n      \"@id\": \"ps:ADDRESS1\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ADMIT_TERM\": {\n      \"@id\": \"ps:ADMIT_TERM\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ANNUAL_RT\": {\n      \"@id\": \"ps:ANNUAL_RT\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"ASSIGNED_TO\": {\n      \"@id\": \"ps:ASSIGNED_TO\",\n      \"@type\": \"xsd:string\"\n    },\n    \"BUSINESS_UNIT\": {\n      \"@id\": \"ps:BUSINESS_UNIT\",\n      \"@type\": \"xsd:string\"\n    },\n    \"BUYER_ID\": {\n      \"@id\": \"ps:BUYER_ID\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CAMPUS\": {\n      \"@id\": \"ps:CAMPUS\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CASE_ID\": {\n      \"@id\": \"ps:CASE_ID\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CATALOG_NBR\": {\n      \"@id\": \"ps:CATALOG_NBR\",\n    \
  \  \"@type\": \"xsd:string\"\n    },\n    \"CATEGORY\": {\n      \"@id\": \"ps:CATEGORY\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CITY\": {\n      \"@id\": \"ps:CITY\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CLASS_NBR\": {\n      \"@id\": \"ps:CLASS_NBR\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"COMPANY\": {\n      \"@id\": \"ps:COMPANY\",\n      \"@type\": \"xsd:string\"\n    },\n    \"COUNTRY\": {\n      \"@id\": \"ps:COUNTRY\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CREATED_DTTM\": {\n      \"@id\": \"ps:CREATED_DTTM\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"CRSE_ID\": {\n      \"@id\": \"ps:CRSE_ID\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CUM_GPA\": {\n      \"@id\": \"ps:CUM_GPA\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"CURRENCY_CD\": {\n      \"@id\": \"ps:CURRENCY_CD\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CUST_ID\": {\n      \"@id\": \"ps:CUST_ID\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DEPTID\"\
  : {\n      \"@id\": \"ps:DEPTID\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DESCR\": {\n      \"@id\": \"ps:DESCR\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DUE_DT\": {\n      \"@id\": \"ps:DUE_DT\",\n      \"@type\": \"xsd:date\"\n    },\n    \"EFFDT\": {\n      \"@id\": \"ps:EFFDT\",\n      \"@type\": \"xsd:date\"\n    },\n    \"EMAIL_ADDR\": {\n      \"@id\": \"ps:EMAIL_ADDR\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EMPLID\": {\n      \"@id\": \"ps:EMPLID\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EMPL_STATUS\": {\n      \"@id\": \"ps:EMPL_STATUS\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ENRL_STATUS_REASON\": {\n      \"@id\": \"ps:ENRL_STATUS_REASON\",\n      \"@type\": \"xsd:string\"\n    },\n    \"FIRST_NAME\": {\n      \"@id\": \"ps:FIRST_NAME\",\n      \"@type\": \"xsd:string\"\n    },\n    \"FISCAL_YEAR\": {\n      \"@id\": \"ps:FISCAL_YEAR\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"FULL_PART_TIME\": {\n      \"@id\": \"ps:FULL_PART_TIME\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"GRADE_INPUT\": {\n      \"@id\": \"ps:GRADE_INPUT\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GROSS_AMT\": {\n      \"@id\": \"ps:GROSS_AMT\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"HIRE_DT\": {\n      \"@id\": \"ps:HIRE_DT\",\n      \"@type\": \"xsd:date\"\n    },\n    \"HR_STATUS\": {\n      \"@id\": \"ps:HR_STATUS\",\n      \"@type\": \"xsd:string\"\n    },\n    \"INSTITUTION\": {\n      \"@id\": \"ps:INSTITUTION\",\n      \"@type\": \"xsd:string\"\n    },\n    \"INVOICE_DT\": {\n      \"@id\": \"ps:INVOICE_DT\",\n      \"@type\": \"xsd:date\"\n    },\n    \"INVOICE_ID\": {\n      \"@id\": \"ps:INVOICE_ID\",\n      \"@type\": \"xsd:string\"\n    },\n    \"JOBCODE\": {\n      \"@id\": \"ps:JOBCODE\",\n      \"@type\": \"xsd:string\"\n    },\n    \"JOURNAL_DATE\": {\n      \"@id\": \"ps:JOURNAL_DATE\",\n      \"@type\": \"xsd:date\"\n    },\n    \"JOURNAL_ID\": {\n      \"@id\": \"ps:JOURNAL_ID\",\n      \"@type\": \"\
  xsd:string\"\n    },\n    \"JRNL_HDR_STATUS\": {\n      \"@id\": \"ps:JRNL_HDR_STATUS\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LAST_NAME\": {\n      \"@id\": \"ps:LAST_NAME\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LEDGER\": {\n      \"@id\": \"ps:LEDGER\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LINES\": {\n      \"@id\": \"ps:LINES\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LOCATION\": {\n      \"@id\": \"ps:LOCATION\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MAX_HEAD_COUNT\": {\n      \"@id\": \"ps:MAX_HEAD_COUNT\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"NAME\": {\n      \"@id\": \"ps:NAME\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PHONE\": {\n      \"@id\": \"ps:PHONE\",\n      \"@type\": \"xsd:string\"\n    },\n    \"POSITION_NBR\": {\n      \"@id\": \"ps:POSITION_NBR\",\n      \"@type\": \"xsd:string\"\n    },\n    \"POSN_STATUS\": {\n      \"@id\": \"ps:POSN_STATUS\",\n      \"@type\":\
  \ \"xsd:string\"\n    },\n    \"POSTAL\": {\n      \"@id\": \"ps:POSTAL\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PO_DT\": {\n      \"@id\": \"ps:PO_DT\",\n      \"@type\": \"xsd:date\"\n    },\n    \"PO_ID\": {\n      \"@id\": \"ps:PO_ID\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PO_STATUS\": {\n      \"@id\": \"ps:PO_STATUS\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PRIORITY\": {\n      \"@id\": \"ps:PRIORITY\",\n      \"@type\": \"xsd:string\"\n    },\n    \"REG_TEMP\": {\n      \"@id\": \"ps:REG_TEMP\",\n      \"@type\": \"xsd:string\"\n    },\n    \"REPORTS_TO\": {\n      \"@id\": \"ps:REPORTS_TO\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RESOLVED_DTTM\": {\n      \"@id\": \"ps:RESOLVED_DTTM\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"SHIP_TO_LOCATION\": {\n      \"@id\": \"ps:SHIP_TO_LOCATION\",\n      \"@type\": \"xsd:string\"\n    },\n    \"STATE\": {\n      \"@id\": \"ps:STATE\",\n      \"@type\": \"xsd:string\"\n    },\n    \"STATUS\"\
  : {\n      \"@id\": \"ps:STATUS\",\n      \"@type\": \"xsd:string\"\n    },\n    \"STDNT_CAR_NBR\": {\n      \"@id\": \"ps:STDNT_CAR_NBR\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"STRM\": {\n      \"@id\": \"ps:STRM\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SUBJECT\": {\n      \"@id\": \"ps:SUBJECT\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SUPERVISOR_ID\": {\n      \"@id\": \"ps:SUPERVISOR_ID\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TERMINATION_DT\": {\n      \"@id\": \"ps:TERMINATION_DT\",\n      \"@type\": \"xsd:date\"\n    },\n    \"TOT_TAKEN_GPA\": {\n      \"@id\": \"ps:TOT_TAKEN_GPA\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"UNT_TAKEN\": {\n      \"@id\": \"ps:UNT_TAKEN\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"VCHR_HDR_STATUS\": {\n      \"@id\": \"ps:VCHR_HDR_STATUS\",\n      \"@type\": \"xsd:string\"\n    },\n    \"VENDOR_ID\": {\n      \"@id\": \"ps:VENDOR_ID\",\n      \"@type\": \"xsd:string\"\n    },\n    \"VOUCHER_ID\"\
  : {\n      \"@id\": \"ps:VOUCHER_ID\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/peoplesoft/refs/heads/main/json-ld/peoplesoft-context.jsonld
tags:
- Campus Solutions
- CRM
- Enterprise Software
- ERP
- Financial Management
- HCM
- Supply Chain Management
- JSON-LD
- Linked Data
- Semantic Web
---
