# DisFS

A Discord-based filesystem for (theoretically) infinite file storage.

## Setup

First, create a server with at least two channels. One channel (File channel) will store the file contents, the other (Listing channel) will store the list of files.

Next, follow [these directions](https://discordpy.readthedocs.io/en/stable/discord.html) to create a bot account.

The bot must have all Text Permissions and the View Channels permission.

Finally, run `disfs ls` to set up the required information.

If all goes well, you should see an empty file list.

Afterwards, you can begin uploading files with `disfs add <filename>`.
