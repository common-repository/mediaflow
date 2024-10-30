=== Mediaflow ===
Tags: mediaflow, upload, images, media
Requires at least: 5.8
Tested up to: 6.6.2
Stable tag: 2.0.28
License: GPLv3
License URI: https://www.gnu.org/licenses/gpl-3.0.html

== Description ==

A Mediaflow integration plugin for WordPress.

== Installation ==

1. Search for Mediaflow in the plugins directory.
2. Install and activate the plugin.

or

1. Download and unzip the plugin and upload the `mediaflow` directory to your `/plugins/` directory.
2. Activate the plugin through the 'Plugins' menu in WordPress.

== Changelog ==

= 2.0.28 =

- Fixed an issue where the access token was not retrieved when the response was a WP_Error

= 2.0.27 =

- Tested against WordPress 6.6.2

= 2.0.26 =

- Fixed file usage registration issue

= 2.0.24 =

- Added WordPress 6.6.1 support

= 2.0.23 =

- Added WordPress 6.5.4 support

= 2.0.22 =

- Added WordPress 6.5.3 support

= 2.0.20 =

- Added WordPress 6.5.2 support

= 2.0.19 =

- Updated nullable return type

= 2.0.18 =

- Added WordPress 6.5 support

= 2.0.17 =

- Updated contributor list

= 2.0.16 =

- Added `image/tiff` support

= 2.0.14 =

- Fixed ping usage issue

= 2.0.13 =

- Removed access token when settings change

= 2.0.11 =

- Fetch access tokens using PHP instead of JavaScript

= 2.0.10 =

- Added environment variable support for `MEDIAFLOW_CLIENT_ID`, `MEDIAFLOW_CLIENT_SECRET`, `MEDIAFLOW_FORCE_ALT_TEXT` and `MEDIAFLOW_REFRESH_TOKEN`

= 2.0 =

- Added video block integration
- Support latest WordPress releases
