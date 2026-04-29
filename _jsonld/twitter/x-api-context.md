---
class_count: 23
classes:
- ActivityStreamingResponse
- ActivitySubscription
- ComplianceJob
- CreateDmConversationRequest
- DmEvent
- Error
- Expansions
- FilteredStreamingTweetResponse
- Get2TweetsSearchRecentResponse
- Get2UsersIdResponse
- List
- ListCreateRequest
- Media
- Place
- Poll
- Problem
- Space
- Tweet
- TweetCreateRequest
- TweetCreateResponse
- TweetDeleteResponse
- User
- UsersFollowingCreateRequest
context_file: json-ld/x-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/twitter/refs/heads/main/json-ld/x-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for X Api from X (Twitter).
layout: jsonld
name: X Api Context
namespaces:
- prefix: x
  uri: https://docs.x.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: affiliation
  type: reference
- container: ''
  name: attachments
  type: reference
- container: ''
  name: authorId
  type: string
- container: ''
  name: cardUri
  type: string
- container: set
  name: cashtags
  type: string
- container: ''
  name: code
  type: string
- container: ''
  name: communityId
  type: string
- container: set
  name: connectionStatus
  type: string
- container: set
  name: containedWithin
  type: string
- container: set
  name: contextAnnotations
  type: string
- container: ''
  name: conversationId
  type: string
- container: ''
  name: conversationType
  type: string
- container: ''
  name: country
  type: string
- container: ''
  name: countryCode
  type: string
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: creatorId
  type: string
- container: ''
  name: data
  type: reference
- container: ''
  name: description
  type: string
- container: ''
  name: detail
  type: string
- container: ''
  name: directMessageDeepLink
  type: string
- container: set
  name: displayTextRange
  type: string
- container: ''
  name: dmConversationId
  type: string
- container: ''
  name: downloadExpiresAt
  type: dateTime
- container: ''
  name: downloadUrl
  type: reference
- container: ''
  name: durationMinutes
  type: string
- container: ''
  name: editControls
  type: reference
- container: set
  name: editHistoryTweetIds
  type: string
- container: ''
  name: editOptions
  type: reference
- container: ''
  name: endDatetime
  type: dateTime
- container: ''
  name: endedAt
  type: dateTime
- container: ''
  name: entities
  type: reference
- container: set
  name: errors
  type: string
- container: ''
  name: eventType
  type: string
- container: ''
  name: filter
  type: reference
- container: ''
  name: followerCount
  type: integer
- container: ''
  name: forSuperFollowersOnly
  type: boolean
- container: ''
  name: fullName
  type: string
- container: ''
  name: geo
  type: reference
- container: set
  name: hashtags
  type: string
- container: ''
  name: height
  type: integer
- container: set
  name: hostIds
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: inReplyToUserId
  type: string
- container: ''
  name: includes
  type: reference
- container: set
  name: invitedUserIds
  type: string
- container: ''
  name: isTicketed
  type: boolean
- container: ''
  name: lang
  type: string
- container: ''
  name: location
  type: string
- container: ''
  name: madeWithAi
  type: boolean
- container: set
  name: matchingRules
  type: string
- container: ''
  name: media
  type: reference
- container: ''
  name: mediaKey
  type: string
- container: ''
  name: memberCount
  type: integer
- container: set
  name: mentions
  type: string
- container: ''
  name: message
  type: string
- container: ''
  name: meta
  type: reference
- container: ''
  name: mostRecentTweetId
  type: string
- container: ''
  name: name
  type: string
- container: ''
  name: nonPublicMetrics
  type: reference
- container: ''
  name: noteTweet
  type: reference
- container: ''
  name: nullcast
  type: boolean
- container: set
  name: options
  type: string
- container: ''
  name: organicMetrics
  type: reference
- container: ''
  name: ownerId
  type: string
- container: ''
  name: paidPartnership
  type: boolean
- container: ''
  name: participantCount
  type: string
- container: set
  name: participantIds
  type: string
- container: ''
  name: pinnedTweetId
  type: string
- container: ''
  name: placeType
  type: string
- container: set
  name: places
  type: string
- container: ''
  name: poll
  type: reference
- container: set
  name: polls
  type: string
- container: ''
  name: possiblySensitive
  type: boolean
- container: ''
  name: private
  type: boolean
- container: ''
  name: profileBannerUrl
  type: reference
- container: ''
  name: profileImageUrl
  type: reference
- container: ''
  name: promotedMetrics
  type: reference
- container: ''
  name: protected
  type: boolean
- container: ''
  name: publicMetrics
  type: reference
- container: ''
  name: quoteTweetId
  type: string
- container: ''
  name: receivesYourDm
  type: boolean
- container: set
  name: referencedTweets
  type: string
- container: ''
  name: reply
  type: reference
- container: ''
  name: replySettings
  type: string
- container: ''
  name: scheduledStart
  type: dateTime
- container: ''
  name: scopes
  type: reference
- container: ''
  name: senderId
  type: string
- container: ''
  name: shareWithFollowers
  type: boolean
- container: ''
  name: source
  type: string
- container: set
  name: speakerIds
  type: string
- container: ''
  name: startedAt
  type: dateTime
- container: ''
  name: state
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: subscriberCount
  type: string
- container: ''
  name: subscriptionId
  type: string
- container: ''
  name: subscriptionType
  type: string
- container: set
  name: suggestedSourceLinks
  type: string
- container: ''
  name: suggestedSourceLinksWithCounts
  type: reference
- container: ''
  name: tag
  type: string
- container: ''
  name: targetUserId
  type: string
- container: ''
  name: text
  type: string
- container: ''
  name: title
  type: string
- container: set
  name: topics
  type: string
- container: set
  name: tweets
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: updatedAt
  type: dateTime
- container: ''
  name: uploadExpiresAt
  type: dateTime
- container: ''
  name: uploadUrl
  type: reference
- container: ''
  name: url
  type: string
- container: set
  name: urls
  type: string
- container: ''
  name: username
  type: string
- container: set
  name: users
  type: string
- container: ''
  name: verified
  type: boolean
- container: ''
  name: verifiedType
  type: string
- container: ''
  name: votingStatus
  type: string
- container: ''
  name: webhookId
  type: string
- container: ''
  name: width
  type: integer
- container: ''
  name: withheld
  type: reference
property_count: 118
provider_name: X (Twitter)
provider_slug: twitter
slug: x-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"x\": \"https://docs.x.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ActivityStreamingResponse\": \"x:ActivityStreamingResponse\",\n    \"ActivitySubscription\": \"x:ActivitySubscription\",\n    \"ComplianceJob\": \"x:ComplianceJob\",\n    \"CreateDmConversationRequest\": \"x:CreateDmConversationRequest\",\n    \"DmEvent\": \"x:DmEvent\",\n    \"Error\": \"x:Error\",\n    \"Expansions\": \"x:Expansions\",\n    \"FilteredStreamingTweetResponse\": \"x:FilteredStreamingTweetResponse\",\n    \"Get2TweetsSearchRecentResponse\": \"x:Get2TweetsSearchRecentResponse\",\n    \"Get2UsersIdResponse\": \"x:Get2UsersIdResponse\",\n    \"List\": \"x:List\",\n    \"ListCreateRequest\": \"x:ListCreateRequest\",\n    \"Media\": \"x:Media\",\n    \"Place\": \"x:Place\",\n    \"Poll\": \"x:Poll\",\n    \"Problem\": \"x:Problem\",\n    \"Space\": \"x:Space\",\n    \"Tweet\"\
  : \"x:Tweet\",\n    \"TweetCreateRequest\": \"x:TweetCreateRequest\",\n    \"TweetCreateResponse\": \"x:TweetCreateResponse\",\n    \"TweetDeleteResponse\": \"x:TweetDeleteResponse\",\n    \"User\": \"x:User\",\n    \"UsersFollowingCreateRequest\": \"x:UsersFollowingCreateRequest\",\n    \"affiliation\": {\n      \"@id\": \"x:affiliation\",\n      \"@type\": \"@id\"\n    },\n    \"attachments\": {\n      \"@id\": \"x:attachments\",\n      \"@type\": \"@id\"\n    },\n    \"authorId\": {\n      \"@id\": \"x:author_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cardUri\": {\n      \"@id\": \"x:card_uri\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cashtags\": {\n      \"@id\": \"x:cashtags\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"code\": {\n      \"@id\": \"x:code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"communityId\": {\n      \"@id\": \"x:community_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"connectionStatus\": {\n\
  \      \"@id\": \"x:connection_status\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"containedWithin\": {\n      \"@id\": \"x:contained_within\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"contextAnnotations\": {\n      \"@id\": \"x:context_annotations\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"conversationId\": {\n      \"@id\": \"x:conversation_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"conversationType\": {\n      \"@id\": \"x:conversation_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"country\": {\n      \"@id\": \"x:country\",\n      \"@type\": \"xsd:string\"\n    },\n    \"countryCode\": {\n      \"@id\": \"x:country_code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdAt\": {\n      \"@id\": \"x:created_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"creatorId\": {\n      \"@id\": \"x:creator_id\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"data\": {\n      \"@id\": \"x:data\",\n      \"@type\": \"@id\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"detail\": {\n      \"@id\": \"x:detail\",\n      \"@type\": \"xsd:string\"\n    },\n    \"directMessageDeepLink\": {\n      \"@id\": \"x:direct_message_deep_link\",\n      \"@type\": \"xsd:string\"\n    },\n    \"displayTextRange\": {\n      \"@id\": \"x:display_text_range\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dmConversationId\": {\n      \"@id\": \"x:dm_conversation_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"downloadExpiresAt\": {\n      \"@id\": \"x:download_expires_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"downloadUrl\": {\n      \"@id\": \"x:download_url\",\n      \"@type\": \"@id\"\n    },\n    \"durationMinutes\": {\n      \"@id\": \"x:duration_minutes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"editControls\"\
  : {\n      \"@id\": \"x:edit_controls\",\n      \"@type\": \"@id\"\n    },\n    \"editHistoryTweetIds\": {\n      \"@id\": \"x:edit_history_tweet_ids\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"editOptions\": {\n      \"@id\": \"x:edit_options\",\n      \"@type\": \"@id\"\n    },\n    \"endDatetime\": {\n      \"@id\": \"x:end_datetime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"endedAt\": {\n      \"@id\": \"x:ended_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"entities\": {\n      \"@id\": \"x:entities\",\n      \"@type\": \"@id\"\n    },\n    \"errors\": {\n      \"@id\": \"x:errors\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eventType\": {\n      \"@id\": \"x:event_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"filter\": {\n      \"@id\": \"x:filter\",\n      \"@type\": \"@id\"\n    },\n    \"followerCount\": {\n      \"@id\": \"x:follower_count\",\n      \"@type\": \"xsd:integer\"\
  \n    },\n    \"forSuperFollowersOnly\": {\n      \"@id\": \"x:for_super_followers_only\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"fullName\": {\n      \"@id\": \"x:full_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"geo\": {\n      \"@id\": \"x:geo\",\n      \"@type\": \"@id\"\n    },\n    \"hashtags\": {\n      \"@id\": \"x:hashtags\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"height\": {\n      \"@id\": \"x:height\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"hostIds\": {\n      \"@id\": \"x:host_ids\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"x:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"inReplyToUserId\": {\n      \"@id\": \"x:in_reply_to_user_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"includes\": {\n      \"@id\": \"x:includes\",\n      \"@type\": \"@id\"\n    },\n    \"invitedUserIds\": {\n      \"@id\": \"x:invited_user_ids\",\n \
  \     \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isTicketed\": {\n      \"@id\": \"x:is_ticketed\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"lang\": {\n      \"@id\": \"x:lang\",\n      \"@type\": \"xsd:string\"\n    },\n    \"location\": {\n      \"@id\": \"x:location\",\n      \"@type\": \"xsd:string\"\n    },\n    \"madeWithAi\": {\n      \"@id\": \"x:made_with_ai\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"matchingRules\": {\n      \"@id\": \"x:matching_rules\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"media\": {\n      \"@id\": \"x:media\",\n      \"@type\": \"@id\"\n    },\n    \"mediaKey\": {\n      \"@id\": \"x:media_key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"memberCount\": {\n      \"@id\": \"x:member_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"mentions\": {\n      \"@id\": \"x:mentions\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n \
  \   \"message\": {\n      \"@id\": \"x:message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"meta\": {\n      \"@id\": \"x:meta\",\n      \"@type\": \"@id\"\n    },\n    \"mostRecentTweetId\": {\n      \"@id\": \"x:most_recent_tweet_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nonPublicMetrics\": {\n      \"@id\": \"x:non_public_metrics\",\n      \"@type\": \"@id\"\n    },\n    \"noteTweet\": {\n      \"@id\": \"x:note_tweet\",\n      \"@type\": \"@id\"\n    },\n    \"nullcast\": {\n      \"@id\": \"x:nullcast\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"options\": {\n      \"@id\": \"x:options\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"organicMetrics\": {\n      \"@id\": \"x:organic_metrics\",\n      \"@type\": \"@id\"\n    },\n    \"ownerId\": {\n      \"@id\": \"x:owner_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"paidPartnership\"\
  : {\n      \"@id\": \"x:paid_partnership\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"participantCount\": {\n      \"@id\": \"x:participant_count\",\n      \"@type\": \"xsd:string\"\n    },\n    \"participantIds\": {\n      \"@id\": \"x:participant_ids\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pinnedTweetId\": {\n      \"@id\": \"x:pinned_tweet_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"placeType\": {\n      \"@id\": \"x:place_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"places\": {\n      \"@id\": \"x:places\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"poll\": {\n      \"@id\": \"x:poll\",\n      \"@type\": \"@id\"\n    },\n    \"polls\": {\n      \"@id\": \"x:polls\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"possiblySensitive\": {\n      \"@id\": \"x:possibly_sensitive\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"private\": {\n \
  \     \"@id\": \"x:private\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"profileBannerUrl\": {\n      \"@id\": \"x:profile_banner_url\",\n      \"@type\": \"@id\"\n    },\n    \"profileImageUrl\": {\n      \"@id\": \"x:profile_image_url\",\n      \"@type\": \"@id\"\n    },\n    \"promotedMetrics\": {\n      \"@id\": \"x:promoted_metrics\",\n      \"@type\": \"@id\"\n    },\n    \"protected\": {\n      \"@id\": \"x:protected\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"publicMetrics\": {\n      \"@id\": \"x:public_metrics\",\n      \"@type\": \"@id\"\n    },\n    \"quoteTweetId\": {\n      \"@id\": \"x:quote_tweet_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"receivesYourDm\": {\n      \"@id\": \"x:receives_your_dm\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"referencedTweets\": {\n      \"@id\": \"x:referenced_tweets\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reply\": {\n      \"@id\": \"x:reply\",\n      \"@type\": \"\
  @id\"\n    },\n    \"replySettings\": {\n      \"@id\": \"x:reply_settings\",\n      \"@type\": \"xsd:string\"\n    },\n    \"scheduledStart\": {\n      \"@id\": \"x:scheduled_start\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"scopes\": {\n      \"@id\": \"x:scopes\",\n      \"@type\": \"@id\"\n    },\n    \"senderId\": {\n      \"@id\": \"x:sender_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shareWithFollowers\": {\n      \"@id\": \"x:share_with_followers\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"source\": {\n      \"@id\": \"x:source\",\n      \"@type\": \"xsd:string\"\n    },\n    \"speakerIds\": {\n      \"@id\": \"x:speaker_ids\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startedAt\": {\n      \"@id\": \"x:started_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"state\": {\n      \"@id\": \"x:state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"x:status\",\n      \"@type\": \"\
  xsd:string\"\n    },\n    \"subscriberCount\": {\n      \"@id\": \"x:subscriber_count\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subscriptionId\": {\n      \"@id\": \"x:subscription_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subscriptionType\": {\n      \"@id\": \"x:subscription_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"suggestedSourceLinks\": {\n      \"@id\": \"x:suggested_source_links\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"suggestedSourceLinksWithCounts\": {\n      \"@id\": \"x:suggested_source_links_with_counts\",\n      \"@type\": \"@id\"\n    },\n    \"tag\": {\n      \"@id\": \"x:tag\",\n      \"@type\": \"xsd:string\"\n    },\n    \"targetUserId\": {\n      \"@id\": \"x:target_user_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"text\": {\n      \"@id\": \"x:text\",\n      \"@type\": \"xsd:string\"\n    },\n    \"title\": {\n      \"@id\": \"x:title\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"topics\": {\n      \"@id\": \"x:topics\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tweets\": {\n      \"@id\": \"x:tweets\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"x:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"x:updated_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"uploadExpiresAt\": {\n      \"@id\": \"x:upload_expires_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"uploadUrl\": {\n      \"@id\": \"x:upload_url\",\n      \"@type\": \"@id\"\n    },\n    \"url\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"xsd:string\"\n    },\n    \"urls\": {\n      \"@id\": \"x:urls\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"username\": {\n      \"@id\": \"x:username\",\n      \"@type\": \"xsd:string\"\n    },\n    \"users\": {\n      \"@id\": \"x:users\",\n      \"@container\"\
  : \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"verified\": {\n      \"@id\": \"x:verified\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"verifiedType\": {\n      \"@id\": \"x:verified_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"votingStatus\": {\n      \"@id\": \"x:voting_status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"webhookId\": {\n      \"@id\": \"x:webhook_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"width\": {\n      \"@id\": \"x:width\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"withheld\": {\n      \"@id\": \"x:withheld\",\n      \"@type\": \"@id\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/twitter/refs/heads/main/json-ld/x-api-context.jsonld
tags:
- Social Media
- Microblogging
- Real-Time Data
- Streaming
- Advertising
- Content
- JSON-LD
- Linked Data
- Semantic Web
---
