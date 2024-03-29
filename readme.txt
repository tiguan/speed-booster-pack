﻿=== Speed Booster Pack ===
Contributors: tiguan
Donate link: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=EH65WAWPEYPXU
Tags: speed, optimization, performance, speed booster, scripts to the footer, Google Libraries, CDN, defer parsing of javascript, remove query strings, lazy load, lazy load images, GTmetrix, Google PageSpeed, YSlow
Requires at least: 3.6
Tested up to: 3.9.1
Stable tag: 1.7
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Features options to improve your website performance and get a higher score on the major speed testing services.

== Description ==

Speed Booster Pack allows you to improve your page loading speed and get a higher score on the major speed testing services such as [GTmetrix](http://gtmetrix.com/), [Google PageSpeed](http://developers.google.com/speed/pagespeed/insights/), [YSlow](https://developer.yahoo.com/yslow/), [Pingdom](http://tools.pingdom.com/fpt/), [Webpagetest](http://www.webpagetest.org/) or other speed testing tools.

= Why Site Speed Is Important =

When visitors lands on your site for the first time, you only have 3 seconds to capture their attention and convince them to stick around. That's not convinced you? Read on:

* Google incorporating site speed in search rankings
* 47% of online consumers expect a web page to load in 2 seconds or less
* 40% of people will abandon a site that takes more than 3 seconds to load
* 80% of online consumers are less likely to return to a slow website

= Main Plugin Features =

* **Moves scripts to the footer** to improve page loading speed.
* **Loads javascript files from Google Libraries** rather than serving them from your WordPress install directly, to reduce latency, increase parallelism and improve caching.
* **Defers parsing of javascript files** to reduce the initial load time of your page.
* **Removes query strings from static resources** to improve your speed scores.
* **Lazy load images** to improve page load times and save bandwidth.
* **Removes extra Font Awesome stylesheets** added to your theme by certain plugins, if *Font Awesome* is already used in your theme.
* **Removes junk header tags** to clean up your WordPress Header.

= Page Load Stats =

Page Load Stats is a brief statistic displayed in the plugin options page. It displays your homepage loading speed (in seconds) and number of processed queries.

**Page loading time** – the progress bar color will be:

* *green* if the page load takes less than a second
* *orange* when loading the page takes between 1 and 2 seconds
* *red* if the page loading takes longer than 2 seconds

**Number of executed queries** – the progress bar color will be:

* *green* if there were less than 100 queries
* *orange* if there were between 100 and 200 queries
* *red* if the page required more than 200 queries

= Other Notes =

* For complete usage instructions visit [Plugin Documentation](http://tiguandesign.com/docs/speed-booster/)
* Thanks to [Jason Penney](http://jasonpenney.net/) for Google Libraries feature.
* Credits for Lazy Load feature belongs to: WordPress.com VIP team at Automattic, the TechCrunch 2011 Redesign team, and Jake Goldman (10up LLC).
* Uses [jQuery.sonar](http://www.artzstudio.com/files/jquery-boston-2010/jquery.sonar/) by Dave Artz (AOL).

== Installation ==

1. Download the plugin (.zip file) on your hard drive.
2. Unzip the zip file contents.
3. Upload the `speed-booster-pack` folder to the `/wp-content/plugins/` directory.
4. Activate the plugin through the 'Plugins' menu in WordPress.
5. A new sub menu item `Speed Booster Pack` will appear in your main Settings menu.

== Screenshots ==
1. Plugin options page, simple view (v1.7)

== Changelog ==

= 1.7 =
* Fixed Lazy Load missed js.

= 1.6 =
* Fixed some errors and missed codes from plugin fuctions.

= 1.5 =
* Added Lazy Load feature to improve the web page loading times of your images.
* Added an option to remove all rss feed links from WP Head.
* Added plugin options informations to the footer, visible in page source, useful for debugging.

= 1.4 =
* Added a new option to remove extra Font Awesome stylesheets added to your theme by certain plugins, if Font Awesome is already used in your theme.
* Added a new option to remove WordPress Version Number.

= 1.3 =
* Fixed strict standards error: redefining already defined constructor for class.

= 1.2 =
* Modified the plugin version number variable in plugin options page.

= 1.1 =
* Modified Readme file

= 1.0 =
* Initial release