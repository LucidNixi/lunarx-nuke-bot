# Nuking Discord Server Bot/Nuke Bot
## Made by pablo
Lunarx is currently the **FASTEST** and **FREE** open source self-hosted nuke bot out here. All commands will be focused on nuking-related.

If you need help with the bot contact me on discord @230607x, I might not answer right after you add me but i will answer.

We have combined threading, queue, requests, and discord.py API to make the commands run as fast as possible. If you are seeing

rate limiting logged in your console while using this script, then that is simply because it runs too fast.

Python version 3.8.0 or higher is required if you are going to run the file from source code.

[All 51 commands](manual.md)

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

# IMPORTANT: 
* We will not take any responsibility over whatever you are going to do with this bot.
* Also, since we are using HTTP requests, unlike other nuke bot out there, Lunarx spam creating channel, role, and category(CRC) can create beyond the 250 limit for CRC that the old nuking bots have.

## Guides
### 1.0 setup
* Run the .exe or the .py
* You will see the "Enter token" message. You can only enter a bot token because selfbot is no longer supported.
* Next you will see "Enter user ID or tag", you should enter the user ID or tag that you wanted to command the bot with. All command permissions will be granted to the user with the ID or tag you entered here.
* If you want to know what commmands are there, then run `.help`
* If you want to config any settings like the after commands or the webhook spam commands, you have to use `.config`. For more information on how to config will be in the `.config` command.
* If you are having problems, feel free to make a issue in this github page.  

## Problems/issues
* If the bot doesn't respond to any of the commands, check if the console is in highlighting/mark mode. If it's highlighting/mark mode, click the console then press any key on your keyboard, and it'll resolve.
* If you see a bunch of white worded errors displaying in the console, and then crashed that means it's 90% a bug. So please make a new issue about it.
