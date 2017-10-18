# Advanced Discord Bot

From kicking and banning people to giving roles for specific amounts of time, this Discord bot can be helpful for anyone who wants to learn how to make
a discord.js bot, I made this so new users can also look at the methods used for certain commands and get some ideas for their Discord bot.

## Commands

NOTE: ignore the [ ] that just shows what should be there when entering the command

```
speak [ANYTIHNG] - This will Make it look like the bot said whatever is put inside the []
coin - This will flip a coin that can either get heads or tales
8ball [QUESTION] - This will get a random answer for the question asked
embed - to show an example embed used for testing the positioning of the text
highlight [ANYTHING] This will make it look like the bot said whatever is in the []
timer [1s/1m/1h] - To start a timer for the given amount of time
invite - this is a basic embed made that shows the user the Perm invite i made then put in the code
notice - This is a basic command that shows how to reply to the person who used the command
play [YOUTUBE URL] - This can play a YouTube song, only 1 at a time
skip - This skips the current song and plays the next one
stop - This stops the currently playing song and disconnects the bot from the channel
userinfo - This shows whoever typed the command there profile info
images [SEARCH TERM] - This gets a random image everyime based upon the search results
memes - This gets a random meme from reddit, but there is alot of duplicates
```

## Admin Commands:

NOTE: ignore the [ ] that just shows what should be there when entering the command

```
dev - This is just a simple reply to the user
prefix [NEW PREFIX] - This can change the bots prefix (globally), i am working on a local version
rename [NAME] - This renames the bot to whatever "name" is
clear [NUMBER] - This purge deletes any amount of number of messages in a text channel
addrole [@NAME] [ROLE] [LENGTH] - This adds the role of the mentioned person for certain time
removerole [@NAME] [ROLE] - This removes the role mentioned from the person mentioned
kick [@NAME] - To kick the mentioned user from the server.
```

## TO DO:

* add more commands
* add more functionality
* maybe a overwatch stats checker
* maybe a CSGO float checker
* make a local prefix so it can be used on multiple servers
* make YouTube playlists supported

## Getting Started

* You will need [FFmpeg](https://www.ffmpeg.org/) for the play, stop and skip commands, because the ytdl-core package needs ffmpeg or it will not work.
* Make a folder and git clone this repository: https://github.com/MrWall112/Advanced-Dicsord-Bot.git
* Then type "npm install" to get the needed packages for the bot

## Built With:

* [Discord.js](https://discord.js.org/#/) - The Discord Library
* [Node JS](https://nodejs.org/en/) - Java Script Framework

## Authors:

* **Ben Wall** - Main Coder
* **James** - Second Coder
