# Lichess-Bots
[![Python Build](https://github.com/codingforhelp/Lichess-Bot/actions/workflows/python-build.yml/badge.svg)](https://github.com/StormElectric/Lichess-Bots/actions/workflows/python-build.yml)

## Using languages

![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=ffffff)
![Docker](https://img.shields.io/badge/-docker-00599C?logo=docker%2b%2b&logoColor=ffffff)


## Using Softwares

![VS Code](https://img.shields.io/badge/VSCode-%23007ACC?logo=Visual-studio-code)
![Pycharm](https://img.shields.io/badge/PyCharm-green?logo=PyCharm)
![Linux](https://img.shields.io/badge/-Linux-FCC624?logo=linux&logoColor=000000)

# Maintainers
[RoyalRacer_2](lichess.org/@/Royalracer_2) and [StormElectric](github.com/stormelectric)

# lichess-bot
A bridge between Lichess API and bots.
This bot is made with Python and it is running using stack container and is concentrated on heroku.

# Bot information
Playing Standard Chess and as well as all other variants
Playing Bullet to Classical
# How to setup?
Import or Fork this repository to your Github.
Open the config.yml file and insert your API access token in to token option and commit changes over here.
Install Heroku CLI and create a new app in Heroku.
Do note that in certain operating systems Heroku CLI doesn't get added to path automatically. If that's the case you'll have to add heroku to your path manually.
Run this command in cmd or powershell heroku stack:set container -a appname, where appname is replaced with your Heroku app's name.
In heroku, in the Deploy tab click on Connect to GitHub and then click on search and select your fork/import of this repository.
Now scroll down and under Manual deploy, click on deploy with the master branch selected.

Note: You could also Enable Automatic Deploys with the master branch selected if you would like each commit you make to get automatically and easily deployed onto your bot. It is your choice whether you'd like to Enable Automatic Deploys.
After deploying wait for about 5 minutes till the build finishes and then in the Resources tab in heroku turn worker dynos. If you do not see any option to enable any dynos, then you'll have to wait for about 5 minutes and then refresh your page on heroku.
You're now connected to lichess and awaiting challenges! Your bot is up and ready!

# How to use stockfish
Your **BOT** can play all variants and also standard but your bot is not playing **standard** very strong, if you want to make it stronger change the [6th line of config.yml](/config.yml#L6) to chess-engine then you'll have to wait 5 minutes, After 5 minutes your **BOT** is playing very strong but it will not play all other variants. If you want your bot to play all other variants once again, you can change the [6th line of config.yml](/config.yml#L6) to fsf or fairy-sf and then you'll have to wait 5 minutes.

# How to make the bot decline other BOT's challenges?
If you want other BOTS challenge your bot and you want to decline them, then you can the [96th line of config.yml](/config.yml#L96) from true to false and commit your changes and then you'll have to wait 5 minutes.
