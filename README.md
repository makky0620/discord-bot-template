# Discord Bot Template

A simple Discord bot template built with TypeScript and discord.js.

## Features

*   Responds to `!ping` with `Pong!`.
*   Easily extendable for more commands.
*   Uses `dotenv` for environment variable management.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

*   [Node.js](https://nodejs.org/) (v16.9.0 or newer)
*   A Discord Bot Token. You can get one from the [Discord Developer Portal](https://discord.com/developers/applications).

### Installation

1.  Clone the repository:
    ```sh
    git clone https://github.com/your-username/discord-bot-template.git
    cd discord-bot-template
    ```
2.  Install the dependencies:
    ```sh
    npm install
    ```
3.  Create a `.env` file in the root of the project and add your Discord bot token:
    ```
    DISCORD_TOKEN=your_bot_token_here
    ```

## Usage

### Development

To run the bot in development mode with hot-reloading, use:

```sh
npm run dev
```

### Production

1.  Build the TypeScript code:
    ```sh
    npm run build
    ```
2.  Start the bot:
    ```sh
    npm run start
    ```

## Commands

*   `!ping` - The bot will reply with `Pong!`.

## Dependencies

*   [discord.js](https://discord.js.org/): A powerful Node.js module for interacting with the Discord API.
*   [dotenv](https://github.com/motdotla/dotenv): A zero-dependency module that loads environment variables from a `.env` file.
*   [TypeScript](https://www.typescriptlang.org/): A typed superset of JavaScript that compiles to plain JavaScript.

## License

This project is licensed under the ISC License - see the `LICENSE` file for details.
