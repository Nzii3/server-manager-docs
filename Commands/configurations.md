# Configurations
---
Server Manager's configuration system allows you to set configurations on the fly with ease, whether that's admin roles, moderator roles, a suggestions channel, etc.

Name | Description | Example |
--- | --- | --- |
`/config admin_roles` | View all the admin roles set |
`/config admin_role add` | Add an admin role | `/config admin_role add role:@Admin`
`/config admin_role remove` | Remove an admin role | `/config admin_role remove role:@Moderator`
`/config moderator_roles` | View all the moderator roles set |
`/config moderator_role add` | Add a moderator role | `/config moderator_role add role:@Moderator`
`/config moderator_role remove` | Remove a moderator role | `/config moderator_role remove role:@Admin`
`/config custom_reasons` | View all the custom reasons (pre-defined reasons) set |
`/config custom_reason add` | Add a custom reason | `/config custom_reason add name:dm_ads value:DM advertising`
`/config custom_reason remove` | Remove a custom reason | `/config custom_reason remove name:dm_ads`
`/config log_channel` | Set the logs channel | `/config log_channel channel:#mod-logs`
`/config suggestions_channel` | Set the suggestions channel | `/config suggestions_channel channel:#suggestions`
`/config suggestions_ping` | Set the role that is pinged when a suggestion is submitted | `/config suggestions_ping role:@Suggestions`
`/config discussion_threads` | Whether the bot should create a thread when a suggestion is submitted |