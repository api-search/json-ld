---
api_specs:
- filename: the-racing-api-openapi.yml
  format: yaml
  label: The Racing API
  slug: the-racing-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/the-racing-api/refs/heads/main/openapi/the-racing-api-openapi.yml
class_count: 124
classes:
- JockeyTrainerAnalysis
- app__models__sires__Distance
- RacecardsOddsPage
- TrainerJockeyAnalysis
- DamClassAnalysis
- HorsePro
- MeetRaces
- app__models__courses__Course
- app__models__jockeys__Jockey
- Trainers
- app__models__dams__Distance
- app__models__owners__Trainer
- app__models__na_entries__Weather
- OddsNoHistory
- JockeyCourseAnalysis
- Change
- app__models__trainers__Jockey
- app__models__owners__Owner
- app__models__owners__Course
- RunnerMedical
- app__models__na_results__Runner
- Distances
- RacecardsSummary
- TrainerDistanceAnalysis
- ResultsStandardPage
- JockeyDistanceAnalysis
- app__models__na_meets__Meets
- app__models__jockeys__Distance
- Dam
- RacecardSummary
- app__models__na_entries__Runner
- TimesGoing
- app__models__aus_races__Runner
- Results
- app__models__trainers__Trainer
- RunnerStableTour
- Racecard
- TrainerHorseAgeAnalysis
- TimeData
- ResultFree
- app__models__racecards__RunnerOdds
- RaceKey
- HorseDistanceTimeAnalysis
- RunnerQuote
- RacePool
- Jockeys
- RacecardOddsPro
- WagerType
- TrainerOwnerAnalysis
- RaceRunnerOdds
- JockeyOwnerAnalysis
- app__models__na_meets__Meet
- app__models__jockeys__Trainer
- TrainerCourseAnalysis
- ResultsBasicPage
- Horse
- DamDistanceAnalysis
- RacecardBasic
- app__models__racecards__RunnerBasic
- app__models__trainers__Course
- app__models__owners__Jockey
- ResultStandard
- app__models__damsires__Distance
- app__models__jockeys__Course
- OwnerDistanceAnalysis
- HorseAges
- app__models__dams__Class
- app__models__racecards__Runner
- DamsireClassAnalysis
- app__models__na_entries__Race
- app__models__na_entries__Jockey
- Sires
- OwnerJockeyAnalysis
- ResultsFreePage
- app__models__owners__Distance
- Horses
- app__models__sires__Class
- RaceRunnerOddsBookmakers
- CoursesPage
- app__models__trainers__Distance
- Damsire
- app__models__aus_races__RunnerOdds
- Dams
- Payoff
- RunnerStandard
- app__models__jockeys__Owner
- Entries
- DamsireDistanceAnalysis
- SireClassAnalysis
- app__models__damsires__Class
- Sire
- app__models__na_entries__Trainer
- RunnerStats
- app__models__trainers__Owner
- OddsHistory
- HorsePool
- SireDistanceAnalysis
- app__models__aus_meets__Meet
- app__models__na_results__Weather
- app__models__na_results__Race
- OwnerTrainerAnalysis
- RunnerPrevTrainer
- RunnerOddsPro
- RacecardsPage
- RaceRunnerOddsHistory
- RunnerTrainer14Days
- app__models__aus_races__Race
- RunnerStatsBreakdown
- ResultBasic
- RunnerPrevOwner
- RacecardOdds
- Region
- RacecardsBasicPage
- RacecardsOddsProPage
- app__models__aus_meets__Meets
- Fraction
- app__models__result__RunnerBasic
- OwnerCourseAnalysis
- Races
- Damsires
- RunnerFree
- Owners
- name
- description
context_file: json-ld/the-racing-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/the-racing-api/refs/heads/main/json-ld/the-racing-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for The Racing Api from The Racing API.
layout: jsonld
name: The Racing Api Context
namespaces:
- prefix: racing
  uri: https://api.theracingapi.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: id
  type: string
- container: ''
  name: jockey
  type: string
- container: ''
  name: totalRides
  type: integer
- container: set
  name: trainers
  type: string
- container: set
  name: query
  type: string
- container: ''
  name: dist
  type: string
- container: ''
  name: distY
  type: string
- container: ''
  name: distM
  type: string
- container: ''
  name: distF
  type: string
- container: ''
  name: runners
  type: integer
- container: ''
  name: 1st
  type: integer
- container: ''
  name: 2nd
  type: integer
- container: ''
  name: 3rd
  type: integer
- container: ''
  name: 4th
  type: integer
- container: ''
  name: a/e
  type: decimal
- container: ''
  name: win%
  type: decimal
- container: ''
  name: 1Pl
  type: decimal
- container: set
  name: racecards
  type: string
- container: ''
  name: total
  type: integer
- container: ''
  name: limit
  type: integer
- container: ''
  name: skip
  type: integer
- container: ''
  name: trainer
  type: string
- container: ''
  name: totalRunners
  type: integer
- container: set
  name: jockeys
  type: string
- container: ''
  name: dam
  type: string
- container: set
  name: classes
  type: string
- container: ''
  name: breeder
  type: string
- container: ''
  name: colour
  type: string
- container: ''
  name: colourCode
  type: string
- container: ''
  name: damId
  type: string
- container: ''
  name: damsire
  type: string
- container: ''
  name: damsireId
  type: string
- container: ''
  name: dob
  type: string
- container: ''
  name: sex
  type: string
- container: ''
  name: sexCode
  type: string
- container: ''
  name: sire
  type: string
- container: ''
  name: sireId
  type: string
- container: ''
  name: distance
  type: string
- container: ''
  name: class
  type: string
- container: ''
  name: raceGroup
  type: string
- container: ''
  name: raceName
  type: string
- container: ''
  name: raceNumber
  type: string
- container: ''
  name: raceStatus
  type: string
- container: ''
  name: offTime
  type: string
- container: ''
  name: course
  type: string
- container: ''
  name: regionCode
  type: string
- container: ''
  name: region
  type: string
- container: set
  name: searchResults
  type: string
- container: ''
  name: trainerId
  type: string
- container: ''
  name: forecastWeatherDescription
  type: string
- container: ''
  name: forecastHigh
  type: string
- container: ''
  name: forecastLow
  type: string
- container: ''
  name: forecastPrecipitation
  type: string
- container: ''
  name: currentWeatherDescription
  type: string
- container: ''
  name: bookmaker
  type: string
- container: ''
  name: fractional
  type: string
- container: ''
  name: decimal
  type: string
- container: ''
  name: ewPlaces
  type: string
- container: ''
  name: ewDenom
  type: string
- container: ''
  name: updated
  type: string
- container: set
  name: courses
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: text
  type: string
- container: ''
  name: jockeyId
  type: string
- container: ''
  name: courseId
  type: string
- container: ''
  name: date
  type: string
- container: ''
  name: breederName
  type: string
- container: ''
  name: horseName
  type: string
- container: ''
  name: jockeyFirstName
  type: string
- container: ''
  name: jockeyFirstNameInitial
  type: string
- container: ''
  name: jockeyLastName
  type: string
- container: ''
  name: ownerFirstName
  type: string
- container: ''
  name: ownerLastName
  type: string
- container: ''
  name: placePayoff
  type: string
- container: ''
  name: programNumber
  type: string
- container: ''
  name: programNumberStripped
  type: string
- container: ''
  name: showPayoff
  type: string
- container: ''
  name: sireName
  type: string
- container: ''
  name: trainerFirstName
  type: string
- container: ''
  name: trainerLastName
  type: string
- container: ''
  name: weightCarried
  type: string
- container: ''
  name: winPayoff
  type: string
- container: set
  name: times
  type: string
- container: ''
  name: runs
  type: integer
- container: set
  name: racecardSummaries
  type: string
- container: set
  name: distances
  type: string
- container: ''
  name: results
  type: string
- container: ''
  name: meets
  type: string
- container: ''
  name: rides
  type: integer
- container: ''
  name: raceId
  type: string
- container: ''
  name: raceClass
  type: string
- container: ''
  name: offDt
  type: string
- container: ''
  name: bigRace
  type: string
- container: ''
  name: isAbandoned
  type: string
- container: ''
  name: claiming
  type: string
- container: ''
  name: coupledType
  type: string
- container: ''
  name: damName
  type: string
- container: ''
  name: damSireName
  type: string
- container: ''
  name: equipment
  type: string
- container: ''
  name: handicapperName
  type: string
- container: ''
  name: horseDataPools
  type: string
- container: ''
  name: liveOdds
  type: string
- container: ''
  name: medication
  type: string
- container: ''
  name: morningLineOdds
  type: string
- container: ''
  name: postPos
  type: string
- container: ''
  name: registrationNumber
  type: string
- container: ''
  name: scratchIndicator
  type: string
- container: ''
  name: weight
  type: string
- container: ''
  name: time
  type: string
- container: ''
  name: going
  type: string
- container: ''
  name: position
  type: string
- container: ''
  name: horseId
  type: string
- container: ''
  name: horse
  type: string
- container: ''
  name: age
  type: string
- container: ''
  name: comment
  type: string
- container: ''
  name: draw
  type: string
- container: ''
  name: form
  type: string
- container: ''
  name: jockeyClaim
  type: string
- container: ''
  name: margin
  type: string
- container: ''
  name: number
  type: string
- container: ''
  name: odds
  type: string
- container: ''
  name: owner
  type: string
- container: ''
  name: prize
  type: string
- container: ''
  name: rating
  type: string
- container: ''
  name: scratched
  type: string
- container: ''
  name: silkUrl
  type: string
- container: ''
  name: sp
  type: string
- container: ''
  name: stats
  type: string
- container: ''
  name: meetId
  type: string
- container: ''
  name: trackId
  type: string
- container: ''
  name: trackName
  type: string
- container: ''
  name: country
  type: string
- container: ''
  name: races
  type: string
- container: ''
  name: weather
  type: string
- container: ''
  name: quote
  type: string
- container: ''
  name: distanceRound
  type: string
- container: ''
  name: distanceF
  type: string
- container: ''
  name: pattern
  type: string
- container: ''
  name: sexRestriction
  type: string
- container: ''
  name: ageBand
  type: string
- container: ''
  name: ratingBand
  type: string
- container: ''
  name: fieldSize
  type: string
- container: ''
  name: goingDetailed
  type: string
- container: ''
  name: railMovements
  type: string
- container: ''
  name: stalls
  type: string
- container: ''
  name: surface
  type: string
- container: set
  name: horseAges
  type: string
- container: ''
  name: minutes
  type: string
- container: ''
  name: seconds
  type: string
- container: ''
  name: hundredths
  type: string
- container: ''
  name: milliseconds
  type: string
- container: ''
  name: fifths
  type: string
- container: ''
  name: strFifths
  type: string
- container: ''
  name: timeInFifths
  type: string
- container: ''
  name: timeInHundredths
  type: string
- container: ''
  name: 'off'
  type: string
- container: ''
  name: sexRest
  type: string
- container: ''
  name: damRegion
  type: string
- container: ''
  name: sireRegion
  type: string
- container: ''
  name: damsireRegion
  type: string
- container: ''
  name: trainerLocation
  type: string
- container: ''
  name: trainer14Days
  type: string
- container: ''
  name: ownerId
  type: string
- container: ''
  name: prevTrainers
  type: string
- container: ''
  name: prevOwners
  type: string
- container: ''
  name: spotlight
  type: string
- container: ''
  name: quotes
  type: string
- container: ''
  name: stableTour
  type: string
- container: ''
  name: medical
  type: string
- container: ''
  name: headgear
  type: string
- container: ''
  name: headgearRun
  type: string
- container: ''
  name: windSurgery
  type: string
- container: ''
  name: windSurgeryRun
  type: string
- container: ''
  name: pastResultsFlags
  type: string
- container: ''
  name: lbs
  type: string
- container: ''
  name: ofr
  type: string
- container: ''
  name: rpr
  type: string
- container: ''
  name: ts
  type: string
- container: ''
  name: lastRun
  type: string
- container: ''
  name: trainerRtf
  type: string
- container: ''
  name: dayEvening
  type: string
- container: ''
  name: totalRuns
  type: integer
- container: ''
  name: race
  type: string
- container: ''
  name: distanceY
  type: string
- container: ''
  name: maximumWagerAmount
  type: string
- container: ''
  name: minimumBoxAmount
  type: string
- container: ''
  name: minimumWagerAmount
  type: string
- container: ''
  name: minimumWheelAmount
  type: string
- container: ''
  name: poolCode
  type: string
- container: ''
  name: poolName
  type: string
- container: ''
  name: raceList
  type: string
- container: ''
  name: jumps
  type: string
- container: ''
  name: tip
  type: string
- container: ''
  name: verdict
  type: string
- container: ''
  name: bettingForecast
  type: string
- container: ''
  name: wagerType
  type: string
- container: ''
  name: wagerDescription
  type: string
- container: ''
  name: baseAmount
  type: string
- container: set
  name: owners
  type: string
- container: ''
  name: winningTimeDetail
  type: string
- container: ''
  name: comments
  type: string
- container: ''
  name: nonRunners
  type: string
- container: ''
  name: toteWin
  type: string
- container: ''
  name: totePl
  type: string
- container: ''
  name: toteEx
  type: string
- container: ''
  name: toteCsf
  type: string
- container: ''
  name: toteTricast
  type: string
- container: ''
  name: toteTrifecta
  type: string
- container: ''
  name: horseAge
  type: string
- container: ''
  name: ageRestriction
  type: string
- container: ''
  name: ageRestrictionDescription
  type: string
- container: ''
  name: breed
  type: string
- container: ''
  name: changes
  type: string
- container: ''
  name: courseType
  type: string
- container: ''
  name: courseTypeClass
  type: string
- container: ''
  name: distanceDescription
  type: string
- container: ''
  name: distanceUnit
  type: string
- container: ''
  name: distanceValue
  type: string
- container: ''
  name: grade
  type: string
- container: ''
  name: hasFinished
  type: string
- container: ''
  name: hasResults
  type: string
- container: ''
  name: isCancelled
  type: string
- container: ''
  name: maxClaimPrice
  type: string
- container: ''
  name: minClaimPrice
  type: string
- container: ''
  name: mtp
  type: string
- container: ''
  name: postTime
  type: string
- container: ''
  name: postTimeLong
  type: string
- container: ''
  name: purse
  type: string
- container: ''
  name: raceKey
  type: string
- container: ''
  name: racePools
  type: string
- container: ''
  name: raceRestriction
  type: string
- container: ''
  name: raceRestrictionDescription
  type: string
- container: ''
  name: raceType
  type: string
- container: ''
  name: raceTypeDescription
  type: string
- container: ''
  name: sexRestrictionDescription
  type: string
- container: ''
  name: surfaceDescription
  type: string
- container: ''
  name: timeZone
  type: string
- container: ''
  name: toteTrackId
  type: string
- container: ''
  name: trackCondition
  type: string
- container: ''
  name: alias
  type: string
- container: ''
  name: firstName
  type: string
- container: ''
  name: firstNameInitial
  type: string
- container: ''
  name: lastName
  type: string
- container: ''
  name: middleName
  type: string
- container: ''
  name: history
  type: string
- container: ''
  name: winOdds
  type: string
- container: ''
  name: placeOdds
  type: string
- container: ''
  name: carryover
  type: string
- container: ''
  name: numberOfRights
  type: string
- container: ''
  name: numberOfTicketsBet
  type: string
- container: ''
  name: payoffAmount
  type: string
- container: ''
  name: totalPool
  type: string
- container: ''
  name: wagerName
  type: string
- container: ''
  name: winningNumbers
  type: string
- container: ''
  name: spDec
  type: string
- container: ''
  name: bsp
  type: string
- container: ''
  name: btn
  type: string
- container: ''
  name: ovrBtn
  type: string
- container: ''
  name: weightLbs
  type: string
- container: ''
  name: or
  type: string
- container: ''
  name: tsr
  type: string
- container: ''
  name: jockeyClaimLbs
  type: string
- container: ''
  name: careerPrize
  type: string
- container: ''
  name: careerWinPercent
  type: string
- container: ''
  name: careerPlacePercent
  type: string
- container: ''
  name: courseStats
  type: string
- container: ''
  name: courseDistanceStats
  type: string
- container: ''
  name: distanceStats
  type: string
- container: ''
  name: groundFirmStats
  type: string
- container: ''
  name: groundGoodStats
  type: string
- container: ''
  name: groundHeavyStats
  type: string
- container: ''
  name: groundSoftStats
  type: string
- container: ''
  name: groundAwStats
  type: string
- container: ''
  name: jockeyStats
  type: string
- container: ''
  name: jumpsStats
  type: string
- container: ''
  name: lastRaced
  type: string
- container: ''
  name: lastTenRacesStats
  type: string
- container: ''
  name: lastTwelveMonthsStats
  type: string
- container: ''
  name: lastWon
  type: string
- container: ''
  name: maxWinningDistance
  type: string
- container: ''
  name: minWinningDistance
  type: string
- container: ''
  name: poolTypeName
  type: string
- container: ''
  name: amount
  type: string
- container: ''
  name: fractionalOdds
  type: string
- container: ''
  name: dollar
  type: string
- container: ''
  name: state
  type: string
- container: ''
  name: currentTemperature
  type: string
- container: ''
  name: alsoRan
  type: string
- container: ''
  name: fraction
  type: string
- container: ''
  name: maximumClaimPrice
  type: string
- container: ''
  name: minimumClaimPrice
  type: string
- container: ''
  name: payoffs
  type: string
- container: ''
  name: scratches
  type: string
- container: ''
  name: totalPurse
  type: string
- container: ''
  name: trackConditionDescription
  type: string
- container: ''
  name: wagerTypes
  type: string
- container: ''
  name: changeDate
  type: string
- container: ''
  name: changedAt
  type: string
- container: ''
  name: wins
  type: string
- container: ''
  name: percent
  type: string
- container: ''
  name: isJumpOut
  type: string
- container: ''
  name: isTrial
  type: string
- container: ''
  name: prizes
  type: string
- container: ''
  name: prizeTotal
  type: string
- container: ''
  name: raceConditions
  type: string
- container: ''
  name: winningTime
  type: string
- container: ''
  name: winningTimeHundredths
  type: string
- container: ''
  name: first
  type: string
- container: ''
  name: second
  type: string
- container: ''
  name: third
  type: string
- container: ''
  name: fraction1
  type: string
- container: ''
  name: fraction2
  type: string
- container: ''
  name: fraction3
  type: string
- container: ''
  name: fraction4
  type: string
- container: ''
  name: fraction5
  type: string
property_count: 315
provider_name: The Racing API
provider_slug: the-racing-api
slug: the-racing-api-context
source_filename: the-racing-api-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"racing\": \"https://api.theracingapi.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"JockeyTrainerAnalysis\": \"racing:JockeyTrainerAnalysis\",\n    \"app__models__sires__Distance\": \"racing:app__models__sires__Distance\",\n    \"RacecardsOddsPage\": \"racing:RacecardsOddsPage\",\n    \"TrainerJockeyAnalysis\": \"racing:TrainerJockeyAnalysis\",\n    \"DamClassAnalysis\": \"racing:DamClassAnalysis\",\n    \"HorsePro\": \"racing:HorsePro\",\n    \"MeetRaces\": \"racing:MeetRaces\",\n    \"app__models__courses__Course\": \"racing:app__models__courses__Course\",\n    \"app__models__jockeys__Jockey\": \"racing:app__models__jockeys__Jockey\",\n    \"Trainers\": \"racing:Trainers\",\n    \"app__models__dams__Distance\": \"racing:app__models__dams__Distance\",\n    \"app__models__owners__Trainer\": \"racing:app__models__owners__Trainer\"\
  ,\n    \"app__models__na_entries__Weather\": \"racing:app__models__na_entries__Weather\",\n    \"OddsNoHistory\": \"racing:OddsNoHistory\",\n    \"JockeyCourseAnalysis\": \"racing:JockeyCourseAnalysis\",\n    \"Change\": \"racing:Change\",\n    \"app__models__trainers__Jockey\": \"racing:app__models__trainers__Jockey\",\n    \"app__models__owners__Owner\": \"racing:app__models__owners__Owner\",\n    \"app__models__owners__Course\": \"racing:app__models__owners__Course\",\n    \"RunnerMedical\": \"racing:RunnerMedical\",\n    \"app__models__na_results__Runner\": \"racing:app__models__na_results__Runner\",\n    \"Distances\": \"racing:Distances\",\n    \"RacecardsSummary\": \"racing:RacecardsSummary\",\n    \"TrainerDistanceAnalysis\": \"racing:TrainerDistanceAnalysis\",\n    \"ResultsStandardPage\": \"racing:ResultsStandardPage\",\n    \"JockeyDistanceAnalysis\": \"racing:JockeyDistanceAnalysis\",\n    \"app__models__na_meets__Meets\": \"racing:app__models__na_meets__Meets\",\n    \"app__models__jockeys__Distance\"\
  : \"racing:app__models__jockeys__Distance\",\n    \"Dam\": \"racing:Dam\",\n    \"RacecardSummary\": \"racing:RacecardSummary\",\n    \"app__models__na_entries__Runner\": \"racing:app__models__na_entries__Runner\",\n    \"TimesGoing\": \"racing:TimesGoing\",\n    \"app__models__aus_races__Runner\": \"racing:app__models__aus_races__Runner\",\n    \"Results\": \"racing:Results\",\n    \"app__models__trainers__Trainer\": \"racing:app__models__trainers__Trainer\",\n    \"RunnerStableTour\": \"racing:RunnerStableTour\",\n    \"Racecard\": \"racing:Racecard\",\n    \"TrainerHorseAgeAnalysis\": \"racing:TrainerHorseAgeAnalysis\",\n    \"TimeData\": \"racing:TimeData\",\n    \"ResultFree\": \"racing:ResultFree\",\n    \"app__models__racecards__RunnerOdds\": \"racing:app__models__racecards__RunnerOdds\",\n    \"RaceKey\": \"racing:RaceKey\",\n    \"HorseDistanceTimeAnalysis\": \"racing:HorseDistanceTimeAnalysis\",\n    \"RunnerQuote\": \"racing:RunnerQuote\",\n    \"RacePool\": \"racing:RacePool\"\
  ,\n    \"Jockeys\": \"racing:Jockeys\",\n    \"RacecardOddsPro\": \"racing:RacecardOddsPro\",\n    \"WagerType\": \"racing:WagerType\",\n    \"TrainerOwnerAnalysis\": \"racing:TrainerOwnerAnalysis\",\n    \"RaceRunnerOdds\": \"racing:RaceRunnerOdds\",\n    \"JockeyOwnerAnalysis\": \"racing:JockeyOwnerAnalysis\",\n    \"app__models__na_meets__Meet\": \"racing:app__models__na_meets__Meet\",\n    \"app__models__jockeys__Trainer\": \"racing:app__models__jockeys__Trainer\",\n    \"TrainerCourseAnalysis\": \"racing:TrainerCourseAnalysis\",\n    \"ResultsBasicPage\": \"racing:ResultsBasicPage\",\n    \"Horse\": \"racing:Horse\",\n    \"DamDistanceAnalysis\": \"racing:DamDistanceAnalysis\",\n    \"RacecardBasic\": \"racing:RacecardBasic\",\n    \"app__models__racecards__RunnerBasic\": \"racing:app__models__racecards__RunnerBasic\",\n    \"app__models__trainers__Course\": \"racing:app__models__trainers__Course\",\n    \"app__models__owners__Jockey\": \"racing:app__models__owners__Jockey\",\n  \
  \  \"ResultStandard\": \"racing:ResultStandard\",\n    \"app__models__damsires__Distance\": \"racing:app__models__damsires__Distance\",\n    \"app__models__jockeys__Course\": \"racing:app__models__jockeys__Course\",\n    \"OwnerDistanceAnalysis\": \"racing:OwnerDistanceAnalysis\",\n    \"HorseAges\": \"racing:HorseAges\",\n    \"app__models__dams__Class\": \"racing:app__models__dams__Class\",\n    \"app__models__racecards__Runner\": \"racing:app__models__racecards__Runner\",\n    \"DamsireClassAnalysis\": \"racing:DamsireClassAnalysis\",\n    \"app__models__na_entries__Race\": \"racing:app__models__na_entries__Race\",\n    \"app__models__na_entries__Jockey\": \"racing:app__models__na_entries__Jockey\",\n    \"Sires\": \"racing:Sires\",\n    \"OwnerJockeyAnalysis\": \"racing:OwnerJockeyAnalysis\",\n    \"ResultsFreePage\": \"racing:ResultsFreePage\",\n    \"app__models__owners__Distance\": \"racing:app__models__owners__Distance\",\n    \"Horses\": \"racing:Horses\",\n    \"app__models__sires__Class\"\
  : \"racing:app__models__sires__Class\",\n    \"RaceRunnerOddsBookmakers\": \"racing:RaceRunnerOddsBookmakers\",\n    \"CoursesPage\": \"racing:CoursesPage\",\n    \"app__models__trainers__Distance\": \"racing:app__models__trainers__Distance\",\n    \"Damsire\": \"racing:Damsire\",\n    \"app__models__aus_races__RunnerOdds\": \"racing:app__models__aus_races__RunnerOdds\",\n    \"Dams\": \"racing:Dams\",\n    \"Payoff\": \"racing:Payoff\",\n    \"RunnerStandard\": \"racing:RunnerStandard\",\n    \"app__models__jockeys__Owner\": \"racing:app__models__jockeys__Owner\",\n    \"Entries\": \"racing:Entries\",\n    \"DamsireDistanceAnalysis\": \"racing:DamsireDistanceAnalysis\",\n    \"SireClassAnalysis\": \"racing:SireClassAnalysis\",\n    \"app__models__damsires__Class\": \"racing:app__models__damsires__Class\",\n    \"Sire\": \"racing:Sire\",\n    \"app__models__na_entries__Trainer\": \"racing:app__models__na_entries__Trainer\",\n    \"RunnerStats\": \"racing:RunnerStats\",\n    \"app__models__trainers__Owner\"\
  : \"racing:app__models__trainers__Owner\",\n    \"OddsHistory\": \"racing:OddsHistory\",\n    \"HorsePool\": \"racing:HorsePool\",\n    \"SireDistanceAnalysis\": \"racing:SireDistanceAnalysis\",\n    \"app__models__aus_meets__Meet\": \"racing:app__models__aus_meets__Meet\",\n    \"app__models__na_results__Weather\": \"racing:app__models__na_results__Weather\",\n    \"app__models__na_results__Race\": \"racing:app__models__na_results__Race\",\n    \"OwnerTrainerAnalysis\": \"racing:OwnerTrainerAnalysis\",\n    \"RunnerPrevTrainer\": \"racing:RunnerPrevTrainer\",\n    \"RunnerOddsPro\": \"racing:RunnerOddsPro\",\n    \"RacecardsPage\": \"racing:RacecardsPage\",\n    \"RaceRunnerOddsHistory\": \"racing:RaceRunnerOddsHistory\",\n    \"RunnerTrainer14Days\": \"racing:RunnerTrainer14Days\",\n    \"app__models__aus_races__Race\": \"racing:app__models__aus_races__Race\",\n    \"RunnerStatsBreakdown\": \"racing:RunnerStatsBreakdown\",\n    \"ResultBasic\": \"racing:ResultBasic\",\n    \"RunnerPrevOwner\"\
  : \"racing:RunnerPrevOwner\",\n    \"RacecardOdds\": \"racing:RacecardOdds\",\n    \"Region\": \"racing:Region\",\n    \"RacecardsBasicPage\": \"racing:RacecardsBasicPage\",\n    \"RacecardsOddsProPage\": \"racing:RacecardsOddsProPage\",\n    \"app__models__aus_meets__Meets\": \"racing:app__models__aus_meets__Meets\",\n    \"Fraction\": \"racing:Fraction\",\n    \"app__models__result__RunnerBasic\": \"racing:app__models__result__RunnerBasic\",\n    \"OwnerCourseAnalysis\": \"racing:OwnerCourseAnalysis\",\n    \"Races\": \"racing:Races\",\n    \"Damsires\": \"racing:Damsires\",\n    \"RunnerFree\": \"racing:RunnerFree\",\n    \"Owners\": \"racing:Owners\",\n    \"id\": {\n      \"@id\": \"racing:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"jockey\": {\n      \"@id\": \"racing:jockey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"totalRides\": {\n      \"@id\": \"racing:total_rides\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"trainers\": {\n      \"@id\": \"racing:trainers\"\
  ,\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"query\": {\n      \"@id\": \"racing:query\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dist\": {\n      \"@id\": \"racing:dist\",\n      \"@type\": \"xsd:string\"\n    },\n    \"distY\": {\n      \"@id\": \"racing:dist_y\",\n      \"@type\": \"xsd:string\"\n    },\n    \"distM\": {\n      \"@id\": \"racing:dist_m\",\n      \"@type\": \"xsd:string\"\n    },\n    \"distF\": {\n      \"@id\": \"racing:dist_f\",\n      \"@type\": \"xsd:string\"\n    },\n    \"runners\": {\n      \"@id\": \"racing:runners\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"1st\": {\n      \"@id\": \"racing:1st\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"2nd\": {\n      \"@id\": \"racing:2nd\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"3rd\": {\n      \"@id\": \"racing:3rd\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"4th\": {\n      \"@id\": \"racing:4th\",\n      \"\
  @type\": \"xsd:integer\"\n    },\n    \"a/e\": {\n      \"@id\": \"racing:a/e\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"win%\": {\n      \"@id\": \"racing:win_%\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"1Pl\": {\n      \"@id\": \"racing:1_pl\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"racecards\": {\n      \"@id\": \"racing:racecards\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"total\": {\n      \"@id\": \"racing:total\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"limit\": {\n      \"@id\": \"racing:limit\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"skip\": {\n      \"@id\": \"racing:skip\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"trainer\": {\n      \"@id\": \"racing:trainer\",\n      \"@type\": \"xsd:string\"\n    },\n    \"totalRunners\": {\n      \"@id\": \"racing:total_runners\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"jockeys\": {\n      \"@id\": \"racing:jockeys\",\n      \"@container\"\
  : \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dam\": {\n      \"@id\": \"racing:dam\",\n      \"@type\": \"xsd:string\"\n    },\n    \"classes\": {\n      \"@id\": \"racing:classes\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"breeder\": {\n      \"@id\": \"racing:breeder\",\n      \"@type\": \"xsd:string\"\n    },\n    \"colour\": {\n      \"@id\": \"racing:colour\",\n      \"@type\": \"xsd:string\"\n    },\n    \"colourCode\": {\n      \"@id\": \"racing:colour_code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"damId\": {\n      \"@id\": \"racing:dam_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"damsire\": {\n      \"@id\": \"racing:damsire\",\n      \"@type\": \"xsd:string\"\n    },\n    \"damsireId\": {\n      \"@id\": \"racing:damsire_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dob\": {\n      \"@id\": \"racing:dob\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"sex\": {\n\
  \      \"@id\": \"racing:sex\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sexCode\": {\n      \"@id\": \"racing:sex_code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sire\": {\n      \"@id\": \"racing:sire\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sireId\": {\n      \"@id\": \"racing:sire_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"distance\": {\n      \"@id\": \"racing:distance\",\n      \"@type\": \"xsd:string\"\n    },\n    \"class\": {\n      \"@id\": \"racing:class\",\n      \"@type\": \"xsd:string\"\n    },\n    \"raceGroup\": {\n      \"@id\": \"racing:race_group\",\n      \"@type\": \"xsd:string\"\n    },\n    \"raceName\": {\n      \"@id\": \"racing:race_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"raceNumber\": {\n      \"@id\": \"racing:race_number\",\n      \"@type\": \"xsd:string\"\n    },\n    \"raceStatus\": {\n      \"@id\": \"racing:race_status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"offTime\": {\n      \"@id\": \"racing:off_time\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"course\": {\n      \"@id\": \"racing:course\",\n      \"@type\": \"xsd:string\"\n    },\n    \"regionCode\": {\n      \"@id\": \"racing:region_code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"region\": {\n      \"@id\": \"racing:region\",\n      \"@type\": \"xsd:string\"\n    },\n    \"searchResults\": {\n      \"@id\": \"racing:search_results\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"trainerId\": {\n      \"@id\": \"racing:trainer_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"forecastWeatherDescription\": {\n      \"@id\": \"racing:forecast_weather_description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"forecastHigh\": {\n      \"@id\": \"racing:forecast_high\",\n      \"@type\": \"xsd:string\"\n    },\n    \"forecastLow\": {\n      \"@id\": \"racing:forecast_low\",\n      \"@type\": \"xsd:string\"\n    },\n    \"forecastPrecipitation\": {\n      \"@id\": \"racing:forecast_precipitation\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"currentWeatherDescription\": {\n      \"@id\": \"racing:current_weather_description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bookmaker\": {\n      \"@id\": \"racing:bookmaker\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fractional\": {\n      \"@id\": \"racing:fractional\",\n      \"@type\": \"xsd:string\"\n    },\n    \"decimal\": {\n      \"@id\": \"racing:decimal\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ewPlaces\": {\n      \"@id\": \"racing:ew_places\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ewDenom\": {\n      \"@id\": \"racing:ew_denom\",\n      \"@type\": \"xsd:string\"\n    },\n    \"updated\": {\n      \"@id\": \"racing:updated\",\n      \"@type\": \"xsd:string\"\n    },\n    \"courses\": {\n      \"@id\": \"racing:courses\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"racing:type\",\n      \"@type\": \"xsd:string\"\n    },\n   \
  \ \"text\": {\n      \"@id\": \"racing:text\",\n      \"@type\": \"xsd:string\"\n    },\n    \"jockeyId\": {\n      \"@id\": \"racing:jockey_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"courseId\": {\n      \"@id\": \"racing:course_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"date\": {\n      \"@id\": \"racing:date\",\n      \"@type\": \"xsd:string\"\n    },\n    \"breederName\": {\n      \"@id\": \"racing:breeder_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"horseName\": {\n      \"@id\": \"racing:horse_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"jockeyFirstName\": {\n      \"@id\": \"racing:jockey_first_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"jockeyFirstNameInitial\": {\n      \"@id\": \"racing:jockey_first_name_initial\",\n      \"@type\": \"xsd:string\"\n    },\n    \"jockeyLastName\": {\n      \"@id\": \"racing:jockey_last_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ownerFirstName\": {\n      \"@id\": \"racing:owner_first_name\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"ownerLastName\": {\n      \"@id\": \"racing:owner_last_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"placePayoff\": {\n      \"@id\": \"racing:place_payoff\",\n      \"@type\": \"xsd:string\"\n    },\n    \"programNumber\": {\n      \"@id\": \"racing:program_number\",\n      \"@type\": \"xsd:string\"\n    },\n    \"programNumberStripped\": {\n      \"@id\": \"racing:program_number_stripped\",\n      \"@type\": \"xsd:string\"\n    },\n    \"showPayoff\": {\n      \"@id\": \"racing:show_payoff\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sireName\": {\n      \"@id\": \"racing:sire_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"trainerFirstName\": {\n      \"@id\": \"racing:trainer_first_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"trainerLastName\": {\n      \"@id\": \"racing:trainer_last_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"weightCarried\": {\n      \"@id\": \"racing:weight_carried\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"winPayoff\": {\n      \"@id\": \"racing:win_payoff\",\n      \"@type\": \"xsd:string\"\n    },\n    \"times\": {\n      \"@id\": \"racing:times\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"runs\": {\n      \"@id\": \"racing:runs\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"racecardSummaries\": {\n      \"@id\": \"racing:racecard_summaries\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"distances\": {\n      \"@id\": \"racing:distances\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"results\": {\n      \"@id\": \"racing:results\",\n      \"@type\": \"xsd:string\"\n    },\n    \"meets\": {\n      \"@id\": \"racing:meets\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rides\": {\n      \"@id\": \"racing:rides\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"raceId\": {\n      \"@id\": \"racing:race_id\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"raceClass\": {\n      \"@id\": \"racing:race_class\",\n      \"@type\": \"xsd:string\"\n    },\n    \"offDt\": {\n      \"@id\": \"racing:off_dt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bigRace\": {\n      \"@id\": \"racing:big_race\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isAbandoned\": {\n      \"@id\": \"racing:is_abandoned\",\n      \"@type\": \"xsd:string\"\n    },\n    \"claiming\": {\n      \"@id\": \"racing:claiming\",\n      \"@type\": \"xsd:string\"\n    },\n    \"coupledType\": {\n      \"@id\": \"racing:coupled_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"damName\": {\n      \"@id\": \"racing:dam_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"damSireName\": {\n      \"@id\": \"racing:dam_sire_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\",\n    \"equipment\": {\n      \"@id\": \"racing:equipment\",\n      \"@type\": \"xsd:string\"\n    },\n    \"handicapperName\"\
  : {\n      \"@id\": \"racing:handicapper_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"horseDataPools\": {\n      \"@id\": \"racing:horse_data_pools\",\n      \"@type\": \"xsd:string\"\n    },\n    \"liveOdds\": {\n      \"@id\": \"racing:live_odds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"medication\": {\n      \"@id\": \"racing:medication\",\n      \"@type\": \"xsd:string\"\n    },\n    \"morningLineOdds\": {\n      \"@id\": \"racing:morning_line_odds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"postPos\": {\n      \"@id\": \"racing:post_pos\",\n      \"@type\": \"xsd:string\"\n    },\n    \"registrationNumber\": {\n      \"@id\": \"racing:registration_number\",\n      \"@type\": \"xsd:string\"\n    },\n    \"scratchIndicator\": {\n      \"@id\": \"racing:scratch_indicator\",\n      \"@type\": \"xsd:string\"\n    },\n    \"weight\": {\n      \"@id\": \"racing:weight\",\n      \"@type\": \"xsd:string\"\n    },\n    \"time\": {\n      \"@id\": \"racing:time\",\n\
  \      \"@type\": \"xsd:string\"\n    },\n    \"going\": {\n      \"@id\": \"racing:going\",\n      \"@type\": \"xsd:string\"\n    },\n    \"position\": {\n      \"@id\": \"racing:position\",\n      \"@type\": \"xsd:string\"\n    },\n    \"horseId\": {\n      \"@id\": \"racing:horse_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"horse\": {\n      \"@id\": \"racing:horse\",\n      \"@type\": \"xsd:string\"\n    },\n    \"age\": {\n      \"@id\": \"racing:age\",\n      \"@type\": \"xsd:string\"\n    },\n    \"comment\": {\n      \"@id\": \"racing:comment\",\n      \"@type\": \"xsd:string\"\n    },\n    \"draw\": {\n      \"@id\": \"racing:draw\",\n      \"@type\": \"xsd:string\"\n    },\n    \"form\": {\n      \"@id\": \"racing:form\",\n      \"@type\": \"xsd:string\"\n    },\n    \"jockeyClaim\": {\n      \"@id\": \"racing:jockey_claim\",\n      \"@type\": \"xsd:string\"\n    },\n    \"margin\": {\n      \"@id\": \"racing:margin\",\n      \"@type\": \"xsd:string\"\n    },\n    \"\
  number\": {\n      \"@id\": \"racing:number\",\n      \"@type\": \"xsd:string\"\n    },\n    \"odds\": {\n      \"@id\": \"racing:odds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"owner\": {\n      \"@id\": \"racing:owner\",\n      \"@type\": \"xsd:string\"\n    },\n    \"prize\": {\n      \"@id\": \"racing:prize\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rating\": {\n      \"@id\": \"racing:rating\",\n      \"@type\": \"xsd:string\"\n    },\n    \"scratched\": {\n      \"@id\": \"racing:scratched\",\n      \"@type\": \"xsd:string\"\n    },\n    \"silkUrl\": {\n      \"@id\": \"racing:silk_url\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sp\": {\n      \"@id\": \"racing:sp\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stats\": {\n      \"@id\": \"racing:stats\",\n      \"@type\": \"xsd:string\"\n    },\n    \"meetId\": {\n      \"@id\": \"racing:meet_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"trackId\": {\n      \"@id\": \"racing:track_id\",\n      \"\
  @type\": \"xsd:string\"\n    },\n    \"trackName\": {\n      \"@id\": \"racing:track_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"country\": {\n      \"@id\": \"racing:country\",\n      \"@type\": \"xsd:string\"\n    },\n    \"races\": {\n      \"@id\": \"racing:races\",\n      \"@type\": \"xsd:string\"\n    },\n    \"weather\": {\n      \"@id\": \"racing:weather\",\n      \"@type\": \"xsd:string\"\n    },\n    \"quote\": {\n      \"@id\": \"racing:quote\",\n      \"@type\": \"xsd:string\"\n    },\n    \"distanceRound\": {\n      \"@id\": \"racing:distance_round\",\n      \"@type\": \"xsd:string\"\n    },\n    \"distanceF\": {\n      \"@id\": \"racing:distance_f\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pattern\": {\n      \"@id\": \"racing:pattern\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sexRestriction\": {\n      \"@id\": \"racing:sex_restriction\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ageBand\": {\n      \"@id\": \"racing:age_band\",\n      \"\
  @type\": \"xsd:string\"\n    },\n    \"ratingBand\": {\n      \"@id\": \"racing:rating_band\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fieldSize\": {\n      \"@id\": \"racing:field_size\",\n      \"@type\": \"xsd:string\"\n    },\n    \"goingDetailed\": {\n      \"@id\": \"racing:going_detailed\",\n      \"@type\": \"xsd:string\"\n    },\n    \"railMovements\": {\n      \"@id\": \"racing:rail_movements\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stalls\": {\n      \"@id\": \"racing:stalls\",\n      \"@type\": \"xsd:string\"\n    },\n    \"surface\": {\n      \"@id\": \"racing:surface\",\n      \"@type\": \"xsd:string\"\n    },\n    \"horseAges\": {\n      \"@id\": \"racing:horse_ages\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"minutes\": {\n      \"@id\": \"racing:minutes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"seconds\": {\n      \"@id\": \"racing:seconds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"hundredths\":\
  \ {\n      \"@id\": \"racing:hundredths\",\n      \"@type\": \"xsd:string\"\n    },\n    \"milliseconds\": {\n      \"@id\": \"racing:milliseconds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fifths\": {\n      \"@id\": \"racing:fifths\",\n      \"@type\": \"xsd:string\"\n    },\n    \"strFifths\": {\n      \"@id\": \"racing:str_fifths\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timeInFifths\": {\n      \"@id\": \"racing:time_in_fifths\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timeInHundredths\": {\n      \"@id\": \"racing:time_in_hundredths\",\n      \"@type\": \"xsd:string\"\n    },\n    \"off\": {\n      \"@id\": \"racing:off\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sexRest\": {\n      \"@id\": \"racing:sex_rest\",\n      \"@type\": \"xsd:string\"\n    },\n    \"damRegion\": {\n      \"@id\": \"racing:dam_region\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sireRegion\": {\n      \"@id\": \"racing:sire_region\",\n      \"@type\": \"xsd:string\"\n\
  \    },\n    \"damsireRegion\": {\n      \"@id\": \"racing:damsire_region\",\n      \"@type\": \"xsd:string\"\n    },\n    \"trainerLocation\": {\n      \"@id\": \"racing:trainer_location\",\n      \"@type\": \"xsd:string\"\n    },\n    \"trainer14Days\": {\n      \"@id\": \"racing:trainer_14_days\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ownerId\": {\n      \"@id\": \"racing:owner_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"prevTrainers\": {\n      \"@id\": \"racing:prev_trainers\",\n      \"@type\": \"xsd:string\"\n    },\n    \"prevOwners\": {\n      \"@id\": \"racing:prev_owners\",\n      \"@type\": \"xsd:string\"\n    },\n    \"spotlight\": {\n      \"@id\": \"racing:spotlight\",\n      \"@type\": \"xsd:string\"\n    },\n    \"quotes\": {\n      \"@id\": \"racing:quotes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stableTour\": {\n      \"@id\": \"racing:stable_tour\",\n      \"@type\": \"xsd:string\"\n    },\n    \"medical\": {\n      \"@id\": \"racing:medical\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"headgear\": {\n      \"@id\": \"racing:headgear\",\n      \"@type\": \"xsd:string\"\n    },\n    \"headgearRun\": {\n      \"@id\": \"racing:headgear_run\",\n      \"@type\": \"xsd:string\"\n    },\n    \"windSurgery\": {\n      \"@id\": \"racing:wind_surgery\",\n      \"@type\": \"xsd:string\"\n    },\n    \"windSurgeryRun\": {\n      \"@id\": \"racing:wind_surgery_run\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pastResultsFlags\": {\n      \"@id\": \"racing:past_results_flags\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lbs\": {\n      \"@id\": \"racing:lbs\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ofr\": {\n      \"@id\": \"racing:ofr\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rpr\": {\n      \"@id\": \"racing:rpr\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ts\": {\n      \"@id\": \"racing:ts\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastRun\": {\n      \"@id\": \"racing:last_run\",\n   \
  \   \"@type\": \"xsd:string\"\n    },\n    \"trainerRtf\": {\n      \"@id\": \"racing:trainer_rtf\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dayEvening\": {\n      \"@id\": \"racing:day_evening\",\n      \"@type\": \"xsd:string\"\n    },\n    \"totalRuns\": {\n      \"@id\": \"racing:total_runs\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"race\": {\n      \"@id\": \"racing:race\",\n      \"@type\": \"xsd:string\"\n    },\n    \"distanceY\": {\n      \"@id\": \"racing:distance_y\",\n      \"@type\": \"xsd:string\"\n    },\n    \"maximumWagerAmount\": {\n      \"@id\": \"racing:maximum_wager_amount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"minimumBoxAmount\": {\n      \"@id\": \"racing:minimum_box_amount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"minimumWagerAmount\": {\n      \"@id\": \"racing:minimum_wager_amount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"minimumWheelAmount\": {\n      \"@id\": \"racing:minimum_wheel_amount\",\n      \"@type\": \"\
  xsd:string\"\n    },\n    \"poolCode\": {\n      \"@id\": \"racing:pool_code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"poolName\": {\n      \"@id\": \"racing:pool_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"raceList\": {\n      \"@id\": \"racing:race_list\",\n      \"@type\": \"xsd:string\"\n    },\n    \"jumps\": {\n      \"@id\": \"racing:jumps\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tip\": {\n      \"@id\": \"racing:tip\",\n      \"@type\": \"xsd:string\"\n    },\n    \"verdict\": {\n      \"@id\": \"racing:verdict\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bettingForecast\": {\n      \"@id\": \"racing:betting_forecast\",\n      \"@type\": \"xsd:string\"\n    },\n    \"wagerType\": {\n      \"@id\": \"racing:wager_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"wagerDescription\": {\n      \"@id\": \"racing:wager_description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"baseAmount\": {\n      \"@id\": \"racing:base_amount\",\n   \
  \   \"@type\": \"xsd:string\"\n    },\n    \"owners\": {\n      \"@id\": \"racing:owners\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"winningTimeDetail\": {\n      \"@id\": \"racing:winning_time_detail\",\n      \"@type\": \"xsd:string\"\n    },\n    \"comments\": {\n      \"@id\": \"racing:comments\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nonRunners\": {\n      \"@id\": \"racing:non_runners\",\n      \"@type\": \"xsd:string\"\n    },\n    \"toteWin\": {\n      \"@id\": \"racing:tote_win\",\n      \"@type\": \"xsd:string\"\n    },\n    \"totePl\": {\n      \"@id\": \"racing:tote_pl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"toteEx\": {\n      \"@id\": \"racing:tote_ex\",\n      \"@type\": \"xsd:string\"\n    },\n    \"toteCsf\": {\n      \"@id\": \"racing:tote_csf\",\n      \"@type\": \"xsd:string\"\n    },\n    \"toteTricast\": {\n      \"@id\": \"racing:tote_tricast\",\n      \"@type\": \"xsd:string\"\n    },\n    \"toteTrifecta\"\
  : {\n      \"@id\": \"racing:tote_trifecta\",\n      \"@type\": \"xsd:string\"\n    },\n    \"horseAge\": {\n      \"@id\": \"racing:horse_age\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ageRestriction\": {\n      \"@id\": \"racing:age_restriction\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ageRestrictionDescription\": {\n      \"@id\": \"racing:age_restriction_description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"breed\": {\n      \"@id\": \"racing:breed\",\n      \"@type\": \"xsd:string\"\n    },\n    \"changes\": {\n      \"@id\": \"racing:changes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"courseType\": {\n      \"@id\": \"racing:course_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"courseTypeClass\": {\n      \"@id\": \"racing:course_type_class\",\n      \"@type\": \"xsd:string\"\n    },\n    \"distanceDescription\": {\n      \"@id\": \"racing:distance_description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"distanceUnit\": {\n      \"\
  @id\": \"racing:distance_unit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"distanceValue\": {\n      \"@id\": \"racing:distance_value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"grade\": {\n      \"@id\": \"racing:grade\",\n      \"@type\": \"xsd:string\"\n    },\n    \"hasFinished\": {\n      \"@id\": \"racing:has_finished\",\n      \"@type\": \"xsd:string\"\n    },\n    \"hasResults\": {\n      \"@id\": \"racing:has_results\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isCancelled\": {\n      \"@id\": \"racing:is_cancelled\",\n      \"@type\": \"xsd:string\"\n    },\n    \"maxClaimPrice\": {\n      \"@id\": \"racing:max_claim_price\",\n      \"@type\": \"xsd:string\"\n    },\n    \"minClaimPrice\": {\n      \"@id\": \"racing:min_claim_price\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mtp\": {\n      \"@id\": \"racing:mtp\",\n      \"@type\": \"xsd:string\"\n    },\n    \"postTime\": {\n      \"@id\": \"racing:post_time\",\n      \"@type\": \"xsd:string\"\n  \
  \  },\n    \"postTimeLong\": {\n      \"@id\": \"racing:post_time_long\",\n      \"@type\": \"xsd:string\"\n    },\n    \"purse\": {\n      \"@id\": \"racing:purse\",\n      \"@type\": \"xsd:string\"\n    },\n    \"raceKey\": {\n      \"@id\": \"racing:race_key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"racePools\": {\n      \"@id\": \"racing:race_pools\",\n      \"@type\": \"xsd:string\"\n    },\n    \"raceRestriction\": {\n      \"@id\": \"racing:race_restriction\",\n      \"@type\": \"xsd:string\"\n    },\n    \"raceRestrictionDescription\": {\n      \"@id\": \"racing:race_restriction_description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"raceType\": {\n      \"@id\": \"racing:race_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"raceTypeDescription\": {\n      \"@id\": \"racing:race_type_description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sexRestrictionDescription\": {\n      \"@id\": \"racing:sex_restriction_description\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"surfaceDescription\": {\n      \"@id\": \"racing:surface_description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timeZone\": {\n      \"@id\": \"racing:time_zone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"toteTrackId\": {\n      \"@id\": \"racing:tote_track_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"trackCondition\": {\n      \"@id\": \"racing:track_condition\",\n      \"@type\": \"xsd:string\"\n    },\n    \"alias\": {\n      \"@id\": \"racing:alias\",\n      \"@type\": \"xsd:string\"\n    },\n    \"firstName\": {\n      \"@id\": \"racing:first_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"firstNameInitial\": {\n      \"@id\": \"racing:first_name_initial\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastName\": {\n      \"@id\": \"racing:last_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"middleName\": {\n      \"@id\": \"racing:middle_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"history\": {\n      \"@id\":\
  \ \"racing:history\",\n      \"@type\": \"xsd:string\"\n    },\n    \"winOdds\": {\n      \"@id\": \"racing:win_odds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"placeOdds\": {\n      \"@id\": \"racing:place_odds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"carryover\": {\n      \"@id\": \"racing:carryover\",\n      \"@type\": \"xsd:string\"\n    },\n    \"numberOfRights\": {\n      \"@id\": \"racing:number_of_rights\",\n      \"@type\": \"xsd:string\"\n    },\n    \"numberOfTicketsBet\": {\n      \"@id\": \"racing:number_of_tickets_bet\",\n      \"@type\": \"xsd:string\"\n    },\n    \"payoffAmount\": {\n      \"@id\": \"racing:payoff_amount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"totalPool\": {\n      \"@id\": \"racing:total_pool\",\n      \"@type\": \"xsd:string\"\n    },\n    \"wagerName\": {\n      \"@id\": \"racing:wager_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"winningNumbers\": {\n      \"@id\": \"racing:winning_numbers\",\n      \"@type\":\
  \ \"xsd:string\"\n    },\n    \"spDec\": {\n      \"@id\": \"racing:sp_dec\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bsp\": {\n      \"@id\": \"racing:bsp\",\n      \"@type\": \"xsd:string\"\n    },\n    \"btn\": {\n      \"@id\": \"racing:btn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ovrBtn\": {\n      \"@id\": \"racing:ovr_btn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"weightLbs\": {\n      \"@id\": \"racing:weight_lbs\",\n      \"@type\": \"xsd:string\"\n    },\n    \"or\": {\n      \"@id\": \"racing:or\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tsr\": {\n      \"@id\": \"racing:tsr\",\n      \"@type\": \"xsd:string\"\n    },\n    \"jockeyClaimLbs\": {\n      \"@id\": \"racing:jockey_claim_lbs\",\n      \"@type\": \"xsd:string\"\n    },\n    \"careerPrize\": {\n      \"@id\": \"racing:career_prize\",\n      \"@type\": \"xsd:string\"\n    },\n    \"careerWinPercent\": {\n      \"@id\": \"racing:career_win_percent\",\n      \"@type\": \"xsd:string\"\n\
  \    },\n    \"careerPlacePercent\": {\n      \"@id\": \"racing:career_place_percent\",\n      \"@type\": \"xsd:string\"\n    },\n    \"courseStats\": {\n      \"@id\": \"racing:course_stats\",\n      \"@type\": \"xsd:string\"\n    },\n    \"courseDistanceStats\": {\n      \"@id\": \"racing:course_distance_stats\",\n      \"@type\": \"xsd:string\"\n    },\n    \"distanceStats\": {\n      \"@id\": \"racing:distance_stats\",\n      \"@type\": \"xsd:string\"\n    },\n    \"groundFirmStats\": {\n      \"@id\": \"racing:ground_firm_stats\",\n      \"@type\": \"xsd:string\"\n    },\n    \"groundGoodStats\": {\n      \"@id\": \"racing:ground_good_stats\",\n      \"@type\": \"xsd:string\"\n    },\n    \"groundHeavyStats\": {\n      \"@id\": \"racing:ground_heavy_stats\",\n      \"@type\": \"xsd:string\"\n    },\n    \"groundSoftStats\": {\n      \"@id\": \"racing:ground_soft_stats\",\n      \"@type\": \"xsd:string\"\n    },\n    \"groundAwStats\": {\n      \"@id\": \"racing:ground_aw_stats\",\n\
  \      \"@type\": \"xsd:string\"\n    },\n    \"jockeyStats\": {\n      \"@id\": \"racing:jockey_stats\",\n      \"@type\": \"xsd:string\"\n    },\n    \"jumpsStats\": {\n      \"@id\": \"racing:jumps_stats\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastRaced\": {\n      \"@id\": \"racing:last_raced\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastTenRacesStats\": {\n      \"@id\": \"racing:last_ten_races_stats\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastTwelveMonthsStats\": {\n      \"@id\": \"racing:last_twelve_months_stats\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastWon\": {\n      \"@id\": \"racing:last_won\",\n      \"@type\": \"xsd:string\"\n    },\n    \"maxWinningDistance\": {\n      \"@id\": \"racing:max_winning_distance\",\n      \"@type\": \"xsd:string\"\n    },\n    \"minWinningDistance\": {\n      \"@id\": \"racing:min_winning_distance\",\n      \"@type\": \"xsd:string\"\n    },\n    \"poolTypeName\": {\n      \"@id\": \"racing:pool_type_name\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"amount\": {\n      \"@id\": \"racing:amount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fractionalOdds\": {\n      \"@id\": \"racing:fractional_odds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dollar\": {\n      \"@id\": \"racing:do\n\n# --- truncated at 32 KB (34 KB total) ---\n# Full source: https://raw.githubusercontent.com/api-evangelist/the-racing-api/refs/heads/main/json-ld/the-racing-api-context.jsonld\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/the-racing-api/refs/heads/main/json-ld/the-racing-api-context.jsonld
tags:
- Horse Racing
- Sports
- Statistics
- Betting
- Analytics
- JSON-LD
- Linked Data
- Semantic Web
---
