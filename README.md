### mikrotik routeros auto dns switcher for pihole

In order for services like pihole or adguard home to work under mikrotik networks, a script like this or similar has to be used, if more than one DNS servers need to be set such as backup.

Remember to edit variables in the script:

telegramBotKey - your telegram bot token

chatID - the telegram group you want to receive notifications at (the bot has to be in there)

piholeDNS - adguard home or pihole IP

backupDNS - secondary dns ip addresses, separate with commas

testDomain - domain to be used for dns query check, use something like www.google.com or your own domain

Use on routeros under system / scheduler / add. 

Set interval 30-40 seconds or something, paste script under 'event'