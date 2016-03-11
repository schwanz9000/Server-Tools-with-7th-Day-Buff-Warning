# 7dtd-ServerTools with 7th Day Buff Warning
Server tools for 7 days to die dedicated servers<br>

#7th Day Buff Warning Branch
Added a Buff and a Warning to display during each 7th day.<br>
Requires the Info Ticker to be setup with at least one message to display.<br>
This branch uses the info ticker message(s) as the trigger to test the day number and display a buff and warning if it is a 7th day.<br>

# Installation
Go to https://github.com/dmustanger/7dtd-ServerTools/releases<br>
Download and extract the files.<br>
Copy the Mods folder to the root directory of your sever.<br>
Start the server. The mod will auto create the config file in the game save directory. Enable each part of the mod you want via ..\your game save directory\ServerTools\ServerToolsConfig.xml<br>
Once a module is enabled if it has a config it will auto create them in the ServerTools folder.<br>

# Current Features
Custom chat commands with custom color. Add your own commands via config.<br>
/Gimme with adjustable timer and items via config.<br>
/Killme with adjustable timer via config.<br>
/home /sethome /delhome with adjustable timer for /home via config.<br>
High ping kicker with ping immunity. Can add players to the immunity list via config or console command.<br>
Ban or kick players for invalid items/blocks in their inventory. Chose what items/blocks are invalid via config.<br>
Alert players of Invalid Item stack numbers in their inventory.<br>
Chat logger. Saves all ingame chat to a log file in the game save directory.<br>
Bad word filter. Replaces bad words with "*****". Can add bad words via config.<br>
Motd adjustable via config.<br>
InfoTicker/Scrolling messages adjustable via config.<br>
Auto save the world every x amount of minutes adjustable via config.<br>