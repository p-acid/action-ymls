# Github Action Script Storage 📦

<h4 align='center'>
  A collection of GitHub Actions to improve your development process 💬
</h4>

<br/>

### Notice

> All scripts are written assuming that **you use the Node.js** for your project.

<br/>

## CHANGELOG

Scripts for who: 

- Wants to record your update history automatically 

<br/>


### Release Please

A script to record your update history with Google's Github Actions plugin

> ✋ **Need to prepare**
>
> - Add `package.json` file for versioning
> - Approve workflow permissions in your project repo
>   - Read and write permissions
>   - Allow GitHub Actions to create and approve your pull requests

- [`release-please.yml`](https://github.com/p-acid/action-ymls/blob/main/.github/workflows/release-please.yml)

<br/>

## Telegram 

Scripts for who:

- Use Telegram to communicate with their team members
- Make personal project in small team

<br/>

### PR Review Bot

A set of scripts to be notified of Github activity via a Telegram bot

> ✋ **Need to prepare**
>
> - Make Telegram Bot
> - Set Telegram Token
>   - Bot Id(`TELEGRAM_TOKEN`)
>   - Chat Id(`TELEGRAM_CHAT_ID`)

- [`pr-created.yml`](https://github.com/p-acid/action-ymls/blob/main/.github/workflows/telegram-pr-created.yml)
- [`pr-review.yml`](https://github.com/p-acid/action-ymls/blob/main/.github/workflows/telegram-pr-review.yml)

