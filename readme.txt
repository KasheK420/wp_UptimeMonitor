=== Uptime Monitor ===
Contributors: lukasmajoros
Donate link: https://lukasmajoros.com/donate
Tags: uptime, monitoring, ping, status, dashboard, server monitoring, website monitoring
Requires at least: 5.0
Tested up to: 6.4
Stable tag: 1.1.0
Requires PHP: 7.2
License: GPL-2.0+
License URI: https://www.gnu.org/licenses/gpl-2.0.html

Monitor your servers, websites, and services with a visual status dashboard. Get notifications when devices go down.

== Description ==

Uptime Monitor is a powerful WordPress plugin that allows you to monitor the status of your servers, websites, and services right from your WordPress dashboard.

With Uptime Monitor, you can:

* **Track status** of servers, websites, routers, and other devices
* **Group devices** for easier management
* **Display uptime statistics** with beautiful visual indicators
* **Get notified** when services go down
* **Show status dashboards** anywhere on your site with shortcodes or widgets

= Key Features =

* **Real-time Status Monitoring:** Automatically pings your devices and services at configurable intervals
* **Visual Status Display:** Clear visual indicators show up/down status with customizable themes
* **Device Grouping:** Organize your devices into logical groups for easier management
* **Flexible Display Options:** Add status displays anywhere with shortcodes or widgets
* **Detailed History:** Track 24-hour uptime history with visual timeline
* **Response Time Tracking:** Monitor response times for performance insights
* **Email Notifications:** Get alerted when a device goes down
* **Mobile-friendly:** Responsive design works on all devices

= Available Themes =

Choose from multiple display themes to match your site's design:

* **Modern**: A card-based layout with visual indicators and detailed device information
* **Compact**: A space-efficient list view, ideal for sidebars or when monitoring many devices
* **Classic**: The original uptime monitor style with simple status indicators

= Usage =

**Shortcodes**

Use these shortcodes to display your uptime monitor on any page or post:

`[uptime_monitor]` - Display all devices
`[uptime_monitor group="Group Name"]` - Display devices from a specific group
`[uptime_monitor device_ids="1,2,3"]` - Display specific devices by ID
`[uptime_monitor theme="modern"]` - Set the display theme
`[uptime_monitor title="Custom Title"]` - Set a custom title

Example:
`[uptime_monitor group="Servers" theme="modern" title="Server Status"]`

**Widget**

The Uptime Monitor Widget can be added to any widget area in your theme.

= Requirements =

* WordPress 5.0 or higher
* PHP 7.2 or higher
* MySQL 5.6 or higher
* Ability to create scheduled tasks (for the uptime checking functionality)

= Credits =

Developed by [Lukáš Majoros](https://lukasmajoros.com/).

== Installation ==

= From WordPress Plugin Repository =

1. Log in to your WordPress dashboard
2. Navigate to **Plugins** > **Add New**
3. Search for "Uptime Monitor"
4. Click **Install Now** and then **Activate**

= Manual Installation =

1. Download the [latest release](https://github.com/lukasmajoros/uptime-monitor/releases/latest)
2. Log in to your WordPress dashboard
3. Navigate to **Plugins** > **Add New**
4. Click **Upload Plugin**
5. Choose the downloaded zip file and click **Install Now**
6. After installation, click **Activate Plugin**

= Post-Installation =

After installing and activating the plugin:

1. Navigate to **Uptime Monitor** in your WordPress admin menu
2. Add the devices you want to monitor
3. Configure the monitoring settings as needed
4. Use the shortcode `[uptime_monitor]` on any page or post to display the status panel
5. Alternatively, add the Uptime Monitor widget to any widget area

== Frequently Asked Questions ==

= How does the plugin check if a device is online? =

The plugin uses the ping functionality to check if devices are online. For websites, it can also use an HTTP request to verify if the website is responsive.

= How often does the plugin check device status? =

By default, the plugin checks device status hourly. You can adjust this in the settings to check twice hourly or daily.

= Can I monitor external websites or just my own servers? =

You can monitor any device or website that can be reached from your WordPress server, including external websites, routers, servers, or any other device with an IP address.

= Will this plugin slow down my website? =

No. The status checking runs in the background using WordPress cron jobs and doesn't affect your website's performance. The status display is lightweight and optimized for performance.

= Does this plugin work with caching plugins? =

Yes, the plugin is compatible with most caching plugins. However, for real-time status updates, you might need to adjust your caching settings.

= Can I receive notifications when a device goes down? =

Yes, the plugin includes email notification functionality that can alert you when a device status changes.

= Can I monitor services on specific ports? =

Not in the current version, but this feature is planned for a future update.

== Screenshots ==

1. Modern theme display showing device status
2. Admin dashboard with device overview
3. Device management interface
4. Group management interface
5. Widget configuration

== Changelog ==

= 1.1.0 =
* Added device groups functionality
* Added multiple display themes (Modern, Compact, Classic)
* Improved widget with device selection options
* Added response time tracking
* Improved admin interface with dashboard

= 1.0.0 =
* Initial release

== Upgrade Notice ==

= 1.1.0 =
Major update with new features including device groups, multiple themes, and response time tracking.

== Copyright ==

Uptime Monitor, Copyright 2025 Lukáš Majoros

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 2 of the License, or
any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the
GNU General Public License for more details.