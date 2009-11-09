=== Anti Feed-Scraper Message ===
Contributors: Joen
Tags: rss, xml, feed, atom, rss2, scrape, anti, prevention, spam
Requires at least: 2.6
Tested up to: 2.8.5
Stable tag: trunk

== Description ==

Helps prevent your RSS feed from being "scraped" (copied and reposted elsewhere), by adding a customizable message with a link to your original post.

When the plugin is activated, a default message is shown. This message can then be configured in the options page. This is the default message:

`[postname] originally appeared on [sitename] on [postdate].`

[postname], [sitename] and [postdate] are automatically replaced by the plugin.

Also available: [tweetthis], which adds a tiny link to allow readers to tweet a link to your post in the format of `http://www.yoursite.com/?p=<postID>`.

== Installation ==

1. Unpack the plugin, put it in your "plugins" folder (`/wp-content/plugins/`).
2. Activate the plugin from the Plugins section.

== Screenshots ==

1. This shows the default message at the bottom of the post.
2. This shows the options page where you can customize the message.

== Changelog ==

* 0.9.2: Added `[tweetthis]` as an optional thing to add to your feed.
* 0.9.1: Fixed a problem with the date formatting. Now it shows the format picked in your Wordpress backend under "General Settings". 
* 0.9: First release.
