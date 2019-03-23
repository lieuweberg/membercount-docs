# V2 Changelog

## Member Count v2 is released!

The time has come.   
This is the biggest update we've ever had.   
****TL;DR Brand new counters, huge performance improvements, as well as general changes.

## **New features**

* Added 2 new counters. Channel count and role count.
* Added aliases for various commands, such as `m!info` \(aliases: `about`, `stats`\) and `m!category` \(alias: `cat`\).
* New command: `m!counter update`. You can now update the counters manually.

## Mentionable changes

* The bot now recognises counters by channel ID instead of name.
* The commands `m!membercount`, `m!botcount` and `m!usercount` are combined as one. It is changed to `m!counter <counter> <on/off>`.
* The category commands are combined too. They are now subcommands, `m!category create` and `m!category update`.
* You now require the `Administrator` permission to use the main commands, such as `m!setup` and `m!category`, instead of `Manage Server`.
* The bot no longer requires the `Administrator` permission. These are the permissions it needs now: 

  ```text
  Read Messages
  Send Messages
  Manage Channels
  Manage Roles
  Attach Files
  Connect
  Embed Links
  ```

* The counter name is completely customizable now, which means that you can move the count to any part of the name, instead of just after the `:`. Example: `m!countername user {count} amazing people` will change the counter name to `99 amazing people`. \(Patrons only\)

## Greatly improved uptime

* Changed to Eris \(another js library\) due to the poor memory management in Discord.js.
* Switched out of the legacy sharding. We now use Node.js's cluster module to spread shards more evenly.
* Clustering and improvements for shard management. This essentially means that the main process will reconnect the shards if needed. This also means that the memory issue is FIXED!
* Many more smaller changes for performance improvements and bug fixes.

## _**What's next?**_

The new counters are automatically enabled for existing servers, they will show up when a role/channel is created/deleted. You can also use the command `m!counter update` and the counters will be created. The documentation is a work in progress. Meanwhile, if you have any questions, try using `m!help <command>`, or ask in this server.

