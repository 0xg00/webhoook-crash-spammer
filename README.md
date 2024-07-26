# Discord Webhook Spammer

A simple script to send repeated spam messages to a specified Discord webhook URL.

## Description

This script repeatedly sends a set of predefined spam messages to a Discord webhook URL. The messages include text and images embedded in Discord's rich embeds. The script runs indefinitely until stopped manually.

## Features

- Sends spam messages to a specified Discord webhook.
- Includes embedded images and formatted text.
- Runs indefinitely until manually stopped.

## Requirements

- Node.js
- `node-fetch` package

## Installation

1. Clone the repository:

    ```sh
    git clone https://github.com/0xg00/webhoook-crash-spammer.git
    ```

2. Navigate to the project directory:

    ```sh
    cd discord-webhook-spammer
    ```

3. Install the required packages:

    ```sh
    npm install node-fetch
    ```

## Usage

1. Update the `webhookUrl` variable in the script with your Discord webhook URL.

    ```js
    const webhookUrl = 'your-webhook';
    ```

2. Run the script:

    ```sh
    node spammer.js
    ```
