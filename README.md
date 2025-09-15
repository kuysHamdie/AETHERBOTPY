# AETHERBOTPY

AETHERBOTPY is a customizable Discord admin bot built with **discord.py**.  
It offers secure access control, server moderation tools, and easy management — perfect for communities that want safety, control, and automation.

---

## ✨ Features

- **Access Control**  
  Only the owner, server admins, or whitelisted users can use most commands.

- **Moderation**  
  - Kick members  
  - Ban members  
  - Assign roles  
  - Remove roles

- **Info & Utility Commands**  
  - Check if bot is online (`!status`)  
  - Get server info (`!serverinfo`)  
  - Get user info (`!userinfo @user`)  
  - Ping latency (`!ping`)  

- **Owner-only Controls**  
  - `!shutdown` — shut the bot down  
  - `!restart` — restart the bot  
  - `!setstatus <type> <text>` — change bot’s status message  
  - Whitelist management: add/remove/show allowed users

- **Persistence**  
  - Bot remembers its last status after restarts  
  - Whitelist is saved so permissions persist between runs

---

## 📋 Prerequisites

- Python 3.9+  
- `discord.py` library  
- A Discord Bot account (token)  
- Enabled intents:
  - Message Content Intent  
  - Server Members Intent  
  - (Others depending on features: presence, etc.)

---

## 🛠 Setup & Installation

1. Clone this repo:  
   ```bash
   git clone https://github.com/kuysHamdie/AETHERBOTPY.git
   cd AETHERBOTPY
