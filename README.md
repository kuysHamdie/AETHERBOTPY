# 🤖 Discord Admin Bot

A powerful and customizable **Discord server management bot** built with [discord.py](https://discordpy.readthedocs.io).  
This bot provides moderation, server info, and custom access control for a safe and well-managed community.

---

## ✨ Features

- 🔒 **Access Control**
  - Only the **owner**, **admins**, or **whitelisted users** can use most commands.
  - Owner can manage who is whitelisted.

- 🔨 **Moderation Commands**
  - `!kick @user [reason]` → Kick a member
  - `!ban @user [reason]` → Ban a member
  - `!addrole @user @role` → Give a role
  - `!removerole @user @role` → Remove a role

- ⚙️ **Owner Only Commands**
  - `!shutdown` → Shut down the bot
  - `!restart` → Restart the bot
  - `!setstatus <type> <text>` → Change the bot’s activity/status
  - `!addwhitelist @user` → Add a user to whitelist
  - `!removewhitelist @user` → Remove a user from whitelist
  - `!showwhitelist` → Show all whitelisted users

- 📊 **Info Commands**
  - `!status` → Check if the bot is online
  - `!serverinfo` → Show server information
  - `!userinfo [@user]` → Show user details
  - `!ping` → Check bot latency

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/discord-admin-bot.git
cd discord-admin-bot
