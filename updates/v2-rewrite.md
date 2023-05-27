---
authors:
  - name: Nziie
    avatar: https://cdn.nziie.xyz/u/files/XLuj6e2Zm19R
---

# v2 Rewrite

**Server Manager** is being fully re-written to provide additional features, customization, and bug fixes. These changes will not be reflected in the main bot (Server Manager) immediately, but they will be in [Server Manager Beta](https://servermanagerbot.ml/beta-program).

**Below are logs of changes and updates:**

## 5/14/2023 PST
- __Rewrite started__

## 5/16/2023 PST
- Fixed all existing bugs
- Server Manager Beta is online and fully functioning

## 5/17/2023 PST
- Rewrote configurations system to make it more simple
- Added customizable embeds with an embed builder for servers to customize embed responses (e.g. ban dm, giveaway embed, etc.)
- Update embed builder/handler

## 5/18/2023 PST
- 90% complete with new configurations system

## 5/21/2023 PST
- Fully completed new configurations system
- Opened Beta program to everyone (https://servermanagerbot.ml/beta-program)
- Beefed up embed builder to support basic placeholders for building embeds to use in other systems
- Rewrote premium system to support slots for premium servers, beta access slots, and custom branded bot slots
- Started to rewrite moderation responses and behavior

## 5/23/2023 PST
- Fixed bugs in the embed builder
- Rewrote ban, warn, kick, and mute commands to support embed responses and user DMs
- Rewrote the commands above to support placeholders/variables

## 5/24/2023 PST
- Fix bugs in the embed builder
- Finish `/config show` command to show all configs, their current value, and help info

## 5/26/2023 PST
- Add `suggestions.embed` configuration to allow customization of the embed template used when suggesting something
- Fix more embed builder bugs

## 5/27/2023 PST
- Rewrote suggestion marking
- **BREAKING:** Changed `/suggestions ...` group to `/suggestion ...`
