# Configurations

## Commands

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

The following categories use these placeholders:
#### Ban Placeholders
#### Kick Placeholders
#### Mute Placeholders
---
Placeholder | Description |
--- | --- |
`{case.id}` | Linked case ID
`{duration}` | Duration of the action
`{reason}` | Reason for the action

#### Warn Placeholders
An extra placeholder is added in this category to show how many warnings a member has with the correct suffix.

---

Placeholder | Description | Example
--- | --- | --- |
`{case.warning_number_with_suffix}` | Warning number with suffix (e.g. `st`, `nd`, `rd`, `th`, etc.) | 1st

### Suggestions Placeholders
These placeholders are used in the `suggestion.embed` configuration.

---
Placeholder | Description | Example
--- | --- | --- |
`{suggestion.content}` | Suggestion's content, what they are actually suggesting | More updates!
`{suggestion.id}` | Suggestion's generated ID, for future status marking, deleting, editing, etc. | fXpVdLYn8BkCZ
`{suggestion.future.upvotes}` | Raw number of upvotes the suggestion has | 7
`{suggestion.future.upvotes_percent}` | Calculated percent of upvotes compared to downvotes, this and `{suggestion.future.downvotes_percent}` add up to 100% | 85%
`{suggestion.future.downvotes}` | Raw number of downvotes the suggestion has | 3
`{suggestion.future.downvotes_percent}` | Calculated percent of downvotes compared to upvotes, this and `{suggestion.future.upvotes_percent}` add up to 100% | 15%

### Poll Placeholders
These placeholders are used in the `polls.embed` configuration.

---
Placeholder | Description
--- | --- |
`{poll.content}` | Poll's content/message
`{poll.id}` | Poll's randomly generated ID, used for future use to close a poll
