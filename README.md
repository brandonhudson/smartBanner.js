smartBanner.js
==============

Smart Banner JS - Universal/Customizable App Bannering for Web

Functionality
-------------

Simply add** the included javascript, css, and custom font package to your website and configure (Steps Below)! This smart banner plugin is capable of large customization, including two modes, web-app and native-app, which provide different uses depending on the use case. This plugin support smart User Agent detection on all three major platforms: iOS, Android, and Windows Phone.

**To add this plugin to your website, place the CSS and JS files anywhere into your website's directory. Note that the CSS file and the SB-fonts folder MUST be placed in the same directory in order for the banner to display properly.

API
---

Place the following code directly into any page that you would like to display the banner on, or create a custom .js file, place this code inside, and simply link that custom file to any page you would like to have a banner on

```javascript
SmartBanner({
//parameters
});
```

Parameters
----------
**title**: "title" - Title of the Application/Web-Application

**iconpath**: "path/to/icon.png" - Path to your application Icon

**developer**: "Developer Name" - Application Developer's Name

**price**: "price" - Price of your Application (Include $ for values like e.g. $1.00)

**position**: "position" - Position to show banner
<ul>
  <LI>Options:</LI>
  <ul>
  <LI>"top-push" - pushes page down and places banner at the top of the page</LI>
  <LI>"top" - places banner at the top of the page, over all content at the top</LI>
  <LI>"bottom" - places banner tha the bottom of he page, over all content at the bottom</LI>
  </ul>
  </ul>
	
**mode**: "app-type" - select a mode to run your banner in
<ul>
	<LI>Options:</LI>
	<UL>
	<LI>"web-app" - In web-app mode, the VIEW button is changed to ADD, and when tapped, provides device-specific instructions on how to add the web-app to the homescreen
	</LI>
	<LI>
	"native-app" - In native-app mode, the VIEW button provides a link to the device-specific app store where your           application is being sold
	</LI>
	</UL>
	</ul>
	

**ios**: "true/false" - Support smart banner on iOS (True = Support / False = No Support)

**android**: "true/false" - Support smart banner on Android (True = Support / False = No Support)

**windows**: "true/false" - support smart banner on Windows (True = Support / False = No Support)

**applinkios**: "http://www.itunes.com/apps/yourapp" - Link to your application in the iOS App Store

**applinkandroid**: "https://play.google.com/store/apps/details?id=yourappID&hl=en" - Link to your application in the Google Play Store

**applinkwindows**: "http://apps.microsoft.com/windows/en-us/app/yourapp" - Link to your application in the Microsoft Store

**messageios**: "on the App Store" - Message to display for iOS users

**messageandroid**: "on Google Play" - Message to display for Android users

**messagewindows**: "on the Microsoft Store" - Message to display for Windows users

**force**: "ios/android/windows" - Force the Banner on a specific platform 

**theme**: "dark/light" - Use a preset theme on the banner

**alertfadespeed**: 400 - speed that the animation should fade away (any number)

**alertdelay**: 3000 - timeframe that the banner should be present after the user engages it (for use with web-app mode)

**bannerslidespeed**: 200 - speed that the banner should slide at (any number)

**cookiedays**: -1 // -1 means no cookies will be used and banner will display every time

