# Blockland Discord Bridge
This is a Discord bridge for Blockland that allows the players in a server to communicate with Discord, and vice versa.

See also: [Brikkit Discord Bridge](https://github.com/LakeYS/Brikkit-Discord-Bridge) - A Discord bridge for Brickadia.

# Setup
Detailed setup instructions coming soon.

The bridge is separated into two parts: the in-game portion that reads messages, and an external application that connects to the game and communicates with Discord. This is necessary due to Blockland's lack of modern networking functions to use Discord's API. The application requires [Node.js](https://nodejs.org/en/download/) in order to run. It can run natively on both Windows and Linux.

In order to start the bot, the settings.json must be filled out with a Discord bot token, a Discord channel ID, and at least one moderator role name. The applicaton can be started by running the command `node main.js` in a terminal or batch/shell file within the application folder.
