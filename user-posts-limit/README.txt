=== User Posts Limit ===
Contributors: condless
Tags: limit, post, user, role
Requires at least: 5.2
Tested up to: 6.8
Requires PHP: 7.0
Stable tag: 1.2.3
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Limit the number of posts user can create. Any post type.

== Description ==

Limit the number of posts user can create. Any post type.

[Documentation](https://en.condless.com/user-posts-limit/) | [Contact](https://en.condless.com/contact/)

= How To Use =
1. Plugin Settings: Select role, post type, limit, and cycle.

= How It Works =
* On post creation the number of posts from this post type belong to this user for the specified cycle will be counted and if applicable the post creation will be prevented.

= Features =
* **Post Creation Limits**: Limit the number of posts each user role can create daily/weekly/monthly/yearly/ever.
* **Hide Content**: In order to make some content hidden when posts limit exceeded wrap it with the shortcodes (replace &#34;post&#34; with the post type of the relevant rules): [upl_hide type=&#34;post&#34;][/upl_hide]
* **Display Limits**: Display the limits to the user anywhere with the [upl_limits] shortcode.
* **Users Stats**: Track how many posts each user used from his quota.
* **Multisite**: Network-wide rules can be applied via the Network Admin Dashboard (doesn't support the Hide Content, Display Limits and Users Stats features).
* **Integrations**: WooCommerce, Paid Memberships Pro, MyListing theme, Restrict Content Pro, PeepSo, WordPress REST API.
* **Limits per User**: Set limits per user (see instructions in docs).

== Installation ==

= Minimum Requirements =
WordPress 5.2 or greater
PHP 7.0 or greater

= Automatic installation =
1. Go to your Dashboard => Plugins => Add new
1. In the search form write: Condless
1. When the search return the result, click on the Install Now button

= Manual Installation =
1. Download the plugin from this page clicking on the Download button
1. Go to your Dashboard => Plugins => Add new
1. Now select Upload Plugin button
1. Click on Select file button and select the file you just download
1. Click on Install Now button and the Activate Plugin

== Screenshots ==
1. User Posts Limit Plugin Settings
1. Post creation limit notification
1. Role option
1. Post type option
1. Users Screen stats

== Frequently Asked Questions ==

= Why the limits do not work as expected? =

* The counts include posts in trash/draft/pending status
* Limits will not be applied on users with the Plugin Management Capability or (in multisite) the create_users capability
* The post creation date and not the post published date is taken into account when using the cycle option

= How to use the [upl_hide] shortcode with Elementor? =

Insert shortcode widget with [upl_hide type=&#34;post&#34;][/upl_start] before your content and another shortcode widget with [/upl_hide] after your content.

== Changelog ==

= 1.2.3 - May 8, 2025 =
* Enhancement - WordPress version compatibility

= 1.2.2 - November 12, 2024 =
* Dev - WP compatibility

= 1.2.1 - May 22, 2024 =
* Dev - WP compatibility

= 1.2 - March 1, 2024 =
* Dev - WP compatibility

= 1.1.9 - October 12, 2023 =
* Dev - WP compatibility

= 1.1.8 - June 30, 2023 =
* Dev - WP compatibility

= 1.1.7 - March 18, 2023 =
* Dev - WP compatibility

= 1.1.6 - December 22, 2022 =
* Dev - WP compatibility

= 1.1.5 - August 19, 2022 =
* Dev - WP compatibility

= 1.1.4 - June 1, 2022 =
* Dev - User's stats enabled by default

= 1.1.3 - April 10, 2022 =
* Dev - WP compatibility

= 1.1.2 - February 27, 2022 =
* Dev - Query speed improvement

= 1.1.1 - January 5, 2022 =
* Dev - Current post type filter and Messages filter

= 1.1 - July 28, 2021 =
* Dev - WP compatibility

= 1.0.9 - June 30, 2021 =
* Dev - WP compatibility

= 1.0.8 - April 7, 2021 =
* Dev - Date filter

= 1.0.7 - February 13, 2021 =
* Dev - Cycle limit by GMT time

= 1.0.6 - October 12, 2020 =
* Feature - Rules Filters

= 1.0.5 - September 22, 2020 =
* Feature - WPMU support

= 1.0.4 - September 16, 2020 =
* Feature - Rules priority

= 1.0.3 - September 08, 2020 =
* Feature - Hide content shortcode

= 1.0.2 - August 25, 2020 =
* Feature - Users stats

= 1.0.1 - April 20, 2020 =
* Feature - Timing rule

= 1.0 - April 10, 2020 =
* Initial release
