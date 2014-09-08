Wordpress gallery-oembed
========================

Wordpress video, music, pictures, polls, social and other media gallery. Youtube, Vimeo, Coub, SoundCloud, Twitter, TED and more.

Description
===========

Gallery oEmbed is a plugin for creating galleries with oEmbed supported media quickly with management by short code.

TODO
====

1. Update info, screenshots and submit to wordpress plugins repos
1. Check size settings
1. Use fancybox or create settings for using other UI
1. Make sources English-based, reverse the Portugal language files, add Russian translation
1. Save thumnails as the post thumbnail, add a setting whether to hotlink or store thumbnails in media library
1. Add switchable editor field to add arbitrary text

Supported media
===============

Discovery is disabled for users lacking the unfiltered_html capability.
Only providers in this array will be used for those users.

To embed media from Coub and other oEmbed supporting services one has to add posts with unfiltered_html capability to use oEmbed autodiscovery.

One can declare oEmbed provider using (wp_oembed_add_provider)[https://codex.wordpress.org/Function_Reference/wp_oembed_add_provider] to add another provider to this whitelist.

Supported providers:

| ------------ | -------------------- | ----- | --------- |
|   Provider   |        Flavor        |  SSL  |   Since   |
| ------------ | -------------------- | ----- | --------- |
| Blip         | blip.tv              |       | 2.9.0     |
| Dailymotion  | dailymotion.com      |  Yes  | 2.9.0     |
| Flickr       | flickr.com           |  Yes  | 2.9.0     |
| Hulu         | hulu.com             |  Yes  | 2.9.0     |
| Photobucket  | photobucket.com      |       | 2.9.0     |
| Revision3    | revision3.com        |       | 2.9.0     |
| Scribd       | scribd.com           |  Yes  | 2.9.0     |
| Vimeo        | vimeo.com            |  Yes  | 2.9.0     |
| WordPress.tv | wordpress.tv         |  Yes  | 2.9.0     |
| YouTube      | youtube.com/watch    |  Yes  | 2.9.0     |
| ------------ | -------------------- | ----- | --------- |
| Funny or Die | funnyordie.com       |  Yes  | 3.0.0     |
| Polldaddy    | polldaddy.com        |  Yes  | 3.0.0     |
| SmugMug      | smugmug.com          |  Yes  | 3.0.0     |
| YouTube      | youtu.be             |  Yes  | 3.0.0     |
| ------------ | -------------------- | ----- | --------- |
| Twitter      | twitter.com          |  Yes  | 3.4.0     |
| ------------ | -------------------- | ----- | --------- |
| Instagram    | instagram.com        |       | 3.5.0     |
| Instagram    | instagr.am           |       | 3.5.0     |
| Slideshare   | slideshare.net       |  Yes  | 3.5.0     |
| SoundCloud   | soundcloud.com       |  Yes  | 3.5.0     |
| ------------ | -------------------- | ----- | --------- |
| Dailymotion  | dai.ly               |       | 3.6.0     |
| Flickr       | flic.kr              |  Yes  | 3.6.0     |
| Rdio         | rdio.com             |  Yes  | 3.6.0     |
| Rdio         | rd.io                |  Yes  | 3.6.0     |
| Spotify      | spotify.com          |  Yes  | 3.6.0     |
| ------------ | -------------------- | ----- | --------- |
| Imgur        | imgur.com            |  Yes  | 3.9.0     |
| Meetup.com   | meetup.com           |  Yes  | 3.9.0     |
| Meetup.com   | meetu.ps             |  Yes  | 3.9.0     |
| ------------ | -------------------- | ----- | --------- |
| Animoto      | animoto.com          |  Yes  | 4.0.0     |
| Animoto      | video214.com         |  Yes  | 4.0.0     |
| CollegeHumor | collegehumor.com     |  Yes  | 4.0.0     |
| Issuu        | issuu.com            |  Yes  | 4.0.0     |
| Mixcloud     | mixcloud.com         |  Yes  | 4.0.0     |
| Polldaddy    | poll.fm              |  Yes  | 4.0.0     |
| TED          | ted.com              |  Yes  | 4.0.0     |
| YouTube      | youtube.com/playlist |  Yes  | 4.0.0     |
| ------------ | -------------------- | ----- | --------- |

No longer supported providers:

| ------------ | -------------------- | ----- | --------- | --------- |
|   Provider   |        Flavor        |  SSL  |   Since   |  Removed  |
| ------------ | -------------------- | ----- | --------- | --------- |
| Qik          | qik.com              |  Yes  | 2.9.0     | 3.9.0     |
| ------------ | -------------------- | ----- | --------- | --------- |
| Viddler      | viddler.com          |  Yes  | 2.9.0     | 4.0.0     |
| ------------ | -------------------- | ----- | --------- | --------- |

Based on youtube-simple-gallery
===============================

  * [https://github.com/wp-plugins/youtube-simple-gallery]
  * [https://wordpress.org/plugins/youtube-simplegallery/]