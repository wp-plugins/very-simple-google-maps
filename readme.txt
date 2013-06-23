=== Very Simple Google Maps ===
Contributors: MasterK
Tags: maps, direction, contact, google
Requires at least: 3.3
Tested up to: 3.5.2
Stable tag: 2.0
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Contains a simple way to add an embedded Google Map to any page or post.

== Description ==

Contains a simple way to add an embedded Google Map to any page or post. See the FAQ for usage info.

== Installation ==

1. Upload the plugin to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Add shortcode to your post or page where map should appear.

== Frequently asked questions ==

1. Shortcodes what??

The shortcode you need to use is this:

`[vsgmap address="address to display"]`

2. What are the options for use with the shortcode?

The following options are available:
align="left" (default is left. Valid are left, right, center)

width="400" (default is 400. Any pixel dimension is valid)

height="380" (default is 380. Any pixel dimension is valid)

info_window="A" (default is A which displays marker popup. Other option is near and the marker popup will not appear until marker is clicked on)

zoom="14" (set the default map zoom level. Valid options are 1 through 16)

companycode="" (Enter Google string cid from company maps listing URL)

3. How do I find the Google cid code???

Find your company listing on a Google Maps result page and click the link to email the link. It will open an email and the full link will be visible. The cid # is usually easy to see. you only need the part after cid= you do not need the whole thing.

4. How can I put a border around the map?

The plugin warps the embed withing a div so this cam be achived with css.
Simply add the following to your themes style.css
.vsg-map iframe { border: 1px solid; }

Of course you can change the css any way you like.

== Changelog ==

Version 2.0 is the first public and stable version.
