=== Post Reference URL ===
Contributors: Kasun Sameera
Tags: reference, url, citation, source, attribution
Requires at least: 5.2
Tested up to: 6.5
Stable tag: 1.0.0
License: GPL-2.0+
License URI: https://www.gnu.org/licenses/gpl-2.0.html

Add reference URLs to posts and pages with a simple meta box. Perfect for citations, sources, or external attributions.

== Description ==

The **Post Reference URL** plugin allows you to:

* Add a reference URL to any post or page via a meta box
* Automatically displays the reference link below post content
* Simple, lightweight solution with no unnecessary features
* Follows WordPress coding standards and security best practices

== Installation ==

1. Upload the `post-reference-url` folder to `/wp-content/plugins/`
2. Activate the plugin through the 'Plugins' screen in WordPress
3. Edit any post/page to add a reference URL in the new meta box

== Frequently Asked Questions ==

= Where does the reference URL appear? =
It appears automatically below the post/page content with the label "Reference Website".

= Can I change the display style? =
Yes, edit the `display_reference_url()` method in the plugin file to modify the HTML/CSS.

= Does this work with custom post types? =
Not by default, but you can modify the `add_meta_boxes` action to include other post types.

= How do I make the link open in the same tab? =
Remove `target="_blank"` from the anchor tag in the `display_reference_url()` method.

== Screenshots ==

1. The reference URL meta box in the post editor
2. How the reference link appears below post content

== Changelog ==

= 1.0.0 =
* Initial release with basic functionality:
  - Meta box for reference URLs
  - Automatic display below content
  - Secure saving with nonce verification

== Upgrade Notice ==

1.0.0 - First stable release. No upgrades needed.
