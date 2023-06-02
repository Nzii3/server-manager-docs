# Moderation
---

Name | Description | Example |
--- | --- | --- |
`/warn` | Warn a member | `/warn member:@vNziie-- reason:Spamming!`
`/warnings` | View a member's warnings |
`/remove_warning` | Remove a warning by ID | `/remove_warning id:059185`
`/delete_all_warnings` | Delete **ALL** warnings from your server - useful if the bot is acting slow when warning users in your server |
`/kick` | Kick a member from the server | `/kick member:@vNziie-- reason:More spam`
`/ban` | Ban a member from the server | `/ban member:@vNziie-- reason:Stop spamming!`
`/purge` | Purge messags from the current channel (max 1,000) | `/purge amount:10`

## Customizable Embeds
The following configurations edit responses and user DMs (⭐️ notes the configuration is unlocked when purchasing premium).
- `moderation.ban.response`
- ⭐ `moderation.ban.user_dm`
- `moderation.kick.response`
- ⭐ `moderation.kick.user_dm`
- `moderation.mute.response`
- ⭐ `moderation.mute.user_dm`
- `moderation.warn.response`
- ⭐ `moderation.warn.user_dm`

> See the [Configurations](../configurations) category for more information.

## Cases
We've implemented our own cases system so you can look back on a user's history, even if they aren't in the server.

Name | Description | Example
--- | --- | --- |
`/case` | View a case by ID | `/case case_id:L18d60Gj63W`
`/cases` | View cases for the whole server for a user
`/createcase` | Create a custom case for a user | `/createcase member:@vNziie-- reason:I think they are a bad dev. proof:https://redirect.nziie.is-a.dev/proof`
