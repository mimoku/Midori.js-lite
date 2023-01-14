<p align="center">
  <img src="https://media.discordapp.net/attachments/1033604720570404874/1040123011187081226/500px-493Arceus.png" />
</p>
<h1 align="center">midori.js-lite</h1>


**The most powerful string package to create a discord bot with custom features having aoi.js features!**

**Thanks to the actual owner of Midori.js! Huge credits to him**


[Discord Server]([https://discord.gg/xPURT2B3sA](https://discord.gg/CHXQzQ6t))


* New features <br> <br>
* $ver [kiss] [handhold] [nom] [poke] [glomp] [waifu] [shinobu] [oppai] <br>
* $nsfw (function in docs) (i was forced to add) <br>
* Command handler (by using fs) <br>
* Aoi.js v5 support <br>
* Minor changes <br>



---



Install


```js
npm i midori.js-lite
```

---
* Setup

```js
const { AoiClient } = require("aoi.js");

const bot = new AoiClient({
    token: "DISCORD_BOT_TOKEN",
    intents: ["GUILDS", "GUILD_MESSAGES"],
    prefix: "DISCORD_BOT_PREFIX"
})


const { Plugins } = require("midori.js-lite"); 
const plugins = new Plugins({ bot:bot }); 
plugins.loadPlugins(); 


bot.onMessage()


bot.command({
  name : "meme",
  code : `$meme`
})
```

* Developers

<strong>ZeRealOne</strong>
<br>
<strong>ItsHyper</strong>
<br>
<strong>spook</strong>






