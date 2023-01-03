---
order: 1
---
# Getting Started
---
Getting started with Server Manager is simple.

## Log Channel
You're going to want to set the `log_channel` where logs will go (including moderation actions).

To do this, you can use the [!badge variant="info" text="/config log_channel"] command.

!!!
The following occurances will be logged to the log channel:
- Cases
- Case updates
- Warnings
- Warning deletions
- Mutes
- Kicks
- Bans
- *And more to come!*
!!!

## Admin Roles
The [!badge variant="info" text="Admin Roles"] configuration allows you to set roles that can use mostly every command Server Manager has to offer. This can be useful if you want to have users in a role be able to manage Server Manager, but not have [!badge variant="info" text="Manage Guild"] or [!badge variant="info" text="Server Administrator"] permissions.



!!!warning
Users in at least one role in the [!badge variant="info" text="Admin Roles"] configuration bypass the [!badge variant="info" text="Moderator Roles"] configuration.
!!!

## Moderator Roles
The [!badge variant="info" text="Moderator Roles"] configuration is similar to the [!button size="xs" text="Admin Roles"](#admin-roles) config, but these roles won't be able to set configurations, host polls, start giveaways, manage forms, etc. The [!badge variant="info" text="Moderator Roles"] are restricted to only using the [!button size="xs" text="Moderation"](/Commands/moderation.md) commands.