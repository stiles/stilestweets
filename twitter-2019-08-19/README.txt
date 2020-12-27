INTRODUCTION
============
This archive was generated at the request of the following user:
- @username at the time the archive was generated: stiles
- Account ID: 14790314

This archive consists of machine-readable JSON files containing information associated with your account. We’ve included the information we believe is most relevant and useful to you, including your profile information, your Tweets, your DMs, your Moments, your media (images, videos and GIFs you’ve attached to Tweets, DMs, or Moments), a list of your followers, a list of accounts following you, your address book, Lists that you’ve created, are a member of, or are subscribed to, interest and demographic information that we have inferred about you, information about ads that you’ve seen or engaged with on Twitter, and more.

The information contained in this archive reflects the state of the account at the time when the archive was created. In addition, if we do not have any data associated with your account for a particular category (e.g., if you have never created a List), then this archive will not include a file for that category.


CONTENTS
========
This archive contains:

	/account_timezone.js: Account timezone information.
	/moment.js: Twitter Moments (a collection of Tweets that can be shared across the Twitter platform) created by the account.
	/periscope-comments-made-by-user.js: Comments left by account holder on other users’ live broadcasts.
	/follower.js: Other accounts that follow this account.
	/moments_media: Folder containing image or video included in the moment.
	/periscope_broadcast_media: Encoded live broadcast video files created by this account.
	/connected-application.js: List of applications authorized by user to connect to this account.
	/moments_tweets_media: Folder containing images, videos, and/or gifs associated with the Tweets in the Moment.
	/tweet.js: Tweets posted to the account.
	/ageinfo.js: Date of birth provided to Twitter and corresponding current age.
	/direct-message-group-headers.js: Contains only metadata associated with GDMs.
	/direct_message_media: Folder of images, videos, and/or gifs included in the account’s DMs
	/direct-message-headers.js: Contains only metadata associated with DMs.
	/direct-message.js: Contains the text and associated metadata for Direct Messages (DMs) sent or received by the account.
	/direct_message_group_media: Folder of images, videos, and/or gifs included in the account’s GDMs
	/direct-message-group.js: Contains the text and associated metadata for Group Direct Messages (GDMs) sent or received by the account.
	/ad-online-conversions-attributed.js: All online (website) activities associated with an account in the last 90 days via advertiser website integrations which are attributable to a Promoted Tweet engagement on Twitter.
	/periscope-profile-description.js: Periscope account description ported over from the Twitter account when the shell account was created.
	/periscope-broadcast-metadata.js: Metadata associated with the account’s live broadcasts.
	/email-address-change.js: History of email addresses associated with the account.
	/ip-audit.js: IP addresses per session (not per Tweet).
	/account-suspension.js: Account’s suspension history. At the time of account creation, accounts are unsuspended by default.
	/contact.js: Contacts imported into this account.
	/personalization.js: Contains information Twitter may have inferred about this account.
	/ad-mobile-conversions-attributed.js: Mobile application events associated with an account in the last 90 days which are attributable to a Promoted Tweet engagement on Twitter.
	/ad-engagements.js: Promoted Tweets engaged with by the account and any associated metadata.
	/lists-subscribed.js: Lists subscribed to by this account.
	/lists-member.js: Public lists created by other accounts that include this account.
	/lists-created.js: Lists created by this account.
	/ad-online-conversions-unattributed.js: All online (website) activities associated with an account in the last 10 days via advertiser website integrations which may become attributable to a Promoted Tweet engagement on Twitter.
	/mute.js: Other accounts muted by this account.
	/profile.js: Profile bio, location, and website associated with the account.
	/ad-mobile-conversions-unattributed.js: Mobile application events associated with an account in the last 10 days which may become attributable to a Promoted Tweet engagement on Twitter.
	/ni-devices.js: Mobile devices (e.g., mobile phone) associated with the account.
	/tweet_media: Folder of images, videos, and/or gifs included in the account’s Tweets.
	/periscope-followers.js: Other accounts that follow this account.
	/ad-impressions.js: Promoted Tweets viewed by the account and associated metadata.
	/following.js: Other accounts followed by this account.
	/profile_media: Folder containing profile avatar and header image, if provided.
	/periscope-account-information.js: Basic information for the Periscope "shell account", which is automatically created when a user broadcasts live from Twitter.
	/account-creation-ip.js: IP address used when the account was created.
	/screen-name-change.js: Records of changes to this account’s @username.
	/account.js: Basic account information.
	/phone_number.js: Phone number provided by the user and which is associated with the account.
	/block.js: Other accounts blocked by this account.
	/device-token.js: List of known device token(s).
	/saved-search.js: Searches saved by this account.
	/verified.js: Account’s verification status.
	/protected-history.js: History of a user protecting (that is, restricting only to their followers) and unprotecting their Tweets within the 6 months prior to the date this file was created. At the time of account creation, Tweets are unprotected by default.
	/like.js: Tweets marked as ‘Favorites’ or ‘Likes’ by this account.
	/periscope-expired-broadcasts.js: Live broadcasts on Twitter that have expired and cannot be encoded.


DETAILED DOCUMENTATION
======================
This section documents the data in each file in more detail.

account_timezone.js
-------------------
Account timezone information.
* accountId: Unique identifier for the account.
* timeZone: Time zone specified by account holder, if provided.

moment.js
---------
Twitter Moments (a collection of Tweets that can be shared across the Twitter platform) created by the account. For more information, please refer to https://help.twitter.com/en/using-twitter/twitter-moments.
* momentId: Unique identifier of the Moment.
* createdAt: Date and time a Moment is created, in Coordinated Universal Time (UTC).
* createdBy: User ID (unique identifier) of the account holder who generated the Moment.
* title: Title attributed to the Moment by the account holder.
* tweets: Tweets selected by the account holder to include in the Moment. Please note that these Tweets may or may not have been posted by the account holder who created the Moment.  This record contains the API output of the Tweets added to the Moment and they are ordered according to how they appear in the Moment. Definitions for each of the variables that may be included in any particular Tweet are available in our API documentation: https://developer.twitter.com/en/docs/tweets/post-and-engage/api-reference/post-statuses-update.
* description: Description text on the cover page of the Moment added by the account holder who generated the Moment.

periscope-comments-made-by-user.js
----------------------------------
Comments left by account holder on other users’ live broadcasts.
* broadcastId: Unique id for the broadcast.
* byAccountId: Account Id of the commenter.
* createdAt: Time comment was made.
* text: The comment text.

follower.js
-----------
Other accounts that follow this account.

moments_media
-------------
Folder containing images, videos, and/or gifs uploaded through Twitter’s photo hosting service (if any) for Tweets that have been included in this Moment, including the Moment cover media. This file does not contain images hosted by third parties (e.g., FlickR, TwitPic, etc.). Please also note that these images may or may not have been posted by the account holder who created the Moment.

periscope_broadcast_media
-------------------------
Folder containing the encoded live broadcast video files created by this account.

connected-application.js
------------------------
List of applications authorized by user to connect to this account.
* id: Unique identifier for the application.
* name: Name of the application.
* description: Brief description of the application as provided by the organization.
* organization: Name of the developer of the application as well as relevant URLs such as their Privacy Policy or Terms Of Service.
* permissions: List of permissions granted to the connected application by the Twitter account. For example: read or write.
* approved_at: Date and time when the account authorized the application.

moments_tweets_media
--------------------
Folder containing images, videos, and/or gifs uploaded through Twitter’s photo hosting service (if any) for Tweets that have been included in this Moment, including the Moment cover media. This file does not contain images hosted on platforms other than Twitter (e.g., Flickr). Please also note that these images may or may not have been posted by the account holder who created the Moment.

tweet.js
--------
Tweets posted to account. This record contains the API output of Tweets for this account. Definitions for each of the variables that may be included in any particular Tweet are available in our API documentation: https://developer.twitter.com/en/docs/tweets/post-and-engage/api-reference/post-statuses-update.

ageinfo.js
----------
Date of birth provided to Twitter and corresponding current age.
* birthDate: Date of birth provided by the user.
* age: Current age.

direct-message-group-headers.js
-------------------------------
Contains only metadata associated with Group Direct Messages (GDMs) sent or received by the account.


direct_message_media
--------------------
Folder of images, videos, and/or gifs included in the account’s DMs.
NOTE: Does not contain content hosted on platforms other than Twitter (e.g. YouTube, Flickr)


direct-message-headers.js
-------------------------
Contains only metadata associated with Direct Messages (DMs) sent or received by the account.


direct-message.js
-----------------
Contains the text and associated metadata for Direct Messages (DMs) sent or received by the account.
* conversationId: DMs are grouped by conversations. The conversation IDs are created by joining two user IDs of the two participants in the conversation. For example, if one participant’s user ID is 1234 and the other participant’s user ID is 7890, the conversation ID will be 1234-7890. The conversation IDs are ordered from the lowest to highest value of the first user ID. Within a conversation, the DMs are ordered in reverse chronological order, meaning that the latest DM will be at the top of the list. DMs contain information (e.g., user ID and text of message) for both the sender and receiver.
* messages: List of each message sent or received by the account. Variables that may be included in any particular Direct Message are defined in our API documentation: https://developer.twitter.com/en/docs/direct-messages/sending-and-receiving/guides/message-create-object

NOTE: This data may be split into multiple parts/files depending on the volume of messages. Due to user deletions, the file may not contain comprehensive logs of join events, participants lists, name change events, and message create events.


direct_message_group_media
--------------------------
Folder of images, videos, and/or gifs included in the account’s GDMs.
NOTE: Does not contain content hosted on platforms other than Twitter (e.g. YouTube, Flickr)


direct-message-group.js
-----------------------
Contains the text and associated metadata for Group Direct Messages (GDMs) sent or received by the account.
* conversationId: DMs are grouped by conversations. Each conversation has a unique randomly generated conversation ID. Within a conversation, the DMs are ordered in reverse chronological order, meaning that the latest DM will be at the top of the list. DMs contain information (e.g., user ID and text of message) for both the sender and receiver.
* messages: List of each message sent or received by the account. Variables that may be included in any particular Direct Message are defined in our API documentation: https://developer.twitter.com/en/docs/direct-messages/sending-and-receiving/guides/message-create-object

Group Direct Messages (GDMs) contain information (e.g., user ID and text of message) for both the sender and the other participants of the group. Group Direct Messages are grouped by conversations. The conversations will be ordered in chronological order, based on when the conversation was created. This means that the conversation that is created first is listed at the top of the file. Within a conversation, the logged events are ordered in reverse chronological order, meaning that the latest event will be at the top of the list.

Additional logged events in the GDM file include:
- Join Conversation event: occurs when a user adds other participants to the conversation.
- Conversation name change events (change the name of the conversation).
- Message create event: this is the actual DM and is shown when a DM message is created by a user.
- Leave event: when a user leaves the group DM conversation.

NOTE: This data may be split into multiple parts/files depending on the volume of messages. Due to user deletions, the file may not contain comprehensive logs of join events, participants lists, name change events, and message create events.


ad-online-conversions-attributed.js
-----------------------------------
All online (website) activities associated with an account in the last 90 days via advertiser website integrations which are attributable to a Promoted Tweet engagement on Twitter.
* conversionTime: The UTC time of the event.
* advertiserInfo: The name and Twitter handle of the advertiser.
* conversionPlatform: Mobile or Desktop.
* conversionUrl: The URL of the website on which the event occurred.
* eventType: The raw event type recorded from the website (e.g. pageview, signup).
* attributedConversionType: The type of activity specifically associated with the conversion.
* conversionValue: The value of the conversion.
* additionalParameters: Other optional parameters associated with the event, such as content category, SKU, etc.

periscope-profile-description.js
--------------------------------
Periscope account description ported over from the Twitter account when the shell account was created.

periscope-broadcast-metadata.js
-------------------------------
Metadata associated with the account’s live broadcasts.
* id: Unique id for the broadcast.
* hasLocation: Flag to indicate if the broadcast has associated location.
* latitude: Specific latitude for the broadcast’s location.
* longitude: Specific longitude for the broadcast’s location.
* city: (optional) City where the broadcast took place.
* country: (optional) Country where the broadcast took place.
* createdAt: Time broadcast was created.
* updatedAt: Time broadcast was updated or modified.

email-address-change.js
-----------------------
History of email addresses associated with the account.
* accountId: Unique identifier for the account that performed the action.
* changedAt: Date and time of action.
* changedFrom: Previous email address.
* changedTo: New email address.

ip-audit.js
-----------
IP addresses per session (not per Tweet).
* accountId: Unique identifier for the account.
* createdAt: Time of login.
* loginIp: IP address used for login.

account-suspension.js
---------------------
Account’s suspension history. At the time of account creation, accounts are unsuspended by default.

contact.js
----------
Contacts imported into this account.
* emails: Emails of the contacts imported to the account.
* phoneNumbers: Phone numbers of the contacts imported to the account.

personalization.js
------------------
Contains information Twitter may have inferred about this account.
* languages: Languages associated with the account. Please note that this information may be inferred.
* genderInfo: Gender associated with the account. Please note that this information may be inferred.
* interests: Interests associated with the account. Please note that this information may be inferred.
* partnerInterests: Interests from partners that are associated with the account.
* numAudiences: Number of tailored audiences (audiences generated by advertisers) the account is a part of.
* advertisers: List of screennames for the advertisers that own the tailored audiences the account is a part of.
* inferredAgeInfo: Date of birth Twitter has inferred about the account and corresponding current age.
* locationHistory: Location history associated with the account based on activity from the last 60 days.

ad-mobile-conversions-attributed.js
-----------------------------------
Mobile application events associated with an account in the last 90 days which are attributable to a Promoted Tweet engagement on Twitter.
* conversionTime: The UTC time of the event.
* applicationName: The name of the application in which the activity occurred.
* mobilePlatform: The mobile platform of the application (e.g, Android, iOS)
* conversionEvent: The raw event type from the application (e.g., install, signup).
* attributedConversionType: The type of activity specifically associated with the conversion.
* conversionValue: The value of the conversion.
* additionalParameters: Other optional parameters associated with the event.

ad-engagements.js
-----------------
Promoted Tweets engaged with by the account and any associated metadata.
* impressionData: Data on which ads were viewed by the account; includes the same data as noted in impressions.js.
* engagementTime: Time when account engaged with the ad.
* engagementType: Type of engagement (e.g., Chargeable impression, Video playback)

lists-subscribed.js
-------------------
Lists subscribed to by this account.

lists-member.js
---------------
Public lists created by other accounts that include this account.

lists-created.js
----------------
Lists created by this account.

ad-online-conversions-unattributed.js
-------------------------------------
All online (website) activities associated with an account in the last 10 days via advertiser website integrations which may become attributable to a Promoted Tweet engagement on Twitter.
* conversionTime: The UTC time of the event.
* advertiserInfo: The name and Twitter handle of the advertiser.
* conversionPlatform: Mobile or Desktop.
* conversionUrl: The URL of the website on which the event occurred.
* eventType: The raw event type recorded from the website (e.g. pageview, signup).
* conversionValue: The value of the conversion.
* additionalParameters: Other optional parameters associated with the event, such as content category, SKU, etc.

mute.js
-------
Other accounts muted by this account.

profile.js
----------
Profile bio, location, and website associated with the account.
* bio: Account bio as displayed on account’s public profile.
* website: Account website as displayed on account’s public profile.
* location: Account location as displayed on account’s public profile.
* avatarMediaUrl: Link to profile avatar image.
* headerMediaUrl: Link to profile header image.

ad-mobile-conversions-unattributed.js
-------------------------------------
Mobile application events associated with an account in the last 10 days which may become attributable to a Promoted Tweet engagement on Twitter.
* conversionTime: The UTC time of the event.
* applicationName: The name of the application in which the activity occurred.
* mobilePlatform: The mobile platform of the application (e.g., Android, iOS)
* conversionEvent: The raw event type from the application (e.g., install, signup).
* conversionValue: The value of the conversion.
* additionalParameters: Other optional parameters associated with the event.

ni-devices.js
-------------
Mobile devices (e.g., mobile phone) associated with the account.
* deviceType: Manufacturer for devices that are marked as “pushDevice”. For devices marked as “messagingDevice”, the field will indicate “Auth” if the device is only used for two-factor authentication purposes, and “Full” if the device is set to receive notifications from Twitter.
* carrier: Optional field indicating the carrier associated with the device.
* phone_number: Phone number associated with the device.
* deviceVersion: Operating system version associated with the device.
* createdDate: Field indicating when the association between the device and the Twitter account was made.
* updatedDate: Field indicating the last time this association was updated.

tweet_media
-----------
Folder of images, videos, and/or gifs included in the account’s Tweets.
NOTE: Does not contain content hosted on platforms other than Twitter (e.g. YouTube, Flickr)


periscope-followers.js
----------------------
Other accounts that follow this shell account.

ad-impressions.js
-----------------
Promoted Tweets viewed by the account and associated metadata.
* impressionTime: Time when ad was viewed.
* deviceInfo: Device where ad was viewed (e.g. Desktop, Mobile).
* displayLocation: Location on Twitter where the ad was viewed (e.g. Timeline).
* advertiserInfo: Information about the advertiser.
* promotedTweet: Unique identifier of the Promoted Tweet used in the ad. Matching & targeting criteria used to deliver the ad to this account.

following.js
------------
Other accounts followed by this account.

profile_media
-------------
Folder containing profile image, header image, and background image, if provided.

periscope-account-information.js
--------------------------------
Information about the Periscope "shell account" automatically created for users who broadcast live on Twitter.
* id: Unique id for the account.
* displayName: Account’s name as displayed on its Twitter profile.
* username: Current @username of the Twitter account.  (NOTE: @username may change, but account_id remains the same).
* isBanned: Indicates whether the account is suspended or not.
* createdAt: Time account was created.
* isTwitterUser: Flag to indicate if the account is also a Twitter user; should always be true.
* twitterId: Unique id of the associated Twitter account.
* twitterScreenName: Current @username of the associated Twitter account (NOTE: @username may change, but twitterId remains the same).
* isTwitterVerified: (optional) Indicates if the associated Twitter account is a verified Twitter user account.

account-creation-ip.js
----------------------
IP address used when the account was created.

screen-name-change.js
---------------------
Records of changes to this account’s @username.
* accountId: Unique identifier for the account that performed the action.
* changedAt: Date and time of action.
* changedFrom: Previous screen name.
* changedTo: New screen name.

account.js
----------
Basic account information.
* accountId: Unique identifier for the account.
* createdAt: Date and time of account creation.
* createdVia: Client application used to create account.
* username: Account’s current @username (NOTE: @username may change, but account_id remains the same).
* accountDisplayName: Account’s name as displayed on its profile.

phone_number.js
---------------
Phone number provided by the user and which is associated with the account.

block.js
--------
Other accounts blocked by this account.

device-token.js
---------------
List of known device token(s).
* token: Token associated with a mobile device or web browser that was used to sign up or log in to this account through twitter.com or one of the other Twitter owned or operated apps within the last 18 months.
* lastSeenAt: Date and time of most recent use. Please note that there may be instances where older tokens do show this information.
* clientApplicationId: Unique identifier of the application associated with the token. Please note that there may be instances where older tokens do not have a unique identifier associated with them.
* clientApplicationName: Name of the application associated with the token. Please note that there may be instances where older tokens do not have an application name associated with them.
* createdAt: Data and time of the creation of the token.

saved-search.js
---------------
Searches saved by this account.
* savedSearchId: Unique identifier for the search.
* query: Actual search query.

verified.js
-----------
Account’s verification status.
* accountId: Unique identifier for the account that performed the action.
* verified: Verification status of the account.

protected-history.js
--------------------
History of a user protecting (that is, restricting only to their followers) and unprotecting their Tweets within the 6 months prior to the date this file was created. At the time of account creation, Tweets are unprotected by default.

like.js
-------
Tweets marked as ‘Favorites’ or ‘Likes’ by this account.
* tweetId: Unique identifiers for the Tweets liked.
* expandedUrl: Tweets URL.
* fullText: (optional) Tweets full text.

periscope-expired-broadcasts.js
-------------------------------
Live broadcasts on Twitter that have expired and cannot be encoded.
* broadcastIds: A list of the broadcast id’s that have expired.
* reason: Explanation of why broadcast replay files are unavailable (hard-coded).
