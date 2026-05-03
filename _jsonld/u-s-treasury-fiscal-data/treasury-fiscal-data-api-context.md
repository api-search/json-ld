---
api_specs:
- filename: treasury-fiscal-data-api-openapi.yaml
  format: yaml
  label: Treasury Fiscal Data API
  slug: fiscal-data-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/u-s-treasury-fiscal-data/refs/heads/main/openapi/treasury-fiscal-data-api-openapi.yaml
class_count: 0
classes: []
context_file: json-ld/treasury-fiscal-data-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/u-s-treasury-fiscal-data/refs/heads/main/json-ld/treasury-fiscal-data-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Treasury Fiscal Data Api from U.S. Treasury Fiscal Data.
layout: jsonld
name: Treasury Fiscal Data Api Context
namespaces:
- prefix: treasury
  uri: https://fiscaldata.treasury.gov/vocab/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: FiscalMeta
  type: ''
- container: ''
  name: FiscalLinks
  type: ''
- container: ''
  name: DebtRecord
  type: ''
- container: ''
  name: DebtToPennyResponse
  type: ''
- container: ''
  name: ExchangeRateRecord
  type: ''
- container: ''
  name: ExchangeRateResponse
  type: ''
- container: ''
  name: InterestRateRecord
  type: ''
- container: ''
  name: InterestRateResponse
  type: ''
- container: ''
  name: DailyTreasuryRecord
  type: ''
- container: ''
  name: DailyTreasuryStatementResponse
  type: ''
- container: ''
  name: MonthlyTreasuryRecord
  type: ''
- container: ''
  name: MonthlyTreasuryStatementResponse
  type: ''
- container: ''
  name: GenericFiscalResponse
  type: ''
- container: ''
  name: ErrorResponse
  type: ''
- container: ''
  name: record_date
  type: date
- container: ''
  name: tot_pub_debt_out_amt
  type: ''
- container: ''
  name: debt_held_public_amt
  type: ''
- container: ''
  name: intragov_hold_amt
  type: ''
- container: ''
  name: country
  type: ''
- container: ''
  name: currency
  type: ''
- container: ''
  name: exchange_rate
  type: ''
- container: ''
  name: country_currency_desc
  type: ''
- container: ''
  name: effective_date
  type: date
- container: ''
  name: security_desc
  type: ''
- container: ''
  name: security_type_desc
  type: ''
- container: ''
  name: avg_interest_rate_amt
  type: ''
- container: ''
  name: account_type
  type: ''
- container: ''
  name: open_today_bal
  type: ''
- container: ''
  name: deposits_withdrawls_net
  type: ''
- container: ''
  name: close_today_bal
  type: ''
- container: ''
  name: classification_desc
  type: ''
- container: ''
  name: current_month_rcpt_outly_amt
  type: ''
- container: ''
  name: current_fytd_rcpt_outly_amt
  type: ''
- container: ''
  name: prior_fytd_rcpt_outly_amt
  type: ''
- container: ''
  name: count
  type: integer
- container: ''
  name: labels
  type: ''
- container: ''
  name: total-count
  type: integer
- container: ''
  name: total-pages
  type: integer
- container: ''
  name: data
  type: ''
- container: ''
  name: meta
  type: ''
- container: ''
  name: links
  type: ''
- container: ''
  name: self
  type: ''
- container: ''
  name: first
  type: ''
- container: ''
  name: prev
  type: ''
- container: ''
  name: next
  type: ''
- container: ''
  name: last
  type: ''
- container: ''
  name: error
  type: ''
- container: ''
  name: message
  type: ''
- container: ''
  name: detail
  type: ''
- container: ''
  name: dataFormats
  type: ''
- container: ''
  name: dataTypes
  type: ''
- container: ''
  name: open_fy_bal
  type: ''
- container: ''
  name: open_mo_bal
  type: ''
- container: ''
  name: prior_yr_fytd_rcpt_outly_amt
  type: ''
- container: ''
  name: record_calendar_day
  type: ''
- container: ''
  name: record_calendar_month
  type: ''
- container: ''
  name: record_calendar_quarter
  type: ''
- container: ''
  name: record_calendar_year
  type: ''
- container: ''
  name: record_fiscal_quarter
  type: ''
- container: ''
  name: record_fiscal_year
  type: ''
- container: ''
  name: src_line_nbr
  type: ''
- container: ''
  name: status
  type: integer
property_count: 62
provider_name: U.S. Treasury Fiscal Data
provider_slug: u-s-treasury-fiscal-data
slug: treasury-fiscal-data-api-context
source_filename: treasury-fiscal-data-api-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"treasury\": \"https://fiscaldata.treasury.gov/vocab/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"FiscalMeta\": {\n      \"@id\": \"treasury:FiscalMeta\"\n    },\n    \"FiscalLinks\": {\n      \"@id\": \"treasury:FiscalLinks\"\n    },\n    \"DebtRecord\": {\n      \"@id\": \"treasury:DebtRecord\"\n    },\n    \"DebtToPennyResponse\": {\n      \"@id\": \"treasury:DebtToPennyResponse\"\n    },\n    \"ExchangeRateRecord\": {\n      \"@id\": \"treasury:ExchangeRateRecord\"\n    },\n    \"ExchangeRateResponse\": {\n      \"@id\": \"treasury:ExchangeRateResponse\"\n    },\n    \"InterestRateRecord\": {\n      \"@id\": \"treasury:InterestRateRecord\"\n    },\n    \"InterestRateResponse\": {\n      \"@id\": \"treasury:InterestRateResponse\"\n    },\n    \"DailyTreasuryRecord\": {\n      \"@id\": \"treasury:DailyTreasuryRecord\"\
  \n    },\n    \"DailyTreasuryStatementResponse\": {\n      \"@id\": \"treasury:DailyTreasuryStatementResponse\"\n    },\n    \"MonthlyTreasuryRecord\": {\n      \"@id\": \"treasury:MonthlyTreasuryRecord\"\n    },\n    \"MonthlyTreasuryStatementResponse\": {\n      \"@id\": \"treasury:MonthlyTreasuryStatementResponse\"\n    },\n    \"GenericFiscalResponse\": {\n      \"@id\": \"treasury:GenericFiscalResponse\"\n    },\n    \"ErrorResponse\": {\n      \"@id\": \"treasury:ErrorResponse\"\n    },\n    \"record_date\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:date\"\n    },\n    \"tot_pub_debt_out_amt\": {\n      \"@id\": \"treasury:totalPublicDebtOutstanding\"\n    },\n    \"debt_held_public_amt\": {\n      \"@id\": \"treasury:debtHeldByPublic\"\n    },\n    \"intragov_hold_amt\": {\n      \"@id\": \"treasury:intragovernmentalHoldings\"\n    },\n    \"country\": {\n      \"@id\": \"schema:addressCountry\"\n    },\n    \"currency\": {\n      \"@id\": \"treasury:currency\"\
  \n    },\n    \"exchange_rate\": {\n      \"@id\": \"treasury:exchangeRate\"\n    },\n    \"country_currency_desc\": {\n      \"@id\": \"treasury:countryCurrencyDescription\"\n    },\n    \"effective_date\": {\n      \"@id\": \"schema:validFrom\",\n      \"@type\": \"xsd:date\"\n    },\n    \"security_desc\": {\n      \"@id\": \"dcterms:description\"\n    },\n    \"security_type_desc\": {\n      \"@id\": \"treasury:securityTypeDescription\"\n    },\n    \"avg_interest_rate_amt\": {\n      \"@id\": \"treasury:averageInterestRate\"\n    },\n    \"account_type\": {\n      \"@id\": \"treasury:accountType\"\n    },\n    \"open_today_bal\": {\n      \"@id\": \"treasury:openingBalance\"\n    },\n    \"deposits_withdrawls_net\": {\n      \"@id\": \"treasury:depositsWithdrawalsNet\"\n    },\n    \"close_today_bal\": {\n      \"@id\": \"treasury:closingBalance\"\n    },\n    \"classification_desc\": {\n      \"@id\": \"dcterms:description\"\n    },\n    \"current_month_rcpt_outly_amt\": {\n    \
  \  \"@id\": \"treasury:currentMonthAmount\"\n    },\n    \"current_fytd_rcpt_outly_amt\": {\n      \"@id\": \"treasury:currentFYTDAmount\"\n    },\n    \"prior_fytd_rcpt_outly_amt\": {\n      \"@id\": \"treasury:priorFYTDAmount\"\n    },\n    \"count\": {\n      \"@id\": \"schema:numberOfItems\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"labels\": {\n      \"@id\": \"treasury:labels\"\n    },\n    \"total-count\": {\n      \"@id\": \"treasury:totalCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"total-pages\": {\n      \"@id\": \"treasury:totalPages\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"data\": {\n      \"@id\": \"schema:itemListElement\"\n    },\n    \"meta\": {\n      \"@id\": \"treasury:meta\"\n    },\n    \"links\": {\n      \"@id\": \"schema:potentialAction\"\n    },\n    \"self\": {\n      \"@id\": \"schema:url\"\n    },\n    \"first\": {\n      \"@id\": \"treasury:firstPage\"\n    },\n    \"prev\": {\n      \"@id\": \"treasury:previousPage\"\n    },\n\
  \    \"next\": {\n      \"@id\": \"treasury:nextPage\"\n    },\n    \"last\": {\n      \"@id\": \"treasury:lastPage\"\n    },\n    \"error\": {\n      \"@id\": \"treasury:error\"\n    },\n    \"message\": {\n      \"@id\": \"schema:description\"\n    },\n    \"detail\": {\n      \"@id\": \"treasury:errorDetail\"\n    },\n    \"dataFormats\": {\n      \"@id\": \"treasury:dataFormats\"\n    },\n    \"dataTypes\": {\n      \"@id\": \"treasury:dataTypes\"\n    },\n    \"open_fy_bal\": {\n      \"@id\": \"treasury:open_fy_bal\"\n    },\n    \"open_mo_bal\": {\n      \"@id\": \"treasury:open_mo_bal\"\n    },\n    \"prior_yr_fytd_rcpt_outly_amt\": {\n      \"@id\": \"treasury:prior_yr_fytd_rcpt_outly_amt\"\n    },\n    \"record_calendar_day\": {\n      \"@id\": \"treasury:record_calendar_day\"\n    },\n    \"record_calendar_month\": {\n      \"@id\": \"treasury:record_calendar_month\"\n    },\n    \"record_calendar_quarter\": {\n      \"@id\": \"treasury:record_calendar_quarter\"\n    },\n  \
  \  \"record_calendar_year\": {\n      \"@id\": \"treasury:record_calendar_year\"\n    },\n    \"record_fiscal_quarter\": {\n      \"@id\": \"treasury:record_fiscal_quarter\"\n    },\n    \"record_fiscal_year\": {\n      \"@id\": \"treasury:record_fiscal_year\"\n    },\n    \"src_line_nbr\": {\n      \"@id\": \"treasury:src_line_nbr\"\n    },\n    \"status\": {\n      \"@id\": \"treasury:status\",\n      \"@type\": \"xsd:integer\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/u-s-treasury-fiscal-data/refs/heads/main/json-ld/treasury-fiscal-data-api-context.jsonld
tags:
- Federal Government
- Finance
- Treasury
- National Debt
- Exchange Rates
- Economics
- JSON-LD
- Linked Data
- Semantic Web
---
