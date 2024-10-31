=== Republish Old Posts ===
Contributors: Marios Alexandrou
Donate link: https://infolific.com/technology/software-worth-using/republish-old-posts-for-wordpress/#pro-version
Tags: republish, republishing, old post promoter, post promoter
Requires at least: 5.0
Tested up to: 6.7
License: GPLv2 or later

Republish old posts automatically by resetting the date to the current date. Promote old posts to users that haven't seen them.

== Description ==

** WARNING: DON'T USE THIS PLUGIN IF YOUR PERMALINKS INCLUDE DATES **

The Republish Old Posts plugin helps revive old posts by resetting the publish date to the current date. This will push old posts to your front page, the top of archive pages, and back into RSS feeds. Ideal for sites with a large repository of evergreen content. 

Why would you want to do this? Here are a few reasons:

1. New visitors to your site haven't seen your old content. This will help them discover it.
2. Old content won't show up in date-based searches on search engines, but resetting the date can make them look fresh again.
3. People like to share and link to new content and they determine that by looking at the publication date.

A [pro version](https://infolific.com/technology/software-worth-using/republish-old-posts-for-wordpress/#pro-version) (a lifetime license is less than $15) with many additional options (see screenshots) for controlling when and what posts are republished.

== Installation ==

1. Upload Republish Old Posts to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Adjust the options as needed to suit your republishing schedule

== Screenshots ==

1. Set the time that should elapse before posts are republished. Options in red are available only in the [pro version](https://infolific.com/technology/software-worth-using/republish-old-posts-for-wordpress/#pro-version).
2. Add a randomness interval to when posts are republished. Options in red are available only in the [pro version](https://infolific.com/technology/software-worth-using/republish-old-posts-for-wordpress/#pro-version).
3. Determine how old posts should be before they're considered for republishing. Options in red are available only in the [pro version](https://infolific.com/technology/software-worth-using/republish-old-posts-for-wordpress/#pro-version).
4. Ability to specify a post-level, custom field to exclude posts from ever being republished. This option available only in the [pro version](https://infolific.com/technology/software-worth-using/republish-old-posts-for-wordpress/#pro-version).

== Frequently Asked Questions ==

= Are posts duplicated? =

No. The date on posts is updated to the current date making a post appear new. URLs don't change and comments continue to display with the post.

= Doesn't changing the timestamp affect permalinks that include dates?  =

Yes permalinks with dates would be affected. This plugin shouldn't be used if your permalinks include dates since those dates will change when a post is republished.

= I like this plugin, do you have others? =

= Does this work with WPMU? =

Yes it does. 

= Two posts are being republished at the same time. How do I fix this? =

Odd behavior has been noticed when both the All in One SEO plugin and the Republish Old Posts plugin are active. If you're not using the AIO SEO plugin, but still experiencing issues, please leave a message in the support forum. Republish Old Posts works fine with the Yoast SEO plugin and no other SEO plugin conflicts have been reported.

= Why do post slugs change upon republishing? =

This plugin doesn't alter post slugs. It changes the post date and, depending on the settings, changes the post's status. If you have other plugins that take actions when a post's date or status change, you may see some unexpected results. There isn't much I can do about the behavior of other plugins.

== Changelog ==

= 1.27 =
* All Versions: Added nonce check for additional security against CSRF. Thanks to Skalucy of Patchtack.com. Synching version number with Pro version.

= 1.21 =
* All Versions: Updated info regarding the pro version.

= 1.20 =
* All Versions: Fixed problem with displaying which categories have been omitted.

= 1.19 =
* All Versions: Added code to delete last update value in database when plugin is deactivated. May fix issues related to unexpected re-publishing.

= 1.18 =
* Pro Version: Added option to update a post's GUID when it is republished.

= 1.17 =
* All Versions: Added cache clearing code for the WP Fastest Cache plugin.
* Free Version: Synchronizing plugin version number with pro version.

= 1.15 =
* All Versions: Security issue (cross-site scripting) fix applied.

= 1.14 =
* Pro Version: Added option to trigger a publish event within WordPress when a post is republished. If you want to "tell" other plugins that a post has been republished, check this option.

= 1.13 =
* Pro Version: Added 28 days as an option for the minimum post age.

= 1.12 =
* Pro Version: Added 28 days as an option for the minimum interval.

= 1.11 =
* All Versions: Fixed issue where posts wouldn't be republished when plugin first installed.

= 1.10 =
* All Versions: Fixed time zone issue that sometimes resulted in republished posts having a future time.
* Pro version: Added random interval of 0 for better control over publishing time.
* Pro version: Added age values of 6 and 12 hours to allow for new posts to be republished.

= 1.9 =
* Pro version: Changed behavior of phrase matching filter. Now examines post title and not the post content.

= 1.8 =
* Pro version: Can now specify posts to republish by a word that they contain e.g. if set to "word" only posts containing word, keyword, words, or other similar matches will be considered for republishing.

= 1.7 =
* Pro version: Added options for republishing posts that are just 1 day, 1 week, or 2 weeks old.

= 1.6 =
* Pro version: Can now choose to republish a random old post rather than the oldest post.

= 1.5 =
* Pro version: Added 5 minute minimum interval option.
* Pro version: Added 5, 15, and 30 minute randomness interval options.

= 1.4 =
* Free version: Bug fix to SQL.

= 1.3 =
* All versions: Code cleanup. Conforming with WordPress coding standards.
* All versions: Tweaks to admin interface.
* Pro version: Added an option to force a post to be republished when it is the oldest post of those that otherwise match the criteria you specified.

= 1.2 =
* All versions: Forcing SVN refresh as last commit doesn't seem to have worked.

= 1.1 =
* All versions: Tweaks to documentation including the readme.txt.
* All versions: Revised admin interface to provide more instruction and supporting information.
* Pro version: Added ability to filter out any posts of your choosing so that they are never republished. This provides more fine-grained control than just selecting a category.
* Pro version: Additional minimum intervals added: 15 minutes, 30 minutes, 1 hour, 2 days, 3 days, and 7 days.
* Pro version: Additional randomness intervals added: 12 hours and 24 hours.
* Pro version: Additional post age options added: 120 days, 240 days, 365 days, 730 days.

= 1.0 =
* Initial release of fork of now defunct and unavailable Old Post Promoter plugin.
* Removed link injection from original plugin i.e. this plugin will not insert any links.
* Removed Twitter functionality from original plugin. This plugin does one and only one thing: republish old posts.
* A number of bugs fixed so running with "debug messages on" shouldn't result in any messages.
