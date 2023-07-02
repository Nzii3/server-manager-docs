# Templates

!!!success Recent changes
<h2>Coming soon! By 7/3/2023</h2>
!!!

=== What are templates?
Templates in Server Manager are, well, *templates* of the following:
- Messages (with content and embeds)
- [Buttons](#buttons)
- Menus/selects *(coming soon)

Message templates can be sent in channels (optional webhook to send with) with buttons, embeds, and much more; making message templates the core of the entire system.


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
**Sending:** [!badge variant="info" text="/messages send"] | Send a message template in a channel | [!badge variant="info" text="/messages send name:Self roles"]


## Buttons
You can create buttons with a label, color/style, unique id, multiple actions, and an optional URL (for link buttons). These buttons can be attached to message templates, providing them with a comfortable "*home*." This is referred to as the parent message of a button.
### Actions
The button callback triggers actions. Each button allows for 2 actions (5 with premium). If you require an increase in the actions limit for a particular button but prefer not to buy premium, please don't hesitate to contact us in our support server ([!badge variant="info" text="#limits-increase"] channel). Follow the instructions provided in the channel to submit a request for increasing the limits.

==- Example Images
<h2>Coming soon!</h2>
===
