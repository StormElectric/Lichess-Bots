# Lichess-Bots
https://github.com/StormElectric/Lichess-Bots/actions/workflows/python-build.yml
# Using Languages
https://camo.githubusercontent.com/021b6ad53e86ce0d33efdeec1cd93ddb78236829f30453f1e662f3e3b6fb5644/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f2d507974686f6e2d3337373641423f6c6f676f3d707974686f6e266c6f676f436f6c6f723d666666666666 https://camo.githubusercontent.com/1141ebbf3636f578b0efb1086ff5564c4014e797eac87aad656be92b44a9224a/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f2d646f636b65722d3030353939433f6c6f676f3d646f636b6572253262253262266c6f676f436f6c6f723d666666666666

# Using softwares
https://camo.githubusercontent.com/3417f0072d9618128d8ce7106111f197baabca97d41c2203d36461cefdba6eb2/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f5653436f64652d2532333030374143433f6c6f676f3d56697375616c2d73747564696f2d636f6465 https://camo.githubusercontent.com/918bd391b91cde687c7475d823a85d7d7912a7fa3ea2ce93ef14e357875f5e7a/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f5079436861726d2d677265656e3f6c6f676f3d5079436861726d https://camo.githubusercontent.com/7d1d18f27004e1249004816298a686dd07d06fcf6a7b44e7a99377fa2ef18f92/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f2d4c696e75782d4643433632343f6c6f676f3d6c696e7578266c6f676f436f6c6f723d303030303030

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
