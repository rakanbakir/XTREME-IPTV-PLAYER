# XTREME IPTV PLAYER Feature Roadmap

This document tracks the progress of implementing additional features for the XTREME IPTV PLAYER (v4.0). Features are prioritized based on feasibility and user impact. Each feature includes a brief description, estimated complexity, and implementation status.

## 1. Recently Watched List
- **Description**: Track the last 10-20 played channels/movies/episodes. Display in a new tab or section with quick-play buttons. Persist across sessions.
- **Complexity**: Medium
- **Status**: [ ] Not Started

## 2. Global Search Across All Tabs
- **Description**: A single search bar that searches LIVE channels, Movies, Series, and Favorites simultaneously. Results grouped by category with clickable items.
- **Complexity**: Medium
- **Status**: [ ] Not Started

## 3. Playlist Export/Import
- **Description**: Export Favorites or full playlists to M3U files. Import M3U playlists from files or URLs, adding them as custom categories.
- **Complexity**: Medium
- **Status**: [ ] Not Started

## 4. EPG Enhancements
- **Description**: Program search within EPG data, reminders/alerts for upcoming programs, and EPG cache management (manual/auto-refresh).
- **Complexity**: High
- **Status**: [ ] Not Started

## 5. Stream Recording
- **Description**: Add a "Record" button in the context menu to save streams to MP4 files using mpv or ffmpeg. Choose duration or record until stopped.
- **Complexity**: High
- **Status**: [ ] Not Started

## 6. Customizable Themes and UI Improvements
- **Description**: More built-in themes (light/dark variants), user-customizable colors via settings dialog, and improved icons/channel logos.
- **Complexity**: Medium
- **Status**: [ ] Not Started

## 7. Keyboard Shortcuts
- **Description**: Hotkeys for play/pause, volume, tab switching, search, etc. Configurable in a settings menu.
- **Complexity**: Low
- **Status**: [ ] Not Started

## 8. Parental Controls
- **Description**: Password-protect certain categories (e.g., adult content). Age ratings for VOD/Series with filters.
- **Complexity**: Medium
- **Status**: [ ] Not Started

## 9. Resume Playback for VOD/Series
- **Description**: Track progress for movies/series and resume from where left off. Save timestamps to config.
- **Complexity**: Medium
- **Status**: [x] Completed

## 10. Multi-Server Support
- **Description**: Allow switching between multiple saved servers without restarting. Profiles for different accounts.
- **Complexity**: High
- **Status**: [ ] Not Started

## 11. Notifications and Alerts
- **Description**: System tray notifications for login status, EPG updates, errors, and expiring subscriptions.
- **Complexity**: Medium
- **Status**: [ ] Not Started

## 12. Performance and Bug Fixes
- **Description**: Optimize loading times, lazy-load data, fix UI glitches, and improve error handling.
- **Complexity**: Ongoing
- **Status**: [x] Completed

## 13. Backup/Restore
- **Description**: Backup all settings, favorites, and credentials to a ZIP file. Restore from backup.
- **Complexity**: Medium
- **Status**: [ ] Not Started

## 14. Integration with External APIs
- **Description**: Fetch more metadata from TMDb or IMDb for better descriptions/posters. Optional weather/news overlays.
- **Complexity**: High
- **Status**: [ ] Not Started

## Notes
- **Prioritization**: Start with low/medium complexity features like Keyboard Shortcuts or Recently Watched List.
- **Dependencies**: Some features (e.g., EPG Enhancements) build on existing EPG code.
- **Testing**: Each feature should be tested with real IPTV credentials where possible.
- **Updates**: Mark status as [x] In Progress or [x] Completed as we implement.

Last Updated: November 14, 2025</content>
<parameter name="filePath">/home/rakan/Github/XTREME-IPTV-PLAYER-by-MY-1/context.md