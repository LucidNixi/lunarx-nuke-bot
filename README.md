# Lunarx Nuking Bot
Lunarx is currently the **FASTEST** and **FREE** open-source, self-hosted nuke bot available. All commands are specifically designed for **nuking-related** purposes.  

If you need assistance with the bot, feel free to contact me on Discord at **@230607x**. Please note, I might not respond immediately after you add me, but I will get back to you.  

We have combined **threading**, **queue**, **requests**, and the **discord.py API** to ensure the commands execute as quickly as possible. If you notice **rate limiting** logged in your console while using this script, it’s simply because it operates at such a high speed.  

To run the file from the source code, **Python version 3.8.0 or higher** is required.  

[Explore all 51 commands](manual.md)  

```
[addRole] [addChannel] [autoNick] [addVoiceChannel] [autoStatus]  
[addEmoji] [addCategory] [banAll] [bans] [ban] [channelBomb]  
[categoryBomb] [config] [checkRolePermissions] [connect] [categories]  
[changeStatus] [channels] [deleteRole] [deleteChannel]  
[deleteVoiceChannel] [deleteCategory] [deleteCC] [deleteEmoji]  
[deleteAllRoles] [deleteAllChannels] [disableCommunityMode]  
[deleteAllEmojis] [deleteAllWebhooks] [emojis] [grantAllPerm]  
[help] [joinNuke] [kaboom] [leave] [leaveAll] [link] [moveRole]  
[members] [nuke] [off] [purge] [roles] [roleBomb] [roleTo] [servers]  
[serverIcon] [serverName] [unban] [voiceChannels] [webhook]  
```  

## IMPORTANT:  
- We take **no responsibility** for how you use this bot.  
- Since Lunarx uses **HTTP requests**, unlike other nuke bots, it can **spam-create channels, roles, and categories (CRC)** beyond the usual 250-limit imposed by older nuking bots.  

---

## Guides  
### 1.0 Setup  
1. Run the `.exe` or `.py` file.  
2. When prompted with **"Enter token"**, input a bot token. Note that selfbot is no longer supported.  
3. Next, when prompted with **"Enter user ID or tag"**, provide the user ID or tag you wish to command the bot with. All command permissions will be granted to this user.  
4. To view available commands, run `.help`.  
5. To configure settings like after-commands or webhook spam, use `.config`. More details about configuration can be found within the `.config` command.  
6. If you encounter any issues, feel free to open an issue on our GitHub page.  

---

## Problems/Issues  
- If the bot doesn’t respond to commands, check if the console is in **highlighting/mark mode**. If it is, click the console and press any key to resolve the issue.  
- If you encounter a crash with a series of **white text errors** displayed in the console, it is likely a bug. Please report it by opening a new issue.  
