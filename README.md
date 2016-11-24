Latest Version 
--------------
##### _Jul 12st, 2016_ - v1.4

Getting Started
---------------
Check out our [official documentation](https://www.devtodev.com/help/64/windows_8_1_10_integration/) to learn how to install the library on your IDE. You will also learn how to make use of all the features we currently support!

Changelog
---------
See [releases](https://github.com/devtodev-analytics/winstore-sdk/releases).

### Windows 8.1/10 and Windows Phone 8.1/10

#### Version 1.5
* Added interactivity to push-notifications: buttons, sharing, URLs, deeplinks, sound control.
* Ability to send “quiet push-notifications” 

#### Version 1.4
* Added new "Progression event". First of all, the event is used for the games with short (within one game session) locations, game levels. The event allows you to gather data on passing the locations and get statistics on parameters which vary during the the location passing.

#### Version 1.3.1
* WACK serfitication was fixed

#### Version 1.3
* User profile feature is added. Here you can store properties about a specific user.
 - New methods for managing preset and custom properties of user profile are added.
 - Old methods: age, gender and cheater, are removed. These properties are moved to user profile.
* Initial referrer data tracking method is added

#### Version 1.2.5
* Improved stability

#### Version 1.2.4
* Minor changes related to Microsoft approving process

#### Version 1.2.3
* Support of push-notifications is added

#### Version 1.2.2
* Improvement of the user identification in cross-platform projects

#### Version 1.2.1
* Improved compatibility with Acer devices

#### Version 1.2
* SDK preparation for usage in cross-platform projects: added methods for user initialization (UserID, ReplaceUserId, SetCurrentLevel).
* Optimization for Windows 10. WinMD library format.
* Minor changes in session length calculation.
* Other negligeable improvements.

### Windows Phone 8 (unsupported SDK)

#### Version 1.5.4 
* Bugfix with logging exceptions

#### Version 1.5.3
* Blocking of certain events from SDK.
* Improvement of new user calculation method.

#### Version 1.5.1
* The start/finish constants of the tutorial are added to the tutorial steps event.
* Filtering of resending for once committed tutorial steps is made.
* Constants with the names of popular social networks are added to connecting and posting to social networks events.
* Method for getting devtodev SDK integrated version.
* Method for immediate dispatching of events.

#### Version 1.5 
* Unified SDK! No more need to use multiple small files, it's enough to integrate one library.
* In-game purchases for several in-game currencies.
* An ability to track currency/resources circulation and balances upon moving to the next level.
