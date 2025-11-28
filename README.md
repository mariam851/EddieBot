# EddieBot

The official **EddieBot** for the EddieHub [Discord server](https://discord.eddiehub.org).  
Join our community today! 

<a href="https://gitpod.io/#https://github.com/EddieHubCommunity/EddieBot" target="_blank">
  <img src="https://gitpod.io/button/open-in-gitpod.svg" alt="Open EddieBot in Gitpod">
</a>

---

## Overview

EddieBot helps maintain an inclusive, welcoming environment by analyzing member messages for inclusive and positive language.  
It is fully open source and maintained by the community.

---

## Features

- Detects non-inclusive language in messages  
- Sends friendly reminders to encourage inclusive communication  
- Configurable responses and behavior  
- Easy to deploy and run on your own server  
- **“Edit this page”** button for documentation contributors (new feature)  

![Eddie bit warning](https://user-images.githubusercontent.com/624760/200577618-af25764f-a9ce-4ce8-a1f2-f8808c682c77.png)

---

## Config / Secrets (Environment Variables)

Below are the required environment variables. **Do not commit real secrets to GitHub!**  
For local development, copy these into a `.env` file or use your preferred secret manager.

Required: Discord API token

DISCORD_TOKEN=YOUR_DISCORD_BOT_TOKEN

Required: MongoDB URL connection string

EDDIEBOT_MONGO_CONNECTION_STRING=YOUR_MONGO_CONNECTION_STRING

Optional: debug webhook

DEBUG_HOOK=YOUR_DEBUG_HOOK

Required: Discord server ID

HOME_GUILD="699608417039286293"

Optional: Node environment

NODE_ENV="development"

Required: channel ID for logs

ADMIN_CHANNEL=YOUR_ADMIN_CHANNEL_ID



---

## Installation & Setup

1. Fork the repository.  
2. Clone your fork:

```bash
# SSH
git clone git@github.com:EddieHubCommunity/EddieBot.git

# HTTPS
git clone https://github.com/EddieHubCommunity/EddieBot.git

# GitHub CLI
gh repo clone EddieHubCommunity/EddieBot
