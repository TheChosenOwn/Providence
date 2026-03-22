# 📋 Changelog

All notable changes to **Providence** will be documented in this file.

---

## [0.3.0] - Initial Release

### ✨ Core Features

#### Multi-Account System
- Add unlimited Discord accounts with token authentication
- Account groups: Main, Raid, Spam, Alt with color-coded badges
- Connect/disconnect accounts individually or all at once
- Primary account designation for priority operations
- Account-specific task execution
- Persistent account storage across sessions

#### Modern GUI Interface
- Beautiful dark theme with animated background glow effects
- Custom frameless titlebar with minimize, maximize, close buttons
- Dashboard with real-time statistics (accounts, active tasks, messages, uptime)
- Live activity log with color-coded event types
- Sidebar navigation with quick account switching
- Smooth page transitions and hover animations

### 🔌 Plugin System
- Load custom plugins from `plugins/` folder
- Plugins can extend functionality with custom commands
- Enable/disable plugins without restart
- Plugin API with access to Discord client
- Built-in plugin template and documentation

### 📜 Custom Command Scripting
- Create automation scripts with JavaScript
- Built-in script editor with syntax highlighting
- Run scripts from GUI or via `!runscript` chat command
- Access to Discord client, account, and logging functions
- Share and import scripts easily

### 🌍 Multiple Language Support
- Interface translation system
- English included by default
- Load custom languages from `languages/` folder
- Easy language switching in settings
- Create and share language packs

### 🎨 Custom Themes/Skins
- CSS variable-based theming system
- Built-in dark theme
- Visual theme editor with color pickers
- Preview themes before applying
- Export/import theme JSON files
- Customize: background, accent, text, success, warning, error colors

### ⚡ Chat Commands (Remote Control)
- Control bot via Discord messages
- Configurable command prefix (default: `!`)
- Permission system with allowed user IDs
- Help command with usage information

#### Available Chat Commands
| Command | Description |
|---------|-------------|
| `!ping` | Check bot latency |
| `!spam` | Start message spam |
| `!stopspam` | Stop spamming |
| `!kill` | Target user with spam |
| `!stopkill` | Stop kill |
| `!ladder` | Ladder pattern spam |
| `!blaze` | Play audio in VC |
| `!stopblaze` | Stop audio |
| `!runscript` | Run custom script |
| `!autoreply` | Set auto-reply |
| `!avatar` | Get user avatar |
| `!stream` | Set streaming status |
| `!help` | Show commands |

### 🔥 Spam & Kill Features
- **Fast Spam** - Rapid message spamming with adjustable speed (400-5000ms)
- **Kill** - Target specific users with wordlist + mention spam
- **Ladder Spam** - Sequential wordlist messages with counters
- **Ladder Spam 2** - Alternative wordlist option
- **Random Send** - Random words from configured wordlist
- **Slow/Fast Send** - Timed message sending options

### 🎵 VC Blazing
- Play audio in voice channels with DAVE E2EE support
- Custom MP3 file support
- Default audio file fallback
- Adjustable volume (14.4x boost)
- Auto-loop playback
- Connection state handling (disconnect/reconnect)

### 🛡️ Automation Features
- **Auto-Reply** - Automatically reply to specific users
- **Auto-React** - React to user's messages with emoji
- **Anti Group-DM** - Automatically leave group DMs

### 📊 Utility Features
- Delete own messages in bulk
- Get user avatar URLs
- User overview with account details
- Mass DM all friends
- Set streaming status with custom text

### ⚙️ Settings & Configuration
- Wordlist 1 for Kill/Random/Ladder commands
- Wordlist 2 for Ladder2 command
- Load wordlists from `.txt` files
- Chat commands enable/disable toggle
- Command prefix configuration
- Allowed users whitelist

### 🔧 Technical Features
- Built with Electron 28
- discord.js-selfbot-v13 for Discord API
- @discordjs/voice for voice support
- @snazzah/davey for DAVE protocol
- ffmpeg-static for audio processing
- Auto-updating FFMPEG path for packaged builds




---

## Roadmap

### Coming Soon
- Proxy support per account
- Message queue system
- Export/import accounts
- Auto-reconnect on disconnect

### Future Considerations
- Linux/macOS support
- Cloud sync for settings
- More automation features

---

<div align="center">

**[⬆ Back to Top](#-changelog)**

</div>
