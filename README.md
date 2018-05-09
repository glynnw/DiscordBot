# Discord Bot

> self-hosted modular bot

This project's goal is to make a full featured, modular, self-hosted bot in javascript.

## Getting up and running
1. Clone this repo
2. `npm install`
3. Create a `.env` file with:
```
TOKEN=<Bot Token>
OWNER_ID=<Bot owner id>
```
4. `npm start`

## Contributing

Read [CONTRIBUTING.md](CONTRIBUTING.md) for details

## Deployment
### Glitch.io
1. Create a bot app [here](https://discordapp.com/developers/applications/me)

    a. Click add new app
    b. Give the bot a name (Optionally fill in the description and give the bot a profile image)
2. Click "Create bot user" (Click the public checkbox if you want others to be able to add the bot to their servers)
3. Record the bot token and app client id
4. Click here: [![Remix on Glitch](https://cdn.glitch.com/2703baf2-b643-4da7-ab91-7ee2a2d00b5b%2Fremix-button.svg)](https://glitch.com/edit/#!/import/github/https://github.com/campDevs/DiscordBot/)
5. Add the bot token obtained to the `.env` file: `TOKEN="<TOKEN>"`
6. Replace client id in this link: `https://discordapp.com/oauth2/authorize?client_id=<CLIENT ID>&scope=bot`
7. Navigate to the link and select the server you want to add the bot to from the dropdown

## Contributors

[contributors](https://github.com/campDevs/DiscordBot/contributors)

## License

[MIT](LICENSE.md)
