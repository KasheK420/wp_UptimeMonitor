# Uptime Monitor

![Version](https://img.shields.io/badge/version-1.1.0-blue.svg)
![PHP Version](https://img.shields.io/badge/php-%3E%3D%207.2-8892BF.svg)
![WordPress Version](https://img.shields.io/badge/wordpress-%3E%3D%205.0-0073aa.svg)
![License](https://img.shields.io/badge/license-GPL--2.0%2B-green.svg)

A powerful WordPress plugin for monitoring device uptime with visual status displays and notification capabilities.

![Uptime Monitor Preview](assets/screenshot-1.png)

## Features

- **Real-time Status Monitoring:** Automatically pings your devices and services at configurable intervals
- **Visual Status Display:** Clear visual indicators show up/down status with customizable themes
- **Device Grouping:** Organize your devices into logical groups for easier management
- **Flexible Display Options:** Add status displays anywhere with shortcodes or widgets
- **Detailed History:** Track 24-hour uptime history with visual timeline
- **Response Time Tracking:** Monitor response times for performance insights
- **Email Notifications:** Get alerted when a device goes down
- **Mobile-friendly:** Responsive design works on all devices

## 🎨 Available Themes

Choose from multiple display themes to match your site's design:

- **Modern**: A card-based layout with visual indicators and detailed device information
- **Compact**: A space-efficient list view, ideal for sidebars or when monitoring many devices
- **Classic**: The original uptime monitor style with simple status indicators

## 📋 Usage

### Shortcodes

Use these shortcodes to display your uptime monitor on any page or post:

```
[uptime_monitor]                         // Display all devices
[uptime_monitor group="Group Name"]      // Display devices from a specific group
[uptime_monitor device_ids="1,2,3"]      // Display specific devices by ID
[uptime_monitor theme="modern"]          // Set the display theme
[uptime_monitor title="Custom Title"]    // Set a custom title
```

Example:
```
[uptime_monitor group="Servers" theme="modern" title="Server Status"]
```

### Widget

The Uptime Monitor Widget can be added to any widget area in your theme.

## 🔧 Installation

See [INSTALLATION.md](INSTALLATION.md) for detailed installation instructions.

## 📄 Documentation

Full documentation is available in the [Wiki](https://github.com/lukasmajoros/uptime-monitor/wiki).

## 📝 Changelog

### 1.1.0 (April 29, 2025)
- Added device groups functionality
- Added multiple display themes (Modern, Compact, Classic)
- Improved widget with device selection options
- Added response time tracking
- Improved admin interface with dashboard

### 1.0.0 (February 15, 2025)
- Initial release

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📜 License

This project is licensed under the GPL-2.0+ License - see the [LICENSE.md](LICENSE.md) file for details.

## 👤 Author

- **Lukáš Majoros** - [lukasmajoros](https://github.com/lukasmajoros)

---

Made with ❤️ for the WordPress community.