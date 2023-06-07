# Moderation
---

!!!success Recent changes
- Removed [!badge variant="info" text="/delete_all_warnings"] command to due lack of use
- Renamed [!badge variant="info" text="/remove_warning"] to [!badge variant="info" text="/delwarn"] for ease-of-use
- Added [custom embed support](#customized-embeds)
- Fixed bugs

See [recent updates](/updates) for more information.
!!!

Name | Description | Example |
--- | --- | --- |
[!badge variant="info" text="/warn"] | Warn a member | `/warn member:@vNziie-- reason:Spamming!`
[!badge variant="info" text="/warnings"] | View a member's warnings | -
[!badge variant="info" text="/delwarn"] | Remove a warning by ID | `/delwarn id:059185`
[!badge variant="info" text="/kick"] | Kick a member from the server | `/kick member:@vNziie-- reason:More spam`
[!badge variant="info" text="/ban"] | Ban a member from the server | `/ban member:@vNziie-- reason:Stop spamming!`
[!badge variant="info" text="/purge"] | Purge messags from the current channel (max 1,000) | `/purge amount:10`

## Customizable Embeds
The following configurations edit responses and user DMs ([⭐](https://servermanagerbot.ml/premium) notes the configuration is unlocked when purchasing premium).
- `moderation.ban.response`
- `moderation.ban.user_dm` [⭐](https://servermanagerbot.ml/premium)
- `moderation.kick.response`
- `moderation.kick.user_dm` [⭐](https://servermanagerbot.ml/premium)
- `moderation.mute.response`
- `moderation.mute.user_dm` [⭐](https://servermanagerbot.ml/premium)
- `moderation.warn.response`
- `moderation.warn.user_dm` [⭐](https://servermanagerbot.ml/premium)
!!!
See the [Configurations](../configurations) category for more information.
!!!
## Cases
We've implemented our own cases system so you can look back on a user's history, even if they aren't in the server.

Name | Description | Example
--- | --- | --- |
[!badge variant="info" text="/case"] | View a case by ID | `/case case_id:L18d60Gj63W`
[!badge variant="info" text="/cases"] | View cases for the whole server for a user | -
[!badge variant="info" text="/createcase"] | Create a custom case for a user | `/createcase member:@vNziie-- reason:I think they are a bad dev. proof:https://redirect.nziie.is-a.dev/proof`
