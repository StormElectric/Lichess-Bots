# Lichess-Bots
Python Build Passing
# Using Languages
Python and Dockerfile

# Using softwares
VS Code, Pycharm and Linux

# Maintainers
[RoyalRacer_2](lichess.org/@/Royalracer_2) and [StormElectric](github.com/stormelectric)

# lichess-bot
A bridge between Lichess API and bots.
This bot is made with Python and it is running using stack container and is concentrated on heroku.

# How to setup?
Import or Fork this repository to your Github.
Open the config.yml file and insert your API access token in to token option and commit changes over here.
Install Heroku CLI and create a new app in Heroku.
Do note that in certain operating systems Heroku CLI doesn't get added to path automatically. If that's the case you'll have to add heroku to your path manually.
Run this command in cmd or powershell heroku stack:set container -a appname, where appname is replaced with your Heroku app's name.
In heroku, in the Deploy tab click on Connect to GitHub and then click on search and select your fork/import of this repository.
Now scroll down and under Manual deploy, click on deploy with the master branch selected.

Note: You could also Enable Automatic Deploys with the master branch selected if you would like each commit you make to get automatically and easily deployed onto your bot. It is your choice whether you'd like to Enable or Disable Automatic Deploys.
After deploying wait for about 5 minutes till the build finishes and then in the Resources tab in heroku turn worker dynos. If you do not see any option to enable any dynos, then you'll have to wait for about 5 minutes and then refresh your page on heroku.
You're now connected to lichess and awaiting challenges! Your bot is up and ready!
