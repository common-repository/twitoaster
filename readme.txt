=== Twitter Comments - Twitoaster ===
Contributors: Twitoaster
Donate link: http://twitoaster.com/about/
Tags: twitter, comment, comments, post, posts, plugin, widget, wpmu, wordpress
Requires at least: 2.2
Tested up to: 3.0
Stable tag: 1.3.7

Twitter Comments system. Automatically retrieve Twitter Replies and/or Twitter Retweets to your Blog's Posts using WP built-in comment system.

== Description ==
DEPRECATION NOTICE: Twitoaster and its API will be shut down this Sunday (March 20th). That means this WordPress Plugin will cease to function (like any other service relying on Twitoaster API). [Read the full Announcement here](http://blog.twitoaster.com/twitoaster-shutting-down "Twitoaster shutting down")

Twitter Comments system. Give to you readers the possibility to send comments via Twitter! Automatically retrieve Twitter Replies and/or Twitter Retweets to your Blog's Posts. These Twitter mentions are handled like Posts Comments, using WP built-in comment system.

Here is how Twitter Comments work:

1. You Post an article on your blog
2. You update your Twitter status (or let the plugin do it for you)
3. You automatically get all related Twitter Replies and/or Twitter Retweets as comments to your Post

The plugin also brings two widgets:

1. Analytics charts showing how many Twitter Replies and Twitter Retweets you are receiving
2. Listings of your 20 most recent Twitter Conversations

== Installation ==
1. Unzip then upload the `twitoaster` folder to your `/wp-content/plugins/` directory
2. Activate the plugin through the `Plugins` menu in WordPress
3. Enter the [Twitoaster API Key](http://twitoaster.com/api/authentication/ "Twitoaster API Authentication") linked to your Twitter account
4. Go to the `Settings` -> `Twitoaster` to manage options (Twitter Replies, Twitter Status updates, Twitter Charts...)

== Frequently Asked Questions ==
= How does it work? =
The plugin uses the [Twitoaster API](http://twitoaster.com/api/ "Twitoaster API - Twitter conversations and statistics") to search for posts URLs in your Twitter updates (url shorteners are supported). Each Twitter update found sees its replies and/or retweets added as comments to the matching post. The widgets (Twitter charts and Twitter conversations) also use the [Twitoaster API](http://twitoaster.com/api/ "Twitoaster API - Twitter conversations and statistics").

= What is Twitoaster? =
[Twitoaster](http://twitoaster.com/ "Twitoaster - Twitter conversations threading and statistics") is a Twitter service. It threads and archives your Twitter conversations, bringing you all the background, context and statistics you need. In other words, it's all about improving and optimizing the way you communicate with your followers on Twitter.

= What is the Twitoaster API? =
The Twitoaster WP plugin uses the [Twitoaster API](http://twitoaster.com/api/ "Twitoaster API - Twitter conversations and statistics") to retrieve your Twitter extended information.

== Screenshots ==
1. Main plugin configuration page (Twitter comments and Twitter updates)
2. Individual "Tweet Post" option (update your Twitter status when you post)
3. Widgets configuration page (Twitter charts and Twitter conversations)

== Changelog ==

= 1.3.6 =
* WordPress Beta 3 support

= 1.3.5 =
* New: Twitter status update for scheduled posts

= 1.3.4 =
* New: bit.ly support for Tweet Post feature (auto update Twitter status update when you post)

= 1.3.3 =
* Fix: Duplicate Twitter comments could appear on some installations

= 1.3.2 =
* New: Retrieving Twitter Replies and Twitter Retweets faster for new posts

= 1.3.1 =
* Fix: Twitter avatars for WP > 2.9

= 1.3.0 =
* New: ReTweet support (with an option to display Twitter Replies, Twitter Retweets, or both Twitter Replies and Retweets)

= 1.2.5 =
* New: Twitter Comments updated (avatar, screen_name...) if changed
* Fix: Rare Twitter duplicate comments bug fixed

= 1.2.4 =
* Fix: Twitter Comments algorithm rewritten (better locking mechanism)

= 1.2.3 =
* New: Better looking Twitter avatars (for themes using avatar sizes > 48px)
* Fix: Snoopy class redirection bug (for old WordPress versions like 2.2)

= 1.2.2 =
* Fix: Timeout error handling (if Twitter is down)

= 1.2.1 =
* Fix: Adding Twitter Comments locking mechanism
* Fix: Adding a workaround if PHP doesn't support mb_strings

= 1.2.0 =
* New: Optimizing the way Twitter Comments are retrieved
* New: Twitter Status Update entirely rewritten (Tweet format, individual Post options...)

= 1.1.3 =
* Fix: Forcing Snoopy if PHP is in safe mode

= 1.1.2 =
* Fix: An image file was missing (twitter.png) in the package

= 1.1.1 =
* New: Twitter URL Shortener changed to "toast.tw" (for Twitter status updates)
* New: Twitter Comments follow your WP "notify email" options (if you activated the option, you'll receive an email when someone post a comment via Twitter)
* New: Twitter comments follow your WP "close comments" options (Comments received via Twitter after your "close comment" limit won't be added)

= 1.1.0 =
* New: Option to update your Twitter status when you post
* Fix: No more warning message on new post edition

= 1.0.0 =
* First beta version (Twitter Replies only)
