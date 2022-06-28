—————---Thank you for your purchase! ————————————————

To get started, open go to our documentation using the link file or visit:
https://sherdle.com/help/documentation/universal/

If you don’t have an internet connection, you can check the offline documentation (exported pdf of the web version).

————————————————— License ————————————————————————————

For more license information, check the License.txt file inside the template's folder.

——————————— Change log & Upgrading ———————————————————

From V1.0.0 to V1.1.0

Warning: Analytics has been removed from the template.
Updates: Check our website.
Upgrading: Complete reconfiguration required, you can not recycle any files except
single assets (images).



From V1.1.0 to V1.1.1

Information: You only have to update if you use Wordpress in Rss.
Updates: Check our website.
Upgrading: Complete reconfiguration required, you can not recycle any files except
single assets (images).



From V1.1.1 to V1.2.0

Updates: Check our website.
Warning: We dropped the functionality to switch between NativeWeb & Webview for RSS descriptions
Updates: Check our website.
Upgrading: Complete reconfiguration required, you can not recycle any files except
single assets (images).




From V1.2.0 to V1.2.1

Updates: fixed bug's only
Upgrading: Replace your current WordpressDetailActivity with the new one



From V1.2.0 to V1.2.2

Updates:
Aug:
- Youtube Playlist Compatibility
- Overall bugfixes
Sep:
- Wordpress thumbnail compatibility and fallback
- Rss refresh button
- Rss adview reliability
Upgrading: You can keep your all you non-layout xml files and the SlidingMenuFragment.java file



From V1.2.2 to V1.2.3

Updates: Bugfixes & Stability improvements
Upgrading: You can keep most of you files:
Replace the RSS packages
Replace the Wordpress packages
Replace the XML layout files.



From V1.2.3 to V2.0.0

Updates:
- Material Design
- Redesigned Application Framework, fragment based
- Faster loading, especially for Wordpress Items
- Twitter supports search (e.g. hashtag) as content
- Easier Setup using configuration file
- Video Documentation
- No connection handling improved
- Endless scrolling loading indication footer
- Fading ActionBar (toolbar)
- Using official NavigationDrawer instead of SlidingMenu library
- Looks better on tablets
- Multi-orientation support
- Improvements regarding notifications
- Stability and Compatibility improvements
- Lollipop bugfixes & features (e.g. not using the in app player due to compatibility issues, ripple and tint).

Deprecated:
- User can not set a default item, it’s now by default the first item in the menu
- Links in RSS/Wordpress do not open in WebView anymore

Upgrading:
Complete reconfiguration required.



From V2.0.0 to V2.1.0

Updates:
- Android Studio documentation and main version
- Background loading of items (you’re free to navigate)
- Background radio playing
- RSS notifications are easier to configure and on by default.
- Notifications have content preview
- Links from detail views will be loaded in web-view again.
- Wordpress & Tumblr reload bug fix
- Menu open by default bug fix
- Losing connection while using app fix

Upgrading:
Complete reconfiguration recommended.



From V2.1.0 to V2.2.0

Updates:
- New Navigation Drawer
- Google Places API
- Headers/highlighted items for Wordpress Youtube
- Maps Navigation
- WebView fullscreen HTML5 Video
- WebView stability & appearance
- Bug fixes & Stability improvements

Upgrading:
A summary of all changed files can be found in ‘File Changelog.txt’



From V2.2.0 to V2.2.1

Updates:
- RTL Arab & Hebrew support for Android 4.2+
- Settings cleaned up, ability to set font size
- Author & Date shown for wordpress
- RSS reliability & media updated
- Higher quality wordpress attachements & images.
- Ability to hide menu (just add 1 item).
- Bug fixes: Youtube sharing, Adview in detail focus, notification body, webview background playing.

Upgrading:
A summary of all changed files can be found in ‘File Changelog.txt’




From V2.2.1 to V2.3.0

Updates:
- Native Facebook support
- Native Instagram support
- In-App purchase to remove ads & unlock sections
- Comments for Youtube, Facebook, Instagram and Wordpress
- Related posts for Wordpress
- Support for RSS podcasts
- Built-in media viewer (for images, video and sound)
- Radio player notification & call  interrupt
- Layout improvements (more icons, more material design)
- Updates for Android 5.1
- Notification Sound
- Bug fixes: Notifications stop when turned off, Menu width, RTL support improved, empty search results toast, Webview related improvements, other minor improvements.

Upgrading:
It’s recommended to start over, you can reuse your Configuration file. Strings.xml has to be reconfigured since we’ve added some strings. Menu Icons, Launcher icons and Drawer Header images can be transferred to your new project.





From V2.3.0 to V2.3.1
Updates:
- Bug fixes
- Play button over Facebook video
- Translation improvements
- Debug info hints

Upgrading:
It’s not necessary to upgrade if you’re not having any problems with the current version. If you do, the main updates are in the Facebook package (and layout files) and the Wordpress package. You can replace these packages and files.





From V2.3.1 to V2.3.2
Updates:
- Bug fixes and compatibility improvements
- Facebook not playing
- Translation improvements
- Download option for videos, images and audio (built-in player)
- Text size setting now works for Facebook & Instagram
- More optional settings on file basis

Upgrading:
It’s not necessary to upgrade if you’re not having any problems with the current version. If you do, consider only upgrading the package’s your having trouble with. Otherwise a complete reinstallation is recommended. Config.xml and images can be kept.





From V2.3.2 to V2.4.0
Updates:
- Android Marshmallow support (including new permission system)
- New dedicated tablet layout
- Pull-to-refresh for WebView
- Adviews (Admob) now better optimized for all devices and located at the bottom.
- More layout and code re-using
- Bugfixes for: Instagram would not load, Theme issues, WebView local file issues

Upgrading:
This is a recommended update to support all new Android Marshmallow devices. You can keep your drawables, strings file and configuration file (config.java) all other files should be updated.





From V2.4.0 to V2.5.0
New features:
- SoundCloud support!
- Disqus comments for Wordpress
- Radio Player now playing info
- Wordpress items load automatically in background, resulting in near-instant loading
- Date and time are relative now
- Menu items are translatable/can use string resource

Under the hood updates and fixes:
- Picasso instead of UIL
- Incompatible videos are opened externally now
- Support for new Instagram API
- More code re-use and optimization
- Added some settings like; Logging can be disabled with a simple toggle, API access way, in app webview behavior and more.
- Fix for WebView bugs on rotation and full screen video

Upgrading:
If you are using WebView, Instagram or would like SoundClound or Disqus, this update is recommended, otherwise this update is optional. You can keep your drawables, most Strings. Configuration file (config.java) can be partially re-used but requires an update.




From V2.5.0 to V2.6.0
New features:
- JetPack API / Wordpress.com support for Wordpress
- AAC Support for Radio Player
- New visualizer + Album Art support for Radio Player
- Live TV / Video Stream support
- Reduced app size to < 5 mb
- Custom intents/app launch option from menu added
- WebView file upload support
- Option to disable ads with Youtube
- Some Android Nougat related improvements
- Bugfixes and stability improvements

Warning! Support for Android 4.0 has been dropped.

Upgrading:
This is an update that you should use if you are currently having trouble using Radio (e.g compatibility) or Wordpress JSON API problems.
You can keep your drawables, API keys, and your configuration file (it may have to be updated to comply with the documentation).




From V2.6.0 to V3.0.1
New features:
- Support for Tabs
- Support for OverView items (a screen with additional menu items or a 'category' screen)
- Configuration is now done in a .JSON file that can be remotely updated, and configured from our UI editor.
- OneSignal support for Push Notifications
- Support for Admob Interstitials (when switching menu items or tabs)
- Collapsing Toolbar
- Pinterest support added
- Radio notification opens player
- Notifications can open in-app url (WebView), provide 'url' as extra.
- Added option to hide Drawer
- Changed target SDK to 25 & updated libraries
- Bugfixes & Stability improvements

Support for RSS based notifications has been dropped. You could use a service like Zapier to send RSS notifications over OneSignal instead.

Upgrading:
This update is recommended for all users. It will require a complete reconfiguration! That mean's you'll have to re-import the project from scratch.
You can keep your drawables, and existing API tokens, Admob ID & About text in Strings.xml.




From V3.0.1 to V3.1.0
New features
- Support for SoundCloud Playlists
- Basic WP REST API support (no images)
- Overview screens show loading
- Option to show drawer on app launch re-added
- Overview screen items have ads now (HolderActivity)
- RTL Support for ViewPager
- Bugfixes (WebView sliders, FB, Instagram) and library updates (VideoPlayer, RadioPlayer, Google Support/Services)

Upgrading:
This updated is only recommended if you are experiencing issues with the older version, or if you'd like to use one of the features above.
You can re-use your configuration overview/json files, API tokens & drawables.




From V3.1.0 to V3.1.1
New features
- Youtube Live
- Option to hide WebView navigation
- Bugfixes (ViewPager RTL, TV, Ads WebView) and library updates

Upgrading:
This updated is only recommended if you are experiencing issues with the older version, or if you'd like to use one of the features above.
You can re-use your configuration overview/json files, API tokens & drawables.





From V3.1.1 to V4.0.0
New features
- WooCommerce Support!
- New RadioPlayer with new visualiser and new layout! Based on ExoPlayer.
- New StreamPlayer with new UI! Based on ExoPlayer.
- Android Oreo Support.
- Wordpress Category chips.
- Wordpress full support for WP REST API with attachments and featured images.
- Wordpress attachment slider (images, files, video, audio) and attachment slider FAB (optional).
- Maps updated with support for GeoJSON
- New highlight / header layout. And option to apply this layout to all rows.
- Updated Wordpress, Instagram, Facebook, Twitter, Pinterest, Youtube, RSS row layout.
- Updated Wordpress & Youtube detailview.
- Recyclerview and fancy emptyview for all list based content providers.
- Fragments as custom intent.
- Zooming for images
- More options to fine-tune Universal in Config.java
- Updated libraries and bugfixes.

Upgrading:
A complete reconfiguration is recommended. You can keep your api tokens, custom drawables and Config.json file.
Content providers; Youtube and Instagram need to be re-setup according to documentation.





From V4.0.0 to V4.1.0
New features
- WooCommerce new layout, order history and login
- WooCommerce speed improvements
- Bugfixes: tumblr, youtube, instagram, tablet rotation
- Android Studio 3.0

Upgrading:
A complete reconfiguration is recommended. You can keep your api tokens, custom drawables and Config.json file.





From V4.1.0 to V4.2.0
New features
- Flickr support! Support for Flickr photosets (albums) and galleries.
- Interstitial is preloaded and loads instantly
- New WebView Engine and offline screen. Geolocation support
- Updated and 'materialised' SoundCloud layout
- Twitter more characters, larger profile images.
- WooCommerce support for external products and variable product stock
- Option to hide Toolbar
- Bugfixes and stability improvements (among others: RTL, Admob & Live TV)

Upgrading:
A complete reconfiguration is recommended. You can keep your api tokens, custom drawables and Config.json file.




From V4.2.0 to V4.3.0
New features
- New Light Toolbar Theme
- New Bottom NavigationView
- New Dynamic Toolbar Elevation
- New Material Design for Drawer
- New Row Layouts for Wordpress, Youtube, Rss
- User changeable row layouts (Optional)
- New Wordpress Audio Content provider
- Pull Refresh for Wordpress, Youtube, RSS
- New Home Screen design for WooCommerce
- Product Filters for WooCommerce
- New Instagram Graph API
- New Facebook Graph API
- Radio Metadata immediately shown upon resuming
- Open Source Licenses screen
- Updated to latest Support and Build libraries
- WebView (fullscreen), WooCommerce (stock and product visibility), Flickr (no connection), Instagram (paging) bugfixes

Upgrading:
A complete reinstallation is required. You can re-use most api tokens, custom drawables and Config.json file.
Facebook and Instagram require new API tokens and configuration



From V4.3.0 to V4.3.1
New features
- WooCommerce cart is cleared only after completed purchase
- Bugfixes and performance Improvements
- Android 9 compatibility

Upgrading:
Only need to upgrade if you experience bugs. A complete reinstallation is then required.
You can use api tokens, drawables and json files.



From V4.3.1 to V4.3.2.
- Android Studio 4.3 improvements, Gradle upgrades
- Latest ExoPlayer
- Twitter retweets fix

Upgrading:
Only need to upgrade if you experience bugs. A complete reinstallation is then required.
You can use api tokens, drawables and json files.



From V4.3.2 to V4.3.3
- SoundCloud Bugfixes
- Update to Facebook API v3.3
- WP REST API fix for posts without author

Upgrading:
Only need to upgrade if you experience bugs. A complete reinstallation is then required.
You can use api tokens, drawables and json files.



From V4.3.3 to V4.4
- Wordpress Images and Videos providers
- Vimeo support
- New layout for Twitter, Instagram & Facebook
- Twitter support for multiple images and videos
- Facebook & Instagram support for multiple images
- Improved Wordpress layout and improvements to related posts
- Option in settings to manage notifications
- Migrated to WooCommerce V3 API, support for sorting products
- Music (Radio, Soundcloud, WP audio) is automatically paused when interrupted
- Fixed Pinterest bug
- Migrated to AndroidX, updated billing library and target SDKs

Upgrading:
A complete reinstallation is required.
You can re-use your api tokens, your drawables and your Config.json file.



From V4.4.0 to V4.4.1
- Bugfixes and performance improvements

Upgrading:
A complete reinstallation is required.
You can re-use your api tokens, your drawables and your Config.json file.



From V4.4.1 to V4.4.2
- Firebase Analytics, Crashlytics support 
- Data collection consent dialog
- Updated libraries
- Option to define Webview open outside urls
- Bugfixes

Upgrading:
A complete reinstallation is required.
You can re-use your api tokens, your drawables and your Config.json file.



From V4.4.2 to V4.4.3
- Button toolbar in 'colourful theme' layout fix
- External url opening fix
- All streams are properly closed

Upgrading:
A complete reinstallation is required.
You can re-use your api tokens, your drawables and your Config.json file.



From V4.4.3 to V4.4.4
- Radio Autoplay
- Radio Logo
- Android Studio 4.0 support

Upgrading:
A complete reinstallation is required.
You can re-use your api tokens, your drawables and your Config.json file.



From V4.4.4 to V4.4.5
- Facebook, Instagram and Youtube tokens/api keys moved to config.json
- Radio logo now also when resuming from notification

Upgrading:
A complete reinstallation is required.
You can NOT re-use your Config.json file, please create a new config.json file



From V4.4.5 to V4.4.6
- Wordpress Pages support
- Wordpress notifications open natively
- Toolbar will hide in WebView
- Bugfixes for Videos/Youtube/SoundCloud

Upgrading:
A complete reinstallation is required.
You can re-use your api tokens, your drawables and your Config.json file.



From V4.4.6 to V4.5.0
- Google Play billing V3
- RTL improvements
- WooCommerce in stock and category filter options
- Improved WooCommerce home layout
- Improved WooCommerce cart and product screens
- New WooCommerce Product variant selection
- New WooCommerce categories screen
- WooCommerce, SoundCloud, Notification bugfixes and performance improvements

Upgrading:
A complete reinstallation is required.
You can re-use your api tokens, your drawables and your Config.json file.


From V4.5.0 to V4.5.1
- Android 30 and Gradle 7

From V4.5.1 to V4.5.2
- SoundCloud oAuth 2.0 fix
- Youtube player on newer Android
- WooCommerce layout fixes

Upgrading:
A complete reinstallation is required.
You can re-use your api tokens, your drawables and your Config.json file.
