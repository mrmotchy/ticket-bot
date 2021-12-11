![Logo](https://github.com/mrmotchy/stuff/blob/main/ticket-transparent-background-411627.png?raw=true)

<div align="center">
  
<br>![Windows](https://github.com/danielkrupinski/Osiris/workflows/Windows/badge.svg?branch=master&event=push)
[![Downloads](https://img.shields.io/github/downloads/jagrosh/MusicBot/total.svg)](https://discord.gg/9ZrzNkzeN4)
[![Discord](https://discordapp.com/api/guilds/147698382092238848/widget.png)](https://dsc.gg/dst74)<br>
[![PayPal](https://img.shields.io/badge/donate-PayPal-104098.svg?style=plastic&logo=PayPal)](https://paypal.me/mrmotchy)
  
  </div>
  
  # Features
  * **Watch my YT video & host your [bot 24/7](https://dsc.gg/dst74)**
  * Easy to run
  * nice & clean color roles bot


# 🔩 Installation
## Install [discord.js](https://discord.js.org/#/)
```
$ npm install discord.js
```

## Install [npm](https://www.npmjs.com)
```
$ npm install 
```

# 💻 Code example
This is a simple example of code using this package.

```js
if(command === settings.prefix + settings.rainbowcommand) {
        const rolez = message.mentions.roles.first() || message.guild.roles.find(r=> r.name === args [0])
        if(!rolez) return message.channel.send(settings.messageresponse.rolenotfound).catch(err=> message.channel.send("No response"))
        if(!message.guild.member(bot.user.id).hasPermission("MANAGE_ROLES")) return message.channel.send(settings.messageresponse.missingperm).catch(err=> message.channel.send("no response"))
        var colors = settings.rainbowrole
        var rolestart = setInterval(function() {
            var colorsz = colors[Math.floor(Math.random() * colors.length)];
            rolez.setColor(colorsz)
        }, settings.rainbowdelay); 
            message.channel.send(settings.messageresponse.success).catch(err=> message.channel.send("No response"))
```
&
```js
const Discord = require("discord.js") 
const settings = require("./settings.json")
const bot = new Discord.Client()
bot.on('ready', async => {
console.log("Rainbow bot is ready!" + "\n" + bot.user.tag + "\n" + "Server Count: "  + bot.guilds.size + "\n" + "Cached users: " + bot.users.size + "\n" + "Enjoy!")
});
```

<br/>



## Installation


 ### Click [here](https://www.youtube.com/channel/UCmkPzf-eAJsiuCh-5kz4Abw) to watch my YouTube video !
 ![](https://github.com/mrmotchy/stuff/blob/main/Bild_2021-06-14_181143.png?raw=true)


 ### Click [here](https://dsc.gg/dst74) to join my discord server !
 [![Setup](https://github.com/mrmotchy/stuff/blob/main/adada.gif?raw=true)](https://dsc.gg/dst74)

