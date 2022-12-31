# Giveaways
---
Server Manager's giveaway system is similar and different compared to others. Server Manager allows you to use **all** features in giveaways that others don't. You can __add extra entries__, __set required roles__, __set blacklisted roles__, and more!

Name | Description | Example |
--- | --- | --- |
`/giveaway start` | Start a giveaway | `/giveaway start name:$5 Nitro duration: 1d`
`/giveaway end` | End a giveaway | `/giveaway end giveaway_id:1055584705577230478` <span style="color:#e74c3c">*</span>
`/giveaway view` | View a specific giveaway or all giveaways | `/giveaway view giveaway_id:1055584705577230478` <span style="color:#e74c3c">*</span>
`/giveaway delete` | Delete a giveaway | `/giveaway delete giveaway_id:1055584705577230478` <span style="color:#e74c3c">*</span> <span style="color:#e74c3c">**</span>

<span style="color:#e74c3c">*</span> The `giveaway_id` is the giveaway's message ID, you'll need to use that.

<span style="color:#e74c3c">**</span> Please use the `/giveaway delete` command when wanting to delete a giveaway, deleting the message doesn't remove it from the database and doing so can mean lower performance for your server specifically when managing giveaways.