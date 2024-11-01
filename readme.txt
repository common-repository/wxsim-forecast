=== Plugin Name ===

Contributors: Rob Douglass
Donate link: http://www.jmrwebsolutions.co.uk
Tags: weather, wxsim, forecast
Requires at least: 3.3
Tested up to: 3.4.2
Stable tag: 2.1

Displays WXSIM forecast on a specific page of your wordpress site.

== Description ==

This Plugin is just a port from Saratoga weather scripts for use in Wordpress

Original Concept: Ken True - http://www.saratoga-weather.org/index.php 

== Installation ==

1. Unzip and upload files the files to `/wp-content/plugins/WXSIMforecast/`
2. Activate the plugin
3. Go to Settings then WXSIM forecast
4. Specify weather station
5. Specify where to get the plaintext file from (this is the folder you upload to)
6. Temperature can either be Celsius or Fahrenheit
7. Language is by default English however you can download translations from http://www.saratoga-weather.org/
8. Max width can be either a percentage or pixel value and this is the space allowed for the forecast
9. Max Icons is the number of Icon you want to display which restricts the amount of days displayed
10. Minimum Probability of Precipitation(PoP) - PoP percentage must equal this value or above to display rain icon, otherwise the sky icon with PoP is displayed.
11. Display Beaufort - Set to V' for no Beaufort and set to 'T' for translated name
12. Show Humidity Index - Selecting "No" will disable the humidity index from being displayed.
13. Show Frost - Selecting "No" will disable the Frost from being displayed.
14. Show Heat Index - Selecting "No" will disable the heat index from being displayed.
15. Show Hot icon - Heat Icon will be displayed if the value is equal to or greater than the value entered (Fahrenheit)
16. Show Hot icon - Heat Icon will be displayed if the value is equal to or greater than the value entered (Celcius)
17. Show Windchill - Selecting "No" will disable Windchill from being displayed.
18. Show Cold - Cold Icon will be displayed if the value is less than or greater than the value entered (Fahrenheit)
19. Show Cold - Cold Icon will be displayed if the value is less than or greater than the value entered (Celcius)
20. UOM Temperature - Selecting either °C or °F this value should match forecast temperature
21. TimeZone - Please enter your timezone Visit the following to identify the correct value http://php.net/manual/en/timezones.america.php
22. Show Animated images - Selecting "No" will show static images and selecting "Yes" will show animated images.

To add the widget to a posts and/or pages use the shortcode [forecast]
You can now pass a language parameter in the shortcode to allow for multilinguaal forecast throughout your site [forecast lang = cy]. You must have a valid plaintext-parser-lang file for this to work.

== Frequently Asked Questions ==

1. This will only work if you are running WXSIM and upload data from this to the web, IT IS NOT A STANDALONE PLUGIN

== Screenshots ==

None

== Changelog ==

= 2.1 - 19.11.2012 =
* Fixed error stopping you getting into the admin area

= 2.0 - 12.11.2012 =
* Fixed numerous bugs in code
* Added a number of additional configuration items
* Added shortcode parameter for multilingual functionality
* Included animated images

= 1.0 - 21.10.2010  =
* Fixed numerous bugs in code
* Fixed CSS problems including all alignment issues
* Add three new option in the admin section
* Fixed Image alignment fault

= 0.2 - 07.10.2010  =
* upgrade to latest version of script from Ken
* Fixed a display problem with regarding the number of days forecast
* Implemented a CSS file and specified font size for plug in
* Fixed language problem.  Now shows the correct language.

= 0.1 - 17.03.2010  =
* initial release


== Upgrade Notice ==


== Arbitrary section ==


== A brief Markdown Example ==
