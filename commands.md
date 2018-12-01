---
description: 'In this page, you will find all the commands of the bot.'
---

# Commands

## Legend

`<>` Required argument

`[]` Optional argument

## Counters

### Member Count

> Toggles the member counter on or off. This displays the total amount of members in this server. 
> 
> #### Usage:

> ```text
> m!membercount <on/off>
> ```

### User Count

> Toggles the user counter on or off. This displays the total amount of users \(humans\) in this server. 
>
> #### Usage:
>
> ```text
> m!usercount <on/off>
> ```

### Bot Count

> Toggles the bot counter on or off. This displays the total amount of bots in this server.
>
> #### Usage:
>
> ```text
> m!botcount <on/off>
> ```

## Utility 

### Counter Name \(Patron-only\)

Changes the name of the specified counter **in front of** the `:`. Specify which counter with member, user or bot.

Example: `m!countername user Hobbits`

This sets the usercounter to display `Hobbits: 99`. 

#### Usage:

```text
m!countername <counter> <name>
```

### Help

Returns the help menu with all the commands or, when specified, information about a command. 

#### Usage:

```text
m!help
m!help <command>
```

### Invite

Returns with my invite link. 

#### Usage:

```text
m!invite
```

### Member List

Returns a text file \(.txt\) with a list of copy-pasteable usernames of the members in your server.

{% hint style="info" %}
Note that if this returns one long string of characters, open the list in a different text editor.
{% endhint %}

#### Flags: 

`-ids` includes the id of every user, seperated by `||`. `-nicks` instead of usernames, this will return nicknames. _You can use both flags in one command._ 

#### Examples:

```text
m!memberlist -nicks
m!memberlist -ids -nicks
```

#### Usage:

```text
m!memberlist [-ids] [-nicks]
```

### Setup

Reverts all of the settings back to default and turns every counter on. Very useful for when you want to quickly set the bot up like normal. 

#### Usage:

```text
m!setup
```

### Support

Returns with an invite link to the support server. 

#### Usage:

```text
m!support
```

## Category

### Create Category

Creates a category for your counters. 

#### Usage:

```text
m!createcategory
```

### Update Category

Puts all of the counters back to their orginal positions. 

#### Usage:

```text
m!updatecategory
```

## Others

### Data

Returns all of the permanently stored data about your server. I want you to know that you are safe.

#### Usage:

```text
m!data
```

### Info

Returns information about the bot. 

#### Usage:

```text
m!info
```

### Ping

Returns with the bot's API ping. 

#### Usage:

```text
m!ping
```



