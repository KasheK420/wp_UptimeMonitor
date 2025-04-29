# Changelog

All notable changes to the Uptime Monitor plugin will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.1.0] - 2025-04-29

### Added
- Device groups functionality for organizing monitored devices
- Multiple display themes: Modern, Compact, and Classic
- Response time tracking for performance monitoring
- Enhanced widget with device/group selection options
- Dashboard view with status overview and quick actions
- Email notifications when device status changes
- New shortcode options for greater customization
- Theme preview images in settings

### Changed
- Restructured plugin into multiple files for better organization
- Improved admin interface with tabbed navigation
- Enhanced CSS for better responsiveness on mobile devices
- Optimized database queries for better performance
- Updated ping mechanism to capture response times

### Fixed
- Issue with cron scheduling on some hosting environments
- Display glitches in status history timeline
- Widget display issues in some WordPress themes
- Database cleanup to prevent excessive log entries

## [1.0.0] - 2025-02-15

### Added
- Initial release
- Basic uptime monitoring functionality
- Device management interface
- Status display with uptime percentage
- 24-hour history visualization
- Shortcode support
- Widget for sidebar display

[1.1.0]: https://github.com/lukasmajoros/uptime-monitor/compare/v1.0.0...v1.1.0
[1.0.0]: https://github.com/lukasmajoros/uptime-monitor/releases/tag/v1.0.0