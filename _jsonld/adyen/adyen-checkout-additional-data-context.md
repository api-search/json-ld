---
class_count: 14
classes:
- AdditionalDataAirline
- AdditionalDataCarRental
- AdditionalDataCommon
- AdditionalDataLevel23
- AdditionalDataLodging
- AdditionalDataOpenInvoice
- AdditionalDataOpi
- AdditionalDataRatepay
- AdditionalDataRetry
- AdditionalDataRisk
- AdditionalDataRiskStandalone
- AdditionalDataSubMerchant
- AdditionalDataTemporaryServices
- AdditionalDataWallets
context_file: json-ld/adyen-checkout-additional-data-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-checkout-additional-data-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Checkout Additional Data from Adyen.
layout: jsonld
name: Adyen Checkout Additional Data Context
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
  name: airline.agencyInvoiceNumber
  type: string
- container: ''
  name: airline.agencyPlanName
  type: string
- container: ''
  name: airline.airlineCode
  type: string
- container: ''
  name: airline.airlineDesignatorCode
  type: string
- container: ''
  name: airline.boardingFee
  type: string
- container: ''
  name: airline.computerizedReservationSystem
  type: string
- container: ''
  name: airline.customerReferenceNumber
  type: string
- container: ''
  name: airline.documentType
  type: string
- container: ''
  name: airline.flightDate
  type: string
- container: ''
  name: airline.leg.carrierCode
  type: string
- container: ''
  name: airline.leg.classOfTravel
  type: string
- container: ''
  name: airline.leg.dateOfTravel
  type: string
- container: ''
  name: airline.leg.departAirport
  type: string
- container: ''
  name: airline.leg.departTax
  type: string
- container: ''
  name: airline.leg.destinationCode
  type: string
- container: ''
  name: airline.leg.fareBaseCode
  type: string
- container: ''
  name: airline.leg.flightNumber
  type: string
- container: ''
  name: airline.leg.stopOverCode
  type: string
- container: ''
  name: airline.passenger.dateOfBirth
  type: string
- container: ''
  name: airline.passenger.firstName
  type: string
- container: ''
  name: airline.passenger.lastName
  type: string
- container: ''
  name: airline.passenger.telephoneNumber
  type: string
- container: ''
  name: airline.passenger.travellerType
  type: string
- container: ''
  name: airline.passengerName
  type: string
- container: ''
  name: airline.ticketIssueAddress
  type: string
- container: ''
  name: airline.ticketNumber
  type: string
- container: ''
  name: airline.travelAgencyCode
  type: string
- container: ''
  name: airline.travelAgencyName
  type: string
- container: ''
  name: carRental.checkOutDate
  type: string
- container: ''
  name: carRental.customerServiceTollFreeNumber
  type: string
- container: ''
  name: carRental.daysRented
  type: string
- container: ''
  name: carRental.fuelCharges
  type: string
- container: ''
  name: carRental.insuranceCharges
  type: string
- container: ''
  name: carRental.locationCity
  type: string
- container: ''
  name: carRental.locationCountry
  type: string
- container: ''
  name: carRental.locationStateProvince
  type: string
- container: ''
  name: carRental.noShowIndicator
  type: string
- container: ''
  name: carRental.oneWayDropOffCharges
  type: string
- container: ''
  name: carRental.rate
  type: string
- container: ''
  name: carRental.rateIndicator
  type: string
- container: ''
  name: carRental.rentalAgreementNumber
  type: string
- container: ''
  name: carRental.rentalClassId
  type: string
- container: ''
  name: carRental.renterName
  type: string
- container: ''
  name: carRental.returnCity
  type: string
- container: ''
  name: carRental.returnCountry
  type: string
- container: ''
  name: carRental.returnDate
  type: string
- container: ''
  name: carRental.returnLocationId
  type: string
- container: ''
  name: carRental.returnStateProvince
  type: string
- container: ''
  name: carRental.taxExemptIndicator
  type: string
- container: ''
  name: travelEntertainmentAuthData.duration
  type: string
- container: ''
  name: travelEntertainmentAuthData.market
  type: string
- container: ''
  name: RequestedTestErrorResponseCode
  type: string
- container: ''
  name: allowPartialAuth
  type: string
- container: ''
  name: authorisationType
  type: string
- container: ''
  name: customRoutingFlag
  type: string
- container: ''
  name: industryUsage
  type: string
- container: ''
  name: manualCapture
  type: string
- container: ''
  name: networkTxReference
  type: string
- container: ''
  name: overwriteBrand
  type: string
- container: ''
  name: subMerchantCity
  type: string
- container: ''
  name: subMerchantCountry
  type: string
- container: ''
  name: subMerchantID
  type: string
- container: ''
  name: subMerchantName
  type: string
- container: ''
  name: subMerchantPostalCode
  type: string
- container: ''
  name: subMerchantState
  type: string
- container: ''
  name: subMerchantStreet
  type: string
- container: ''
  name: subMerchantTaxId
  type: string
- container: ''
  name: enhancedSchemeData.customerReference
  type: string
- container: ''
  name: enhancedSchemeData.destinationCountryCode
  type: string
- container: ''
  name: enhancedSchemeData.destinationPostalCode
  type: string
- container: ''
  name: enhancedSchemeData.destinationStateProvinceCode
  type: string
- container: ''
  name: enhancedSchemeData.dutyAmount
  type: string
- container: ''
  name: enhancedSchemeData.freightAmount
  type: string
- container: ''
  name: enhancedSchemeData.itemDetailLine[itemNr].commodityCode
  type: string
- container: ''
  name: enhancedSchemeData.itemDetailLine[itemNr].description
  type: string
- container: ''
  name: enhancedSchemeData.itemDetailLine[itemNr].discountAmount
  type: string
- container: ''
  name: enhancedSchemeData.itemDetailLine[itemNr].productCode
  type: string
- container: ''
  name: enhancedSchemeData.itemDetailLine[itemNr].quantity
  type: string
- container: ''
  name: enhancedSchemeData.itemDetailLine[itemNr].totalAmount
  type: string
- container: ''
  name: enhancedSchemeData.itemDetailLine[itemNr].unitOfMeasure
  type: string
- container: ''
  name: enhancedSchemeData.itemDetailLine[itemNr].unitPrice
  type: string
- container: ''
  name: enhancedSchemeData.orderDate
  type: string
- container: ''
  name: enhancedSchemeData.shipFromPostalCode
  type: string
- container: ''
  name: enhancedSchemeData.totalTaxAmount
  type: string
- container: ''
  name: lodging.checkInDate
  type: string
- container: ''
  name: lodging.checkOutDate
  type: string
- container: ''
  name: lodging.customerServiceTollFreeNumber
  type: string
- container: ''
  name: lodging.fireSafetyActIndicator
  type: string
- container: ''
  name: lodging.folioCashAdvances
  type: string
- container: ''
  name: lodging.folioNumber
  type: string
- container: ''
  name: lodging.foodBeverageCharges
  type: string
- container: ''
  name: lodging.noShowIndicator
  type: string
- container: ''
  name: lodging.prepaidExpenses
  type: string
- container: ''
  name: lodging.propertyPhoneNumber
  type: string
- container: ''
  name: lodging.room1.numberOfNights
  type: string
- container: ''
  name: lodging.room1.rate
  type: string
- container: ''
  name: lodging.totalRoomTax
  type: string
- container: ''
  name: lodging.totalTax
  type: string
- container: ''
  name: openinvoicedata.merchantData
  type: string
- container: ''
  name: openinvoicedata.numberOfLines
  type: string
- container: ''
  name: openinvoicedata.recipientFirstName
  type: string
- container: ''
  name: openinvoicedata.recipientLastName
  type: string
- container: ''
  name: openinvoicedataLine[itemNr].currencyCode
  type: string
- container: ''
  name: openinvoicedataLine[itemNr].description
  type: string
- container: ''
  name: openinvoicedataLine[itemNr].itemAmount
  type: string
- container: ''
  name: openinvoicedataLine[itemNr].itemId
  type: string
- container: ''
  name: openinvoicedataLine[itemNr].itemVatAmount
  type: string
- container: ''
  name: openinvoicedataLine[itemNr].itemVatPercentage
  type: string
- container: ''
  name: openinvoicedataLine[itemNr].numberOfItems
  type: string
- container: ''
  name: openinvoicedataLine[itemNr].returnShippingCompany
  type: string
- container: ''
  name: openinvoicedataLine[itemNr].returnTrackingNumber
  type: string
- container: ''
  name: openinvoicedataLine[itemNr].returnTrackingUri
  type: string
- container: ''
  name: openinvoicedataLine[itemNr].shippingCompany
  type: string
- container: ''
  name: openinvoicedataLine[itemNr].shippingMethod
  type: string
- container: ''
  name: openinvoicedataLine[itemNr].trackingNumber
  type: string
- container: ''
  name: openinvoicedataLine[itemNr].trackingUri
  type: string
- container: ''
  name: opi.includeTransToken
  type: string
- container: ''
  name: ratepay.installmentAmount
  type: string
- container: ''
  name: ratepay.interestRate
  type: string
- container: ''
  name: ratepay.lastInstallmentAmount
  type: string
- container: ''
  name: ratepay.paymentFirstday
  type: string
- container: ''
  name: ratepaydata.deliveryDate
  type: string
- container: ''
  name: ratepaydata.dueDate
  type: string
- container: ''
  name: ratepaydata.invoiceDate
  type: string
- container: ''
  name: ratepaydata.invoiceId
  type: string
- container: ''
  name: retry.chainAttemptNumber
  type: string
- container: ''
  name: retry.orderAttemptNumber
  type: string
- container: ''
  name: retry.skipRetry
  type: string
- container: ''
  name: riskdata.[customFieldName]
  type: string
- container: ''
  name: riskdata.basket.item[itemNr].amountPerItem
  type: string
- container: ''
  name: riskdata.basket.item[itemNr].brand
  type: string
- container: ''
  name: riskdata.basket.item[itemNr].category
  type: string
- container: ''
  name: riskdata.basket.item[itemNr].color
  type: string
- container: ''
  name: riskdata.basket.item[itemNr].currency
  type: string
- container: ''
  name: riskdata.basket.item[itemNr].itemID
  type: string
- container: ''
  name: riskdata.basket.item[itemNr].manufacturer
  type: string
- container: ''
  name: riskdata.basket.item[itemNr].productTitle
  type: string
- container: ''
  name: riskdata.basket.item[itemNr].quantity
  type: string
- container: ''
  name: riskdata.basket.item[itemNr].receiverEmail
  type: string
- container: ''
  name: riskdata.basket.item[itemNr].size
  type: string
- container: ''
  name: riskdata.basket.item[itemNr].sku
  type: string
- container: ''
  name: riskdata.basket.item[itemNr].upc
  type: string
- container: ''
  name: riskdata.promotions.promotion[itemNr].promotionCode
  type: string
- container: ''
  name: riskdata.promotions.promotion[itemNr].promotionDiscountAmount
  type: string
- container: ''
  name: riskdata.promotions.promotion[itemNr].promotionDiscountCurrency
  type: string
- container: ''
  name: riskdata.promotions.promotion[itemNr].promotionDiscountPercentage
  type: string
- container: ''
  name: riskdata.promotions.promotion[itemNr].promotionName
  type: string
- container: ''
  name: riskdata.riskProfileReference
  type: string
- container: ''
  name: riskdata.skipRisk
  type: string
- container: ''
  name: PayPal.CountryCode
  type: string
- container: ''
  name: PayPal.EmailId
  type: string
- container: ''
  name: PayPal.FirstName
  type: string
- container: ''
  name: PayPal.LastName
  type: string
- container: ''
  name: PayPal.PayerId
  type: string
- container: ''
  name: PayPal.Phone
  type: string
- container: ''
  name: PayPal.ProtectionEligibility
  type: string
- container: ''
  name: PayPal.TransactionId
  type: string
- container: ''
  name: avsResultRaw
  type: string
- container: ''
  name: bin
  type: string
- container: ''
  name: cvcResultRaw
  type: string
- container: ''
  name: riskToken
  type: string
- container: ''
  name: threeDAuthenticated
  type: string
- container: ''
  name: threeDOffered
  type: string
- container: ''
  name: tokenDataType
  type: string
- container: ''
  name: subMerchant.numberOfSubSellers
  type: string
- container: ''
  name: subMerchant.subSeller[subSellerNr].city
  type: string
- container: ''
  name: subMerchant.subSeller[subSellerNr].country
  type: string
- container: ''
  name: subMerchant.subSeller[subSellerNr].id
  type: string
- container: ''
  name: subMerchant.subSeller[subSellerNr].mcc
  type: string
- container: ''
  name: subMerchant.subSeller[subSellerNr].name
  type: string
- container: ''
  name: subMerchant.subSeller[subSellerNr].postalCode
  type: string
- container: ''
  name: subMerchant.subSeller[subSellerNr].state
  type: string
- container: ''
  name: subMerchant.subSeller[subSellerNr].street
  type: string
- container: ''
  name: subMerchant.subSeller[subSellerNr].taxId
  type: string
- container: ''
  name: enhancedSchemeData.employeeName
  type: string
- container: ''
  name: enhancedSchemeData.jobDescription
  type: string
- container: ''
  name: enhancedSchemeData.regularHoursRate
  type: string
- container: ''
  name: enhancedSchemeData.regularHoursWorked
  type: string
- container: ''
  name: enhancedSchemeData.requestName
  type: string
- container: ''
  name: enhancedSchemeData.tempStartDate
  type: string
- container: ''
  name: enhancedSchemeData.tempWeekEnding
  type: string
- container: ''
  name: androidpay.token
  type: string
- container: ''
  name: masterpass.transactionId
  type: string
- container: ''
  name: payment.token
  type: string
- container: ''
  name: paywithgoogle.token
  type: string
- container: ''
  name: samsungpay.token
  type: string
- container: ''
  name: visacheckout.callId
  type: string
property_count: 187
provider_name: Adyen
provider_slug: adyen
slug: adyen-checkout-additional-data-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AdditionalDataAirline\": \"adyen:AdditionalDataAirline\",\n    \"AdditionalDataCarRental\": \"adyen:AdditionalDataCarRental\",\n    \"AdditionalDataCommon\": \"adyen:AdditionalDataCommon\",\n    \"AdditionalDataLevel23\": \"adyen:AdditionalDataLevel23\",\n    \"AdditionalDataLodging\": \"adyen:AdditionalDataLodging\",\n    \"AdditionalDataOpenInvoice\": \"adyen:AdditionalDataOpenInvoice\",\n    \"AdditionalDataOpi\": \"adyen:AdditionalDataOpi\",\n    \"AdditionalDataRatepay\": \"adyen:AdditionalDataRatepay\",\n    \"AdditionalDataRetry\": \"adyen:AdditionalDataRetry\",\n    \"AdditionalDataRisk\": \"adyen:AdditionalDataRisk\",\n    \"AdditionalDataRiskStandalone\": \"adyen:AdditionalDataRiskStandalone\",\n    \"AdditionalDataSubMerchant\"\
  : \"adyen:AdditionalDataSubMerchant\",\n    \"AdditionalDataTemporaryServices\": \"adyen:AdditionalDataTemporaryServices\",\n    \"AdditionalDataWallets\": \"adyen:AdditionalDataWallets\",\n    \"airline.agencyInvoiceNumber\": {\n      \"@id\": \"adyen:airline.agency_invoice_number\",\n      \"@type\": \"xsd:string\"\n    },\n    \"airline.agencyPlanName\": {\n      \"@id\": \"adyen:airline.agency_plan_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"airline.airlineCode\": {\n      \"@id\": \"adyen:airline.airline_code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"airline.airlineDesignatorCode\": {\n      \"@id\": \"adyen:airline.airline_designator_code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"airline.boardingFee\": {\n      \"@id\": \"adyen:airline.boarding_fee\",\n      \"@type\": \"xsd:string\"\n    },\n    \"airline.computerizedReservationSystem\": {\n      \"@id\": \"adyen:airline.computerized_reservation_system\",\n      \"@type\": \"xsd:string\"\n    },\n \
  \   \"airline.customerReferenceNumber\": {\n      \"@id\": \"adyen:airline.customer_reference_number\",\n      \"@type\": \"xsd:string\"\n    },\n    \"airline.documentType\": {\n      \"@id\": \"adyen:airline.document_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"airline.flightDate\": {\n      \"@id\": \"adyen:airline.flight_date\",\n      \"@type\": \"xsd:string\"\n    },\n    \"airline.leg.carrierCode\": {\n      \"@id\": \"adyen:airline.leg.carrier_code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"airline.leg.classOfTravel\": {\n      \"@id\": \"adyen:airline.leg.class_of_travel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"airline.leg.dateOfTravel\": {\n      \"@id\": \"adyen:airline.leg.date_of_travel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"airline.leg.departAirport\": {\n      \"@id\": \"adyen:airline.leg.depart_airport\",\n      \"@type\": \"xsd:string\"\n    },\n    \"airline.leg.departTax\": {\n      \"@id\": \"adyen:airline.leg.depart_tax\",\n\
  \      \"@type\": \"xsd:string\"\n    },\n    \"airline.leg.destinationCode\": {\n      \"@id\": \"adyen:airline.leg.destination_code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"airline.leg.fareBaseCode\": {\n      \"@id\": \"adyen:airline.leg.fare_base_code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"airline.leg.flightNumber\": {\n      \"@id\": \"adyen:airline.leg.flight_number\",\n      \"@type\": \"xsd:string\"\n    },\n    \"airline.leg.stopOverCode\": {\n      \"@id\": \"adyen:airline.leg.stop_over_code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"airline.passenger.dateOfBirth\": {\n      \"@id\": \"adyen:airline.passenger.date_of_birth\",\n      \"@type\": \"xsd:string\"\n    },\n    \"airline.passenger.firstName\": {\n      \"@id\": \"adyen:airline.passenger.first_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"airline.passenger.lastName\": {\n      \"@id\": \"adyen:airline.passenger.last_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"airline.passenger.telephoneNumber\"\
  : {\n      \"@id\": \"adyen:airline.passenger.telephone_number\",\n      \"@type\": \"xsd:string\"\n    },\n    \"airline.passenger.travellerType\": {\n      \"@id\": \"adyen:airline.passenger.traveller_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"airline.passengerName\": {\n      \"@id\": \"adyen:airline.passenger_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"airline.ticketIssueAddress\": {\n      \"@id\": \"adyen:airline.ticket_issue_address\",\n      \"@type\": \"xsd:string\"\n    },\n    \"airline.ticketNumber\": {\n      \"@id\": \"adyen:airline.ticket_number\",\n      \"@type\": \"xsd:string\"\n    },\n    \"airline.travelAgencyCode\": {\n      \"@id\": \"adyen:airline.travel_agency_code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"airline.travelAgencyName\": {\n      \"@id\": \"adyen:airline.travel_agency_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"carRental.checkOutDate\": {\n      \"@id\": \"adyen:carRental.checkOutDate\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"carRental.customerServiceTollFreeNumber\": {\n      \"@id\": \"adyen:carRental.customerServiceTollFreeNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"carRental.daysRented\": {\n      \"@id\": \"adyen:carRental.daysRented\",\n      \"@type\": \"xsd:string\"\n    },\n    \"carRental.fuelCharges\": {\n      \"@id\": \"adyen:carRental.fuelCharges\",\n      \"@type\": \"xsd:string\"\n    },\n    \"carRental.insuranceCharges\": {\n      \"@id\": \"adyen:carRental.insuranceCharges\",\n      \"@type\": \"xsd:string\"\n    },\n    \"carRental.locationCity\": {\n      \"@id\": \"adyen:carRental.locationCity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"carRental.locationCountry\": {\n      \"@id\": \"adyen:carRental.locationCountry\",\n      \"@type\": \"xsd:string\"\n    },\n    \"carRental.locationStateProvince\": {\n      \"@id\": \"adyen:carRental.locationStateProvince\",\n      \"@type\": \"xsd:string\"\n    },\n    \"carRental.noShowIndicator\"\
  : {\n      \"@id\": \"adyen:carRental.noShowIndicator\",\n      \"@type\": \"xsd:string\"\n    },\n    \"carRental.oneWayDropOffCharges\": {\n      \"@id\": \"adyen:carRental.oneWayDropOffCharges\",\n      \"@type\": \"xsd:string\"\n    },\n    \"carRental.rate\": {\n      \"@id\": \"adyen:carRental.rate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"carRental.rateIndicator\": {\n      \"@id\": \"adyen:carRental.rateIndicator\",\n      \"@type\": \"xsd:string\"\n    },\n    \"carRental.rentalAgreementNumber\": {\n      \"@id\": \"adyen:carRental.rentalAgreementNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"carRental.rentalClassId\": {\n      \"@id\": \"adyen:carRental.rentalClassId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"carRental.renterName\": {\n      \"@id\": \"adyen:carRental.renterName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"carRental.returnCity\": {\n      \"@id\": \"adyen:carRental.returnCity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"\
  carRental.returnCountry\": {\n      \"@id\": \"adyen:carRental.returnCountry\",\n      \"@type\": \"xsd:string\"\n    },\n    \"carRental.returnDate\": {\n      \"@id\": \"adyen:carRental.returnDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"carRental.returnLocationId\": {\n      \"@id\": \"adyen:carRental.returnLocationId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"carRental.returnStateProvince\": {\n      \"@id\": \"adyen:carRental.returnStateProvince\",\n      \"@type\": \"xsd:string\"\n    },\n    \"carRental.taxExemptIndicator\": {\n      \"@id\": \"adyen:carRental.taxExemptIndicator\",\n      \"@type\": \"xsd:string\"\n    },\n    \"travelEntertainmentAuthData.duration\": {\n      \"@id\": \"adyen:travelEntertainmentAuthData.duration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"travelEntertainmentAuthData.market\": {\n      \"@id\": \"adyen:travelEntertainmentAuthData.market\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RequestedTestErrorResponseCode\":\
  \ {\n      \"@id\": \"adyen:RequestedTestErrorResponseCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"allowPartialAuth\": {\n      \"@id\": \"adyen:allowPartialAuth\",\n      \"@type\": \"xsd:string\"\n    },\n    \"authorisationType\": {\n      \"@id\": \"adyen:authorisationType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"customRoutingFlag\": {\n      \"@id\": \"adyen:customRoutingFlag\",\n      \"@type\": \"xsd:string\"\n    },\n    \"industryUsage\": {\n      \"@id\": \"adyen:industryUsage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"manualCapture\": {\n      \"@id\": \"adyen:manualCapture\",\n      \"@type\": \"xsd:string\"\n    },\n    \"networkTxReference\": {\n      \"@id\": \"adyen:networkTxReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"overwriteBrand\": {\n      \"@id\": \"adyen:overwriteBrand\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subMerchantCity\": {\n      \"@id\": \"adyen:subMerchantCity\",\n      \"@type\": \"xsd:string\"\n \
  \   },\n    \"subMerchantCountry\": {\n      \"@id\": \"adyen:subMerchantCountry\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subMerchantID\": {\n      \"@id\": \"adyen:subMerchantID\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subMerchantName\": {\n      \"@id\": \"adyen:subMerchantName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subMerchantPostalCode\": {\n      \"@id\": \"adyen:subMerchantPostalCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subMerchantState\": {\n      \"@id\": \"adyen:subMerchantState\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subMerchantStreet\": {\n      \"@id\": \"adyen:subMerchantStreet\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subMerchantTaxId\": {\n      \"@id\": \"adyen:subMerchantTaxId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"enhancedSchemeData.customerReference\": {\n      \"@id\": \"adyen:enhancedSchemeData.customerReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"enhancedSchemeData.destinationCountryCode\"\
  : {\n      \"@id\": \"adyen:enhancedSchemeData.destinationCountryCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"enhancedSchemeData.destinationPostalCode\": {\n      \"@id\": \"adyen:enhancedSchemeData.destinationPostalCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"enhancedSchemeData.destinationStateProvinceCode\": {\n      \"@id\": \"adyen:enhancedSchemeData.destinationStateProvinceCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"enhancedSchemeData.dutyAmount\": {\n      \"@id\": \"adyen:enhancedSchemeData.dutyAmount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"enhancedSchemeData.freightAmount\": {\n      \"@id\": \"adyen:enhancedSchemeData.freightAmount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"enhancedSchemeData.itemDetailLine[itemNr].commodityCode\": {\n      \"@id\": \"adyen:enhancedSchemeData.itemDetailLine[itemNr].commodityCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"enhancedSchemeData.itemDetailLine[itemNr].description\": {\n  \
  \    \"@id\": \"adyen:enhancedSchemeData.itemDetailLine[itemNr].description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"enhancedSchemeData.itemDetailLine[itemNr].discountAmount\": {\n      \"@id\": \"adyen:enhancedSchemeData.itemDetailLine[itemNr].discountAmount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"enhancedSchemeData.itemDetailLine[itemNr].productCode\": {\n      \"@id\": \"adyen:enhancedSchemeData.itemDetailLine[itemNr].productCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"enhancedSchemeData.itemDetailLine[itemNr].quantity\": {\n      \"@id\": \"adyen:enhancedSchemeData.itemDetailLine[itemNr].quantity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"enhancedSchemeData.itemDetailLine[itemNr].totalAmount\": {\n      \"@id\": \"adyen:enhancedSchemeData.itemDetailLine[itemNr].totalAmount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"enhancedSchemeData.itemDetailLine[itemNr].unitOfMeasure\": {\n      \"@id\": \"adyen:enhancedSchemeData.itemDetailLine[itemNr].unitOfMeasure\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"enhancedSchemeData.itemDetailLine[itemNr].unitPrice\": {\n      \"@id\": \"adyen:enhancedSchemeData.itemDetailLine[itemNr].unitPrice\",\n      \"@type\": \"xsd:string\"\n    },\n    \"enhancedSchemeData.orderDate\": {\n      \"@id\": \"adyen:enhancedSchemeData.orderDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"enhancedSchemeData.shipFromPostalCode\": {\n      \"@id\": \"adyen:enhancedSchemeData.shipFromPostalCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"enhancedSchemeData.totalTaxAmount\": {\n      \"@id\": \"adyen:enhancedSchemeData.totalTaxAmount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lodging.checkInDate\": {\n      \"@id\": \"adyen:lodging.checkInDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lodging.checkOutDate\": {\n      \"@id\": \"adyen:lodging.checkOutDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lodging.customerServiceTollFreeNumber\": {\n      \"@id\": \"adyen:lodging.customerServiceTollFreeNumber\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"lodging.fireSafetyActIndicator\": {\n      \"@id\": \"adyen:lodging.fireSafetyActIndicator\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lodging.folioCashAdvances\": {\n      \"@id\": \"adyen:lodging.folioCashAdvances\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lodging.folioNumber\": {\n      \"@id\": \"adyen:lodging.folioNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lodging.foodBeverageCharges\": {\n      \"@id\": \"adyen:lodging.foodBeverageCharges\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lodging.noShowIndicator\": {\n      \"@id\": \"adyen:lodging.noShowIndicator\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lodging.prepaidExpenses\": {\n      \"@id\": \"adyen:lodging.prepaidExpenses\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lodging.propertyPhoneNumber\": {\n      \"@id\": \"adyen:lodging.propertyPhoneNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lodging.room1.numberOfNights\"\
  : {\n      \"@id\": \"adyen:lodging.room1.numberOfNights\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lodging.room1.rate\": {\n      \"@id\": \"adyen:lodging.room1.rate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lodging.totalRoomTax\": {\n      \"@id\": \"adyen:lodging.totalRoomTax\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lodging.totalTax\": {\n      \"@id\": \"adyen:lodging.totalTax\",\n      \"@type\": \"xsd:string\"\n    },\n    \"openinvoicedata.merchantData\": {\n      \"@id\": \"adyen:openinvoicedata.merchantData\",\n      \"@type\": \"xsd:string\"\n    },\n    \"openinvoicedata.numberOfLines\": {\n      \"@id\": \"adyen:openinvoicedata.numberOfLines\",\n      \"@type\": \"xsd:string\"\n    },\n    \"openinvoicedata.recipientFirstName\": {\n      \"@id\": \"adyen:openinvoicedata.recipientFirstName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"openinvoicedata.recipientLastName\": {\n      \"@id\": \"adyen:openinvoicedata.recipientLastName\",\n      \"\
  @type\": \"xsd:string\"\n    },\n    \"openinvoicedataLine[itemNr].currencyCode\": {\n      \"@id\": \"adyen:openinvoicedataLine[itemNr].currencyCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"openinvoicedataLine[itemNr].description\": {\n      \"@id\": \"adyen:openinvoicedataLine[itemNr].description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"openinvoicedataLine[itemNr].itemAmount\": {\n      \"@id\": \"adyen:openinvoicedataLine[itemNr].itemAmount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"openinvoicedataLine[itemNr].itemId\": {\n      \"@id\": \"adyen:openinvoicedataLine[itemNr].itemId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"openinvoicedataLine[itemNr].itemVatAmount\": {\n      \"@id\": \"adyen:openinvoicedataLine[itemNr].itemVatAmount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"openinvoicedataLine[itemNr].itemVatPercentage\": {\n      \"@id\": \"adyen:openinvoicedataLine[itemNr].itemVatPercentage\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"openinvoicedataLine[itemNr].numberOfItems\": {\n      \"@id\": \"adyen:openinvoicedataLine[itemNr].numberOfItems\",\n      \"@type\": \"xsd:string\"\n    },\n    \"openinvoicedataLine[itemNr].returnShippingCompany\": {\n      \"@id\": \"adyen:openinvoicedataLine[itemNr].returnShippingCompany\",\n      \"@type\": \"xsd:string\"\n    },\n    \"openinvoicedataLine[itemNr].returnTrackingNumber\": {\n      \"@id\": \"adyen:openinvoicedataLine[itemNr].returnTrackingNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"openinvoicedataLine[itemNr].returnTrackingUri\": {\n      \"@id\": \"adyen:openinvoicedataLine[itemNr].returnTrackingUri\",\n      \"@type\": \"xsd:string\"\n    },\n    \"openinvoicedataLine[itemNr].shippingCompany\": {\n      \"@id\": \"adyen:openinvoicedataLine[itemNr].shippingCompany\",\n      \"@type\": \"xsd:string\"\n    },\n    \"openinvoicedataLine[itemNr].shippingMethod\": {\n      \"@id\": \"adyen:openinvoicedataLine[itemNr].shippingMethod\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"openinvoicedataLine[itemNr].trackingNumber\": {\n      \"@id\": \"adyen:openinvoicedataLine[itemNr].trackingNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"openinvoicedataLine[itemNr].trackingUri\": {\n      \"@id\": \"adyen:openinvoicedataLine[itemNr].trackingUri\",\n      \"@type\": \"xsd:string\"\n    },\n    \"opi.includeTransToken\": {\n      \"@id\": \"adyen:opi.includeTransToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ratepay.installmentAmount\": {\n      \"@id\": \"adyen:ratepay.installmentAmount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ratepay.interestRate\": {\n      \"@id\": \"adyen:ratepay.interestRate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ratepay.lastInstallmentAmount\": {\n      \"@id\": \"adyen:ratepay.lastInstallmentAmount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ratepay.paymentFirstday\": {\n      \"@id\": \"adyen:ratepay.paymentFirstday\",\n      \"@type\": \"xsd:string\"\n    },\n \
  \   \"ratepaydata.deliveryDate\": {\n      \"@id\": \"adyen:ratepaydata.deliveryDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ratepaydata.dueDate\": {\n      \"@id\": \"adyen:ratepaydata.dueDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ratepaydata.invoiceDate\": {\n      \"@id\": \"adyen:ratepaydata.invoiceDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ratepaydata.invoiceId\": {\n      \"@id\": \"adyen:ratepaydata.invoiceId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"retry.chainAttemptNumber\": {\n      \"@id\": \"adyen:retry.chainAttemptNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"retry.orderAttemptNumber\": {\n      \"@id\": \"adyen:retry.orderAttemptNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"retry.skipRetry\": {\n      \"@id\": \"adyen:retry.skipRetry\",\n      \"@type\": \"xsd:string\"\n    },\n    \"riskdata.[customFieldName]\": {\n      \"@id\": \"adyen:riskdata.[customFieldName]\",\n      \"@type\": \"xsd:string\"\n\
  \    },\n    \"riskdata.basket.item[itemNr].amountPerItem\": {\n      \"@id\": \"adyen:riskdata.basket.item[itemNr].amountPerItem\",\n      \"@type\": \"xsd:string\"\n    },\n    \"riskdata.basket.item[itemNr].brand\": {\n      \"@id\": \"adyen:riskdata.basket.item[itemNr].brand\",\n      \"@type\": \"xsd:string\"\n    },\n    \"riskdata.basket.item[itemNr].category\": {\n      \"@id\": \"adyen:riskdata.basket.item[itemNr].category\",\n      \"@type\": \"xsd:string\"\n    },\n    \"riskdata.basket.item[itemNr].color\": {\n      \"@id\": \"adyen:riskdata.basket.item[itemNr].color\",\n      \"@type\": \"xsd:string\"\n    },\n    \"riskdata.basket.item[itemNr].currency\": {\n      \"@id\": \"adyen:riskdata.basket.item[itemNr].currency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"riskdata.basket.item[itemNr].itemID\": {\n      \"@id\": \"adyen:riskdata.basket.item[itemNr].itemID\",\n      \"@type\": \"xsd:string\"\n    },\n    \"riskdata.basket.item[itemNr].manufacturer\": {\n      \"\
  @id\": \"adyen:riskdata.basket.item[itemNr].manufacturer\",\n      \"@type\": \"xsd:string\"\n    },\n    \"riskdata.basket.item[itemNr].productTitle\": {\n      \"@id\": \"adyen:riskdata.basket.item[itemNr].productTitle\",\n      \"@type\": \"xsd:string\"\n    },\n    \"riskdata.basket.item[itemNr].quantity\": {\n      \"@id\": \"adyen:riskdata.basket.item[itemNr].quantity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"riskdata.basket.item[itemNr].receiverEmail\": {\n      \"@id\": \"adyen:riskdata.basket.item[itemNr].receiverEmail\",\n      \"@type\": \"xsd:string\"\n    },\n    \"riskdata.basket.item[itemNr].size\": {\n      \"@id\": \"adyen:riskdata.basket.item[itemNr].size\",\n      \"@type\": \"xsd:string\"\n    },\n    \"riskdata.basket.item[itemNr].sku\": {\n      \"@id\": \"adyen:riskdata.basket.item[itemNr].sku\",\n      \"@type\": \"xsd:string\"\n    },\n    \"riskdata.basket.item[itemNr].upc\": {\n      \"@id\": \"adyen:riskdata.basket.item[itemNr].upc\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"riskdata.promotions.promotion[itemNr].promotionCode\": {\n      \"@id\": \"adyen:riskdata.promotions.promotion[itemNr].promotionCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"riskdata.promotions.promotion[itemNr].promotionDiscountAmount\": {\n      \"@id\": \"adyen:riskdata.promotions.promotion[itemNr].promotionDiscountAmount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"riskdata.promotions.promotion[itemNr].promotionDiscountCurrency\": {\n      \"@id\": \"adyen:riskdata.promotions.promotion[itemNr].promotionDiscountCurrency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"riskdata.promotions.promotion[itemNr].promotionDiscountPercentage\": {\n      \"@id\": \"adyen:riskdata.promotions.promotion[itemNr].promotionDiscountPercentage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"riskdata.promotions.promotion[itemNr].promotionName\": {\n      \"@id\": \"adyen:riskdata.promotions.promotion[itemNr].promotionName\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"riskdata.riskProfileReference\": {\n      \"@id\": \"adyen:riskdata.riskProfileReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"riskdata.skipRisk\": {\n      \"@id\": \"adyen:riskdata.skipRisk\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PayPal.CountryCode\": {\n      \"@id\": \"adyen:PayPal.CountryCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PayPal.EmailId\": {\n      \"@id\": \"adyen:PayPal.EmailId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PayPal.FirstName\": {\n      \"@id\": \"adyen:PayPal.FirstName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PayPal.LastName\": {\n      \"@id\": \"adyen:PayPal.LastName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PayPal.PayerId\": {\n      \"@id\": \"adyen:PayPal.PayerId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PayPal.Phone\": {\n      \"@id\": \"adyen:PayPal.Phone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PayPal.ProtectionEligibility\": {\n      \"@id\": \"adyen:PayPal.ProtectionEligibility\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"PayPal.TransactionId\": {\n      \"@id\": \"adyen:PayPal.TransactionId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"avsResultRaw\": {\n      \"@id\": \"adyen:avsResultRaw\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bin\": {\n      \"@id\": \"adyen:bin\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cvcResultRaw\": {\n      \"@id\": \"adyen:cvcResultRaw\",\n      \"@type\": \"xsd:string\"\n    },\n    \"riskToken\": {\n      \"@id\": \"adyen:riskToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"threeDAuthenticated\": {\n      \"@id\": \"adyen:threeDAuthenticated\",\n      \"@type\": \"xsd:string\"\n    },\n    \"threeDOffered\": {\n      \"@id\": \"adyen:threeDOffered\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tokenDataType\": {\n      \"@id\": \"adyen:tokenDataType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subMerchant.numberOfSubSellers\": {\n      \"@id\": \"adyen:subMerchant.numberOfSubSellers\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"subMerchant.subSeller[subSellerNr].city\": {\n      \"@id\": \"adyen:subMerchant.subSeller[subSellerNr].city\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subMerchant.subSeller[subSellerNr].country\": {\n      \"@id\": \"adyen:subMerchant.subSeller[subSellerNr].country\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subMerchant.subSeller[subSellerNr].id\": {\n      \"@id\": \"adyen:subMerchant.subSeller[subSellerNr].id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subMerchant.subSeller[subSellerNr].mcc\": {\n      \"@id\": \"adyen:subMerchant.subSeller[subSellerNr].mcc\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subMerchant.subSeller[subSellerNr].name\": {\n      \"@id\": \"adyen:subMerchant.subSeller[subSellerNr].name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subMerchant.subSeller[subSellerNr].postalCode\": {\n      \"@id\": \"adyen:subMerchant.subSeller[subSellerNr].postalCode\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"subMerchant.subSeller[subSellerNr].state\": {\n      \"@id\": \"adyen:subMerchant.subSeller[subSellerNr].state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subMerchant.subSeller[subSellerNr].street\": {\n      \"@id\": \"adyen:subMerchant.subSeller[subSellerNr].street\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subMerchant.subSeller[subSellerNr].taxId\": {\n      \"@id\": \"adyen:subMerchant.subSeller[subSellerNr].taxId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"enhancedSchemeData.employeeName\": {\n      \"@id\": \"adyen:enhancedSchemeData.employeeName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"enhancedSchemeData.jobDescription\": {\n      \"@id\": \"adyen:enhancedSchemeData.jobDescription\",\n      \"@type\": \"xsd:string\"\n    },\n    \"enhancedSchemeData.regularHoursRate\": {\n      \"@id\": \"adyen:enhancedSchemeData.regularHoursRate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"enhancedSchemeData.regularHoursWorked\": {\n      \"\
  @id\": \"adyen:enhancedSchemeData.regularHoursWorked\",\n      \"@type\": \"xsd:string\"\n    },\n    \"enhancedSchemeData.requestName\": {\n      \"@id\": \"adyen:enhancedSchemeData.requestName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"enhancedSchemeData.tempStartDate\": {\n      \"@id\": \"adyen:enhancedSchemeData.tempStartDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"enhancedSchemeData.tempWeekEnding\": {\n      \"@id\": \"adyen:enhancedSchemeData.tempWeekEnding\",\n      \"@type\": \"xsd:string\"\n    },\n    \"androidpay.token\": {\n      \"@id\": \"adyen:androidpay.token\",\n      \"@type\": \"xsd:string\"\n    },\n    \"masterpass.transactionId\": {\n      \"@id\": \"adyen:masterpass.transactionId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"payment.token\": {\n      \"@id\": \"adyen:payment.token\",\n      \"@type\": \"xsd:string\"\n    },\n    \"paywithgoogle.token\": {\n      \"@id\": \"adyen:paywithgoogle.token\",\n      \"@type\": \"xsd:string\"\n \
  \   },\n    \"samsungpay.token\": {\n      \"@id\": \"adyen:samsungpay.token\",\n      \"@type\": \"xsd:string\"\n    },\n    \"visacheckout.callId\": {\n      \"@id\": \"adyen:visacheckout.callId\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-checkout-additional-data-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
