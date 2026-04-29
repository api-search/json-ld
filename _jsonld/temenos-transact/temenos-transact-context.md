---
class_count: 31
classes:
- id
- type
- Account
- CurrentAccount
- SavingsAccount
- CorporateAccount
- IslamicAccount
- DepositAccount
- LoanAccount
- Customer
- CorporateCustomer
- Beneficiary
- Transaction
- FundTransfer
- PaymentOrder
- StandingOrder
- DirectDebit
- Product
- DepositProduct
- LoanProduct
- CardProduct
- Card
- DebitCard
- CreditCard
- Currency
- Country
- Address
- counterparty
- description
- status
- audit
context_file: json-ld/temenos-transact-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/temenos-transact/refs/heads/main/json-ld/temenos-transact-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Temenos Transact from Temenos Transact.
layout: jsonld
name: Temenos Transact Context
namespaces:
- prefix: temenos
  uri: https://developer.temenos.com/ns/transact/
- prefix: fibo
  uri: https://spec.edmcouncil.org/fibo/ontology/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
properties:
- container: ''
  name: accountId
  type: string
- container: ''
  name: accountName
  type: string
- container: ''
  name: accountType
  type: string
- container: ''
  name: customerId
  type: string
- container: ''
  name: customerName
  type: string
- container: ''
  name: customerMnemonic
  type: string
- container: ''
  name: shortName
  type: string
- container: list
  name: displayNames
  type: ''
- container: list
  name: customerNames
  type: ''
- container: ''
  name: title
  type: string
- container: ''
  name: gender
  type: string
- container: ''
  name: dateOfBirth
  type: date
- container: ''
  name: nationalityId
  type: string
- container: ''
  name: residenceId
  type: string
- container: list
  name: communicationDevices
  type: ''
- container: ''
  name: deviceType
  type: string
- container: ''
  name: deviceValue
  type: string
- container: list
  name: addresses
  type: ''
- container: ''
  name: addressType
  type: string
- container: ''
  name: addressLine1
  type: string
- container: ''
  name: addressLine2
  type: string
- container: ''
  name: city
  type: string
- container: ''
  name: state
  type: string
- container: ''
  name: postCode
  type: string
- container: ''
  name: country
  type: string
- container: ''
  name: transactionId
  type: string
- container: ''
  name: transactionType
  type: string
- container: ''
  name: debitOrCredit
  type: string
- container: ''
  name: amount
  type: decimal
- container: ''
  name: currency
  type: string
- container: ''
  name: bookingDate
  type: date
- container: ''
  name: valueDate
  type: date
- container: ''
  name: processingDate
  type: date
- container: ''
  name: reference
  type: string
- container: ''
  name: endToEndReference
  type: string
- container: ''
  name: narrative
  type: string
- container: ''
  name: counterpartyName
  type: string
- container: ''
  name: counterpartyAccountId
  type: string
- container: ''
  name: balance
  type: decimal
- container: ''
  name: workingBalance
  type: decimal
- container: ''
  name: availableBalance
  type: decimal
- container: ''
  name: clearedBalance
  type: decimal
- container: ''
  name: lockedAmount
  type: decimal
- container: ''
  name: overdraftLimit
  type: decimal
- container: ''
  name: accruedInterest
  type: decimal
- container: ''
  name: exchangeRate
  type: decimal
- container: ''
  name: chargesAmount
  type: decimal
- container: ''
  name: reversalIndicator
  type: boolean
- container: ''
  name: statementNumber
  type: string
- container: ''
  name: transactionStatus
  type: string
- container: ''
  name: channel
  type: string
- container: ''
  name: paymentMethod
  type: string
- container: ''
  name: debitAccountId
  type: string
- container: ''
  name: creditAccountId
  type: string
- container: ''
  name: debitAmount
  type: decimal
- container: ''
  name: creditAmount
  type: decimal
- container: ''
  name: debitCurrency
  type: string
- container: ''
  name: creditCurrency
  type: string
- container: ''
  name: transferType
  type: string
- container: ''
  name: paymentType
  type: string
- container: ''
  name: beneficiaryId
  type: string
- container: ''
  name: beneficiaryName
  type: string
- container: ''
  name: beneficiaryIban
  type: string
- container: ''
  name: beneficiaryBic
  type: string
- container: ''
  name: beneficiaryType
  type: string
- container: ''
  name: remittanceInformation
  type: string
- container: ''
  name: chargesType
  type: string
- container: ''
  name: iban
  type: string
- container: ''
  name: bic
  type: string
- container: ''
  name: bankName
  type: string
- container: ''
  name: frequency
  type: string
- container: ''
  name: startDate
  type: date
- container: ''
  name: endDate
  type: date
- container: ''
  name: nextPaymentDate
  type: date
- container: ''
  name: productId
  type: string
- container: ''
  name: productName
  type: string
- container: ''
  name: productGroup
  type: string
- container: ''
  name: principalAmount
  type: decimal
- container: ''
  name: outstandingBalance
  type: decimal
- container: ''
  name: interestRate
  type: decimal
- container: ''
  name: effectiveRate
  type: decimal
- container: ''
  name: maturityDate
  type: date
- container: ''
  name: disbursementDate
  type: date
- container: ''
  name: term
  type: string
- container: ''
  name: renewalType
  type: string
- container: ''
  name: repaymentFrequency
  type: string
- container: ''
  name: cardId
  type: string
- container: ''
  name: cardNumber
  type: string
- container: ''
  name: cardType
  type: string
- container: ''
  name: cardholderName
  type: string
- container: ''
  name: expiryDate
  type: string
- container: ''
  name: dailyLimit
  type: decimal
- container: ''
  name: availableLimit
  type: decimal
- container: ''
  name: currencyCode
  type: string
- container: ''
  name: currencyName
  type: string
- container: ''
  name: decimalPlaces
  type: integer
- container: ''
  name: buyRate
  type: decimal
- container: ''
  name: sellRate
  type: decimal
- container: ''
  name: midRate
  type: decimal
- container: ''
  name: countryCode
  type: string
- container: ''
  name: countryName
  type: string
- container: ''
  name: openingDate
  type: date
- container: ''
  name: branchId
  type: string
- container: ''
  name: accountOfficerId
  type: integer
- container: ''
  name: sectorId
  type: integer
- container: ''
  name: industryId
  type: integer
- container: ''
  name: language
  type: integer
- container: ''
  name: customerStatus
  type: integer
- container: ''
  name: customerCompany
  type: string
- container: ''
  name: amlCheck
  type: string
- container: ''
  name: amlResult
  type: string
- container: ''
  name: kycStatus
  type: string
- container: ''
  name: executionDate
  type: date
- container: ''
  name: totalCharges
  type: decimal
- container: ''
  name: rejectionReason
  type: string
- container: ''
  name: createdBy
  type: string
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: modifiedBy
  type: string
- container: ''
  name: modifiedAt
  type: dateTime
- container: ''
  name: authorizedBy
  type: string
- container: ''
  name: authorizedAt
  type: dateTime
property_count: 121
provider_name: Temenos Transact
provider_slug: temenos-transact
slug: temenos-transact-context
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"temenos\": \"https://developer.temenos.com/ns/transact/\",\n    \"fibo\": \"https://spec.edmcouncil.org/fibo/ontology/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n\n    \"id\": \"@id\",\n    \"type\": \"@type\",\n\n    \"Account\": \"schema:BankAccount\",\n    \"CurrentAccount\": \"temenos:CurrentAccount\",\n    \"SavingsAccount\": \"temenos:SavingsAccount\",\n    \"CorporateAccount\": \"temenos:CorporateAccount\",\n    \"IslamicAccount\": \"temenos:IslamicAccount\",\n    \"DepositAccount\": \"temenos:DepositAccount\",\n    \"LoanAccount\": \"schema:LoanOrCredit\",\n\n    \"Customer\": \"schema:Person\",\n    \"CorporateCustomer\": \"schema:Organization\",\n    \"Beneficiary\": \"temenos:Beneficiary\",\n\n    \"Transaction\": \"temenos:Transaction\",\n    \"FundTransfer\": \"schema:TransferAction\",\n \
  \   \"PaymentOrder\": \"schema:PayAction\",\n    \"StandingOrder\": \"temenos:StandingOrder\",\n    \"DirectDebit\": \"temenos:DirectDebit\",\n\n    \"Product\": \"schema:FinancialProduct\",\n    \"DepositProduct\": \"temenos:DepositProduct\",\n    \"LoanProduct\": \"temenos:LoanProduct\",\n    \"CardProduct\": \"temenos:CardProduct\",\n\n    \"Card\": \"temenos:BankCard\",\n    \"DebitCard\": \"temenos:DebitCard\",\n    \"CreditCard\": \"temenos:CreditCard\",\n\n    \"Currency\": \"temenos:Currency\",\n    \"Country\": \"schema:Country\",\n    \"Address\": \"schema:PostalAddress\",\n\n    \"accountId\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accountName\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accountType\": {\n      \"@id\": \"temenos:accountType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"customerId\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"customerName\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"customerMnemonic\": {\n      \"@id\": \"temenos:customerMnemonic\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shortName\": {\n      \"@id\": \"schema:alternateName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"displayNames\": {\n      \"@id\": \"schema:name\",\n      \"@container\": \"@list\"\n    },\n    \"customerNames\": {\n      \"@id\": \"schema:name\",\n      \"@container\": \"@list\"\n    },\n\n    \"title\": {\n      \"@id\": \"schema:honorificPrefix\",\n      \"@type\": \"xsd:string\"\n    },\n    \"gender\": {\n      \"@id\": \"schema:gender\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dateOfBirth\": {\n      \"@id\": \"schema:birthDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"nationalityId\": {\n      \"@id\": \"schema:nationality\",\n      \"@type\": \"xsd:string\"\n    },\n    \"residenceId\": {\n      \"@id\": \"temenos:residenceId\",\n      \"\
  @type\": \"xsd:string\"\n    },\n\n    \"communicationDevices\": {\n      \"@id\": \"schema:contactPoint\",\n      \"@container\": \"@list\"\n    },\n    \"deviceType\": {\n      \"@id\": \"schema:contactType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deviceValue\": {\n      \"@id\": \"schema:value\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"addresses\": {\n      \"@id\": \"schema:address\",\n      \"@container\": \"@list\"\n    },\n    \"addressType\": {\n      \"@id\": \"temenos:addressType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"addressLine1\": {\n      \"@id\": \"schema:streetAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"addressLine2\": {\n      \"@id\": \"temenos:addressLine2\",\n      \"@type\": \"xsd:string\"\n    },\n    \"city\": {\n      \"@id\": \"schema:addressLocality\",\n      \"@type\": \"xsd:string\"\n    },\n    \"state\": {\n      \"@id\": \"schema:addressRegion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"postCode\": {\n\
  \      \"@id\": \"schema:postalCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"country\": {\n      \"@id\": \"schema:addressCountry\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"transactionId\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"transactionType\": {\n      \"@id\": \"temenos:transactionType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"debitOrCredit\": {\n      \"@id\": \"temenos:debitOrCredit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"amount\": {\n      \"@id\": \"schema:amount\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"currency\": {\n      \"@id\": \"schema:currency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bookingDate\": {\n      \"@id\": \"temenos:bookingDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"valueDate\": {\n      \"@id\": \"temenos:valueDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"processingDate\": {\n      \"@id\": \"temenos:processingDate\",\n      \"@type\"\
  : \"xsd:date\"\n    },\n    \"reference\": {\n      \"@id\": \"temenos:reference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"endToEndReference\": {\n      \"@id\": \"temenos:endToEndReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"narrative\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"counterparty\": \"temenos:counterparty\",\n    \"counterpartyName\": {\n      \"@id\": \"temenos:counterpartyName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"counterpartyAccountId\": {\n      \"@id\": \"temenos:counterpartyAccountId\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"balance\": {\n      \"@id\": \"temenos:balance\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"workingBalance\": {\n      \"@id\": \"temenos:workingBalance\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"availableBalance\": {\n      \"@id\": \"temenos:availableBalance\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"clearedBalance\": {\n \
  \     \"@id\": \"temenos:clearedBalance\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"lockedAmount\": {\n      \"@id\": \"temenos:lockedAmount\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"overdraftLimit\": {\n      \"@id\": \"temenos:overdraftLimit\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"accruedInterest\": {\n      \"@id\": \"temenos:accruedInterest\",\n      \"@type\": \"xsd:decimal\"\n    },\n\n    \"exchangeRate\": {\n      \"@id\": \"schema:exchangeRate\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"chargesAmount\": {\n      \"@id\": \"temenos:chargesAmount\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"reversalIndicator\": {\n      \"@id\": \"temenos:reversalIndicator\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"statementNumber\": {\n      \"@id\": \"temenos:statementNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"transactionStatus\": {\n      \"@id\": \"temenos:transactionStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"\
  channel\": {\n      \"@id\": \"temenos:channel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"paymentMethod\": {\n      \"@id\": \"schema:paymentMethod\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"debitAccountId\": {\n      \"@id\": \"temenos:debitAccountId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"creditAccountId\": {\n      \"@id\": \"temenos:creditAccountId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"debitAmount\": {\n      \"@id\": \"temenos:debitAmount\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"creditAmount\": {\n      \"@id\": \"temenos:creditAmount\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"debitCurrency\": {\n      \"@id\": \"temenos:debitCurrency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"creditCurrency\": {\n      \"@id\": \"temenos:creditCurrency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"transferType\": {\n      \"@id\": \"temenos:transferType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"paymentType\": {\n\
  \      \"@id\": \"temenos:paymentType\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"beneficiaryId\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"beneficiaryName\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"beneficiaryIban\": {\n      \"@id\": \"temenos:beneficiaryIban\",\n      \"@type\": \"xsd:string\"\n    },\n    \"beneficiaryBic\": {\n      \"@id\": \"temenos:beneficiaryBic\",\n      \"@type\": \"xsd:string\"\n    },\n    \"beneficiaryType\": {\n      \"@id\": \"temenos:beneficiaryType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"remittanceInformation\": {\n      \"@id\": \"temenos:remittanceInformation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"chargesType\": {\n      \"@id\": \"temenos:chargesType\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"iban\": {\n      \"@id\": \"temenos:iban\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bic\": {\n      \"@id\": \"temenos:bic\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"bankName\": {\n      \"@id\": \"temenos:bankName\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"frequency\": {\n      \"@id\": \"temenos:frequency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startDate\": {\n      \"@id\": \"schema:startDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"endDate\": {\n      \"@id\": \"schema:endDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"nextPaymentDate\": {\n      \"@id\": \"temenos:nextPaymentDate\",\n      \"@type\": \"xsd:date\"\n    },\n\n    \"productId\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"productName\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"productGroup\": {\n      \"@id\": \"temenos:productGroup\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\",\n\n    \"principalAmount\": {\n      \"@id\": \"temenos:principalAmount\",\n      \"@type\"\
  : \"xsd:decimal\"\n    },\n    \"outstandingBalance\": {\n      \"@id\": \"temenos:outstandingBalance\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"interestRate\": {\n      \"@id\": \"temenos:interestRate\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"effectiveRate\": {\n      \"@id\": \"temenos:effectiveRate\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"maturityDate\": {\n      \"@id\": \"temenos:maturityDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"disbursementDate\": {\n      \"@id\": \"temenos:disbursementDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"term\": {\n      \"@id\": \"temenos:term\",\n      \"@type\": \"xsd:string\"\n    },\n    \"renewalType\": {\n      \"@id\": \"temenos:renewalType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"repaymentFrequency\": {\n      \"@id\": \"temenos:repaymentFrequency\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"cardId\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"xsd:string\"\n\
  \    },\n    \"cardNumber\": {\n      \"@id\": \"temenos:cardNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cardType\": {\n      \"@id\": \"temenos:cardType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cardholderName\": {\n      \"@id\": \"temenos:cardholderName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"expiryDate\": {\n      \"@id\": \"temenos:expiryDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dailyLimit\": {\n      \"@id\": \"temenos:dailyLimit\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"availableLimit\": {\n      \"@id\": \"temenos:availableLimit\",\n      \"@type\": \"xsd:decimal\"\n    },\n\n    \"currencyCode\": {\n      \"@id\": \"temenos:currencyCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"currencyName\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"decimalPlaces\": {\n      \"@id\": \"temenos:decimalPlaces\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"buyRate\": {\n      \"@id\"\
  : \"temenos:buyRate\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"sellRate\": {\n      \"@id\": \"temenos:sellRate\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"midRate\": {\n      \"@id\": \"temenos:midRate\",\n      \"@type\": \"xsd:decimal\"\n    },\n\n    \"countryCode\": {\n      \"@id\": \"temenos:countryCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"countryName\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"openingDate\": {\n      \"@id\": \"temenos:openingDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"branchId\": {\n      \"@id\": \"temenos:branchId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accountOfficerId\": {\n      \"@id\": \"temenos:accountOfficerId\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"sectorId\": {\n      \"@id\": \"temenos:sectorId\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"industryId\": {\n      \"@id\": \"temenos:industryId\",\n      \"@type\": \"xsd:integer\"\n    },\n\
  \    \"language\": {\n      \"@id\": \"schema:inLanguage\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"customerStatus\": {\n      \"@id\": \"temenos:customerStatus\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"customerCompany\": {\n      \"@id\": \"temenos:customerCompany\",\n      \"@type\": \"xsd:string\"\n    },\n    \"amlCheck\": {\n      \"@id\": \"temenos:amlCheck\",\n      \"@type\": \"xsd:string\"\n    },\n    \"amlResult\": {\n      \"@id\": \"temenos:amlResult\",\n      \"@type\": \"xsd:string\"\n    },\n    \"kycStatus\": {\n      \"@id\": \"temenos:kycStatus\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"status\": \"temenos:status\",\n    \"executionDate\": {\n      \"@id\": \"temenos:executionDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"totalCharges\": {\n      \"@id\": \"temenos:totalCharges\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"rejectionReason\": {\n      \"@id\": \"temenos:rejectionReason\",\n      \"@type\": \"xsd:string\"\n   \
  \ },\n\n    \"audit\": \"temenos:audit\",\n    \"createdBy\": {\n      \"@id\": \"dcterms:creator\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdAt\": {\n      \"@id\": \"dcterms:created\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"modifiedBy\": {\n      \"@id\": \"temenos:modifiedBy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"modifiedAt\": {\n      \"@id\": \"dcterms:modified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"authorizedBy\": {\n      \"@id\": \"temenos:authorizedBy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"authorizedAt\": {\n      \"@id\": \"temenos:authorizedAt\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/temenos-transact/refs/heads/main/json-ld/temenos-transact-context.jsonld
tags:
- Banking
- Core Banking
- Digital Banking
- Enterprise
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
