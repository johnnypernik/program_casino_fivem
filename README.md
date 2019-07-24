# program_casino_fivem
A resource-pack with casino scripts in Lua for ESX & fiveM
There is a perfect money circulation, when people win or lose, the money goes in and out of the casino's account.

# Required
* esx_society
* esx_datastore
* pNotify

# Installation 
1. Upload [cas] directory to resource directory
1. Add this to server.cfg
* >start program-casino
* >start program-blackjack
* >start slotmachine_1
3. Configure the files to your own liking.
4. Import program-casino.sql to database.


# Configurate
* To edit the Casino's zones you have to edit the config.lua in program-casino.
* To edit the Teleport pads to enter the casino, you have to edit it in program-casino/client/main.lua in the 'teleport' section.
* To edit the blackjack points you have edit program-blackjack/config.lua.
* To edit the slotmachine zones you have to edit slotmachine_1/client/main.lua. There is a lot of coords so you will find it easily.

# IMPORTANT
The map that showcases the resources is not uploaded here, you can easily download a version of it yourself or change the zones to other locations. Here is the link to the map: https://pl.gta5-mods.com/maps/sasino-interior

# CREDITS
Thanks to 's0ig', which have released slotmachine_1 that is used in this resource-pack.

If you find any bugs or exploits, please make an issue here on github or post a comment in the fiveM-forum post!
