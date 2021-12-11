![Logo](https://www.seekpng.com/png/full/270-2700588_vip-tickets-for-trixie-delight-u0026-starship-vip.png)

<div align="center">
  
<br>![Windows](https://github.com/danielkrupinski/Osiris/workflows/Windows/badge.svg?branch=master&event=push)
[![Downloads](https://img.shields.io/github/downloads/jagrosh/MusicBot/total.svg)](https://discord.gg/9ZrzNkzeN4)
[![Discord](https://discordapp.com/api/guilds/147698382092238848/widget.png)](https://dsc.gg/dst74)<br>
[![PayPal](https://img.shields.io/badge/donate-PayPal-104098.svg?style=plastic&logo=PayPal)](https://paypal.me/mrmotchy)
  
  </div>
  
  # Features
  * **Watch my YT video & host your [bot 24/7](https://dsc.gg/dst74)**
- Setup 
- Open 
- Close
- Add
- Remove
- Rename
- Close
- Reopen
- Per Server Prefix 
- Ping Command

# 💎 Preview
## This it what the bot looks like...
![](https://github.com/mrmotchy/stuff/blob/main/Unben55555555555555annt.PNG?raw=true)

![](https://github.com/mrmotchy/stuff/blob/main/Unben6666666666annt.PNG?raw=true)

# 🔩 Installation
## Create [TOKEN](https://discord.com/developers/)
```
$ under bot_token
```

## Create [prefix]()
```
$ server prefixes could be -; +; !; ?;...
```

# 💻 Code example
This is a simple example of code using this package.

```js
            id: require('quick.db').fetch(`TicketAdminRole_${message.guild.id}`),
            allow: ["SEND_MESSAGES", "VIEW_CHANNEL"]
        }, {
            id: message.guild.roles.everyone,
            deny: ["VIEW_CHANNEL"]
        }]).then(() => {
            message.channel.send({
                embed: {
                    title: '✅ | Done',
                    description: `${txt} has been added to this ticket`,
                    color: 0x00D700
                }
            }).then(async function(msg) {
                setTimeout(() => {
                    msg.delete().catch(err => { return })
                }, 1000 * 7);
```
&
```js
                const embed2 = new Discord.MessageEmbed()
                .setTitle(`Premium Ticket Commands`)
                .setThumbnail(message.guild.iconURL({ dynamic: true }))
                .setDescription(`**__Here Are My Commands:__**\n\`setup,\` \`transcript,\` \`rename,\` \`remove,\` \`ping,\` \`open,\` \`close\``)
                .setColor(`#0x2F3136`)
```

<br/>



## Installation


 ### Click [here](https://www.youtube.com/channel/UCmkPzf-eAJsiuCh-5kz4Abw) to watch my YouTube video !
 ![](https://github.com/mrmotchy/stuff/blob/main/Bild_2021-06-14_181143.png?raw=true)


 ### Click [here](https://dsc.gg/dst74) to join my discord server !
 [![Setup](https://github.com/mrmotchy/stuff/blob/main/adada.gif?raw=true)](https://dsc.gg/dst74)

