# LOTR Bot
A fork of York's amazing [GuideBot](https://github.com/An-Idiots-Guide/guidebot) designed specifically for the LOTR server owner community. I used the GuideBot as a base to build off of, but many features were added to benefit LOTR server owners.

I am hosting the official version of this bot, which can be invited to your server via [this link](https://discordapp.com/api/oauth2/authorize?client_id=384037879304814613&permissions=268692502&scope=bot)

## Requirements

- `git` command line ([Windows](https://git-scm.com/download/win)|[Linux](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)|[MacOS](https://git-scm.com/download/mac)) installed
- `node` [Version 8.0.0 or higher](https://nodejs.org)
- `MySQL or equivalent` [MySQL](https://www.mysql.com/downloads/) | [MariaDB](https://mariadb.org/download/)

You also need your bot's token. This is obtained by creating an application in
the Developer section of discordapp.com. Check the [first section of this page](https://anidiots.guide/getting-started/the-long-version.html)
for more info.

## Downloading

In a command prompt in your projects folder (wherever that may be) run the following:

`git clone https://github.com/ToTheFarWest/LOTRBot.git`

Once finished:

- In the folder from where you ran the git command, run `cd LOTRBot` and then run `npm install`
- Rename or copy `config.js.example` to `config.js`
- Edit `config.js` and fill in all the relevant details as indicated in the file's comments.

## Setting up the MySQL server
The bot does most of the work for you, but you do need to create the initial server. Here are the official guides to install [MySQL](https://dev.mysql.com/doc/refman/5.7/en/installing.html) or [MariaDB](https://mariadb.com/kb/en/library/binary-packages/)

## Starting the bot

To start the bot, in the command prompt, run the following command:
`node index.js`

## Inviting to a guild

To add the bot to your guild, you have to get an oauth link for it.

You can use this site to help you generate a full OAuth Link, which includes a calculator for the permissions:
[https://finitereality.github.io/permissions-calculator/?v=0](https://finitereality.github.io/permissions-calculator/?v=0)
