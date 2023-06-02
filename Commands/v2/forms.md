# Forms
---
Server Manager's forms/applications system gives you a unique experience when creating and managing forms. We've made it easier than ever to **create**, **edit**, **delete**, and **respond** to forms. Including our own tickets system, you can create a followup discussion ticket with the user that submitted a form. You can close/disable forms, set roles to be given (when accepted), set a ping role, add/remove questions, customize accepted and denied messages, and much more while editing a form.

Name | Description | Example |
--- | --- | --- |
`/forms create` | Create a form | `/forms create name:Staff Application response_channel:#apps`
`/forms edit` | Edit a form, much more customization here | `/forms edit name:Staff Application`
`/forms delete` | Permanently delete a form | `/forms delete name:Staff Application`
`/forms export` | Export raw JSON files of a form | `/forms export name:Staff Application`
`/forms import` | Import JSON files to a form [use this format]()
`/form` | Fill out a form | `/form name:Staff Application`
`/apply` | Fill out a form (alias for `/form`) | `/apply name:Staff Application`

## JSON Formatting
Please use the following JSON template in order to import a form from JSON correctly.

```json
{"name": "Form name", "description": "Form description", "questions": ["Question 1", "Question 2", "Question 3"], "response_channel": VALID_CHANNEL_ID_INTEGER, "settings": {"given_roles": [ROLES_IDS_IN_LIST], "required_roles": [ROLE_IDS_IN_LIST], "ping_roles": [ROLE_IDS_IN_LIST], "accepted_message": "Put as `null` for default", "denied_message": "Put as `null` for default"}}
```

==- Example Images
![Customized accepted message](/static/forms1.png)
![Manage a form](/static/forms2.png)
![Filling out a form (1)](/static/forms4.png)
![Finished form (2)](/static/forms3.png)
![Edit a form](/static/forms5.png)
===
