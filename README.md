<div align="center">
  <img src="https://cdn.discordapp.com/attachments/519145981917265921/543001500079882260/ELECTROHEADER.png" align="center">
  <br>
  <strong><i>A simple moderation & fun bot for Discord.</i></strong>
  <br>
  <br>
    
  <a href="https://heroku.com/deploy?template=https://github.com/kyb3r/modmail">
    <img src="https://cdn.discordapp.com/attachments/519145981917265921/543025770671636494/JoinDiscord.png">
  </a>
  
  <a href="https://discord.gg/j5e9p8w">
    <img src="https://cdn.discordapp.com/attachments/519145981917265921/543025770671636491/SubscribeYoutube.png">
  </a>
  

</div>

---

## How Does Modmail Work?

<img src="https://i.imgur.com/GGukNDs.png" align="right" height="350">

When a user sends a direct message to the bot, a channel is created within an isolated category. This channel is where messages will be relayed. To reply to the message, simply use the command `?reply` in the channel. A full list of commands can be found in the [wiki](https://github.com/kyb3r/modmail/wiki) or by using the `?help` command.

## Installation

Currently, the easiest and fastest way to set up the bot is by using Heroku, which is a service that offers a free plan for hosting applications. If you choose to install the bot using Heroku, you will not need to download anything. The [**installation guide**](https://github.com/kyb3r/modmail/wiki/Installation) will guide you through the entire installation process. If you run into any problems, join our [Discord server](https://discord.gg/etJNHCQ) for help and support. Even if you don't have any issues, you should come and check out our awesome Discord community! :wink:

---

# Notable Features

## Customizability

Modmail has a range of configuration variables that you can dynamically alter with the `?config` command. You can use them to change the different aspects of the bot, for example, the embed color, responses, reactions, status, etc. Snippets and custom command aliases are also supported. Snippets are shortcuts for predefined messages that you can send. Add or remove snippets with the `?snippets` command. The level of customization is ever growing thanks to our exceptional contributors.

## Linked Messages

<img src="https://i.imgur.com/6L9aaNw.png" align="right" height="350">

Have you sent something with the `?reply` command by accident? Don't fret, you can delete your original message, and the bot will automatically delete the corresponding message sent to the recipient of the thread!  You can also use the `?edit` command to edit a message you sent.

## Thread Logs

Thread conversations are automatically logged with a generated viewable website of the complete thread. Logs are rendered with styled HTML and presented in an aesthetically pleasing way—it blends seamlessly with the mobile version of Discord. An example of a logged conversation: https://logs.modmail.tk/02032d65a6f3

## Automatic Updates

The bot checks for new updates every hour and will automatically update to the newest version. Modmail is under active development, which means that you can always look forward to new and useful features! To disable this functionality, for example, when you customized your fork, you can do so by adding a `disable_autoupdates` config variable and set it to `yes` or `true`. 

---

# Contributing

This project is licenced under MIT. If you have any new ideas, create an issue or a pull request. Contributions to Modmail are always welcome, whether it be improvements to the documentation or new functionality, please feel free make the change.

If you use Modmail and love it, consider supporting me on **[Patreon](https://www.patreon.com/kyber)** :heart:
