# Configurations

Name | Description | Example |
--- | --- | --- |
[!badge variant="info" text="/config show"] | View all configurations, their current value, description, and more information on said configuration | -
[!badge variant="info" text="/config set"] | Set a configuration by key | [!badge variant="info" text="/config set config:giveaway_embed"]
[!badge variant="info" text="/config reset"] | Reset a configuration to it's default value | [!badge variant="info" text="/config reset config:moderation.ban.user_dm"]

## Placeholders
Placeholders give you the ability to use variables in custom embeds, allowing you to use information from a command in those custom embed responses. For example, saying the duration of a mute in the `moderation.mute.user_dm` or `moderation.mute.response` embed in the mute command. This gives you full customization on how the bot responds to commands specifically for your server.

### Basic Placeholders
!!!
These placeholders are always given to use in any command that has a custom embed response eligible.
!!!

!!!warning
You must provide the braces (`{}`) in the placeholder names to work
!!!

Placeholder | Description |
--- | --- | --- |
`{user.name}` | User or the `member` argument in the command object, displays the usernameof that user
`{user.full_name}` | User's username and discriminator (e.g. Wumpus#0000)
`{user.avatar}` | User's avatar as a string, can be used in `icon_url` embed fields, if none returns Discord's default logo
`{user.id}` | User's ID
`{user.notified}` | 'Yes' or 'No' of whether the user was notified for an action or not, if not obtainable, returns 'No'
`{guild.name}` | The guild the command is being used in, shows the guild (server)'s name
`{guild.icon}` | Guild's icon as a string, if none, returns Discord's default logo; can be used in `icon_url` fields
`{guild.id}` | Guild's ID
`{author.name}` | Author of the commmand's name
`{author.full_name}` | Author's username and discriminator (e.g. Wumpus#0000)
`{author.avatar}` | Author's avatar as a string, can be used in `icon_url` embed fields, if none returns Discord's default logo
`{author.id}` | Author's ID

### Moderation Placeholders

Placeholder | Description | Example |
--- | --- | --- |
`{case.id}` | Linked case ID
`{duration}` | Duration of the action
`{reason}` | Reason for the action