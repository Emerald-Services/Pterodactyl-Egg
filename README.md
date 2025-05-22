# Pterodactyl Egg for SupportBot by EmeraldSRV

This repository contains a Pterodactyl egg for deploying [SupportBot](https://github.com/Emerald-Services/SupportBot) on your Pterodactyl panel.

## What is SupportBot?

SupportBot is an Open-Source discord bot built with [discord.js](https://github.com/discordjs/discord.js). It's primarily focused to help servers organise and manage their support system in a unique way with full customisation to match your brand.

## Features of this Egg

*   **Simple Deployment:** Easily deploy SupportBot with minimal configuration.
*   **Automatic Dependency Installation:**  The egg automatically installs all required dependencies.
*   **Configuration File Management:** Includes a basic configuration file with placeholders for your Discord bot token, and other essential settings.
*   **Automatic Start-up:** Ensures SupportBot starts automatically after deployment.

## Requirements

*   A Pterodactyl panel running version 1.0 or higher.
*   A Discord bot token.
*   Node.js version 20 or higher installed on your Pterodactyl server node.
*   Sufficient resources allocated to the server (RAM, CPU, Disk Space).  The recommended resource allocation will depend on the size and activity of your Discord server.  Start with a minimum of 512MB RAM and 1 vCPU.

## Installation

1.  **Download the Egg:**  Download the `egg-support-bot.json` file from this repository.
2.  **Import the Egg:**
    *   Log in to your Pterodactyl panel as an administrator.
    *   Navigate to "Nests" and select the nest you want to add the SupportBot egg to (e.g., "Discord Bots").
    *   Click "Import Egg" and upload the `egg-support-bot.json` file.
3.  **Create a Server:**
    *   Create a new server within the nest you imported the egg into.
    *   Select the "SupportBot" egg.
    *   Configure the server settings according to your needs (RAM, CPU, Disk Space, etc.).
4.  **Configure the Startup Command:** (Optional, but recommended)
    *   On the Server Settings page, make sure the "Startup Command" is set to the standard command. This command tells the server how to start your bot.
5.  **Install the Bot:**
    *   Start the server.  This will automatically install the necessary dependencies.
    *   Check the server console for any errors.
6.  **Configure the Bot:**
    *   Access the server's file manager.
    *   Edit the `Configs\supportboy.yml` file.  **This is crucial!**
    *   Replace the placeholders with your Discord bot token, prefix, and other relevant settings.
    *   **Save the configuration file.**
7.  **Start the Bot:**
    *   Restart the server.  This will start your SupportBot.
    *   Invite your bot to your Discord server using the appropriate bot invite link.  (You can find information on generating invite links on the Discord Developer Portal.)

## Documentation

You can find the documentation of the bot [here](https://docs.emeraldsrv.com/bots/supportbot/configuration)
