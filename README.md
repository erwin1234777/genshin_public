# Genshin Utilities Bot(GenshinUtils)

This bot is made using Typescript, using discord.js library.

It is a Genshin oriented bot aimed to help travelers in their journeys.
This bot is Safe For Work.

# Add this bot to your server! 
Simply click [HERE](https://discord.com/oauth2/authorize?client_id=773585165317570610&permissions=2081778770&redirect_uri=https%3A%2F%2Fdiscord.gg%2F6QEExsN&scope=bot&response_type=code) to add it.

[![Discord Shield](https://discordapp.com/api/guilds/628731905423966219/widget.png?style=shield)](https://discord.gg/6QEExsN)

#### Features:
- Daily customizable reminders(so you know what to farm each day)
- Gacha tracker(so you never again have to count your history of wishes to see when next 5* is coming)[Click here for more](https://github.com/erwin1234777/genshin_public/blob/main/README.md#gacha-tracker-visual-tutorial)
- Community guides and tips about specific farming places/methods

#### Incoming features: 
- Farming maps
- Ticket system
- Feedback system
### Need support? 
Click [HERE](https://discord.gg/6QEExsN)

#### This bot stores the following data: 
- The guild ID for moderation log purposes to prevent api abuse(constantly kicking/adding bot)
- User ID (only when the user subscribes to reminders, including the options they chose to be reminded)
- Channel ID (used for enabling a specific channel to allow reminder messages to be sent in)

Simply dm the author Not Erwin#8753 if you request data deletion

#### Default prefix is `g.` , though it can be changed in the g.settings configs

## Discord Commands
| Command | Arguments| Description                    | Example |
| --------|----------|--------------------------------|---------|
| `g.gacha`| [Blank] | Wishes tracker for your wishes in genshin. More info at the end of the page [HERE](https://github.com/erwin1234777/genshin_public/blob/main/README.md#gacha-tracker-visual-tutorial) |g.gacha|
| `g.help`| [Blank] | Provides a link to this page |g.help|
| `g.invite`| [Blank] | Sends an embed containing the invite for the bot, with a redirect to the support page |g.invite|
| `g.reload`| [Blank] | NOT PUBLIC, used to reload the cache of the bot(for quick maintenece) |g.reload|
| `g.reminders`| [Blank] | WIP, selector for the reminders you wish to be reminded of |g.reminders|
| `g.settings`| [Blank] | Brings all current settings for your guild(permissions may be required) |g.settings|
| `g.settings prefix`| [Blank] | Bring all info about the current prefix in the guild |g.settings prefix !|
| `g.settings prefix set/change`| [prefix(max 3 characters)] | Changes the prefix for the whole guild |g.settings prefix set !|
| `g.settings reminders enable`| [Blank] | Enables reminders messages to be sent on the guild |g.settings reminders enable|
| `g.settings reminders disable`| [Blank] | Disables reminders messages to be sent on the guild |g.gacha|
| `g.settings reminders output`| [#channel-name] | Forces messages from the reminders to be sent to a specific channel |g.settings reminders output #general|
| `g.sub`| [Blank] | Enable reminders to be sent when you start genshin(once a day, resets at UTC-8, Genshin daily reset for: 天空岛, 世界树 ,TW, HK, MO , Asia) |g.sub|
| `g.test`| [Blank] | WIP, current placeholder for command g.reminders |g.test|
| `g.unsub`| [Blank] | Disable reminders to be sent when you start genshin |g.gacha|

# Gacha Tracker visual tutorial

Requirements: 
- Ensure that the bot is on the server you plan to use it on

## First Time setup
Head over to Discord, and type g.gacha, a message should appear with 3 buttons, each containing a different reaction/icon

<img src="https://i.imgur.com/CKvH41p.png" width="320">

After that is done, head over to Genshin, you'll need to repeat this process 3 times, one for each banner.
Once inside genshin, click on the wishes tab.

<img src="https://i.imgur.com/fFOPLwR.png" width="320">

Now you are going to start with any banner, for this tutorial purposes, we'll be using the standard banner(permanent wishes)

<img src="https://i.imgur.com/bVRBCUa.png" width="680">

Once you have selected the banner, head over to discord and click on the corresponding banner you are in(in this case, the standard banner)

<img src="https://i.imgur.com/pjyUthw.png" width="320">

After the message changes, click the 1234 button on the most right position

<img src="https://i.imgur.com/l7cZEXK.png" width="320">

This will start a collector, so be careful, its listening to the next message in chat. Now, dont type anything in chat until we are done, okay?
Next you'll head back to genshin, this time, ON THE SAME BANNER YOU WERE< click on HISTORY, on the bottom left corner of your wishes screen(ensure you are on the same banner)

<img src="https://i.imgur.com/sbr7jkd.png" width="680">

Now will be the part where you will have to be careful, this step is important so take your time.
The button you clicked on discord is expecting an input containing the total wishes you done(which isnt necessary, if you want to count your total amount of wishes, its up to you, i would recommend you put 0), the 4* star streak and 5* star streak you have, i'll give you more detailed information.
First, find your latest 4* star you got, it doesnt matter if its a character or weapon.
Now that you found it, we are going to count them until the last wish you made. ALWAYS start counting the 4* itself as 0, the one above as 1, the next 2, 3 and so on, just remember to start counting AFTER the wish(aka, start counting the 4* itself as 0) as seen in the example below

<img src="https://i.imgur.com/kFlnOrf.png" width="800">

Remember that 4* cannot have a streak higher than 9(you can only have 9 between 4* streaks, as the 10th is guaranteed another 4* star).
Now that you have that number, you are going to write it down.
Repeat the same process for the 5*, find the LATEST 5* star you got(or if you didnt get any, start from as far as it goes). Now that you counted BOTH 4* star and 5* star, we are ready to go back to discord.
The command should still be waiting for your next message, so now we are going to finish it up.
Type this : 0, YOUR 4* STAR streak here, YOUR 5* STAR streak here
It should look like this `0,7,12` for example, separated by commas
Thats it, now do the same for the other 2 banners. This is only needed once to get you started.

## Already Setup or Fresh Accounts
Now that you have your banners setup, your task is simple
Go to genshin.
Get on the Wishes Page
Select what banner you will be getting wishes from
Head over to discord, type g.gacha
Click the same button for the banner you are pulling wishes from
Roll a wish on genshin, wait for it to finish so you know what you got
AFTER YOU KNOW WHAT YOU GOT, react correspondingly to what you got. 
If you got a 3* Star, react with white
If you got a 4* Star, react with purple
If you got a 5* Star, reac with orange

<img src="https://i.imgur.com/8W2e4Jy.png" width="320">

