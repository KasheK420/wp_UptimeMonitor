# Installation Guide

There are several ways to install the Uptime Monitor plugin on your WordPress site.

## Method 1: From WordPress Plugin Repository

1. Log in to your WordPress dashboard
2. Navigate to **Plugins** > **Add New**
3. Search for "Uptime Monitor"
4. Click **Install Now** and then **Activate**

## Method 2: Manual Installation

### Via WordPress Dashboard

1. Download the [latest release](https://github.com/lukasmajoros/uptime-monitor/releases/latest)
2. Log in to your WordPress dashboard
3. Navigate to **Plugins** > **Add New**
4. Click **Upload Plugin**
5. Choose the downloaded zip file and click **Install Now**
6. After installation, click **Activate Plugin**

### Via FTP

1. Download the [latest release](https://github.com/lukasmajoros/uptime-monitor/releases/latest)
2. Extract the zip file
3. Connect to your server using an FTP client
4. Upload the extracted `uptime-monitor` folder to the `/wp-content/plugins/` directory
5. Log in to your WordPress dashboard
6. Navigate to **Plugins**
7. Find "Uptime Monitor" and click **Activate**

## Method 3: Using Composer

```bash
composer require lukasmajoros/uptime-monitor
```

## Method 4: Using WP-CLI

```bash
wp plugin install uptime-monitor --activate
```

## System Requirements

- WordPress 5.0 or higher
- PHP 7.2 or higher
- MySQL 5.6 or higher
- Ability to create scheduled tasks (for the uptime checking functionality)

## Post-Installation

After installing and activating the plugin:

1. Navigate to **Uptime Monitor** in your WordPress admin menu
2. Add the devices you want to monitor
3. Configure the monitoring settings as needed
4. Use the shortcode `[uptime_monitor]` on any page or post to display the status panel
5. Alternatively, add the Uptime Monitor widget to any widget area

## Troubleshooting

### Ping Not Working

If pinging is not working correctly:

1. Make sure your server allows the execution of the `ping` command
2. Check if your server has outbound connectivity to the devices you're monitoring
3. Some hosting providers block ICMP traffic - contact your hosting provider for assistance

### Scheduled Tasks Not Running

If scheduled monitoring is not working:

1. Navigate to **Uptime Monitor** > **Settings**
2. Click "Force Ping All Devices" to test connectivity
3. Check your server's cron jobs to ensure they're running properly
4. Consider using an external cron service if your hosting has limitations

### Still Need Help?

- Check the [Wiki](https://github.com/lukasmajoros/uptime-monitor/wiki) for more information
- Submit an issue on [GitHub](https://github.com/lukasmajoros/uptime-monitor/issues)
- Visit the [support forum](https://wordpress.org/support/plugin/uptime-monitor/)

## Upgrading

To upgrade to a newer version:

1. Deactivate and delete the current version of the plugin
2. Follow the installation instructions above for the new version
3. Your existing settings and data will be preserved

Always back up your database before upgrading.