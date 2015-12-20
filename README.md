# Discord Chat Bot

A chat bot for Discord written in JavaScript. 

Notably cool because it has Wolfram Alpha built in as a chat command.

## Requirements
* node
* npm
* [Wolfram Alpha App ID](http://products.wolframalpha.com/developers/)
* [Discord](https://discordapp.com/) account for your bot
* Make sure the bot is in the channels you want it listening
* [nodemon](https://github.com/remy/nodemon) (recommended to keep bot running 24/7 + change detection)

## Installation
Install dependencies

    npm install

Rename config file
    
    mv config.example.js config.js

Fill in config file with your credentials

Run the bot (requires nodemon)

    npm start

Or without nodemon

    node bot.js

## Example Output

`!help`

    Things I can do:
    !help - Shows what I can do
    !question <your question> - Ask and you shall recieve
    !roll - Roll a number between 1-100
    !flip - Flip a coin
    !8ball - Ask the magic 8ball a question



`!question what is the capital city of Canada?`

    @nehero, Ottowa, Ontario, Canada

`!question what is 9 + 10`

    @nehero, 19

`!question what is the meaning of life * 10`

    @nehero, 420

## Credits

* [Discord-js](https://github.com/hydrabolt/discord.js)
* [node-wolfram](https://www.npmjs.com/package/node-wolfram)