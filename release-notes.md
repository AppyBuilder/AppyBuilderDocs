# Release Notes

This page lists AppyBuilder Release dates / notes in reverse chronological order. Join Community here: [http://Community.AppyBuilder.com](http://Community.AppyBuilder.com)

---

![](/assets/ab_icon.png) Jan 31, 2018 [**Companion v4.02**](https://play.google.com/store/apps/details?id=com.appybuilder.companiongold)

Updates to **Notifier component**. It now includes updated design and features:

* Ability to include html tags
* Ability to include hyperlinks
* Ability to contain large amount of text with scrolling feature
* Animation from top, side, bottom \(animationStyle 1 to 3\)

![](/assets/notifier2.png)

---

![](/assets/ab_icon.png) Jan 28, 2018 [**Companion v4.01**](https://play.google.com/store/apps/details?id=com.appybuilder.companiongold)

* **Feature:** Notifier - Updated ShowAlert to use fancy material design interface with images
   \(ref 24 [HERE](https://github.com/AppyBuilder/AppyBuilder/issues/24)\). 
  * Block also includes slot for showAtBottom. If true, displays at bottom or at center
  * Block also includes alertType \(1 through 6\) for different alert types
* **Feature:** Notifier - Updated ShowChooseDialog to use fancy material design interface. 
  * Block also includes a slot for animationType \(1 through 3\) that allows you to animate the pop-up from Top, Side or Bottom
* **Feature:** Notifier - Updated ShowMessageDialog to use fancy material design interface. 
  * Block also includes a slot for animationType \(1 through 3\) that allows you to animate the pop-up from Top, Side or Bottom
* **Feature:** Now includes block and designer property for adding TitleColor \(ref 22 [HERE](https://github.com/AppyBuilder/AppyBuilder/issues/22)\) \(Sync with MIT AI\)
* **Bug Fix:** Map FeatureCollection icon was not displaying during drag
* **Feature:** ListViewCuston - Now includes ability to load images from SD Card \(ref 18 [HERE](https://github.com/AppyBuilder/AppyBuilder/issues/18)\)
* **Feature:** WebViewer Added designer and block for opening a WebViewer in external browser \(ref 10 [HERE](https://github.com/AppyBuilder/AppyBuilder/issues/10)\)
* **Feature:** Added color palette wheel to designer color property
   \(ref 25 [HERE](https://github.com/AppyBuilder/AppyBuilder/issues/25)\)
* **Feature:** Accelerometer: Implements a workaround for an Android issue that would cause the Accelerometer to switch X and Y directions on some landscape mode devices \(sync with MIT AI\)
* **Feature:** Blocks editor Text drawer: Added an “is-text?” block to test whether a value is a string \(ref 26 [HERE](https://github.com/AppyBuilder/AppyBuilder/issues/26)\)

![](/assets/notifierMaterial.png)

---

![](/assets/ab_icon.png) Jan 16, 2018 [**Companion v3.26**](https://play.google.com/store/apps/details?id=com.appybuilder.companiongold)

* **CloudDB** Component: New. EXPERIMENTAL -  Integrated CloudDB, allowing you to store / retrieve data from cloud server
* **Slider**: Fixed bug. When ThumbEnabled was set to false, Slider Thumb was disappearing 
* **LinedTextBox: **Moved from Experimental to User Interface category

* **UI/UX:** Logo update - \(\_Thanks to Peter Mathijssen for his work\)

* **Extension: **Bug fix. UsesPermissions annotation with empty string was resulting in invalid manifest

* **Label** - feature: Added ReadMore property / block. If set TRUE, it will make automatically make the Label expandable and collapsable \(_**Thanks to Andres Cotes for his input**_\)

* ![](/assets/labelReadMore.png) ![](/assets/readmore2.png)

---

**AppyBuilder needs your support:**

[http://AppyBuilder.com/appybuildersupport.html](https://www.gitbook.com/book/appybuilder/reference/edit#)

![](/assets/ab_icon.png) Dec 31, 2017 [**Companion v3.25**](https://play.google.com/store/apps/details?id=com.appybuilder.companiongold)

**Map Component**: New Integrated MIT latest Openstreet Map component. For more information, see [HERE](http://gold.appybuilder.com/reference/components/maps.html#Map).

* * Simple Map .aia that was developed by Evan from MIT can be found [HERE](http://AppyBuilder.com/tutorials/openstreet/MapsSimple.aia) \(NOTE: GPS location services needs to be turned on

![](/assets/mapOpenStreet.png)

* **MemoryInfo**: Non-visible sensor component to get information about device memory and SD Card

![](/assets/memoryInfo2.png)

---

![](/assets/ab_icon.png) Dec 11, 2017 [**Companion v3.24**](https://play.google.com/store/apps/details?id=com.appybuilder.companiongold) - **AppyBuilder needs your support:** [http://AppyBuilder.com/appybuildersupport.html](http://appybuilder.com/appybuildersupport.html)

* **HorizontalArrangement:** Updated _**IsCard**_ \[1\]so that it now setups margins all around the border 
* **VerticalArrangement:** Updated _**IsCard**_ \[1\]so that it now setups margins all around the border
* **HorizonalArrangement:** For above, updated Card border background to match the Material Card color
* **VerticalArrangement:** For above, updated Card border background to match the Material Card color
* **Feature: **Arrangements now include UseRoundCorners block. If set to false, the Material Design card will use Rectangle corners, else Round Corners: ![](/assets/materialCard2.png)
* **FTPManager:** Added _**DeleteFolder**_ block._** Can delete non-empty remote or local folders**_. For remote, use  /public\_html/folder1/folder2/... and for local use /folder1/folder2/... ![](/assets/ftpManager.png)
* **UX:** When deleting component, now displays GWT pop-up window
* **Feature:** Added _**Click**_ event-block to all layout arrangements
* **Feature:** Added _**LongClick**_ event-block to all layout arrangements
* Feature: Added StatusBarColor block ![](/assets/statusBarColor.png) to Screen. NOTE: Designer won't show color-change.
* **Bug fix:** Updated ListView _**TextSize**_ so that it now can dynamically change text size
* **Bug fix:** Updated ListViewCustom _**TextSize**_ so that it now can dynamically change text size
* **Memory issues:** Performs memory management for loading images and reduces the Out Of Memory issues

**\[1\]**

** **![](/assets/materialCard.png)

---

![](/assets/ab_icon.png) Nov 27, 2017 [**Companion v3.23**](https://play.google.com/store/apps/details?id=com.appybuilder.companiongold) - **AppyBuilder needs your support:** [http://AppyBuilder.com/appybuildersupport.html](http://appybuilder.com/appybuildersupport.html)

* **Screen: **Added padding to Screen for top, left, bottom, right. Padding can be specified as single number \(e.g. 5\), or 4 numbers \(e.g. 6,7,8,9 for top, left, bottom, right\)
* **Layout Arrangements: **Material Card representation. New property / block \(IsCard\) in Horizontal / Vertical Arrangement. If set to true, arrangement will be converted to Material Card
* **OneSignalPush**: Added blocks for SubscriptionEnabled, VibrateEnabled, SoundEnabled
* Fix messages in some non-English translations \(e.g. Chinese\)
* Display an extension’s version in the help widget
* Perofmance improvement: Prevent error checking on block during drag
* **GalleryViewer**: added Thumbnail width, height in designer with default values
* Make TitleVisible property to toggle title bar's visibility \(Credits to Ben - @moliata on GitHub\)
* **NetworkManager**: New component to get network information, such as below. See doc [HERE](https://help.appybuilder.com/components/networkmanager.html) for details
  * if connected through WiFi, mobile, ...
  * If GPS is on
  * Start GPS options
  * Connection speed; slow, medium, fast

![](/assets/androidCards2.png)

---

![](/assets/ab_icon.png) Oct 28, 2017 [**Companion v3.22**](https://play.google.com/store/apps/details?id=com.appybuilder.companiongold) - AppyBuilder Gold Support / Contribution? [**http://PayPal.me/AppyBuilder**](https://www.gitbook.com/book/appybuilder/reference/edit#) :o\)

* Browser bug fixes
* Chrome browser performance update
* Now **FREE **to everyone - no membership required. Just log into [http://Gold.AppyBuilder.com](http://Gold.AppyBuilder.com)
* For forum community please sign into here: [http://Community.AppyBuilder.com](http://Community.AppyBuilder.com)

---

![](/assets/ab_icon.png) Oct. 11, 2017 [**Companion v3.21**](https://play.google.com/store/apps/details?id=com.appybuilder.companiongold) - AppyBuilder Gold -

* Bugfix - **Chrome **latest update \(61\) introduced issue with drop-down position of pop-up menus. This was observed when in Design Editor. Issue resolved
* Feature - **KitchenSink**: Now includes block _**IsKeyboardOpen**_
  \*\*
* Feature - **VideoPlayer**: Added **ControlsEnabled **_peroperty / block_. Allows you to show/hide the controls. By default, its set to enabled
* Feature - **UI **- Added ability to preview media - _**\(Thanks to Aaron Suarez for his contribution **_[_**HERE**_](https://github.com/mit-cml/appinventor-sources/pull/764)_**\)**_
* Feature - **UI**: Added ability to drag & drop media files for upload into assets_** \(Thanks to Aaron Suarez for his contribution **_[_**HERE**_](https://github.com/mit-cml/appinventor-sources/pull/763)_**\)**_
* Feature - **Switch **component - Click event: Now includes 'isChecked' paramter that indicates if Switch is Checked or Unchecked
* Feature - **Checkbox **component - Changed event: Now includes '_**isChecked**_' parameter that indicates if Switch is Checked or Unchecked
* Bugfix - Fixed scrolling issue, in both Designer and Blocks-editor:  [http://community.appybuilder.com/t/please-fix-that-scroll-does-not-go-back-to-top/1246/3](http://community.appybuilder.com/t/please-fix-that-scroll-does-not-go-back-to-top/1246/3)
* Feature - Added **EXPERIMENTAL LinedTextBox **component. This is same as TextBox component, however, it includes notepad like lines and is always multiline
* Bugfix - **OneSignalPush **- some devices were experiencing issues at certain times when push message was received. Issue is now fixed

---

![](/assets/ab_icon.png) Sept. 28, 2017 [**Companion v3.19**](https://play.google.com/store/apps/details?id=com.appybuilder.companiongold) - AppyBuilder Gold_** **_

* Feature - **Label**: now has _Click_ events can be used to simulate tabs
* Feature - **Label**: now has _LongClick_ events
* Feature - **ListViewCustom**: now can accept SIMPLE html text 
* Feature - New **OneSignalPush** notification component \(Advanced category\) -- See component tutorial [HERE](https://help.appybuilder.com/components/onesignalpush.html)
* Feature - **Label**: _Designer_ now provides draggable text-entry for entering text. This will be useful when entering long text in designer
* Feature - **TextBox**: _Designer_ now provides draggable text-entry for entering text. This will be useful when entering long text in designer
* Feature - **CheckBox**: Added _CheckboxColor_ property & block \(default Dark Gray\)
* Enhancement - **Spinner**: Made spacing between drop-down items wider \(when ShowRadioButton is false\)
* Feature - Added **Windows USB Live Testing** ability. Download the installer zip file from [**HERE**](http://AppyBuilder.com/companion/AppyBuilderStarterSetup.zip) and unzip and run the .msi instller app, which will install AppyBuilder-installer-app into "**C:\Program Files \(x86\)\AppyBuilder Starter**" folder. It will also create a shortcut on your Desktop: ![](/assets/StarterApp3.png) Follow setup direction [**HERE**](https://help.appybuilder.com/live-testing.html)
* BugFix - **WebViewer** _geolocation_ was not working properly
* BugFix: **ListViewCustom** _AfterDeleting_ was returning a zero-based position of deleted-item. Its been updated so that it is now starts from 1. See [**HERE**](http://community.appybuilder.com/t/custom-listview/1402/20) for details
* Documentation: **GalleryViewer** _AfterPicking_ block. Fixed block tooltip
* BugFix: Fixes a bug where the block position in older projects was sometimes forgotten. See [**HERE**](https://github.com/mit-cml/appinventor-sources/pull/931) for details

---

![](/assets/ab_icon.png) Aug 29, 2017 - [**Companion v3.18**](https://play.google.com/store/apps/details?id=com.appybuilder.companiongold) - AppyBuilder Gold

* Bug fix - Camera component update. Flash was not working on some devices. Now fixed
* Bug fix - ListViewCustom - text now shows left-aliged instead of centered
* Bug fix - ListViewCustom - Now can change FontSize
* Feature - ListViewCustom - New block for changing image size
* Feature - Spinner - now you can set background color
* Feature - Spinner - now you ShowRadioButtons for it
* Feature - UI - Minor UI/UX updates  
* Feature - New Switch component
* Feature - New RatingBar component
* Feature - New 3D shadow effect BLOCK \(SetShadow\) for Label
* Feature - New 3D shadow effect BLOCK \(SetShadow\) for TexBox 
* Feature - New 3D shadow effect BLOCK \(SetShadow\) for CheckBox 
* Feature - New 3D shadow effect BLOCK \(SetShadow\) for Button 
* Feature - New 3D shadow effect BLOCK \(SetShadow\) for ListPicker 

---

![](/assets/ab_icon.png) Aug 29, 2017 - [**Companion v3.17**](https://play.google.com/store/apps/details?id=com.appybuilder.companiongold) - AppyBuilder Gold - **Same as before, No need to re-install**

* Just a non-component release that included enhancement to Design Editor. It now includes Android phone background frame for the phone viewer 

---

###### ![](/assets/ab_icon.png) Aug 21, 2017 -  [Companion v3.17](https://play.google.com/store/apps/details?id=com.appybuilder.companiongold) - AppyBuilder Gold

* New component - **Added AdMob Rewards Video** - This component can be found under Monetize category
* New Component -** Millenium Media Interstitial Ad** - This component can be found under Montetize category

---

###### ![](/assets/ab_icon.png) July 26, 2017 - [Companion v3.16](https://play.google.com/store/apps/details?id=com.appybuilder.companiongold) - AppyBuilder Gold

* Bug fix - Creating new projects or even opening old projects, could’ve loaded some default extensions. This issue is now resolved.

---

###### ![](/assets/ab_icon.png) July 24, 2017 - [Companion v3.15](https://play.google.com/store/apps/details?id=com.appybuilder.companiongold) - AppyBuilder Gold

* Sound component - Added PlayRate
* ListView component - AfterDeleting block now includes position \(of the deleted item - index\)
* Notifier component  - Now includes Linkify for enabling the hyperlinks
* New ListViewCustom component -. Same as ListView, but now can include image and list item
* New ListPickerCustom component - Same as ListPicker, but now can include image and list item

---

###### ![](/assets/ab_icon.png) June 29, 2017 - [Companion v3.14](/ https://play.google.com/store/apps/details?id=com.appybuilder.companiongold) - AppyBuilder Gold

* Bug fix: Fixed crash for GoogleMap 
* Fixed issue with companion crashing on some devices

---

###### ![](/assets/ab_icon.png)  June 26, 2017 - [Companion v3.13](/ https://play.google.com/store/apps/details?id=com.appybuilder.companiongold) - AppyBuilder Gold

Added ability to include PackageName as a Screen1 property. Can be used even for apps with multiple screens

**Includes latest MIT AI updates below:**

_MIT AI Changes between nb155 and nb156 \(May 25, 2017\)_

_This is a non-component release, however it is a significant release because of a major upgrade to the Blocks Editor._

1. _Added the ability to zoom the workspace in/out. Zooming gestures include:_

2. 1. _Click the +/- buttons in the lower left corner above the trashcan._

   2. _Ctrl+Mouse wheel on a mouse._

   3. _Multi-touch trackpad users with Chrome, zooming can also be done with the pinch/expand gesture._
3. _Added the ability to pan the workspace. Panning gestures include:_

4. 1. _Mouse wheel up/down will pan the view vertical._

   2. _Wheels with 2-dimensional scrolling can also pan left/right._

   3. _Multi-touch trackpad users can pan in two dimensions using two-finger scrolling._
5. _Added Reset to center button will set the zoom back to 1:1 and move to the center of the blocks workspace._

6. _Added workspace grid. Right-clicking \(Ctrl+Click on Mac\) on the workspace brings up a context menu with "Enable Workspace Grid" option. This option is a user setting and will persist across workspaces and across App Inventor sessions._

7. _Added workspace snapping. If the grid is enabled, another menu option "Enable Snap to Grid" will be available. Enabling this option will make the top-left corner of blocks snap to the nearest grid point. This option is a user setting and will persist across workspaces and across App Inventor sessions._

---

###### ![](/assets/ab_icon.png) April 07, 2017 - [Companion v3.08](/ https://play.google.com/store/apps/details?id=com.appybuilder.companiongold) - AppyBuilder Gold

* Sync with MIT AI nb154a and nb155
* Make the Backpack persistent – If you leave AppyBuilder with blocks left in your backpack, they will be there the next time you login
* Updates to better support newer versions of Android
* Webviewer - Added new blockLoadHtmlblockwhich will allow you to useTextblock to type in any valid HTML string
* Webviewer now includes ability to upload files from local device

* Webviewer now includes ability to take picture for directly uploading to server. From Designer, just set AllowCamera to true \(NOTE: You will need to drag-n-drop a Camera component for this to work\)

* PasswordTextBox - Fixed Bug

![](https://lh3.googleusercontent.com/UZE-SYOLdf39xwQicXQAtgeGaRcNQ1IsJbs_9wF7WAmqemjFaKaXwtETtULSJVzz4jjjkXR_if2zAOskP39hbNn4lWaJFWB3GU_Bk6cdiioyWdLZ_h4PtibYqEBX8wjJvgdtSfw1)

