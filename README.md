<div align="center">

# ⬡ Providence

**Advanced Discord Selfbot GUI Application**

*A powerful, multi-account Discord selfbot with an elegant interface*

[![Version](https://img.shields.io/badge/version-0.3.0-7c6af7?style=for-the-badge)](https://github.com/TheChosenOwn/providence)
[![License](https://img.shields.io/badge/license-MIT-4ade80?style=for-the-badge)](LICENSE)
[![Platform](https://img.shields.io/badge/platform-Windows-4ade80?style=for-the-badge)](https://github.com/TheChosenOwn/providence)

</div>

---

## 📋 Table of Contents

- [Features](#-features)
- [Preview](#-preview)
- [Download](#-download)
- [Usage](#-usage)
- [Commands](#-commands)
- [Disclaimer](#-disclaimer)
- [License](#-license)

---

## ✨ Features

### 🎮 Multi-Account Management
- Add unlimited Discord accounts
- Organize accounts into groups: **Main**, **Raid**, **Spam**, **Alt**
- Connect/disconnect accounts individually or all at once
- Set primary account for priority operations

### 💻 Modern GUI Interface
- Beautiful dark theme with animated background glows
- **Custom themes/skins** - Personalize your interface
- Custom titlebar with window controls
- Real-time activity log panel
- Dashboard with statistics (accounts, tasks, messages, uptime)

### ⚡ Chat Commands (Remote Control)
- Let trusted users control your bot via Discord chat
- Configurable prefix (default: `!`)
- Permission system with allowed user IDs

### 🔌 Plugin System
- Extend functionality with custom plugins
- Easy plugin installation and management
- Create your own plugins with the plugin API
- Plugins can add custom chat commands

### 📜 Custom Command Scripting
- Write your own automation scripts
- JavaScript-based scripting system
- Run scripts from GUI or via chat command
- Share scripts with the community

### 🌍 Multiple Language Support
- Interface available in multiple languages
- Easy language switching in settings
- Create and share language packs

### 🎨 Custom Themes/Skins
- Built-in dark theme
- Create custom color schemes
- Color picker for all UI elements
- Export and share themes

### 🔥 Spam & Kill Features
- **Fast Spam** - Rapid message spamming
- **Kill** - Target specific users in channels
- **Ladder Spam** - Ascending/descending number patterns
- **Random Send** - Random word messages from wordlist

### 🎵 VC Blazing (DAVE Support)
- Play audio in voice channels
- DAVE protocol support for E2EE voice
- Custom MP3 file support
- Auto-join voice channels
- Loop audio playback

### 🛡️ Automation
- **Auto-Reply** - Automatically reply to specific users
- **Auto-React** - React to messages automatically
- **Anti Group-DM** - Auto-leave group DMs

### 📊 Utility
- Delete messages in bulk
- Get user avatars
- User overview/stats
- Mass DM friends
- Set streaming status

---

## 🖼️ Preview

```
┌─────────────────────────────────────────────────────────────┐
│  ⬡ PROVIDENCE                              v0.3.0       ○ ○ │
├────────────┬────────────────────────────────────────────────┤
│            │  Dashboard                          🔌 ⛔     │
│  ⬡ Dashboard│─────────────────────────────────────────────│
│  👥 Accounts│  ┌─────┐ ┌─────┐ ┌─────┐ ┌─────┐            │
│  ⌘ Commands │  │Accs │ │Active│ │Msgs │ │Time │            │
│  🔌 Plugins │  │  3  │ │  2  │ │ 156 │ │01:23│            │
│  📜 Scripts │  └─────┘ └─────┘ └─────┘ └─────┘            │
│  🎨 Themes  │                                                │
│  ⚙ Settings │  ┌──────────────────────────────────────────┐ │
│            │  │ 👤 MyMain#1234          🔵 MAIN     🟢  │ │
│ Quick Switch│  │ ─────────────────────────────────────── │ │
│  ● Main    │  │ [Disconnect] [Remove] [Primary]          │ │
│  ○ Raid1   │  └──────────────────────────────────────────┘ │
│            │                                                │
│────────────│  ┌──────────────────────────────────────────┐ │
│ 3 accounts │  │ Live Log                          All Accs│ │
│ ● Connected│  │ 12:34:56 [Main] OK Connected             │ │
└────────────┴─│ 12:35:01 [Raid1] WARN Task started      │ │
               └──────────────────────────────────────────┘ │
               └────────────────────────────────────────────────┘
```

---

## 📥 Download

### Requirements
- **Windows 10/11** (64-bit)

### Get the Latest Release

1. Go to the [Releases](https://github.com/TheChosenOwn/providence/releases) page
2. Download `Providence Setup 0.3.0.exe`
3. Run the installer
4. Launch Providence from your desktop

---

## 🎯 Usage

### Adding Accounts

1. Open the **Accounts** page from the sidebar
2. Paste your Discord token in the Token field
3. Enter a name for the account
4. Select a group (Main/Raid/Spam/Alt)
5. Click **Add Account**

### Getting Your Discord Token

⚠️ **Warning**: Never share your token with anyone!

1. Open Discord in your browser
2. Press `F12` to open Developer Tools
3. Go to **Application** → **Local Storage** → `https://discord.com`
4. Find the `token` entry and copy its value

### Using Commands

1. Navigate to the **Commands** page
2. Select an account (or "All Accounts")
3. Expand a command card
4. Fill in the required parameters
5. Adjust speed slider if available
6. Click **Execute**

### Chat Commands (Remote Control)

Enable chat commands in Settings to allow control via Discord messages:

| Command | Description |
|---------|-------------|
| `!ping` | Check bot status |
| `!spam <channelId> <msg>` | Start spamming |
| `!stopspam` | Stop spamming |
| `!kill <channelId> <userId>` | Kill a user |
| `!stopkill` | Stop kill |
| `!ladder <channelId> [userId]` | Ladder spam |
| `!blaze <vcId> [mp3]` | Play audio in VC |
| `!stopblaze` | Stop audio |
| `!runscript <name>` | Run a custom script |
| `!autoreply <userId> <msg>` | Auto-reply to user |
| `!avatar <userId>` | Get user avatar |
| `!stream <status>` | Set streaming status |
| `!help [command]` | Show help |

---

## 📋 GUI Commands

### Utility Commands
| Command | Description | Arguments |
|---------|-------------|-----------|
| Delete Messages | Delete messages in a channel | Channel ID, Amount |
| Get Avatar | Get a user's avatar URL | User ID |
| User Overview | Get user information | User ID |

### Automation Commands
| Command | Description | Arguments |
|---------|-------------|-----------|
| Auto-Reply | Automatically reply to a user | User ID, Message |
| Auto-React | React to user's messages | User ID, Emoji |
| Anti Group-DM | Auto-leave group DMs | None |

### Spam Commands
| Command | Description | Arguments | Speed |
|---------|-------------|-----------|-------|
| Fast Spam | Rapid message spam | Channel ID, Message | Adjustable |
| Kill | Target user in channel | Channel ID, User ID | Adjustable |
| Ladder Spam | Number pattern spam | Channel ID, User ID | Adjustable |
| Random Send | Random wordlist messages | Channel ID | Adjustable |

### VC Commands
| Command | Description | Arguments |
|---------|-------------|-----------|
| VC Blaze | Play audio in voice channel | VC ID, MP3 Path |

### Other Commands
| Command | Description | Arguments |
|---------|-------------|-----------|
| Set Stream | Set streaming status | Status Text |
| Mass DM | DM all friends | Message |

---

## ⚙️ Settings

### Wordlists

Configure wordlists in **Settings** for random message features:
- **Wordlist 1** - Used for Kill, Random, and Ladder commands
- **Wordlist 2** - Used for Ladder2 command

Load wordlists from `.txt` files or paste directly.

### Chat Commands Settings

| Setting | Description | Default |
|---------|-------------|---------|
| Enable Chat Commands | Allow remote control via Discord | On |
| Command Prefix | Prefix for chat commands | `!` |
| Allowed User IDs | Users who can use commands (empty = everyone) | Empty |

### Themes

Customize your interface in the **Themes** page:
- Choose from built-in themes
- Create custom color schemes with color pickers
- Preview themes before applying
- Export/import theme files

### Plugins

Extend functionality in the **Plugins** page:
- Install plugins from `.js` files
- Enable/disable installed plugins
- Create your own plugins

### Scripts

Create automation scripts in the **Scripts** page:
- Built-in script editor
- Run scripts from GUI or chat
- Access Discord client in scripts

---

## ⚠️ Disclaimer

> **This software is for educational purposes only.**

Using selfbots violates Discord's Terms of Service and may result in:
- Account termination
- IP banning
- Legal action in severe cases

**Use at your own risk.** The developers are not responsible for any consequences resulting from the use of this software.

### Safety Tips
- Don't use on your main account
- Use reasonable delays between actions
- Don't spam in servers you care about
- Be aware of Discord's rate limits

---

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

<div align="center">

**[⬆ Back to Top](#-providence)**

Made with 💜 by TheChosenOwn

*Star ⭐ this repo if you find it useful!*

</div>
