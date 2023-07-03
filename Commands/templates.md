# Templates

!!!success Recent changes
- Addition of the templates system
- Big fixes
!!!

=== What are templates?
Templates in Server Manager are, well, *templates* of the following:
- Messages (with content and embeds)
- [Buttons](#buttons)
- Menus/selects *(coming soon)

Message templates serve as the foundation of the entire system by enabling the sending of comprehensive messages in channels. These templates can include buttons, embeds, and various other elements. Additionally, the option to include an optional webhook allows for more versatile message delivery.


===

## Commands

Name | Description | Example |
--- | --- | --- |
[!badge variant="info" text="/messages create"] | Create a message template | [!badge variant="info" text="/messages create name:Self roles"]
[!badge variant="info" text="/buttons create"] | Create a button template for a message | [!badge variant="info" text="/buttons create label:Giveaways unique_id:giveaways-role-button color:Green"]
[!badge variant="info" text="/messages edit"] | Edit a message template | [!badge variant="info" text="/messages edit name:Self roles"]
[!badge variant="info" text="/buttons edit"] | Edit a button template | [!badge variant="info" text="/buttons edit unique_id:giveaways-role-button"]
[!badge variant="info" text="/messages delete"] | Delete a message template | [!badge variant="info" text="/messages delete name:Self roles"]
[!badge variant="info" text="/buttons delete"] | Delete a button template | [!badge variant="info" text="/buttons delete unique_id:giveaways-role-button"]
**Webhooks:** [!badge variant="info" text="/messages webhooks create"] | Create a webhook to send templates with buttons | [!badge variant="info" text="/messages webhooks create name:Self Roles Manager avatar:[attachment]"]
**Sending:** [!badge variant="info" text="/messages send"] | Send a message template in a channel | [!badge variant="info" text="/messages send name:Self roles"]
**Editing:** [!badge variant="info" text="/messages edit_message"] | Edit a message (or bot webhook message) to update the template on that message | [!badge variant="info" text="/messages edit_message message_id:1017856153718925112 channel:#development name:Self roles"]


## Buttons
You can create buttons with a label, color/style, unique id, multiple actions, and an optional URL (for link buttons). These buttons can be attached to message templates, providing them with a comfortable "*home*." This is referred to as the parent message of a button.
### Actions
The button callback triggers actions. Each button allows for 2 actions (5 with premium). If you require an increase in the actions limit for a particular button but prefer not to buy premium, please don't hesitate to contact us in our support server ([!badge variant="info" text="#limits-increase"] channel). Follow the instructions provided in the channel to submit a request for increasing the limits.

## Self/Button Roles {#self-roles}
Indeed! You can utilize buttons and the **Toggle Role** action to accomplish self roles. By default, the bot will provide information about the role that was granted or revoked. However, you have the option to customize this response by including a send template response action within the button's actions.

## Webhooks
You are given the ability to use webhooks to even more customize message templates. The bot can send messages with any webhook in the server, but make sure it has the **Manage Webhooks** permission.

!!!warning Webhooks With Buttons
**Templates featuring buttons are restricted from being sent with webhooks unless the bot is the owner of the webhook**. This is the reason why the [!badge variant="info" text="/messages create name:Self roles"] command exists. It addresses the <u>limitation imposed by Discord</u>, which prohibits bots from managing buttons on webhook messages they don't own, and this restriction is quite understandable for obvious reasons.
!!!


==- Example Images
![](/static/templates1.png)
![](/static/templates2.png)
===
