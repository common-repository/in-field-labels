=== In Field Labels ===
Contributors: dipali.dhole27@gmail.com
Donate link: http://webelusion.com/
Tags: wordpress plugins,In field labels,in-field labels,infield labels,In-field Form Labels
Requires at least: 3.0
Tested up to: 3.8.1
Stable tag: 2.0.0
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Properly formatted HTML forms turns into with in-field labels

== Description ==
This plugin turns properly formatted html forms into in-field labels.
This is integration with the <a href="http://fuelyourcoding.com/scripts/infield/">http://fuelyourcoding.com/scripts/infield/</a>
when the input field is focussed then label fade & entry begins in input field then label text disappered.
When clearing the field the label text reappears. 

= Html form format as below =

`<form id="test" method="post" >
<p>
  <label for="field_id">Label Text</label><br />
  <input type="text" name="field_id" value="" id="field_id" placeholder="">
</p>
</form>`



== Installation ==

Installing the In Field Labels plugin is very easy. Simply follow the steps below.

1. Extract the package to obtain the `in-field-labels` folder
1. Upload the `in-field-labels` folder to the `/wp-content/plugins/` directory
1. Activate the plugin through the 'Plugins' menu in WordPress
1. Configure the settings according to your needs through the **Settings > In Field Labels** menu
1. Add form id (not including # sign) separated with comma( like commentform,test )  in the 'In Field Labels' section


== Frequently Asked Questions ==
= What will be the html form formats =

Simple format of html forms

`<form id="test" method="post" >
<p>
  <label for="field_id">Label Text</label><br />
  <input type="text" name="field_id" value="" id="field_id" placeholder="">
</p>
</form>`


== Screenshots ==
1. Add form id's in the backend separated with comma.
2. form looks like in the front end.


== Changelog ==

= 1.0 =
* Initial release of the In Field Labels plugin
