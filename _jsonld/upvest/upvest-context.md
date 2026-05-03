---
api_specs:
- filename: upvest-investment-api-openapi.yml
  format: yaml
  label: Upvest Investment API
  slug: investment-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/upvest/refs/heads/main/openapi/upvest-investment-api-openapi.yml
class_count: 63
classes:
- Account
- AccountCreate
- AccountReturn
- AccountTransfer
- AccountTransferCreate
- AccountUpdate
- Address
- CashBalance
- CorporateAction
- DirectDebit
- DirectDebitCreate
- Exchange
- Execution
- Fee
- FeeConfiguration
- Instrument
- InstrumentPrice
- Liquidation
- LiquidationCreate
- Mandate
- Order
- OrderCancellation
- OrderCreate
- Portfolio
- PortfolioAllocation
- PortfolioAllocationCreate
- PortfolioCreate
- PortfolioOrder
- PortfolioOrderCreate
- PortfolioUpdate
- Position
- RebalancingExecution
- ReferenceAccount
- Report
- SavingsPlan
- SavingsPlanCreate
- SavingsPlanUpdate
- SecuritiesTransfer
- SecuritiesTransferCreate
- TaxResidency
- TaxResidencyCreate
- Transaction
- TreasuryReport
- Upvest Order
- Upvest Webhook Event
- User
- UserCheck
- UserCreate
- UserIdentifier
- UserIdentifierCreate
- UserIdentifierUpdate
- UserUpdate
- Valuation
- WebhookSubscription
- WebhookSubscriptionCreate
- WebhookSubscriptionUpdate
- Withdrawal
- WithdrawalCreate
- createdAt
- email
- name
- updatedAt
- url
context_file: json-ld/upvest-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/upvest/refs/heads/main/json-ld/upvest-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Upvest from Upvest.
layout: jsonld
name: Upvest Context
namespaces:
- prefix: upvest
  uri: https://docs.upvest.co/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: accountGroupId
  type: string
- container: ''
  name: accountHolder
  type: string
- container: ''
  name: accountId
  type: string
- container: ''
  name: additionalLine
  type: string
- container: ''
  name: address
  type: reference
- container: set
  name: allocations
  type: reference
- container: ''
  name: amount
  type: string
- container: ''
  name: available
  type: string
- container: ''
  name: averageBuyInPrice
  type: string
- container: ''
  name: bic
  type: string
- container: ''
  name: cashAmount
  type: string
- container: ''
  name: city
  type: string
- container: ''
  name: completedAt
  type: dateTime
- container: ''
  name: country
  type: string
- container: ''
  name: currency
  type: string
- container: ''
  name: dateOfBirth
  type: date
- container: ''
  name: direction
  type: string
- container: set
  name: eventCategories
  type: string
- container: ''
  name: exDate
  type: date
- container: ''
  name: exchangeId
  type: string
- container: set
  name: exchanges
  type: reference
- container: ''
  name: executedAt
  type: dateTime
- container: ''
  name: fileId
  type: string
- container: ''
  name: firstName
  type: string
- container: ''
  name: fractionalTradingEnabled
  type: boolean
- container: ''
  name: frequency
  type: string
- container: ''
  name: iban
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: instrumentId
  type: string
- container: ''
  name: isin
  type: string
- container: ''
  name: lastName
  type: string
- container: ''
  name: limitPrice
  type: string
- container: ''
  name: mandateId
  type: string
- container: ''
  name: mic
  type: string
- container: ''
  name: nationality
  type: string
- container: ''
  name: nextExecutionDate
  type: date
- container: ''
  name: orderId
  type: string
- container: set
  name: payload
  type: string
- container: ''
  name: pending
  type: string
- container: ''
  name: periodEnd
  type: date
- container: ''
  name: periodStart
  type: date
- container: ''
  name: portfolioId
  type: string
- container: ''
  name: postalCode
  type: string
- container: ''
  name: price
  type: string
- container: ''
  name: quantity
  type: string
- container: ''
  name: rate
  type: string
- container: ''
  name: recordDate
  type: date
- container: ''
  name: remittanceInformation
  type: string
- container: ''
  name: side
  type: string
- container: ''
  name: sourceAccountId
  type: string
- container: ''
  name: state
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: stopPrice
  type: string
- container: ''
  name: street
  type: string
- container: ''
  name: targetAccountId
  type: string
- container: ''
  name: taxIdentificationNumber
  type: string
- container: ''
  name: timestamp
  type: dateTime
- container: ''
  name: total
  type: string
- container: ''
  name: totalReturn
  type: string
- container: ''
  name: totalReturnPercentage
  type: string
- container: ''
  name: totalValue
  type: string
- container: ''
  name: tradeable
  type: boolean
- container: ''
  name: type
  type: string
- container: ''
  name: userId
  type: string
- container: ''
  name: value
  type: string
- container: ''
  name: valuedAt
  type: dateTime
- container: ''
  name: weight
  type: string
- container: ''
  name: wkn
  type: string
property_count: 68
provider_name: Upvest
provider_slug: upvest
slug: upvest-context
source_filename: upvest-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"upvest\": \"https://docs.upvest.co/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Account\": \"upvest:Account\",\n    \"AccountCreate\": \"upvest:AccountCreate\",\n    \"AccountReturn\": \"upvest:AccountReturn\",\n    \"AccountTransfer\": \"upvest:AccountTransfer\",\n    \"AccountTransferCreate\": \"upvest:AccountTransferCreate\",\n    \"AccountUpdate\": \"upvest:AccountUpdate\",\n    \"Address\": \"upvest:Address\",\n    \"CashBalance\": \"upvest:CashBalance\",\n    \"CorporateAction\": \"upvest:CorporateAction\",\n    \"DirectDebit\": \"upvest:DirectDebit\",\n    \"DirectDebitCreate\": \"upvest:DirectDebitCreate\",\n    \"Exchange\": \"upvest:Exchange\",\n    \"Execution\": \"upvest:Execution\",\n    \"Fee\": \"upvest:Fee\",\n    \"FeeConfiguration\": \"upvest:FeeConfiguration\",\n    \"Instrument\": \"upvest:Instrument\"\
  ,\n    \"InstrumentPrice\": \"upvest:InstrumentPrice\",\n    \"Liquidation\": \"upvest:Liquidation\",\n    \"LiquidationCreate\": \"upvest:LiquidationCreate\",\n    \"Mandate\": \"upvest:Mandate\",\n    \"Order\": \"upvest:Order\",\n    \"OrderCancellation\": \"upvest:OrderCancellation\",\n    \"OrderCreate\": \"upvest:OrderCreate\",\n    \"Portfolio\": \"upvest:Portfolio\",\n    \"PortfolioAllocation\": \"upvest:PortfolioAllocation\",\n    \"PortfolioAllocationCreate\": \"upvest:PortfolioAllocationCreate\",\n    \"PortfolioCreate\": \"upvest:PortfolioCreate\",\n    \"PortfolioOrder\": \"upvest:PortfolioOrder\",\n    \"PortfolioOrderCreate\": \"upvest:PortfolioOrderCreate\",\n    \"PortfolioUpdate\": \"upvest:PortfolioUpdate\",\n    \"Position\": \"upvest:Position\",\n    \"RebalancingExecution\": \"upvest:RebalancingExecution\",\n    \"ReferenceAccount\": \"upvest:ReferenceAccount\",\n    \"Report\": \"upvest:Report\",\n    \"SavingsPlan\": \"upvest:SavingsPlan\",\n    \"SavingsPlanCreate\"\
  : \"upvest:SavingsPlanCreate\",\n    \"SavingsPlanUpdate\": \"upvest:SavingsPlanUpdate\",\n    \"SecuritiesTransfer\": \"upvest:SecuritiesTransfer\",\n    \"SecuritiesTransferCreate\": \"upvest:SecuritiesTransferCreate\",\n    \"TaxResidency\": \"upvest:TaxResidency\",\n    \"TaxResidencyCreate\": \"upvest:TaxResidencyCreate\",\n    \"Transaction\": \"upvest:Transaction\",\n    \"TreasuryReport\": \"upvest:TreasuryReport\",\n    \"Upvest Order\": \"upvest:Upvest Order\",\n    \"Upvest Webhook Event\": \"upvest:Upvest Webhook Event\",\n    \"User\": \"upvest:User\",\n    \"UserCheck\": \"upvest:UserCheck\",\n    \"UserCreate\": \"upvest:UserCreate\",\n    \"UserIdentifier\": \"upvest:UserIdentifier\",\n    \"UserIdentifierCreate\": \"upvest:UserIdentifierCreate\",\n    \"UserIdentifierUpdate\": \"upvest:UserIdentifierUpdate\",\n    \"UserUpdate\": \"upvest:UserUpdate\",\n    \"Valuation\": \"upvest:Valuation\",\n    \"WebhookSubscription\": \"upvest:WebhookSubscription\",\n    \"WebhookSubscriptionCreate\"\
  : \"upvest:WebhookSubscriptionCreate\",\n    \"WebhookSubscriptionUpdate\": \"upvest:WebhookSubscriptionUpdate\",\n    \"Withdrawal\": \"upvest:Withdrawal\",\n    \"WithdrawalCreate\": \"upvest:WithdrawalCreate\",\n    \"accountGroupId\": {\n      \"@id\": \"upvest:account_group_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accountHolder\": {\n      \"@id\": \"upvest:account_holder\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accountId\": {\n      \"@id\": \"upvest:account_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"additionalLine\": {\n      \"@id\": \"upvest:additional_line\",\n      \"@type\": \"xsd:string\"\n    },\n    \"address\": {\n      \"@id\": \"upvest:address\",\n      \"@type\": \"@id\"\n    },\n    \"allocations\": {\n      \"@id\": \"upvest:allocations\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"amount\": {\n      \"@id\": \"upvest:amount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"available\": {\n      \"@id\"\
  : \"upvest:available\",\n      \"@type\": \"xsd:string\"\n    },\n    \"averageBuyInPrice\": {\n      \"@id\": \"upvest:average_buy_in_price\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bic\": {\n      \"@id\": \"upvest:bic\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cashAmount\": {\n      \"@id\": \"upvest:cash_amount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"city\": {\n      \"@id\": \"upvest:city\",\n      \"@type\": \"xsd:string\"\n    },\n    \"completedAt\": {\n      \"@id\": \"upvest:completed_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"country\": {\n      \"@id\": \"upvest:country\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdAt\": \"schema:dateCreated\",\n    \"currency\": {\n      \"@id\": \"upvest:currency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dateOfBirth\": {\n      \"@id\": \"upvest:date_of_birth\",\n      \"@type\": \"xsd:date\"\n    },\n    \"direction\": {\n      \"@id\": \"upvest:direction\",\n      \"@type\":\
  \ \"xsd:string\"\n    },\n    \"email\": \"schema:email\",\n    \"eventCategories\": {\n      \"@id\": \"upvest:event_categories\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"exDate\": {\n      \"@id\": \"upvest:ex_date\",\n      \"@type\": \"xsd:date\"\n    },\n    \"exchangeId\": {\n      \"@id\": \"upvest:exchange_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"exchanges\": {\n      \"@id\": \"upvest:exchanges\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"executedAt\": {\n      \"@id\": \"upvest:executed_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"fileId\": {\n      \"@id\": \"upvest:file_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"firstName\": {\n      \"@id\": \"upvest:first_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fractionalTradingEnabled\": {\n      \"@id\": \"upvest:fractional_trading_enabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"frequency\": {\n      \"\
  @id\": \"upvest:frequency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"iban\": {\n      \"@id\": \"upvest:iban\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"upvest:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"instrumentId\": {\n      \"@id\": \"upvest:instrument_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isin\": {\n      \"@id\": \"upvest:isin\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastName\": {\n      \"@id\": \"upvest:last_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"limitPrice\": {\n      \"@id\": \"upvest:limit_price\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mandateId\": {\n      \"@id\": \"upvest:mandate_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mic\": {\n      \"@id\": \"upvest:mic\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"nationality\": {\n      \"@id\": \"upvest:nationality\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nextExecutionDate\"\
  : {\n      \"@id\": \"upvest:next_execution_date\",\n      \"@type\": \"xsd:date\"\n    },\n    \"orderId\": {\n      \"@id\": \"upvest:order_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"payload\": {\n      \"@id\": \"upvest:payload\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pending\": {\n      \"@id\": \"upvest:pending\",\n      \"@type\": \"xsd:string\"\n    },\n    \"periodEnd\": {\n      \"@id\": \"upvest:period_end\",\n      \"@type\": \"xsd:date\"\n    },\n    \"periodStart\": {\n      \"@id\": \"upvest:period_start\",\n      \"@type\": \"xsd:date\"\n    },\n    \"portfolioId\": {\n      \"@id\": \"upvest:portfolio_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"postalCode\": {\n      \"@id\": \"upvest:postal_code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"price\": {\n      \"@id\": \"upvest:price\",\n      \"@type\": \"xsd:string\"\n    },\n    \"quantity\": {\n      \"@id\": \"upvest:quantity\",\n      \"@type\": \"\
  xsd:string\"\n    },\n    \"rate\": {\n      \"@id\": \"upvest:rate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"recordDate\": {\n      \"@id\": \"upvest:record_date\",\n      \"@type\": \"xsd:date\"\n    },\n    \"remittanceInformation\": {\n      \"@id\": \"upvest:remittance_information\",\n      \"@type\": \"xsd:string\"\n    },\n    \"side\": {\n      \"@id\": \"upvest:side\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sourceAccountId\": {\n      \"@id\": \"upvest:source_account_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"state\": {\n      \"@id\": \"upvest:state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"upvest:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stopPrice\": {\n      \"@id\": \"upvest:stop_price\",\n      \"@type\": \"xsd:string\"\n    },\n    \"street\": {\n      \"@id\": \"upvest:street\",\n      \"@type\": \"xsd:string\"\n    },\n    \"targetAccountId\": {\n      \"@id\": \"upvest:target_account_id\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"taxIdentificationNumber\": {\n      \"@id\": \"upvest:tax_identification_number\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timestamp\": {\n      \"@id\": \"upvest:timestamp\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"total\": {\n      \"@id\": \"upvest:total\",\n      \"@type\": \"xsd:string\"\n    },\n    \"totalReturn\": {\n      \"@id\": \"upvest:total_return\",\n      \"@type\": \"xsd:string\"\n    },\n    \"totalReturnPercentage\": {\n      \"@id\": \"upvest:total_return_percentage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"totalValue\": {\n      \"@id\": \"upvest:total_value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tradeable\": {\n      \"@id\": \"upvest:tradeable\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"type\": {\n      \"@id\": \"upvest:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"updatedAt\": \"schema:dateModified\",\n    \"url\": \"schema:url\",\n    \"userId\": {\n    \
  \  \"@id\": \"upvest:user_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"upvest:value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"valuedAt\": {\n      \"@id\": \"upvest:valued_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"weight\": {\n      \"@id\": \"upvest:weight\",\n      \"@type\": \"xsd:string\"\n    },\n    \"wkn\": {\n      \"@id\": \"upvest:wkn\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/upvest/refs/heads/main/json-ld/upvest-context.jsonld
tags:
- Banking Infrastructure
- Fintech
- Investments
- Securities
- Fractional Investing
- Custody
- Wealth Management
- JSON-LD
- Linked Data
- Semantic Web
---
