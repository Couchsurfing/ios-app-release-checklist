## Couchsurfing 

|Overview Info|Details|
|:-------------------------------------|-------------------------------------:|
| App name                             |      TBD                             |
| Version                              |      TBD                             |
| Date of submission                   |      TBD 		                        |

This checklist confirms that all major areas of testing have been completed prior to a build Release to the App Store.

This version has been adjusted for the requirements of Couchsurfing (in particular, an app baseline of iOS 6.1) and 
should be applicable for any app built for the company. 

--

###Internet Connectivity
Test all the data downloading sections of the app by trying them on the appropriate connection type. Consider graceful degradation and failure as well as success conditions.

| Connection | N/A | NO | YES |
|:---|:---:|:---:|:---:|
| Wifi | | | |
| Edge | | | |
| GPRS | | | |
| No Network (Airplane Mode) | | | |
| Intermittent Network (use Charles to simulate) | | | |
| Server unreachable - timeout | | | |
| Resumed connect - multi-part File Transfer | | | |

--

###Locale
Change device’s settings then load the app. Check that dates appear correctly, especially dates from external feeds or services.

| Locale | N/A | NO | YES |
|:---|:---:|:---:|:---:|
| 12 and 24 hour clocks | | | |
| | | | | 
| **Regions** 
| United States | | |
| Australia | | |
| UK |||
| France | | |
| Netherlands | | |
| Spain | | |
| Italy | | |
| China | | |
| Poland | | |
| Brazil | | |
| Russia | | |
| Turkey | | |
| Korea | | |
| | | | |
| **Languages**
| English | | |
| French | | |
| Dutch | | |
| Espanol | | |
| Italiano | | |
| Chinese (Mandarin) | | |
| Polish | | |
| Portuguese | | |
| Korean | | |
| Russian | | |
| Turkish | | |
| | | | |
| Timezones  | | | |
| Daylight Savings Time | | | |

--

###Translation
Confirm that translation testing has been completed by a native speaker for each language supported in the app. 

||Included in App| Confirmed as Appropriate|
|:---|:---:|:---:|
| **Languages**
| English | | |
| French | | |
| Dutch | | |
| Espanol | | |
| Italiano | | |
| Chinese (Mandarin) | | |
| Polish | | |
| Portuguese | | |
| Korean | | |
| Russian | | |
| Turkish | | |



--

### Devices
Run the application through navigations using different devices with different iOS versions and display formats.

| Device | N/A | NO | YES |
|:---|:---:|:---:|:---:|
| iPhone / iPod touch running iOS 6.1.x | | | |
| iPhone / iPod touch running iOS 7.0.x | | | |
| Retina iPhone display | | | |
| Non-retina iPhone display | | | |
| | | | |
| Retina iPad display | | | |
| Non-retina iPad display | | | |
| iPad mini display | | | |

--

### Audio
If app plays audio, perform the following checks. For streaming audio, make sure the checks in the network section above have also been done.

| Audio | N/A | NO | YES |
|:---|:---:|:---:|:---:|
| Headphones/speaker routing  | | | |
| Dock connector audio out routing   | | | |
| iPod touch audio routing (consider model without speaker) | | | |
| Mute switch functionality (officially it mutes non-user-requested sounds) | | | |
| Audio pause on received phone call | | | |
| Background audio (if supported): playback and multitasking bar controls | | | |
| Start playing audio when another app is already playing | | | |
| Headphone remote for audio control | | | |
| Multitasking screen audio control | | | |

--

###Video
Streaming video should have been checked in the network tests.

| Video | N/A | NO | YES |
|:---|:---:|:---:|:---:|
| User cancels video before playback begins  | | | |
| User cancels video during playback  | | | |
| Video plays to the end  | | | |
| Video return from full screen  | | | |
| Dock connector video out  | | | |
| Video transition between inline and full screen  | | | |

--

###Location

| Location | N/A | NO | YES |
|:---|:---:|:---:|:---:|
| True GPS | | | |
| Wifi location | | | |
| Cell tower location | | | |
| Unable to find location | | | |
| No results returned (e.g. too far from any searchable points of interest)  | | | |
| Location services turned off | | | |
| Location services disabled for this app | | | |

--

###Logging

| Confirmed as appropriate | N/A | NO | YES |
|:---|:---:|:---:|:---:|
| Logging events to live server | | | |
| Logging errors | | | |
| Flurry |  |  |  |
| Crashlytics|  |  |  |

--

###User Interface
Test each major view in the app.

| Title | N/A | NO | YES |
|:---|:---:|:---:|:---:|
| Double height status bar (eg in call) | | | |
| Orientation change | | | |
| Upside-down orientation | | | |
| Orientation lock | | | |
| VoiceOver turned on | | | |
| Usable by a new user with Screen Curtain turned on | | | |
| Works with Accessibility Zoom turned on | | | |

--

###Core Data

| Core Data | N/A | NO | YES |
|:---|:---:|:---:|:---:|
| Validation error in user input | | | |
| Validation error in web server input | | | |
| Test migrations with valid and invalid data files | | | |

--

###Installation

| Installation | N/A | NO | YES |
|:---|:---:|:---:|:---:|
| Fresh install | | | |
| Upgrade from previous live version | | | |
| Upgrade from older live version | | | |

--

###Text

| Title | N/A | NO | YES |
|:---|:---:|:---:|:---:|
| Shake to Undo | | | |
| Text selection (including disabled when appropriate) | | | |
| Copy / Paste | | | |
| Editing when keyboard is hidden | | | |

--

###Third Party Services
All third party services should use production API key and the new app version should be registered in the respective dashboards

| Title | N/A | NO | YES |
|:---|:---:|:---:|:---:|
| Production analytics/tracking API key | | | |
| New app version tracking data available tracking in dashboard | | | |
| Production crash reporting API key | | | |
| Upload dSYM to crash reporting tool | | | |
| New app version available in crash reporting dashboard | | | |
| Push notification service API key | | | |
| New app version added to push service dashboard | | | |
| Production App ID for social services (Twitter, Facebook, Instagram, etc) | | | |

--

###Misc

| Misc | N/A | NO | YES |
|:---|:---:|:---:|:---:|
| Motion | | | |
| Tested in Ad Hoc mode | | | |
| Version number upgraded | | | |
| Bundle identifier correct for release | | | |



###iTunes Connect

| Misc | N/A | NO | YES |
|:---|:---:|:---:|:---:|
| Artwork organized for iTunes Connect ||||
| Marketing copy organized for iTunes Connect ||||
| Search terms organized for iTunes Connect ||||
| Version placeholder setup (set to manual release) | |||
| Test Submission completed | | | |


--
<br><br>
