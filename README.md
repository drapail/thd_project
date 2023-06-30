# The Dungeons and Dragons bot

## General
This is a Dungeons and Dragons bot. He tells you the situation in which your charater is and waits for your action. You can fight, negotiate, hide or interact with an enemy in any other way. But be careful, depending on your choice, the encounter can end successfully or you can die!
If you want to end the game and see stats of how you played with the bot: simply type `quit` or some similar message.

## Local deployment
To start the bot locally, simply follow these steps:
1) Clone the repository
2) `cd` to `front` directory
3) Run `npm install --force` in terminal to download all dependencies
4) Run `npm run build` to build static frontend
5) Create `back/public` directory and move all what is inside the `front/build` into it
6) `cd` to the root and run `back/server.js`
7) The bot is running and you can play with him, you are breathtaking :grin:
