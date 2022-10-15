---
label: Backup
icon: database
align: left
authors:
  - name: mrcrypticx
    link: https://twitter.com/mrcrypticxdev
    avatar: https://cdn.discordapp.com/avatars/503215722407657478/bae8263de249352f344bf5421734ab45.webp?size=1024
---

# Backup Commands

!!! :zap: Let's get started! :zap:
It is recommended to use our slash commands for better experience. Message commands doesn't have every property we support on slash commands. You can use the `;` prefix or `/` to the various commands.
!!!

### [!badge variant="primary" text="backup create"]

# Syntax

Syntax (example)  | Type
---    | ---
;backup create ?n Croc's World ?c crocodile | Message Command
/backup create name:Croc's World custom-id:crocodile | Slash Command

![](https://im-an.explorer.workers.dev/mXnBxlc.png)

![](https://im-an.explorer.workers.dev/NSSW8P9.png)

## Properties
*Use `?` as a prefix to all message commands params below.*
<!-- - c - **customId** - A phrase to easily remember your backup.
- n - **Backup Name** - An optional name for your backup. -->

Parameter   | Output | Type
---    | --- | ---
[!badge variant="success" text="?c"] |  A phrase to easily remember your backup. | Message Command
[!badge variant="success" text="?n"]  | An optional name for your backup. | Message Command
[!badge variant="primary" text="name"]  | An optional name for your backup. | Slash Command
[!badge variant="primary" text="custom-id"] | A phrase to easily remember your backup. | Slash Command

### Permissions
- `Administrator` - Required to create a backup. This is by default.  ![](https://im-an.explorer.workers.dev/FQl06rX.png)


To disable the privilege to admins creating backups, you can run `;config edit owneronly true`. This will only allow the owner of the guidl to create backups and other create methods. ![](https://im-an.explorer.workers.dev/Nq5YO5n.png)