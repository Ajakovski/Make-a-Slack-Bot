# Make-a-Slack-Bot
# ***Smartio***
This bot isn't slacking off — it replies to commands 24/7!

# channel where you can test it out!!
https://hackclub.enterprise.slack.com/archives/C0BSYLSSPQQ

## Commands

| Command                 | Description                                                   |
| ----------------------- | ------------------------------------------------------------- |
| `/smartio-ping`         | Replies with `Pong!`.                                         |
| `/smartio-help`         | Shows available commands                                      |
| `/smartio-catfact`      | Sends an interesting cat fact!                                |

> [!NOTE]
> followed the official guide on how to finish te project

## What I learned from this project:
I learned a lot about what API's are and how they work, ssh servers, and hosting code, and backend systems. I learned to build a slack bot using node.js and slack bolt, work with external API's and async request handling, connect multiple services together (slack, external API's) and even deploy and host backend code on remote servers using ssh

### if you want to run your own version

clone the repository:
git clone https://github.com/Ajakovski/Make-a-Slack-Bot

cd https://github.com/Ajakovski/Make-a-Slack-Bot

npm install

set environment variables (create a .env file):

SLACK_BOT_TOKEN=your_token

SLACK_APP_TOKEN=your_token

run the bot:
  node index.js
