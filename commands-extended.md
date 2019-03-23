---
description: 'On this page, you will find all the commands of the bot.'
---

# Commands \(extended\)

## Legend

`<>` Required argument

`[]` Optional argument

## Main

### Category

> Use the command `m!category create` to create a category named '📊 Server Stats 📊'. 
>
> If the category already exists, you can use `m!category update` to move all the counters back there.
>
> #### Usage
>
> ```text
> m!membercount <on/off>
> ```
>
> #### Alias
>
> `cat`

### Counter

> The bot's most important command. With this command you can toggle counters on and off. The channels can also be updated with this command, using `m!counter update`. 
>
> **Examples:**
>
> ```text
> m!counter users on => turns the user counter on
> m!counter channels off => turns the channels counter off.
> ```
>
>  For a list of counters, do `m!counter`.
>
> #### Usage
>
> ```text
> m!counter <counter> <on/off>
> m!counter update
> ```
>
> #### Aliases
>
> `channel`, `count`

### Counter Name \(Patrons only\)

> Changes the name of the specified counter. The available counters are member, user, bot, roles, channels. Include `{count}` in the name, where you want the count \(the number\) to be. 
>
> **Example:**
>
> ```text
> m!countername user {count} very cool people
> ```
>
>  This will set the user counter to display as `99 very cool people`.
>
> #### Usage
>
> ```text
> m!countername <counter> <name>
> ```
>
> #### Alias
>
> `cname`

### Setup

> Very useful for when you want to quickly set me up like normal. Reverts all of the settings back to default and turns every counter on. This will also create the counters and the category.
>
> #### Usage
>
> ```
> m!setup
> ```

## Utility

### Help

> Returns the help menu with all the commands or, when specified, information about a command.
>
> #### Usage
>
> ```text
> m!help [command]
> ```
>
> #### Aliases
>
> `h`, `commands`

### Invite

> Returns with my invite link.
>
> #### Usage
>
> ```text
> m!invite
> ```

### Member List

> Returns a text file \(.txt\) with a list of copy-pasteable usernames of the members in your server. 
>
> **Flags:** 
>
> `-ids` includes the id of every user, separated by `||`.   
> `-nicks` instead of usernames, this will return nicknames.   
> _You can use both flags in one command._ 
>
> **Examples:**
>
> ```text
> m!memberlist -nicks
> m!memberlist -ids -nicks
> ```
>
> #### Usage
>
> ```text
> m!memberlist [-ids] [-nicks]
> ```
>
> #### Alias
>
> `mlist`

### Support

> Returns with an invite link to my support server.
>
> #### Usage
>
> ```text
> m!support
> ```
>
> #### Alias
>
> `server`

## Other

### Data

> Returns all the data I have stored about your server.
>
> #### Usage
>
> ```text
> m!data
> ```

### Info

> Returns information about the bot.
>
> #### Usage
>
> ```text
> m!info
> ```
>
> #### Aliases
>
> `stats`, `about`

### Ping

> Returns with the bot's ping.
>
> #### Usage
>
> ```text
> m!ping
> ```

