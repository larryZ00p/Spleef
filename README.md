<div align="center">
    <img src="data/PotatoBotBranding.png"/>
    <h5>Made for Discord Hack Week ♥</b>
</div> 

# PotatoBot

Beep beep, boop beep?

**This bot is still under development and the source code is only for
demonstrations only and not for own use.**

## Description

Introducing, the first project by me made for one of famous youtube, @ItsAlexClark
Based on JDA (Java Discord API). This bot is made to tamper every problems made by
others bot. We couldn't rely on other bot since they have unstable uptime. Also this
bot was a part of the very first Discord Hack Week.

This bot main target is to made its first bot to produce the first Spotify, Apple Music,
Soundcloud and even your own file music player! To add more fun, we are going to implement
more commands and easter eggs.Also we have been thinking to add some sort of statistics and data analysis.

This bot however couldn't reach to its final development, but it doesn't
mean that this project could not be developed furthermore.

## Maintainers & Testers
- MrPotato101#0060 - [@larryTheCoder](https://github.com/larryTheCoder)
- Stykers#2614 - [@Stykers](https://github.com/stykers)
- Arumos#7101
- Illustrated#0698

## Installation

There is two way on installing this bot. With and without auto updater.

### Installing without AutoUpdater

First, make sure you have [Java 8](https://www.java.com/download) installing in your machine before running.

On this project root, run
```
mvn clean package
java -jar target/PotatoBot-1.0-SNAPSHOT.jar
```

### With an AutoUpdater

Create a folder named `PotatoBot` or whichever you like. Then create a folder named `BotRepository` in that directory. In there, you need to clone this git repository, build the packages with maven and then copy that jar from `target` folder into `PotatoBot` folder you have created earlier
```
mkdir PotatoBot
mkdir PotatoBot/BotRepository
cd PotatoBot/BotRepository

git clone https://github.com/larryTheCoder/PotatoBot.git
mvn clean package

cp "target/PotatoBot-1.0-SNAPSHOT.jar" "../PotatoBot-1.0-SNAPSHOT.jar"
cd ..
```

Once you done copying the files, grab some of the scripts from this git repo located in `data/`
Chose either `start.sh` if you are in linux, or `start.bat` if you are in windows

Run those scripts and walla, your bot is running wild in your host!

### Configuration

Once you have the bot running, there will be a config file named `bot.yml` in the bot folder. You must specify your bot token tokey to the bot in `token-key`. Otherwise you wont be able to connect to discord.


<div align="center">
    <img width=200 height=200 src="https://cdn.discordapp.com/attachments/514331305111191563/610795190881484813/unknown.png"/>
    <h5>Thank you for all of your support.</b>
    <h5>Kanna is Adorable UwU#9977 | Arumos#7101 | Illustrated#0698 | VelvetSpyder#1122 | general bread#2278 | TulaBula#9114</b>
    <h5>The Jedi Glutch of Breadios#0068 | jay_jay#1941 | 2Night#6683 | jasmine2380#5412 | Stykers#2614</b>
    <h5>And more, especially from Nukkit community.<b>
</div> 
