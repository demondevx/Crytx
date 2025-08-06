# 🤖 Crytx Bot - User Guide

## 📋 Table of Contents
- [Getting Started](#getting-started)
- [Command Categories](#command-categories)
- [Moderation Commands](#moderation-commands)
- [Fun Commands](#fun-commands)
- [Utility Commands](#utility-commands)
- [Games](#games)
- [Configuration](#configuration)
- [Troubleshooting](#troubleshooting)

---

## 🚀 Getting Started

### Inviting Crytx to Your Server
1. Use `/invite` command or click the invite link
2. Grant necessary permissions
3. Use `/help` to see all available commands

### Basic Commands
- `/help` - Show all commands and categories
- `/ping` - Check bot latency
- `/botinfo` - View bot information

---

## 🛡️ Moderation Commands

### User Management
```
/ban user:@user reason:[text] - Ban a user from the server
/kick user:@user reason:[text] - Kick a user from the server
/mute user:@user duration:[time] reason:[text] - Mute a user
/unmute user:@user - Unmute a user
/softban user:@user reason:[text] - Ban and delete messages
/unban user:[user-id] - Unban a previously banned user
```

### Warning System
```
/warn user:@user reason:[text] - Warn a user
/warnings user:@user - View user's warnings
/clearwarnings user:@user - Clear all warnings
```

### Role Management
```
/addrole user:@user role:@role - Add role to user
/removerole user:@user role:@role - Remove role from user
/createrole name:[name] color:[hex] - Create new role
/roleall role:@role - Add role to all members
```

### Channel Management
```
/purge amount:[number] - Delete multiple messages
/nuke - Delete all messages in channel
/lock - Lock channel for everyone
/unlock - Unlock channel
```

### Voice Management
```
/voicekick user:@user - Kick user from voice channel
/votekick user:@user - Start vote kick
```

---

## 🎮 Fun Commands

### Interactive Commands
```
/8ball question:[text] - Ask the magic 8-ball
/joke - Get a random joke
/roast user:@user - Roast someone (for fun)
/respect user:@user - Pay respects
/trigger user:@user - Trigger someone
```

### Social Interactions
```
/hug user:@user - Hug someone
/kiss user:@user - Kiss someone
/slap user:@user - Slap someone
/cuddle user:@user - Cuddle someone
/pet user:@user - Pet someone
/feed user:@user - Feed someone
/spank user:@user - Spank someone
```

### Games
```
/catchthefish - Fishing mini-game
/football - Football game
/gunfight - Gunfight game
/snake - Snake game
/chess - Chess game
/poker - Poker game
```

---

## 🛠️ Utility Commands

### Information Commands
```
/userinfo user:@user - Get user information
/serverinfo - Get server information
/channelinfo - Get channel information
/avatar user:@user - Get user's avatar
/emojiid emoji:[emoji] - Get emoji ID
/userid user:@user - Get user ID
```

### Server Management
```
/announce message:[text] - Make an announcement
/poll question:[text] - Create a poll
/vote question:[text] - Create a vote
/suggestion message:[text] - Submit a suggestion
```

### External Services
```
/weather city:[name] - Get weather information
/google query:[text] - Search Google
/wiki query:[text] - Search Wikipedia
/lyrics song:[name] - Get song lyrics
```

### Channel Management
```
/createtext name:[name] - Create text channel
/createvoice name:[name] - Create voice channel
/delchannel - Delete current channel
```

---

## ⚙️ Configuration

### Server Settings
```
/config - View current configuration
/prefix prefix:[new-prefix] - Set server prefix
/autorole role:@role - Set auto-role for new members
/antilink enable/disable - Toggle anti-link protection
```

### Ticket System
```
/ticket - Configure ticket system
/tickets - View ticket settings
```

### Welcome/Leave Messages
```
/joinmessage message:[text] - Set welcome message
/leavemessage message:[text] - Set leave message
/joinchannel channel:#channel - Set welcome channel
/leavechannel channel:#channel - Set leave channel
```

---

## 🔧 Troubleshooting

### Common Issues

**Bot not responding:**
- Check if bot has proper permissions
- Verify bot is online
- Use `/ping` to test connectivity

**Commands not working:**
- Ensure you have required permissions
- Check if command is enabled
- Use `/help` to verify command syntax

### Permission Requirements

**Moderation Commands:**
- Ban Members, Kick Members, Manage Roles
- Manage Messages, Manage Channels

**Configuration Commands:**
- Manage Server, Manage Roles

---

## 📞 Support

- **Server Issues:** Contact server administrators
- **Bot Issues:** Use `/suggestion` to report bugs
- **Feature Requests:** Submit via `/suggestion`
- **Support Server:** [Join our Discord](https://discord.gg/BvQRGsMtCZ)
- **Bot Owner:** @demondev_

---

## 🎯 Tips for Best Experience

1. **Use slash commands** - They provide better UX with parameter validation
2. **Check permissions** - Ensure bot has necessary permissions
3. **Read command descriptions** - Use `/help [command]` for detailed info
4. **Report issues** - Help improve the bot by reporting bugs
5. **Stay updated** - Check for bot updates regularly

---

*Last updated: 6 August 2025*
*Bot Version: 2.0* 
