# IMPORANT
An updated version of this is avaliable [here](https://github.com/foobball/HyVerify) and a hosted version can be found at [https://bonk.ml](https://bonk.ml)

# HyVerify
This code is very awful as I wrote it in about 2 days. I never bothered to fix it because I'm not able to verify the bot through Discord's new process. This code is being held together by literal glue, I don't know how it works AAAAAAAAAAAAAAAAAAAAA.

HyVerify is a Discord bot that gives a user a role and changes their nickname when they link their Discord and Hypixel accounts. This is based off of SkyblockZ's verification bot, which basically does the same thing.

The recommended permissions should be No `Change nickname` permission to prevent bypassing the bot's set nickname.
Also you should move the role `HyVerifed` to the top of your role list, so that it is able to change the nicknames of the members who use it.

# Setting up the bot

Setting up the bot is really simple:

    1.) Run `npm install` to install all dependencies
    2.) Start the bot with `npm start` after supplying a proper __creds.json__ file (format can be found in the top of `app.js` and in `creds.example.json`) and create a file called `roles.json` in the `db` folder.

# Commands

The prefix for the bot is by default `v!`. This can be changed by editing the `prefix` constant in the top of app.js.

| Command | What it does |
| ------------- | ------------- |
| v!help  | Displays this list as a rich embed  |
| v!verify [Username]  | Checks to see if that Hypixel user's Discord matches the command executor's tag. Gives the `Hypixel Verified` role and Hypixel server rank, and changes nickname to username. |
| v!unverify | Removes the `Hypixel Verified` role and resets the user's nickname. |
| v!invite | Gives you a link to invite the bot to your own server. |
| v!donate | Gives you a link to donate to me |
