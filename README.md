
# ðŸ“˜ Blick Bot Documentation

Welcome to the official documentation for **Blick** â€“ your all-in-one Discord bot designed to make server management, moderation, and engagement easier than ever.

> Created with care to help Discord server admins and members thrive.

---

## ðŸ“Œ Table of Contents

1. [Features](#features)  
2. [Getting Started](#getting-started)  
3. [Installation & Inviting Blick](#installation--inviting-blick)  
4. [Permissions](#permissions)  
5. [Command Categories](#command-categories)  
6. [Command List](#command-list)  
7. [Configuration](#configuration)  
8. [Data & Privacy](#data--privacy)  
9. [Troubleshooting](#troubleshooting)  
10. [Support](#support)

---

## ðŸŽ¯ Features

- ðŸ”¨ **Moderation**: Kick, ban, mute, warn, and audit server activity.
- ðŸŽ‰ **Fun & Games**: Memes, trivia, image generation, and more.
- âš™ï¸ **Custom Configuration**: Set custom prefixes, auto roles, welcome messages.
- ðŸ§® **Utilities**: Polls, reminders, timers, server info, user lookups.
- ðŸ”” **Logging**: Message edits/deletes, join/leave logs, moderation logs.
- ðŸ’¬ **AI & Chat Features**: Optional AI chatbot, auto-responses, and smart replies.

---

## ðŸš€ Getting Started

### Requirements:
- A Discord server where you have admin/manage server permissions.
- A Discord account.

### Steps:

1. Invite Blick using the link: `[Insert Invite Link]`
2. Grant the requested permissions.
3. Type `!help` (or your configured prefix) in a server channel to see the available commands.
4. Start using features or run the setup wizard: `!setup`

---

## ðŸ”— Installation & Inviting Blick

Click the invite link below to add Blick to your server:

ðŸ‘‰ [**Invite Blick**](#)

Make sure to grant it the necessary permissions when prompted.

---

## ðŸ›¡ Permissions

Blick requires the following permissions to function properly:

- `Manage Messages`
- `Kick Members`
- `Ban Members`
- `Read Message History`
- `Send Messages`
- `Embed Links`
- `Use External Emojis`
- `Manage Roles` *(only if you use autorole or moderation)*

---

## ðŸ§­ Command Categories

| Category     | Description |
|--------------|-------------|
| Moderation   | Ban, kick, warn, mute, unmute, purge |
| Utility      | Server info, user info, poll, reminder |
| Fun          | Meme, coin flip, 8ball, trivia |
| AI & Chat    | AI replies, chatbot toggles, responses |
| Config       | Prefix, autorole, welcome, logs |
| Admin        | Setup, role management, permission checks |

---

## ðŸ“œ Command List

> Replace `!` with your bot's prefix if you customized it.

### Moderation Commands
```
!ban @user [reason]         - Ban a user
!kick @user [reason]        - Kick a user
!warn @user [reason]        - Warn a user
!warnings @user             - View warnings
!mute @user [time]          - Mute a user
!unmute @user               - Unmute a user
!purge [amount]             - Delete messages
```

### Utility Commands
```
!userinfo @user             - Shows user info
!serverinfo                 - Shows server details
!poll "Question" "Option1" "Option2" ...
!remindme [time] [message]  - Set a personal reminder
```

### Fun Commands
```
!meme                       - Random meme
!8ball [question]           - Ask the magic 8-ball
!coinflip                   - Flip a coin
!trivia                     - Start a trivia question
```

### AI & Chat Commands
```
!chatbot enable/disable     - Toggle chatbot
!respond add [trigger] [reply] - Add custom reply
!respond remove [trigger]   - Remove a reply
```

### Config Commands
```
!prefix [new_prefix]        - Change command prefix
!setup                      - Run setup wizard
!welcome set [channel] [message] - Set welcome message
!autorole set @role         - Set auto-role
!logs set [type] [channel]  - Set log channels
```

---

## âš™ï¸ Configuration

Blick can be customized per server. Use `!setup` to launch the guided setup, or use the specific commands above.

All configurations are stored per-server and persist across bot restarts.

---

## ðŸ” Data & Privacy

Blick stores only essential data to function:
- Server settings (prefix, welcome messages, logs, etc.)
- User warnings and moderation logs
- Chatbot configurations (if enabled)

Data is **never** shared, sold, or used outside the botâ€™s functionality. You can request deletion of your serverâ€™s data by contacting support.

---

## ðŸ›  Troubleshooting

| Problem                        | Solution |
|-------------------------------|----------|
| Bot not responding             | Check if it has proper permissions and role hierarchy. |
| Commands not working           | Check the prefix or use `@Blick help`. |
| AI/chat not responding         | Make sure it's enabled and youâ€™re using the right channel. |
| Log messages not showing       | Re-run `!logs set` to reconfigure channels. |

Still stuck? Join the support server below.

---

## ðŸ“ž Support

Need help? Have a bug report? Want to suggest a feature?

- ðŸ’¬ **Join our Support Server**: [Insert Discord invite]
- ðŸ“§ **Email us (optional)**: [Insert email]
- ðŸ§  **Feature Suggestions**: Use `!suggest [your idea]` in your server
