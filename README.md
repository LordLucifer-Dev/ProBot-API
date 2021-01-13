# ProBot-API

**This Is Not The Official API, We Are Not Affiliated With ProBot Team By Any Mean**
- Please Use This Package If Your A Pro Proggramer.
- This Package Is Under MIT License.
- You Should Know That If Probot Team Asked To Shutdown The API,We Will

`Using This API With Your Own Rsponsibility`


## How Do I Get Probot Access Token?
To Get Probot Access Token Simply 

1 - Go To https://probot.io/dashboard
![](https://cdn.discordapp.com/attachments/795472250160939042/798818745455083550/download_1.png)

2 - Press ctrl + shift + i
![](https://cdn.discordapp.com/attachments/795472250160939042/798819000423415858/unknown.png)

3 - Click console
![](https://cdn.discordapp.com/attachments/795472250160939042/798819252961542154/unknown.png)

4 - Copy + Paste This In Console
`localStorage.ac`
And `Enter`
![](https://cdn.discordapp.com/attachments/795472250160939042/798819768102551572/unknown.png)

4 - Copy Your Acces Token And Paste It

## Why Do It Says Invaild Access Token?
Probot Changes Access Token  Every Time You Close Browser So You Have To Keep Browser Open Or Use RDP And Login, Get Access Token And Keep RDP Open.

# Examples 


#### Get Probot Stats [ No Need To Access Token]
```js
const API = require('probot-api');
const probot = new API({ token : "Yor Acces Token"});

probot.getStats() // {"guilds":1236218,"db_users":36289723,"members":113823218}
```
#### Get Your Probot  Stats [ Require Access Token]
```js
const API = require('probot-api');
const probot = new API({ token : "Yor Acces Token"});

probot.getMyStats() // https://pastebin.pl/view/a3eaa544
```
#### Get Guild Daily  Stats [ Require Access Token + Guild Permissions   ]
```js
const API = require('probot-api');
const probot = new API({ token : "Yor Acces Token"});

probot.getDailyStats('GUILD_ID') //{"messages":"15","joined":"2","members":"132","left":"1"}
```
#### Get Probot Top Credits   [ No Need Access Token  ]
```js
const API = require('probot-api');
const probot = new API({ token : "Yor Acces Token"});

probot.getTopCredits() // https://pastebin.pl/view/3c7cab86
```
#### Get Probot Top Xp   [ No Need Access   Token  ]
```js
const API = require('probot-api');
const probot = new API({ token : "Yor Acces Token"});

probot.getTopXp() // https://pastebin.pl/view/1bcf4f75
```
#### Get Guild Data [ Require Access  Token + Guild Perrm ]
```js
const API = require('probot-api');
const probot = new API({ token : "Yor Acces Token"});

probot.getGuildData('GUILD_ID') // https://pastebin.ubuntu.com/p/tT6ZfdJFxN/
```
