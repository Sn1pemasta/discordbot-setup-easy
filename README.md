# Discord AI Bot with OpenAI GPT-4o-mini Integration

This is a simple Discord bot built using `discord.js` and the OpenAI API. The bot uses GPT-4o-mini for handling queries and providing helpful responses when pinged by users.

## Features

- The bot listens for messages in Discord channels.
- When the bot is pinged, it processes the message using the OpenAI GPT-4o-mini model.
- Replies with generated responses to user queries.
- It can be extended for more functionalities like role management, commands, and more.

## Requirements

Before running the bot, ensure you have the following installed:

- [Node.js](https://nodejs.org/)
- [Discord.js](https://discord.js.org/)
- OpenAI API key

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/discord-ai-bot.git
   cd discord-ai-bot
Install dependencies:

bash
Copy
Edit
npm install
Replace YOUR_DISCORD_TOKEN with your Discord bot token and YOUR_OPENAI_API_KEY with your OpenAI API key in the bot.js file.

Run the bot:

bash
Copy
Edit
node bot.js
Usage
Invite the bot to your server using your bot's invite link.
Mention the bot in a Discord channel to get a response.
Example of bot interaction:

User: @Bot what can you do?
Bot: I can help you with a wide range of topics! What would you like assistance with today?
Code Explanation
bot.js: The main bot file, containing the logic for connecting to the Discord API, listening to messages, and interacting with the OpenAI API.

getAiResponse function: This function queries OpenAI's GPT-4o-mini model and returns a response based on the user's input.

messageCreate event: The bot listens for messages and checks if it’s mentioned. If so, it processes the query using the AI.
