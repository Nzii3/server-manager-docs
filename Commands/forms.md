# Forms
---

!!!success Recent changes
- Added a **Form Settings** embed field to show settings for the form when editing one (community suggested feature)
- Added [FAQ](#faq)

See [recent updates](/updates) for more information.
!!!
Server Manager's forms/applications system gives you a unique experience when creating and managing forms. We've made it easier than ever to **create**, **edit**, **delete**, and **respond** to forms. Including our own tickets system, you can create a followup discussion ticket with the user that submitted a form. You can close/disable forms, set roles to be given (when accepted), set a ping role, add/remove questions, customize accepted and denied messages, and much more while editing a form.

Name | Description | Example |
--- | --- | --- |
[!badge variant="info" text="/forms create"] | Create a form | `/forms create name:Staff Application response_channel:#apps`
[!badge variant="info" text="/forms edit"] | Edit a form, much more customization here | `/forms edit name:Staff Application`
[!badge variant="info" text="/forms delete"] | Permanently delete a form | `/forms delete name:Staff Application`
[!badge variant="info" text="/forms export"] | Export raw JSON files of a form | `/forms export name:Staff Application`
[!badge variant="info" text="/forms import"] | Import JSON files to a form, [use this format](#json-formatting) | -
[!badge variant="info" text="/form"] | Fill out a form | `/form name:Staff Application`
[!badge variant="info" text="/apply"] | Fill out a form (alias for [!badge variant="info" text="/form"]) | `/apply name:Staff Application`

## JSON Formatting
Please use the following JSON template in order to import a form from JSON correctly.

```json
{"name": "Form name", "description": "Form description", "questions": ["Question 1", "Question 2", "Question 3"], "response_channel": VALID_CHANNEL_ID_INTEGER, "settings": {"given_roles": [ROLES_IDS_IN_LIST], "required_roles": [ROLE_IDS_IN_LIST], "ping_roles": [ROLE_IDS_IN_LIST], "accepted_message": "Put as `null` for default", "denied_message": "Put as `null` for default"}}
```

## FAQ
==- How do I send form responses to another server?
You can use [json formatting](#json-formatting) to make Server Manager send form responses to another channel in another server. Just simply set the `response_channel` key in the JSON data to whatever channel ID you want. Please note **the bot must be in the secondary server**.
===
==- Discord auto-complete in the `name` argument isn't working, help!
Unfortonately we cannot do anything about that, since it's a bug that sometimes happens with Discord's UI. It's recommended to try restarting your Discord client (CTRL+R for windows), or refreshing it by closing the app on mobile.

![Form argument](https://cdn.nziie.xyz/u/files/zXY6ZF8Re1kD)
===


---

==- Example Images
![Customized accepted message](/static/forms1.png)
![Manage a form](/static/forms2.png)
![Filling out a form (1)](/static/forms4.png)
![Finished form (2)](/static/forms3.png)
![Edit a form](/static/forms5.png)
===
