=== Customize Posts CSS ===
Contributors:      xwp, westonruter
Tags:              customizer, customize
Requires at least: 4.9
Tested up to:      4.9
Stable tag:        0.1.0
License:           GPLv2 or later
License URI:       http://www.gnu.org/licenses/gpl-2.0.html
Requires PHP:      5.4

Add and edit CSS that is displayed on pages which show a given post in the main query, whether singular or an archive.

== Description ==

Since WordPress 4.7 core has provided an Additional CSS section in the Customizer for users to add and preview custom CSS for their site (see [#35395](https://core.trac.wordpress.org/ticket/35395)).

This plugin brings the same functionality to be able to provide custom CSS for individual posts and pages on your site. To do this, it has a few dependencies:

* It relies on CodeMirror being in core as of 4.9-alpha. See [#12423](https://core.trac.wordpress.org/ticket/12423).
* It uses the `WP_Customize_Code_Editor_Control` proposed for WordPress 4.9. See [#41897](https://core.trac.wordpress.org/ticket/41897).
* It requires the [Customize Posts](https://wordpress.org/plugins/customize-posts/) plugin for adding the ability to manage and preview postmeta in the Customizer. The Custom CSS control is added to the post/page Customizer sections which this plugin adds.

See also [#38707](https://core.trac.wordpress.org/ticket/38707) which proposes extending the Custom CSS editor in core with being able to edit per page CSS.

== Changelog ==

= 0.1.0 =

Initial release.
