![Typing SVG](https://readme-typing-svg.herokuapp.com/?lines=Welcome+To+Doctor-Strange!;Created+by+𝐂𝐫𝐚𝐳𝐲𝐃𝐞𝐯𝐞𝐥𝐨𝐩𝐞𝐫ᠰ𝐓𝐆!;A+simple+and+powerful+Bot!;Indexes+Files+above+2GB;A+Bot+with+double+button!;Start+message+with+pic!;And+more+features!)
</p>
<p align="center">
  <img src="https://telegra.ph/file/77283bdd7509ba368a43f.jpg" alt="Strange">
</p>
<h1 align="center">
  <b>Doctor-Strange</b>
</h1>

<a href="https://t.me/czdbotz_support">
  <img src="https://img.shields.io/badge/Join-blue?logo=telegram" width="70">

[![Stars](https://img.shields.io/github/stars/CrazyDeveloperTG/Doctor-Strange?style=flat-square&color=yellow)](https://github.com/CrazyDeveloperTG/Doctor-Strange/stargazers)
[![Forks](https://img.shields.io/github/forks/CrazyDeveloperTG/Doctor-Strange?style=flat-square&color=orange)](https://github.com/CrazyDeveloperTG/Doctor-Strange/fork)
[![Size](https://img.shields.io/github/repo-size/CrazyDeveloperTG/Doctor-Strange?style=flat-square&color=green)](https://github.com/CrazyDeveloperTG/Doctor-Strange)   
[![Open Source Love svg2](https://badges.frapsoft.com/os/v2/open-source.svg?v=103)](https://github.com/CrazyDeveloperTG/Doctor-Strange)   
[![Contributors](https://img.shields.io/github/contributors/CrazyDeveloperTG/Doctor-Strange?style=flat-square&color=green)](https://github.com/CrazyDeveloperTG/Doctor-Strange/graphs/contributors)
[![License](https://img.shields.io/badge/License-AGPL-blue)](https://github.com/CrazyDeveloperTG/Doctor-Strange/blob/main/LICENSE)
[![Sparkline](https://stars.medv.io/CrazyDeveloperTG/Doctor-Strange.svg)](https://stars.medv.io/CrazyDeveloperTG/Doctor-Strange)
## Features

- [x] Auto Filter
- [x] Manual Filter
- [x] IMDB
- [x] Admin Commands
- [x] Broadcast
- [x] Index
- [x] IMDB search
- [x] Inline Search
- [x] Random pics
- [x] ids and User info 
- [x] Stats, Users, Chats
- [x] Spelling Check Feature
- [x] File Store
- [x] PM & Channel 
- [x] Auto delete
- [x] 2GB+File Support
- [x] song video download
- [x] gfilter
- [x] group broadcast
- [x] telegraph
- [x] games
- [x] ping
- [x] pdf convert to voice
- [x] font
- [x] translate
- [x] PreDVD and CamRip Delete Mode
- [x] Multiple File Deletion

## Variables

### Required Variables
* `BOT_TOKEN`: Create a bot using [@BotFather](https://telegram.dog/BotFather), and get the Telegram API token.
* `API_ID`: Get this value from [telegram.org](https://my.telegram.org/apps)
* `API_HASH`: Get this value from [telegram.org](https://my.telegram.org/apps)
* `CHANNELS`: Username or ID of channel or group. Separate multiple IDs by space
* `ADMINS`: Username or ID of Admin. Separate multiple Admins by space
* `DATABASE_URI`: [mongoDB](https://www.mongodb.com) URI. Get this value from [mongoDB](https://www.mongodb.com).
* `DATABASE_NAME`: Name of the database in [mongoDB](https://www.mongodb.com). For more help watch this 
* `LOG_CHANNEL` : A channel to log the activities of bot. Make sure bot is an admin in the channel.
* `SUPPORT_CHAT` : @czdbotz_support
* `PICS`: Telegraph links of images to show in start message.( Multiple images can be used seperated by space )
* `FILE_CHANNEL` : File redirect to channel
* `DELETE_CHANNELS` : you can delete multiple files by forwarding those files into a private channel. Firstly make a private channel, add your bot as admin, add that channel's ID as a variable named DELETE_CHANNELS and forward the files to that private channel and the bot will delete those files from its database. You can check logs to confirm whether the file is deleted from the bot's database or not.
### Optional Variables

## Credits
<details>

 Thanks To [Mahesh](https://github.com/Mahesh0253/Media-Search-bot) MediaSearch

 Thanks To [Subinps](https://github.com/subinps/Media-Search-bot) AutoFilter & Base repo
 
 Thanks To [Joelkb](https://github.com/Joelkb) Collaborator [Add Redirect feature,Error fixed, Add new features]


</details>

## Deploy
You can deploy this bot anywhere.


<details><summary>Deploy To Heroku</summary>
<br>
<p>
<a href="https://heroku.com/deploy?template=https://github.com/CrazyDeveloperTG/Doctor-Strange">
  <img src="https://www.herokucdn.com/deploy/button.svg" alt="Deploy">
</a>
</p></details>

<details><summary>Deploy To Koyeb</summary>
<br>
<p>
<a href="https://app.koyeb.com/deploy?type=git&repository=github.com/CrazyDeveloperTG/Doctor-Strange&env[BOT_TOKEN]&env[API_ID]&env[API_HASH]&env[CHANNELS]&env[ADMINS]&env[PICS]&env[LOG_CHANNEL]&env[AUTH_CHANNEL]&env[CUSTOM_FILE_CAPTION]&env[DATABASE_URI]&env[DATABASE_NAME]&env[COLLECTION_NAME]=Telegram_files&env[FILE_CHANNEL]=-1001832732995&env[SUPPORT_CHAT]&env[IMDB]=False&env[IMDB_TEMPLATE]&env[SINGLE_BUTTON]=True&env[AUTH_GROUPS]&env[P_TTI_SHOW_OFF]=True&branch=main&name=doctor-strainge">
 <img src="https://www.koyeb.com/static/images/deploy/button.svg">
</p>
</details>
<details><summary> Deploy To Okteto </summary>
<br>
<p>
<a href="https://cloud.okteto.com/deploy?repository=https://github.com/CrazyDeveloperTG/Doctor-Strange&branch=main">
  <img src="https://okteto.com/develop-okteto.svg" alt="Develop on Okteto">
</a>
</p>
</details>
<details><summary>Deploy To VPS</summary>
<p>
<pre>
git clone https://github.com/CrazyDeveloperTG/Doctor-Strange
# Install Packages
pip3 install -U -r requirements.txt
Edit info.py with variables as given below then run bot
python3 bot.py
</pre>
</p>
</details>

## Commands

```
* /logs - to get the rescent errors
* /stats - to get status of files in db.
* /filter - add manual filters
* /filters - view filters
* /connect - connect to PM.
* /disconnect - disconnect from PM
* /del - delete a filter
* /delall - delete all filters
* /deleteall - delete all index(autofilter)
* /delete - delete a specific file from index.
* /info - get user info
* /id - get tg ids.* /imdb - fetch info from imdb.
* /users - to get list of my users and ids.
* /chats - to get list of the my chats and ids* /broadcast - to broadcast a message to all Elsa users
* /gfilter - group filter
* /grp_broadcast - broadcast to all group
* /song - get song
* /video - get video
* /setskip - used in index where indexing a specific number
* /font - fonts for your text
```
<b> 😇CREATOR » [AFSAL](https://t.me/AFxSU)</b>

<p align="center">
<img src="https://github-readme-stats.vercel.app/api?username=CrazyDeveloperTG&theme=highcontrast" align="center">
<img src="https://github-readme-streak-stats.herokuapp.com?user=CrazyDeveloperTG&theme=tokyonight" align="center">
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=CrazyDeveloperTG&layout=compact&theme=tokyonight" align="center">
    <a href="https://www.python.org" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="20" height="20"/> </a>
    <a href="https://www.w3.org/html/" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="20" height="20"/> </a>
    <a href="https://www.w3schools.com/cpp/" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" alt="cplusplus" width="20" height="20"/> </a>
    <a href="https://nodejs.org" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="nodejs" width="20" height="20"/> </a> 
    <a href="https://golang.org/" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/go/go-original.svg" alt="Go" width="20px" height="20" /></a>
    <a href="https://www.w3schools.com/js/" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="JavaScript" width="20px" height="20" /></a>
</p>
