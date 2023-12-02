# Suggestions
---

!!!success Recent changes
- Rename base command group from [!badge variant="info" text="/suggestions"] to [!badge variant="info" text="/suggestion"]
- Added [custom embed support](#customized-embeds)
- Changed suggestion marking behavior
- Added future support for custom suggestion marking statuses
- Fixed bugs
- Documentation: updated images

See [recent updates](/updates) for more information.
!!!

Server Manager's suggestions system allows members to share their ideas about your server with ease, while allowing them to vote on other suggestions using buttons and vote percentages, similar to how a [poll's](./polls.md) voting works. **Server Manager allows the following of a suggestion** by clicking the `🔔` button to subscribe to the suggestion, thus you getting direct messaged by the bot when a suggestion is **accepted**, **denied**, **considered**, **implemented**, **in progress**, or **commented on**. **Need to unsubscribe?** Just click the button again!

Name | Description | Example |
--- | --- | --- |
[!badge variant="info" text="/suggest"] | Suggest something to the server | `/suggest suggestion:Host more giveaways!`
[!badge variant="info" text="/suggestion edit"] | Edit a suggestion<span style="color:#e74c3c">*</span> | `/suggestion edit suggestion_id:p37Z78mc57Df`
[!badge variant="info" text="/suggestion view"] | View a suggestion by ID | -
[!badge variant="info" text="/suggestion mark"] | Mark a suggestion with a status | `/suggestion mark suggestion_id:p37Z78mc57Df status:Approved close_voting:True comment:Approved!`
[!badge variant="info" text="/suggestion delete"] | Delete a suggestion by ID | -

<span style="color:#e74c3c">*</span> This command can only be used by server moderators+ or the suggestion author

## Customizable Embeds
The following embeds are customizable via embed builder when using the [[!badge variant="info" text="/config set"] command](./configurations.md/#commands):
- `suggestion.embed`

==- Example Images
![Suggest something](https://cdn.nziie.xyz/u/files/24grHPTEKbUd)
![Suggestion voting](https://cdn.nziie.xyz/u/files/UYxJ7KH1B2Te)
![Approved suggestion](https://cdn.nziie.xyz/u/files/kQtPZrnBascy)
![Approved suggestion (DM)](https://cdn.nziie.xyz/u/files/t2rqTdPcHFtr)

![Customizing suggestion embed](https://cdn.nziie.xyz/u/files/4Xubd70t1isz)
===
