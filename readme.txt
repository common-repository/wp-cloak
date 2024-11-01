=== Plugin Name ===
Contributors: FancyGuppy
Plugin Name: WP Cloak
Author: FacnyGuppy
Author URI: http://fancyguppy.com/
Requires at least: 2.1
Tested up to: 3.1.1
Stable tag: 1
Version: 1
Tags: detect, bot, robot, bots, crawler, spider, seo, google
Donate link: http://fancyguppy.com

== Description ==

This lightweight plugin allows you to detect bots (also known as crawlers or spiders) on your website. This allows you to cloak (hide stuff from or show stuff to search engine bots such as the Google Bot).


To use, simply call the function, `is_bot()`.

For example, you can use:
`if ( is_bot() ) {
    // Content with a high keyword density
} else {
    // Login, ads, Javascript, etc
}`

*** Please note: Please do not use this plugin for unethical purposes such as keyword stuffing ***


== Installation ==

1. Upload `wp-cloak` directory to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Enjoy :)

== Frequently Asked Questions ==

= How will cloaking benefit me? =
Search engines (such as Google) use many factors to determine if your website/blog with appear first on their listings. Some these factors are:
* Keywords - You can show extra keywords to Search Engines with this plugin.
* Speed - Don't load Javascript or CSS if it's a Seach Engine. These will not improve your ranking, it will decrease your ranking because it takes longer for your blog to load.
* Links - Remove external links for Search Engines to maintain your PageRank inside your own blog.

= How do I detect bots? =
Simply use `is_bot()` or `!is_bot()` anywhere in your blog.

== Changelog ==

1.0

* Initial version