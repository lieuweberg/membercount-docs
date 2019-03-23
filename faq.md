# FAQ

## Why is Member Count not responding?

Please check the following before asking for help. 

* Make sure the bot has `Read Messages`, `Send Messages`, and `Embed Links` permissions. 
* Make sure the bot is online. Discord might be having issues, or the bot might be restarting.

## How do I change the prefix?

You can't change the prefix of the bot currently. If another bot coincidentally has the same prefix as Member Count, you can mention the bot with the command. For example: `@Member Count#7205 ping`.

## How do I change the counter names?

Use the command [`m!countername <counter> <name>`](commands-extended.md#counter-name-patrons-only), and include `{count}` in the name where you want the number to be at. This feature is for Patrons only. You can donate at [https://www.patreon.com/member\_count](https://www.patreon.com/member_count).

## How do I turn off a counter?

Run [`m!counter <counter> <on/off>`](commands-extended.md#counter). For the counter, choose from the following:`- members (users + bots)  
- users (humans)  
- bots (bots)  
- roles (total roles)  
- channels (total channels)`

## Can the bot display a count other than the 5 options? \(e.g. YouTube subscription\)

As of now, those are the only counters available. We are working on members in a role count, online count, and API count. Please look out for [\#announcements](https://discord.gg/dWMgWWw).

## How do I prevent normal users from using the commands?

All counter related commands are already restricted to users with the `Administrator` permission. To prevent usage of other commands, restrict the bot under channel settings: `Permissions` &gt; `Add Member` &gt; `Member Count` &gt; `Select ╳ under Send Messages`. Note that this will prevent you from being able to use the bot in that channel as well.

## Why are the counters duplicating/not updating?

Please ensure that the bot has the correct permissions to the counters \(i.e. `See Voice Channel`, `Manage Channel` and `Connect`\).

## Can I change the bot's username and avatar?

No, username and avatar are global. Changing it will affect all servers Member Count is on. You can only change the bot's nickname under Manage User, if **you** have the `Manage Nicknames` permission.

## Can I self-host the bot?

No, you can't. The bot's code is closed source.

