---
api_specs:
- filename: tazama-transaction-monitoring-service-openapi.yml
  format: yaml
  label: Tazama Transaction Monitoring Service API
  slug: transaction-monitoring-service
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tazama/refs/heads/main/openapi/tazama-transaction-monitoring-service-openapi.yml
class_count: 38
classes:
- TransactionMonitoringService
- FraudDetection
- AMLCompliance
- RuleProcessor
- TypologyProcessor
- TADProc
- TransactionResponse
- RuleResult
- TypologyScore
- ISO20022Pain001
- ISO20022Pain013
- ISO20022Pacs008
- ISO20022Pacs002
- CstmrCdtTrfInitn
- CdtrPmtActvtnReq
- FIToFICstmrCdtTrf
- FIToFIPmtSts
- GrpHdr
- MsgId
- CreDtTm
- NbOfTxs
- InitgPty
- PmtInf
- Dbtr
- DbtrAcct
- DbtrAgt
- Cdtr
- CdtrAcct
- CdtrAgt
- message
- status
- ruleId
- typologyId
- score
- threshold
- triggered
- alertGenerated
- decision
context_file: json-ld/tazama-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/tazama/refs/heads/main/json-ld/tazama-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Tazama from Tazama.
layout: jsonld
name: Tazama Context
namespaces:
- prefix: tazama
  uri: https://tazama.org/vocabulary/
- prefix: iso20022
  uri: https://www.iso20022.org/vocabulary/
properties: []
property_count: 0
provider_name: Tazama
provider_slug: tazama
slug: tazama-context
source_filename: tazama-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"tazama\": \"https://tazama.org/vocabulary/\",\n    \"iso20022\": \"https://www.iso20022.org/vocabulary/\",\n    \"TransactionMonitoringService\": \"tazama:TransactionMonitoringService\",\n    \"FraudDetection\": \"tazama:FraudDetection\",\n    \"AMLCompliance\": \"tazama:AMLCompliance\",\n    \"RuleProcessor\": \"tazama:RuleProcessor\",\n    \"TypologyProcessor\": \"tazama:TypologyProcessor\",\n    \"TADProc\": \"tazama:TransactionAggregationDecisioningProcessor\",\n    \"TransactionResponse\": \"tazama:TransactionResponse\",\n    \"RuleResult\": \"tazama:RuleResult\",\n    \"TypologyScore\": \"tazama:TypologyScore\",\n    \"ISO20022Pain001\": \"iso20022:pain.001.001.11\",\n    \"ISO20022Pain013\": \"iso20022:pain.013.001.09\",\n    \"ISO20022Pacs008\": \"iso20022:pacs.008.001.10\",\n    \"ISO20022Pacs002\": \"iso20022:pacs.002.001.12\",\n    \"CstmrCdtTrfInitn\": \"iso20022:CustomerCreditTransferInitiation\"\
  ,\n    \"CdtrPmtActvtnReq\": \"iso20022:CreditorPaymentActivationRequest\",\n    \"FIToFICstmrCdtTrf\": \"iso20022:FinancialInstitutionToFinancialInstitutionCustomerCreditTransfer\",\n    \"FIToFIPmtSts\": \"iso20022:FinancialInstitutionToFinancialInstitutionPaymentStatus\",\n    \"GrpHdr\": \"iso20022:GroupHeader\",\n    \"MsgId\": \"iso20022:MessageIdentification\",\n    \"CreDtTm\": \"iso20022:CreationDateTime\",\n    \"NbOfTxs\": \"iso20022:NumberOfTransactions\",\n    \"InitgPty\": \"iso20022:InitiatingParty\",\n    \"PmtInf\": \"iso20022:PaymentInformation\",\n    \"Dbtr\": \"iso20022:Debtor\",\n    \"DbtrAcct\": \"iso20022:DebtorAccount\",\n    \"DbtrAgt\": \"iso20022:DebtorAgent\",\n    \"Cdtr\": \"iso20022:Creditor\",\n    \"CdtrAcct\": \"iso20022:CreditorAccount\",\n    \"CdtrAgt\": \"iso20022:CreditorAgent\",\n    \"message\": \"schema:description\",\n    \"status\": \"schema:status\",\n    \"ruleId\": \"tazama:ruleIdentifier\",\n    \"typologyId\": \"tazama:typologyIdentifier\"\
  ,\n    \"score\": \"tazama:score\",\n    \"threshold\": \"tazama:threshold\",\n    \"triggered\": \"tazama:triggered\",\n    \"alertGenerated\": \"tazama:alertGenerated\",\n    \"decision\": \"tazama:decision\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/tazama/refs/heads/main/json-ld/tazama-context.jsonld
tags:
- Financial Technology
- Fraud Detection
- Anti-Money Laundering
- Linux Foundation
- Open Source
- Transaction Monitoring
- ISO 20022
- Real Time
- JSON-LD
- Linked Data
- Semantic Web
---
