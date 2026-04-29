---
class_count: 0
classes: []
context_file: json-ld/factset-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/factset/refs/heads/main/json-ld/factset-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Factset from Factset.
layout: jsonld
name: Factset Context
namespaces:
- prefix: factset
  uri: https://developer.factset.com/vocab/
- prefix: schema
  uri: https://schema.org/
- prefix: fibo
  uri: https://spec.edmcouncil.org/fibo/ontology/
- prefix: fibo-fnd
  uri: https://spec.edmcouncil.org/fibo/ontology/FND/
- prefix: fibo-sec
  uri: https://spec.edmcouncil.org/fibo/ontology/SEC/
- prefix: fibo-be
  uri: https://spec.edmcouncil.org/fibo/ontology/BE/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Company
  type: ''
- container: ''
  name: IncomeStatement
  type: ''
- container: ''
  name: BalanceSheet
  type: ''
- container: ''
  name: CashFlowStatement
  type: ''
- container: ''
  name: FinancialRatios
  type: ''
- container: ''
  name: ConsensusEstimate
  type: ''
- container: ''
  name: Segment
  type: ''
- container: ''
  name: FiscalPeriod
  type: ''
- container: ''
  name: Fundamental
  type: ''
- container: ''
  name: financialStatements
  type: ''
- container: ''
  name: incomeStatement
  type: reference
- container: ''
  name: balanceSheet
  type: reference
- container: ''
  name: cashFlowStatement
  type: reference
- container: ''
  name: ratios
  type: reference
- container: ''
  name: estimates
  type: reference
- container: ''
  name: segments
  type: ''
- container: ''
  name: metadata
  type: reference
property_count: 17
provider_name: Factset
provider_slug: factset
slug: factset-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n\n    \"factset\": \"https://developer.factset.com/vocab/\",\n    \"schema\": \"https://schema.org/\",\n    \"fibo\": \"https://spec.edmcouncil.org/fibo/ontology/\",\n    \"fibo-fnd\": \"https://spec.edmcouncil.org/fibo/ontology/FND/\",\n    \"fibo-sec\": \"https://spec.edmcouncil.org/fibo/ontology/SEC/\",\n    \"fibo-be\": \"https://spec.edmcouncil.org/fibo/ontology/BE/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Company\": {\n      \"@id\": \"factset:Company\",\n      \"@context\": {\n        \"requestId\": {\n          \"@id\": \"factset:requestId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"fsymId\": {\n          \"@id\": \"factset:fsymId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"companyName\": {\n          \"@id\": \"schema:legalName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"ticker\": {\n       \
  \   \"@id\": \"schema:tickerSymbol\",\n          \"@type\": \"xsd:string\"\n        },\n        \"exchange\": {\n          \"@id\": \"factset:exchange\",\n          \"@type\": \"xsd:string\"\n        },\n        \"country\": {\n          \"@id\": \"schema:addressCountry\",\n          \"@type\": \"xsd:string\"\n        },\n        \"currency\": {\n          \"@id\": \"schema:currency\",\n          \"@type\": \"xsd:string\"\n        },\n        \"sectorCode\": {\n          \"@id\": \"factset:sectorCode\",\n          \"@type\": \"xsd:string\"\n        },\n        \"industryCode\": {\n          \"@id\": \"factset:industryCode\",\n          \"@type\": \"xsd:string\"\n        },\n        \"fiscalYearEnd\": {\n          \"@id\": \"factset:fiscalYearEnd\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"IncomeStatement\": {\n      \"@id\": \"factset:IncomeStatement\",\n      \"@context\": {\n        \"sales\": {\n          \"@id\": \"factset:FF_SALES\",\n          \"\
  @type\": \"xsd:double\"\n        },\n        \"costOfGoodsSold\": {\n          \"@id\": \"factset:FF_COGS\",\n          \"@type\": \"xsd:double\"\n        },\n        \"grossIncome\": {\n          \"@id\": \"factset:FF_GROSS_INC\",\n          \"@type\": \"xsd:double\"\n        },\n        \"sellingGeneralAdmin\": {\n          \"@id\": \"factset:FF_SGA\",\n          \"@type\": \"xsd:double\"\n        },\n        \"researchDevelopment\": {\n          \"@id\": \"factset:FF_RD_EXP\",\n          \"@type\": \"xsd:double\"\n        },\n        \"depreciation\": {\n          \"@id\": \"factset:FF_DEP_AMORT\",\n          \"@type\": \"xsd:double\"\n        },\n        \"operatingIncome\": {\n          \"@id\": \"factset:FF_OPER_INC\",\n          \"@type\": \"xsd:double\"\n        },\n        \"interestExpense\": {\n          \"@id\": \"factset:FF_INT_EXP\",\n          \"@type\": \"xsd:double\"\n        },\n        \"pretaxIncome\": {\n          \"@id\": \"factset:FF_PTAX_INC\",\n          \"@type\"\
  : \"xsd:double\"\n        },\n        \"incomeTax\": {\n          \"@id\": \"factset:FF_TAX\",\n          \"@type\": \"xsd:double\"\n        },\n        \"netIncome\": {\n          \"@id\": \"factset:FF_NET_INC\",\n          \"@type\": \"xsd:double\"\n        },\n        \"earningsPerShare\": {\n          \"@id\": \"factset:FF_EPS\",\n          \"@type\": \"xsd:double\"\n        },\n        \"earningsPerShareDiluted\": {\n          \"@id\": \"factset:FF_EPS_DIL\",\n          \"@type\": \"xsd:double\"\n        },\n        \"ebitda\": {\n          \"@id\": \"factset:FF_EBITDA\",\n          \"@type\": \"xsd:double\"\n        },\n        \"ebit\": {\n          \"@id\": \"factset:FF_EBIT\",\n          \"@type\": \"xsd:double\"\n        },\n        \"dividendsPerShare\": {\n          \"@id\": \"factset:FF_DPS\",\n          \"@type\": \"xsd:double\"\n        }\n      }\n    },\n\n    \"BalanceSheet\": {\n      \"@id\": \"factset:BalanceSheet\",\n      \"@context\": {\n        \"totalAssets\"\
  : {\n          \"@id\": \"factset:FF_ASSETS\",\n          \"@type\": \"xsd:double\"\n        },\n        \"currentAssets\": {\n          \"@id\": \"factset:FF_CURR_ASSETS\",\n          \"@type\": \"xsd:double\"\n        },\n        \"cashAndEquivalents\": {\n          \"@id\": \"factset:FF_CASH\",\n          \"@type\": \"xsd:double\"\n        },\n        \"shortTermInvestments\": {\n          \"@id\": \"factset:FF_STI\",\n          \"@type\": \"xsd:double\"\n        },\n        \"accountsReceivable\": {\n          \"@id\": \"factset:FF_ACCT_RCV\",\n          \"@type\": \"xsd:double\"\n        },\n        \"inventory\": {\n          \"@id\": \"factset:FF_INVENTORIES\",\n          \"@type\": \"xsd:double\"\n        },\n        \"propertyPlantEquipment\": {\n          \"@id\": \"factset:FF_PPE_NET\",\n          \"@type\": \"xsd:double\"\n        },\n        \"goodwill\": {\n          \"@id\": \"factset:FF_GOODWILL\",\n          \"@type\": \"xsd:double\"\n        },\n        \"intangibleAssets\"\
  : {\n          \"@id\": \"factset:FF_INTANG\",\n          \"@type\": \"xsd:double\"\n        },\n        \"totalLiabilities\": {\n          \"@id\": \"factset:FF_LIABS\",\n          \"@type\": \"xsd:double\"\n        },\n        \"currentLiabilities\": {\n          \"@id\": \"factset:FF_CURR_LIABS\",\n          \"@type\": \"xsd:double\"\n        },\n        \"accountsPayable\": {\n          \"@id\": \"factset:FF_ACCT_PAY\",\n          \"@type\": \"xsd:double\"\n        },\n        \"shortTermDebt\": {\n          \"@id\": \"factset:FF_STD\",\n          \"@type\": \"xsd:double\"\n        },\n        \"longTermDebt\": {\n          \"@id\": \"factset:FF_LTD\",\n          \"@type\": \"xsd:double\"\n        },\n        \"totalDebt\": {\n          \"@id\": \"factset:FF_DEBT\",\n          \"@type\": \"xsd:double\"\n        },\n        \"totalEquity\": {\n          \"@id\": \"factset:FF_SHLDRS_EQ\",\n          \"@type\": \"xsd:double\"\n        },\n        \"retainedEarnings\": {\n          \"\
  @id\": \"factset:FF_RE\",\n          \"@type\": \"xsd:double\"\n        },\n        \"bookValuePerShare\": {\n          \"@id\": \"factset:FF_BK_VAL_PS\",\n          \"@type\": \"xsd:double\"\n        }\n      }\n    },\n\n    \"CashFlowStatement\": {\n      \"@id\": \"factset:CashFlowStatement\",\n      \"@context\": {\n        \"operatingCashFlow\": {\n          \"@id\": \"factset:FF_OPER_CF\",\n          \"@type\": \"xsd:double\"\n        },\n        \"capitalExpenditures\": {\n          \"@id\": \"factset:FF_CAPEX\",\n          \"@type\": \"xsd:double\"\n        },\n        \"freeCashFlow\": {\n          \"@id\": \"factset:FF_FREE_CF\",\n          \"@type\": \"xsd:double\"\n        },\n        \"investingCashFlow\": {\n          \"@id\": \"factset:FF_INVEST_CF\",\n          \"@type\": \"xsd:double\"\n        },\n        \"financingCashFlow\": {\n          \"@id\": \"factset:FF_FIN_CF\",\n          \"@type\": \"xsd:double\"\n        },\n        \"dividendsPaid\": {\n          \"@id\"\
  : \"factset:FF_DIV_PAID\",\n          \"@type\": \"xsd:double\"\n        },\n        \"shareRepurchases\": {\n          \"@id\": \"factset:FF_REPURCH\",\n          \"@type\": \"xsd:double\"\n        },\n        \"netChangeInCash\": {\n          \"@id\": \"factset:FF_CHG_CASH\",\n          \"@type\": \"xsd:double\"\n        }\n      }\n    },\n\n    \"FinancialRatios\": {\n      \"@id\": \"factset:FinancialRatios\",\n      \"@context\": {\n        \"priceToEarnings\": {\n          \"@id\": \"factset:FF_PE\",\n          \"@type\": \"xsd:double\"\n        },\n        \"priceToBook\": {\n          \"@id\": \"factset:FF_PBK\",\n          \"@type\": \"xsd:double\"\n        },\n        \"priceToSales\": {\n          \"@id\": \"factset:FF_PS\",\n          \"@type\": \"xsd:double\"\n        },\n        \"priceToCashFlow\": {\n          \"@id\": \"factset:FF_PCF\",\n          \"@type\": \"xsd:double\"\n        },\n        \"enterpriseValueToEbitda\": {\n          \"@id\": \"factset:FF_EV_EBITDA\"\
  ,\n          \"@type\": \"xsd:double\"\n        },\n        \"enterpriseValueToSales\": {\n          \"@id\": \"factset:FF_EV_SALES\",\n          \"@type\": \"xsd:double\"\n        },\n        \"dividendYield\": {\n          \"@id\": \"factset:FF_DIV_YLD\",\n          \"@type\": \"xsd:double\"\n        },\n        \"returnOnEquity\": {\n          \"@id\": \"factset:FF_ROE\",\n          \"@type\": \"xsd:double\"\n        },\n        \"returnOnAssets\": {\n          \"@id\": \"factset:FF_ROA\",\n          \"@type\": \"xsd:double\"\n        },\n        \"returnOnInvestedCapital\": {\n          \"@id\": \"factset:FF_ROIC\",\n          \"@type\": \"xsd:double\"\n        },\n        \"grossMargin\": {\n          \"@id\": \"factset:FF_GROSS_MARGIN\",\n          \"@type\": \"xsd:double\"\n        },\n        \"operatingMargin\": {\n          \"@id\": \"factset:FF_OPER_MARGIN\",\n          \"@type\": \"xsd:double\"\n        },\n        \"netProfitMargin\": {\n          \"@id\": \"factset:FF_NET_MARGIN\"\
  ,\n          \"@type\": \"xsd:double\"\n        },\n        \"currentRatio\": {\n          \"@id\": \"factset:FF_CURR_RATIO\",\n          \"@type\": \"xsd:double\"\n        },\n        \"quickRatio\": {\n          \"@id\": \"factset:FF_QUICK_RATIO\",\n          \"@type\": \"xsd:double\"\n        },\n        \"debtToEquity\": {\n          \"@id\": \"factset:FF_DEBT_EQUITY\",\n          \"@type\": \"xsd:double\"\n        },\n        \"debtToAssets\": {\n          \"@id\": \"factset:FF_DEBT_ASSETS\",\n          \"@type\": \"xsd:double\"\n        },\n        \"interestCoverage\": {\n          \"@id\": \"factset:FF_INT_COV\",\n          \"@type\": \"xsd:double\"\n        },\n        \"revenueGrowth\": {\n          \"@id\": \"factset:FF_SALES_GR\",\n          \"@type\": \"xsd:double\"\n        },\n        \"epsGrowth\": {\n          \"@id\": \"factset:FF_EPS_GR\",\n          \"@type\": \"xsd:double\"\n        },\n        \"marketCapitalization\": {\n          \"@id\": \"factset:FF_MKT_CAP\"\
  ,\n          \"@type\": \"xsd:double\"\n        },\n        \"enterpriseValue\": {\n          \"@id\": \"factset:FF_EV\",\n          \"@type\": \"xsd:double\"\n        }\n      }\n    },\n\n    \"ConsensusEstimate\": {\n      \"@id\": \"factset:ConsensusEstimate\",\n      \"@context\": {\n        \"metric\": {\n          \"@id\": \"factset:estimateMetric\",\n          \"@type\": \"xsd:string\"\n        },\n        \"fiscalYear\": {\n          \"@id\": \"factset:fiscalYear\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"estimateCount\": {\n          \"@id\": \"factset:estimateCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"mean\": {\n          \"@id\": \"factset:estimateMean\",\n          \"@type\": \"xsd:double\"\n        },\n        \"median\": {\n          \"@id\": \"factset:estimateMedian\",\n          \"@type\": \"xsd:double\"\n        },\n        \"high\": {\n          \"@id\": \"factset:estimateHigh\",\n          \"@type\": \"xsd:double\"\n \
  \       },\n        \"low\": {\n          \"@id\": \"factset:estimateLow\",\n          \"@type\": \"xsd:double\"\n        },\n        \"standardDeviation\": {\n          \"@id\": \"factset:estimateStdDev\",\n          \"@type\": \"xsd:double\"\n        }\n      }\n    },\n\n    \"Segment\": {\n      \"@id\": \"factset:Segment\",\n      \"@context\": {\n        \"label\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"segmentType\": {\n          \"@id\": \"factset:segmentType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"metric\": {\n          \"@id\": \"factset:segmentMetric\",\n          \"@type\": \"xsd:string\"\n        },\n        \"date\": {\n          \"@id\": \"dcterms:date\",\n          \"@type\": \"xsd:date\"\n        },\n        \"value\": {\n          \"@id\": \"schema:value\",\n          \"@type\": \"xsd:double\"\n        }\n      }\n    },\n\n    \"FiscalPeriod\": {\n      \"@id\": \"factset:FiscalPeriod\"\
  ,\n      \"@context\": {\n        \"periodicity\": {\n          \"@id\": \"factset:periodicity\",\n          \"@type\": \"xsd:string\"\n        },\n        \"fiscalPeriod\": {\n          \"@id\": \"factset:fiscalPeriod\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"fiscalYear\": {\n          \"@id\": \"factset:fiscalYear\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"fiscalEndDate\": {\n          \"@id\": \"factset:fiscalEndDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"reportDate\": {\n          \"@id\": \"factset:reportDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"updateType\": {\n          \"@id\": \"factset:updateType\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"Fundamental\": {\n      \"@id\": \"factset:Fundamental\",\n      \"@context\": {\n        \"requestId\": {\n          \"@id\": \"factset:requestId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"fsymId\":\
  \ {\n          \"@id\": \"factset:fsymId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"metric\": {\n          \"@id\": \"factset:metric\",\n          \"@type\": \"xsd:string\"\n        },\n        \"value\": {\n          \"@id\": \"schema:value\"\n        }\n      }\n    },\n\n    \"financialStatements\": {\n      \"@id\": \"factset:financialStatements\"\n    },\n    \"incomeStatement\": {\n      \"@id\": \"factset:incomeStatement\",\n      \"@type\": \"@id\"\n    },\n    \"balanceSheet\": {\n      \"@id\": \"factset:balanceSheet\",\n      \"@type\": \"@id\"\n    },\n    \"cashFlowStatement\": {\n      \"@id\": \"factset:cashFlowStatement\",\n      \"@type\": \"@id\"\n    },\n    \"ratios\": {\n      \"@id\": \"factset:ratios\",\n      \"@type\": \"@id\"\n    },\n    \"estimates\": {\n      \"@id\": \"factset:estimates\",\n      \"@type\": \"@id\"\n    },\n    \"segments\": {\n      \"@id\": \"factset:segments\"\n    },\n    \"metadata\": {\n      \"@id\": \"factset:metadata\"\
  ,\n      \"@type\": \"@id\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/factset/refs/heads/main/json-ld/factset-context.jsonld
tags:
- Financial
- Financial Data
- Investment Analytics
- Market Data
- Portfolio Analytics
- Research
- JSON-LD
- Linked Data
- Semantic Web
---
