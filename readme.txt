===SEContactForm (SMS Email Contact Form)===
Contributors: mobiweb
Tags: contact, form, contact form, feedback, email, ajax, captcha, SMS
Requires at least: 3.0
Tested up to: 3.3
Stable tag: trunk
License: GPLv2 or later

Contact form plugin, with  SMTP, SMS notification, CAPTCHA and easy configuration.

== Description ==

SEContactForm (SMS Email Contact Form) comes with email SMTP and send mail capability. It is integrate with http://isms.com.my to provide SMS notification capability. 
SEContactForm support CAPTCHA for spam filtering, it comes with predefined columns and user can choose to add in as many as 30 fields in a form.
ISMS.com.my is able to send SMS worldwide with prepaid credit.

= Plugin's Official Site =

SEContactForm (SMS Email Contact Form) ([http://isms.com.my/se_contact_form.php](http://isms.com.my/se_contact_form.php))

== Installation ==

1. Upload the entire `secontactform` folder to the `/wp-content/plugins/` directory.
2. Activate the plugin through the 'Plugins' menu in WordPress.
3. Use shortcode [secontactform] anywhere in your post or page to show the form.

You will find 'SE Contact Form' menu in your WordPress setting panel.

For basic usage, you can also have a look at the [plugin homepage](http://isms.com.my/se_contact_form.php).

== Frequently Asked Questions ==

= For SMTP =
1. Setup SMTP account according to your provider.
2. With SMTP, some server may not work. It depends on your provider.

= For iSMS =
1. Purchase the SMS credit at isms.com.my, the SMS credit supports worldwide.
2. Then set your username and password into the form to send SMS notification when anyone submitted the inquiry.

[Support](http://isms.com.my/se_contact_form.php)
Contact us for any issue, bug fix.

== Changelog ==
= 1.2.2 =
* Updated SMS send function to use cURL instead of f_open
* Updated SMS link to use iSMS SSL link
* Added auto response for SMS

= 1.2.1 =
* Added SMTP debug option for better SMTP error handling and debugging
* Tailing semi-colon are removed from destination email automatically while sending email

= 1.2.0.1 =
* Fixed a small bug that causes warning

= 1.2.0 =
* Some update to CSS style to correct interface problem in admin page
* Added auto response feature

= 1.1.8 =
* Some additional parameters in url are removed on each form submit to prevent them from stacking

= 1.1.7 =
* More bug fixes

= 1.1.6 =
* More bug fixes

= 1.1.5.2 =
* More bug fixes

= 1.1.5.1 =
* Some small bug fixes

= 1.1.5 =
* Folder secontactform removed
* Renamed readme.txt

= 1.1.4 =
* Changed country field from text field to select field
* A default list of countries are preloaded
* Added option to define own list of countries

= 1.1.3 =
* Updated error in custom field 1 loading values in custom field 2
* Captcha field correctly aligned

= 1.1.2 =
* Added some icons to messages

= 1.1.1 =
* Updated some interface and CSS

= 1.1.0 =
* Updated bugged mobile phone field in both javascript and form
* Some functions rewritten to return values instead of printing output directly
* Removed some extra texts at the top that was not removed in the last revision
* Existence of a session is checked before starting a session
* Parameters prevented from stacking behind URL
* Moved includes into function to fix extra bytes problem when installing the plugin
* Fixed message required name typo
* Allow redirect to work in both pretty URL enabled and non-pretty URL enabled wordpress
* Script property exited after redirects

= 1.0.0 =
* Initial release
