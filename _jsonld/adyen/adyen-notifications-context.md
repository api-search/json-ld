---
class_count: 86
classes:
- AccountCloseNotification
- AccountCreateNotification
- AccountEvent
- AccountFundsBelowThresholdNotificationContent
- AccountFundsBelowThresholdNotification
- AccountHolderCreateNotification
- AccountHolderDetails
- AccountHolderPayoutNotificationContent
- AccountHolderPayoutNotification
- AccountHolderStatusChangeNotificationContent
- AccountHolderStatusChangeNotification
- AccountHolderStatus
- AccountHolderStoreStatusChangeNotificationContent
- AccountHolderStoreStatusChangeNotification
- AccountHolderUpcomingDeadlineNotificationContent
- AccountHolderUpcomingDeadlineNotification
- AccountHolderUpdateNotification
- AccountHolderVerificationNotificationContent
- AccountHolderVerificationNotification
- AccountPayoutState
- AccountProcessingState
- AccountUpdateNotification
- Amount
- BankAccountDetail
- BeneficiarySetupNotificationContent
- BeneficiarySetupNotification
- BusinessDetails
- CloseAccountResponse
- CompensateNegativeBalanceNotificationContent
- CompensateNegativeBalanceNotificationRecord
- CompensateNegativeBalanceNotification
- CreateAccountHolderResponse
- CreateAccountResponse
- DirectDebitInitiatedNotificationContent
- DirectDebitInitiatedNotification
- ErrorFieldType
- FieldType
- IndividualDetails
- KYCCheckResult
- KYCCheckStatusData
- KYCCheckSummary
- KYCLegalArrangementCheckResult
- KYCLegalArrangementEntityCheckResult
- KYCPayoutMethodCheckResult
- KYCShareholderCheckResult
- KYCSignatoryCheckResult
- KYCUltimateParentCompanyCheckResult
- KYCVerificationResult
- LegalArrangementDetail
- LegalArrangementEntityDetail
- LocalDate
- Message
- NotificationErrorContainer
- NotificationResponse
- OperationStatus
- PaymentFailureNotificationContent
- PaymentFailureNotification
- PayoutMethod
- PayoutScheduleResponse
- PersonalDocumentData
- RefundFundsTransferNotificationContent
- RefundFundsTransferNotification
- RefundResult
- ReportAvailableNotificationContent
- ReportAvailableNotification
- ScheduledRefundsNotificationContent
- ScheduledRefundsNotification
- ShareholderContact
- SignatoryContact
- SplitAmount
- Split
- StoreDetail
- Transaction
- TransferFundsNotificationContent
- TransferFundsNotification
- UltimateParentCompanyBusinessDetails
- UltimateParentCompany
- UpdateAccountHolderResponse
- UpdateAccountResponse
- ViasAddress
- ViasName
- ViasPersonalData
- ViasPhoneNumber
- email
- description
- name
context_file: json-ld/adyen-notifications-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-notifications-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Notifications from Adyen.
layout: jsonld
name: Adyen Notifications Context
namespaces:
- prefix: adyen
  uri: https://docs.adyen.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: content
  type: string
- container: ''
  name: error
  type: string
- container: ''
  name: eventDate
  type: dateTime
- container: ''
  name: eventType
  type: string
- container: ''
  name: executingUserKey
  type: string
- container: ''
  name: live
  type: boolean
- container: ''
  name: pspReference
  type: string
- container: ''
  name: event
  type: string
- container: ''
  name: executionDate
  type: dateTime
- container: ''
  name: reason
  type: string
- container: ''
  name: accountCode
  type: string
- container: ''
  name: balanceDate
  type: string
- container: ''
  name: currentFunds
  type: string
- container: ''
  name: fundThreshold
  type: string
- container: ''
  name: merchantAccountCode
  type: string
- container: ''
  name: address
  type: string
- container: set
  name: bankAccountDetails
  type: string
- container: ''
  name: bankAggregatorDataReference
  type: string
- container: ''
  name: businessDetails
  type: string
- container: ''
  name: fullPhoneNumber
  type: string
- container: ''
  name: individualDetails
  type: string
- container: ''
  name: lastReviewDate
  type: string
- container: set
  name: legalArrangements
  type: string
- container: ''
  name: merchantCategoryCode
  type: string
- container: ''
  name: metadata
  type: reference
- container: set
  name: payoutMethods
  type: string
- container: ''
  name: principalBusinessAddress
  type: string
- container: set
  name: storeDetails
  type: string
- container: ''
  name: webAddress
  type: string
- container: ''
  name: accountHolderCode
  type: string
- container: set
  name: amounts
  type: string
- container: ''
  name: bankAccountDetail
  type: string
- container: ''
  name: estimatedArrivalDate
  type: string
- container: set
  name: invalidFields
  type: string
- container: ''
  name: merchantReference
  type: string
- container: ''
  name: originalPspReference
  type: string
- container: ''
  name: payoutAccountCountry
  type: string
- container: ''
  name: payoutAccountNumber
  type: string
- container: ''
  name: payoutBalanceAccountId
  type: string
- container: ''
  name: payoutBankName
  type: string
- container: ''
  name: payoutBranchCode
  type: string
- container: ''
  name: payoutReference
  type: integer
- container: ''
  name: payoutSpeed
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: newStatus
  type: string
- container: ''
  name: oldStatus
  type: string
- container: set
  name: events
  type: string
- container: ''
  name: payoutState
  type: string
- container: ''
  name: processingState
  type: string
- container: ''
  name: statusReason
  type: string
- container: ''
  name: store
  type: string
- container: ''
  name: storeReference
  type: string
- container: ''
  name: kycCheckStatusData
  type: string
- container: ''
  name: legalArrangementCode
  type: string
- container: ''
  name: legalArrangementEntityCode
  type: string
- container: ''
  name: payoutMethodCode
  type: string
- container: ''
  name: shareholderCode
  type: string
- container: ''
  name: signatoryCode
  type: string
- container: ''
  name: allowPayout
  type: boolean
- container: ''
  name: disableReason
  type: string
- container: ''
  name: disabled
  type: boolean
- container: ''
  name: notAllowedReason
  type: string
- container: ''
  name: payoutLimit
  type: string
- container: ''
  name: tierNumber
  type: integer
- container: ''
  name: processedFrom
  type: string
- container: ''
  name: processedTo
  type: string
- container: ''
  name: currency
  type: string
- container: ''
  name: value
  type: integer
- container: ''
  name: accountNumber
  type: string
- container: ''
  name: accountType
  type: string
- container: ''
  name: bankAccountName
  type: string
- container: ''
  name: bankAccountReference
  type: string
- container: ''
  name: bankAccountUUID
  type: string
- container: ''
  name: bankBicSwift
  type: string
- container: ''
  name: bankCity
  type: string
- container: ''
  name: bankCode
  type: string
- container: ''
  name: bankName
  type: string
- container: ''
  name: branchCode
  type: string
- container: ''
  name: checkCode
  type: string
- container: ''
  name: countryCode
  type: string
- container: ''
  name: currencyCode
  type: string
- container: ''
  name: iban
  type: string
- container: ''
  name: ownerCity
  type: string
- container: ''
  name: ownerCountryCode
  type: string
- container: ''
  name: ownerDateOfBirth
  type: string
- container: ''
  name: ownerHouseNumberOrName
  type: string
- container: ''
  name: ownerName
  type: string
- container: ''
  name: ownerNationality
  type: string
- container: ''
  name: ownerPostalCode
  type: string
- container: ''
  name: ownerState
  type: string
- container: ''
  name: ownerStreet
  type: string
- container: ''
  name: primaryAccount
  type: boolean
- container: ''
  name: taxId
  type: string
- container: ''
  name: urlForVerification
  type: string
- container: ''
  name: destinationAccountCode
  type: string
- container: ''
  name: destinationAccountHolderCode
  type: string
- container: ''
  name: sourceAccountCode
  type: string
- container: ''
  name: sourceAccountHolderCode
  type: string
- container: ''
  name: transferDate
  type: dateTime
- container: ''
  name: doingBusinessAs
  type: string
- container: ''
  name: legalBusinessName
  type: string
- container: set
  name: listedUltimateParentCompany
  type: string
- container: ''
  name: registrationNumber
  type: string
- container: set
  name: shareholders
  type: string
- container: set
  name: signatories
  type: string
- container: ''
  name: stockExchange
  type: string
- container: ''
  name: stockNumber
  type: string
- container: ''
  name: stockTicker
  type: string
- container: ''
  name: resultCode
  type: string
- container: set
  name: records
  type: string
- container: ''
  name: amount
  type: string
- container: ''
  name: accountHolderDetails
  type: string
- container: ''
  name: accountHolderStatus
  type: string
- container: ''
  name: legalEntity
  type: string
- container: ''
  name: primaryCurrency
  type: string
- container: ''
  name: verification
  type: string
- container: ''
  name: verificationProfile
  type: string
- container: ''
  name: payoutSchedule
  type: string
- container: ''
  name: debitInitiationDate
  type: string
- container: set
  name: splits
  type: string
- container: ''
  name: errorCode
  type: integer
- container: ''
  name: errorDescription
  type: string
- container: ''
  name: fieldType
  type: string
- container: ''
  name: field
  type: string
- container: ''
  name: fieldName
  type: string
- container: ''
  name: personalData
  type: string
- container: set
  name: checks
  type: string
- container: set
  name: requiredFields
  type: string
- container: ''
  name: summary
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: kycCheckCode
  type: integer
- container: ''
  name: kycCheckDescription
  type: string
- container: ''
  name: ultimateParentCompanyCode
  type: string
- container: ''
  name: accountHolder
  type: string
- container: set
  name: legalArrangementsEntities
  type: string
- container: set
  name: ultimateParentCompany
  type: string
- container: set
  name: legalArrangementEntities
  type: string
- container: ''
  name: legalArrangementReference
  type: string
- container: ''
  name: legalForm
  type: string
- container: ''
  name: taxNumber
  type: string
- container: ''
  name: legalArrangementEntityReference
  type: string
- container: set
  name: legalArrangementMembers
  type: string
- container: ''
  name: legalEntityType
  type: string
- container: ''
  name: phoneNumber
  type: string
- container: ''
  name: month
  type: integer
- container: ''
  name: year
  type: integer
- container: ''
  name: code
  type: string
- container: ''
  name: text
  type: string
- container: ''
  name: message
  type: string
- container: ''
  name: notificationResponse
  type: string
- container: ''
  name: statusCode
  type: string
- container: set
  name: errorFields
  type: string
- container: ''
  name: errorMessage
  type: string
- container: ''
  name: modificationMerchantReference
  type: string
- container: ''
  name: modificationPspReference
  type: string
- container: ''
  name: paymentMerchantReference
  type: string
- container: ''
  name: paymentPspReference
  type: string
- container: ''
  name: merchantAccount
  type: string
- container: ''
  name: payoutMethodReference
  type: string
- container: ''
  name: recurringDetailReference
  type: string
- container: ''
  name: shopperReference
  type: string
- container: ''
  name: nextScheduledPayout
  type: dateTime
- container: ''
  name: schedule
  type: string
- container: ''
  name: expirationDate
  type: string
- container: ''
  name: issuerCountry
  type: string
- container: ''
  name: issuerState
  type: string
- container: ''
  name: number
  type: string
- container: ''
  name: originalReference
  type: string
- container: ''
  name: originalTransaction
  type: string
- container: ''
  name: response
  type: string
- container: ''
  name: remoteAccessUrl
  type: string
- container: ''
  name: success
  type: boolean
- container: ''
  name: lastPayout
  type: string
- container: set
  name: refundResults
  type: string
- container: ''
  name: jobTitle
  type: string
- container: ''
  name: shareholderReference
  type: string
- container: ''
  name: shareholderType
  type: string
- container: ''
  name: signatoryReference
  type: string
- container: ''
  name: account
  type: string
- container: ''
  name: reference
  type: string
- container: ''
  name: logo
  type: string
- container: ''
  name: merchantHouseNumber
  type: string
- container: ''
  name: shopperInteraction
  type: string
- container: ''
  name: splitConfigurationUUID
  type: string
- container: ''
  name: storeName
  type: string
- container: ''
  name: virtualAccount
  type: string
- container: ''
  name: captureMerchantReference
  type: string
- container: ''
  name: capturePspReference
  type: string
- container: ''
  name: creationDate
  type: dateTime
- container: ''
  name: disputePspReference
  type: string
- container: ''
  name: disputeReasonCode
  type: string
- container: ''
  name: payoutPspReference
  type: string
- container: ''
  name: transactionStatus
  type: string
- container: ''
  name: transferCode
  type: string
- container: ''
  name: city
  type: string
- container: ''
  name: country
  type: string
- container: ''
  name: houseNumberOrName
  type: string
- container: ''
  name: postalCode
  type: string
- container: ''
  name: stateOrProvince
  type: string
- container: ''
  name: street
  type: string
- container: ''
  name: firstName
  type: string
- container: ''
  name: gender
  type: string
- container: ''
  name: infix
  type: string
- container: ''
  name: lastName
  type: string
- container: ''
  name: dateOfBirth
  type: string
- container: set
  name: documentData
  type: string
- container: ''
  name: nationality
  type: string
- container: ''
  name: phoneCountryCode
  type: string
- container: ''
  name: phoneType
  type: string
property_count: 209
provider_name: Adyen
provider_slug: adyen
slug: adyen-notifications-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AccountCloseNotification\": \"adyen:AccountCloseNotification\",\n    \"AccountCreateNotification\": \"adyen:AccountCreateNotification\",\n    \"AccountEvent\": \"adyen:AccountEvent\",\n    \"AccountFundsBelowThresholdNotificationContent\": \"adyen:AccountFundsBelowThresholdNotificationContent\",\n    \"AccountFundsBelowThresholdNotification\": \"adyen:AccountFundsBelowThresholdNotification\",\n    \"AccountHolderCreateNotification\": \"adyen:AccountHolderCreateNotification\",\n    \"AccountHolderDetails\": \"adyen:AccountHolderDetails\",\n    \"AccountHolderPayoutNotificationContent\": \"adyen:AccountHolderPayoutNotificationContent\",\n    \"AccountHolderPayoutNotification\": \"adyen:AccountHolderPayoutNotification\",\n    \"AccountHolderStatusChangeNotificationContent\"\
  : \"adyen:AccountHolderStatusChangeNotificationContent\",\n    \"AccountHolderStatusChangeNotification\": \"adyen:AccountHolderStatusChangeNotification\",\n    \"AccountHolderStatus\": \"adyen:AccountHolderStatus\",\n    \"AccountHolderStoreStatusChangeNotificationContent\": \"adyen:AccountHolderStoreStatusChangeNotificationContent\",\n    \"AccountHolderStoreStatusChangeNotification\": \"adyen:AccountHolderStoreStatusChangeNotification\",\n    \"AccountHolderUpcomingDeadlineNotificationContent\": \"adyen:AccountHolderUpcomingDeadlineNotificationContent\",\n    \"AccountHolderUpcomingDeadlineNotification\": \"adyen:AccountHolderUpcomingDeadlineNotification\",\n    \"AccountHolderUpdateNotification\": \"adyen:AccountHolderUpdateNotification\",\n    \"AccountHolderVerificationNotificationContent\": \"adyen:AccountHolderVerificationNotificationContent\",\n    \"AccountHolderVerificationNotification\": \"adyen:AccountHolderVerificationNotification\",\n    \"AccountPayoutState\": \"adyen:AccountPayoutState\"\
  ,\n    \"AccountProcessingState\": \"adyen:AccountProcessingState\",\n    \"AccountUpdateNotification\": \"adyen:AccountUpdateNotification\",\n    \"Amount\": \"adyen:Amount\",\n    \"BankAccountDetail\": \"adyen:BankAccountDetail\",\n    \"BeneficiarySetupNotificationContent\": \"adyen:BeneficiarySetupNotificationContent\",\n    \"BeneficiarySetupNotification\": \"adyen:BeneficiarySetupNotification\",\n    \"BusinessDetails\": \"adyen:BusinessDetails\",\n    \"CloseAccountResponse\": \"adyen:CloseAccountResponse\",\n    \"CompensateNegativeBalanceNotificationContent\": \"adyen:CompensateNegativeBalanceNotificationContent\",\n    \"CompensateNegativeBalanceNotificationRecord\": \"adyen:CompensateNegativeBalanceNotificationRecord\",\n    \"CompensateNegativeBalanceNotification\": \"adyen:CompensateNegativeBalanceNotification\",\n    \"CreateAccountHolderResponse\": \"adyen:CreateAccountHolderResponse\",\n    \"CreateAccountResponse\": \"adyen:CreateAccountResponse\",\n    \"DirectDebitInitiatedNotificationContent\"\
  : \"adyen:DirectDebitInitiatedNotificationContent\",\n    \"DirectDebitInitiatedNotification\": \"adyen:DirectDebitInitiatedNotification\",\n    \"ErrorFieldType\": \"adyen:ErrorFieldType\",\n    \"FieldType\": \"adyen:FieldType\",\n    \"IndividualDetails\": \"adyen:IndividualDetails\",\n    \"KYCCheckResult\": \"adyen:KYCCheckResult\",\n    \"KYCCheckStatusData\": \"adyen:KYCCheckStatusData\",\n    \"KYCCheckSummary\": \"adyen:KYCCheckSummary\",\n    \"KYCLegalArrangementCheckResult\": \"adyen:KYCLegalArrangementCheckResult\",\n    \"KYCLegalArrangementEntityCheckResult\": \"adyen:KYCLegalArrangementEntityCheckResult\",\n    \"KYCPayoutMethodCheckResult\": \"adyen:KYCPayoutMethodCheckResult\",\n    \"KYCShareholderCheckResult\": \"adyen:KYCShareholderCheckResult\",\n    \"KYCSignatoryCheckResult\": \"adyen:KYCSignatoryCheckResult\",\n    \"KYCUltimateParentCompanyCheckResult\": \"adyen:KYCUltimateParentCompanyCheckResult\",\n    \"KYCVerificationResult\": \"adyen:KYCVerificationResult\"\
  ,\n    \"LegalArrangementDetail\": \"adyen:LegalArrangementDetail\",\n    \"LegalArrangementEntityDetail\": \"adyen:LegalArrangementEntityDetail\",\n    \"LocalDate\": \"adyen:LocalDate\",\n    \"Message\": \"adyen:Message\",\n    \"NotificationErrorContainer\": \"adyen:NotificationErrorContainer\",\n    \"NotificationResponse\": \"adyen:NotificationResponse\",\n    \"OperationStatus\": \"adyen:OperationStatus\",\n    \"PaymentFailureNotificationContent\": \"adyen:PaymentFailureNotificationContent\",\n    \"PaymentFailureNotification\": \"adyen:PaymentFailureNotification\",\n    \"PayoutMethod\": \"adyen:PayoutMethod\",\n    \"PayoutScheduleResponse\": \"adyen:PayoutScheduleResponse\",\n    \"PersonalDocumentData\": \"adyen:PersonalDocumentData\",\n    \"RefundFundsTransferNotificationContent\": \"adyen:RefundFundsTransferNotificationContent\",\n    \"RefundFundsTransferNotification\": \"adyen:RefundFundsTransferNotification\",\n    \"RefundResult\": \"adyen:RefundResult\",\n    \"ReportAvailableNotificationContent\"\
  : \"adyen:ReportAvailableNotificationContent\",\n    \"ReportAvailableNotification\": \"adyen:ReportAvailableNotification\",\n    \"ScheduledRefundsNotificationContent\": \"adyen:ScheduledRefundsNotificationContent\",\n    \"ScheduledRefundsNotification\": \"adyen:ScheduledRefundsNotification\",\n    \"ShareholderContact\": \"adyen:ShareholderContact\",\n    \"SignatoryContact\": \"adyen:SignatoryContact\",\n    \"SplitAmount\": \"adyen:SplitAmount\",\n    \"Split\": \"adyen:Split\",\n    \"StoreDetail\": \"adyen:StoreDetail\",\n    \"Transaction\": \"adyen:Transaction\",\n    \"TransferFundsNotificationContent\": \"adyen:TransferFundsNotificationContent\",\n    \"TransferFundsNotification\": \"adyen:TransferFundsNotification\",\n    \"UltimateParentCompanyBusinessDetails\": \"adyen:UltimateParentCompanyBusinessDetails\",\n    \"UltimateParentCompany\": \"adyen:UltimateParentCompany\",\n    \"UpdateAccountHolderResponse\": \"adyen:UpdateAccountHolderResponse\",\n    \"UpdateAccountResponse\"\
  : \"adyen:UpdateAccountResponse\",\n    \"ViasAddress\": \"adyen:ViasAddress\",\n    \"ViasName\": \"adyen:ViasName\",\n    \"ViasPersonalData\": \"adyen:ViasPersonalData\",\n    \"ViasPhoneNumber\": \"adyen:ViasPhoneNumber\",\n    \"content\": {\n      \"@id\": \"adyen:content\",\n      \"@type\": \"xsd:string\"\n    },\n    \"error\": {\n      \"@id\": \"adyen:error\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eventDate\": {\n      \"@id\": \"adyen:eventDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"eventType\": {\n      \"@id\": \"adyen:eventType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"executingUserKey\": {\n      \"@id\": \"adyen:executingUserKey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"live\": {\n      \"@id\": \"adyen:live\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"pspReference\": {\n      \"@id\": \"adyen:pspReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"event\": {\n      \"@id\": \"adyen:event\",\n      \"@type\": \"\
  xsd:string\"\n    },\n    \"executionDate\": {\n      \"@id\": \"adyen:executionDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"reason\": {\n      \"@id\": \"adyen:reason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accountCode\": {\n      \"@id\": \"adyen:accountCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"balanceDate\": {\n      \"@id\": \"adyen:balanceDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"currentFunds\": {\n      \"@id\": \"adyen:currentFunds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fundThreshold\": {\n      \"@id\": \"adyen:fundThreshold\",\n      \"@type\": \"xsd:string\"\n    },\n    \"merchantAccountCode\": {\n      \"@id\": \"adyen:merchantAccountCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"address\": {\n      \"@id\": \"adyen:address\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bankAccountDetails\": {\n      \"@id\": \"adyen:bankAccountDetails\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"bankAggregatorDataReference\": {\n      \"@id\": \"adyen:bankAggregatorDataReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"businessDetails\": {\n      \"@id\": \"adyen:businessDetails\",\n      \"@type\": \"xsd:string\"\n    },\n    \"email\": \"schema:email\",\n    \"fullPhoneNumber\": {\n      \"@id\": \"adyen:fullPhoneNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"individualDetails\": {\n      \"@id\": \"adyen:individualDetails\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastReviewDate\": {\n      \"@id\": \"adyen:lastReviewDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"legalArrangements\": {\n      \"@id\": \"adyen:legalArrangements\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"merchantCategoryCode\": {\n      \"@id\": \"adyen:merchantCategoryCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"metadata\": {\n      \"@id\": \"adyen:metadata\",\n      \"@type\": \"@id\"\n    },\n    \"payoutMethods\"\
  : {\n      \"@id\": \"adyen:payoutMethods\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"principalBusinessAddress\": {\n      \"@id\": \"adyen:principalBusinessAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"storeDetails\": {\n      \"@id\": \"adyen:storeDetails\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"webAddress\": {\n      \"@id\": \"adyen:webAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accountHolderCode\": {\n      \"@id\": \"adyen:accountHolderCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"amounts\": {\n      \"@id\": \"adyen:amounts\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bankAccountDetail\": {\n      \"@id\": \"adyen:bankAccountDetail\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\",\n    \"estimatedArrivalDate\": {\n      \"@id\": \"adyen:estimatedArrivalDate\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"invalidFields\": {\n      \"@id\": \"adyen:invalidFields\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"merchantReference\": {\n      \"@id\": \"adyen:merchantReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"originalPspReference\": {\n      \"@id\": \"adyen:originalPspReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"payoutAccountCountry\": {\n      \"@id\": \"adyen:payoutAccountCountry\",\n      \"@type\": \"xsd:string\"\n    },\n    \"payoutAccountNumber\": {\n      \"@id\": \"adyen:payoutAccountNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"payoutBalanceAccountId\": {\n      \"@id\": \"adyen:payoutBalanceAccountId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"payoutBankName\": {\n      \"@id\": \"adyen:payoutBankName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"payoutBranchCode\": {\n      \"@id\": \"adyen:payoutBranchCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"payoutReference\"\
  : {\n      \"@id\": \"adyen:payoutReference\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"payoutSpeed\": {\n      \"@id\": \"adyen:payoutSpeed\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"adyen:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"newStatus\": {\n      \"@id\": \"adyen:newStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"oldStatus\": {\n      \"@id\": \"adyen:oldStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"events\": {\n      \"@id\": \"adyen:events\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"payoutState\": {\n      \"@id\": \"adyen:payoutState\",\n      \"@type\": \"xsd:string\"\n    },\n    \"processingState\": {\n      \"@id\": \"adyen:processingState\",\n      \"@type\": \"xsd:string\"\n    },\n    \"statusReason\": {\n      \"@id\": \"adyen:statusReason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"store\": {\n      \"@id\": \"adyen:store\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"storeReference\": {\n      \"@id\": \"adyen:storeReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"kycCheckStatusData\": {\n      \"@id\": \"adyen:kycCheckStatusData\",\n      \"@type\": \"xsd:string\"\n    },\n    \"legalArrangementCode\": {\n      \"@id\": \"adyen:legalArrangementCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"legalArrangementEntityCode\": {\n      \"@id\": \"adyen:legalArrangementEntityCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"payoutMethodCode\": {\n      \"@id\": \"adyen:payoutMethodCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shareholderCode\": {\n      \"@id\": \"adyen:shareholderCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"signatoryCode\": {\n      \"@id\": \"adyen:signatoryCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"allowPayout\": {\n      \"@id\": \"adyen:allowPayout\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"disableReason\": {\n      \"@id\": \"adyen:disableReason\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"disabled\": {\n      \"@id\": \"adyen:disabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"notAllowedReason\": {\n      \"@id\": \"adyen:notAllowedReason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"payoutLimit\": {\n      \"@id\": \"adyen:payoutLimit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tierNumber\": {\n      \"@id\": \"adyen:tierNumber\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"processedFrom\": {\n      \"@id\": \"adyen:processedFrom\",\n      \"@type\": \"xsd:string\"\n    },\n    \"processedTo\": {\n      \"@id\": \"adyen:processedTo\",\n      \"@type\": \"xsd:string\"\n    },\n    \"currency\": {\n      \"@id\": \"adyen:currency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"adyen:value\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"accountNumber\": {\n      \"@id\": \"adyen:accountNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accountType\": {\n\
  \      \"@id\": \"adyen:accountType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bankAccountName\": {\n      \"@id\": \"adyen:bankAccountName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bankAccountReference\": {\n      \"@id\": \"adyen:bankAccountReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bankAccountUUID\": {\n      \"@id\": \"adyen:bankAccountUUID\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bankBicSwift\": {\n      \"@id\": \"adyen:bankBicSwift\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bankCity\": {\n      \"@id\": \"adyen:bankCity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bankCode\": {\n      \"@id\": \"adyen:bankCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bankName\": {\n      \"@id\": \"adyen:bankName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"branchCode\": {\n      \"@id\": \"adyen:branchCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"checkCode\": {\n      \"@id\": \"adyen:checkCode\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"countryCode\": {\n      \"@id\": \"adyen:countryCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"currencyCode\": {\n      \"@id\": \"adyen:currencyCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"iban\": {\n      \"@id\": \"adyen:iban\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ownerCity\": {\n      \"@id\": \"adyen:ownerCity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ownerCountryCode\": {\n      \"@id\": \"adyen:ownerCountryCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ownerDateOfBirth\": {\n      \"@id\": \"adyen:ownerDateOfBirth\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ownerHouseNumberOrName\": {\n      \"@id\": \"adyen:ownerHouseNumberOrName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ownerName\": {\n      \"@id\": \"adyen:ownerName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ownerNationality\": {\n      \"@id\": \"adyen:ownerNationality\",\n      \"@type\": \"xsd:string\"\n    },\n    \"\
  ownerPostalCode\": {\n      \"@id\": \"adyen:ownerPostalCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ownerState\": {\n      \"@id\": \"adyen:ownerState\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ownerStreet\": {\n      \"@id\": \"adyen:ownerStreet\",\n      \"@type\": \"xsd:string\"\n    },\n    \"primaryAccount\": {\n      \"@id\": \"adyen:primaryAccount\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"taxId\": {\n      \"@id\": \"adyen:taxId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"urlForVerification\": {\n      \"@id\": \"adyen:urlForVerification\",\n      \"@type\": \"xsd:string\"\n    },\n    \"destinationAccountCode\": {\n      \"@id\": \"adyen:destinationAccountCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"destinationAccountHolderCode\": {\n      \"@id\": \"adyen:destinationAccountHolderCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sourceAccountCode\": {\n      \"@id\": \"adyen:sourceAccountCode\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"sourceAccountHolderCode\": {\n      \"@id\": \"adyen:sourceAccountHolderCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"transferDate\": {\n      \"@id\": \"adyen:transferDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"doingBusinessAs\": {\n      \"@id\": \"adyen:doingBusinessAs\",\n      \"@type\": \"xsd:string\"\n    },\n    \"legalBusinessName\": {\n      \"@id\": \"adyen:legalBusinessName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"listedUltimateParentCompany\": {\n      \"@id\": \"adyen:listedUltimateParentCompany\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"registrationNumber\": {\n      \"@id\": \"adyen:registrationNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shareholders\": {\n      \"@id\": \"adyen:shareholders\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"signatories\": {\n      \"@id\": \"adyen:signatories\",\n      \"@container\": \"@set\",\n   \
  \   \"@type\": \"xsd:string\"\n    },\n    \"stockExchange\": {\n      \"@id\": \"adyen:stockExchange\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stockNumber\": {\n      \"@id\": \"adyen:stockNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stockTicker\": {\n      \"@id\": \"adyen:stockTicker\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resultCode\": {\n      \"@id\": \"adyen:resultCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"records\": {\n      \"@id\": \"adyen:records\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"amount\": {\n      \"@id\": \"adyen:amount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accountHolderDetails\": {\n      \"@id\": \"adyen:accountHolderDetails\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accountHolderStatus\": {\n      \"@id\": \"adyen:accountHolderStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"legalEntity\": {\n      \"@id\": \"adyen:legalEntity\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"primaryCurrency\": {\n      \"@id\": \"adyen:primaryCurrency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"verification\": {\n      \"@id\": \"adyen:verification\",\n      \"@type\": \"xsd:string\"\n    },\n    \"verificationProfile\": {\n      \"@id\": \"adyen:verificationProfile\",\n      \"@type\": \"xsd:string\"\n    },\n    \"payoutSchedule\": {\n      \"@id\": \"adyen:payoutSchedule\",\n      \"@type\": \"xsd:string\"\n    },\n    \"debitInitiationDate\": {\n      \"@id\": \"adyen:debitInitiationDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"splits\": {\n      \"@id\": \"adyen:splits\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"errorCode\": {\n      \"@id\": \"adyen:errorCode\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"errorDescription\": {\n      \"@id\": \"adyen:errorDescription\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fieldType\": {\n      \"@id\": \"adyen:fieldType\",\n    \
  \  \"@type\": \"xsd:string\"\n    },\n    \"field\": {\n      \"@id\": \"adyen:field\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fieldName\": {\n      \"@id\": \"adyen:fieldName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"personalData\": {\n      \"@id\": \"adyen:personalData\",\n      \"@type\": \"xsd:string\"\n    },\n    \"checks\": {\n      \"@id\": \"adyen:checks\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"requiredFields\": {\n      \"@id\": \"adyen:requiredFields\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"summary\": {\n      \"@id\": \"adyen:summary\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"adyen:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"kycCheckCode\": {\n      \"@id\": \"adyen:kycCheckCode\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"kycCheckDescription\": {\n      \"@id\": \"adyen:kycCheckDescription\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"ultimateParentCompanyCode\": {\n      \"@id\": \"adyen:ultimateParentCompanyCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accountHolder\": {\n      \"@id\": \"adyen:accountHolder\",\n      \"@type\": \"xsd:string\"\n    },\n    \"legalArrangementsEntities\": {\n      \"@id\": \"adyen:legalArrangementsEntities\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ultimateParentCompany\": {\n      \"@id\": \"adyen:ultimateParentCompany\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"legalArrangementEntities\": {\n      \"@id\": \"adyen:legalArrangementEntities\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"legalArrangementReference\": {\n      \"@id\": \"adyen:legalArrangementReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"legalForm\": {\n      \"@id\": \"adyen:legalForm\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"taxNumber\": {\n      \"@id\": \"adyen:taxNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"legalArrangementEntityReference\": {\n      \"@id\": \"adyen:legalArrangementEntityReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"legalArrangementMembers\": {\n      \"@id\": \"adyen:legalArrangementMembers\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"legalEntityType\": {\n      \"@id\": \"adyen:legalEntityType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"phoneNumber\": {\n      \"@id\": \"adyen:phoneNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"month\": {\n      \"@id\": \"adyen:month\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"year\": {\n      \"@id\": \"adyen:year\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"code\": {\n      \"@id\": \"adyen:code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"text\": {\n      \"@id\": \"adyen:text\",\n      \"@type\": \"xsd:string\"\n    },\n    \"message\"\
  : {\n      \"@id\": \"adyen:message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"notificationResponse\": {\n      \"@id\": \"adyen:notificationResponse\",\n      \"@type\": \"xsd:string\"\n    },\n    \"statusCode\": {\n      \"@id\": \"adyen:statusCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"errorFields\": {\n      \"@id\": \"adyen:errorFields\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"errorMessage\": {\n      \"@id\": \"adyen:errorMessage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"modificationMerchantReference\": {\n      \"@id\": \"adyen:modificationMerchantReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"modificationPspReference\": {\n      \"@id\": \"adyen:modificationPspReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"paymentMerchantReference\": {\n      \"@id\": \"adyen:paymentMerchantReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"paymentPspReference\": {\n      \"@id\": \"adyen:paymentPspReference\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"merchantAccount\": {\n      \"@id\": \"adyen:merchantAccount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"payoutMethodReference\": {\n      \"@id\": \"adyen:payoutMethodReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"recurringDetailReference\": {\n      \"@id\": \"adyen:recurringDetailReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shopperReference\": {\n      \"@id\": \"adyen:shopperReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nextScheduledPayout\": {\n      \"@id\": \"adyen:nextScheduledPayout\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"schedule\": {\n      \"@id\": \"adyen:schedule\",\n      \"@type\": \"xsd:string\"\n    },\n    \"expirationDate\": {\n      \"@id\": \"adyen:expirationDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"issuerCountry\": {\n      \"@id\": \"adyen:issuerCountry\",\n      \"@type\": \"xsd:string\"\n    },\n    \"issuerState\": {\n      \"@id\"\
  : \"adyen:issuerState\",\n      \"@type\": \"xsd:string\"\n    },\n    \"number\": {\n      \"@id\": \"adyen:number\",\n      \"@type\": \"xsd:string\"\n    },\n    \"originalReference\": {\n      \"@id\": \"adyen:originalReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"originalTransaction\": {\n      \"@id\": \"adyen:originalTransaction\",\n      \"@type\": \"xsd:string\"\n    },\n    \"response\": {\n      \"@id\": \"adyen:response\",\n      \"@type\": \"xsd:string\"\n    },\n    \"remoteAccessUrl\": {\n      \"@id\": \"adyen:remoteAccessUrl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"success\": {\n      \"@id\": \"adyen:success\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"lastPayout\": {\n      \"@id\": \"adyen:lastPayout\",\n      \"@type\": \"xsd:string\"\n    },\n    \"refundResults\": {\n      \"@id\": \"adyen:refundResults\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"jobTitle\": {\n      \"@id\": \"adyen:jobTitle\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"shareholderReference\": {\n      \"@id\": \"adyen:shareholderReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shareholderType\": {\n      \"@id\": \"adyen:shareholderType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"signatoryReference\": {\n      \"@id\": \"adyen:signatoryReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"account\": {\n      \"@id\": \"adyen:account\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reference\": {\n      \"@id\": \"adyen:reference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"logo\": {\n      \"@id\": \"adyen:logo\",\n      \"@type\": \"xsd:string\"\n    },\n    \"merchantHouseNumber\": {\n      \"@id\": \"adyen:merchantHouseNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shopperInteraction\": {\n      \"@id\": \"adyen:shopperInteraction\",\n      \"@type\": \"xsd:string\"\n    },\n    \"splitConfigurationUUID\": {\n      \"@id\": \"adyen:splitConfigurationUUID\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"storeName\": {\n      \"@id\": \"adyen:storeName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"virtualAccount\": {\n      \"@id\": \"adyen:virtualAccount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"captureMerchantReference\": {\n      \"@id\": \"adyen:captureMerchantReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"capturePspReference\": {\n      \"@id\": \"adyen:capturePspReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"creationDate\": {\n      \"@id\": \"adyen:creationDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"disputePspReference\": {\n      \"@id\": \"adyen:disputePspReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"disputeReasonCode\": {\n      \"@id\": \"adyen:disputeReasonCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"payoutPspReference\": {\n      \"@id\": \"adyen:payoutPspReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"transactionStatus\": {\n   \
  \   \"@id\": \"adyen:transactionStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"transferCode\": {\n      \"@id\": \"adyen:transferCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"city\": {\n      \"@id\": \"adyen:city\",\n      \"@type\": \"xsd:string\"\n    },\n    \"country\": {\n      \"@id\": \"adyen:country\",\n      \"@type\": \"xsd:string\"\n    },\n    \"houseNumberOrName\": {\n      \"@id\": \"adyen:houseNumberOrName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"postalCode\": {\n      \"@id\": \"adyen:postalCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stateOrProvince\": {\n      \"@id\": \"adyen:stateOrProvince\",\n      \"@type\": \"xsd:string\"\n    },\n    \"street\": {\n      \"@id\": \"adyen:street\",\n      \"@type\": \"xsd:string\"\n    },\n    \"firstName\": {\n      \"@id\": \"adyen:firstName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"gender\": {\n      \"@id\": \"adyen:gender\",\n      \"@type\": \"xsd:string\"\n    },\n    \"\
  infix\": {\n      \"@id\": \"adyen:infix\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastName\": {\n      \"@id\": \"adyen:lastName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dateOfBirth\": {\n      \"@id\": \"adyen:dateOfBirth\",\n      \"@type\": \"xsd:string\"\n    },\n    \"documentData\": {\n      \"@id\": \"adyen:documentData\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nationality\": {\n      \"@id\": \"adyen:nationality\",\n      \"@type\": \"xsd:string\"\n    },\n    \"phoneCountryCode\": {\n      \"@id\": \"adyen:phoneCountryCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"phoneType\": {\n      \"@id\": \"adyen:phoneType\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-notifications-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
