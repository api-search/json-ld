---
api_specs:
- filename: 1factory-openapi.json
  format: json
  label: 1Factory API
  slug: 1factory
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/1factory/refs/heads/main/openapi/1factory-openapi.json
class_count: 29
classes:
- Address
- AssemblyEntry
- Assembly
- Capa
- Certification
- Complaint
- FaiDetail
- Fai
- InspectionDetail
- Inspection
- Issue
- Ncr
- NewFai
- NewInspection
- NewPartMaster
- PartData
- PartMaster
- PlanDetail
- Plan
- Qualification
- SpecInspectionType
- Specification
- SuperInspection
- Supplier
- User
- description
- email
- name
- version
context_file: json-ld/1factory-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/1factory/refs/heads/main/json-ld/1factory-context.jsonld
description: JSON-LD context defining the semantic vocabulary for 1Factory from 1Factory.
layout: jsonld
name: 1Factory Context
namespaces:
- prefix: factory
  uri: https://1factory.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: ID
  type: string
- container: ''
  name: address
  type: string
- container: ''
  name: altPartNumber
  type: string
- container: ''
  name: altPartNumber2
  type: string
- container: ''
  name: altRev
  type: string
- container: ''
  name: altRev2
  type: string
- container: ''
  name: approvalStatus
  type: string
- container: ''
  name: blnNo
  type: string
- container: ''
  name: bonus
  type: decimal
- container: ''
  name: bonusTolerance
  type: string
- container: ''
  name: causedBy
  type: string
- container: ''
  name: certification
  type: string
- container: set
  name: certifications
  type: string
- container: ''
  name: characteristic
  type: string
- container: ''
  name: characteristicType
  type: string
- container: ''
  name: city
  type: string
- container: ''
  name: closedOn
  type: string
- container: ''
  name: comments
  type: string
- container: set
  name: commodityCodes
  type: string
- container: set
  name: componentParts
  type: string
- container: ''
  name: cost
  type: double
- container: ''
  name: country
  type: string
- container: ''
  name: createdByName
  type: string
- container: ''
  name: createdOn
  type: string
- container: ''
  name: customerIdent
  type: string
- container: ''
  name: customerName
  type: string
- container: ''
  name: dataType
  type: string
- container: ''
  name: date
  type: dateTime
- container: ''
  name: defectiveQuantity
  type: decimal
- container: ''
  name: descriptorDatum
  type: string
- container: ''
  name: detectedAt
  type: string
- container: ''
  name: dimensionType
  type: string
- container: ''
  name: direct
  type: boolean
- container: ''
  name: expirationDate
  type: dateTime
- container: ''
  name: faiType
  type: string
- container: ''
  name: frequency
  type: integer
- container: ''
  name: grpIdent
  type: string
- container: ''
  name: hasPpap
  type: boolean
- container: ''
  name: id
  type: integer
- container: ''
  name: impact
  type: string
- container: ''
  name: inSpecPct
  type: double
- container: ''
  name: indirect
  type: boolean
- container: ''
  name: inspIdent1
  type: string
- container: ''
  name: inspIdent2
  type: string
- container: ''
  name: inspIdent3
  type: string
- container: ''
  name: inspectedByName
  type: string
- container: ''
  name: inspectedOn
  type: dateTime
- container: ''
  name: inspectionMethod
  type: string
- container: ''
  name: inspectionQuantity
  type: decimal
- container: ''
  name: inspectionStatus
  type: string
- container: ''
  name: inspectionType
  type: string
- container: ''
  name: isAssembly
  type: boolean
- container: ''
  name: isBuy
  type: boolean
- container: ''
  name: isItar
  type: boolean
- container: ''
  name: isKey
  type: boolean
- container: ''
  name: isLibrary
  type: boolean
- container: ''
  name: isSpecLib
  type: boolean
- container: ''
  name: isTabulated
  type: boolean
- container: ''
  name: label
  type: string
- container: ''
  name: lastQualificationDate
  type: dateTime
- container: ''
  name: lotQuantity
  type: decimal
- container: ''
  name: lotSize
  type: string
- container: ''
  name: lowerSpecLimit
  type: decimal
- container: ''
  name: machines
  type: string
- container: set
  name: measurements
  type: reference
- container: ''
  name: mfgInspIdent1
  type: string
- container: ''
  name: mfgInspIdent2
  type: string
- container: ''
  name: ncrCount
  type: decimal
- container: set
  name: ncrs
  type: string
- container: ''
  name: nominal
  type: decimal
- container: ''
  name: notes
  type: string
- container: ''
  name: number
  type: decimal
- container: ''
  name: numberOfParts
  type: string
- container: ''
  name: operation
  type: string
- container: set
  name: organizationCodes
  type: string
- container: ''
  name: owner
  type: string
- container: ''
  name: parentPartNumber
  type: string
- container: ''
  name: parentRev
  type: string
- container: ''
  name: partDescription
  type: string
- container: ''
  name: partNumber
  type: string
- container: ''
  name: partsFailed
  type: string
- container: ''
  name: partsPassed
  type: string
- container: ''
  name: place
  type: integer
- container: ''
  name: planCount
  type: decimal
- container: ''
  name: postalCode
  type: string
- container: ''
  name: problemSummary
  type: string
- container: ''
  name: problemType
  type: string
- container: ''
  name: projectIdentifier
  type: string
- container: ''
  name: purchasing
  type: string
- container: ''
  name: qualificationStatus
  type: string
- container: set
  name: qualifications
  type: string
- container: ''
  name: quantity
  type: decimal
- container: ''
  name: reQualificationDate
  type: dateTime
- container: ''
  name: recInspIdent1
  type: string
- container: ''
  name: recInspIdent2
  type: string
- container: ''
  name: referencedFeature
  type: string
- container: ''
  name: rev
  type: string
- container: ''
  name: reviewStatus
  type: string
- container: ''
  name: reviewedByName
  type: string
- container: ''
  name: reviewedOn
  type: dateTime
- container: ''
  name: rootCause
  type: string
- container: ''
  name: rowIdent
  type: string
- container: ''
  name: samplingRule
  type: string
- container: ''
  name: sheetZone
  type: string
- container: ''
  name: site
  type: string
- container: ''
  name: smallBusiness
  type: boolean
- container: set
  name: specifications
  type: string
- container: ''
  name: state
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: strategic
  type: boolean
- container: ''
  name: street
  type: string
- container: ''
  name: subParts
  type: string
- container: ''
  name: supplierIdent
  type: string
- container: ''
  name: supplierName
  type: string
- container: ''
  name: supplierNumber
  type: string
- container: ''
  name: supplierQualityManager
  type: string
- container: ''
  name: supplyChainManager
  type: string
- container: ''
  name: taskCount
  type: decimal
- container: ''
  name: taskStatus
  type: string
- container: ''
  name: totalCost
  type: decimal
- container: ''
  name: type
  type: string
- container: ''
  name: unit
  type: string
- container: ''
  name: updatedOn
  type: string
- container: ''
  name: upperSpecLimit
  type: decimal
- container: ''
  name: value
  type: decimal
- container: ''
  name: vendorCode
  type: string
- container: ''
  name: versionStatus
  type: string
property_count: 127
provider_name: 1Factory
provider_slug: 1factory
slug: 1factory-context
source_filename: 1factory-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"factory\": \"https://1factory.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Address\": \"factory:Address\",\n    \"AssemblyEntry\": \"factory:AssemblyEntry\",\n    \"Assembly\": \"factory:Assembly\",\n    \"Capa\": \"factory:Capa\",\n    \"Certification\": \"factory:Certification\",\n    \"Complaint\": \"factory:Complaint\",\n    \"FaiDetail\": \"factory:FaiDetail\",\n    \"Fai\": \"factory:Fai\",\n    \"InspectionDetail\": \"factory:InspectionDetail\",\n    \"Inspection\": \"factory:Inspection\",\n    \"Issue\": \"factory:Issue\",\n    \"Ncr\": \"factory:Ncr\",\n    \"NewFai\": \"factory:NewFai\",\n    \"NewInspection\": \"factory:NewInspection\",\n    \"NewPartMaster\": \"factory:NewPartMaster\",\n    \"PartData\": \"factory:PartData\",\n    \"PartMaster\": \"factory:PartMaster\",\n    \"PlanDetail\": \"\
  factory:PlanDetail\",\n    \"Plan\": \"factory:Plan\",\n    \"Qualification\": \"factory:Qualification\",\n    \"SpecInspectionType\": \"factory:SpecInspectionType\",\n    \"Specification\": \"factory:Specification\",\n    \"SuperInspection\": \"factory:SuperInspection\",\n    \"Supplier\": \"factory:Supplier\",\n    \"User\": \"factory:User\",\n    \"ID\": {\n      \"@id\": \"factory:ID\",\n      \"@type\": \"xsd:string\"\n    },\n    \"address\": {\n      \"@id\": \"factory:address\",\n      \"@type\": \"xsd:string\"\n    },\n    \"altPartNumber\": {\n      \"@id\": \"factory:alt_part_number\",\n      \"@type\": \"xsd:string\"\n    },\n    \"altPartNumber2\": {\n      \"@id\": \"factory:alt_part_number2\",\n      \"@type\": \"xsd:string\"\n    },\n    \"altRev\": {\n      \"@id\": \"factory:alt_rev\",\n      \"@type\": \"xsd:string\"\n    },\n    \"altRev2\": {\n      \"@id\": \"factory:alt_rev2\",\n      \"@type\": \"xsd:string\"\n    },\n    \"approvalStatus\": {\n      \"@id\": \"\
  factory:approval_status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"blnNo\": {\n      \"@id\": \"factory:bln_no\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bonus\": {\n      \"@id\": \"factory:bonus\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"bonusTolerance\": {\n      \"@id\": \"factory:bonus_tolerance\",\n      \"@type\": \"xsd:string\"\n    },\n    \"causedBy\": {\n      \"@id\": \"factory:caused_by\",\n      \"@type\": \"xsd:string\"\n    },\n    \"certification\": {\n      \"@id\": \"factory:certification\",\n      \"@type\": \"xsd:string\"\n    },\n    \"certifications\": {\n      \"@id\": \"factory:certifications\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"characteristic\": {\n      \"@id\": \"factory:characteristic\",\n      \"@type\": \"xsd:string\"\n    },\n    \"characteristicType\": {\n      \"@id\": \"factory:characteristic_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"city\": {\n      \"@id\": \"factory:city\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"closedOn\": {\n      \"@id\": \"factory:closed_on\",\n      \"@type\": \"xsd:string\"\n    },\n    \"comments\": {\n      \"@id\": \"factory:comments\",\n      \"@type\": \"xsd:string\"\n    },\n    \"commodityCodes\": {\n      \"@id\": \"factory:commodity_codes\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"componentParts\": {\n      \"@id\": \"factory:component_parts\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cost\": {\n      \"@id\": \"factory:cost\",\n      \"@type\": \"xsd:double\"\n    },\n    \"country\": {\n      \"@id\": \"factory:country\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdByName\": {\n      \"@id\": \"factory:created_by_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdOn\": {\n      \"@id\": \"factory:created_on\",\n      \"@type\": \"xsd:string\"\n    },\n    \"customerIdent\": {\n      \"@id\": \"factory:customer_ident\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"customerName\": {\n      \"@id\": \"factory:customer_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dataType\": {\n      \"@id\": \"factory:data_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"date\": {\n      \"@id\": \"factory:date\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"defectiveQuantity\": {\n      \"@id\": \"factory:defective_quantity\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"description\": \"schema:description\",\n    \"descriptorDatum\": {\n      \"@id\": \"factory:descriptor_datum\",\n      \"@type\": \"xsd:string\"\n    },\n    \"detectedAt\": {\n      \"@id\": \"factory:detected_at\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dimensionType\": {\n      \"@id\": \"factory:dimension_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"direct\": {\n      \"@id\": \"factory:direct\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"email\": \"schema:email\",\n    \"expirationDate\":\
  \ {\n      \"@id\": \"factory:expiration_date\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"faiType\": {\n      \"@id\": \"factory:fai_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"frequency\": {\n      \"@id\": \"factory:frequency\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"grpIdent\": {\n      \"@id\": \"factory:grp_ident\",\n      \"@type\": \"xsd:string\"\n    },\n    \"hasPpap\": {\n      \"@id\": \"factory:has_ppap\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"id\": {\n      \"@id\": \"factory:id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"impact\": {\n      \"@id\": \"factory:impact\",\n      \"@type\": \"xsd:string\"\n    },\n    \"inSpecPct\": {\n      \"@id\": \"factory:in_spec_pct\",\n      \"@type\": \"xsd:double\"\n    },\n    \"indirect\": {\n      \"@id\": \"factory:indirect\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"inspIdent1\": {\n      \"@id\": \"factory:insp_ident_1\",\n      \"@type\": \"xsd:string\"\n    },\n    \"inspIdent2\"\
  : {\n      \"@id\": \"factory:insp_ident_2\",\n      \"@type\": \"xsd:string\"\n    },\n    \"inspIdent3\": {\n      \"@id\": \"factory:insp_ident_3\",\n      \"@type\": \"xsd:string\"\n    },\n    \"inspectedByName\": {\n      \"@id\": \"factory:inspected_by_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"inspectedOn\": {\n      \"@id\": \"factory:inspected_on\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"inspectionMethod\": {\n      \"@id\": \"factory:inspection_method\",\n      \"@type\": \"xsd:string\"\n    },\n    \"inspectionQuantity\": {\n      \"@id\": \"factory:inspection_quantity\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"inspectionStatus\": {\n      \"@id\": \"factory:inspection_status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"inspectionType\": {\n      \"@id\": \"factory:inspection_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isAssembly\": {\n      \"@id\": \"factory:is_assembly\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"\
  isBuy\": {\n      \"@id\": \"factory:is_buy\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isItar\": {\n      \"@id\": \"factory:is_itar\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isKey\": {\n      \"@id\": \"factory:is_key\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isLibrary\": {\n      \"@id\": \"factory:is_library\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isSpecLib\": {\n      \"@id\": \"factory:is_spec_lib\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isTabulated\": {\n      \"@id\": \"factory:is_tabulated\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"label\": {\n      \"@id\": \"factory:label\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastQualificationDate\": {\n      \"@id\": \"factory:last_qualification_date\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"lotQuantity\": {\n      \"@id\": \"factory:lot_quantity\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"lotSize\": {\n      \"@id\": \"factory:lot_size\",\n      \"\
  @type\": \"xsd:string\"\n    },\n    \"lowerSpecLimit\": {\n      \"@id\": \"factory:lower_spec_limit\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"machines\": {\n      \"@id\": \"factory:machines\",\n      \"@type\": \"xsd:string\"\n    },\n    \"measurements\": {\n      \"@id\": \"factory:measurements\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"mfgInspIdent1\": {\n      \"@id\": \"factory:mfg_insp_ident_1\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mfgInspIdent2\": {\n      \"@id\": \"factory:mfg_insp_ident_2\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"ncrCount\": {\n      \"@id\": \"factory:ncr_count\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"ncrs\": {\n      \"@id\": \"factory:ncrs\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nominal\": {\n      \"@id\": \"factory:nominal\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"notes\": {\n      \"@id\": \"\
  factory:notes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"number\": {\n      \"@id\": \"factory:number\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"numberOfParts\": {\n      \"@id\": \"factory:number_of_parts\",\n      \"@type\": \"xsd:string\"\n    },\n    \"operation\": {\n      \"@id\": \"factory:operation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"organizationCodes\": {\n      \"@id\": \"factory:organization_codes\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"owner\": {\n      \"@id\": \"factory:owner\",\n      \"@type\": \"xsd:string\"\n    },\n    \"parentPartNumber\": {\n      \"@id\": \"factory:parent_part_number\",\n      \"@type\": \"xsd:string\"\n    },\n    \"parentRev\": {\n      \"@id\": \"factory:parent_rev\",\n      \"@type\": \"xsd:string\"\n    },\n    \"partDescription\": {\n      \"@id\": \"factory:part_description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"partNumber\": {\n      \"@id\": \"factory:part_number\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"partsFailed\": {\n      \"@id\": \"factory:parts_failed\",\n      \"@type\": \"xsd:string\"\n    },\n    \"partsPassed\": {\n      \"@id\": \"factory:parts_passed\",\n      \"@type\": \"xsd:string\"\n    },\n    \"place\": {\n      \"@id\": \"factory:place\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"planCount\": {\n      \"@id\": \"factory:plan_count\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"postalCode\": {\n      \"@id\": \"factory:postal_code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"problemSummary\": {\n      \"@id\": \"factory:problem_summary\",\n      \"@type\": \"xsd:string\"\n    },\n    \"problemType\": {\n      \"@id\": \"factory:problem_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"projectIdentifier\": {\n      \"@id\": \"factory:project_identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"purchasing\": {\n      \"@id\": \"factory:purchasing\",\n      \"@type\": \"xsd:string\"\n  \
  \  },\n    \"qualificationStatus\": {\n      \"@id\": \"factory:qualification_status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"qualifications\": {\n      \"@id\": \"factory:qualifications\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"quantity\": {\n      \"@id\": \"factory:quantity\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"reQualificationDate\": {\n      \"@id\": \"factory:re_qualification_date\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"recInspIdent1\": {\n      \"@id\": \"factory:rec_insp_ident_1\",\n      \"@type\": \"xsd:string\"\n    },\n    \"recInspIdent2\": {\n      \"@id\": \"factory:rec_insp_ident_2\",\n      \"@type\": \"xsd:string\"\n    },\n    \"referencedFeature\": {\n      \"@id\": \"factory:referenced_feature\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rev\": {\n      \"@id\": \"factory:rev\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reviewStatus\": {\n      \"@id\": \"factory:review_status\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"reviewedByName\": {\n      \"@id\": \"factory:reviewed_by_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reviewedOn\": {\n      \"@id\": \"factory:reviewed_on\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"rootCause\": {\n      \"@id\": \"factory:root_cause\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rowIdent\": {\n      \"@id\": \"factory:row_ident\",\n      \"@type\": \"xsd:string\"\n    },\n    \"samplingRule\": {\n      \"@id\": \"factory:sampling_rule\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sheetZone\": {\n      \"@id\": \"factory:sheet_zone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"site\": {\n      \"@id\": \"factory:site\",\n      \"@type\": \"xsd:string\"\n    },\n    \"smallBusiness\": {\n      \"@id\": \"factory:small_business\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"specifications\": {\n      \"@id\": \"factory:specifications\",\n      \"@container\": \"@set\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"state\": {\n      \"@id\": \"factory:state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"factory:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"strategic\": {\n      \"@id\": \"factory:strategic\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"street\": {\n      \"@id\": \"factory:street\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subParts\": {\n      \"@id\": \"factory:sub_parts\",\n      \"@type\": \"xsd:string\"\n    },\n    \"supplierIdent\": {\n      \"@id\": \"factory:supplier_ident\",\n      \"@type\": \"xsd:string\"\n    },\n    \"supplierName\": {\n      \"@id\": \"factory:supplier_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"supplierNumber\": {\n      \"@id\": \"factory:supplier_number\",\n      \"@type\": \"xsd:string\"\n    },\n    \"supplierQualityManager\": {\n      \"@id\": \"factory:supplier_quality_manager\",\n      \"@type\": \"xsd:string\"\n    },\n    \"supplyChainManager\"\
  : {\n      \"@id\": \"factory:supply_chain_manager\",\n      \"@type\": \"xsd:string\"\n    },\n    \"taskCount\": {\n      \"@id\": \"factory:task_count\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"taskStatus\": {\n      \"@id\": \"factory:task_status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"totalCost\": {\n      \"@id\": \"factory:total_cost\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"type\": {\n      \"@id\": \"factory:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"unit\": {\n      \"@id\": \"factory:unit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"updatedOn\": {\n      \"@id\": \"factory:updated_on\",\n      \"@type\": \"xsd:string\"\n    },\n    \"upperSpecLimit\": {\n      \"@id\": \"factory:upper_spec_limit\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"value\": {\n      \"@id\": \"factory:value\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"vendorCode\": {\n      \"@id\": \"factory:vendor_code\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"version\": \"schema:version\",\n    \"versionStatus\": {\n      \"@id\": \"factory:version_status\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/1factory/refs/heads/main/json-ld/1factory-context.jsonld
tags:
- Analytics
- Data Collection
- Manufacturing
- Monitoring
- Quality
- JSON-LD
- Linked Data
- Semantic Web
---
