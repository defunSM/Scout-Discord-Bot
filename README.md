## Epic Scout Discord Bot

### Problem Statement

I am busy and don't want to check when a free epic game is available and don't want to log in or go to the site to see what the free game is (I know I am lazy). However I am consistently on discord so I can get a reminder from the bot whenever there is a free game so I don't miss out no one likes (FOMO). 

The main usage of this discord bot is to remind/display what free game is available on epic games each week.

The approach will be to scrape the game image and display it along with the game name in the discord at the start of the week. Along with later features that can add to the functionally of the bot perhaps it can list free games from steam and other sites too?

#### Possible features

1. Setting the time of periodic reminders.

2. Include an option to react with thumbs up if already gotten the game so that it doesn't keep repeating.

### Setup

1. Clone the repo into your work environment.
2. Install the dependencies from the package.json by running the following command. (Make sure npm is installed)

``` bash
npm install
```
3. Create a .env file in the main working directory with the following:

``` bash
DISCORD_BOT_TOKEN=discord-bot-secret-key
CLIENT_ID=client-id-key
GUILD_ID=server-id-you-want-to-run-the-bot-in
```
4. Run the command to start the discord bot.

```
npm start
```

