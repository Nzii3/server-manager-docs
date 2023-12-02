# Giveaways
---

!!!success Recent changes
- Rename command group from [!badge variant="info" text="/giveaway"] to [!badge variant="info" text="/giveaways"]
- Renamed [!badge variant="info" text="/giveaways start"] to [!badge variant="info" text="/giveaways create"]
- Added [custom embed support](#customized-embeds)
- Changed giveaway behavior
- Fixed bugs

See [recent updates](/updates) for more information.
!!!

Server Manager's giveaway system is similar and different compared to others. Server Manager allows you to use **all** features in giveaways that others don't. You can __add extra entries__, __set required roles__, __set blacklisted roles__, and more!

Name | Description | Example |
--- | --- | --- |
[!badge variant="info" text="/giveaways create"] | Create a giveaway from scratch | `/giveaways start name:$5 Nitro duration: 1d`
[!badge variant="info" text="/giveaways end"] | End a giveaway | `/giveaways end giveaway_id:1055584705577230478` <span style="color:#e74c3c">*</span>
[!badge variant="info" text="/giveaways view"] | View a specific giveaway or all giveaways | `/giveaways view giveaway_id:1055584705577230478` <span style="color:#e74c3c">*</span>
[!badge variant="info" text="/giveaways delete"] | Delete a giveaway | `/giveaways delete giveaway_id:1055584705577230478` <span style="color:#e74c3c">*</span> <span style="color:#e74c3c">**</span>

<span style="color:#e74c3c">*</span> The [!badge variant="info" text="giveaway_id"] is the giveaway's message ID, you'll need to use that.

<span style="color:#e74c3c">**</span> Please use the [!badge variant="info" text="/giveaways delete"] command when wanting to delete a giveaway, deleting the message doesn't remove it from the database and doing so can mean lower performance for your server specifically when managing giveaways.

## Customized Embeds
With the [!badge variant="info" text="giveaway_embed"] configuration in the [[!badge variant="info" text="/config set"] command](./configurations.md/#commands), you can customize the embed that is sent when a giveaway is hosted. See the [Configurations](../configurations) tab for more info.

## FAQ
==- How do I host a drop giveaway?
Currently, **there is no feature to host a drop giveaway**. However, we are always looking for community insights on new features we should add! Let us know in our [support server](https://servermanagerbot.ml/support) if you'd like to see this in Server Manager.
===
---
==- Example Images
![Creating a giveaway](/static/giveaways1.png)
![(Reaction) Giveaway started](/static/giveaways2.png)
![(Button) Entering giveaway](/static/giveaways3.png)
===
