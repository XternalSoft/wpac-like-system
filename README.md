# WPAC Like & Reaction System
Simple Like &amp; Dislike Plugin for WordPress. :v:

This plugin was created during basic course of <a href="https://wpacademy.pk/course/wordpress-plugin-development-for-beginners-in-urdu-hindi/" target="_blank">Plugin Development in Urdu</a>. Later we decided to distribute this code so students can use it and even try to improve it for educational purpose.
Not Only Like System, this plugin now has a Reaction System as well. Add beautiful reactions to your blog posts or pages.

## Installation

1. Click on the `Download ZIP` button at the right to download the plugin.
2. Upload the entire `wpac-like-system` folder to the `/wp-content/plugins/` directory.
3. Activate the plugin through the `Plugins` menu in WordPress.

## Settings
You can change button labels and other settings by visiting `WPAC Settings` Tab

<img src="https://user-images.githubusercontent.com/38207694/46508463-16800a00-c857-11e8-90c0-e2d844731604.png" alt="WPAC Settings Screen">

## Shortcodes
`[WPAC_LIKE_SYSTEM]` Display Like & Dislike buttons in post or page. 

`[WPAC_LIKE_COUNT]` Return Like count for current post being viewed.

`[WPAC_DISLIKE_COUNT]` Return Dislike count for current post being viewed.

`[WPAC_LIKE_COUNT id="123"]` Return Like count for given post ID.

`[WPAC_DISLIKE_COUNT id="123"]` Return Disike count for given post ID.

`[WPAC_LIKE_COUNT string="Liked % times"]` Return Like count wrapped in a string, use `%` where you want to display count value.

`[WPAC_DISLIKE_COUNT string="Disliked % times"]` Return Disike count wrapped in a string, use `%` where you want to display count value.


## Changelog

1. 2.0.0 - Added Reaction System, New Shortcode and Fixed Bugs.
2. 1.0.0 - Started the project