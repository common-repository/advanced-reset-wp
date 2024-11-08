=== Advanced Reset WordPress ===
Contributors: WebFactory
Tags: clean, clean database, cleaner, database clean, database reset, developer, installation, reset, reset database, reset wordpress, reset wp, restore, wordpress-reset, wp reset, wp-reset, remove post, remove page, delete plugins, delete themes
Requires at least: 4.6
Tested up to: 4.9.2
Stable tag: 1.3
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Re-install or reset WordPress, delete themes, plugins and posts, pages, attachments.

== Description ==

**This plugin has a new home in the WordPress repo - <a href="https://wordpress.org/plugins/wp-reset/">wordpress.org/plugins/wp-reset/</a> - Please download it from there as this repo will soon be deleted. Thank you!** New plugin has all the same features, is completely free and used by over 50,000 people. More info about <a href="https://wpreset.com/?utm_source=wordpressorg&utm_medium=content&utm_campaign=advanced-reset-wp&utm_term=wp%20reset">WP Reset</a>.

This plugin is very helpful for plugin and theme developers.

Resets the WordPress database back to it's defaults. Deletes all customizations and content.

In addition, our plug-in gives developers the ability to one-click delete themes or plugins. Also, delete posts, pages, revisions and attachments.

= Featured list =
* Re-install WordPress - this option a reset makes a fresh installation of your database. Therefore, ANY data in your database will be lost
* Re-install WordPress and clear "uploads" folder - this option a reset makes a fresh installation of your database. Therefore, ANY data in your database will be lost. There will also be completely cleared folder "uploads"
* Post cleaning - this option is to remove posts, pages, revisions, attachments or all items
* Delete themes - this option is to remove all of your theme except active theme
* Delete plugins - this option is to remove all of your plugins
* Clear "uploads" folder - this option is to clean the "uploads" folder
* Deep cleaning - this option removes the your plugins and themes, cleared "uploads" folder and then start a re-installation WordPress!

== Installation ==

1. Upload the plugin files to the `/wp-content/plugins/advanced-reset-wp` directory, or install the plugin through the WordPress plugins screen directly.
1. Activate the plugin through the 'Plugins' screen in WordPress
1. Use the Dashboard -> Tools -> Advanced Reset WP

== Screenshots ==

1. Admin page of the plugin

== Changelog ==

= 1.3 =
* WebFactory took over development on 2018/05/26

= 1.2.3 =
* add Russian translate

= 1.2.2 =
* minor code style fix

= 1.2.1 =
* *fixed bug on old PHP versions

= 1.2.0 =
* +new option: Re-install WordPress and clear "uploads" folder
* *fixed bug where after the Re-Install WordPress does not create new user if the operation does not run from the user with the login "admin"
* *fixed minor bugs

= 1.1.0 =
* +new option clear "uploads" folder
* *activate current theme after reinstall WordPress

= 1.0.1 =
* *fix deep cleaning after which was not removed attachments files

= 1.0.0 =
* +first release