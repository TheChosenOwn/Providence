# 📋 Changelog

All notable changes to **Providence** will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/).

---

## [0.3.0] - Latest Release

### ✨ Added
- **DAVE Protocol Support** for voice channel blazing
  - End-to-end encrypted voice connections
  - Improved voice connection reliability
- **Permission System** for chat commands
  - Configurable allowed user IDs
  - Empty = everyone can use commands
  - Per-command permission checks

### 🔧 Changed
- Simplified DAVE implementation approach
- Improved voice connection stability
- Better account reconnection handling

### 🐛 Fixed
- **"File is not defined" error** - Fixed initialization order
- Voice connection stability issues
- Account reconnection handling

---

## [0.2.0]

### ✨ Added
- **Multi-Account System** - Complete rewrite
  - Account groups: Main, Raid, Spam, Alt
  - Add/remove accounts dynamically
  - Connect/disconnect individual accounts
  - Connect/disconnect all accounts
  - Primary account system
  - Account-specific task execution
- **GUI Commands Page** - New command center
  - Expandable command cards
  - Input fields for parameters
  - Speed/intensity sliders
  - Account selector dropdown
  - Stop buttons for each command
- **Chat Commands** - Remote control via Discord
  - Configurable prefix (default: `!`)
  - Enable/disable toggle in settings
  - Commands: ping, spam, kill, ladder, blaze, autoreply, avatar, stream, help
- **Live Activity Log** in Dashboard
  - Real-time event logging
  - Account name labels
  - Event type tags (OK, INFO, WARN, ERR)
  - Auto-scroll with 100 entry limit

### 🎨 UI Improvements
- Animated background glow effects
- Custom titlebar with window controls (minimize, maximize, close)
- Improved account cards with group badges
- Stat cards on dashboard (Accounts, Active, Messages, Uptime)
- Quick account switch in sidebar
- Connection status indicator

---

## [0.1.0]

### ✨ Added
- **Initial Release** of Providence
- Basic Discord selfbot functionality
- Single account support
- Modern GUI with dark theme
- Basic commands:
  - Spam commands
  - Kill command
  - VC Blazing (basic)
  - Auto-reply
- Dashboard with connection status
- Settings page with wordlist configuration

---

## 📊 Version Overview

| Version | Major Features | Status |
|---------|---------------|--------|
| 0.3.0 | DAVE Protocol, Permissions | **Current** |
| 0.2.0 | Multi-account, GUI Commands, Chat Commands | Deprecated (never realesed) |
| 0.1.0 | Initial release | Deprecated (never realesed) |

---

## 🔮 Roadmap

### Planned for 0.4.0
- [ ] Custom themes/skins
- [ ] Proxy support per account
- [ ] Message queue system
- [ ] Export/import accounts
- [ ] Auto-reconnect on disconnect

### Planned for 0.5.0
- [ ] Plugin system
- [ ] Custom command scripting
- [ ] Multiple language support

---

<div align="center">

**[⬆ Back to Top](#-changelog)**

</div>
