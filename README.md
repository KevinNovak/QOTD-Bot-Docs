# QOTD Bot

[![top.gg](https://top.gg/api/widget/status/713586207119900693.svg?noavatar=true)](https://top.gg/bot/713586207119900693)
[![top.gg](https://top.gg/api/widget/servers/713586207119900693.svg?noavatar=true)](https://top.gg/bot/713586207119900693)

**Discord bot** - Automatically posts a Question of the Day each day!

## [Add to your Discord Server!](https://discord.com/oauth2/authorize?client_id=713586207119900693&scope=bot%20applications.commands&permissions=51808267280)

[Join Support Server](https://discord.gg/JdeZ5PF) | [Donate with PayPal!](https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=EW389DYYSS4FC)

QOTD Bot helps keep your community active by automatically posting a Question of the Day each day in the questions channel!

![Example usage](https://i.imgur.com/ytjt4GH.png)

QOTD Bot comes with many built-in questions and the also the ability to add your own custom questions!

![Example conversion](https://i.imgur.com/wmnid88.png)

Customize what time questions are posted, how questions are chosen, who is allowed to add new questions, who can suggest new questions, and more!

### User Commands

-   **/help** - View help menu and list of commands.
-   **/default view [page]** - View built-in default questions.
-   **/custom view [page]** - View the server's custom questions.
-   **/queue view [page]** - View suggested custom questions.
-   **/queue suggest <question>** - Suggest a new custom question for the server.
-   **/settings** - View server settings.
-   **/premium info** - Information about QOTD Bot Premium.
-   **/premium subscribe** - Subscribe to QOTD Bot Premium.
-   **/info** - View bot info.

### Manager Commands

-   **/custom add [question]** - Add a new custom question for the server.
-   **/custom remove [question_number]** - Remove a custom question from the server.
-   **/default blacklist [question_number]** - Prevent a built-in default question from being asked.
-   **/default unblacklist [question_number]** - Remove a built-in default question from the blacklist.
-   **/queue approve [question_number]** - Approve a suggested custom question.
-   **/queue deny [question_number]** - Deny a suggested custom question.
-   **/test** - Post a test question.
-   **/post** - Force a question to be posted.

### Admin Commands

-   **/setup [type]** - Run server setup.
-   **/default reset** - Reset built-in default questions.

## References

-   [discord.js](https://discord.js.org/) - A powerful JavaScript library for interacting with the Discord API.
-   [Node Schedule](https://github.com/node-schedule/node-schedule) - A cron-like job scheduler for Node.
-   [Moment Timezone](https://momentjs.com/timezone/) - Parse and display dates in any time zone.
