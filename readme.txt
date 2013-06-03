=== optiontree Shortcode ===
Contributors: ethanpil
Tags: shortcode, optiontree, ot_get_option
Requires at least: 3.0
Tested up to: 3.5.1
Stable tag: trunk
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Add a [ot_get_option] shortcode to the Wordpress editor to include data from OptionTree.

== Description ==

This plugin adds a shortcode [ot_get_option] to pull info from like the function ot_get_option(). Its very simple to use and supports the same values as ot_get_option().

If you aren't using OptionTree ( http://wordpress.org/plugins/option-tree/ ) this will probably be useless for you!

Its used like this:

    [ot_get_option option_id="XYZ" default="123"]

This is the equivalent of the following in PHP:

    ot_get_option("XYZ","123");

Fork away: https://github.com/ethanpil/wp-optiontree-shortcode

== Installation ==

1. Upload `wp-optiontree-shortcode.php` to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Include the [ot_get_option] shortcode in your editor....

== Frequently Asked Questions ==

= I dont see any settings or options! =

There arent any!

= How to I enable it? =

If the plugins system has it on then its working.

== Screenshots ==

There is nothing to see here.

== Changelog ==

= 1.0 =
* Hello World!