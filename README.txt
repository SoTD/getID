getID - "get item id by name and vice versa"
Version: 0.4

Description:
"getID" is my first plugin for bukkit. If you input an item name, it outputs the corresponding item ID. I wrote this plugin mostly to get into bukkit development and to improve my java programming-skill. And yet, it's helpful for me and maybe for you sometimes. I remember many times i thought "damn what was the id for this item again.."..so you maybe give it a try.

Usage:
Put "getID.jar" in your server's /plugin/ directory.

To get an item ID: /getid <item name>
Example: /getid stone, /getid pink dye, ...

To get an item name: /getname <id>
Example: /getname 20, /getname 328,..

To add an alias: /getidadd <alias> <id>
Example: /getidadd diapick 278, /getidadd cart 328,..

To remove an alias: /getidrem <alias>
Example: /getidrem diapick, /getidrem cart

Editing the item configuration file (getid.ini):
If you want to add an alias without using in-game commands, or if you want to edit the itemlist, you can do this in the "getid.ini"-file located in "plugins/getID/getid.ini". The items are sorted by the ID. There shouldn't be any itemname or alias twice, otherwise the plugin might not work properly.
You can find the place to add aliases at the bottom, under "###ALIAS###.
Example:
###ALIAS###
278=diapick
328=cart

If you did anything wrong, just delete the "get.ini"-file and restart the server, or reload the plugin. It will create a fresh "get.ini"-file for you.

Permissions:
If you want to use permissions, use this node:
getid.id - for /getid command
getid.name - for /getname command
getid.add - for /getidadd command
getid.rem - for /getidrem command

Download:
Version: 0.4 - https://github.com/SoTD/getID/raw/master/getID.jar