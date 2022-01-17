# Managing commands

!!! info**colors 💚⚪⚫🔶🔵🔴
    Please consider using the Dashboard at [https://carl.gg](https://carl.gg) it is much, much easier for this and allows for per-command customization *far* beyond what commands offer.

!!! info
    Restricted commands require a bot channel to be set up.

| Name | Example | Usage |
| :--- | :--- | :--- |
| **ignore [channels...] [commands...]**  | !ignore #general #log #adminsonly "temp home" ping activity | If no channel is specified, the current channel is ignored. If a command is supplied, it will ignore that command in the specified channel. Manage server bypasses this. You can supply more than one channel and or command. |
| **ignore server** | !ignore server | This is essentially the sa
| **ignore all [commands...]**  | !ignore all "pc top" ping | This is equal to typing !ignore channel command subcommand in all channels the bot can see, useful if you want to ignore a command in all channels except for one. This will not work for channels created in the future. If the command is already ignored in a channel, this will unignore it. |
| **unignore [channels...] [command...]** | !unignore \#general \#log temp ping | Rev
| **disable &lt;commands...&gt;** | !disable "pc top" rr temp | This really disables the co
| **d
